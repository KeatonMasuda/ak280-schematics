# ak280-schematics

[Japanese README is here](README.ja.md)

This repository contains the circuit schematics created from the PCB pattern and mounted components of the AK-280 audio amplifier purchased on Amazon. The schematics have been implemented using KiCad.

## Project Purpose
This project is purely a personal hobby. There is no specific purpose or goal other than the author's own interest in analyzing the hardware.

## Directory Structure

```text
ak280-schematics/
├── hardware/
├── images/
├── LICENSE
├── README.ja.md
└── README.md
```

## File Descriptions

* **hardware/**: Contains all KiCad schematic files and design data.
* **images/**: Contains screenshots and images of the circuit schematics for quick preview.
* **LICENSE**: The license terms and conditions for using these project files.
* **README.ja.md**: Detailed project description written in Japanese.
* **README.md**: Detailed project description written in English (this file).

## How to Use
1. Clone this repository to your local machine.
2. Open the project file `hardware/AK-280.kicad_pro` using KiCad (v7.0 or later recommended).
3. Navigate to the schematic editor to view the created circuit diagram.
4. GIMP is required to view and edit the `.xcf` files in the `images/` directory.

## Disclaimer
The schematics in this repository were reverse-engineered by analyzing the physical board with the assistance of an AI-generated pattern diagram (`fig04-ai-generated-reference.png`). While efforts have been made to ensure accuracy, the completeness of the netlist is not 100% guaranteed. The author shall not be held liable for any damages, hardware failures, unexpected issues, or any other losses arising from the use of these files. Use them at your own risk.

## Credits
* The KiCad symbol for TDA7377 was sourced from Snapmagic (https://www.snapmagic.com/).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.