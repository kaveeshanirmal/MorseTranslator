# Morse Code Translator using ESP32

## 📌 Overview
This project is a **gesture-based Morse Code Translator** built using **ESP32**, which detects hand movements using an **ultrasonic sensor**, converts them into Morse code, and translates it into text. The translated text is displayed on an **LCD screen** and can also be accessed via a **real-time web interface** over Wi-Fi.

## 🚀 Features
- **Gesture-Based Morse Code Input**: Hand movements are detected and translated into Morse code.
- **Real-Time Translation**: Displays the translated text on an LCD screen.
- **Web Interface**: View real-time translations through a Wi-Fi-hosted dashboard.
- **Buzzer Feedback**: Indicates dots and dashes with audible tones.

## 🛠️ Components Used
- **ESP32** (Microcontroller)
- **LCD Display** (16x2)
- **Ultrasonic Sensor** (HC-SR04)
- **Buzzer**
- **LDR** (Light Dependent Resistor)
- **LEDs**
- **Jumper Wires & Breadboard**

## 📜 Code
The full source code is available in this repository: [View Code](./final.ino)

## 🔧 Installation & Setup
### 1️⃣ Hardware Connections
| ESP32 Pin | Component |
|-----------|-----------|
| GPIO 12  | Ultrasonic Sensor (Trig) |
| GPIO 13  | Ultrasonic Sensor (Echo) |
| GPIO 14  | Buzzer |
| GPIO 21, 4, 5, 18, 19, 22 | LCD (RS, EN, D4, D5, D6, D7) |

### 2️⃣ Software Setup
1. Install **Arduino IDE** with ESP32 board support.
2. Install required libraries:
   - `WiFi.h`
   - `ESPAsyncWebServer.h`
   - `LiquidCrystal.h`
3. Clone this repository and open the `.ino` file in Arduino IDE.
4. Upload the code to your ESP32.

### 3️⃣ Running the Project
1. Power up the ESP32.
2. Connect to the Wi-Fi network defined in the code.
3. Open a browser and enter the ESP32's **IP Address** to access the web interface.
4. Start using hand gestures to input Morse code!

## 🎯 Usage
- Place your hand within the detection range of the **ultrasonic sensor** to start input.
- Hold for **less than 1 second** for a **dot** and **more than 1 second** for a **dash**.
- Remove your hand to finalize the input and get the decoded character.
- The translated text appears on the **LCD screen** and **web interface**.

## 🤝 Contributors
This project was developed by a team of **10 members** including me.


#IoT #ESP32 #MorseCode #Arduino #EmbeddedSystems #TechForGood
