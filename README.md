# Autonomous Hospital Utility Robot Prototype using Arduino

[![Platform: Arduino](https://img.shields.io/badge/Platform-Arduino%20Uno-00979C.svg?logo=arduino&logoColor=white)]()
[![Language: C/C++](https://img.shields.io/badge/Language-Embedded%20C%2B%2B-00599C.svg)]()
[![Sensors: HC-SR04 & Telemetry](https://img.shields.io/badge/Sensors-HC--SR04%20%7C%20DHT11-blue.svg)]()

> An autonomous embedded utility robot designed for indoor hospital ward assistance, combining ultrasonic distance sensing for collision-free path navigation, ambient environmental telemetry, and PWM differential DC drive actuation.

---

## 👤 Author
* **J Shreyas Aradhya** — Electronics & Communication Engineering

---

## 🤖 System Features & Hardware
* **Microcontroller**: Arduino Uno (ATmega328P).
* **Obstacle Detection**: HC-SR04 Ultrasonic Sensor with servo scanning sweep (Left, Center, Right).
* **Motor Driver**: L298N Dual H-Bridge driving 2x DC Gearmotors with PWM speed regulation.
* **Environmental Telemetry**: DHT11 Temperature & Humidity sensor monitoring ward thermal comfort.
* **Autonomous Collision Avoidance**: Continuous distance evaluation ($d_{thresh} = 20\text{ cm}$); triggers pivot turn maneuver when obstacle is encountered.

---

## 📁 Repository Structure
```
├── src/
│   └── hospital_robot.ino            # Complete embedded Arduino C++ firmware
├── schematics/
│   └── pin_mapping.md                # Pin connection and circuit wiring tables
├── .gitignore
├── LICENSE
└── README.md
```
