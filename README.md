# 🏛️ 3D Modeling and Printing of the Roman Colosseum

This project involves the complete workflow of designing, optimizing, and 3D printing a miniaturized model of the Roman Colosseum using Autodesk Fusion 360 and Ultimaker Cura.

---

## 📐 Overview

A historically inspired, scaled-down 3D CAD model of the Colosseum was created with precision using **Autodesk Fusion 360**. The model was then processed for 3D printing and fabricated using the **Fablab’s Ultimaker 3D printer**.

---

## 🛠 Tools & Software Used

| Tool              | Purpose                             |
|-------------------|-------------------------------------|
| Autodesk Fusion 360 | 3D CAD modeling and STL export     |
| Ultimaker Cura     | G-code generation and print optimization |
| Ultimaker 3D Printer (Fablab) | Final model fabrication      |

---

## 📂 Project Workflow

### 1. CAD Modeling
- Designed the Colosseum’s structure in **Fusion 360** using reference images.
- Incorporated architectural details like arches, outer walls, and tiered seating.
- Ensured proper **scaling and tolerances** for printability.

### 2. STL Export
- Exported the finalized design as an `.stl` file from Fusion 360.

### 3. Print Preparation (Ultimaker Cura)
- Imported `.stl` into **Ultimaker Cura**.
- Configured slicing settings:
  - **Layer height:** 0.2 mm
  - **Infill density:** 10%
  - **Supports:** Enabled where necessary
- Resized and oriented model to minimize print time and improve stability.
- Exported the sliced file as `.gcode`.

### 4. 3D Printing
- Printed the model using the **Ultimaker 3D printer** in the **campus Fab Lab**.
- Material used: PLA
- Total print time: 8 hours

---

## 🧠 Learnings & Skills Demonstrated

- Proficiency in **parametric modeling** with Autodesk Fusion 360
- Understanding of **3D print constraints and optimization techniques**
- Experience with **slicing software (Ultimaker Cura)**
- Practical knowledge of **FDM 3D printing** workflow
- Architectural translation of historical structures into digital models

---

## 📎 Files

| File Name            | Description                       |
|----------------------|-----------------------------------|
| `Colosseum CAD.jpg`| Image of CAD model |
| `Colosseum Projections.png`| Isometric and Orthographic Projections |
| `Colosseum.f3d`| F3D file of Colosseum |
| `Colosseum.gcode`| Gcode file of Colosseum |
| `Colosseum Model.jpg`| Image of 3D Printed Colosseum |
---

## 📌 Future Improvements

- Add finer details like inner seating and underground structures
- Multi-part printing for higher resolution and scale
- Post-processing: sanding, painting, or assembly

---
