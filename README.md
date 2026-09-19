# Smart Window Cleaning System Using Embedded Technology

## 📌 Project Overview

The Smart Window Cleaning System is an embedded-system-based project designed to assist in cleaning glass windows using motorized movement and suction.
The system uses an STM32 microcontroller to control the movement of the cleaning mechanism. DC gear motors are used for movement, while a BLDC motor-based suction mechanism provides the required holding force on the glass surface. Bluetooth communication is used for wireless control.

## 🎯 Objectives
* To develop a compact embedded system for window cleaning.
* To control the movement of the system using DC gear motors.
* To provide suction for maintaining contact with the glass surface.
* To provide wireless control using Bluetooth.
* To develop a practical and cost-effective window cleaning system.

## ⚙️ Main Technologies
* Arduino-uno Microcontroller
* Embedded C
* N20 Gear Motors
* BLDC Suction Motor
* Motor Driver
* Bluetooth Communication
* SMPS Power Supply

## 🧩 System Components

| Component        | Purpose                      |
| ---------------- | ---------------------------- |
| STM32            | Main system controller       |
| DC Gear Motors   | Movement of the system       |
| Motor Driver     | Drives the DC motors         |
| BLDC Motor       | Generates suction            |
| Impeller         | Produces airflow for suction |
| Bluetooth Module | Wireless control             |
| SMPS             | Power supply                 |
| Wheels           | Movement on glass surface    |

## 🔄 Working Principle

The Arduino-uno microcontroller acts as the main controller of the system.
The Bluetooth module receives movement commands from the user and sends them to the microcontroller
The STM32 processes these commands and controls the DC gear motors through the motor driver.
A BLDC motor drives the suction mechanism to generate the required suction force and maintain contact with the glass surface.

## 🧱 System Architecture
The major blocks of the system are:
Bluetooth → Arduino-uno → Motor Driver → DC Gear Motors

 Software

* Arduino IDE
* Embedded C
* Proteus / simulation tools where applicable

## 📁 Repository Structure

```text
smart-window-cleaning-system/
│
├── README.md
├── Code/
├── Circuit_Diagram/
├── Block_Diagram/
├── Images/
├── Simulation/
└── Documentation/
```

## 📷 Project Images

Project photographs, circuit diagrams and testing images will be added to the repository.

## 📊 Project Status

**Development Status:** Ongoing

The project is being developed and tested as a major project in Electronics and Telecommunication Engineering.

## 🔮 Future Improvements

* Automatic window-edge detection
* Improved suction control
* Obstacle and edge detection
* Automatic cleaning path
* Sensor-based safety control
* Improved battery-powered operation

## 👩‍💻 Author

**Mrunmai Joshi**

Electronics & Telecommunication Engineering


## 📌 Note
This repository contains the development work, source code, design files and documentation associated with the project.
