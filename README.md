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

This repository presents the **structural and mechanical design** of our **Türksat Model Satellite 2024–25**, developed by **Team PSIT Vyomnauts (India)** for **Teknofest, Turkey**.  
The design features an **autonomous Mechanical Filtering Module** that utilizes servo-driven gear trains to rotate optical filters for precise multi-spectral imaging.

---

## 🏆 Achievements

<div align="center">

### 🛰️ Türksat Model Satellite Competition 2024–25  

**Competition:** Türksat Teknofest 2024–25, Model Satellite Category 1  
**Developed by:** *PSIT Vyomnauts, India*  

---

### 🌍 International Rankings

| Phase | Achievement | Rank | Recognition |
|:------:|:-------------|:------:|:-------------|
| 🛰️ PDR (Preliminary Design Report) | Qualified Internationally | **Top 16** | Demonstrated Conceptual & Structural Innovation |
| ⚙️ CDR (Critical Design Report) | Qualified Internationally | **Top 15** | Excellence in Mechanical & System Design |

---

### 📊 Official Results

<p align="center">
  <img src="https://github.com/user-attachments/assets/4c206ab7-c5f7-4922-bba1-2f563996f456" width="480" alt="PDR Results"/>
  <img src="https://github.com/user-attachments/assets/63096474-3b48-44d4-84eb-7ac57b29936f" width="480" alt="CDR Results"/>
</p>

---

> 🏅 *Recognized for innovation, modularity, and mechanical precision in payload design.*

</div>


---

## 📸 Gallery

<div align="center">

### 🧱 Science Payload CAD Model
<img width="300" height="700" alt="Science Payload CAD" src="https://github.com/user-attachments/assets/e0cb5862-1aa2-426f-8ce9-c1381e846569" />

---

### 🛰️ Real Manufactured Science Payload
<img src="https://github.com/user-attachments/assets/e1147eb9-bc83-495f-bbf9-36060443dfb7" alt="Real Science Payload" width="460"/>

---

### ⚙️ Mechanical Filtering Module (CAD & Real)
<img width="474" height="441" alt="Mechanical Filtering CAD" src="https://github.com/user-attachments/assets/8cb654f8-921f-4214-ac6a-14fe2281ada8" />
<br>
<img src="https://github.com/user-attachments/assets/a3f586c7-8096-4bb5-bb36-c2d7a1734372" alt="Real Filtering Module" width="460"/>

---

### 🪂 Payload and Parachute Setup
<img src="https://github.com/user-attachments/assets/10cdefef-0cc4-4a77-9805-dd5fcc1e5ee8" alt="Payload and Parachute Setup" width="500"/>

---

### 🎬 Science Payload Drop Test (5th Floor)
<p align="center">
  <video src="https://github.com/user-attachments/assets/db06ba9d-fc3c-4d21-b04b-d542a5b91720" controls width="600"></video>
  <br>
  <em>Science Payload Drop and Parachute Deployment Test</em>
</p>

</div>

---

## 🧭 Table of Contents

