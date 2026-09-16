# GenesisX

[![License: CERN-OHL-S-2.0](https://img.shields.io/badge/License-CERN--OHL--S--2.0-blue.svg)](LICENSE)

GenesisX is an open-source 2-in-1 laptop that I'm designing from scratch. The plan is to make a Linux laptop with a custom motherboard, OLED touchscreen, 360° hinge, detachable wireless keyboard and active pen support.

## Why I started this

I wanted to build something that was actually challenging instead of just putting together existing modules. GenesisX is mainly a learning project where I can work on PCB design, CAD, embedded systems, power, cooling, firmware and Linux.

## About me

I'm **phantom-ascii**, a student interested in hardware, Linux, programming and CAD. I've worked on smaller PCB and hardware projects before, but GenesisX is a much bigger step up.

One of my longer-term goals is to become a **Hack Club Gappie**, and I'm using projects like this to build up the skills and experience to get there.

## Progress

Currently working on the system architecture, component research, motherboard design and mechanical design.

This repo will contain the designs, CAD, documentation and other files as the project develops.


## GenesisX Rough BOM

This is an early estimate and will change as the design develops. Prices are rough and mainly here to give an idea of the overall cost.

| Category | Part | Qty | Estimated Cost |
|---|---|---:|---:|
| Compute | High-end compute module / SOM | 1 | £150–300 |
| Storage | 2TB M.2 NVMe SSD | 1 | £90–130 |
| Display | 13–14" 16:10 OLED touchscreen, 2.5K–3K, 90–120Hz | 1 | £150–250 |
| Pen | Active pen + digitizer/controller | 1 | £50–120 |
| Wi-Fi / Bluetooth | Wi-Fi 6E/7 module | 1 | £20–40 |
| Motherboard | Custom 6–8 layer PCB | 1 | £80–150 |
| Power | USB-C PD + charging circuitry | 1 | £20–40 |
| Battery | 60–70Wh battery pack | 1 | £50–80 |
| Keyboard | Custom keyboard PCB, switches and keycaps | 1 | £40–70 |
| Trackpad | Glass trackpad + controller | 1 | £30–60 |
| Wireless | Bluetooth MCU + antenna | 1 | £5–15 |
| Pogo connector | Keyboard connection | 1 set | £5–15 |
| Ports | USB-C, USB-A, HDMI, microSD, 3.5mm | 1 set | £10–25 |
| Speakers | Laptop speakers | 2 | £10–20 |
| Cooling | Heatsink, heatpipe and fan | 1 | £30–60 |
| Hinge | Custom 360° hinge assembly | 2 | £30–70 |
| Chassis | Aluminium / 3D-printed chassis | 1 | £80–150 |
| Miscellaneous | Screws, cables, antennas, thermal pads, etc. | — | £50–100 |

## Estimated Totals

| Estimate | Cost |
|---|---:|
| Lower estimate | ~£950 |
| Higher estimate | ~£1,650 |
| Working budget | ~£1,200 |

### Notes

- These are rough estimates, not final component prices.
- The compute module is currently the biggest unknown and will affect the motherboard, cooling and power design.
- Display prices can vary significantly depending on availability and panel specifications.
- Custom PCB costs depend on board size, layer count, quantity and manufacturer.
- Mechanical costs will depend on whether the final chassis is 3D printed, CNC machined or a combination of both.
- The keyboard is detachable and wireless, but the main laptop contains the compute, storage, battery, networking and I/O.
- Parts will be replaced with exact manufacturers and part numbers as the design progresses.

## License

Hardware designs are licensed under **CERN-OHL-S-2.0**.