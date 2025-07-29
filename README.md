# BLIND-STICK-IOT-

# 👁️ Smart Blind Stick for Visually Impaired

This project is an IoT-based smart blind stick designed to assist visually impaired individuals in navigating their environment safely. The system integrates multiple sensors and image recognition capabilities using Arduino Uno and ESP32-CAM. Real-time alerts, obstacle classification, and navigational assistance are provided via the Blynk IoT platform.

---

## 🔍 Project Overview

The smart blind stick detects obstacles such as humans, chairs, benches, vehicles, rods, and stones. It classifies them using an image recognition model and sends timely alerts and feedback to the user through vibration, sound, and smartphone notifications. The system is compact, portable, and designed to be user-friendly for day-to-day mobility support.

---

## 🛠️ Hardware Components

| Component             | Description                                       |
|----------------------|---------------------------------------------------|
| ESP32-CAM             | Captures real-time images and transmits data via Wi-Fi |
| Arduino Uno           | Controls sensors and executes main logic         |
| Ultrasonic Sensor     | Detects distance to obstacles                    |
| IR Sensor             | Detects nearby objects within a short range       |
| UV Sensor             | Detects ambient light conditions                 |
| Vibrator Motor        | Provides haptic feedback for navigation           |
| Buzzer                | Emits sound alert on obstacle detection           |
| Microphone & Speaker  | Delivers audio instructions or alerts             |
| Jumper Wires & Breadboard | Used for wiring the components               |
| Power Source (3.7V/5V Battery) | Portable power supply                   |

---

## 💡 Key Features

- Real-time image capturing and obstacle detection
- Object recognition: identifies chairs, humans, vehicles, etc.
- Obstacle distance measurement using sensors
- Vibration feedback for close-range obstacles
- Audio navigation guidance via speaker and microphone
- Real-time notifications and object info sent to Blynk app
- Works over Wi-Fi or Bluetooth using ESP32-CAM’s built-in modules

---

## 🧠 System Workflow

1. The ESP32-CAM continuously captures the surroundings.
2. Image recognition identifies the object type (chair, human, vehicle, etc.).
3. Sensors determine obstacle proximity.
4. Feedback is provided through:
   - Vibration motor (left/right direction guidance)
   - Buzzer (audible warning)
   - Audio guidance (e.g., "Obstacle on left, move right")
   - Notification to the Blynk app (object type and position)

---

## 📲 Blynk IoT App Configuration

1. Download and install the Blynk IoT app from the App Store or Google Play.
2. Create a new project and select “ESP32” as the device.
3. Copy the generated Auth Token sent to your registered email.
4. Add the following widgets to your Blynk dashboard:
   - Label (to display object type and location)
   - LED (for alert indication)
   - Notification or Image Button (for custom alerts)
5. Paste your Auth Token into your ESP32 code.

---

## 🔌 Wiring Overview

- Connect the Ultrasonic Sensor to Arduino Uno (Trig and Echo pins).
- Connect IR and UV sensors to digital pins on Arduino.
- Wire the vibrator motor and buzzer to appropriate output pins.
- Interface ESP32-CAM with FTDI module for programming.
- Connect ESP32-CAM’s TX/RX to Arduino if using I2C/UART for coordination.
- Power all components through a regulated 5V supply or battery.

---

## 🚀 Future Enhancements

- Integration with Google Text-to-Speech API
- Edge AI using TensorFlow Lite on ESP32-CAM
- GPS integration for real-time location tracking
- Emergency call/SMS system

---

## 🤝 Acknowledgements

This project is inspired by the need for accessible assistive technology for the visually impaired. It combines embedded systems, machine learning, and IoT to deliver a low-cost, effective solution.

---

  
## 📬 Contact Developer

For questions or collaboration:
- 📧 Email: thezainabjahan14@gmail.com
- 🌐 LinkedIn:

---

Thank you for checking out this project! Your feedback and contributions are welcome.


