# stm32-rtos-sensor-system

A real-time multi-sensor monitoring system built on the STM32F446RE 
(Cortex-M4) running FreeRTOS. Reads environmental and distance data 
from multiple sensors, displays live readings on an OLED screen, and 
streams data over UART to a host PC.

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


