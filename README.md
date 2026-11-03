🚗 Project Overview

CrashGuard is a Smart Vehicle-to-Vehicle (V2V) Communication System developed to reduce collision risks through wireless communication, distance monitoring, and automatic speed control.

The system consists of two prototype vehicles. When Vehicle 1 transmits braking information, Vehicle 2 receives the signal and adjusts its speed based on the distance between the vehicles.

🔧 Hardware Components

- ESP32 Microcontroller
- L298N Motor Driver
- nRF24L01 Wireless Communication Module
- HC-SR04 Ultrasonic Sensor
- DC Motors
- Buzzer
- LED Indicators
- Battery Supply
- Bluetooth Mobile Control

💻 Technologies Used

- Embedded C / Arduino C++
- Arduino IDE
- ESP32
- Bluetooth Communication
- nRF24L01 RF Communication
- Ultrasonic Sensor Interfacing

⚙️ Working Principle

1. Vehicle 1 wirelessly transmits its braking status.
2. Vehicle 2 receives the braking signal.
3. The ultrasonic sensor measures the distance between the vehicles.
4. Vehicle 2 reduces its speed according to the measured distance.
5. An emergency stop is triggered when the distance reaches a critically low level.

📏 Distance-Based Control

Distance| Vehicle Response
Above 50 cm| Normal speed
20–50 cm| Reduced speed
10–20 cm| Very low speed
Below 10 cm| Emergency stop

🎯 Applications

- Intelligent Transportation Systems
- Collision Avoidance
- Smart Mobility
- Automotive Embedded Systems
- V2V Communication Research

👨‍💻 Developer

Raju M
BE Electrical & Electronics Engineering
Don Bosco Institute of Technology, Bengaluru
Expected Graduation: 2027

⚠️ Disclaimer

This project is an academic prototype developed for educational purposes and is not intended for use in real vehicles.
