# 🌞 Solar Station Project with ESPHome

## 🌟 Overview

Welcome to the Solar Station Project! This project harnesses the power of ESPHome and an ESP8266-based Wemos D1 Mini to monitor and control a solar station. It integrates a variety of sensors to measure and analyze environmental and operational data, providing a comprehensive view of your solar setup.

## 🔥 Features

- **Temperature and Humidity Monitoring**: Get real-time updates on ambient conditions using a DHT22 sensor.
- **Battery Temperature Monitoring**: Keep track of your battery's health with a Dallas temperature sensor.
- **Wind Speed Measurement**: Measure wind speed in mph using an ADC-based sensor.
- **WiFi Signal Strength**: Monitor the strength of your WiFi connection.
- **Uptime Monitoring**: Know how long your solar station has been running.
- **Battery Remaining Percentage**: Calculate the remaining battery life based on voltage levels.
- **Battery Usage**: Track how much battery power has been used over the last 6 hours.
- **Storm Prediction**: Get a heads-up on potential storms based on various environmental factors.
- **Battery Health Percentage**: Assess the health of your battery considering voltage and temperature.
- **Solar Panel Efficiency**: Measure how efficiently your solar panels are operating.
- **Air Quality Monitoring**: Monitor the levels of particulate matter (PM1.0, PM2.5, PM10) in the air.
- **Solar Panel Power Output**: Check the power output of your solar panels.
- **Power Loss Due to Resistance**: Calculate power loss in the system due to resistance.
- **Indicator Light**: An addressable LED strip indicates air quality and battery charge status.

## 🛠️ Hardware Requirements

- **Wemos D1 Mini (ESP8266)**: The main controller of the project.
- **DHT22 Temperature and Humidity Sensor**: Measures the ambient temperature and humidity.
- **Dallas Temperature Sensor**: Monitors the battery temperature.
- **ADC-based Wind Speed Sensor**: Measures the wind speed.
- **PMS5003 Air Quality Sensor**: Monitors particulate matter in the air.
- **INA219 Current Sensor**: Measures current and voltage from the solar panel and battery.
- **WS2812B Addressable LED Strip**: Provides visual indications for air quality and battery status.

## 🖥️ Software Requirements

- **ESPHome**: A system to control your ESP8266/ESP32 by simple yet powerful configuration files and control them remotely through Home Automation systems.
- **Home Assistant (optional)**: For integrating and visualizing the data from the solar station.

## 🔌 Hardware Setup

### Wemos D1 Mini (ESP8266) Connections

- **DHT22 Sensor**
  - VCC -> 3.3V
  - GND -> GND
  - Data -> D4

- **Dallas Temperature Sensor**
  - VCC -> 3.3V
  - GND -> GND
  - Data -> D5

- **Wind Speed Sensor**
  - Signal -> A0
  - GND -> GND

- **PMS5003 Air Quality Sensor**
  - VCC -> 5V
  - GND -> GND
  - TX -> D2
  - RX -> D1

- **INA219 Current Sensor (Solar Panel)**
  - VCC -> 3.3V
  - GND -> GND
  - SCL -> D7
  - SDA -> D6

- **INA219 Current Sensor (Battery)**
  - VCC -> 3.3V
  - GND -> GND
  - SCL -> D7
  - SDA -> D6

- **WS2812B Addressable LED Strip**
  - VCC -> 5V
  - GND -> GND
  - Data -> D8

### Power Supply

Ensure that your power supply can provide sufficient current for the Wemos D1 Mini and all connected sensors and peripherals. Typically, a 5V 2A power adapter is recommended.

## 🚀 Getting Started

1. **Clone the Repository**: Start by cloning this repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/solarstation.git
   ```

2. **Configure ESPHome**: Install ESPHome on your machine and configure it to connect to your ESP8266 device. Use the provided YAML configuration file for ESPHome.

3. **Upload the Configuration**: Connect your Wemos D1 Mini to your computer via USB and upload the ESPHome configuration.
   ```bash
   esphome run solarstation.yaml
   ```

4. **Connect the Sensors**: Follow the hardware setup instructions to connect all the sensors to the Wemos D1 Mini.

5. **Monitor the Data**: Once everything is set up and running, you can monitor the data via the ESPHome dashboard or integrate it with Home Assistant for advanced visualization and automation.

## 📚 Documentation

For more detailed information on ESPHome configurations and Home Assistant integrations, refer to the [ESPHome Documentation](https://esphome.io/) and [Home Assistant Documentation](https://www.home-assistant.io/).

## 🤝 Contributing

We welcome contributions to this project! Feel free to open issues or submit pull requests on GitHub. Together, we can improve and expand the capabilities of the Solar Station Project.

## 📧 Contact

If you have any questions or need further assistance, please open an issue on GitHub or contact me at prokyle123@gmail.com.

---

Feel free to copy and paste this into your `README.md` file on GitHub!
