<!-- 🌌 HEADER ANIMATION -->
<p align="center">
  <img src="https://github.com/user-attachments/assets/9a04e89a-animated-banner.gif" width="90%" alt="Türksat Model Satellite 2024–25 Banner"/>
</p>

<!-- ✨ TITLE -->
<h1 align="center">🛰️ Türksat Model Satellite Competition 2024–25 — PSIT Vyomnauts</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=600&size=22&pause=1000&color=00E5FF&center=true&vCenter=true&repeat=false&width=700&lines=Top+16+Internationally+in+PDR;Top+15+in+CDR+Round;Developed+by+PSIT+Vyomnauts;Innovation+Through+Engineering+and+Design" alt="Typing Animation" />
</p>

---

This repository contains the **complete structural and mechanical design details** of our **Türksat Model Satellite 2024–25**, developed for **Teknofest Turkey** by **PSIT Vyomnauts**.  
Our design integrates a **Mechanical Filtering Module** that autonomously rotates optical filters for scientific imaging tasks.

---

## 🏆 Achievements

<div align="center">

### 🥇 **Türksat Model Satellite Competition 2024–25**
<img src="https://github.com/user-attachments/assets/2455a36e-6757-4e25-aff9-c239466fb65b.jpg" alt="Türksat Competition Trophy" width="350"/>

**Rankings:**  
- 🌍 *Top 16 Internationally in PDR Round*  
- 🛰️ *Top 15 Internationally in CDR Round*  

**Competition:** Türksat Teknofest 2024–25, Model Satellite Category 1  
**Developed by:** *Team PSIT Vyomnauts (India)*

> 🏅 *Recognized for innovation, modular design, and precise mechanical integration of the filtering module.*

</div>

---

## 📸 Gallery

<div align="center">

### 🧱 Science Payload CAD Model
<img width="238" height="680" alt="image" src="https://github.com/user-attachments/assets/e0cb5862-1aa2-426f-8ce9-c1381e846569" />


---

### ⚙️ Mechanical Filtering Module
<img width="474" height="441" alt="Screenshot 2025-08-31 010939" src="https://github.com/user-attachments/assets/8cb654f8-921f-4214-ac6a-14fe2281ada8" />


---

