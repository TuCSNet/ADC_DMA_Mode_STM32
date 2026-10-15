# ADC_DMA_Mode_STM32
##Overview 
This project demonstrates embedded C development on an STM32 Nucleo-F446RE development board.
When user press buttion B1(PC13) the temperature will display on the screen.
##Hardware
STM32 Nucleo-F446RE development board
USB connection to PC
##Software and Tools
STM32CubeIDE
STM32CubeMX
STM32 HAL
C programming language
##Features
UART communication between STM32 and a PC
ADC uses DMA to trasfer data
##Project Structure
Core/Inc/ — application header files
Core/Src/ — application source files
Drivers/ — STM32 HAL and CMSIS dependencies
.ioc — STM32CubeMX configuration
