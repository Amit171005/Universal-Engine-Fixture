# Universal Motorcycle Engine Fixture

**Bajaj TORQ Challenge 2026 – Stage 2 Project**

## Overview

This project presents a **universal flexible fixture** designed to mount multiple motorcycle engines (125–400 cc) on a single platform while maintaining high rigidity, precision, and adaptability.

Unlike conventional fixtures, this system is not just universal—it is **designed for future automation**, enabling transition toward Industry 4.0 assembly systems.

## Problem Statement

Assembly lines currently face:

* Multiple dedicated fixtures → high tooling cost
* 20–30 minute changeover delays
* No scalability for new engine models

The challenge was to create a **single fixture** that:

* Handles multiple engine geometries
* Maintains ±0.1 mm accuracy
* Works under real assembly torque conditions

## Core Design Concept

### Triangular 3-Point Locating System

* Eliminates rocking
* Ensures complete constraint
* Distributes load efficiently

### Modular Locator Architecture

* Fixed primary locator (datum)
* Single-axis secondary slider (dovetail)
* Two-axis tertiary slider

### Bush-Based Precision System

* One universal pin
* Precision achieved through interchangeable bushes
* Handles diameter, depth, and alignment variations

## Structural Validation (ANSYS + Analytical)

* Max Stress: **67.77 MPa**
* Factor of Safety: **3.68**
* Locator deformation: **0.0657 mm (< ±0.1 mm)**
* Analytical FOS: **~4.78**

  Fully elastic behavior
  Stable under 50 kg load + 20 kg·m torque 

# Future-Ready Automation (Key Highlight)

## Motor + Lead Screw Based Actuation

The current design uses **manual slider positioning**, but it is intentionally engineered to support **full automation using motor-driven lead screw systems**.

### Concept

* Replace manual slider adjustment with:

  * **Electric motor + lead screw mechanism**
* Convert rotational motion → precise linear positioning of sliders

## Why This Is Critical

### 1. Fully Automated Changeover

* Current: 5–10 minutes manual adjustment
* With automation: **< 60 seconds changeover** 

### 2. Programmable Fixture Positions

* Each engine configuration stored as coordinates
* Motor-driven system moves locators automatically
* Eliminates human dependency and setup errors

### 3. Industry 4.0 Integration

* Can be integrated with:

  * PLC systems
  * Conveyor line control
  * Smart manufacturing databases

### 4. High Precision Positioning

* Lead screw provides:

  * Controlled motion
  * Repeatable positioning
  * No backlash (with proper design)

### 5. Scalable Architecture

* Same base fixture can:

  * Adapt to new engine models
  * Update via software instead of hardware redesign

## Automation Extensions

### Automated Slider Locking

* Replace manual bolts with:

  * Servo/pneumatic locking
* Ensures fast and consistent clamping

### Smart Changeover System

* Pre-programmed engine database
* One-click reconfiguration
* No manual intervention

### Hybrid Constraint System

* Integration with:

  * Front boss grippers
  * Sensor-based positioning

## Engineering Significance

This project is not just a fixture—it is a **transition from conventional tooling to intelligent fixturing systems**.

* Separates rigidity and adaptability
* Enables automation without redesign
* Bridges mechanical design with mechatronics

## Supported Engines

* Bajaj Pulsar NS 200
* Bajaj Pulsar NS 400
* KTM 250 / 390
* Triumph Speed 400

## Manufacturing & Practicality

* Fully manufacturable using standard machining
* No special tooling required
* Replaceable wear components

## Key Advantages

* Single fixture replaces multiple fixtures
* Reduced cost and floor space
* Faster changeover
* Automation-ready architecture

## Project Structure

Analysis/       → ANSYS simulations  
CAD/            → 3D models  
Presentation/   → Pitch deck  
Report/         → Detailed report  

## Future Scope

* Motorized lead screw actuation (primary upgrade)
* PLC-controlled fixture positioning
* Smart factory integration
* Sensor-based feedback system

## Team

**Tractive Minds**
Amit Kumar | A. Bharath Kumar | A. Srinidhi

