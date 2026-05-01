# Elevated Sensors Bed Presence Mk1

[![CI](https://github.com/ElevatedSensors/bed-presence-mk1/actions/workflows/ci.yml/badge.svg)](https://github.com/ElevatedSensors/bed-presence-mk1/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/ElevatedSensors/bed-presence-mk1/main)](https://github.com/ElevatedSensors/bed-presence-mk1/commits/main)
[![GitHub issues](https://img.shields.io/github/issues/ElevatedSensors/bed-presence-mk1.svg)](https://github.com/ElevatedSensors/bed-presence-mk1/issues)

**Bed Presence Mk1** is an ESP32-C3 powered occupancy sensor designed for high-reliability detection within the Home Assistant ecosystem. It provides instantaneous state changes for bed-based automations, optimized for the modern smart home.

---

### 🚀 Quick Start
*   **Documentation:** [docs.elevatedsensors.com](https://docs.elevatedsensors.com)
*   **Web Installer:** [Install via Browser](https://docs.elevatedsensors.com/install)
*   **Hardware:** [Purchase at Elevated Sensors](https://elevatedsensors.com)

---

### 🛠 Technical Specifications
*   **Microcontroller:** ESP32-C3 (RISC-V)
*   **Firmware:** ESPHome 2026.4.3+ (v2.0.0 Infrastructure)
*   **Connectivity:** 2.4GHz Wi-Fi (Optimized for Mesh)
*   **Input Voltage:** 5V via USB-C

### 📦 Repository Structure
*   `/firmware`: ESPHome configuration files and custom components.
*   `/electronics`: Schematics, BOM, and PCB design files.
*   `/enclosure`: 3D printable STL files and assembly guides.
*   `/docs`: Product-specific troubleshooting and advanced configuration.

---

### 🔧 Installation & Usage
1.  **Direct Flash:** Use the [Elevated Sensors Web Installer](https://docs.elevatedsensors.com/install) to flash the latest firmware over USB.
2.  **Home Assistant:** The device will be automatically discovered via the ESPHome integration once connected to your network.
3.  **OTA Updates:** Devices running v2.0.0+ receive automatic update notifications via our Netlify-hosted manifest system.

---

### 🤝 Contributing & Support
*   **Issues:** Please report bugs or feature requests via the [GitHub Issues](https://github.com/ElevatedSensors/bed-presence-mk1/issues) tab.
*   **Discussions:** Join the community for setup help and automation ideas in [Discussions](https://github.com/ElevatedSensors/bed-presence-mk1/discussions).

### ⚖️ License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.  
Copyright (c) 2024-2026 Stephen Papierski / Elevated Sensors.
