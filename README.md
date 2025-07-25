# CP-NHCB-V1

---

## Description:
## CyberPointer - Network Helper: Communication Board

The FT230XS is a USB to UART converter integrated circuit (IC) manufactured by FTDI (Future Technology Devices International). This chip is a compact, reliable, and easy-to-use solution for serial communication, such as connecting microcontrollers to computers.
The self-powered configuration means that the device does not receive power from USB, but is supplied with the energy required for its operation by an external power supply (external 3.3V stabilized power supply).
The communication PCB is designed to allow direct connection to the Raspberry Pi using a miniUSB cable without opening the case.

---

### Brochure

![](/img/1.jpg)

### Front side

![](/img/2.jpg)

### Back side

![](/img/3.jpg)

---

## Functions:

| Notation | Description                                                  |
| -------- | ------------------------------------------------------------ |
| UART     | Serial communication and power interface (2.54mm pin header) |
| MODE     | Power selectable 3.3V/5V (2.54mm pin header)[^1]             |
| POWER    | Power led                                                    |
| FEEDBACK | TX/RX indicator leds                                         |

[^1]: !!!Caution: Overvoltage!!!

---

### FT230XS Chip UART Features:

- USB 2.0 compatible (Full Speed – 12 Mbps)
- Serial UART interface: TXD, RXD, RTS#, CTS#
- Low power, small size SSOP package
- No external crystal required – uses internal oscillator
- Driver support: Windows, Linux, macOS

---

### Specifications:

- UART Connectror
- 3.3V or 5V power led indicator (programming mode)
- RX/TX leds indicator
- Based FT230XS chip
- Number of PCB layer: 2 layers
- PCB Compliant: ROHS
- 4x M2.5 mounting hole

---

## Applications:

- The NHPSU-V1 PCB is responsible for the power supply, it will always ensure that it is powered. Compatible with RPI with 3.3v voltage.
- Always pay attention to the polarity before connecting them, make sure that you have connected them correctly before turning them on.
- Connection: RPI TX <---> NHCB-V1 RX; RPI RX <---> NHCB-V1 TX; VDD <---> NHPSU-V1 VDD; GND <---> NHPSU-V1 GND

---

### V1.0
- [x] First release
- [ ] Problems

---

### Dimension:

![](/img/4.jpg)

---

### Schematic:

![](/img/5.jpg)

---

## BOM (Bill Of Materials): [View](https://htmlpreview.github.io/?https://github.com/drcyberg/Leder_Station_Lamp_V1/blob/main/bom/l_s_l_b.html "View")

---

## Created by DrCyberg: [drcyberg@gmail.com](mailto:drcyberg@gmail.com)
