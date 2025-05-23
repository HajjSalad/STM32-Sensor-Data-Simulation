## Sensor Data Simulation

This project simulates analog sensor readings on STM32 using the Hardware Abstraction Layer (HAL). The simulated data is transmitted to ESP32 for integration into [IoT Control and Monitor System](https://github.com/HajjSalad/ESP32-IoT-Control-and-Monitor-System).

### Tools & Software Used
Peripherals:
- PWM: Generate analog-like signals for sensor simulation.<br>
- ADC: Sample the PWM signals to convert them into digital sensor data.<br>
- UART: Transmit the simulated sensor data from STM32 to ESP32.<br>

STM32 Development:
 - STM32CubeIDE (with HAL for configuration)
 - ST-Link Debugger

Hardware:
 - STM32 MCU
