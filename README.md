# Autonomous Garden

An automated environmental monitoring and smart irrigation system designed to track water run-off rates, soil quality, and local weather patterns in suburban housing communities in Irvine, CA. The system uses custom hardware, ESP32 microcontrollers, and cloud-based data storage to optimize water regulation and pave teh way for smarter water usage and clean, sustainable practices.

## Features
• Multi-Sensor Data Collection: Real-time tracking of soil moisture, ambient temperature, and light intensity using I2C sensors.
• Environmental Analytics: Measures and analyzes local water run-off rates and regional weather patterns.
• Custom Hardware: Integrating custom schematics and a tailored PCB layout for seamless microcontroller and sensor connectivity.
• Wireless Data Logging: Utilizing an ESP32 microcontroller to transmit gathered data over Wi-Fi directly to a cloud database.
• Cloud Integration: Backed by Supabase for efficient data storage, enabling future predictive water regulation and optimal irrigation modeling.

## Tech Stack & Hardware
• Hardware & Electronics
    • Microcontroller: ESP32 (Wi-Fi enabled)
    • Sensors: 
        • STEMMA QT I2C Lux Sensor
        • SparkFun Qwiic Soil Moisture Sensor
        • Adafruit STEMMA I2C Capacitive Moisture Sensor
        • Grove - Water Sensor (RC0603JR)
    • PCB Design: Custom schematics and layout designed in KiCad
• Software & Cloud
    • Firmware: C/C++ (Arduino IDE)
    • Database: Supabase
    • Version Control: Git
