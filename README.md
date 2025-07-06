# Flood-monitoring-system

 
#  👉 Aim
To simulate an IoT-based flood monitoring system that can measure water level in real time and alert concerned authorities when the water level exceeds a critical threshold.


# 💡 Problem Statement
Floods are one of the most destructive natural disasters, causing severe damage to life and property. Early detection of rising water levels is crucial in preventing such disasters. The objective of this project is to design a system that:
•	Continuously monitors water level using sensors.
•	Provides real-time alerts when a certain threshold is crossed.
•	Displays information on an LCD screen.
•	Sends alerts using visual (LEDs) and audio (buzzer) indicators.


# 👉 Scope of the Solution
•	This system can be deployed at dams, riversides, or urban drainage points.
•	Can be further integrated with cloud-based dashboards for remote monitoring.
•	It helps authorities take timely preventive actions and evacuations.
•	Can be scaled up by integrating multiple sensors and locations.

# 🛠️ Required Components

Hardware:
•	ESP32 development board
•	Ultrasonic sensor (HC-SR04)
•	16x2 LCD display with I2C module
•	Red LED (for alert)
•	Green/Blue LED (for normal condition)
•	Buzzer
•	Jumper wires
•	Breadboard
Software:
Wokwi simulator (for testing circuit virtually)

# 👉 FlowChart Of The Code

Start  
↓  
Initialize LCD, pins, sensor  
↓  
Measure distance  
↓  
Is distance less than 100 cm?  
→ Yes:  
    Show “Danger”  
    Turn ON Red LED  
    Turn ON Buzzer  
→ No:  
    Show “Safe”  
    Turn ON Blue LED  
    Turn OFF Red LED  
↓  
Wait 1 second  
↓  
Repeat / Loop  










