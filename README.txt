# EUROBOT 2026 PCBs

Repository containing PCB design files for the Eurobot 2026 competition.

Author: Hatem Ben Salha
GitHub: https://github.com/Hatem-BS4
LinkedIn: https://linkedin.com/in/hatem-ben-salha

---

## Repository Contents

**carte distribution/**
- Component distribution files and circuit schematics

**Carte Mosfet/**
- MOSFET driver PCB design files
- Schematics and board layouts

**Carte servo/**
- Servo motor control PCB designs
- PWM signal conditioning circuits

**ESP motors - 2.0/**
- ESP32-based motor control v2.0
- Firmware and hardware integration
- Communication protocols for competition robot

**Pami_ESP32/**
- Primary ESP32 board design
- Main controller for the competition robot
- Sensor integration interfaces

**Gerbers/**
- PCB manufacturing files (Gerber format)
- Drill files and layer specifications
- Ready for PCB fabrication

---

## Project Context

These PCB designs were developed as part of the Eurobot 2026 competition, an international robotics competition for engineering students.

The designs include:
- Custom motor drivers for competition robot actuation
- Sensor interface circuits for vision and obstacle detection
- ESP32-based communication modules for wireless control
- Power management circuits for battery optimization
- Modular design approach for rapid prototyping and iteration

## Technical Details

**Software Used:**
- KiCad EDA (for schematic capture and PCB layout)
- Gerber format for PCB manufacturing
- Embedded C/Firmware for ESP32 microcontroller

**Hard Platform:**
- STM32/ESP32 microcontrollers (as per competition requirements)
- Custom 2-4 layer PCBs for optimal signal integrity
- Surface-mount components for compact design

## Getting Started

1. Clone the repository to explore the design files:
   ```bash
   git clone https://github.com/Hatem-BS4/EUROBOT-2026-PCBs.git
