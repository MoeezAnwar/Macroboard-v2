# 🧠 Macroboard v2 — Compact 4-Key Mechanical Macro Pad with Rotary Encoder

![Macroboard Render](images/render.png)

**Macroboard v2** is a compact, hot-swappable **4-key mechanical macro pad** featuring a high-quality rotary encoder, designed by **Moeez Anwar**. It’s perfect for streamlining workflows, creative shortcuts, and gaming macros. This open-source project includes full PCB design, schematics, 3D models, and all necessary files to build your own Macroboard.

---

## 📦 Repository Structure

| Folder/File                     | Description                                                                 |
|--------------------------------|-----------------------------------------------------------------------------|
| `Macroboard-v2.kicad_sch`      | Electrical schematic designed in KiCad.                                     |
| `Macroboard-v2.kicad_pcb`      | PCB layout file.                                                            |
| `Macroboard-v2.step`           | 3D STEP model of the assembled macro pad with components.                   |
| `Macroboard-v2.csv`            | Bill of Materials (BOM) including part prices and sources.                  |
| `Gerber/`                      | Complete Gerber files ready for PCB fabrication.                            |
| `3d Model/`                    | STL and STEP files for 3D-printable case/enclosure.                         |
| `AutoDesk Project File/`       | Fusion 360 project files for case customization.                            |
| `images/`                      | Photos, renders, and other visual references.                               |
| `JOURNAL.md`                   | Development and design notes.                                               |
| `.gitignore`                   | Git ignore file.                                                            |
| `README.md`                    | This document.                                                              |

---

## 🧰 Features

- ✅ **4 Mechanical Keys** — Minimalist layout for essential macros.
- ✅ **Rotary Encoder** — Smooth, precise control for volume, scrolling, or custom functions.
- ✅ **Kailh Hot-Swap Sockets** — Easily swap switches without soldering.
- ✅ **MX-Style Switch Compatible** — Supports all Cherry MX-style switches.
- ✅ **USB-C Connector** — Modern, reversible connection interface.
- ✅ **QMK / VIA Firmware Compatible** — Full programmability and customization.
- ✅ **Open Source Hardware & Software** — Full transparency and freedom to customize.

---

## 🛠️ Bill of Materials (BOM)

The full BOM is detailed in [Macroboard-v2.csv](Macroboard-v2.csv), including:

- Kailh hot-swap sockets
- Recommended switches (e.g., Kailh Speed Pro Heavy / Super Speed)
- Rotary encoder (e.g., DCR_PEC12R-4015F-S0024)
- LEDs (SMD 1206 package)
- NPN transistors (SOT-23 package) for LED control
- SMD resistors (0603 package)
- Microcontroller and USB-C connector (not included in the repo)

Prices and supplier info included.

---

## 🖨️ 3D Printed Case

Included are 3D-printable case files located in the [`3d Model/`](./3d%20Model) and [`AutoDesk Project File/`](./AutoDesk%20Project%20File) folders. The case is designed to protect the PCB and provide a sleek, ergonomic enclosure.

---

## 📤 Manufacturing Instructions

1. Upload the Gerber files in the `Gerber/` folder to your PCB manufacturer of choice (e.g., JLCPCB, PCBWay).
2. Select 1.6mm FR4, 2-layer PCB, HASL finish.
3. Order and wait for delivery.
4. Assemble components following the schematic and BOM.

---

## 🧪 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/MoeezAnwar/Macroboard.git
   cd Macroboard
Open and edit the project in KiCad 7+.

Program the microcontroller with QMK or compatible firmware to customize key mappings and encoder behavior.

---



## ✍️ Author

**Moeez Anwar**  
Founder, Flurryhost  
[LinkedIn](https://linkedin.com/in/MoeezAnwar) 

---

## 🛡️ License

Open source under the [MIT License](LICENSE). Feel free to use, modify, and share with credit.

---

## 🙏 Acknowledgments

Thanks to the KiCad community and open hardware advocates for enabling projects like this.

---

Share your builds and improvements! Contributions and issues are welcome.
