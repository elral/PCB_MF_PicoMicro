# PicoMicro Board

## Board overview
The PicoMicro Board is a small processor board using the RP2040.
It is intended to replace an Arduino ProMicro or for new designs where the number of pins is sufficient.


![Top View](promicro-top.png)


### Description of Connectors and parts


## Connecting and wiring


### MobiFlight Prototyping Board

### Direct connection

#### Wiring

![image](wiring-diagram.png)

#### Board configuration

![Top View](board-configuration.png)

## MobiFlight Configuration

## Additional information

### Bottom side
![Top View](promicro-bottom.png)

### Schematic
![Schematic](schematic.png)

---------------------------------------------------------------------------------------------

# ✈️ RP2350A ProMicro-Compatible Board for Mobiflight

![Mobiflight Compatible](./assets/mobiflight-badge.svg)
![Arduino IDE](https://img.shields.io/badge/Arduino_IDE-Supported-success?style=flat-square)
![Form Factor](https://img.shields.io/badge/Form_Factor-ProMicro-green?style=flat-square)

This board is designed as a **drop-in replacement** for the classic Arduino Pro Micro (ATmega32U4), but powered by the **modern Raspberry Pi RP2350A microcontroller**.  
It keeps the same **form factor and pinout** while offering massive improvements in performance, memory, and connectivity — making it the **ideal choice for Mobiflight cockpits**.

---

## 🚀 Why RP2350A for Mobiflight?

### ⚡ Drop-In Upgrade
- Identical footprint & pinout to the Arduino Pro Micro  
- Works with existing wiring and PCB layouts → **no hardware redesign required**

### 📈 Higher Performance for Complex Cockpits
- **Dual-core ARM Cortex-M33 @ up to 150 MHz** (with FPU & DSP)  
- Handles many encoders, switches, LEDs, and displays simultaneously  
- **512 KB SRAM + up to 16 MB Flash** → no memory limits for complex setups

### 🔌 Richer Connectivity
- **Native USB 2.0 FS/HS** with multiple device classes  
- Multiple **UART, SPI, and I²C buses** for parallel device control  
- **PIO (Programmable I/O)** → accurate timing for LEDs, drivers, or custom protocols  
- Integrated **crypto hardware** (AES, SHA, etc.)

### ⚡ True 5V Compatibility
- **5V-tolerant I/O pins** → safe with legacy 5V sensors, LEDs, and modules  
- No need for external level shifters  
- Fully compatible with common cockpit electronics

### 🔋 Efficiency & Reliability
- ARM-based low-power modes for large setups  
- Stable & future-proof, backed by Raspberry Pi Foundation support

---

## 📊 RP2350A vs. Arduino Pro Micro (ATmega32U4)

| Feature  | RP2350A ProMicro                          | Arduino Pro Micro (ATmega32U4) |
|----------|-------------------------------------------|--------------------------------|
| MCU      | Dual-core ARM Cortex-M33 @ up to 150 MHz, FPU, DSP | 8-bit AVR @ 16 MHz |
| Flash    | Up to 16 MB QSPI (typ. 2–8 MB onboard)    | 32 KB |
| RAM      | 512 KB                                    | 2.5 KB |
| USB      | Native USB 2.0 FS/HS, multiple device classes | Native USB 2.0 FS (limited) |
| I/O      | **3.3 V logic, 5 V-tolerant pins**        | 5 V I/O (native) |
| Extra HW | 2× PIO, Crypto engine, more UART/SPI/I²C | – |
| Power    | Low-power modes, efficient ARM design     | Limited power saving |

---

## ✈️ Why It Matters for Mobiflight
- **Supports more devices per board** → fewer boards, fewer USB connections  
- **Fast response times** → smoother input/output handling with no lag  
- **Drop-in compatibility** → works in place of the Pro Micro in your cockpit modules  
- **Future-ready** → while the ATmega32U4 reaches its limits, the RP2350A provides plenty of headroom for upcoming Mobiflight features  

---

## 🛠 Software Support
- Fully **Arduino IDE compatible** (just like the Pro Micro)  
- Also supports **MicroPython, CircuitPython, and C/C++ SDK** (for developers extending beyond Mobiflight)

---

## 📌 Summary
The **RP2350A ProMicro** is not just a replacement for the Arduino Pro Micro — it is a **next-generation upgrade built for Mobiflight cockpit builders**:  
✅ More performance  
✅ More memory  
✅ 5V-tolerant IO  
✅ 100% ProMicro form factor  

> **Upgrade your cockpit today — without changing your wiring!**
