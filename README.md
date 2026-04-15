
# HACK FLY 32 (3 inch fpv drone using esp32 s3)

A compact 3-inch 3D printed FPV drone designed for efficiency, stability, and extended flight time. This project features a custom-built flight controller, ExpressLRS (ELRS) communication, and GPS support, all running on Betaflight firmware.
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Betaflight](https://img.shields.io/badge/Betaflight-Compatable%25-blue)

<img width="1106" height="614" alt="Screenshot 2026-04-12 003450" src="https://github.com/user-attachments/assets/b14870b5-b535-459b-bb79-ff70f3c01772" />


⚠️ Disclaimer
The use and operation of this drone may require licenses in certain countries. This project is experimental and provided without any guarantee of safety or reliability and it's under the [MIT License](/license).

USE AT YOUR OWN RISK.



# Specifications


Frame Size: 3-inch.

Motors: 1104 – 4300KV.

Propeller: Gemfan 3018 bi-blade.

Battery Support: 2S – 3S LiPo.

suggested battery: (900-1500)mah 3s lipo.

Flight Controller: Custom-designed FC.

Firmware: Betaflight.

RC Protocol: ExpressLRS (ELRS)

Navigation: GPS supported.

gps compatibility: any 15*15mm gps (Hglrs m100 mini suggested)

Use Case: Long-range FPV, exploration, and experimental flight testing.




# Why HACK FLY?

A custom hardware and PCB that gives you your own way to add spice to it.
Also compatible with BetaFlight (you can achieve very agile and stable flight characteristics). Supports all types of Radio RX protocols: PPM, SBUS, IBUS, and CRSF Receivers.
If you combine it with a high-performance 18650 Li-ion battery (like Molicel PB28A,Eve 30pl,Ampace jp30 or Sony vt6), you can get over 10 minutes of flight time.

Who didn't want his drone to be repairable? The 3D-printed frame gives you that flexibility.
Break the frame in a crash? Just print another. Cost? less than 1$ even if you use PETG-CF.



# Documentation
In this repository you can find 3D printable STL files, Garber and all the other
files to build your own flight controller and Drone frame. 
for Flashing the latest Betaflight to Flight controller visit rtlopez/esp-fc repo- 
**https://github.com/rtlopez/esp-fc**.

Join our **[Discord Channel](https://discord.gg/Ff5Q2nz4)** to get any kind of help.



# Quick Start

## Requirements

## Hardware:

* Seeed Studio Xiao ESP32 S3(https://www.seeedstudio.com/XIAO-ESP32S3-p-5627.html)
* 1104 4300kv mottor x4 (https://s.click.aliexpress.com/e/_c4sG0n0N)
* 2-3S micro 8A ESC x4 (https://s.click.aliexpress.com/e/_c4ShBcjr)
> [!IMPORTANT]
> **If you also want build your own 4in1 esc**, Visit this repo- **https://github.com/minhazislamnafi/Nano-2-3s-AM32-ESC**.
* Gemfan 3018 bi-blade × 2 pair (https://s.click.aliexpress.com/e/_c34qvZlJ)
* Hglrc m100 mini GPS (https://s.click.aliexpress.com/e/_c4F9Fw8h)
* HGLRC Zeus Nano VTX 350mW (https://s.click.aliexpress.com/e/_c3wNfnSD)
* 2.54mm Round Hole Needle Female & Male Pin Header (https://s.click.aliexpress.com/e/_c327hfoV)

**Components:**

* Mpu6050M QFN-24 (https://s.click.aliexpress.com/e/_c2JBpdQt)
* 0402 10uH inductor (https://s.click.aliexpress.com/e/_c3vbFmHj)
* Some 0603 size Resistors and capacitors [**Checkout Bill of material**](/Flight%20Controller/PCB/BOM_HACK_FLY_V1.2_2026-04-11.csv)
(https://a.aliexpress.com/_c3XHJm1T)
* 0805 size red & green led ×2
(https://s.click.aliexpress.com/e/_c3fRfz0V)

**For detailed parts list follow [Hardware list](/docs/hardware.md)**


## PCB

Use JLCPCB if you're in ASIA or PCBWAY if you're in America. Also, find what manufacturer is better for you. 
If you just want to get Flight controller PCB then use this [**GERBER file**](/Flight%20Controller/PCB/Gerber_HACK_FLY_PCB_V1.2_2026-04-11.zip). Download it and place order.
Or if you just want to build your own PCB, then follow this [**Schematic**](/Flight%20Controller/PCB/Schematic_HACK_FLY_2026-04-11.svg).
<img width="1756" height="806" alt="fc 2 bg2" src="https://github.com/user-attachments/assets/cd0f46fc-6132-4cc7-8963-48be5573cfbb" />


## 3D printed parts

To print all the parts for the HACK FLY frame, please **USE-**

**PETG or ABS** - [Top plate](/Drone%20Frame/Top%20Plate/Top%20plate.stl), [Bottom plate](/Drone%20Frame/Bottom%20plate).(**better to use PETG-CF**)

**TPU** - [Camera mount](/Drone%20Frame/Camera%20Mount/Camera%20mount%20right.stl), [GPS mount](/Drone%20Frame/GPS%20mount/GPS%20mount.stl), [VTXantena mount](/Drone%20Frame/Vtx%20antena%20mount/Antenna%20mount.stl).


**AFTER EVERYTHING IS DONE SOURCING, FOLLOW THESE STEPS**





