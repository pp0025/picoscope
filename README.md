# 📈✨ **PICOSCOPE – Pocket Oscilloscope using Raspberry Pi Pico**

### *A Portable DIY Oscilloscope for Real-Time Signal Visualization*

<p align="center">
  <img src="images/picoscope-cover.jpg" width="420px" />
</p>

---

## 🚀 **Overview**

**PICOSCOPE** is a simple and portable **oscilloscope built using the Raspberry Pi Pico** and the **Scoppy Android app**.
It enables real-time visualization of analog waveforms, making it a compact diagnostic tool for electronics hobbyists, students, and embedded developers.

The system utilizes the Pico’s **ADC hardware** to sample analog signals and stream them to a smartphone for display — creating a low-cost alternative to traditional oscilloscopes.

---

## ⚙️ **Tech Stack**

| Category               | Tools / Hardware       |
| ---------------------- | ---------------------- |
| **Microcontroller**    | Raspberry Pi Pico      |
| **Software Interface** | Scoppy Mobile App      |
| **Sampling System**    | Pico ADC               |
| **Connectivity**       | USB Data Mode          |
| **Development Tool**   | MicroPython / Pico SDK |

---

## ⭐ **Features**

* 📊 Real-time waveform display
* 🔌 Direct USB communication with Scoppy app
* ⚡ ADC-based analog signal sampling
* 🎛️ Adjustable scaling & trigger options (via app)
* 🧰 Perfect for quick debugging and field testing
* 📱 Works directly with any Android smartphone

---

## 🔧 **Hardware Components**

* Raspberry Pi Pico
* USB Cable (Data supported)
* Analog signal input wires
* Breadboard (optional)
* Signal source (function generator / sensor output)

---

## 🔌 **Circuit Wiring**

Upload your wiring diagram to:
`/circuit-diagrams/wiring-diagram.png`

### Basic Signal Wiring

```
Analog Signal → Pico ADC Pin (e.g., GP26/A0)  
Ground → Pico GND  
USB → Smartphone (OTG) or PC
```

---

## 🧠 **How It Works**

1. Raspberry Pi Pico runs firmware compatible with **Scoppy**.
2. Pico samples analog signals using its **12-bit ADC**.
3. ADC samples are streamed over USB at a stable rate.
4. The **Scoppy app** visualizes the waveform in real-time.
5. User can adjust gain, timebase, and trigger settings directly in the app.

This transforms the Pico into a compact, budget-friendly oscilloscope.

---

## 📱 **Scoppy Android App**

Download from Play Store → Connect Pico via USB OTG → Select **Oscilloscope Mode**.

The app automatically detects the Pico and begins streaming data.

Upload your screenshots to:
`/images/scoppy-interface.jpg`

---

## 📁 **Project Folder Structure**

```
picoscope-rpi-pico/
│
├── src/
│   └── firmware-files-here
│
├── circuit-diagrams/
│   └── wiring-diagram.png
│
├── images/
│   ├── picoscope-cover.jpg
│   ├── scoppy-interface.jpg
│   └── signal-test.jpg
│
└── README.md
```

---

## 📚 **Libraries / Tools Used**

* Raspberry Pi Pico SDK / MicroPython Firmware
* Scoppy App & Firmware Interface
* Pico ADC Hardware Module

---

## 🔮 **Future Improvements**

* Add dual-channel input support
* Include signal frequency measurement
* Add waveform export as CSV
* Add protective input circuitry
* Integrate with PC-based UI

---

## ❤️ **Developed By**

**Akash Roy**
Electronics & Embedded Systems Enthusiast
📧 [aroy50809@gmail.com](mailto:aroy50809@gmail.com)

---

## ⭐ **Support**

If you like this project, please ⭐ **star the repository** — it helps support future open-source developments!

---


I can create those too!
