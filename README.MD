# DIY Attiny Arduino Keychain Game Console

This repo features the Schematic file, Gerber files and Bill Of material. Feel free to use the files and modify them as you wish.


### YOUTUBE VIDEO CLICK ON PICTURE
[![Attiny_Arcade](https://github.com/ArmourGrade/Attiny85-Arduino-Game-Console/blob/main/Images/IMG1.jpg?raw=true)](https://www.youtube.com/watch?v=D4EZ1D5AoRs&t=7s)

Please note that if you plan on using these gerber (Version 1 of files) files you should flip the coin battery holder during assembly in comparisson to the outline drawn on the PCB for easier replacement of the battery due to close proximity with the switch pins. (Like in the picture bellow)
No additional changes need to be made for this, since the polarity is the same of both left and right pins. (This can be seen in the video)

### Version 1.1 of gerbers (Minor Updates)(Not tested but should work)
I have uploaded a new version of the Gerber files where the footprint is already flipped, This version also features some minor changes.
Through hole resistors changed for SMD.
Added decoupling capacitors to the Micro and Buzzer Driver IC.
PAD sizes increased.

Before soldering the Battery holder you should put a little solder on the PAD thats represents the other polarity of the Battery, as shown in the video. This is so that the battery will have better conntact with the Pad.



The firmware used in the project is from: https://github.com/andyhighnumber/Attiny-Arduino-Games
![Attiny_Arcade_fix](https://github.com/ArmourGrade/Attiny85-Arduino-Game-Console/blob/main/Images/Position%20of%20the%20Battery%20holder.jpg?raw=true)

## Bill of Materials
1. SSD1306 OLED with I2C
2. Attiny85_20PU
3. DIP8P socket 
4. 2x Kailh choch v1 switches and keycaps
5. 2x 10k through-hole resistors (for version 1.1 I used 1206 SMD resistors also 10kOhm)
6. SN74LVC2G04DBVR
7. CPT-1203-78-SMT-TR (buzzer speaker)
8. EG1213 (switch)
9. Keystone Electronics 3003 (Battery Holder)
10. (Version 1.1) 2x 0805 100nF capacitors X7R
