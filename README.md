# Description

The FT230XS is a USB to UART converter integrated circuit (IC) manufactured by FTDI (Future Technology Devices International). This chip is a compact, reliable, and easy-to-use solution for serial communication, such as connecting microcontrollers to computers.
The self-powered configuration means that the device does not receive power from USB, but is supplied with the energy required for its operation by an external power supply (external 3.3V stabilized power supply).
The communication PCB is designed to allow direct connection to the Raspberry Pi using a miniUSB cable without opening the case.
The miniUSB port offers an alternative way to directly access the RPi's command line interface, especially in cases where the computer does not have a serial port or it is easier to connect via USB.

---

## Brochure

![](/img/1.jpg)

## Botton side

![](/img/3.jpg)

## Top side

![](/img/2.jpg)

---

## Functions

| Notation | Description                                                  |
| -------- | ------------------------------------------------------------ |
| UART     | Serial communication and power interface (2.54mm pin header) |
| MODE     | Power selectable 3.3V/5V (2.54mm pin header)[^1]             |
| POWER    | Power led                                                    |
| FEEDBACK | TX/RX indicator leds                                         |

[^1]: !!!Caution: Overvoltage!!!

---

## FT230XS Chip UART Features

- USB 2.0 compatible (Full Speed – 12 Mbps)
- Serial UART interface: TXD, RXD, RTS#, CTS#
- Low power, small size SSOP package
- No external crystal required – uses internal oscillator
- Driver support: Windows, Linux, macOS
- Download driver: [FT230XS Drivers](https://ftdichip.com/products/ft230xs/)

---

## Specifications

- UART pinout connectror
- 3.3V or 5V power led indicator (programming mode)
- RX/TX leds indicator
- Based on FT230XS chip
- Mini-B USB Interface
- Number of PCB layer: 2 layers
- PCB Compliant: ROHS
- 4x M2.5 mounting hole

---

## Applications

- The NHPSU-V1 PCB is responsible for the power supply, it will always ensure that it is powered. Compatible with RPI with 3.3v voltage GPIO.
- Always pay attention to the polarity before connecting them, make sure that you have connected them correctly before turning them on.
- Connection pinout: RPI TX <---> NHCB-V1 RX; RPI RX <---> NHCB-V1 TX; VDD <---> NHPSU-V1 VDD; GND <---> NHPSU-V1 GND
- Local console connection for RPI management.
- Does not provide power, only establishes a data connection.
- Supported operating systems: Windows, Linux, macOS (depending on driver availability and version).
- After installing the driver, the system will recognize the device as a new COM port.
- Terminal Settings: Baud rate: 9600 bps; Data bits: 8; Stop bit: 1; Parity: none; Flow control: none

---

## Release: V1.0
- [x] First release
- [ ] Problems

---

## Dimension

![](/img/4.jpg)

---

## Schematic

![](/img/5.jpg)

---

## BOM (Bill Of Materials)

[View](https://htmlpreview.github.io/?https://github.com/drcyberg/Leder_Station_Lamp_V1/blob/main/bom/l_s_l_b.html "View")

---

## Created by DrCyberg

[drcyberg@gmail.com](mailto:drcyberg@gmail.com)
