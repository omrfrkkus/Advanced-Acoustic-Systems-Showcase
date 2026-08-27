# 🔊 Advanced Custom Acoustic Systems — Hardware Showcase

<p align="center">
  <img src="media/excursion_demo.gif" width="600" alt="High Excursion Drivers in Action" />
</p>

> **Note:** This repository contains the architectural overviews, DSP tuning strategies, and CAD files (`/stl_files`) for two distinct, fully functional 3D-printed acoustic enclosures I engineered from scratch.

## 📌 Project Overview
This showcase demonstrates a full-cycle hardware engineering process, **developed entirely solo from scratch**. Driven by a hands-on approach to problem-solving, I leveraged **AI-assisted research** to independently master the required multidisciplinary skills—from CAD modeling in Autodesk Fusion to electromechanical assembly, power management, and acoustic signal processing. 

The primary goal was to overcome complex acoustic challenges (resonance, standing waves, internal volume constraints) within small 3D-printed form factors, without relying on pre-existing kits or external engineering support.

---

## 🚀 Iteration 2: High-SPL Waterproof System (DSP & Power)
*(Featured in the demo above)*

Pushing the limits of small-enclosure acoustics (<1 Liter), this advanced system focuses on deep low-frequency extension, high current delivery, and weather resistance.

* **Driver Architecture:** Features dual front-firing 4-ohm 11W drivers, physically coupled with a large rear **Passive Radiator** to dramatically extend bass response in a sub-1L volume.
* **High-Current Power (BMS):** Engineered a 1S2P battery pack using high-drain LG HG2 18650 cells. Integrated a dedicated Battery Management System (BMS) to safely handle the high amperage spikes during heavy bass transients.
* **Digital Signal Processing (DSP):** Powered by a 2x10W amplifier. I utilized **ACPWorkbench** to digitally tune the system, surgically cutting resonant frequencies and applying custom EQ curves to maximize high-fidelity output.
* **Acoustic Dampening:** The internal volume is packed with poly-fill material to artificially increase the acoustic compliance and reduce back-wave reflections.

<p align="center">
  <img src="media/advanced_main.jpg" width="45%" alt="Compact High-SPL Speaker" />
  &nbsp;
  <img src="media/dsp_tuning.jpg" width="45%" alt="ACPWorkbench DSP Tuning" />
</p>

---

## 🛠️ Iteration 1: Spherical TWS System (Acoustic Geometry)
The initial prototype focused on geometric acoustic treatment, power efficiency, and wireless synchronization. Built as a paired set for True Wireless Stereo (TWS) operation.

> **🖨️ Open Source Hardware:** The STL files and complete build instructions for this model are publicly available on [Printables: Sphere TWS Speakers](https://www.printables.com/model/1825186-sphere-tws-speakers).

* **Acoustic Design (600ml):** Engineered a spherical closed-box enclosure. The internal walls feature a custom 3D-printed **pyramid diffuser matrix** to break up standing waves and minimize unwanted internal resonance.
* **Hardware Specs:** Driven by a single 4-ohm 5W full-range driver per unit, powered by a Bluetooth/TWS amplifier with Type-C and AUX inputs.
* **Power Management:** Operates efficiently on a single 18650 lithium-ion cell per unit, delivering exceptional battery life for long-duration playback.

<p align="center">
  <img src="media/sphere_tws.jpg" width="30%" alt="Spherical TWS Speakers" />
  &nbsp;
  <img src="media/sphere_cad.jpg" width="30%" alt="Fusion 360 Sphere Model" />
  &nbsp;
  <img src="media/sphere_internals.jpg" width="30%" alt="Internal Pyramid Matrix" />
</p>

---

## 🔩 Structural Engineering & Manufacturing Pipeline
Both systems were manufactured with a strict focus on structural integrity, utilizing custom slicing profiles and mechanical isolation techniques.

* **Internal Bracing & Infill:** Designed custom internal ribbing structures within the CAD models. Slicer profiles were optimized using **Gyroid infill** (minimum 4-5 walls) to provide multi-directional structural strength, preventing panel resonance and acoustic energy loss.
* **Extreme Stress Testing:** Prior to electronic assembly, the empty enclosures underwent severe dynamic load testing—successfully withstanding the full dynamic weight of an adult jumping on them without any mechanical deformation, micro-fractures, or seal failures.
* **Hermetic Chamber Sealing:** Acoustic performance relies on a strict closed-box system. Internal wire routing holes connecting the acoustic chamber to the electronics bay were hermetically sealed with silicone adhesive. Exterior assembly utilizes M3 screws (threading directly into the plastic for the sphere model), secured with high-density sponge isolation tape (gaskets) and dielectric grease.
* **Electromechanical Safety:** Strict safety protocols were implemented for power management, including proper BMS integration and spot-welding/soldering procedures to prevent thermal runaway or short circuits in the 18650 lithium-ion cells.
* **Vibration Isolation:** Custom-designed and printed **TPU (Thermoplastic Polyurethane)** feet to decouple the speakers from resting surfaces, preventing external rattle.

---

## 📂 Repository Contents
* `/stl_files` - Contains the 3D printable CAD models for both iterations.
* `/media` - High-resolution photos, CAD screenshots, and performance GIFs.

## 📬 Contact
* **Email:** [omerfaruk.kus@outlook.com](mailto:omerfaruk.kus@outlook.com)
* **LinkedIn:** [linkedin.com/in/omrfrkkus](https://linkedin.com/in/omrfrkkus)
