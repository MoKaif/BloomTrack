🌱 BloomTrack – Smart Plant Monitoring System

BloomTrack is an IoT-based plant health monitoring system that uses a NodeMCU, DHT11 temperature & humidity sensor, and a soil moisture sensor to collect real-time environmental data for a plant.
The data is sent to Firebase and displayed on a web dashboard, helping you track your plant’s well-being anytime, anywhere.
📸 Features

    🌡 Temperature & Humidity Monitoring – Get live readings from the DHT11 sensor.

    💧 Soil Moisture Tracking – Know when your plant needs watering.

    ☁ Cloud Connectivity – All data stored in Firebase for easy access.

    📊 Real-time Dashboard – Visualize sensor data via an intuitive web interface.

    🔄 Continuous Monitoring – Automatic updates without manual refresh.

🛠 Technologies Used

    Hardware

        NodeMCU ESP8266

        DHT11 Temperature & Humidity Sensor

        Soil Moisture Sensor

    Software & Services

        Arduino IDE

        Firebase Realtime Database

        HTML, CSS, JavaScript

🚀 How It Works

    Sensors Collect Data → The DHT11 and soil moisture sensor measure environmental conditions.

    NodeMCU Reads Sensors → Arduino code processes sensor readings.

    Data Sent to Firebase → NodeMCU uploads readings in real time via Wi-Fi.

    Dashboard Displays Data → A web app retrieves and displays values from Firebase.


⚡ Getting Started
1️⃣ Hardware Setup

    Connect DHT11 to NodeMCU (digital pin).

    Connect soil moisture sensor (analog output) to NodeMCU analog pin.

    Power via USB or external supply.

2️⃣ Software Setup

    Install Arduino IDE.

    Install ESP8266 board package in Arduino IDE.

    Install required libraries:

        DHT sensor library

        ESP8266WiFi

        Firebase ESP8266

    Open hardware/BloomTrack.ino in Arduino IDE.

    Add your Wi-Fi SSID, password, and Firebase credentials in the code.

    Upload the code to NodeMCU.

3️⃣ Dashboard Setup

    Open dashboard/index.html in a browser.

    Configure Firebase credentials in firebase-config.js.

    View real-time plant health stats.

👨‍💻 Contributors

    Fardeen Javed Kachawa

    Siddique Mohammad Kaif

    Om Mohan Deshmukh

    Sujal Ganesh Bhatt

📜 License

This project was developed as a Second Year Mini Project for the Bachelors in Computer Engineering course.
Feel free to use and modify for educational purposes.
