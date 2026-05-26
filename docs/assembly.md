# Assembly Guide

## PCB

### Back Side Components

* Resistors R11 and R25
* U1 socket
* *Do not place capacitors C15 and C16 yet.*

### Front Side Components

* **Sockets and Capacitors**
    * Resistor R12
    * U4 socket
    * Ceramic capacitors C1-C10, C13-C14
* **Power**
    * Diodes D2 and D3
    * Resistors R22 and R23 (or ferite beads)
* **Discretes**
    * Diode D1 
    * Transistors Q1 and Q2
    * Trim pot RV3
    * *Do not place LEDs D4 and D5 yet.*
* **Resistors**
    * R16-R20, R24, R26
    * R1-R10, R14, R15, R21
    * *Do not place R13 yet.*
* **Vactrols**
    * Vactrols U2 and U3
    * Back side ceramic capacitors C15 and C16
    * Front side resistor R13
* **Connections and Controls**
    * Audio jacks J1-J4
    * Control pots RV1, RV2, RV4-RV6 (*note RV4 value*)
    * Switches SW1 and SW2

Mount the LED once the faceplate is in place.

## Calibration and Test

To calibrate, 

* set the toggle switch to "normal" 
* set the offset to max
* set the mode switch to VCF
* set the resonance to a minimum
* apply a higher pitch sound to the audio input (or a swept pitch)
* adjust RV3 to ensure that the high pitch is not too attenuated

If the adjustment of RV3 doesn't have any impact in this setup, it's OK to leave it centred: the offest control will usually have enough range to saturate the LEDs in the optocouplers. See the section [Driving the Vactrols](./theory.md) for more details. 

# BOM

[Download (.csv)](assets/bom.csv)

{%include-markdown "assets/bom.md"%}



