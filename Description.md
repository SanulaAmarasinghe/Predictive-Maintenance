# Predictive Maintenance System with PowerApps and Power BI

This repository contains the implementation of a **Predictive Maintenance System** developed using **PowerApps** for user interaction and **Power BI** for data analysis. The system leverages IoT sensors and cloud storage to monitor the health of equipment and predict potential failures, enabling timely maintenance actions. The data is visualized through Power BI for insights and decision-making.

## Features

- **Real-Time Monitoring:** Monitor equipment status and key performance indicators (KPIs) in real-time through a **PowerApps** mobile application.
- **Predictive Analysis:** The system uses IoT sensors to collect data, and predictive models are employed to forecast potential failures based on historical and real-time data.
- **Power BI Dashboard:** Visualize sensor data, maintenance trends, and predictive maintenance insights through **Power BI** for better decision-making.
- **PowerApps Integration:** The mobile app, built using PowerApps, allows technicians or operators to interact with the system, track equipment health, and log maintenance tasks.
- **Cloud Integration:** IoT data, maintenance logs, and predictive analytics are stored and processed using cloud services (e.g., Azure, AWS, or Google Cloud).

## Technologies Used

- **PowerApps:** For building the mobile application and creating a user-friendly interface for maintenance teams to interact with equipment data.
- **Power BI:** For data visualization and analysis, enabling users to monitor equipment performance, trends, and predictions.
- **IoT Sensors:** For monitoring the condition of equipment (e.g., temperature, vibration, humidity) and detecting anomalies that could indicate potential failures.
- **Cloud Services:** Used for storing data from IoT sensors, maintenance logs, and predictive analytics (e.g., Azure, AWS, or Google Cloud).
- **Machine Learning/AI (Optional):** For predictive maintenance models that forecast equipment failures based on collected data.

## Setup

### Hardware Setup

1. **IoT Sensors**: Install IoT sensors on the equipment to monitor various parameters such as:
   - **Temperature**
   - **Vibration**
   - **Humidity**
   - **Pressure** (optional)

2. **ESP32 (or similar microcontroller)**: Used to collect data from the sensors and transmit it to the cloud.

3. **Predictive Maintenance Algorithm**: Develop or integrate predictive algorithms to analyze sensor data and predict failures based on historical trends.

### Cloud Storage and Data Processing Setup

1. Set up **cloud storage** (e.g., **Azure IoT Hub**, **AWS IoT**, or **Google Cloud IoT**) to store data from IoT sensors.
2. Use cloud services to process sensor data, store historical maintenance data, and apply machine learning models for predictive analytics.

### PowerApps Setup

1. Clone this repository to your local machine.
2. **Create a PowerApps app** to:
   - Display real-time equipment data (e.g., temperature, vibration levels, etc.).
   - Show alerts for predictive maintenance based on sensor readings and predictions.
   - Log maintenance activities and track equipment health status.

3. Connect PowerApps to your cloud service to retrieve sensor data, maintenance logs, and predictive maintenance results.

4. Test the app on your mobile device and ensure it can retrieve data from the cloud and trigger actions based on equipment conditions.

### Power BI Setup

1. **Connect Power BI** to your cloud service or database where sensor data and maintenance logs are stored.
2. Create **Power BI dashboards** to visualize:
   - Real-time equipment health data (temperature, vibration, etc.).
   - Historical data on equipment performance and failure trends.
   - Predictive maintenance insights, including the likelihood of failure for each equipment.
   
3. Publish the Power BI reports and integrate them into PowerApps (optional) for a unified experience.

