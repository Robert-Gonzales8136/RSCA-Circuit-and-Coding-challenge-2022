# RSCA-Circuit-and-Coding-challenge-2022
My submission for CSULB's week of RSCA circuit and coding challenge in 2022. The challenge was space themed and to be done on Tinkercad with an Arduino Uno emulation in an hour and 45 minutes. I won second place. My submission was missing the proximity warnings in the serial monitor because I ran out of time, but it was a bonus challenge for extra points. This version has all the necessary challenges and bonus point challenges except for the LCD display. I have the code as a .txt so it can be easily copied and pasted to Tinkercad or your favorite text editor. 

The program reads and displays temperature in celcius and distance in inches in the serial moitor. Proximity lights, the serial monitor, and the buzzer react based on distance. When a large enough shadow is cast, the the "engine" red LED will light.

Pin	Function
2	Green Anode on RGB LED
3	Blue Anode on RGB LED
4	Red Anode on RGB LED
5	Piezo Buzzer
11	Ultrasonic Trig
12	Ultrasonic Echo
13	Red LED representing engine
A0	TMP36
A1	Photoresistor

Note: The photoresistor is in a voltage divider with a 10K Ohm pull-down resistor. A photodiode was recommended, but I was more comfortable with this.
      The ultrasonic distance sensor wouldn't work in space, so it would instead be a laser distance sensor and the constant would be based on the speed of light
      
