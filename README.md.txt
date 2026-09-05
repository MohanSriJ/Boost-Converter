# DC-DC Boost Converter PCB

A custom **DC-DC Boost Converter PCB** designed using **KiCad**. This project includes the complete schematic, PCB layout, custom component footprints, 3D models, and PCB 3D visualization.

## Project Overview

This project is a DC-DC Boost Converter based on the **XL6009** boost converter module.

The PCB was designed to provide a compact and organized implementation of the boost converter circuit with input/output filtering and adjustable output voltage.

The design also includes custom KiCad resources for the **XL6009** and **DR125-3R3-R** components, including footprints, schematic symbols, and 3D models.

## Main Components

- XL6009 DC-DC Boost Converter
- DR125-3R3-R SMD Power Inductor
- SS34 Schottky Diode
- 47 µF / 50 V Input Capacitor
- 1 µF Input/Output Capacitors
- 220 µF / 50 V Output Capacitor
- 1 kΩ Feedback Resistor
- 50 kΩ Potentiometer
- Input and Output Connectors

## Key Features

- Custom PCB designed in KiCad
- Adjustable output voltage
- Custom XL6009 footprint and symbol
- Custom DR125-3R3-R footprint and 3D model
- SMD and through-hole components
- Wide traces for power paths
- Ground copper zone
- Input and output filtering
- KiCad 3D visualization
- Front and back PCB views

## Schematic

The schematic implements the XL6009 boost converter along with the required power, filtering, diode, and feedback components.

The main sections of the circuit are:

- Input power connection
- Input filtering
- XL6009 boost converter
- Power inductor
- Schottky diode
- Output filtering
- Feedback voltage divider
- Adjustable potentiometer
- Output connection

The potentiometer is used in the feedback network to adjust the output voltage.

![Schematic](./schematic/DC-DC%20Boost%20Converter%20Schematic(1).png)

## PCB Design

The PCB layout was developed in KiCad with attention to component placement, power routing, grounding, and practical board organization.

The design includes:

- Component placement
- Power routing
- Ground copper zone
- Through vias
- SMD and through-hole footprints
- Input and output terminals
- 3D component models

The power paths are routed using wider traces to provide suitable current-carrying paths for the boost converter.

### PCB Layout

![PCB Layout](./pcb-layout/DC-DC%20Boost%20Converter%20Footprints%204(1).png)

## Custom Components

### XL6009

A custom KiCad symbol, footprint, and STEP 3D model are included for the XL6009 module.

See the [XL6009](./XL6009/) folder for the related files and documentation.

### DR125-3R3-R

A custom KiCad footprint, schematic symbol, and STEP 3D model are included for the DR125-3R3-R power inductor.

See the [DR125-3R3-R](./DR125-3R3-R/) folder for the related files and documentation.

## 3D Visualization

The KiCad 3D Viewer was used to verify component placement and visualize the assembled PCB.

The repository contains:

- PCB 3D views
- Different viewing angles
- Front-side and back-side views
- Component 3D models
- 3D visualization video

### 3D PCB View

![3D PCB View](./3D-view/DC-DC%20Boost%20Converter%20Footprints%2012.png)

### Additional 3D View

![3D PCB View](./3D-view/DC-DC%20Boost%20Converter%20Footprints%2015.png)

## Project Documentation

The project documentation and visual references are available in the following folders:

- [Schematic](./schematic/)
- [PCB Layout](./pcb-layout/)
- [3D View](./3D-view/)
- [3D View Video](./3D-view-video/)
- [XL6009 Custom Component](./XL6009/)
- [DR125-3R3-R Custom Component](./DR125-3R3-R/)

## Repository Structure

```text
DC-DC-Boost-Converter/
│
├── XL6009/
│   ├── README.md
│   ├── XL6009.kicad_sym
│   ├── DPAK170P1435X465-6N.kicad_mod
│   ├── XL6009.step
│   ├── XL6009 3D.png
│   └── how-to-import
│
├── DR125-3R3-R/
│   ├── README.md
│   ├── DR125-3R3-R.kicad_sym
│   ├── INDM1250X1250X600.kicad_mod
│   ├── DR125-3R3-R.step
│   ├── DR125 3D.png
│   └── how-to-import
│
├── schematic/
│   └── Schematic images
│
├── pcb-layout/
│   └── PCB layout images
│
├── 3D-view/
│   └── PCB 3D images
│
├── 3D-view-video/
│   └── PCB 3D visualization video
│
├── Boost Converter.kicad_pcb
├── Boost Converter.kicad_sch
├── Boost Converter.kicad_pro
├── Boost Converter.kicad_prl
└── fp-info-cache

Design Files

The repository contains the KiCad project files required to open and modify the design.

File Type	Purpose
.kicad_sch	Schematic design
.kicad_pcb	PCB layout
.kicad_pro	KiCad project file
.kicad_mod	Custom PCB footprints
.kicad_sym	Custom schematic symbols
.step	3D component models
Software
KiCad 7.x
Project Status

The schematic, PCB layout, custom footprints, 3D models, and PCB 3D visualization have been developed as part of the design process.

Author

MohanSriJ

License

This project is provided for educational and design reference purposes.