# Disaster Prediction IoT Sensor Board

An ESP32-based real-time environmental monitoring board designed for localized disaster prediction (cyclones, floods, heatwaves).

## Core Requirements & Components
- **Microcontroller:** ESP32-WROOM-32 module (WiFi and Bluetooth enabled)
- **Power Supply:** USB-C port (5V input) with an onboard 3.3V LDO voltage regulator circuit
- **Core Environmental Sensors:**
  - DHT22 (Temperature and Relative Humidity sensor)
  - BMP180 (Atmospheric Pressure sensor via I2C protocol)
- **Additional Sensors:**
  - Rain Sensor module (analog output interface for precipitation tracking)
  - Anemometer / Wind Speed sensor input (pulse / analog input)
- **Alert & Feedback Peripherals:**
  - Piezo Buzzer for local audio alarm warnings
  - Status Indicator LEDs (Power ON and Alert Status)
- **Form Factor & Layout Constraints:**
  - Compact 2-layer PCB layout
  - Include clear mounting holes suitable for an outdoor IoT enclosure