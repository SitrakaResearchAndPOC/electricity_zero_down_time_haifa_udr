# PATCHED WITH RELAYS : 
# I - HAIFA DOCUMENTATION
[haifa_documentation](https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/HAIFA_DOCUMENTATION/All_haifa_documentation.pdf)

# II - INTERSTING KNOWLEDGE WITH HAIFA UDR
## Voltage range 

INPUT : 80V -> 260V and OUTPUT : 220V

## Power 

POWER : 500va; 1Kva; 1,5Kva; 2Kva; 3Kva; 5Kva; 10kva 

<table border="1" cellpadding="10">
  <tr>
    <td>
      <details>
        <summary>🖼️ Click for having image of available power </summary>
        <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/DOCUMENTATION_INTERESTING_1.jpg"  alt="Image of documentation 1">
  </tr>
</table>


## Curve of minimal power :
<table border="1" cellpadding="10">
  <tr>
    <td>
      <details>
        <summary>🖼️ Click for having image of minimal power on documentation </summary>
 <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/DOCUMENTATION_INTERESTING_2.jpg"  alt="Image of documentation 2">

  </tr>
</table>


eg : for stabilizer 2000va = 2000 * 0.7 W = 1400W  </br>
At 130v, 50% of power ... </br>
so at 210v, it's support 1000va = 1000 * 0,7 w = 700W , current will be near : = 700W/130V = 5,3846A </br>
At 80v, the power maximal power supported is : = 5,3846 * 80 V = 430 w  </br>
 
# III - ARDUINO IC CIRCUIT CONNECTION (PCB DOWN VIEW)
It's easy to follow the inteconnection with down view
<table border="1" cellpadding="10">
  <tr>
    <td>
      <details>
        <summary>🖼️ Click for having image of arduino connection </summary>
 <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/ARDUINO_INTERCONNECTION_1.jpg"  alt="Image of documentation 2">

  </tr>
</table>

<table border="1" cellpadding="10">
  <tr>
    <td>
      <details>
        <summary>🖼️ Click for having image of arduino connection about hardware </summary>
 <img src="https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/ARDUINO_INTERCONNECTION_2.jpg"  alt="Image of documentation 2">

  </tr>
</table>


<table border="1" cellpadding="10">
  <tr>
    <td>
      <details>
        <summary>🖼️ Click for having image of arduino connection about hardware (all in one) </summary>
 <img src="https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/ARDUINO_INTERCONNECTION_ALL.jpg"  alt="Image of documentation 2">

  </tr>
</table>

[arduino_connection](https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/ARDUINO_INTERCONNECTION_ALL.pdf)

# IV - ARDUINO IC CIRCUIT CONNECTION (PCB TOP VIEW)
<table border="1" cellpadding="10">
  <tr>
    <td>
      <details>
        <summary>🖼️ Click for having image of arduino connection top view </summary>
<img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/ARDUINO_INTECONNECTION_TOP_VIEW.jpg"  alt="Image des pins extra transformateur avec notation">

  </tr>
</table>


# V - RELAY CONNECTION
## Schematic 
When command relay is HIGH -> MIDLE AND DOWN IS CONNECTED ON THE RELAY </br>
When command relay is LOW  -> MIDLE AND UP IS CONNECTED ON THE RELAY </br>
[relay_connetion_pdf](https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/RELAY_INTECONNECTION.pdf)
<table border="1" cellpadding="10">
  <tr>
    <td>
      <details>
        <summary>🖼️ Click for having image of relay connection </summary>
        <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/RELAY_INTERCONNECTION_1.JPG" alt="Image des pins extra transformateur">

  </tr>
</table>

<table border="1" cellpadding="10">
  <tr>
    <td>
      <details>
        <summary>🖼️ Click for having image of relay connection about hardware </summary>
        <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/RELAY_INTERCONNECTION_2.jpg" alt="Image des pins extra transformateur avec notation">

  </tr>
</table>

<table border="1" cellpadding="10">
  <tr>
    <td>
      <details>
        <summary>🖼️ Click for having image of relay connection about hardware (all in one) </summary>
        <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/RELAY_INTERCONNECTION_2.jpg" alt="Image des pins extra transformateur avec notation">

  </tr>
</table>


## Relay interconnection with all name

[schematic_with_all_notation](https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/RELAY_INTECONNECTION_ALL_NAME.pdf)
</br>
<table border="1" cellpadding="10">
  <tr>
    <td>
      <details>
        <summary>🧮 click for having interconnection with all name </summary>
       <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/RELAY_INTECONNECTION_ALL_NAME.jpg"  alt="Image of relay interconnection with all name">       
<p> 
    FOR HARDWARE (NOTATION BEGINS BY ONE) </br>
    FOR SOFTWARE AKA CODING (NOTATION BEGINS BY ZERO) </br> </br>
    Equivalence between name's relay : R begin by zero and K begin by one  </br>
    R0 is K1 </br>
    R1 is K2 </br>
    R2 is K3 </br>
    ...</br>
    Equivalence between name's command relay : CR begin by zero and IN begin by one </br>
    CR0 is IN1 </br>
    CR1 is IN2 </br>
    CR2 is IN3 </br>
    ...
</p>
  </tr>
</table>
FOR HARDWARE (NOTATION BEGINS BY ONE) : Relay noted by KX and command noted by INX </br>
FOR SOFTWARE AKA CODING (NOTATION BEGINS BY ZERO) : Relady noted by RX and command noted by CRX </br> </br>


## Explanation by lookuptable

Full complete guide of lookuptable in excel </br>
[lookuptable_excel](https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/LOOKUPTABLE_HAIFA.xlsx)
 </br>
