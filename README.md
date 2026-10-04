# Smart Energy Management System for Residential Buildings

## About the Project

This project is a safe, low-voltage prototype developed to demonstrate how energy usage and basic home conditions can be monitored and controlled in a residential environment.

The system uses sensors to monitor factors such as room temperature, human presence, light conditions, and electrical energy. Based on the collected information, connected low-voltage loads can be controlled to avoid unnecessary energy usage.

## Objective

The main objective of this project is to develop a simple and low-cost energy management system that can improve energy awareness and demonstrate automatic control of electrical loads in a residential environment.

## How It Works

The sensors collect information about the room and its conditions. The microcontroller processes the sensor readings and controls the connected low-voltage loads through a relay module.

The system can use human presence and light conditions to support automatic control, while energy-related measurements can be monitored for analysis.

### Basic Working

**Sensors → ESP32 → Data Processing → Relay Control → Low-Voltage Loads**

## Main Components

- ESP32
- INA219 Current/Voltage Sensor
- PIR Motion Sensor
- LDR
- DHT22 Temperature and Humidity Sensor
- 4-Channel 5V Optocoupler Relay Module
- LCD Display
- Buzzer
- 5V LED Lamp
- 5V Pump
- 5V Fan
- 5V Power Supply

## Parameters Monitored

- Electrical voltage and current
- Room temperature
- Humidity
- Human presence
- Light conditions

## Features

- Low-voltage prototype
- Energy monitoring
- Motion-based control
- Light-based control
- Temperature and humidity monitoring
- Automatic load control
- LCD display
- Buzzer indication
- Safe prototype approach

## Testing

The prototype was tested by monitoring the sensor readings and checking the response of the connected low-voltage loads.

Different conditions were used to observe how the system responds to human presence, light levels, and environmental conditions.

## Results

The prototype demonstrates the basic concept of monitoring residential conditions and controlling low-voltage electrical loads based on sensor inputs.

The testing results, project images, and supporting files are included in this repository.

## Project Images

Images of the prototype, circuit connections, sensor setup, and testing are included in the repository.

## Future Improvements

The system can be further improved by adding:

- IoT-based remote monitoring
- Mobile application control
- Detailed energy consumption analysis
- Smart scheduling
- Improved automation logic
- Historical energy usage graphs
- AI-based energy-saving recommendations

## Safety Note

This project is developed as a **5V low-voltage prototype** for demonstration and learning purposes. It does not directly control household mains electricity.

## Conclusion

This project demonstrates how sensors, energy monitoring, and automatic control can be combined to create a basic smart energy management system for residential applications.

The prototype provides a foundation for developing more advanced energy-efficient and smart home solutions.

## Project Status

Completed
