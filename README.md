# STM32 Health Monitoring Project

This project is a design project built on the STM32G071RB microcontroller. It features:

- 🖥️ **ST7789 screen** driven using **DMA** for efficient graphics rendering.
- ❤️ **MAX30100** sensor for real-time heart rate and SpO₂ measurement.
- 🌡️ **MLX90614** infrared temperature sensor for non-contact temperature reading.
- ⏱️ All sensor readings are triggered and processed via **hardware timer interrupts** for accuracy and efficiency.
- 🔊 **Buzzer integration** for alerts based on critical thresholds.
- 📈 Real-time data is displayed graphically on the screen.

## Features
- Timer-based sampling every 100ms
- Mode filtering for stable BPM/SpO₂ values
- Display data in real time graphically
- Peak detection algorithm for heart rate
- DMA-based screen updates to avoid SPI blocking

## Libraries Used
- [ST7789 STM32 HAL Driver]( https://github.com/Floyd-Fish/ST7789-STM32) – **GPLv3 License**


> 🛠️ Built and tested on STM32CubeIDE on macOS  
> 🧪 Fully functional on STM32G071RB with 3.3V logic level devices
> ## License

**This project is licensed under the [GNU General Public License v3.0](./LICENSE)**  
You are free to use, modify, and distribute this code under the same license.

---
