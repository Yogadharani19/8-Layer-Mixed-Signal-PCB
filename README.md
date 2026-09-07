# 8-Layer Mixed-Signal PCB Design

## 📌 Project Overview

This project focuses on the design and development of an **8-layer mixed-signal PCB using Altium Designer**. The project covers the complete PCB design workflow, from schematic development and component selection to PCB layout, multilayer routing, design-rule configuration, and final verification.

## 🎯 Objectives

* Develop a complete multi-sheet schematic.
* Design an 8-layer PCB stack-up.
* Perform two-sided component placement.
* Implement multilayer PCB routing.
* Configure PCB design rules.
* Perform Design Rule Checking (DRC).
* Apply industry-oriented IPC design guidelines.
* Consider signal integrity, power distribution, EMI/EMC, and manufacturability.

## 🛠️ Tools & Technologies

* **Altium Designer**
* PCB Schematic Design
* PCB Layout & Routing
* Component & Footprint Selection
* Design Rule Configuration
* Design Rule Checking (DRC)

## 📐 PCB Specifications

| Parameter          | Specification     |
| ------------------ | ----------------- |
| Board Size         | 127 mm × 101.6 mm |
| Layer Count        | 8 Layers          |
| PCB Type           | Mixed-Signal      |
| Assembly           | Two-Sided         |
| Routing            | Multilayer        |
| Design Class       | IPC Class 2       |
| Differential Pairs | Not Used          |

## 🧱 Layer Stack-Up

| Layer      | Function            |
| ---------- | ------------------- |
| L1 – TOP   | Signal / Components |
| L2 – PLANE | Ground              |
| L3 – SIG1  | Signal              |
| L4 – PLANE | Power               |
| L5 – PLANE | Ground              |
| L6 – SIG2  | Signal              |
| L7 – PLANE | Ground              |
| L8 – BOT   | Signal / Components |

## 🔄 Design Workflow

**Requirements → Schematic → Component Selection → Footprints → PCB Setup → Layer Stack-Up → Design Rules → Component Placement → Routing → DRC → Final Documentation**

## 📚 Design Guidelines

The PCB design considers:

* IPC Class 2 requirements
* IPC-7351 footprint guidelines
* IPC-222x PCB design guidelines
* Signal integrity
* Power distribution
* EMI/EMC considerations
* Manufacturability
* Two-sided assembly

## 👩‍💻 Project Role

**PCB Design & Layout Engineer**

Designed the schematic, selected components and footprints, configured the 8-layer stack-up, performed component placement and multilayer routing, and verified the design using Altium Designer's PCB design and DRC tools.
