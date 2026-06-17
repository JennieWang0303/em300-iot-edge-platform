# EM300 Product Specification

This document summarizes the technical specifications of the EM300 (FlowPLC) industrial edge controller.

For the full datasheet and the latest documentation, please visit the DOWNLOAD tab on the page: https://en.iotrouter.com/product/em300-modular-industrial-edge-controller/

---

## 1. Core Hardware

- Processor: RK3506J (3 × Cortex-A7 @ 1.2GHz)
- RAM: 512 MB
- Storage: 4 GB
- Expandable Storage: Micro SD up to 128 GB
- RTC: Replaceable battery

---

## 2. Communication Interfaces

- 4G LTE (Cat.1 module, dual SIM support)
- Ethernet: 1 × WAN, 2 × LAN (10/100 Mbps)
- Wi-Fi: Wi-Fi 6 (802.11 a/b/g/n/ac/ax)
  - Dual band: 2.4GHz + 5GHz
  - Mode: STA + AP

---

## 3. USB Interface

- 1 × USB 2.0 (Type-C)

---

## 4. RS485 Interface

- 4 × RS485 ports
- Baud rate: 2400 – 921600 bps
- Data bits: 7 / 8
- Stop bits: 1 / 2
- Parity: None / Even / Odd
- Protection: Full Isolation + ESD + surge protection

---

## 5. Digital Input (DI)

- 2 × DI
- Input type: NPN / PNP
- Voltage detection: 12V / 24V
- Protection: Full Isolation + ESD + surge protection

---

## 6. Digital Output (DO)

- 2 × DO 
- Load capacity:
  - 0.6A @ 125VAC
  - 2A @ 30VDC
- Mechanical Endurance: 10⁶ operations
- Electrical Endurance: 10⁵ operations
- Protection: Full Isolation + ESD + surge protection

---

## 7. Power Supply

- Certification: CE
- UPS: Power-loss protection time: 10 s
- Input voltage: 9–36V DC
- Adapter: 12V / 1A
- Power consumption: ~200mA @ 12V
- Power-loss protection: ~10 seconds

---

## 8. Electrical

- Operating temperature: -40°C ~ 85°C
- Storage temperature: -40°C ~ 85°C
- Humidity: 0–95% RH (non-condensing)

---

## 9. Mechanical

- Size: 53 × 100 × 80 mm
- Enclosure: PC material
- Mounting: DIN rail
- Cooling: Passive

---

## 10. EMC Protection

- ESD: ±8kV air / ±4kV contact
- Surge: ±1kV
- EFT: ±2kV

---

## 11. Protocol Support

- Modbus RTU / TCP
- OPC UA
- IEC104 / IEC61850
- DL/T645 / HJ212 / CJ188
- PLC protocols (Siemens, Mitsubishi, Omron, AB, Delta)
- CNC protocols (Mazak, Haas, Heidenhain, etc.)

---

## 12. Software Features

- Node-RED visual programming
- Remote management
- Remote upgrade
- VPN / Firewall
- Store-and-forward
- Virtual serial port
