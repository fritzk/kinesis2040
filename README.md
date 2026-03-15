# kinesis2040  — Kinesis RP2040 Advantage Controller

This repository contains the design files for a custom replacement controller board for the **Kinesis Advantage** and **Advantage2** keyboards. 

This version updates the classic controller design to use a **Pro Micro-style RP2040** (specifically designed for the [Keeb.io RP2040 Pro Micro](https://keeb.io/products/rp2040-pro-micro-usb-c-controller)) and adds integrated **SK6812MINI-E** addressable RGB indicator lights.

## Design Origins & Credits
This hardware is a **derivative work** based on the [kinT kinesis keyboard controller](https://github.com/kinx-project/kint) by **Michael Stapelberg**.

While the routing, MCU footprint, and LED circuitry are new, this design reuses the **mechanical footprint and header positions** from the kinT project to maintain compatibility with the original Kinesis keywell and thumb cluster ribbon cables.

## Key Features
* **RP2040 Powered:** Designed for the Keeb.io RP2040 Pro Micro, offering high performance, USB-C, and easy flashing (UF2).
* **RGB Indicators:** Replaces standard LEDs with **SK6812MINI-E** addressable RGB LEDs for customizable status indicators and lighting effects.
* **Drop-in Replacement:** Fits the mounting points of the Kinesis Advantage/Advantage2.
* **Header Compatibility:** Uses the kinT-standard pinout for easy connection to existing internal cables.

---

## Licensing & Attribution

This work is licensed under the **Creative Commons Attribution-ShareAlike 4.0 International License**.

> **Attribution:** This project incorporates mechanical layout and pinout designs from the **kinT project** by Michael Stapelberg, licensed under **CC BY-SA 4.0**. 
>
> **ShareAlike:** In accordance with the "SA" provision of the original license, this entire derivative design is released under the same CC BY-SA 4.0 license. You are free to share and adapt this hardware for any purpose, provided you give appropriate credit and distribute your contributions under the same license.

To view a copy of this license, visit [http://creativecommons.org/licenses/by-sa/4.0/](http://creativecommons.org/licenses/by-sa/4.0/).

---

## Disclaimer
*Kinesis and Kinesis Advantage are trademarks of Kinesis Corporation. This project is an independent community-driven hardware mod and is not affiliated with, endorsed by, or supported by Kinesis Corporation.*
