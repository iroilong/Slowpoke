# Slowpoke Adapter Board

## Overview  
Slowpoke is a custom adapter board inspired by the Munchlax Merlin Stereo DSM development platform. It is designed for embedded audio applications and prototyping with ADI 1797A codec, Arduino UNO R4 WiFi. Slowpoke simplifies system integration by providing level shifting, power supply regulation, and flexible connectivity for I2C, SPI, UART, and USB interfaces.

## Features  
- Seamless integration with ADI 1797A, Arduino UNO R4 WiFi
- Multiple level shifters for voltage domain translation (1.8V, 3.3V, 5V)  
- Dedicated reset circuitry for both microcontrollers and peripherals  
- Support for SD card, USB, and RS232 interfaces  
- External 12V and regulated 5V power supply inputs  
- Easy jumper-configured connections for customization and testing  

## Block Diagram  
![Slowpoke Block Diagram](02_HW/Reference/Slowpoke%20Block%20Diagram.jpg)
  

## Getting Started  
1. Connect Slowpoke board components as per the block diagram and jumper configuration.  
2. Ensure level shifters and power supplies are correctly set according to your system voltage domains.  
3. Use standard I2C, SPI, UART, or USB protocols to communicate with connected microcontrollers or audio codecs.  
4. Refer to example code or libraries compatible with Arduino or ADI hardware SDKs for firmware development.  

## Repository Structure  
- `/01_Doc` - Related documentation and design references  
- `/02_HW` - Hardware schematics, PCB layout, and reference diagrams  
- `/examples` - Example firmware and interface testing code  

## Contact  
For questions or support, please reach out via GitHub issues or email.
