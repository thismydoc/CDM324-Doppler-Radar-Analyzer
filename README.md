# CDM324-Doppler-Radar-Analyzer-
A repository for analyzing and experimenting with the CDM324 24.125 GHz microwave Doppler module, also know as IPM165. Includes signal processing, embedded system integration, and motion detection applications.

## 🌟 Key Features

- 📊 **Raw Signal Analysis** (analog output)
- 🤖 **Motion Detection Algorithms** (speed, presence)
- 🔌 **Hardware Integration** (Arduino)


## 📌 Technical Specifications

| Parameter          | Value                  |
|--------------------|------------------------|
| Frequency          | 24.125 GHz             |
| IF Output Signals  | Analog                 |
| Power Requirements | 5V DC, 80mA            |

## 🛠️ Hardware Setup

### Required Components
- 24.125 GHz Doppler Radar Module (CDM324, IPM165)
- MCU (Arduino Uno)
- USB Logic Analyzer (for signal debugging)

### Wiring Guide
```plaintext
Radar Pinout:
VCC    -> 5V
GND    -> GND
OUT -> Analog
