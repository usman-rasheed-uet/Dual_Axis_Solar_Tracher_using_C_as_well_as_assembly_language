# Dual-Axis Solar Tracker ☀️

A **dual-axis solar tracking system** developed using two stepper motors and **TB6600 stepper motor drivers**. The system controls the **azimuth and elevation axes** of a solar panel through a microcontroller-based control system.

The project was developed and simulated using **MPLAB and Proteus**, with the control program implemented in both **C and Assembly language**.

---

## 📌 Project Overview

The solar tracker provides two degrees of freedom:

* **Azimuth Axis** – horizontal movement
* **Elevation Axis** – vertical movement

Each axis is controlled by an independent stepper motor through a TB6600 driver.

---

## ⚙️ Hardware

* 2 × Stepper Motors
* 1 × TB6600 Stepper Motor Drivers
* Microcontroller
* Solar Panel
* Dual-Axis Mechanical Structure
* Power Supply

---

## 💻 Software & Tools

| Tool / Technology | Purpose                           |
| ----------------- | --------------------------------- |
| **MPLAB**         | Firmware development              |
| **Proteus**       | Circuit and system simulation     |
| **C**             | Embedded firmware                 |
| **Assembly**      | Low-level firmware implementation |
| **TB6600**        | Stepper motor control             |

---

## 🔄 System Architecture

```text
                    Solar Panel
                         │
              ┌──────────┴──────────┐
              │                     │
        Azimuth Axis          Elevation Axis
              │                     │
        Stepper Motor          Stepper Motor
              │                     │
           TB6600                TB6600
              │                     │
              └──────────┬──────────┘
                         │
                   Microcontroller
                         │
                  ┌──────┴──────┐
                  │             │
                  C         Assembly
                  │             │
                  └──────┬──────┘
                         │
                      Proteus
                    Simulation
```

---

## ✨ Features

* Dual-axis solar tracking
* Independent azimuth and elevation control
* Stepper motor-based positioning
* TB6600 motor drivers
* C firmware implementation
* Assembly firmware implementation
* Proteus simulation
* MPLAB development environment

---

## 🧠 Engineering Concepts

* Embedded Systems
* Microcontroller Programming
* Stepper Motor Control
* Motor Drivers
* Digital Control
* Hardware–Software Integration
* Circuit Simulation
* Mechatronics
* Renewable Energy Systems

---

## 📂 Repository Structure

```text
Dual-Axis-Solar-Tracker/
│
├── README.md
│
├── C/
│   └── solar_tracker.c
│
├── Assembly/
│   └── solar_tracker.asm
│
├── Proteus/
│   └── solar_tracker.pdsprj
│
├── Documentation/
│   └── Project_Report.pdf
│
└── Images/
    ├── Circuit_Diagram.png
    └── Proteus_Simulation.png
```

---

## 🚀 Future Improvements

* Automatic light-based tracking using LDRs
* Closed-loop position feedback
* Limit-switch protection
* Solar-position calculation
* Real-time tracking
* Solar power monitoring

---

## 👨‍💻 Author

**Usman Rasheed**

Mechatronics & Control Engineer

**Areas:** Embedded Systems · Control Systems · Robotics · Electronics · Renewable Energy

---

## 📜 License

This project is intended for **educational and research purposes**.
