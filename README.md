# Satellite-Thermal-Fault-Detector
This project detects thermal anomalies in real satellite telemetry data using threshold-based fault flags. The data is sourced from **NASA PREFIRE(Polar Radiant Energy in the Far InfraRed Experiment)**, and the logic identifies possible temperature-related subsystem failures in components like batteries, command modules, and the IMU.

---

##  What It Does

- Loads real spacecraft telemetry from CSV files provided by earthdata.nasa.gov
- Extracts key thermal sensors
- Visualizes temperature trends over time
- Applies threshold logic to flag faults
- Counts and reports total fault events

---

##  Sensors Monitored

- Bus Temperature
- IMU Temperature
- Payload Command Temp
- Payload Power Temp
- Battery Temp

Each has custom fault thresholds applied to detect overheat or undercool scenarios.Due to the absence of public documentation on operational thermal limits for the specific satellite used (PREFIRE in this case), fault detection thresholds have been narrowed intentionally for demonstration and testing. 

---

##  Engineering Value in CUrrent Missions

Satellites rely on thermal stability. Identifying overheating trends early can prevent critical failures in orbit. This project is a simplified simulation of what onboard health-monitoring systems do in real missions — now in Python.

---

## 🚀 How to Use

### 1. Clone the Repository.
### 2. Use data from urs.earthdata.nasa.gov or use the uploaded data csv file to jumpstart simulations.


