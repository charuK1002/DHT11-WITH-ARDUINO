
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


## 🧠 Code Overview

The system uses the `DHT.h` library to read **temperature and humidity values** from the DHT11 sensor.

### Core Logic Flow

1. Initialize DHT sensor object  
2. Start Serial communication  
3. Read humidity value from sensor  
4. Read temperature value from sensor  
5. Validate sensor readings using `isnan()`  
6. Display formatted values on Serial Monitor  

---

### Example Code Structure

```cpp
/**
 * @file main.cpp
 * @brief Embedded Temperature and Humidity Monitoring using DHT11
 * @author Charu Khandelwal
 * @date 2026-03-11
 *
 * @details
 * This program reads environmental data from the DHT11 sensor
 * and displays temperature and humidity values on the Serial Monitor.
 */

#include <DHT.h>

// TODO 1: Define the DHT data pin (Use digital pin 2)
// #define DHTPIN ?

// TODO 2: Define the DHT sensor type
// #define DHTTYPE DHT11

// TODO 3: Create DHT object
// DHT dht(DHTPIN, DHTTYPE);

void setup() {

    // TODO 4:
    // Initialize Serial communication (9600 baud rate)

    // TODO 5:
    // Initialize the DHT sensor

    // TODO 6:
    // Print system initialization message
}

void loop() {

    // TODO 7:
    // Read humidity value from sensor

    // TODO 8:
    // Read temperature value from sensor

    // TODO 9:
    // Check if reading failed using isnan()
    // If failed, print error message and return

    // TODO 10:
    // Print formatted temperature and humidity values

    // TODO 11:
    // Add a 2-second delay before next reading
}
--------
🏆 Why This Repository Follows Professional Standards

This repository is designed to ensure:

Structured and organized project layout

Clean and properly formatted Markdown documentation

Compatibility with GitHub Classroom workflow

Industry-standard embedded programming practices

Alignment with modern software engineering principles

--------
