<div align="center">
  <h1>⚡ DC-DC Boost Converter PCB</h1>
  <h3>🔋 Adjustable Boost Converter Designed in KiCad</h3>
  <p><strong>A custom PCB implementation of an XL6009-based DC-DC boost converter with adjustable output voltage, custom footprints, 3D models, and complete KiCad design files.</strong></p>
</div>

---

## 🎯 Project Overview

This project is a **custom DC-DC Boost Converter PCB** designed using **KiCad**.

The design is based on the **XL6009 boost converter** and includes power filtering, feedback-based output adjustment, custom component footprints, and 3D visualization.

The repository contains the complete design workflow:

`Schematic → PCB Layout → Custom Components → 3D Visualization`

---

## 💡 Project Highlights

### 🔑 Key Capabilities

1. **⚡ XL6009 Boost Converter**

   Implements the XL6009 as the main boost conversion element.

2. **🎚️ Adjustable Output Voltage**

   A potentiometer is used in the feedback network to adjust the converter output.

3. **🔌 Input & Output Filtering**

   Capacitors are used for input and output filtering to support stable converter operation.

4. **🧩 Custom KiCad Components**

   Custom footprints, schematic symbols, and 3D models are included for selected components.

5. **🖥️ Complete PCB Design**

   Includes schematic capture, component placement, routing, copper zones, vias, and PCB visualization.

6. **🧊 3D PCB Visualization**

   KiCad's 3D Viewer is used to verify component placement and visualize the assembled board.

---

## 🧰 Main Components

| Component | Description |
|---|---|
| **XL6009** | DC-DC Boost Converter |
| **DR125-3R3-R** | SMD Power Inductor |
| **SS34** | Schottky Diode |
| **47 µF / 50 V** | Input Capacitor |
| **1 µF** | Input/Output Capacitors |
| **220 µF / 50 V** | Output Capacitor |
| **1 kΩ** | Feedback Resistor |
| **50 kΩ** | Adjustable Potentiometer |
| **Connectors** | Input and Output Connections |

---

## 📐 Schematic Design

The schematic contains the complete boost converter circuit and its supporting components.

### Main Circuit Sections

- 🔌 Input power connection
- 🧲 Power inductor
- ⚡ XL6009 boost converter
- 🔋 Schottky diode
- 🧹 Input filtering
- 🧹 Output filtering
- 🎚️ Feedback voltage adjustment
- 🔌 Output connection

### Schematic

![Schematic](./media/schematic/schematic.png)

---

## 🖥️ PCB Design

The PCB was designed as a **2-layer board** using KiCad.

The layout focuses on practical component placement, power routing, grounding, and compact organization.

### PCB Design Includes

- 🧩 SMD and through-hole components
- ⚡ Wide power traces
- 🌐 Ground copper zone
- 🔗 Through vias
- 📍 Organized component placement
- 🔌 Input and output terminals
- 🧊 3D component models

### PCB Layout

![PCB Layout](./media/pcb-layout/pcb_layout.png)

---

## 🧩 Custom Components

### ⚡ XL6009

A custom KiCad component was created for the XL6009 module.

The folder contains:

- 📐 Custom schematic symbol
- 🧩 Custom PCB footprint
- 🧊 STEP 3D model
- 🖼️ 3D reference image
- 📖 Import instructions

👉 [View XL6009 Resources](./XL6009/)

---

### 🧲 DR125-3R3-R

A custom KiCad component was created for the DR125-3R3-R power inductor.

The folder contains:

- 📐 Schematic symbol
- 🧩 Custom PCB footprint
- 🧊 STEP 3D model
- 🖼️ 3D reference image
- 📖 Import instructions

👉 [View DR125-3R3-R Resources](./DR125-3R3-R/)

---

## 🧊 3D PCB Visualization

The KiCad **3D Viewer** was used to inspect the final PCB design and verify component placement.

### 3D View

![3D PCB View](./media/3d-view/3d_view_1.png)

### Additional 3D View

![3D PCB View](./media/3d-view/3d_view_2.png)

---

## 🎥 3D Visualization Video

A 3D visualization video of the PCB is included with the project.

👉 [🎥 View 3D PCB Video](./media/video/)

---

## 📂 Project Documentation

