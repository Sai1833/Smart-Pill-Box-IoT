
# Smart Pill Box IoT

An IoT-enabled Smart Pill Box designed to monitor medication adherence. The system detects when pills are taken from individual compartments and provides real-time status over Wi-Fi via a simple web interface.

## Project Overview

This project implements a complete end-to-end Smart Pill Box solution — from circuit simulation and cardboard prototyping to custom PCB fabrication, 3D enclosure design, laser-cut housing, and final working hardware.

The device monitors **16 pill compartments** using digital inputs and exposes their status (Taken / Replaced) through a lightweight web server running on an ESP32/ESP8266-class microcontroller.

### Key Features
- Real-time monitoring of 16 individual pill slots
- Wi-Fi connectivity with built-in web server
- Status reporting: each slot shows **TAKEN** or **REPLACED**
- Custom PCB design and fabrication
- 3D-designed enclosure with laser-cut parts
- Battery-powered with charging support
- Complete documentation of the development process

## Repository Structure


Smart-Pill-Box-IoT/
├── 01-Simulations/          # Circuit simulations (IR, Push Button, Touch Sensor)
├── 02-Prototype/            # Cardboard prototypes and early testing videos
├── 03-PCB_Design/           # PCB hardware photos + simulation files
│   ├── PCB_Hardware/
│   └── PCB_Simulation/
├── 04-3D_Design/            # AutoCAD 3D models and design images
│   ├── 3D_Design_Cad_Files/
│   └── 3D_Design_vids/
├── 05-Final_output/         # Final assembled device photos and videos
├── 06-Documentations/       # Internship reports and testing documents
├── 07-Code/                 # Firmware (main.c)
└── README.md


## Hardware

### Main Components
- Microcontroller with Wi-Fi (ESP32 / compatible)
- 16 digital input pins connected to compartment sensors/buttons
- Custom etched PCB
- Rechargeable battery + charging circuit
- Power switch
- Laser-cut / 3D-designed enclosure

### Pin Configuration (from firmware)
The firmware uses the following pins for the 16 slots:


32, 33, 25, 26, 27, 14, 12, 13, 23, 22, 21, 19, 18, 5, 4, 15


## Firmware

Located in `07-Code/main.c`.

### Features
- Connects to Wi-Fi
- Starts a web server on port 80
- Reads the state of all 16 slots
- Serves a plain-text status page at the root endpoint (`/`)

### Setup
1. Open `07-Code/main.c`
2. Replace the placeholders:
   ```c
   const char* ssid = "YOUR_WIFI_NAME";
   const char* password = "YOUR_WIFI_PASSWORD";
   
3. Upload the code to your ESP32 (or compatible board)
4. Open the Serial Monitor (115200 baud) to get the device IP address
5. Visit `http://<device-ip>/` in a browser to view the pill box status

### Example Output

Pill Box Status:

Slot 1: TAKEN
Slot 2: REPLACED
Slot 3: TAKEN
...


## Development Process

1. **Simulations** – Tested different sensing methods (IR, push buttons, touch sensors)
2. **Prototyping** – Built cardboard mock-ups to validate mechanical design
3. **PCB Design & Fabrication** – Designed and chemically etched a custom PCB
4. **3D Design** – Created enclosure models in AutoCAD
5. **Final Assembly** – Laser-cut housing, battery integration, and complete device

## Documentation

- Internship Completion Reports (Sai & Manu)
- Testing documentation

See the `06-Documentations/` folder for detailed reports.

## Future Improvements

- Mobile app integration
- Scheduled reminders / buzzer / LED indicators
- Cloud logging of adherence data
- Low-battery alerts
- Support for different compartment counts

## License

This project was developed as part of an internship. Feel free to use and modify it for educational purposes.




