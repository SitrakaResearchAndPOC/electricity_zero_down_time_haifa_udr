# electricity_zero_down_time_part1 : Stabilizer in critic environnement
Inspired of this project [project_udr](https://tahmidmc.blogspot.com/2014/02/automatic-voltage-stabilizer-ac-ac-with.html) </br>
I will make reverse engineering to know the circuit of relay, of the input and of the visual and i will use arduino nano to patch the problem of udr </br>

# Choose of hardware
* I use haifa udr due to this voltage critic 80V and 260V, the main problem of haifa is the problem due to precision ! </br>
no big delay for having more precision, so a quick trigger < 5ms gives me a noisy really bad for the circuit and make the visual to the unusual mode
* I use also haifa because it's circuit is not mounted surface (so more easy for hardware patched)
* Haifa udr use also auto-transformer
  
# Patching hardware
* No diode protection for each relay
* Connecting all pin (follow document in word : HAIFA_UDR_IN_WORD) 
* 
