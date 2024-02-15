# 🌡️ Qualitative Analysis of Resistor's Temperature Behaviour

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Arduino-00979D?style=for-the-badge&logo=arduino" />
  <img src="https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Sensor-MAX6675-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Institute-NSUT-blue?style=for-the-badge" />
</p>

> **Centre for Electronic Design and Technology**  
> Netaji Subhas University of Technology, New Delhi  
> *Date: February 2024*

---

## 📋 Table of Contents
- [Synopsis](#-synopsis)
- [Introduction](#-introduction)
- [Procedure](#-procedure)
- [Results](#-results)
- [Conclusion](#-conclusion)
- [Bill of Materials](#-bill-of-materials)

---

## 🎯 Synopsis

This experiment provides a **qualitative investigation** of how standard resistor values change with temperature. Using a controlled heating setup and an Arduino-based measurement system with a K-type thermocouple (MAX6675), the resistance variation was monitored as the resistor was heated. The results provide visual and empirical evidence of the temperature-dependent behavior of resistive components.

## 📖 Introduction

Resistor values are not constant — they change with temperature. This temperature dependence is an important consideration in precision circuit design. By heating a resistor in a controlled manner and simultaneously measuring both its resistance and temperature, we can observe and characterize this behavior qualitatively.

## ⚙️ Procedure

1. Test resistor placed in a heated cavity (wire-wound power resistor)
2. K-type thermocouple (MAX6675) monitored temperature
3. Resistance measured via voltage divider with Arduino
4. Data logged via serial to CSV using CoolTerm
5. Results analyzed and plotted in Python

## 📊 Results

The resistance–temperature plot clearly shows the expected trend: resistance decreases with increasing temperature for the tested carbon-composition resistors.

## ✅ Conclusion

The experiment successfully demonstrated the qualitative relationship between temperature and resistance, providing visual evidence that supports the theoretical understanding of negative TCR behavior in standard carbon-composition resistors.

## 📦 Bill of Materials

| S.No | Component | Value | Qty |
|------|-----------|-------|-----|
| 1 | Test Resistor | Various | 1 |
| 2 | Power Resistor | 5 Ω (35W) | 1 |
| 3 | Arduino Uno | — | 1 |
| 4 | Thermocouple (MAX6675) | K-type | 1 |
| 5 | DC Power Supply | — | 1 |

## 🛠️ Technologies Used

`Arduino` · `Python` · `MAX6675` · `CoolTerm` · `Matplotlib`

## 👥 Authors
- **Ansh Gupta** — NSUT, New Delhi
- **Shubham Kumar** — NSUT, New Delhi

---
*Centre for Electronic Design and Technology, NSUT, New Delhi*
