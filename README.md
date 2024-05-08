STM32F103-BMP180-I2C-Sensor
Description:
- This project demonstrates interfacing the BMP180 sensor with the STM32F103 microcontroller using the I2C communication protocol.
- BMP180 is a digital pressure sensor that provides precise pressure and temperature data for various applications. The STM32F103 microcontroller, based on the ARM Cortex-M3 core,
serves as the master device in the I2C communication, reading data from the BMP180 sensor.

Features:
- Utilizes the BMP180 sensor to measure pressure and temperature.
- Communicates with the BMP180 sensor via the I2C interface.
- STM32F103 serves as the master device controlling the I2C communication.

Installation
- Connect the BMP180 sensor to the STM32F103 development board.(Use Hard I2C Pins on stm32 board)
- Copy the source code from the STM32F103_Code directory to the STM32CubeIDE, KeilC or any other compatible IDE.
- Compile and upload the code to the STM32F103 microcontroller through serial wire.
  
Usage
- Ensure proper connections between the BMP180 sensor and the STM32F103 microcontroller.
- Run the code on the STM32F103 microcontroller.
- Monitor the pressure and temperature readings from the BMP180 sensor through the serial monitor or display device.

Requirements:
- BMP180 sensor module
- STM32F103 development board
- STM32CubeIDE or compatible IDE
- Wires for connections
