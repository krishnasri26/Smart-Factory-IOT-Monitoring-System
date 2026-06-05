# Smart Factory IoT Monitoring System

## Overview

The Smart Factory IoT Monitoring System is an Industry 4.0-based solution designed to monitor and visualize factory parameters in real time using IoT technologies. The system collects data from multiple virtual sensors, processes the information through a microcontroller, and transmits it to the ThingBoard Cloud platform for remote monitoring and analysis.

The project is developed and tested using PICSimLab simulation software and programmed using Arduino IDE. A web-based dashboard provides real-time visualization of factory conditions, enabling efficient monitoring and decision-making.

---

## Objectives

* Monitor industrial parameters in real time.
* Simulate factory automation using virtual sensors.
* Upload sensor data to the cloud.
* Visualize factory status through a web dashboard.
* Demonstrate Industry 4.0 and Industrial IoT concepts.

---

## Features

* Real-time sensor monitoring
* Cloud-based data visualization
* Industrial parameter tracking
* Web dashboard analytics
* Remote monitoring capability
* PICSimLab virtual simulation
* IoT-based factory management
* Low-cost Industry 4.0 implementation

---

## Technologies Used

| Technology       | Purpose                |
| ---------------- | ---------------------- |
| Arduino IDE      | Programming            |
| PICSimLab        | Simulation Environment |
| ThingBoard Cloud | IoT Platform           |
| Web Dashboard    | Data Visualization     |
| MQTT Protocol    | Data Communication     |
| Wi-Fi Module     | Cloud Connectivity     |

---

## System Architecture

```text
+---------------------+
| Virtual Sensors     |
| Temperature         |
| Humidity            |
| Machine Status      |
| Energy Monitoring   |
+----------+----------+
           |
           v
+---------------------+
| Arduino Controller  |
+----------+----------+
           |
           v
+---------------------+
| MQTT Protocol       |
+----------+----------+
           |
           v
+---------------------+
| ThingBoard Cloud    |
+----------+----------+
           |
           v
+---------------------+
| Web Dashboard       |
| Real-Time Analytics |
+---------------------+
```

---

## Parameters Monitored

### Environmental Monitoring

* Temperature
* Humidity

### Machine Monitoring

* Machine Running Status
* Production Status
* Fault Detection

### Energy Monitoring

* Voltage
* Current
* Power Consumption

---

## Working Principle

1. Sensors continuously collect factory data.
2. Arduino processes the sensor readings.
3. Data is transmitted through Wi-Fi using MQTT protocol.
4. ThingBoard Cloud receives and stores the data.
5. Dashboard widgets display live factory information.
6. Operators monitor machine and environmental conditions remotely.
7. Alerts can be generated when abnormal conditions occur.

---

## Simulation Environment

The project is implemented using PICSimLab for hardware simulation.

### Simulated Components

* Arduino Board
* Temperature Sensor
* Humidity Sensor
* LEDs
* Switches
* Industrial Monitoring Sensors
* Wi-Fi Communication Module

---

## Software Requirements

* Arduino IDE
* PICSimLab
* ThingBoard Cloud Account
* MQTT Library
* WiFi Library
* Web Browser

---

## Dashboard Features

The ThingBoard dashboard displays:

### Live Monitoring

* Temperature Gauge
* Humidity Gauge
* Machine Status Indicator
* Power Consumption Meter

### Historical Analysis

* Data Charts
* Trend Graphs
* Event Logs

### Alerts

* High Temperature Alert
* Machine Fault Alert
* Excessive Power Consumption Alert

---

## Project Flow

```text
Start
   |
Read Sensor Data
   |
Process Parameters
   |
Connect to Wi-Fi
   |
Send Data to ThingBoard
   |
Update Dashboard
   |
Check Threshold Conditions
   |
Generate Alerts (If Required)
   |
Repeat
```

---

## Folder Structure

```text
Smart-Factory-IoT-Monitoring-System/
│
├── Arduino_Code/
│   ├── smart_factory.ino
│
├── Simulation/
│   ├── picsimlab_project.pzw
│
├── Dashboard/
│   ├── dashboard_images
│
├── Documentation/
│   ├── report.pdf
│
├── Images/
│   ├── system_architecture.png
│   ├── simulation_result.png
│
└── README.md
```

---

## Results

* Successful real-time factory monitoring.
* Reliable cloud communication.
* Live dashboard visualization.
* Remote access to factory parameters.
* Improved operational awareness.

---

## Applications

* Smart Manufacturing
* Industrial Automation
* Production Monitoring
* Predictive Maintenance
* Energy Management
* Industry 4.0 Demonstrations
* Academic Research

---

## Future Enhancements

* AI-Based Predictive Maintenance
* Machine Learning Analytics
* Mobile Application Integration
* Digital Twin Technology
* Edge Computing
* Multi-Factory Monitoring

---

## Authors

Krishna Srivastava

Department of Electronics and Communication Engineering

---

## License

This project is developed for educational, simulation, and research purposes.

---

## Acknowledgements

Special thanks to the Industry 4.0, IoT, and Smart Manufacturing communities for inspiring this project.
