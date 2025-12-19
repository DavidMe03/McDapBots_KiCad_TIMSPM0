# McDap Bots Pedagogical Robot

This project was created as a capstone project for the University of Virginia Department of Electrical and Computer Engineering. Our goal was to create a small robot which could be programmed by students, for use as a teaching aide in an embedded systems course. This repository contains the hardware files specific to the robot's main board.

**Authors**
- Colby Wise
- Pratik Pandit
- Austen Yun 
- David Merino
- Marc Rosenthal

**Advisors**: Todd DeLong and Adam Barnes 

**Features at a glance**
- 2 motors (PWM controlled), OLED screen (I2C), reflectance sensor (I2C), bump switches (GPIO), Bluetooth (UART), and infrared sensors (ADC)
- battery charging port and battery voltage display (press button to enable)
- support for TI and STM microcontrollers

## What is contained here

**Project Symbols/Footprints**

Symbols that are specific to this project such as the robot chassis. 

**Schematic File**

KiCad schematic file that shows the electrical connections of each component of the robot. 

**Layout File**

KiCad layout file that shows how the components are placed and routed on the PCB. 

**Bill of Materials Files**

BOM.xlsx contains a list of all the parts needed for the PCB.

Digikey_Parts_List.xlsx can be uploaded to Digikey to select the parts needed for one copy of this board.

## How to use this repository
1. Copy the repository locally to your computer
2. Using KiCad 8.0 (or higher version) open the file `MotorBoardv3_2.kicad_pro`
3. Generate necessary gerber files and order components
4. Follow the provided construction guide to build the robot
