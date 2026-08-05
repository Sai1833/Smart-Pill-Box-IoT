
# 💊 Smart QR Pill Box – IoT Edition

### American Version | ESP32 + Bluetooth | End-to-End Product

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Microcontroller-ESP32-blue?style=for-the-badge&logo=espressif" />
  <img src="https://img.shields.io/badge/Connectivity-Bluetooth-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Healthcare%20IoT-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Internship-Blue%20Planet%20Infosolutions-red?style=for-the-badge" />
</p>

<p align="center">
  <b>A complete smart medication monitoring system designed, fabricated, assembled, and delivered as a working product.</b><br>
  From sensor research → PCB design & manual fabrication → 3D enclosure → battery integration → final tested unit.
</p>

---

## 🌟 Project Vision

Medication non-adherence is a silent global problem.  
This **Smart QR Pill Box** was built to solve it with a practical, portable, and intelligent American-style design.

The system detects when pills are taken from individual compartments and communicates the status via **Bluetooth**, enabling real-time monitoring and future smart features.

---

## ✨ Key Highlights

| Feature                        | Details                                              |
|--------------------------------|------------------------------------------------------|
| 📦 **10 Pill Bays**            | Final production-ready 10-slot design                |
| 📡 **Bluetooth Connectivity**  | Real-time status via ESP32 Bluetooth                 |
| 🔋 **Rechargeable Power**      | 3.7V Li-Ion + TP4060 + MT3608 boost                  |
| 🛠️ **Custom PCB**             | Schematic → Layout → Manual etching → Soldering      |
| 🖨️ **3D Enclosure**           | AutoCAD designed + Laser-cut acrylic finish          |
| 📱 **QR Ready**                | Designed for QR-based medicine identification        |
| 🧪 **Fully Tested**            | Office-level validation + final product delivery     |

---

## 🧠 How It Works


Pill Taken → Conductive detection (Aluminium foil) → ESP32 senses change → 
Bluetooth transmits status → Companion device / future app receives data


The bottom of each compartment uses aluminium foil as a conductive layer. When a pill bottle or compartment is accessed, the system registers the change and updates the status over Bluetooth.

---

## 📁 Repository Structure

Smart-Pill-Box-IoT/
│
├── 01-Simulations/          # Circuit simulations (IR / Button / Touch)
├── 02-Prototype/            # Cardboard prototypes & early testing
├── 03-PCB_Design/           # PCB hardware + fabrication process
├── 04-3D_Design/            # AutoCAD models & enclosure design
├── 05-Final_output/         # Final product photos, videos & laser cutting
├── 06-Documentations/       # Internship reports & testing documents
└── 07-Code/                 # ESP32 firmware


---

## 🔌 Hardware Stack

- **Microcontroller**: ESP32 DevKit V1
- **Connectivity**: Bluetooth
- **Power System**:
  - 3.7V Li-Ion / LiPo battery
  - TP4060 charging module
  - MT3608 boost converter
- **Detection**: Aluminium foil conductive layer
- **Enclosure**: Custom 3D-designed + Laser-cut acrylic (blue shiny finish)
- **PCB**: Multiple versions designed & fabricated (final 10-slot)

---

## 🛠️ Complete Product Development Journey

| Phase                  | What Was Done                                      | Outcome                     |
|------------------------|----------------------------------------------------|-----------------------------|
| **Research**           | Sensor study, QR concept, LLM/SLM feasibility      | Technology selection        |
| **Simulation**         | Multi-configuration circuits (6/10-way)            | Validated sensing methods   |
| **Prototyping**        | Cardboard models + component assembly              | Working proof-of-concept    |
| **PCB Design**         | Schematic → Layout → Dimension optimization        | Multiple PCB revisions      |
| **Manual Fabrication** | Toner transfer + FeCl₃ etching + drilling          | Hands-on PCB manufacturing  |
| **Assembly**           | ESP32 soldering + conductive interface             | Fully functional hardware   |
| **3D Design**          | Base, top, phone holder, slot alignment            | Enclosure ready for printing|
| **Power Integration**  | Battery + charging + boost modules                 | Portable & rechargeable     |
| **Final Assembly**     | Fitting, adhesives, laser cutting, aesthetics      | Product-level finish        |
| **Testing & Delivery** | Office testing + courier to Pune office            | Successfully delivered      |

---

## 💻 Firmware

Located in `07-Code/`

The firmware runs on ESP32 and handles:
- Pill compartment status detection
- Bluetooth communication
- Real-time status reporting

> Update credentials as needed before flashing.

---

## 📸 Project Gallery

Explore the full visual journey:

- **Simulations** → `01-Simulations/`
- **Early Prototypes** → `02-Prototype/`
- **PCB Fabrication Process** → `03-PCB_Design/PCB_Hardware/`
- **3D Designs** → `04-3D_Design/`
- **Final Product** → `05-Final_output/`

---

## 🚀 Future Roadmap

- [ ] Mobile App (Bluetooth pairing + medication schedule)
- [ ] QR code scanning for medicine identification
- [ ] Cloud logging & caregiver dashboard
- [ ] Missed dose alerts & reminders
- [ ] LLM/SLM assisted smart suggestions
- [ ] Multi-user support

---

**Internship Details**  
**Company**: Blue Planet Infosolutions Pvt Ltd (Pan Health)  
**Domain**: Embedded System Development  
**Duration**: June 2025 – December 2025  
**Mentor**: Avi Kulkarni Sir  

---

## 📄 Documentation

Full internship completion report and task-wise attachments are available in the  
[`06-Documentations`](./06-Documentations) folder.

---

<p align="center">
  <b>Built with precision. Tested in real conditions. Delivered as a product.</b><br>
  <i>Helping people never miss their medicine — one smart box at a time.</i>
</p>

<p align="center">
  ★ Star this repository if you find it useful ★
</p>
