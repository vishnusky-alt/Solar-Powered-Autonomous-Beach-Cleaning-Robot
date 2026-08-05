# 🌊 Solar-Powered Autonomous Beach Cleaning Robot

An autonomous robot designed to detect, collect, and sort beach waste using artificial intelligence, computer vision, and renewable energy.

---

## 📖 Overview

The **Solar-Powered Autonomous Beach Cleaning Robot** is an eco-friendly solution for maintaining clean beaches. The robot autonomously detects waste using computer vision, collects it with a robotic arm, and automatically sorts it into **plastic** and **non-plastic** compartments.

The system is powered by a rechargeable battery supported by a solar panel, enabling sustainable operation. It supports both **Autonomous Mode** and **Manual Mode** through the Blynk IoT platform.

---

## ✨ Features

- ☀️ Solar-powered operation
- 🤖 Autonomous waste detection
- ♻️ Automatic waste sorting (Plastic / Non-Plastic)
- 🦾 Robotic arm for waste collection
- 📷 YOLOv8-based object detection
- 🚧 Ultrasonic obstacle avoidance
- 📱 Manual control using Blynk IoT
- 🚙 Differential drive mobility
- 🔋 Rechargeable battery with solar charging

---

## 🛠 Hardware Used

- Raspberry Pi 5
- ESP32 Development Board
- Raspberry Pi Camera Module
- L298N Motor Driver
- MG996R Servo Motors
- DC Geared Motors
- Ultrasonic Sensor
- Solar Panel
- Li-ion Battery Pack
- Robot Chassis

---

## 💻 Software Used

- Python
- Arduino IDE
- OpenCV
- YOLOv8
- Blynk IoT
- ESP32 Libraries

---

## ⚙️ Working Principle

1. The camera continuously captures the surrounding environment.
2. Raspberry Pi processes the images using YOLOv8 to detect waste.
3. The detected waste is classified as **Plastic** or **Non-Plastic**.
4. The robot navigates towards the detected object.
5. A robotic arm collects the waste.
6. The waste is deposited into the corresponding collection compartment.
7. Ultrasonic sensors detect obstacles and help avoid collisions.
8. The robot can also be manually controlled through the Blynk mobile application.

---

## 🚀 Operating Modes

### Autonomous Mode
- AI-based waste detection
- Automatic navigation
- Obstacle avoidance
- Waste collection
- Automatic waste sorting

### Manual Mode
- Remote control using Blynk
- Direction control
- Manual waste collection

---

## 📂 Repository Structure

```
docs/
hardware/
│── cad/
│── circuit/
│── datasheets/
firmware/
│── esp32/
│── raspberry-pi/
ai/
│── dataset/
│── model/
│── scripts/
images/
videos/
```

---

## 📸 Project Gallery

Project images, circuit diagrams, CAD models, and demonstration videos are available in the repository.

---

## 🔮 Future Improvements

- Multi-category waste sorting
- GPS-based navigation
- Autonomous path planning
- SLAM-based mapping
- Cloud monitoring dashboard
- Higher-capacity solar charging system

---

## 👨‍💻 Team

- Vishnu K N
- Jean Jossie
- Sana Fathim C A
- Jasim

**Guide:** Prof. Bindumol E K

Department of Electrical and Electronics Engineering

---

## 📄 License

This project is licensed under the MIT License.
