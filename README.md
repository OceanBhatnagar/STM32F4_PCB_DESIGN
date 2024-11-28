# STM32F4 PCB Design 

This repository contains the PCB design files and documentation for a custom STM32F4-based board featuring integrated IMU, BMP, USB, and SWD circuitry. 
The design uses the STM32F411CEU6 microcontroller, with pinouts configured in **STM32CubeIDE** and PCB layout completed in **Altium Designer**.  

## Features  
- **Microcontroller**: STM32F411CEU6  
- **Integrated Sensors**:  
  - **IMU (MPU-6050)**: Triple-axis accelerometer and gyroscope.  
  - **BMP280**: Barometric pressure sensor for altitude and environmental data.  
- **USB Circuitry**: For programming and communication via USB.  
- **SWD Interface**: For debugging and firmware uploads.  
- Compact 4-layer PCB design optimized for embedded applications.  

## Tools Used  
- **STM32CubeIDE**: For microcontroller configuration and pinout assignments.  
- **Altium Designer**: For schematic capture and PCB layout design.  

## Project Structure  
- **Schematic Files**: Includes all the components and their connections.  
- **PCB Layout Files**: Altium Designer project files for the PCB layout.  
- **Bill of Materials (BOM)**: List of components with specifications and quantities.  
- **Pinout Configuration**: `.ioc` file for STM32CubeIDE configuration.  
 
