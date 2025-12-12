# 📘 Ohm's Law Calculator

A lightweight and interactive web application for calculating **voltage (U)**, **current (I)**, **resistance (R)**, and **power (P)** based on Ohm’s Law.  
Includes dynamic charts that visualize how electrical values change with varying voltage.

---

## ✨ Features

### 🔢 Dynamic Calculations  
You can input any valid combination of electrical values, and the app calculates the missing ones:

- **U + I → R & P**
- **U + R → I & P**
- **P + U → I & R**
- **P + I → U & R**
- **P + R → U & I**

✅ Automatically recalculates in real time  
✅ Supports multiple calculation scenarios  

---

## 📊 Interactive Charts

Two automatically updating charts:

- **Current vs Voltage** (I while U varies)  
- **Power vs Voltage** (P while U varies)

These charts give visual insight into how electrical values behave when voltage changes.

---

## 🎛️ Smart User Interface

- Automatically hides unused fields based on the chosen calculation mode  
- Real-time updating of all values  
- Clean, simple layout  
- All results are nicely rounded  

---

## 🧮 Formulas Used

### **Ohm’s Law**

```math
U = I \cdot R
I = \frac{U}{R}
R = \frac{U}{I}
