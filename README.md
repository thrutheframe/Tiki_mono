# Tiki Monocoque 

![Tiki Mono 01](https://user-images.githubusercontent.com/68491566/167160708-03455499-fa1d-441f-9ffe-d1d5f2e42cbf.png)

## Introduction
Welcome to Tiki Monocoque github page. 

Since the launch of Tiki 3.2 in September 2021, I had done several updates to the design to improve the overall printability and functionality. In addition, I have been working on other projects ie the Donki direct drive extruder and had learned alot (and still learning) in terms of designing a carriage and fan mount system.  In the 2022, I set out to do several things. Learn how use Klipper (done), design and build a bare-bone printer (in progress) and do an update on the Tiki system. 

The original goal of the designing the Tiki was to have a better fanduct system for creality Ender 5. But as time pass, and buying an Orbiter V1.5, I decided to adapt the design for it. That is how Tiki3 came about. Initially my design of the main body takes inspiration from Hangtight (thingiverse) with the side mounted hotend fan and front mounting fanduct. To put things into persepctive, I did not recieve any help nor step files from anyone. I redesign it from ground up to improve printability, incoporated BL touch bracket, cable relief and a mount for the Orbiter. At that time, only thing that I used was the fanduct design because my Fusion360 skills were not good enough. Subsequently, I design the my own 5015 fan duct from scratch. 

Following the path of Tiki3, Tiki Monocoque is designed to support the Orbiter V1.5. If you like using the design and want to spport my work, a contribution to https://www.paypal.com/paypalme/shannonheng will be greatly apperciated. If you want to use the design for commerical/academical intend, do contact me for permission or collaborations. 

## Description
Tiki Monocoque as its namesake is a one piece printed body construction with the fanduct, BL Touch, Orbiter and ADXL345 mounted to it. This approach in design improves rigidity and dimension accuracy. The fanduct is re-wored with input from previous designs. All parts are design with intergrated supports. The fanduct is designed with overhangs of under 60 degree to the horizon. Tiki Monocoque will only work with the parts it is design with. It is lighter that its predecessor, use less material/screws and less parts to print. Please read the instructions below. 

Tiki Monocoque is designed for Creality Ender and CR machines, namely
- Ender 3/3pro/3V2
- Ender 5/5pro/5plus
- CR10 (old version)
- Ender clones with same M5 and screw positions

Hotend that has been designed for:
- Creality stock CR10 hotend (tested)
- Mellow NF-Zone CR10 (tested)
- Mellow NF Zone CR10 (tested)
- Mellow NF-Smart 
- MicroSwiss All Metal and clones

## Instructions
<i>The Instructions section will be updated accordingly when needed.</i>
- You need to reuse the 4010 coaxial fan to cool the hotend. A 5015 radial fan is required for the part cooling fan.
- This carriage/fanduct system uses M3 screws and M3 (4.6D3L) brass inserts. Only the 4010 fan and ADXL345 screw holes will be self tap. The rest will need the m3 brass inserts for better mountung the Orbiter V1.5, fanduct and BL bracket. I will NOT be designing M3 self-tapping version holes. 
- There are 4 printed parts:
    1. Tiki_M Body.stl or Tiki_M Body teardrop.stl
    2. Tiki_M Fanduct.stl
    3. Tiki_M BLbracket.stl
    4. Tiki_M cover.stl or Tiki_M cover 0_2mm offset.stl
- The BL touch offset is X=30 Y=0
- There are 2 versions of the body. One has the vertical holes in teardrop shape to improve circular print and lesser overhangs.
- There are 2 versions of the cover. The version with 0.2mm offset is smaller in size. If you are not sure which will fit, print both the covers. 
- Supports for the body and fanduct are intergrated into the design. The tip of the fanduct is under 60 degree overhang.
- If you are using an all-metal hotend, the Ptfe tube should be sticking out of the bracket about 11-11.5mm. If you are using the stock heatbreak where the ptfe tube touches the nozzle, use a 12-12.5mm length. see image
![ptfe length](https://user-images.githubusercontent.com/68491566/168224837-6d2557ab-7064-44c7-90d7-c7f9cd38209f.png)

- Print orientations:
![print orientation](https://user-images.githubusercontent.com/68491566/168096877-1b820ded-eabb-458e-b13a-3184a3ffc2a9.png)

## Screw BOM
- m2x4mm 2pcs : securing the adxl345 to body.
- m3x8mm 2pcs : securing Orbiter V1.5 to body
- m3x8mm 4pcs : securing BLT & blbracket to body
- m3x10mm 2 or 4pcs : securing 4010 fan to body
- m3x16mm 2pcs : securing fanduct to body
- m3x20mm 2pcs :securing hotend and body to carriage
- m4x20mm + nut 1set: securing 5015 fan to fanduct

## FAQs

Q: Is there any major design changes between this version (Tiki Monocoque) and the previous versions that are uploaded on Thingiverse?

A: Yes, there are lot of changes. Tiki Monocoque is not compatiable with parts from previous versions. 

Q:Will there be a design for V6 /Dragon hotend?

A: Not at the moment.

Q: Would you be able to include a one off custom design for probe bracket/fan duct for other fans etc?

A: Not at the moment. 

Q: Will this system fit the Sovol/Tronxy/TwoTrees etc etc?

A: Maybe. You have to print and test as I do not have those printers. 

Q: Would you release the STEP file for others to remix your design?

A: STEP files for the body and bracket will be release in the later date. STEP files for the fanduct will not be released. 

Q: Did you test print it in PLA? How did you get even get such specific numbers? "...I find stuff like this very misleading with serious potential to cause damage to printers when people try to do it..." 

A: I will try my best to answer questions pertaining to the design. Constructive suggestions and contributions to the design are greatly apperciated. Be polite and have manners in your questions. Patronizing or rude statment will be deleted. 

Q: How accurate is the CFD simulation on your fan duct? Did u consider turbulance of of the 5015? Did u take into account of hotend movement? etc etc.

A: My basic CFD simulation of the particles movement (air) is to provide a validation that the air is directed under the nozzle when designing the fan duct. There are many other parameters that I would not know. It's a fanduct for 3D printer, not a cooling system of a nuclear plant. if you do not feel confident in the design, don't use it. 

Q: Why it is called Tiki?

A: Tiki was the name of our family dog. He passed away several years ago and we still miss him dearly. So I named this system after him. 

### My 2 cents worth
STL files and documentations are free for you to download on this github page. There is NO patreon or membership needed to get access to stl, docs or exclusive support. I have always enjoyed working on Tiki for the Orbiter V1.5 and will continue to do so with no additional agenda. 3d printing is a hobby and any contribution goes to my fun-funds where I use the money on more 3d printer stuff. 

I will try to answer or help when I have the time and energy. This is because I am running other design projects concurrently. There are many fanduct systems out there, and all have it advantages and disadvantages. I try my best to improve Tiki system, and constructive suggestions are greatly appreceiated. But I do not like being patronized nor talk down to.

Credits... this is a tricky subject. While I believe it is important to give credits where its due. I do not want a situation the likes of Elon's Tesla crediting Benz for inventing the first autowagen. 
