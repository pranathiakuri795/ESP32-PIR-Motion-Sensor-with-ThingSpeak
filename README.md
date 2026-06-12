# ESP32 PIR Motion Sensor with ThingSpeak

## Project Overview

This project is an IoT-based Smart Motion Detection System developed using an ESP32 microcontroller, PIR Motion Sensor, and ThingSpeak Cloud Platform. The system detects human motion and sends the sensor data to the cloud through WiFi. The data is then displayed on the ThingSpeak dashboard in real time.

## Components Used

* ESP32 Microcontroller
* PIR Motion Sensor
* WiFi Connection
* ThingSpeak Cloud Platform
* Wokwi Simulator

## Working Principle

The PIR sensor detects human movement and sends a signal to the ESP32. The ESP32 reads the sensor value and connects to the internet using WiFi. The data is sent to the ThingSpeak cloud platform and displayed as a real-time graph. A value of 1 indicates motion detected, while 0 indicates no motion detected.

## Applications

* Home Security Systems
* Office Monitoring
* Smart Home Automation
* Motion-Based Lighting Systems
* Restricted Area Monitoring

## Output

The motion data is successfully uploaded to ThingSpeak and displayed as a real-time graph on the dashboard.

## Conclusion

The project successfully demonstrates motion detection and cloud-based monitoring using IoT technology. It helps in understanding sensor interfacing, WiFi communication, and real-time data visualization.