### 🛰️ Real Manufactured Model
![WhatsApp Image 2025-11-09 at 13 38 42_2ee7a2ac](https://github.com/user-attachments/assets/e1147eb9-bc83-495f-bbf9-36060443dfb7)

---

### 🔬 Filtering Mechanism Close-Up
![WhatsApp Image 2025-11-09 at 13 38 28_5bed3052](https://github.com/user-attachments/assets/a3f586c7-8096-4bb5-bb36-c2d7a1734372)


---

### 🪂 Payload & Parachute Setup
![WhatsApp Image 2025-11-09 at 13 38 34_41582875](https://github.com/user-attachments/assets/10cdefef-0cc4-4a77-9805-dd5fcc1e5ee8)


---

### 🎬 Descent & Testing Video
<p align="center">
  <video src="https://github.com/user-attachments/assets/37bb8966-fd86-4817-8392-eb9e48444964.mp4" controls width="600"></video>
  <br>
  <em>Model Satellite Payload Descent Test</em>
</p>

</div>

---

## 🧭 Table of Contents

1. [🪂 Parachute Compartment](#-1-parachute-compartment)  
2. [🧱 Mechanical Filtering Module](#-2-mechanical-filtering-module)  
3. [⚙️ Filtering Disk Assembly](#-3-filtering-disk-assembly)  
4. [🦾 Carbon Fiber Rods](#-4-carbon-fiber-rods)  
5. [🔩 Clamps](#-5-clamps)  
6. [🧠 PCB Plate](#-6-pcb-plate)  
7. [🔋 Battery Compartment](#-7-battery-compartment)  
8. [🧱 Assembly Summary](#-8-assembly-summary)  
9. [🍀 Key Highlights](#-key-highlights)

---

## 🧩 Structural Overview

| Component | Function | Material |
|------------|-----------|-----------|
| Parachute Compartment | Houses the main parachute and attachment lines | PETG |
| Mechanical Filtering Module | Rotates filtering disks to capture filtered images | PLA+ |
| Filtering Disks | Used for selective wavelength image capture | PETG |
| Carbon Fiber Rods | Provide alignment and strength across compartments | Carbon Fiber (Ø4mm) |
| PCB Plate | Holds sensors, camera, and control boards | FR4 / PETG Mount |
| Battery Compartment | Houses power supply units and distribution board | PETG |
| Clamps | Fix compartments and modules in place | PLA+ |

---

## 🪂 1. Parachute Compartment
The **topmost section** of the satellite payload structure that secures the **main parachute**.  
It ensures smooth descent and stability during recovery.

- **Attachment:** Uses Scott’s Locked Bowline Knot for parachute linkage  
- **Function:** Enables safe recovery after mission descent  
- **Material:** PETG  
- **Connection:** Mounted on carbon fiber rods  

---

## ⚙️ 2. Mechanical Filtering Module
The **core functional module** of the Model Satellite, designed for **optical data filtering** and **camera imaging enhancement**.

- **Mechanism:** Two servo motors rotate interconnected **gear trains** that drive the **filtering disks**.  
- **Gear System:**  
  | Gear | Module | Teeth | Ratio |
  |------|---------|--------|-------|
  | 1 | 1.0 | 14 | 1:2 |
  | 2 | 1.0 | 28 |   |
  | 3 | 1.0 | 10 |   |
  | 4 | 1.0 | 40 |   |

- **Components:**  
  - 2× Servos (MG90S)  
  - 8× Interconnected Gears  
  - 2× Filtering Disks  
- **Function:** Rotates filter disks for multi-spectral image acquisition  
- **Material:** PLA+ (3D printed)  
- **Control:** Driven by servo motors controlled via microcontroller signal  

---

## 🔄 3. Filtering Disk Assembly
This assembly enables rotation and positioning of **optical filters** over the camera sensor.  
It consists of two independent disks mounted concentrically and operated by servo gear systems.

- **Purpose:** Captures filtered images across different wavelengths  
- **Drive:** Servo–gear mechanism ensures synchronized motion  
- **Material:** PETG and PLA+  

---

## 🦾 4. Carbon Fiber Rods
Provide **structural rigidity** and **alignment** throughout the payload.  
All compartments are mounted on these rods using clamp supports.

- Quantity: 4 rods  
- Diameter: 4 mm  
- Function: Load-bearing and structural support  
- Material: Carbon Fiber  

---

## 🔩 5. Clamps
Used to **secure each module** along the carbon fiber rods.  
They enable modular separation of components for quick maintenance or upgrades.

- Type: 3D printed screw-tightening clamps  
- Material: PETG / PLA+  
- Fasteners: M2 screws and nuts  

---

## 🧠 6. PCB Plate
This plate holds all **flight electronics**, including sensors, GPS, camera module, and microcontroller.

- Components: Sensors, camera, telemetry system, SD card module  
- Material: FR4 or PETG base plate  
- Function: Manages data acquisition and module control  

---

## 🔋 7. Battery Compartment
Located at the **bottom section** of the payload, it powers all modules and electronics.

- Components: Battery pack, connectors, distribution board  
- Function: Centralized power delivery  
- Material: PETG  

---

## 🧱 8. Assembly Summary
- **Material:** PETG & PLA+ (3D Printed) with Carbon Fiber reinforcement  
- **Design Software:** SolidWorks 2022 SP1.0  
- **Manufacturing Method:** FDM 3D Printing  
- **Structure:** Modular cylindrical design  
- **Fasteners:** M2 screws and nuts  

---

## 🍀 9. Key Highlights
- 🧩 Modular and serviceable structure  
- ⚙️ Fully functional **mechanical filtering system** with gear–servo actuation  
- 🧱 Durable PETG and carbon fiber hybrid construction  
- 🎥 Integrated optical imaging and onboard data recording  
- 🛰️ Precision-engineered for real flight recovery missions  

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/animated-divider.gif" width="80%" alt="Divider Animation">
</p>

> **Developed by:** *PSIT Vyomnauts — Members: Mohd Faiz & Rahul Kumar*  
> **Competition:** Türksat Model Satellite Competition 2024–25 (Teknofest, Turkey)  
> **Achievement:** Top 16 in PDR | Top 15 in CDR Round  
> **Material Used:** PETG, PLA+, and Carbon Fiber  
> **Design Software:** SolidWorks 2022  
> **Mission Type:** Autonomous Payload with Optical Filtering System  

<p align="center">
  <img src="https://github.com/user-attachments/assets/animated-thanks.gif" alt="Thank you animation" width="400"/>
</p>
