# AVR-Schachzwerg

The AVR-Schachzwerg is a dedicated chess computer based on the 8-bit microcontroller ATmega88. It is very minimalist like its siblings from the late '70s and the early '80s. Four digit 7-segment display, some buttons and a µC, that's it.

AVR-Schachzwerg was originally developed in 2008 by Andre Adrian, he named it "SHAH". In 2009 (or so) Elektor designed and distributed a PCB of this chess computer (aka "AVR-Max Schachcomputer"). But the button layout was just awful and there ware neither a voltage regulator nor connectors for power supply included. So I attempted to make a better PCB layout... 

Schematic is pretty much originally. I only lowered the resistor values for more display brightness and inserted a voltage regulator together with two connectors for power supply. It can be powered either via USB or a ordinary 8-12 VDC power supply (5.5mm / 2.1mm, plus inside).

The program is a adapted version of Micro-Max 4.8. That is a chess engine by H.G. Müller consisting of less than 2000 characters of C code. Playing strength is around 1300 Elo on the www.schachcomputer.info rating list.

EAGLE was used for creating the schematic (schachzwerg.sch) and layout (schachzwerg.brd). gerber-schachzwerg.zip contains all needed gerber files for PCB production. Bill of material is listed in schachzwerg-bom.txt. All components are designed as THT for easy assembly. It is highly recommended using a socket for the µC. __In order to prevent side effects or even damage don't feed both power supply connectors simultaneously!__

## Schematic

![Schematic](https://github.com/d3rvita/avr-schachzwerg/blob/master/schachzwerg-schematic.png)

## PCB

![PCB](https://github.com/d3rvita/avr-schachzwerg/blob/master/schachzwerg-pcb.jpg)
