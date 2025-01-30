# smarthome
# Home Automation System

## 📌 Introduction
This project is a **Home Automation System** using **Arduino**, which controls home appliances like **lights, fans, and doors** based on various environmental factors such as temperature, motion detection, gas leakage, and ambient light.

## ⚙️ Features
- **Automatic Lighting**: Controls bulbs based on room brightness.
- **Fan Speed Control**: Adjusts speed based on temperature.
- **Gas Leakage Detection**: Alerts and opens the door if gas levels are high.
- **Motion-Based Door Control**: Opens/closes doors using a PIR sensor.
- **LCD Display**: Shows system status in real time.

## 🔧 Components Used
| Component        | Quantity | Description |
|-----------------|----------|-------------|
| **Arduino**     | 1        | Microcontroller (Specify model) |
| **PIR Sensor**  | 1        | Detects human presence |
| **Ultrasonic Sensor** | 1 | Measures distance |
| **Gas Sensor**  | 1        | Detects harmful gases |
| **LDR Sensor**  | 1        | Detects ambient light |
| **Temperature Sensor** | 1 | Reads room temperature |
| **Servo Motors** | 2 | Controls door movement |
| **LCD Display (16x2)** | 1 | Displays system status |
| **Bulbs & Fans** | 2 each  | Appliances being controlled |

## 🛠️ Circuit Diagram
![Circuit Diagram](docs/Circuit_Diagram.png)

## 🚀 How It Works
1. **Light Control**: The LDR sensor detects light intensity and adjusts bulb brightness accordingly.
2. **Fan Control**: The fan speed varies depending on temperature readings.
3. **Gas Detection**: If gas levels exceed a threshold, it triggers an alarm and opens the door.
4. **Motion Detection**: The PIR sensor detects movement and opens/closes the door.
5. **LCD Display**: Shows real-time values of sensors and system status.

## ⏳ Setup & Upload Code
1. **Connect the components** as per the circuit diagram.
2. **Upload `home_automation.ino` to Arduino**.
3. **Power the system** and observe automatic operations.

## 🔖 License
This project is licensed under the **MIT License** - feel free to modify and improve!

---

## 📄 **Components_List.md**
```md
# Components List

## 🏠 Home Automation System - Required Components

| Component Name   | Type        | Quantity |
|-----------------|------------|----------|
| **Arduino Board** | Microcontroller | 1 |
| **PIR Sensor**  | Motion Sensor | 1 |
| **Ultrasonic Sensor** | Distance Measurement | 1 |
| **Gas Sensor**  | Safety Sensor | 1 |
| **LDR Sensor**  | Light Detection | 1 |
| **Temperature Sensor** | Temperature Monitoring | 1 |
| **Servo Motors** | Motor | 2 |
| **LCD Display (16x2)** | Display | 1 |
| **Bulbs** | Electrical Load | 2 |
| **Fans** | Electrical Load | 2 |
| **Resistors, Wires, Breadboard** | Miscellaneous | Various |

## 📝 Notes
- Ensure correct connections and check power requirements before use.
- Use **5V for Arduino** and appropriate relays for high-power devices.

---

## 📄 **LICENSE (MIT License)**
```md
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

(Full MIT license text...)