Resume lookuptable  </br>
[lookuptable_pdf](https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/LOOKUPTABLE_HAIFA.pdf)
</br>

<table border="1" cellpadding="10">
  <tr>
    <td>
      <details>
        <summary>🧮 click for having LookUpTable </summary>
       <img src="https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/LOOKUPTABLE_HAIFA.jpg"  alt="Image of lookuptable resume">
       
<p> 
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
</p>
  </tr>
</table>







# VI - ARDUINO + RELAY CONNECTION
## Schematic
<table border="1" cellpadding="10">
  <tr>
    <td>
      <details>
        <summary>🖼️ Click for having image of arduino with relay </summary>
         <img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/ARDUINO_RELAY.jpg"  alt="Image of arduino with relay">
  </tr>
</table>

## TESTING UNIT FOR ALL STATE

* stabilizer_tapping_state_all_on

<table border="1" cellpadding="10">
  <tr>
    <td>
        <details>
        <summary>📑 Click for having code : stabilizer_tapping_state_all_on.ino </summary>
        <p> Copy this code on arduino, save as the name is  stabilizer_tapping_state_all_on.ino and upload + run 
        
         /* haifa with 8 relay : CR7 = D2, CR5 = D3, CR6= D4, CR4= D5, CR3= D6, CR2= D7, CR1 = D8 , CR0 = D9 de 2 à 9 */
        void setup() {
          // put your setup code here, to run once:
          int stat=OUTPUT;
          pinMode(2, stat);
          pinMode(3, stat);
          pinMode(4, stat);
          pinMode(5, stat);
          pinMode(6, stat);
          pinMode(7, stat);
          pinMode(8, stat);
          pinMode(9, stat);
          Serial.begin(9600); 
        }

        void loop() {
          // LOW FOR ACTIVATION
          // HIGH FOR NO ACTIVATION
          // NO OUTPUT CONNECTED ON THE STABILIZER
          // ALL LED RELAY SHOULD BE ON
          int stat = LOW; // change for LOW and HIGH
          digitalWrite(2, stat);
          digitalWrite(3, stat);
          digitalWrite(4, stat);
          digitalWrite(5, stat);
          digitalWrite(6, stat);
          digitalWrite(7, stat);
          digitalWrite(8, stat);
          digitalWrite(9, stat);

          Serial.println("LED RELAY ALL ON");

          delay(200);
        }
        
  </tr>
</table>  



All led realy should be ON

* stabilizer_tapping_state_security_voltage

Copy this code on arduino, save as the name is  stabilizer_tapping_state_security_voltage.ino and upload + run

```  
/*
Programmed by Sitraka : In the hack we trust
*/

int Relay0 = 9;
int Relay1 = 8;
int Relay2 = 7;
int Relay3 = 6;
int Relay4 = 5;
int Relay6 = 4;
int Relay5 = 3;
int Relay7 = 2;

void delayMillis(unsigned long duration) {
  unsigned long previousMillis = millis();  
  while (millis() - previousMillis < duration) {
  }
}

// ALL RELAY INACTIF : HIGH
int Relay0_state = HIGH;
int Relay1_state = HIGH;
int Relay2_state = HIGH;
int Relay3_state = HIGH;
int Relay4_state = HIGH;
int Relay5_state = HIGH;
int Relay6_state = HIGH;
int Relay7_state = HIGH;


// NO OUTPUT for security of equipement
// ALL LED OF RELAY IS OFF indeed RELAY0 or K1

int normal = 0;
void stabilizer_tapping_security_voltage(){
   // Something is anormal on voltage (really high or really low) 
   normal = 0;
   // Relay0 will be inactif so becomes HIGH
   if(Relay0_state == LOW){  
      digitalWrite(Relay0,HIGH); 
      delayMillis(5);
      Relay0_state = HIGH;
   }                        
}

void setup() {
  // put your setup code here, to run once:
  pinMode(Relay0, OUTPUT);
  pinMode(Relay1, OUTPUT);
  pinMode(Relay2, OUTPUT);
  pinMode(Relay3, OUTPUT);
  pinMode(Relay4, OUTPUT);
  pinMode(Relay5, OUTPUT);
  pinMode(Relay6, OUTPUT);
  pinMode(Relay7, OUTPUT);

  pinMode(A0, INPUT);

  // initialization :   
  digitalWrite(Relay0,HIGH);      
  digitalWrite(Relay1,HIGH);
  digitalWrite(Relay2,HIGH);
  digitalWrite(Relay3,HIGH);                    
  digitalWrite(Relay4,HIGH);                    
  digitalWrite(Relay5,HIGH);
  digitalWrite(Relay6,HIGH);
  digitalWrite(Relay7,HIGH);
  
  delay(50);
  Serial.begin(9600);
}

void loop() {
  // Don't activate this part of code to avoid blinking
/*      
  if(Relay0_state == HIGH){
  digitalWrite(Relay0,LOW);
  delayMillis(5);
  Relay0_state = LOW;
  }
*/

  stabilizer_tapping_security_voltage(); 
  delay(200);
}
```  





# VII - ARDUINO + SENSOR VOLTAGE (ZMPT101B)
Calibrate the sensor when the voltage is near of 220V </br>
Do calibration for involtage and outvoltage </br>

# VIII - ARDUINO + LCD OLED OR LCDx1602
## LCDx1602

## LCD OLED

# IV - INTEGRATION CODE
[schematic_global_coding](https://github.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/blob/main/PATCHED_WITH_RELAY/GLOBAL_CODING.pdf)
<img src="https://raw.githubusercontent.com/SitrakaResearchAndPOC/electricity_zero_down_time_haifa_udr/main/PATCHED_WITH_RELAY/GLOBAL_CODING.jpg"  alt="Image of global coding">


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
