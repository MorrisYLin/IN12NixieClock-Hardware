# IN-12A Nixie Clock Project
## Overview
This PCB contains driver circuitry to handle high-voltage nixie tubes, which allows for binary-coded decimal to select the lit digit and independent PWM dimming for each tube. It also handles power conversion from a 12V 2A wall adapter to 170V, 5V, and 3.3V rails for the nixie tubes, development board, and ICs respectively, and accomodates connections to an ESP8266 WiFi module and an EK-TM4C1294XL development board from TI. These were chosen due to their relevance in my courses, and the design may be easily adapted to smaller microcontrollers more fitting for a clock.
## Images
![20240830_153317](https://github.com/user-attachments/assets/a0f065db-4ba7-4946-acc8-af43693be808)
## Files
All design was done through KiCAD 8.0, the `TaylorElectronics` folder includes the footprints & symbols for the TES High-voltage power supply as well as others that are not included in the KiCAD standard library. The `nixies_us` folder contains footprints and symbols for the nixie tubes, credit to [judge2005](https://github.com/judge2005/Eagle-and-KiCAD-Nixie-Libs/tree/master) from nixies.us.
