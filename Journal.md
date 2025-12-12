# Journal

## Working on modularity

### 2025-12-12 - 1.0 hour
I added a laser module to the machine. Swapping between the milling head and the laser head is really easy:

1. Remove the four mounting screws.
2. Take off the spindle and the 3D-printed front cover.
3. Place the laser module in position and secure it using the four screw holes.
4. Install the 3D-printed cover.

And just like that, the machine is ready for engraving.

---

## Controlling Grbl_ESP32

### 2025-12-12 - 2.0 hours
I’ll be controlling the CNC through Universal G-Code Sender. The whole setup will be accessible through a Web-UART interface, so I can run it directly from a browser without needing a dedicated PC.

---

## PSU case

### 2025-12-12 - 8.0 hours
Render of both the CNC and PSU

This looks fire.

**The Case**
Made a 3D-printed power supply case in Fusion 360 and mounted it on the CNC. It actually came out looking really good. I dropped the STL into the repo under the 3D-printable folder so it’s all organized.

---

## Some change

### 2025-12-11 - 3.0 hours

### PCB

Cleaned up the layout and added proper mounting holes so the board can be fixed down. Added some arts (M4 and blueprint logo).

### Repo

Made a KiCad folder and added the Gerber files. Tweaked the CAD folder too (screws, brackets and lead screw nut). Also added a new PCB section in the README.md so everything looks nicer. Added a whole render folder in the repo. Researched a PSU since I forgot about it then added it to the BoM.

---

## Firmware

### 2025-12-11 - 3.0 hours
The CNC is going to run Grbl_ESP32 firmware. I added it in the repo, added pin configuration (pins_scdc.h) in the firmware folder, and added the Gerber of the CNC shield from KiCad.

---

## Fixed the repo

### 2025-12-11 - 5.0 hours

### Logo

Made a logo using Canva and enlarged the BoM, then added the price in dollar and MAD. Made a name for this project and updated the CAD file (SCD-CNC which stands for Super Cool Desktop CNC).

---

## Some change to the shield

### 2025-12-11 - 6.0 hours
Added proper 2-pin connectors for adjusting micro-stepping, then made two socket pins for the limit switch mod. Also added a screw terminal for the big emergency stop button so it can cut the 24V line instantly. Makes the CNC safer and way less sketchy.

---

## Made the CNC shield 1

### 2025-12-11 - 3.0 hours
I researched the available drivers and chose the DRV8825 because it handles higher current and offers finer microstepping. I finished the schematic, then routed the PCB. It took me three attempts, but I eventually settled on this design. I’ll probably upgrade or even change it since I’m not a big fan of the layout nor the screw terminal. This took so much time; I know it’s simple but I’m not that good in electrical engineering.

---

## Finishing touches

### 2025-12-10 - 9.0 hours
Made some final changes to the design (fillets, etc.) and changed the README.md. Now I can hop onto the next task: making the PCB.

---

## Changed the layout

### 2025-12-09 - 2.5 hours
I shortened the frame to save money and reinforced the Y-axis extrusion with a 20mm plate. Since I changed the whole layout, the dimensions are now 469 × 400 mm.

---

## Made the BoM and repo

### 2025-12-09 - 12.0 hours
Created a repo for this project, added a README.md, the CAD files (with full assembly), and the Bill of Materials. Next task is probably making the electronics.

---

## Whole remake

### 2025-12-08 - 2.0 hours
I didn’t like it because it was too small, so I stayed up all night making this CNC router that’s now modular — just swap the head. It’s better, bigger, and yellow, which is also cool. I’ll make a BoM and a repo.

---

## Finished the design

### 2025-12-08 - 1.2 hours
After two hours I finally finished making this CNC milling machine. I’m exhausted and I need to recheck the stepper motors and their supports. Tomorrow I’ll try to make the controller, the GitHub repo, and the BoM.

---

## Y axis

### 2025-12-08 - 0.4 hours
Finished designing the platform for the Z-axis, now moving on to modeling the Y-axis for the CNC mill/plotter project. This is where I will make it modular.

---

## Z axis

### 2025-12-08 - 0.4 hours
Made the Z-axis structure using the same components. Next goal is to make the Z platform where the Y-axis and the spindle/module will be mounted.

---

## Finished the platform

### 2025-12-08 - 1.0 hour
Finally added the platform. Everything is going well for now. Hopefully I’ll design the Y-axis in the next hour, but I still need 3D models of some components like the spindle and the extrusion.

---

## Added the X movement

### 2025-12-08 - 3.0 hours
Designed 3D-printed shaft-support brackets to hold the two guide rods for the X-axis. They keep the rods aligned, and I’ll add the platform next.

---

## Making the base

### 2025-12-08 - 2.0 hours
Started by designing the base of the CNC mill/plotter in Fusion 360 using 20×20 T-slot aluminum extrusion. The frame measures about 239.5 × 200 mm, and I added 3D-printed brackets to hold everything firmly in place.
