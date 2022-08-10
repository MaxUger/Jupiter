# Jupiter
A 75% hotswappable keyboard PCB with adressable RGB backlighting

__THIS PCB IS UNTESTED, IT PROBABLY DOES NOT WORK__

![pcb-backSide](https://user-images.githubusercontent.com/26027105/183543830-bac2c7e8-3205-4381-b174-3bab601892dc.PNG)

## Features
- 75% Layout
- Hot-swappable
- Adressable RGB backlighting
- USB-C connectivity
- QMK compatible

## Microcontroller
![mcu-schematic](https://user-images.githubusercontent.com/26027105/183546608-bc001b31-8bf2-4268-96e4-690bcb2c62f8.PNG)
- Atmel ATmega32u4-MU due to its compatibility with QMK.
- 16MHz crystal oscillator

## USB-C Assembly
![usb-schematic](https://user-images.githubusercontent.com/26027105/183808637-5915568a-b7bf-4b3c-9ffb-c5ef81fe7801.PNG)
- Uses TYPE-C-31-M-14 connector
- PRTR5V0U2X for ESD protection
- 500mA fuse for overcurrent protection

## Switch Matrix
![switchmatrix](https://user-images.githubusercontent.com/26027105/183809487-dbefcc2e-e041-4cc3-afec-6b59f46d6726.PNG)
- Features a traditional matrix

## LED Matrices
![LEDmatrix](https://user-images.githubusercontent.com/26027105/183810052-43f8be9f-e4f2-4b2c-b688-fe9c14e5dcd3.PNG)
- Features SK6812MINI-E LEDs

__REMINDER: THIS PCB IS UNTESTED, IT PROBABLY DOES NOT WORK. THIS PROJECT IS PURELY A TECHNICAL EXERCISE__

__This project falls under the GNU General Public License v3.0. This project is provided without liability, warranty, and garentee of functionality.__
