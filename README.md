🌞 Solar Station Project with ESPHome
🌟 Overview
Welcome to the Solar Station Project! This project harnesses the power of ESPHome and an ESP8266-based Wemos D1 Mini to monitor and control a solar station. It integrates a variety of sensors to measure and analyze environmental and operational data, providing a comprehensive view of your solar setup.

🔥 Features
Temperature and Humidity Monitoring: Get real-time updates on ambient conditions using a DHT22 sensor.
Battery Temperature Monitoring: Keep track of your battery's health with a Dallas temperature sensor.
Wind Speed Measurement: Measure wind speed in mph using an ADC-based sensor.
WiFi Signal Strength: Monitor the strength of your WiFi connection.
Uptime Monitoring: Know how long your solar station has been running.
Battery Remaining Percentage: Calculate the remaining battery life based on voltage levels.
Battery Usage: Track how much battery power has been used over the last 6 hours.
Storm Prediction: Get a heads-up on potential storms based on various environmental factors.
Battery Health Percentage: Assess the health of your battery considering voltage and temperature.
Solar Panel Efficiency: Measure how efficiently your solar panels are operating.
Air Quality Monitoring: Monitor the levels of particulate matter (PM1.0, PM2.5, PM10) in the air.
Solar Panel Power Output: Check the power output of your solar panels.
Power Loss Due to Resistance: Calculate power loss in the system due to resistance.
Indicator Light: An addressable LED strip indicates air quality and battery charge status.
🛠️ Hardware Requirements
Wemos D1 Mini (ESP8266)
DHT22 Temperature and Humidity Sensor
Dallas Temperature Sensor
ADC-based Wind Speed Sensor
PMS5003 Air Quality Sensor
INA219 Current Sensor
WS2812B Addressable LED Strip
🖥️ Software Requirements
ESPHome
Home Assistant (optional, for data integration and visualization)
