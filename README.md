# Arduino-Based-Gas-Leak-Alert-System
This project demonstrates a gas leakage detection system that uses an Arduino UNO R3 along with a gas sensor, LEDs, a buzzer, and an LCD display to detect and alert about gas leaks. 
It's perfect for making fire alarms, gas leak detectors, or home safety systems! 

# Components required
<ul>
<li>
  
**ARDUINO UNO R3** :-The core microcontroller board.
</li>
</ul>
<ul>
<li>
  
**LCD display 16 x 2** :- To show sensor values and status messages.
</li>
</ul>
<ul>
<li>
  
**Breadboard** :- For connecting the components.
</li>
</ul>
  <ul>
<li>
  
**Gas Sensor** :-To sense LPG, smoke, or other combustible gases.
</li>
</ul>
  <ul>
<li>
  
**Piezo Speaker** :-Provides an audible alarm when gas is detected.
</li>
</ul>
  <ul>
<li>
  
**LED light** :- Indicates gas leakage (RED) , Indicates the normal (safe) state(GREEN) .
Resistor

</li>
</ul>

# Components Images 
![Screenshot 2025-05-13 002248](https://github.com/user-attachments/assets/895b4eab-3ffd-4e6f-a5fb-dfa81e4a3b2b)

# Working of the system
<ul>
<li>
Firstly,  when the system is turned ON the green LED light is also turned ON stating the environment/room is safe right now. 
</li>
</ul>
<ul>
<li>
An “ALL SAFE !! ALL CLEAR !!” message is displayed on the LCD display of the device.
</li>
</ul>
<ul>
<li>
Then whenever the Gas Sensor MQ- 2 in this device detects a gas leaks or other emissions that can interface with a control systems the Green LED light turns OFF and a red LED light is turned ON. 
</li>
</ul>
<ul>
<li>
As soon as this happens , the Piezo Speaker starts to buzz with a high tone beep and a message on the LCD is displayed  “ALERT !!! EVACUATE ASAP ! ”
</li>
</ul>







