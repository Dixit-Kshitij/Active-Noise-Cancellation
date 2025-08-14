# 🎧 Active Noise Cancellation (ANC) Circuit

## 📌 Overview
This project implements an **Active Noise Cancellation (ANC)** circuit using two operational amplifiers (op-amps).  
The circuit reduces unwanted noise by generating an **anti-noise signal**—an inverted version of the noise—which is then combined with the original audio signal to cancel the noise.

This principle is widely used in **ANC headphones** and other modern audio systems to improve sound quality.

---

## ⚙ Working Principle

### 1️⃣ First Op-Amp – Inverting Amplifier
- Takes the unwanted noise as input.
- Amplifies and **inverts the phase** of the noise signal.
- This inversion creates an **anti-noise signal**.
- Gain is controlled by resistor values to ensure proper amplitude for cancellation.

### 2️⃣ Second Op-Amp – Summing Amplifier
- Combines the **anti-noise signal** (from the first op-amp) with the **original audio signal**.
- The unwanted noise is effectively **canceled out**, leaving clean audio output.

---

## 🔍 Circuit Explanation
- **Inverting Amplifier**: Generates an anti-noise signal by phase-inverting the unwanted noise.
- **Non-Inverting Summing Amplifier**: Mixes the anti-noise signal with the original audio, canceling noise through destructive interference.

---

## 📊 Applications
- ANC Headphones
- Audio Recording Systems
- Communication Devices
- Industrial Noise Control

---

## 🛠 Components Used
- **Op-Amps** (2x)
- Resistors (for gain control)
- Audio Input Source (music signal)
- Noise Input Source (unwanted noise)
- Power Supply for op-amps


## 🖼 Block Diagram
