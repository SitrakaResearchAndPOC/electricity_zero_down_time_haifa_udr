# PATCHED WITH RELAYS : 
# I - HAIFA DOCUMENTATION
[haifa_documentation](https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/HAIFA_DOCUMENTATION/All_haifa_documentation.pdf)

# II - INTERSTING KNOWLEDGE WITH HAIFA UDR
* Voltage range : [INPUT : 80V -> 260V ; OUTPUT : 220V]

* Power :
<img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/DOCUMENTATION_INTERESTING_1.jpg"  alt="Image of documentation 1">

* Curve of minimal power :
<img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/DOCUMENTATION_INTERESTING_2.jpg"  alt="Image of documentation 2">
eg : for 2000va = 2000 * 0.7 W = 1400W  </br>
At 130v, 50% of power ... so at 210v, it's support 1000va = 1000 * 0,7 w = 700W , current will be near : = 700W/130V = 5,3846A </br>
At 80v, the power maximal power supported is : = 5,3846 * 80 V = 430 w  </br>
 
# III - ARDUINO IC CIRCUIT CONNECTION (PCB DOWN VIEW)
It's easy to follow the inteconnection with down view
<table>
    <tr>
        <td>
            <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/ARDUINO_INTERCONNECTION_1.jpg"  alt="Image of arduino connection 1">
        </td>
        <td>
            <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/ARDUINO_INTERCONNECTION_2.jpg"  alt="Image of arduino connection 2">
        </td>
    </tr>
</table>

# IV - ARDUINO IC CIRCUIT CONNECTION (PCB TOP VIEW)
<img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/ARDUINO_INTECONNECTION_TOP_VIEW.jpg"  alt="Image des pins extra transformateur avec notation">

# V - RELAY CONNECTION
* Schematic :
When command relay is HIGH -> MIDLE AND DOWN IS CONNECTED ON THE RELAY </br>
When command relay is LOW  -> MIDLE AND UP IS CONNECTED ON THE RELAY </br>

[relay_connetion_pdf](https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/RELAY_INTECONNECTION.pdf)


<table>
    <tr>
        <td>
            <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/RELAY_INTERCONNECTION_1.JPG" alt="Image des pins extra transformateur">
        </td>
    </tr>
    <tr>
        <td>
            <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/RELAY_INTERCONNECTION_2.jpg" alt="Image des pins extra transformateur avec notation">
        </td>
    </tr>
</table>

* Relay interconnection with all name
[schematic_with_all_notation](https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/RELAY_INTECONNECTION_ALL_NAME.pdf)
<img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/RELAY_INTECONNECTION_ALL_NAME.jpg"  alt="Image of relay interconnection with all name">

Equivalence between name's relay : R begin by zero and K begin by one  </br>
R0 is K1 </br>
R1 is K2 </br>
R2 is K3 </br>
...
Equivalence between name's command relay : CR begin by zero and IN begin by one </br>
CR0 is IN1 </br>
CR1 is IN2 </br>
CR2 is IN3 </br>
...

* Explanation by lookuptable
Full complete guide of lookuptable in excel </br>
[lookuptable_excel](https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/LOOKUPTABLE_HAIFA.xlsx)

* Resume lookuptable

[lookuptable_pdf](https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/LOOKUPTABLE_HAIFA.pdf)


</br>
<img src="https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/LOOKUPTABLE_HAIFA.jpg"  alt="Image of lookuptable resumme">
R1 : is to connect or not with voltage in of relay or 215 in of relay </br>
R2 : is to connect or not with voltage out of relay </br>
R3 - R7 : could be high for activation or low for no activation </br>
IN_TAP : is interconnection with the intap of transformers  </br>
OUT_TAP : is interconnection with the intap of transformers  </br>
DIFF : is the differenciation between OUT_TAP and IN_TAP  </br>
DEV : is the differenciation between 220V minus DIFF  </br>
Tensions : is approximation interval for having near 220V at the output  </br>
version8 : state choosen by the version 8 program </br>
The last coulumn is the approximate VOLTAGE_TRANSITION_STATE (for each), it will be experimented at the INTEGRATION TEST OF CODE </br>



# VI - ARDUINO + RELAY CONNECTION
* Schematic
<img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/ARDUINO_RELAY.jpg"  alt="Image of arduino with relay">

* verify all relay

* verify in one by one the relay
 choose one by one the relay to be tested



* verify relay state
 

# VII - ARDUINO + SENSOR VOLTAGE (ZMPT101B)
Calibrate the sensor when the voltage is near of 220V </br>
Do calibration for involtage and outvoltage </br>

# VIII - ARDUINO + LCD OLED OR LCDx1602
* LCDx1602

* LCD OLED

# IV - INTEGRATION CODE


# X - PIN TO KNOW
* PIN OF EXTRA TRANSFORMATOR
<table>
    <tr>
        <td>
            <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/PIN_EXTRA_TRANSFO.jpg" width="200" alt="Image des pins extra transformateur">
        </td>
        <td>
            <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/PIN_EXTRA_TRANSFO_NOTATION.jpg" width="200" alt="Image des pins extra transformateur avec notation">
        </td>
    </tr>
</table>
