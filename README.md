# SlimeVR Motherboard BMI 160 (UNTESTED)

This is a project to make it easier to create SlimeVR trackers. This project reduces the amount of cable management needed when making SlimeVR trackers by providing a PCB that can be made for only $2. Beginner instructions on how to buy a PCB are below. Total cost should be around $55-60 for an enhanced core set excluding the cost of cases and straps.

# Sections

 - Parts and Setup
 - PCB Files and Submission
 - STL Files and Description
 - Assembly Instructions

## Parts and Setup

These PCB's use the official SlimeVR [Components](https://docs.slimevr.dev/diy/components-guide.html) and [Tracker Schematics](https://docs.slimevr.dev/diy/tracker-schematics.html). The PCB is compatible with The BMI160 and has locations for optional Battery Sense resistors and Charge Diodes. With this PCB, you will only need wire or a JST Connector for connecting the IMU's. 

All of the parts below are linked in the SlimeVR [Components](https://docs.slimevr.dev/diy/components-guide.html) guide.
This PCB is made for use with the following parts:

 - D1 Mini(https://www.aliexpress.com/item/32631693796.html)
 - BMI 160(https://nl.aliexpress.com/item/4000052683444.html)
 - TP4056 Charging Board (any connector) (https://www.aliexpress.com/item/32930640893.html)
 - 3.7V Batteries(https://www.amazon.nl/ZYGY-1200mAh-lithium-batterij-quadrotor-drone/dp/B08KZKGLW8)
 - SS22F32 DPDT Switch (https://nl.aliexpress.com/item/1005003660190950.html
 - JST 5 pin Right Angle (For Extentions) (https://www.aliexpress.com/item/33008489410.html)
 - JST 2 pin Right Angle (For the Batteries) (https://www.aliexpress.com/item/33008489410.html)
 - (Optional) 180k ohm Battery Sense Resistor
 - (Optional) 1N5817 Charge Diodes

## Case Assembly and STL

3D printable cases for the SlimeVR Trackers are included in this repo.
For printing this it's reccomended to use supports everywhere and have 20mm with 15% infil.

The Case consists of:
- The Main Case
- The Extention Case
- Supports for the Main Case to hold up the PCB
 
## PCB Files

All PCB files are included in this repo in the KiCAD Schematic Folder. Please feel free to modify them as you see fit. KiCAD was use to create this project which is a free and opensource tool to create PCB's. 

- [SlimeVR BMI160 PCB](/Gerber/) - A Modified version of [SlimeVRMotherboard by alecjprobst](https://github.com/alecjprobst/SlimeVRMotherboard).

 <img src="https://github.com/DoctorBlobs/SlimeVR-Motherboard-BMI160/blob/Main/Images/Top.svg" width="400" height="400">

## Credit
This project is based on the work from the lovely people in the SlimeVR Discord server and this Github Repo:
https://github.com/alecjprobst/SlimeVRMotherboard (For more Info and Instructions!)

Hope this Helps someone that wants to make Slimes on the cheap! (If I have the Time and Money I'll try to make a DIY Video on how to make them!)




