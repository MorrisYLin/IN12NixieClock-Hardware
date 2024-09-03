# IN-12A Nixie Clock Project
## Overview
This PCB contains driver circuitry to handle high-voltage nixie tubes, which allows for binary-coded decimal to select the lit digit and independent PWM dimming for each tube. It also handles power conversion from a 12V 2A wall adapter to 170V, 5V, and 3.3V rails for the nixie tubes, development board, and ICs respectively, and accomodates connections to an ESP8266 WiFi module and an EK-TM4C1294XL development board from TI. These were chosen due to their relevance in my courses, and the design may be easily adapted to smaller microcontrollers more fitting for a clock.
## Images
Final Result

![20240830_153317](https://github.com/user-attachments/assets/a0f065db-4ba7-4946-acc8-af43693be808)
Front Copper

<img width="1603" alt="FrontCu" src="https://github.com/user-attachments/assets/1e599c5b-1cdd-4fe6-a968-c47e34937ec2">
Back Copper

<img width="1624" alt="BackCu" src="https://github.com/user-attachments/assets/f28d04b0-08d4-45b7-902d-7c9d1deed9e4">
Main Schematic

<img width="1207" alt="NixieSchematic" src="https://github.com/user-attachments/assets/0897b264-2443-48e3-a10c-bc5dd1c69675">
Tube Driver Schematic

<img width="869" alt="TubeController" src="https://github.com/user-attachments/assets/247b8049-74d6-46a5-b35f-3d5e4cfe0426">
3D Render

<img width="1256" alt="3DRender" src="https://github.com/user-attachments/assets/6f9516f4-1ac0-4795-9ac7-e7079093f9b5">

## Files
All design was done through KiCAD 8.0, the `TaylorElectronics` folder includes the footprints & symbols for the TES High-voltage power supply as well as others that are not included in the KiCAD standard library. The `nixies_us` folder contains footprints and symbols for the nixie tubes, credit to [judge2005](https://github.com/judge2005/Eagle-and-KiCAD-Nixie-Libs/tree/master) from nixies.us.
