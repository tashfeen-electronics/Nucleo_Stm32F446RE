# Nucleo_Stm32F446RE
<img width="1062" height="608" alt="image" src="https://github.com/user-attachments/assets/ec4bf7e5-97bc-44a6-a2cd-b73e8ab121c5" />

# STM32F446RE Hardware & Firmware Module

> A compact, high-performance development module built around the STMicroelectronics STM32F446RE ARM Cortex-M4 microcontroller.

---

## 🚀 Quick Navigation
- **[Hardware Design & Schematics](#-hardware--pcb)** (KiCad / Gerber files)
- **[Firmware & Drivers](#-firmware)** (Bare-metal & HAL drivers)
- **[Pinout & Peripherals](#-pinout-map)**
- **[Getting Started](#-getting-started)**

---

## 🛠️ Hardware & PCB
- **Microcontroller:** STM32F446RE (180 MHz, 512KB Flash, 128KB SRAM)
- **Layer Stackup:** 4-layer standard DFM-compliant layout
- **Files:** Access the full project files in the [`/hardware`](./hardware) directory (KiCad 8 format, Gerber, and PDF schematics).

## 💻 Firmware
- Developed using standard STM32CubeIDE / ARM GNU Toolchain.
- Core peripherals implemented: SPI, I2C, UART, and CAN bus.
- Source code and drivers are located in the [`/firmware`](./firmware) directory.

## 📌 Pinout Map
| Pin | Primary Function | Alternate Function / Peripherals |
| :--- | :--- | :--- |
| **PA2** | USART2_TX | Debug Serial Output |
| **PA3** | USART2_RX | Debug Serial Input |
| **PA5** | SPI1_SCK / LED | On-board User LED & SPI Clock |

## 🚦 Getting Started
1. Clone the repository: `git clone https://github.com/your-username/stm32f446re-module.git`
2. Open the hardware schematics in `/hardware/schematics.pdf` for immediate viewing without CAD software.
3. Import the `/firmware` folder into STM32CubeIDE to build and flash.
