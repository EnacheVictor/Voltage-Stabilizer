# ⚙️ Voltage Stabilizer – OrCAD Capture, PSpice & PCB Layout Project

This repository contains the complete **Voltage Stabilizer** project designed using **OrCAD Capture**, simulated with **PSpice**, and implemented with **PCB layout tools** from the OrCAD suite.

The project demonstrates how to design, simulate, and lay out a discrete analog voltage regulator from scratch.

---

## 🧩 Project Overview

A voltage stabilizer is a critical circuit that ensures a **steady output voltage** despite fluctuations in input voltage or load conditions. The circuit designed here uses:

- Bipolar Junction Transistors (BJTs)
- Zener diodes as voltage references
- Voltage dividers and feedback
- Passive RC components for smoothing
- Custom PCB implementation for hardware realization

---

## 🖼️ Circuit Schematic

![Voltage Stabilizer Circuit](Screenshot%202025-03-27%20200222.png)

> Schematic created in **OrCAD Capture**. Full simulation performed in **PSpice**.

---

## 🛠️ Key Features

- ✅ Discrete analog design (no integrated voltage regulators)
- ✅ Load and line regulation
- ✅ Thermal stability via negative feedback
- ✅ Real PCB layout included (ready for manufacturing)
- ✅ BOM and documentation included

---

## 🧪 How to Use

### 🔍 Simulation (PSpice)
1. Open the `.opj` project file in **OrCAD Capture**.
2. Load one of the PSpice simulation profiles from the `Simulations/` folder.
3. Run transient, DC sweep, or bias point simulations.
4. Analyze output voltage stability, response time, and regulation quality.

### 🧾 PCB Layout
1. Open the layout files from the `Layout/` folder in **OrCAD PCB Editor / Allegro**.
2. Inspect component placement, routing, and ground/power planes.
3. Generate Gerber files for fabrication if needed.

---

## 📁 Project Structure

| Folder / File                | Description                                        |
|-----------------------------|----------------------------------------------------|
| `Schematics/`               | Schematic files (`.dsn`, `.opj`)                   |
| `Simulations/`              | PSpice simulation settings & results               |
| `Layout/`                   | PCB layout files (OrCAD PCB Editor)                |
| `Bill_of_Materials/`        | BOM and component details                          |
| `Proiect docs/`             | Reports and supporting documents                   |
| `schema bloc.jpg`           | Functional block diagram                           |
| `Tema 3 - N10.pdf`          | Assignment brief in Romanian                       |

---

## 🧠 Educational Purpose

This project was developed as part of a lab assignment in the **Analog Electronics** or **Voltage Regulation** module. It’s designed to teach:

- Analog component-level design
- Real-world circuit simulation
- PCB implementation workflow
- Analysis of voltage regulation behavior

---

## 👤 Author

**Enache Victor**  
Group 434D – SERS  
Faculty of Electronics  
📅 Academic Year: 2024–2025

## 📜 License

Shared for academic and educational purposes.  
You may fork, modify, and use the files non-commercially with credit.
