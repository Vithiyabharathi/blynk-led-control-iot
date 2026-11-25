# LED Light Control with Blynk App Using IoT

An IoT-based smart home automation prototype that enables remote ON/OFF control of LED lighting over Wi-Fi using the Blynk mobile application.

## Tech Stack & Hardware
- **Software / Platform:** Arduino IDE (C++), Blynk IoT App
- **Hardware:** NodeMCU (ESP8266), LED, Resistor, Breadboard

## How It Works
1. Connects NodeMCU (ESP8266) to a local Wi-Fi network using Blynk authentication credentials.
2. Maps virtual pins in the Blynk mobile app to GPIO pins on the microcontroller.
3. Toggles the LED state in real time from anywhere via the mobile dashboard.
