# Arduino WebSocket LED Control 🌐💡

A simple IoT project controlling an LED remotely using Arduino Mega, WebSockets, and Ngrok tunneling.

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