The project is organized into separate sections for easier navigation.

- 📐 [Schematic](./media/schematic/)
- 🖥️ [PCB Layout](./media/pcb-layout/)
- 🧊 [3D View](./media/3d-view/)
- 🎥 [3D Video](./media/video/)
- ⚡ [XL6009 Custom Component](./XL6009/)
- 🧲 [DR125-3R3-R Custom Component](./DR125-3R3-R/)

---

## 🗂️ Repository Structure

```text
DC-DC-Boost-Converter/
│
├── media/
│   ├── schematic/
│   │   └── schematic.png
│   │
│   ├── pcb-layout/
│   │   └── pcb_layout.png
│   │
│   ├── 3d-view/
│   │   ├── 3d_view_1.png
│   │   └── 3d_view_2.png
│   │
│   └── video/
│       └── pcb_3d_view.mp4
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
├── Boost Converter.kicad_pcb
├── Boost Converter.kicad_sch
├── Boost Converter.kicad_pro
├── Boost Converter.kicad_prl
└── fp-info-cache
```
## 🛠️ Design Files

The repository contains the complete KiCad project files.

| File Type | Purpose |
|---|---|
| `.kicad_sch` | Schematic design |
| `.kicad_pcb` | PCB layout |
| `.kicad_pro` | KiCad project configuration |
| `.kicad_mod` | Custom PCB footprints |
| `.kicad_sym` | Custom schematic symbols |
| `.step` | 3D component models |

---

## 💻 Software & Tools

### 🖥️ PCB Design

- **KiCad 7.x**

### 📐 Design Tools

- Schematic Capture
- PCB Layout
- Custom Footprint Creation
- Custom Symbol Creation
- STEP 3D Model Integration
- KiCad 3D Viewer

---

## 🔄 Design Workflow

```text
Circuit Concept
      ↓
Schematic Design
      ↓
Component Selection
      ↓
Custom Footprint Creation
      ↓
PCB Component Placement
      ↓
Power & Signal Routing
      ↓
Ground Copper Zone
      ↓
Design Verification
      ↓
3D Model Integration
      ↓
3D PCB Visualization
      ↓
Final PCB Design
```
---

## 📊 PCB Design Overview

| Parameter | Details |
|---|---|
| **Converter Type** | DC-DC Boost Converter |
| **Main Controller** | XL6009 |
| **PCB Layers** | 2 Layer |
| **Design Software** | KiCad 7.x |
| **PCB Type** | Custom Designed PCB |
| **Output** | Adjustable |
| **3D Visualization** | KiCad 3D Viewer |
| **Custom Components** | XL6009, DR125-3R3-R |

---

## ✨ Key Features

- ⚡ XL6009-based boost converter
- 🎚️ Adjustable output voltage
- 🔋 Input and output filtering
- 🧲 Dedicated power inductor
- 🔌 Input and output connectors
- 🧩 Custom KiCad footprints
- 📐 Custom schematic symbols
- 🧊 Custom STEP 3D models
- 🌐 Ground copper zone
- ⚡ Wide power traces
- 🔗 Through vias
- 🖥️ Complete 3D PCB visualization

---

## 📈 Project Status

- ✅ Schematic designed
- ✅ PCB layout completed
- ✅ Component placement completed
- ✅ Power routing completed
- ✅ Ground copper zone added
- ✅ Custom footprints created
- ✅ Custom schematic symbols created
- ✅ 3D models integrated
- ✅ PCB 3D visualization completed
- ✅ Project files organized for GitHub

---

## 🌍 Project Purpose

This project demonstrates the complete process of developing a custom power electronics PCB using KiCad.

It can serve as a reference for learning:

- 🔧 PCB design
- ⚡ Power electronics layout
- 📐 KiCad schematic design
- 🧩 Custom footprint creation
- 🧊 3D model integration
- 🔗 PCB routing
- 📚 Hardware documentation

---

## 👨‍💻 Author

**MohanSriJ**

---

## 📜 License

This project is provided for **educational and design reference purposes**.

Feel free to explore the design files and documentation to understand the PCB development workflow.

---

<div align="center">

⚡ **Designed with KiCad** | 🔋 **Built for Power Electronics** | 🖥️ **Fully Documented**

</div>
