# USB-C Multifunction Converter Board

This repository contains the schematic for a **USB-C multifunction converter board**, designed using **EasyEDA**. The board integrates several subsystems including audio, power regulation, USB bridging, and Ethernet conversion—making it ideal for custom embedded interfaces, docking stations, and portable systems.

---

## 🔧 Key Functional Modules

### 1. USB Type-C Audio + MIC Codec
- Integrated stereo headphone output and microphone input
- Codec supports USB Class audio functionality
- Perfect for headsets and voice-enabled embedded devices

### 2. 12V to 5V Regulator
- Based on AMS1117 or equivalent linear regulator
- Converts 12V input to regulated 5V for logic and USB components

### 3. USB Type-C to USB Type-A Converter
- Converts USB-C data to legacy USB Type-A interface
- Allows USB-C hosts to interface with USB 2.0/3.0 devices

### 4. LAN7800 USB to Ethernet
- USB 3.0 to Gigabit Ethernet bridge (LAN7800 chipset)
- Adds networking to systems via USB-C port

### 5. 12V to 28V Boost Converter
- DC-DC converter to step up 12V to 28V output
- Used for actuators, motor drivers, or sensors needing higher voltage

### 6. 5V to 3.3V Converter
- LDO or buck regulator for supplying low-power 3.3V logic devices

---

## 🧠 Applications
- Embedded networking and communication devices  
- Smart docking stations with USB-C interface  
- Custom audio-enabled control boards  
- Industrial or robotics systems with mixed-voltage domains  

---

## 📁 Repository Contents
- `Schematic (.json/.schdoc)` – Designed in EasyEDA  
- `README.md` – Full project documentation  
- `BOM.csv` – Bill of Materials  
- `PDF_Schematic.pdf` – Printable schematic overview (optional)  

---

## 👨‍💻 Author

**Muddessir Arif**  
📧 muddessirarif140174@gmail.com  
📞 +92 340 0586446  
🔗 [GitHub Profile](https://github.com/muddessirarif)

---

> ⚠️ This schematic is provided for prototyping and educational use only. Exercise caution when working with DC-DC converters and USB-C devices.
