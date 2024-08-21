# electricity_zero_down_time_part1 : Stabilizer in critic environnement
Inspired of this project [project_udr](https://tahmidmc.blogspot.com/2014/02/automatic-voltage-stabilizer-ac-ac-with.html) or [local_document](https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_part1/blob/main/ORIGINAL_INSPIRATION.rar) with this all links : </br>
[link1](http://www.youtube.com/watch?v=C84hwaacdfo) </br>
[link2](http://www.youtube.com/watch?v=Ds7M1bBSyEU) </br>
[link3](http://tahmidmc.blogspot.com/2014/02/automatic-voltage-stabilizer-ac-ac-with.html) </br>

I will make reverse engineering to know the circuit of relay, of the input and of the visual </br> and i will use arduino nano to patch the problem of udr </br>

# Choose of hardware
* I use haifa udr due to this voltage critic 80V and 260V, the main problem of haifa is the bad impact of high precision ! </br>
no big delay for having more precision, so a quick trigger < 5ms gives me a noisy really bad for the circuit and make the visual to the unusual mode
* I use also haifa because it's circuit is not mounted surface (so more easy for hardware patched)
* Haifa udr use also auto-transformer
  
# Patching hardware
* No diode protection for each relay
* Connecting all pin (follow document in word : HAIFA_UDR_IN_WORD) 

# Make a test 
1.	You could verify all schematic by verifying interconnectivity without having current on the input. </br>
2.	You code verify lcd by using the code at stabilizer_lcd and stabilizer_scan_address for having address of i2c </br>
3.	You could verify all relay by changing one by one the value of relay_test with to 2 until 9 to test the command of relay0 until relay7 </br>
 Notices : haifa with 8 relays : CR7 = D2, CR5 = D3, CR6= D4, CR4= D5, CR3= D6, CR2= D7, CR1 = D8 , CR0 = D9 with value of 2 until 9 </br>
4.	Calibration : You could use stabilizer_test_input to test input and make calibration of input. </br>
After launching and seeing the port com the value printed and measure the output value . </br> Make a ration and use this as Kc. </br> For mine : value printed is 128 and value measured is 148. </br> So,The ration is near 0.846.
5.	Test the tapping using ohm_meter between inputtap and outputtap (no resistance if it’s directly connected, with resistance if not) </br>
All test code is : </br>
*	stabilizer_tapping_test_94_231
*	stabilizer_tapping_test_109_215
*	stabilizer_tapping_test_109_231
*	stabilizer_tapping_test_127_215
*	stabilizer_tapping_test_148_215
*	stabilizer_tapping_test_171_215
*	stabilizer_tapping_test_199_215
*	stabilizer_tapping_test_231_231
*	stabilizer_tapping_test_231_215
6.	Test the code stabilizer_haifav3 </br>