1. [🪂 Parachute Compartment](#-1-parachute-compartment)  
2. [⚙️ Mechanical Filtering Module](#-2-mechanical-filtering-module)  
3. [🔄 Filtering Disk Assembly](#-3-filtering-disk-assembly)  
4. [🦾 Carbon Fiber Rods](#-4-carbon-fiber-rods)  
5. [🔩 Clamps](#-5-clamps)  
6. [🧠 PCB Plate](#-6-pcb-plate)  
7. [🔋 Battery Compartment](#-7-battery-compartment)  
8. [🧱 Assembly Summary](#-8-assembly-summary)  
9. [🍀 Key Highlights](#-9-key-highlights)

---

## 🧩 Structural Overview

| Component | Function | Material |
|------------|-----------|-----------|
| Parachute Compartment | Houses main parachute and attachment system | PETG |
| Mechanical Filtering Module | Rotates optical filters using servo-driven gears | PLA+ |
| Filtering Disks | Filter different light wavelengths for imaging | PETG |
| Carbon Fiber Rods | Provides structural integrity and alignment | Carbon Fiber (Ø4mm) |
| PCB Plate | Mounts sensors, camera, and control units | FR4 / PETG |
| Battery Compartment | Holds batteries and power board | PETG |
| Clamps | Locks all modules onto rods | PLA+ |

---

## 🪂 1. Parachute Compartment
The **uppermost section** that safely deploys the main parachute for payload recovery.  
It ensures a smooth descent post-release and houses the tether attachment system.

- **Mechanism:** Scott’s Locked Bowline Knot for secure parachute link  
- **Material:** PETG  
- **Mounting:** On carbon fiber rods with printed clamps  

---

## ⚙️ 2. Mechanical Filtering Module
This is the **core functional part** of the payload that enables **optical filtering for scientific imaging**.  
It uses **two servo motors** connected through **gear trains** to rotate two independent filtering disks.

- **Mechanism:** Servo–gear transmission system  
- **Gear Details:**
  | Gear | Module | Teeth | Ratio |
  |------|---------|--------|-------|
  | 1 | 1.0 | 14 | 1:2 |
  | 2 | 1.0 | 28 |   |
  | 3 | 1.0 | 10 |   |
  | 4 | 1.0 | 40 |   |

- **Components:**  
  - 2× MG90S Servos  
  - 8× Gears (driven & idle)  
  - 2× Filtering Disks  

- **Purpose:** Rotates optical filters for different wavelengths before image capture  
- **Material:** PLA+  
- **Control:** Commanded via microcontroller through PWM signal  

---

## 🔄 3. Filtering Disk Assembly
- Consists of two circular filtering disks mounted concentrically.  
- Each disk is controlled independently by the servo-driven gear mechanism.  
- The filters rotate into position during imaging sequences.

- **Function:** Produces clear, wavelength-filtered images  
- **Material:** PETG / PLA+  
- **Driven By:** Servo motors through 1:2 gear ratio  

---

## 🦾 4. Carbon Fiber Rods
Provide strength, vertical alignment, and distribute structural load evenly.  
All compartments are connected through these rods.

- Quantity: 4  
- Diameter: 4 mm  
- Material: Carbon Fiber  

---

## 🔩 5. Clamps
Used to mount and secure compartments along the carbon fiber rods.

- **Type:** 3D-printed tightening clamps  
- **Material:** PLA+  
- **Fasteners:** M2 screws and nuts  

---

## 🧠 6. PCB Plate
Holds all **electronic and control systems**, including the microcontroller, sensors, camera, and telemetry unit.

- **Function:** Controls servo operations and stores captured image data  
- **Material:** FR4 / PETG  

---

## 🔋 7. Battery Compartment
Located at the base, it powers the servos, sensors, and communication systems.

- **Material:** PETG  
- **Components:** Power distribution board, batteries, wiring harness  

---

## 🧱 8. Assembly Summary

- **Material:** PETG and PLA+ (3D printed) + Carbon Fiber rods  
- **Design Software:** SolidWorks 2022 SP1.0  
- **Manufacturing:** FDM 3D Printing  
- **Structure:** Modular cylindrical architecture  
- **Fasteners:** M2 bolts and nuts  

---

## 🍀 9. Key Highlights

- ✨ Modular and serviceable multi-compartment design  
- ⚙️ Dual-servo **Mechanical Filtering Module**  
- 🧩 Precision gear-driven filter disk rotation  
- 🧱 Robust PETG + Carbon Fiber structure  
- 🎥 Integrated imaging and onboard data logging  
- 🛰️ Optimized for real flight recovery and autonomous data collection  

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/animated-divider.gif" width="80%" alt="Divider Animation">
</p>

> **Developed by:** *PSIT Vyomnauts — Members: Mohd Faiz & Rahul Kumar*  
> **Competition:** Türksat Model Satellite Competition 2024–25 (Teknofest, Turkey)  
> **Achievement:** Top 16 in PDR | Top 15 in CDR Round  
> **Material Used:** PETG, PLA+, and Carbon Fiber  
> **Design Software:** SolidWorks 2022  
> **Mission Type:** Autonomous Payload with Optical Mechanical Filtering Module

<p align="center">
  <img src="https://github.com/user-attachments/assets/animated-thanks.gif" alt="Thank you animation" width="400"/>
</p>
