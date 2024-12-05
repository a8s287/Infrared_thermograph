# Infrared Thermograph

This repository contains the code and necessary libraries for implementing infrared thermography using Arduino. The project includes two main versions of the program, which differ in calibration methods. This README provides an overview of the files, their purposes, and instructions for using the project.

---

## Project Structure
Infrared_thermograph/
│
├── final_0325.ino      
├── final_0409.ino       
├── libraries/           
│   ├── [Library1]/
│   ├── [Library2]/
│   └── ...
└── README.md       

---

## Features

- **Infrared Thermography Implementation**: Code for reading and processing infrared sensor data.
- **Two Program Versions**:
  - `final_0325.ino`: Original version with standard calibration.
  - `final_0409.ino`: Updated version with a different calibration method for improved accuracy.
- **Library Support**: Custom and third-party libraries are used to enhance functionality and simplify development.

---

## Requirements

### Hardware
- Arduino microcontroller
- Infrared sensor compatible with Arduino (e.g., MLX90640)
- Necessary wiring and peripherals for setup

### Software
- Arduino IDE (v1.8.x or higher)

---

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/a8s287/Infrared_thermograph.git
   cd Infrared_thermograph
