# IoT-based Condition Monitoring and Diagnostic System for RCBO/ELCB Circuit Breakers

## Overview

This project implements an IoT-based monitoring and diagnostic system for RCBO/ELCB circuit breakers. The system measures AC current, performs RMS current calculation, and detects zero-crossing points using a microcontroller-based signal processing system. The measured data is transmitted wirelessly using an ESP32 WiFi module for remote monitoring and analysis.

The objective of this project was to develop a smart monitoring platform capable of detecting abnormal electrical conditions and enabling preventive maintenance of circuit protection devices.

Developed at:  
Nemi Parshva Trader LLP (Moti Group), Surat, India  

Duration:  
January 2022 – September 2022

---

## System Architecture

The system is composed of three main layers:

**Sensing Layer**  
Measures AC current flowing through the RCBO/ELCB using a current sensing circuit.

**Processing Layer**  
A microcontroller processes the analog signals, calculates RMS current values, and detects zero-crossing events.

**Communication Layer**  
ESP32 transmits sensor data wirelessly via WiFi to a remote monitoring system.

**Data Flow**

Current Sensor → Signal Conditioning → Microcontroller → ESP32 WiFi → Remote Monitoring

---

## Hardware Components

- Microcontroller for signal processing  
- ESP32 WiFi module for communication  
- Current sensing circuit  
- Zero-cross detection circuit  
- Signal conditioning circuit  
- Custom-designed PCB  

Supporting components:

- Operational amplifiers for signal conditioning  
- Resistors and capacitors for filtering  
- Power supply regulation circuit  

---

## Firmware Implementation

The firmware was developed in Embedded C.

Main functionalities implemented:

- ADC-based current signal acquisition  
- RMS current calculation from AC waveform samples  
- Zero-cross detection for waveform synchronization  
- ESP32 WiFi communication for data transmission  
- Real-time monitoring capability  

---

## Key Features

- Real-time current monitoring  
- Accurate RMS current measurement  
- Zero-cross detection of AC waveform  
- Wireless data communication using ESP32 WiFi  
- Custom PCB design with functional and EMC verification  

---

## Applications

- Industrial electrical protection monitoring  
- Smart electrical distribution panels  
- Predictive maintenance systems  
- IoT-based electrical monitoring solutions  

---

## Future Improvements

- Cloud-based data monitoring platform  
- Mobile dashboard for real-time monitoring  
- Integration with smart grid systems  
- Voltage, power, and energy monitoring features
