# mining-helmet
🔥 Fire Safety Alert System for Mining Areas
Mining environments are highly vulnerable to fire hazards, making early detection and rapid response critical. This project presents a Fire Safety Alert System designed specifically for mining areas to detect fire incidents using sensors and alert personnel through visual display and location tracking.

🚀 Project Overview
The project integrates a smoke sensor, OLED display, and GPS module to:

Detect smoke (early indication of fire)

Warn workers via OLED display when an unsafe condition is detected

Display the GPS location on-screen, allowing quick access to coordinates for emergency response

🛠️ Features
🔍 Smoke Detection: Detects the presence of smoke in real-time using a smoke sensor.

⚠️ Safety Alerts: Displays “Not Safe” warning message on an OLED screen when fire or smoke is detected.

📍 GPS Location: Retrieves the current GPS coordinates of the device and displays them on the OLED screen.

🧑‍🚒 Emergency Support: Location can be conveyed to rescue teams for faster intervention.

🧩 Components Used
Smoke Sensor (e.g., MQ-2 or MQ-135)

OLED Display (0.96” I2C)

GPS Module (e.g., NEO-6M)

Microcontroller (e.g., Arduino/ESP32/ESP8266)

Connecting Wires and Power Source

💡 How It Works
The smoke sensor continuously monitors air quality.

Upon detecting smoke, the OLED displays a "Not Safe" message.

Simultaneously, the GPS module fetches the real-time location.

The coordinates are shown on the OLED so workers can inform emergency teams of their exact location.

📦 Future Improvements
Integrate a buzzer or alarm for audible alerts

Send SMS alerts to supervisors with location data

Store incident data in cloud or SD card for reporting

👨‍💻 Author
Your Guruprakash V K

