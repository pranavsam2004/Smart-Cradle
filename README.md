# Smart-Cradle

# Overview
The Smart Cradle is an advanced baby monitoring system designed to enhance the safety and comfort of infants. This system integrates multiple sensors with an Arduino microcontroller to monitor environmental conditions, detect crying, and ensure the baby’s well-being through real-time notifications and automated responses.

# Features
**Environmental Monitoring**: Continuously monitors temperature and humidity using a DHT sensor to maintain a comfortable environment.

**Cry Detection and Soothing:** Detects a baby's cry using a sound sensor and automatically activates a cradle-swinging mechanism to soothe the baby.

**Anti-Rollover Detection:** Uses a laser diode and light-dependent resistor (LDR) sensor to detect potential rollovers and captures real-time images via an ESP32 camera.

**Real-Time Notifications:** Sends immediate alerts to parents through Telegram for any anomalies or critical conditions.

**User-Friendly Dashboard:** Provides a visual interface via Node-RED for monitoring real-time data and trends.
# Technologies Used
**Arduino:** For sensor data acquisition and control.

**Sensors:** DHT (temperature and humidity), moisture sensor, sound sensor, laser diode, LDR.

**ESP32 Camera:** For capturing images in rollover detection scenarios.

**Node-RED: **For creating an interactive dashboard.

**Telegram API:** For real-time notifications.

# Hardware Requirements
**Arduino Board:** Arduino Uno or compatible.

**Sensors: **DHT sensor, moisture sensor, sound sensor, laser diode.

**ESP32 Camera: **For image capture.

**Additional Components:** Servo motor, resistors, wiring, breadboard.
