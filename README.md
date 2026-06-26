# ⚡ Transformerless Power Supply

> A compact AC-to-DC power supply designed without using a bulky transformer. This project converts AC mains into a regulated low-voltage DC output using a capacitive dropper circuit, bridge rectifier, filter capacitors, and voltage regulator.

---

## 📌 Overview

This project demonstrates the design and simulation of a **Transformerless Power Supply** using **KiCad**. Instead of a conventional transformer, it uses a **capacitive dropper** to reduce the AC voltage, making the circuit lightweight, low-cost, and compact for low-power applications.

The output is regulated using a voltage regulator IC to provide a stable DC voltage suitable for electronic circuits.

---

## ⚙️ Working 

1.  **AC Input**
   - AC mains is applied to the input.

2.  **Capacitive Voltage Drop**
   - An X-rated capacitor limits the current without dissipating much power.

4.  **Rectification**
   - A bridge rectifier converts AC into pulsating DC.

6.  **Voltage Regulation**
   - A voltage regulator IC(7805) provides a stable DC output.

7.  **Output**
   - Clean regulated DC is available for low-power electronic devices.

---

## ✨ Features

 ✅ Transformerless compact design
 
 ✅ Low-cost implementation
 
 ✅ Bridge rectifier for AC-DC conversion
 
 ✅ Filter capacitors for ripple reduction
 
 ✅ Regulated DC output
 
 ✅ KiCad schematic design
 
 ✅ Suitable for low-power embedded applications

---

## 🛠 Components Used
- Input connector
- Capacitive Dropper Capacitor(225k/2.2uf)
- Bridge Rectifier (1N4007 Diodes)
- Filter Capacitors
- Current Limiting Resistors
- Voltage Regulator IC(LM7805)
- LED Indicator
- Output Connector

---

## 🚀 Applications

-  IoT Devices
-  Sensor Modules
-  LED Indicator Circuits
-  Home Automation
-  Low-Power Embedded Systems
-  Electronic Learning Projects

---

## ⚠️ Safety Warning

> **DANGER: HIGH VOLTAGE**

This circuit is **NOT electrically isolated** from the AC mains.

1 Do **NOT** touch any part of the circuit while powered.

2 Use only for educational, simulation, or properly enclosed applications.

3 Always disconnect power before testing or modifying the circuit.

4 Not recommended for beginners without proper supervision.

---

## 💻 Software Used

- 🟢 KiCad (10.0.1)

---

## 📷 Project Preview


---

## 📄 License

This project is intended for **educational and learning purposes**.

---
