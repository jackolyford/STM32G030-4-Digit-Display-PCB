# STM32G030 4-Digit Display - Design, Manufacture with JLCPCB, SMD Assembly, Embedded Firmware

I wanted to get some more practice in the development of custom PCBs from start to finish as well as a bit of embedded programming, so I decided to put together a simple project that will include all of these. This project outlines the design process of an STM32g030 based 4-digit display. The design itself was kept as simple as possible to avoid reiterations as this was simply for practice. It follows the PCB design process, manufacturing, assembly and finally programming. This was my first experience with using smd components and am excited to continue using them in future projects.

## Board Design in KiCad

The board consists of only a few components: An STM32g030, a MIC5504 3.3v regulator, an LTC-4627 4-digit 7-seg display, a USB-C port, a few 0.1uF filter capacitors and finally 220ohm resistors for the segment LEDs. All capacitors and resistors used were of imperial 0603 size with the only through hole component being the display.
![PCB in KiCad](/Images/PCBKiCad.png)

## Getting the Boards Manufactured

After running design rule checks, verifying all the footprints matched the physical components (comparing to datasheet and ordered package options) and checked over everything to make sure nothing major was missed (nearly forgot a programming header), the gerber files were exported and uploaded to JLCPCB. All settings were kept standard and a stencil was also ordered.

![The boards](/Images/board2.jpg)

## Assembly
### 




## Improvements
