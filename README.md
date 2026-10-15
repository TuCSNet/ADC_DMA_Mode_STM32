# ADC_DMA_Mode_STM32

## Overview

This project demonstrates ADC data acquisition using DMA on an STM32 Nucleo-F446RE development board.

The microcontroller reads the internal temperature sensor. When the user presses the B1 button(connected to PC13), the measured temperature is displayed on a PC terminal via UART.

## Hardware

- STM32 Nucleo-F446RE development board
- USB connection to PC

## Software and Tools

- STM32CubeIDE
- STM32CubeMX
- STM32 HAL
- C programming language

## Features

- ADC configuration for internal temperature sensor measurement
- DMA-based ADC data transfer
- GPIO interrupt handling for the B1 user button (PC13)
- UART communication between the STM32 microcontroller and a PC terminal

## Project Structure

- `Core/Inc/` — application header files
- `Core/Src/` — application source files
- `Drivers/` — STM32 HAL and CMSIS dependencies
- `.ioc` — STM32CubeMX configuration file
