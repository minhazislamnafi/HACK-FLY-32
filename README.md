
# HACK FLY 32 (3 inch fpv drone using esp32 s3)

A compact 3-inch 3D printed FPV drone designed for efficiency, stability, and extended flight time. This project features a custom-built flight controller, ExpressLRS (ELRS) communication, and GPS support, all running on Betaflight firmware.

<img width="1106" height="614" alt="Screenshot 2026-04-12 003450" src="https://github.com/user-attachments/assets/b14870b5-b535-459b-bb79-ff70f3c01772" />


⚠️ Disclaimer
The use and operation of this drone may require licenses in certain countries. This project is experimental and provided without any guarantee of safety or reliability.

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
Break the frame in a crash? Just print another. Cost? less than 1$ even if you PETG-CF.



# Documentation
In this repository you can find 3D printable Drone frame STL file, Garber and all the other
files to build your own flight controller. for Flashing the latest Betaflight to 
Flight controller visit rtlopez/esp-fc repo- 
https://github.com/rtlopez/esp-fc.

Join our **[Discord Channel](https://discord.gg/Ff5Q2nz4)** to get help



# Quick Start

## Requirements

**Hardware:**
* Seeed Studio Xiao ESP32 S3(https://www.seeedstudio.com/XIAO-ESP32S3-p-5627.html)
* 1104 4300kv mottor x4 (https://s.click.aliexpress.com/e/_c4sG0n0N)
* 2-3S micro 8A ESC x4 (https://s.click.aliexpress.com/e/_c4ShBcjr)
> [!IMPORTANT]
> **If you also want build your own 4in1 esc**, Visit this repo- **https://github.com/minhazislamnafi/Nano-2-3s-AM32-ESC**.
* Gemfan 3018 bi-blade × 2 pair (https://s.click.aliexpress.com/e/_c34qvZlJ)
* Hglrc m100 mini GPS (https://s.click.aliexpress.com/e/_c4F9Fw8h)
* HGLRC Zeus Nano VTX 350mW (https://s.click.aliexpress.com/e/_c3wNfnSD)

**Components:**

* Mpu6050M QFN-24 (https://s.click.aliexpress.com/e/_c2JBpdQt)
* 0402 10uH inductor (https://s.click.aliexpress.com/e/_c3vbFmHj)
* Some 0603 size Resistors and capacitors [**Checkout Bill of material**](/Flight%20Controller/PCB/BOM_HACK_FLY_V1.2_2026-04-11.csv)
(https://a.aliexpress.com/_c3XHJm1T)
* 0805 size red & green led ×2
(https://s.click.aliexpress.com/e/_c3fRfz0V)











3D print material:

PETG or ABS - Top plate, Bottom plate.(better to use PETG-CF)

TPU - Camera mount, GPS mount, VTX antena mount.




As the Flight controller PCB is 4-layer, choose a well-known manufacturer for better-quality PCBs.

<img width="1756" height="806" alt="fc 2 bg2" src="https://github.com/user-attachments/assets/cd0f46fc-6132-4cc7-8963-48be5573cfbb" />




