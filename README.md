# teensy4-rs-lab

Personal lab monorepo containing Rust applications and crates for the PJRC
[Teensy(R) 4.1](https://www.pjrc.com/store/teensy41.html) development board, featuring the 600 MHz NXP
[i.MX RT1060](https://www.nxp.com/docs/en/nxp/data-sheets/IMXRT1060CEC.pdf) family of Arm(R) Cortex(R)-M7 MCUs.

---

## `MIMXRT1062DVJ6B`

### General Description

The `i.MX RT1060` is a new processor family featuring NXP’s advanced implementation of the Arm(R) Cortex(R)-M7 core,
which operates at speeds up to 600 MHz to provide high CPU performance and best real-time response.

The `i.MX RT1060` processor has 1 MB on-chip RAM. 512 KB can be flexibly configured as TCM or general
purpose on-chip RAM, while the other 512 KB is general-purpose on-chip RAM. The `i.MX RT1060`
integrates advanced power management module with DCDC and LDO that reduces complexity of external
power supply and simplifies power sequencing. The i.MX RT1060 also provides various memory interfaces,
including SDRAM, RAW NAND FLASH, NOR FLASH, SD/eMMC, Quad SPI, and a wide range of
other interfaces for connecting peripherals, such as WLAN, Bluetooth™, GPS, displays, and camera
sensors. The `i.MX RT1060` has rich audio and video features, including LCD display, basic 2D graphics,
camera interface, SPDIF, and I2S audio interface. The i.MX RT1060 has analog interfaces, such as ADC,
ACMP, and TSC.

### Reference Manual

* [IMXRT1060RM](https://www.nxp.com/webapp/Download?colCode=IMXRT1060RM) - i.MX RT1060X Processor Reference
Manual (login required)

---

## Getting Started

### Required Hardware

>The following instructions assume, for simplicity, the existence of an available USB Type-A port on the host device. Use of an adapter providing a USB Type-A port to USB-C connector should also work.

A **USB Micro-B to Type-A cable** is required for connection between the development board and the host device. The USB Micro-B connector plugs into the USB Micro-B port, flat side up, i.e., away from the PCB.

![USB Micro-B port](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/USB_Micro-B_receptacle.svg/150px-USB_Micro-B_receptacle.svg.png)

![USB Type-A connector](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/USB_Type-A_receptacle_Black.svg/150px-USB_Type-A_receptacle_Black.svg.png)

### Required Software

#### macOS

>TODO

#### Windows

>TODO

#### Linux

>TODO

---

## Other Resources

* Ian McIntyre's [teensy4_bsp](https://mciantyre.github.io/teensy4-rs/teensy4_bsp/) Rust board support package
* Paul Stoffregen's [Teensy Loader - Command Line Version](https://github.com/PaulStoffregen/teensy_loader_cli)
utility, which requires `make` and, on some platforms, `libusb-dev`

---

## License

[MIT License](https://spdx.org/licenses/MIT.html)

---

`./README.md`
