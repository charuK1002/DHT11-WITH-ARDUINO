![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-Arduino-orange)
![Language](https://img.shields.io/badge/language-C++-blue)

# Embedded Temperature & Humidity Monitoring using DHT11

An embedded environmental monitoring system that reads **temperature and humidity data** using the **DHT11 sensor** and displays the results through the **Arduino Serial Monitor**.

---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Hardware Requirements](#-hardware-requirements)
- [Software Requirements](#-software-requirements)
- [Wiring Diagram](#-wiring-diagram)
- [DHT11 Sensor Pinout](#-dht11-sensor-pinout)
- [Code Overview](#-code-overview)
- [System Architecture](#-system-architecture)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

# 🚀 Project Overview

This project demonstrates a **basic environmental monitoring system** using the **DHT11 temperature and humidity sensor** with Arduino.

The system:

- Reads **humidity data**
- Reads **temperature values**
- Validates sensor readings
- Displays formatted output through **Serial Monitor**

This project is suitable for:

- Embedded systems learning
- IoT beginner projects
- Sensor integration practice
- GitHub Classroom assignments

---

# 🔧 Hardware Requirements

- Arduino Board (Uno / Uno R4 Recommended)
- DHT11 Temperature & Humidity Sensor
- Breadboard
- Jumper Wires
- USB Cable

Optional:

- External power supply (for extended sensor setups)

---

# 💻 Software Requirements

- Arduino IDE
- DHT Sensor Library
- Git
- GitHub Account

Optional:

- Serial Monitor
- GitHub Desktop

---

# 🔌 Wiring Diagram

### Connection Table

| DHT11 Pin | Connect To |
|-----------|------------|
| VCC       | 5V |
| GND       | GND |
| DATA      | Digital Pin 2 |

> Ensure correct wiring to avoid incorrect sensor readings.

---

# 🔎 DHT11 Sensor Pinout

- 🔴 **VCC** → 5V Power Supply  
- ⚫ **GND** → Ground  
- 🟡 **DATA** → Digital Pin (Pin 2)

**Operating Voltage:** 3.3V – 5V  
**Sensor Type:** Temperature & Humidity Sensor  
**Use Case:** Environmental monitoring systems

---

# 📚 Doxygen Documentation Requirement

Students must follow **proper Doxygen documentation standards**.

### Mandatory Documentation

- File-level documentation
- Function documentation for:
  - `setup()`
  - `loop()`

### Required Doxygen Tags

- `@file`
- `@brief`
- `@author`
- `@date`
- `@details`

---

### 📝 Example File Documentation

```cpp
/**
 * @file main.cpp
 * @brief Embedded Temperature and Humidity Monitoring using DHT11
 * @author Charu Khandelwal
 * @date 2026-03-11
 *
 * @details
 * This program reads temperature and humidity data from the DHT11
 * sensor and displays the results on the Arduino Serial Monitor.
 */
