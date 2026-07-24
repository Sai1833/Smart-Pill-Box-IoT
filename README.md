# Smart-Pill-Box-IoT
# 💊 Smart Pill Box IoT

An **IoT-based Smart Pill Box** that helps users take medicines on time through automatic reminders and real-time monitoring. The system uses an **ESP32** to detect pill box usage, send notifications, and update medicine status over Wi-Fi.

---

## 📖 Overview

The Smart Pill Box is designed to improve medication adherence by reminding users to take medicines at the correct time. It also records whether the medicine compartment has been opened and uploads the information to the cloud, allowing caregivers or users to monitor medication history remotely.

This project is suitable for elderly people, patients with regular medication schedules, and home healthcare applications.

---

## ✨ Features

- 💊 Automatic medicine reminders
- 📶 Wi-Fi connectivity using ESP32
- 🔔 Buzzer and LED notifications
- 📦 Multiple medicine compartments
- 📊 Real-time monitoring through IoT
- ☁️ Cloud data logging
- ⚡ Portable and low-power design

---

## 🛠️ Hardware Components

- ESP32 Development Board
- Touch/Conductivity Sensors
- Buzzer
- LEDs
- Li-ion Battery
- TP4056 Battery Charging Module
- MT3608 Boost Converter
- Custom PCB

---

## 💻 Software Requirements

- Arduino IDE
- Embedded C/C++
- ESP32 Board Package
- Firebase / Blynk / Custom IoT Platform

---

## ⚙️ How It Works

1. Fill the pill box with medicines.
2. Set the medicine schedule.
3. At the scheduled time, the buzzer and LED alert the user.
4. When the compartment is opened, the sensor detects the action.
5. The ESP32 sends the status to the cloud using Wi-Fi.
6. The medicine history can be viewed remotely.

---

## 📂 Project Structure

```
Smart-Pill-Box-IoT/
│
├── Firmware/
│   ├── ESP32_Code/
│   └── Libraries/
│
├── Hardware/
│   ├── Circuit_Diagram/
│   ├── PCB_Design/
│   └── Components/
│
├── Images/
│
├── Documentation/
│
└── README.md
```

---

## 🚀 Applications

- Home Healthcare
- Elderly Care
- Hospitals
- Clinics
- Patient Medication Monitoring
- IoT Healthcare Systems

---

## 🌟 Advantages

- Helps prevent missed medication
- Easy to use
- Portable design
- Real-time monitoring
- Low-cost solution
- Suitable for patients of all ages

---

## 🔮 Future Enhancements

- Mobile Application
- SMS & WhatsApp Notifications
- Voice Assistant Integration
- AI-Based Medicine Scheduling
- Caregiver Alerts
- Battery Status Monitoring

---

## 📸 Project Images

> Add project images inside the `Images` folder.

Example:

```md
![Prototype](Images/prototype.jpg)

![PCB Design](Images/pcb.jpg)

![Circuit Diagram](Images/circuit.png)
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository.
2. Create a new branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## 📜 License

This project is intended for **educational and research purposes**.

---

## 👨‍💻 Author

**Sai Teja**

Embedded Systems & IoT Developer

---

⭐ **If you like this project, give it a Star and share it with others!**
