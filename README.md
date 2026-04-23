# stm32-rtos-sensor-system

A real-time multi-sensor monitoring system built on the STM32F446RE 
(Cortex-M4) running FreeRTOS. Reads environmental and distance data 
from multiple sensors, displays live readings on an OLED screen, and 
streams data over UART to a host PC.

<img width="835" height="374" alt="Screenshot 2026-04-05 at 9 32 55 PM" src="https://github.com/user-attachments/assets/97912ca8-e626-4afb-8195-307c030c12be" />

Sensor data is acquired by the Sensor Task on a fixed 50ms schedule 
and passed via FreeRTOS queues to the Processing Task for filtering. 
Processed data is then distributed to the Display Task (SSD1306 over 
I2C) and the Comms Task (UART).

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
In progress - Nucleo, BME280, and OLED display have arrived!. Just working with just the ultrasonic sensor for now, working out some issues with the measurements.


