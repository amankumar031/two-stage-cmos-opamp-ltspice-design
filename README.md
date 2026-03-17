# Two-Stage CMOS Operational Amplifier Design (LTspice)

## 📌 Overview

This project focuses on the **design and simulation of a two-stage CMOS operational amplifier** using LTspice.

The objective was to develop a stable, high-gain amplifier with MHz-range bandwidth by utilizing CMOS differential architecture and Miller compensation techniques.

---

## ⚙️ Specifications

| Parameter            | Value            |
| -------------------- | ---------------- |
| DC Gain              | **~63 dB**       |
| Unity Gain Bandwidth | **~1 MHz**       |
| Phase Margin         | **~60°**         |
| Supply Voltage       | **1.8 V**        |
| Compensation Method  | Miller Capacitor |

---

## 🧠 Circuit Architecture

The designed op-amp is composed of the following key stages:

### 1️⃣ Differential Input Stage

* NMOS differential pair for input signal processing
* PMOS current mirror acting as active load
* Converts differential input into a single-ended output

### 2️⃣ Gain Stage

* Implemented as a common-source amplifier
* Enhances overall voltage gain of the circuit

### 3️⃣ Compensation Network

* Miller capacitor introduced between stages
* Ensures stability and improves phase margin
* Helps in controlling frequency response

---

## 📊 Simulation Approach

AC analysis was carried out in **LTspice** to evaluate the performance of the amplifier, including:

* Open-loop gain
* Frequency response
* Phase margin
* Unity gain bandwidth

The design uses CMOS transistor models with a **1.8 V supply** for simulation.

---

## 🎯 Key Learnings

* Fundamentals of CMOS analog circuit design
* Working of two-stage operational amplifiers
* Current mirror biasing techniques
* Frequency compensation using Miller capacitor
* Stability analysis through Bode plots
* Practical experience with LTspice simulations

---

## 🛠️ Tools Used

* **LTspice** for circuit design and simulation
* Standard CMOS transistor models

---

## 👨‍💻 Author

**Aman Kumar**

Electronics Engineering Student

Interested in **Analog IC Design and VLSI**
