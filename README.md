🚗 RFID & IR Sensor Based Smart Parking System
An IoT-based Smart Parking System designed to automate vehicle entry, exit, and slot monitoring using RFID authentication and IR sensor-based slot detection. This system reduces manual intervention, prevents unauthorized access, and improves parking efficiency in commercial, residential, and institutional environments.

📌 Project Overview
The system integrates:
RFID Module – For secure vehicle authentication
IR Sensors – For real-time parking slot detection
Microcontroller (Arduino/ESP32) – For system control and processing
LCD Display – For slot availability status
Servo Motor – For automatic gate control
When a vehicle approaches the parking gate:
RFID card is scanned.
System verifies authorization.
If valid and slots are available, gate opens automatically.
IR sensors detect slot occupancy.
Available slot count updates dynamically on display.

🔧 Key Features
✔ Secure RFID-based vehicle authentication
✔ Real-time parking slot monitoring
✔ Automatic gate control using servo motor
✔ Live slot availability display
✔ Reduced human intervention
✔ Cost-effective and scalable design

🛠️ Components Used
Arduino UNO / ESP32
RFID Reader (RC522)
IR Sensors
Servo Motor
LCD Display (16x2)
Jumper Wires
Breadboard
Power Supply

⚙️ Working Principle
The system works on a two-layer mechanism:

1️⃣ Authentication Layer
RFID tag verifies whether the vehicle is authorized.

2️⃣ Detection Layer
IR sensors detect whether parking slots are occupied or vacant.
If both conditions are satisfied:
Gate opens.
Slot count decreases.
Display updates automatically.

💡 Applications
Shopping Malls
Hospitals
Corporate Offices
Educational Institutions
Residential Apartments

📈 Advantages
Minimizes traffic congestion
Saves time
Enhances security
Improves parking space utilization
Easy to implement and maintain

🚀 Future Enhancements
Mobile App Integration
Cloud-based Monitoring
Payment Gateway Integration
License Plate Recognition
Real-time Web Dashboard
