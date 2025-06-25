# Sign-Language-to-Speech-Glove-STM32-based-
A wearable glove that detects sign language gestures using flex sensors and translates them into spoken words using an STM32 microcontroller and an MP3 playback module. The goal is to build an affordable, real-time communication aid for the speech and hearing impaired.

## 🎯 Project Goal

To build a real-time, portable, and affordable wearable that:
- Detects finger gestures through flex sensors
- Processes data on an STM32 microcontroller
- Outputs audio via a speaker using an MP3 module

---

## 🔧 Features

- 👆 Detects basic gestures like `YES`, `NO`, and `PEACE`
- 🧠 STM32 processes analog input from 5 flex sensors
- 🔊 Audio output using DFPlayer Mini / MP3-TF-16P via UART
- 📦 Modular design — easily expandable to more gestures or full ASL alphabet

---

## 🛠️ Hardware Used

| Component              | Quantity | Purpose                          |
|------------------------|----------|----------------------------------|
| STM32 B-L475E-IOT01A1  | 1        | Main microcontroller             |
| Flex Sensors           | 5        | Detect finger bends              |
| MP3-TF-16P Module      | 1        | Audio playback (MP3)             |
| MicroSD Card           | 1        | Stores `.mp3` audio files        |
| 8Ω Speaker             | 1        | Plays audio output               |
| Jumper wires, breadboard, glove | — | Assembly and testing |

---

## ⚙️ Software Stack

- STM32CubeMX & STM32CubeIDE (HAL-based C firmware)
- UART communication with MP3 module
- ADC readings from flex sensors
- Gesture logic with thresholding

---

## 🧪 Current Status

- ✅ Base prototype working
- ✅ Code for 3 gestures (YES, NO, PEACE)
- 🔜 Next: ML integration for dynamic gesture recognition
- 🔜 UI enhancement and packaging into wearable form

---

## 📸 Demo (coming soon...)
