# PCB Design Repository

This repository contains a collection of my PCB design projects. Each project folder contains the schematic, PCB layout, and Gerber files for the completed design.:electric_plug:

## Project List
- **Mixed Signal Board** - This board features a range of components including an Ethernet PHY, I2S DAC for headphones and speakers, MEMS mic, 24-bit ADC, 36W bi-directional   brushed DC motor drivers, UART to USB TTL converter, STM32F103 controller as debugger and programmer, STM32F407 main controller, power supply, and protections.
- **DC-DC BUCK-BOOST Converter** - This design was developed to meet the following requirements: input voltage range of 3.0 to 4.2 V, output voltage of 3.3 V, and output current of 200 mA. The design features the Texas Instruments TPS63000, a cost-effective IC that can maintain 1.2 A of output current in step-down mode and 800 mA of output current in step-up mode. The TPS63000 was chosen for its low cost, high efficiency at the required load, availability, and simple component stack-up, which allowed for a straightforward PCB layout.

## Design Considerations
Each project in this repository was designed with careful consideration of the following factors:

- Layer stack-up selection and rules for defining any stack-up
- Different grounding techniques (signal grounding, earth grounding, chassis grounding)
- Power distribution network analysis (PDN analysis) of any PCB
- EMI and EMC decisions for a complex mixed-signal schematic design
- How to define board shape and rigid-flex PCB board
- Components placement planning for a complex board and its execution
- Power distribution network (PDN analysis) and how to read its report + resolve issues

## Tools and Controllers Used
I use a variety of tools and controllers in my PCB design projects, including:

- Altium Designer for schematic capture and PCB layout
- STMicroelectronics' microcontrollers for embedded control applications
- Analog Devices' MEMS microphones for audio applications
- Maxim Integrated's analog-to-digital converters for high-precision data acquisition
- Texas Instruments' power management and motor control ICs

## License
All of the PCB designs in this repository are released under the MIT License. Feel free to use them for personal or commercial projects. If you have any questions or comments, please feel free to open an issue in the repository or contact me directly.
