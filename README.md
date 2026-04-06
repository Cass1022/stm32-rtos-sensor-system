# stm32-rtos-sensor-system

A real-time multi-sensor monitoring system built on the STM32F446RE 
(Cortex-M4) running FreeRTOS. Reads environmental and distance data 
from multiple sensors, displays live readings on an OLED screen, and 
streams data over UART to a host PC.

<img width="333" height="151" alt="Screenshot 2026-04-05 at 9 31 51 PM" src="https://github.com/user-attachments/assets/a17d8e3a-ee39-4778-a96b-f16c270e3112" />

## Hardware
- STM32F446RE Nucleo-64
- HC-SR04 ultrasonic distance sensor
- BME280 temperature/humidity/pressure sensor
- SSD1306 128x64 OLED display

## Software + Tools
- STM32CubeIDE
- FreeRTOS (via CMSIS-RTOS v2)
- HAL drivers

## Status
In progress - hardware arriving soon :)


