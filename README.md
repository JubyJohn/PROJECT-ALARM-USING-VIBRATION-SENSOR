# PROJECT ALARM USING VIBRATION SENSOR


## AIM

To activate buzzer and laser sensor by the detection of vibration using vibration sensor


## COMPONENTS

1.	ESP8266 NodeMCU
2.	Vibration Sensor Module
3.	Buzzer 
4.	Laser Sensor Module
5.	USB cable
6.	Jumper Wire


## CONNECTION

### Laser Sensor Module Pin Diagram


 ![Laser_sensor](https://github.com/user-attachments/assets/91fdb772-90c3-4772-880f-d4654dfcf2e6)

<br> S  = Output     ---->  D1
<br> Middle    = power supply  ---->  3V3
<br> GND   = ground   ---->  GND

### Vibration Sensor Module Pin Diagram


![Vibration-Sensor](https://github.com/user-attachments/assets/2f19a79d-8dea-46a1-9974-a54e20e00a8b)

<br> S  = Output     ---->  D0
<br> Middle    = power supply  ---->  3V3
<br> GND   = ground   ---->  GND

### Buzzer Pin Diagram
 

![Buzzer-Pinout](https://github.com/user-attachments/assets/56d399b2-68f2-4010-b088-fed8ec4786e0)

<br> +  = Output     ---->  D2
<br> -   = ground   ---->  GND


## PROCEDURE

<br> Step 1 : Interface ESP8266 microcontroller to Arduino IDE using port.
<br> Step 2 : Interface ESP8266 microcontroller with Vibration sensor to test vibration detection
<br> Step 3 : Interface ESP8266 microcontroller with laser sensor to test laser activation
<br> Step 4 : Interface ESP8266 microcontroller with buzzer sensor to test buzzer activation
<br> Step 5 : Combine and modify uploaded programs to get desired outputs


## OUTPUT

Created an alarm system which works when vibration sensor detects vibration, buzzer and laser turned on and otherwise both turned off.
