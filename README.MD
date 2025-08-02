# DIY Attiny Arduino Keychain Game Console

This repo features the Schematic file, Gerber files and Bill Of material. Feel free to use the files and modify them as you wish.


### YOUTUBE VIDEO CLICK ON PICTURE
[![Attiny_Arcade](https://github.com/ArmourGrade/Attiny85-Arduino-Game-Console/blob/main/Images/IMG1.jpg?raw=true)](https://www.youtube.com/watch?v=D4EZ1D5AoRs&t=7s)

Please note that if you plan on using these gerber files you should flip the coin battery holder during assembly in comparisson to the outline drawn on the PCB for easier replacement of the battery due to close proximity with the switch pins. (Like in the picture bellow)
No additional changes need to be made for this, since the polarity is the same of both left and right pins.
I will upload a second version where this visual error is fixed. 
And before soldering the Battery holder you should put a little solder on the PAD thats represents the other polarity of the Battery. This is so that the battery will have better conntact with the Pad.



The firmware used in the project is from: https://github.com/andyhighnumber/Attiny-Arduino-Games
[![Attiny_Arcade_fix](https://github.com/ArmourGrade/Attiny85-Arduino-Game-Console/blob/main/Images/Position%20of%20the%20Battery%20holder.jpg?raw=true)]

## Bill of Materials
1. SSD1306 OLED with I2C
2. Attiny85_20PU
3. DIP8P socket 
4. 2x Kailh choch v1 switches and keycaps
5. 2x 10k through-hole resistors
6. SN74LVC2G04DBVR
7. CPT-1203-78-SMT-TR (buzzer speaker)
8. EG1213 (switch)
9. Keystone Electronics 3003 (Battery Holder)
