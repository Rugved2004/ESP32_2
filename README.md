# ESP32_2 - KiCad PCB Project

A custom ESP32-based PCB design created with KiCad 8.x.

## Overview

This repository contains the complete KiCad project files for an ESP32 development board. The design includes schematic capture, PCB layout, 3D models, and custom footprints/libraries.

## Project Structure

```
ESP32_2/
├── ESP32_2.kicad_pro      # Project configuration
├── ESP32_2.kicad_sch      # Schematic file
├── ESP32_2.kicad_pcb      # PCB layout file
├── ESP32_2.pdf            # PCB fabrication drawing
├── LIB/                   # Custom symbol libraries
├── Footprint/             # Custom footprint libraries
├── 3D_Modelss/            # 3D STEP models for components
├── ESP32_2-backups/       # Automatic KiCad backups
└── imgs/                  # Project images/screenshots
```

## Features

- **ESP32-WROOM-32** module integration
- Custom power management circuitry
- USB-C interface for programming and power
- GPIO breakout headers
- Custom footprint libraries for specific components
- 3D models for mechanical verification

## Getting Started

### Prerequisites

- [KiCad 8.0+](https://www.kicad.org/download/)

### Opening the Project

1. Clone this repository
2. Open `ESP32_2.kicad_pro` in KiCad
3. The schematic and PCB editors will be available

## Manufacturing

### PCB Fabrication

Gerber files can be generated from the PCB editor:
1. Open `ESP32_2.kicad_pcb`
2. File → Fabrication Outputs → Gerbers (.gbr)
3. Use the default settings for most fabs

### Bill of Materials (BOM)

Generate BOM from the schematic editor:
1. Open `ESP32_2.kicad_sch`
2. Tools → Generate Bill of Materials

## Custom Libraries

This project uses custom libraries located in:
- `LIB/` - Schematic symbols
- `Footprint/` - PCB footprints

These are referenced in the project configuration and should be available when opening the project.

## License

This project is open source. Feel free to use, modify, and distribute.

## Author

**Rugved Bhalekar**
- GitHub: [@Rugved2004](https://github.com/Rugved2004)
- Email: rugvedbhalekar2004@gmail.com