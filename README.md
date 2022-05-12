# Tiki Monocoque (under construction)

![Tiki Mono 01](https://user-images.githubusercontent.com/68491566/167160708-03455499-fa1d-441f-9ffe-d1d5f2e42cbf.png)

## Introduction
Welcome to Tiki Monocoque github page. 

Since the launch of Tiki 3.2 in September 2021, I had done several updates to the design to improve the overall printability and functionality. In addition, I have been working on other projects ie the Donki direct drive extruder and had learned alot (and still learning) in terms of designing a carriage and fan mount system.  In the 2022, I set out to do several things. Learn how use Klipper (done), design and build a bare-bone printer (in progress) and do an update on the Tiki system. 

The original goal of the designing the Tiki was to have a better fanduct system for creality Ender 5. But as time pass, and buying an Orbiter V1.5, I decided to adapt the design for it. That is how Tiki3 came about. Initially my design of the main body takes inspiration from Hangtight (thingiverse) with the side mounted hotend fan and front mounting fanduct. To put things into persepctive, I did not recieve any help nor step files from him. I redesign it from ground up to improve printability, incoporated BL touch bracket, cable relief and a mount for the Orbiter. At that time, only thing that I used from his design was the fanduct because I my Fusion360 skills were not good enough. Subsequently, I design the my own 5015 fan duct from scratch. 

Following the path of Tiki3, Tiki Monocoque is designed to support the Orbiter V1.5. <b>STL files and documentations are free for you to download on this github page</b>. There is NO patreon or membership needed to get access to stl, docs or exclusive support. I will try to answer or help if I can. I may (or may not) upload the step files for the body to be adapted to other hotend, but the step files for fanduct will not be shared. If you like using the design and want to spport my work, a contribution to https://www.paypal.com/paypalme/shannonheng will be greatly apperciated. If you want to use the design for commerical/academical intend, do contact me for permission or collaborations. 

## Description
Tiki Monocoque as its namesake is a one piece printed body construction with the fanduct, BL Touch, Orbiter and ADXL345 mounted to it. This approach in design improves rigidity and dimension accuracy. The fanduct is redesigned with input from previous designs. All parts are design with intergrated supports. The fanduct is designed with overhangs of under 60 degree to the horizon. Tiki Monocoque will only work with the parts it is design with. It is lighter that its predecessor, use less material/screws and less parts to print.

Tiki Monocoque is designed for Creality Ender and CR machines, namely
- Ender 3/3pro/3V2
- Ender 5/5pro/5plus
- CR10 (old version)
- Ender clones with same M5 and screw positions

Hotend that has been designed for:
- Creality stock CR10 hotend (tested)
- Mellow NF-Zone CR10 (tested)
- Mellow NF-Smart 
- MicroSwiss All Metal and clones

##Information
- This carriage/fanduct system uses M3 screws and M3 (4.6D3L) brass inserts. I will NOT be designing M3 self-tapping version. 
- You can reuse the 4010 coaxial fan.
- A 5015 radial fan is required to replace the stock 4010 radial fan. 
- Please see the other files for print orientation and BOM of screws and nuts required. 

## FAQs

Q: Is there any major design changes between this version (Tiki Monocoque) and the previous versions that are uploaded on Thingiverse?

A: Yes, there are lot of changes. Tiki Monocoque is not compatiable with parts from previous versions. 

Q:Will there be a design for V6 /Dragon hotend?

A: Nope.

Q: Would you be able to include a one off custom design for probe bracket/fan duct for other fans etc?

A: Nope.

Q: Will this system fit the Sovol/Tronxy/TwoTrees etc etc?

A: Maybe. You have to print and test as I do not have those printers. 

Q: Would you release the STEP file for others to remix your design?

A: STEP files for the body and bracket will be release in the later date. STEP files for the fanduct will not be released. 

Q: Did you test print it in PLA? How did you get even get such specific numbers? "...I find stuff like this very misleading with serious potential to cause damage to printers when people try to do it..." 

A: I try my best to answer questions pertaining to the design. Constructive suggestions and contributions to the design are greatly apperciated. Be polite and have manners in your questions. Patronizing or rude statment will be deleted. 

Q: How accurate is the CFD simulation on your fan duct? Did u consider turbulance of of the 5015? Did u take into account of hotend movement? etc etc.

A: My basic CFD simulation of the particles movement (air) is to provide a validation that the air is directed under the nozzle when designing the fan duct. There are many other parameters that I would not know. tbh, it's a fanduct for 3D printer, not a cooling system of a nuclear plant. 

Q: Why it is called Tiki

A: Tiki was the name of our family dog. He passed away several years ago and we still miss him dearly. So I named this system after him. 
