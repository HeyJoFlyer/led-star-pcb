# LED Star PCB and Panelized Version

## Overview
This repository contains the design files for an open-source LED star printed circuit board (PCB) and a panelized version for ease of production. The PCB is designed to accommodate a single 1W LED for optimal heatsinking and simplified wire connections. This project was made with KiCad.

## Features
- Single 1 / 3W LED mounting footprint
- Terminal points for easy wire connections
- Open-source design for customization and improvements, even for comercial use
- An alternative to the expensive pre-made pcbs
- 100*100mm panelized version for cheaper manufacturing
- square and star shaped pcbs (traced from scan of real star pcb)

## Versions:
-Scanned from original pcb:
![alt text]("https://raw.githubusercontent.com/HeyJoFlyer/led-star-pcb/main/real StarPCB.jpg" "real StarPCB preview")
- Square pcb:
![alt text]("https://raw.githubusercontent.com/HeyJoFlyer/led-star-pcb/main/StarPCB.jpg" "square StarPCB preview")
- Panelized Square pcb:
![alt text]("https://raw.githubusercontent.com/HeyJoFlyer/led-star-pcb/main/StarPCB_panelized.jpg" "panelized square StarPCB preview")

## Usage
### LED Star PCB
1. Manufacture the PCB using the provided Gerber files, you need to choose the aluminum pcb (I used JLCPCB),.
1. Mount the LED onto the designated footprint.
1. Connect wires to the terminals for power supply as indicated.

### Panelized Version (cheaper!)
1. Follow the same steps as for the LED Star PCB but using the panelized Gerber files, you need to choose the aluminum pcb.
1. Sparate individual PCBs from the panel after manufacturing (at the score lines).
1. Assemble each individual PCB as instructed for the LED Star PCB.

### Library
If you want to edit the pcb you will need to install the library `library.pretty` for the solder connections.

## Contributing
Contributions, suggestions, and improvements are welcome! Feel free to fork the repository, make changes, and submit pull requests.

## License
This project is licensed under the [MIT License](LICENSE).
