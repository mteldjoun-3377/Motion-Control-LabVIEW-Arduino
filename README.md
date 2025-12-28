# Stepper Motor Control with LabVIEW & Arduino

## Overview
Control a stepper motor using LabVIEW, Arduino Uno, and L293D Motor Driver.  
The project implements **full-step control** via LINX (VISA) for precise motion management.

## Hardware
- Arduino Uno
- L293D Motor Driver
- Stepper Motor

## Software
- LabVIEW (VI files included)
- LINX Toolkit (VISA communication)

## Usage
1. Connect Arduino to your PC via USB.  
2. Wire the stepper motor through L293D as per circuit diagram.  
3. Open the LabVIEW project (`.lvproj`) and run the VI.

## Wiring Diagram
[Wiring Diagram](Wiring_Diagram.png)

## Notes
- Make sure LINX is installed in LabVIEW.  
- Full-step mode is implemented. You can modify the VI for different stepping modes.
