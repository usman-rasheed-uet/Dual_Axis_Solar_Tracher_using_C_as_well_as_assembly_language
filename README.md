Dual-Axis Solar Tracker ☀️⚙️
A dual-axis solar tracking system designed to control the orientation of a solar panel along two axes using stepper motors and TB6600 stepper motor drivers.
The project was developed and simulated using Proteus and MPLAB, with the embedded control firmware implemented in both C and Assembly language.
Project Overview
The system provides two degrees of freedom:
•	Azimuth axis — horizontal rotation
•	Elevation axis — vertical tilt
Two stepper motors independently control these axes, allowing the solar panel to change its orientation according to the programmed tracking logic.
System Architecture
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
              ┌──────────┴──────────┐
              │                     │
              ▼                     ▼
             C Firmware       Assembly Firmware
              │                     │
              └──────────┬──────────┘
                         ▼
                     Proteus
                    Simulation
Hardware
•	2 × Stepper Motors
•	2 × TB6600 Stepper Motor Drivers
•	Microcontroller
•	Solar Panel
•	Dual-axis mechanical structure
•	Power supply
Software & Tools
•	MPLAB — Firmware development
•	Proteus — Circuit and system simulation
•	C — Embedded firmware
•	Assembly — Low-level microcontroller programming
Motor Control
Each stepper motor controls one axis of the solar tracker.
The microcontroller generates the required STEP and DIRECTION control signals for the TB6600 drivers.
Microcontroller
      │
      ├── STEP / DIR ──► TB6600 ──► Azimuth Motor
      │
      └── STEP / DIR ──► TB6600 ──► Elevation Motor
Firmware
C Implementation
The C firmware implements the motor-control logic and generates the required control signals for the two-axis tracking mechanism.
Assembly Implementation
The same control concept was implemented in Assembly to demonstrate low-level microcontroller programming and direct hardware control.
Proteus Simulation
The system was simulated in Proteus to verify the embedded controller and motor-control logic before hardware implementation.
The simulation was used to test:
•	Microcontroller operation
•	Stepper motor control
•	STEP and DIR signals
•	Azimuth movement
•	Elevation movement
•	Two-axis coordination
•	Firmware behavior
Repository Structure
Dual-Axis-Solar-Tracker/
│
├── README.md
│
├── Firmware/
│   ├── C/
│   │   └── solar_tracker.c
│   │
│   └── Assembly/
│       └── solar_tracker.asm
│
├── Proteus/
│   └── solar_tracker.pdsprj
│
├── Documentation/
│   └── Project_Report.pdf
│
└── Images/
    ├── Proteus_Simulation.png
    └── Circuit_Diagram.png
Key Features
•	Dual-axis solar tracking
•	Independent azimuth and elevation control
•	Two stepper motors
•	TB6600 motor drivers
•	Embedded microcontroller control
•	C firmware
•	Assembly firmware
•	Proteus simulation
•	MPLAB development
•	Mechatronics and renewable-energy application
Engineering Concepts
This project demonstrates practical experience in:
•	Embedded Systems
•	Microcontroller Programming
•	C Programming
•	Assembly Programming
•	Stepper Motor Control
•	Motor Drivers
•	Digital Control
•	Circuit Simulation
•	Mechatronics
•	Renewable Energy Systems
•	Hardware–Software Integration
Future Improvements
•	Light-dependent sensors for closed-loop tracking
•	Solar-position calculation
•	Limit switches for mechanical protection
•	Position feedback
•	Real-time solar tracking
•	Solar power monitoring
•	IoT-based monitoring
•	MPPT integration
Author
Usman Rasheed
Mechatronics & Control Engineer
Electronics | Embedded Systems | Control Systems | Robotics | Renewable Energy
License
This project is intended for educational and research purposes.

