---

---
# Rules And Regulations

---

**Assembly & Venue Requirements**

- Circuit assembly and presentations must be completed at the venue.
- Presentations can be in any format - not necessarily PowerPoint. You may use Obsidian, markdown, or any other documentation format you prefer.

**Component Usage**

- Only components listed in your submitted BOM may be used in your circuit or prototype. Using any unlisted component will result in **disqualification**.
- If you wish to change any component:
    - Present the new component to the organizers
    - Specify which item you want to replace
    - Update your BOM accordingly
    - Ensure it still fits within the 5-sensor limit

**Problem Statement Selection**

- You must choose one of the 5 problem statements provided.
- The selected problem statement must be clearly mentioned during your presentation.

**Penalties**

- **Budget violation**: If your total BOM exceeds the ₹1500 limit, **5 points will be deducted for every ₹25 over the limit**.
- **Sensor limit violation**: If you use more than 5 sensors, **10 points will be deducted per additional sensor**.

**Judging Process**

- You must answer any questions asked by the judges during evaluation.
- Teams will be evaluated based on the following criteria:

|**Criteria**|**Maximum Marks**|
|---|---|
|Innovation & Creativity|25|
|Functionality|25|
|Practical Impact|20|
|Budget & Constraint Adherence|15|
|Presentation & Demo|15|
|**Total**|**100**|

**Competition Timeline**

- **Total Duration**: 6 hours (10:00 AM - 4:00 PM)
- **Includes**: 1-hour lunch break
- **Final 30 minutes**: Reserved for judge evaluation and results

**Final Notes**

- Penalties will be applied after initial scoring
- The team with the highest final score will be declared the winner
- All decisions made by the organizers are final
-----
# 🎯 DETAILED PROBLEM STATEMENTS

---

## 1. ResQTech – Emergency Detection and Alert Systems 🚨

### Problem Statement

Design an intelligent emergency detection system that can automatically identify potential life-threatening situations and provide immediate alerts to save lives and prevent property damage.

### Real-World Context

> Every year, thousands of lives are lost due to delayed emergency response. Your system should detect emergencies like fires, gas leaks, medical emergencies, or accidents and provide instant alerts to users, family members, or emergency services.

### Expected Deliverables

- [ ]  Automatic hazard detection with at least 2 different sensors
- [ ]  Multi-level alerting (local alarm + remote notification)
- [ ]  Battery backup consideration for power failures
- [ ]  User-friendly interface for configuration and monitoring

### Hardware Suggestions

`MQ2/MQ135 (gas)` • `DHT11 (temperature)` • `vibration sensor` • `buzzer` • `LED indicators` • `ESP32/Arduino`

### Success Criteria

⏱️ **System should detect emergencies within 10 seconds and trigger alerts within 15 seconds**

---

## 2. GuardianNode – Smart Home Security Systems 🏠

### Problem Statement

Develop an affordable yet effective smart security system that protects homes from intrusions while providing real-time monitoring and control capabilities to homeowners.

### Real-World Context

> Traditional security systems are expensive and require professional installation. Your system should provide robust security features at a fraction of the cost while being easy to install and manage.

### Expected Deliverables

- [ ]  Multi-point monitoring system covering at least 3 entry points
- [ ]  User authentication mechanism (RFID, keypad, or app-based)
- [ ]  Real-time notifications to homeowner's device
- [ ]  Tamper detection and backup communication methods

### Hardware Suggestions

`PIR motion sensor` • `magnetic door switches` • `RFID/keypad module` • `servo motor` • `buzzer` • `ESP32/Arduino`

### Success Criteria

⏱️ **System should detect intrusions within 3 seconds and send alerts within 10 seconds**

---

## 3. HealthBridge – Affordable Health and Wellness Monitoring 💓

### Problem Statement

Create a comprehensive health monitoring device that tracks vital signs and wellness metrics, making healthcare monitoring accessible and affordable for everyone, especially in rural or underserved communities.

### Real-World Context

> Healthcare is expensive and often inaccessible. Your device should provide continuous health monitoring, early warning systems for health issues, and promote preventive healthcare practices.

### Expected Deliverables

- [ ]  Continuous monitoring of at least 2 health parameters
- [ ]  Abnormality detection with customizable thresholds
- [ ]  Data visualization and historical tracking
- [ ]  Emergency alert system for critical health events

### Hardware Suggestions

`Pulse sensor` • `accelerometer` • `temperature sensor` • `RTC module` • `LCD/OLED display` • `buzzer`

### Success Criteria

📊 **System should provide accurate readings within ±5% of medical-grade devices**

---

## 4. AgroAssist – Smart Farming and Resource Optimization 🌱

### Problem Statement

Design an intelligent agricultural monitoring and automation system that helps farmers optimize crop yield while conserving water and energy resources, especially targeting small-scale and resource-constrained farmers.

### Real-World Context

> Modern farming requires precision and efficiency to feed growing populations while conserving resources. Your system should automate farming decisions, reduce manual labor, and maximize crop productivity.

### Expected Deliverables

- [ ]  Multi-parameter monitoring (soil moisture, temperature, humidity, light)
- [ ]  Automated irrigation system with smart scheduling
- [ ]  Threshold-based alerts for critical conditions
- [ ]  Historical data logging for farming pattern analysis

### Hardware Suggestions

`Soil moisture sensor` • `DHT11` • `LDR` • `water pump with relay` • `RTC` • `ESP32/Arduino`

### Success Criteria

💧 **System should reduce water consumption by 30% while maintaining or improving crop health indicators**

---

## 5. EcoTrack – Environmental Sensing and Monitoring 🌍

### Problem Statement

Build a comprehensive environmental monitoring system that tracks pollution levels, resource consumption, and environmental health indicators to promote sustainable living and environmental awareness in communities.

### Real-World Context

> Environmental degradation affects everyone, but many people lack awareness of their environmental impact. Your system should provide real-time environmental data and encourage sustainable practices.

### Expected Deliverables

- [ ]  Real-time environmental sensing of at least 3 parameters
- [ ]  Data visualization with easy-to-understand metrics
- [ ]  Threshold-based warnings for dangerous levels
- [ ]  Sustainability recommendations based on collected data

### Hardware Suggestions

`MQ135 (air quality)` • `sound sensor` • `current sensor` • `ultrasonic sensor` • `DHT11` • `ESP32/Arduino`

### Success Criteria

🌿 **System should provide environmental readings accurate enough to guide personal or community decisions**

---

## 📋 Quick Reference

|Problem Track|Primary Focus|Key Sensors|Target Impact|
|---|---|---|---|
|**ResQTech**|Emergency Detection|Gas, Temperature, Vibration|Life Safety|
|**GuardianNode**|Home Security|PIR, Door Switch, RFID|Property Protection|
|**HealthBridge**|Health Monitoring|Pulse, Motion, Temperature|Healthcare Access|
|**AgroAssist**|Smart Farming|Soil, Climate, Light|Resource Efficiency|
|**EcoTrack**|Environmental|Air Quality, Sound, Energy|Sustainability|