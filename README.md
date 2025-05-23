# Arduino WebSocket LED Control 🌐💡

A simple IoT project controlling an LED remotely using Arduino Mega, WebSockets, and Ngrok tunneling.

This project is part of my ongoing practice to learn and experiment with software-hardware connectivity, focusing on controlling hardware remotely. It serves as a bridge between an Arduino and a web server, enabling real-time communication via WebSockets. The system provides a foundation for remotely controlling devices like LEDs or other components connected to the Arduino.

The main goal of this project is to enhance my understanding of how software and hardware can interact seamlessly and how to control hardware over the internet. This is a step toward mastering the art of IoT (Internet of Things) systems, and it provides hands-on experience with real-time communication, embedded systems, and web development.

## 📝 Overview
- Arduino Mega connects to a WebSocket server
- Remote clients can turn an LED on/off via WebSocket commands
- Ngrok provides secure public URL to local server (no port forwarding needed)

- ## 💻 Software Setup
1. **Arduino IDE**:
   - Install [WebSockets library](https://github.com/Links2004/arduinoWebSockets)
   - Upload `arduino_ws_led.ino` (change `ssid`/`password` for your WiFi)

2. **Node.js Server**:
   ```bash
   npm install ws  # WebSocket library
   node server.js  # Starts local WebSocket server

## 🌟 Features
  - Real-time LED control from any device
  - WebSocket protocol for bidirectional communication
  - No-IP solution using Ngrok
