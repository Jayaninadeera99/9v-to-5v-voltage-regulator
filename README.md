# 9v-to-5v-voltage-regulator
9V to 5V linear voltage regulator circuit designed in Altium Designer using LM7805T, with schematic, PCB layout, and Gerber/CAM files.

# 9V to 5V Voltage Regulator (Altium Designer Project)

A simple linear voltage regulator circuit that steps down a 9V input to a 
regulated 5V output, designed using Altium Designer 13.1.

## Overview

This project converts a 9V DC input into a stable 5V DC output using the 
LM7805T linear voltage regulator. It includes reverse polarity protection 
and an LED power indicator.

## Circuit Description

- **Input**: 9V DC (via 2-pin header, P1)
- **D1 (1N4007)**: Reverse polarity protection diode
- **C2 (100pF)**: Input decoupling capacitor
- **U1 (LM7805T)**: Linear voltage regulator (INPUT / OUTPUT / GND)
- **C1 (100pF)**: Output decoupling capacitor
- **R1 (1kΩ)**: Current-limiting resistor for the LED indicator
- **D2 (LED)**: Power-on indicator
- **Output**: Regulated 5V DC (via 2-pin header, P2)

## Project Structure

- `9v to 5v.SchDoc` — Schematic diagram
- `9v to 5v.PcbDoc` — PCB layout
- `CAMtastic1.Cam` / `CAMtastic2.Cam` — CAM/Gerber output files
- `9v to 5v.PrjPcb` — Altium project file

## Tools Used

- Altium Designer 13.1
