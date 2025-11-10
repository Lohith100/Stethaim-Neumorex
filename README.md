# Stethaim Wearable Diagnostic Device

A compact, high-fidelity wearable diagnostic platform integrating **Digital MEMS microphone**, **9-axis IMU**, custom PCB, and a 3D-printed CAD enclosure. Designed with ISO 13485 principles for real-time acquisition of **cardiac and pulmonary sounds**.

---

## Project Images


### PCB Front View

<img width="1039" height="738" alt="Image" src="https://github.com/user-attachments/assets/87a28cdc-1a11-4d6f-8a0a-4949e19453b9" />



### PCB Back View
<img width="1057" height="729" alt="Image" src="https://github.com/user-attachments/assets/33ee7664-b0bd-4217-8556-95420a92054f" />
### PCB 3D Design
<img width="1034" height="716" alt="Image" src="https://github.com/user-attachments/assets/5a09f39f-13b7-4b23-8361-70ec99c055b1" />

### Assembled Prototype PCB

<img width="1020" height="664" alt="Image" src="https://github.com/user-attachments/assets/54b3df3b-580d-42af-a548-cb1ae9eafe8e" />
<img width="1018" height="738" alt="Image" src="https://github.com/user-attachments/assets/a5a947b1-ab83-4ff6-82d4-b8baaaf875a8" />

### PCB Schematic
<img width="1381" height="897" alt="Image" src="https://github.com/user-attachments/assets/ef456a96-907f-47e4-9cc9-f6839fb8c4ae" />


---

## Overview

A miniaturized stethoscope-class sensor node capable of capturing:

* High-fidelity heart and lung sounds using a Digital MEMS microphone
* Motion and orientation using a 9-axis IMU
* Real-time streaming using an ESP32-based server

---

## Key Features

* Custom RoHS-compliant PCB (Altium)
* Digital MEMS microphone for low-noise audio
* 9-axis IMU for motion artifact analysis
* CAD-designed enclosure for acoustic performance
* ESP32 WiFi/BLE data transfer
* MATLAB-based filtering pipeline
* Built using ISO 13485-aligned design principles

---

## Hardware Architecture

* **MCU:** ESP32
* **Audio:** Digital MEMS microphone (I2S)
* **IMU:** 9-axis sensor (I2C)
* **Power:** Li-ion battery with onboard regulation
* **Protection:** ESD, filtering, shielding

```
MEMS Mic → ESP32 (I2S) → WiFi/BLE → Mobile App
           IMU (I2C) →   |
```

---

## Firmware Features

* I2S MEMS audio sampling
* IMU data acquisition via I2C
* Real-time streaming using Dumb Display
* Timestamped logging


---

## Signal Processing (MATLAB)

* Band-pass filtering
* Wavelet denoising
* Envelope extraction
* Spectrograms

---

## Enclosure

* Designed in SolidWorks
* Acoustic sealing optimized
* Mounting slots for PCB, mic port, vents

---



## Author

**Lohith Dayantri**

* Hardware Lead, Stethaim Private Limited
* B.Tech Biomedical Engineering, NIT Rourkela

---

## Contributing

Pull requests and suggestions are welcome.
