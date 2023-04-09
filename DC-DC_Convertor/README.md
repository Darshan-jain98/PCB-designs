# DC-DC BUCK-BOOST Converter
This project is a DC-DC buck-boost converter designed to meet specific voltage and current requirements. The design features the Texas Instruments TPS63000 IC, which is a cost-effective device that can maintain 1.2 A of output current in step-down mode and 800 mA of output current in step-up mode. The TPS63000 was chosen for its low cost, high efficiency at the required load, availability, and simple component stack-up, which allowed for a straightforward PCB layout.

## Project Requirements
The project was developed to meet the following requirements:

Input voltage range of 3.0 to 4.2 V
Output voltage of 3.3 V
Output current of 200 mA

## IC Features
The TPS63000 is a DC-DC boost-buck regulator that has an adjustable output voltage. It comes with Device Enable (EN), under-voltage lockout, over-temperature protection, and power save mode functions.
The EN function allows control of the regulator, shutting it down if required. The under-voltage lockout prevents the regulator from starting up when the input supply voltage is lower than the regulator’s threshold voltage. The over-temperature protection function allows the regulator to shut itself down when the internally sensed temperature exceeds a set threshold, protecting the IC and the rest of the circuit. The power save mode uses a dedicated PS/SYNC pin and can be enabled or disabled by connecting a clock signal to this pin.

## Availability
This regulator IC can be purchased from most electronic component distributors such as Mouser, Digi-Key, Farnell, Arrow, Vertical, RS Components.

## Benefits
The TPS63000 regulator IC is designed primarily for portable battery-powered devices, especially those powered by two or three-cell alkaline, NiCd, NiMH, or single-cell lithium-polymer or lithium-ion batteries. With its adjustable voltage variant, this IC offers flexibility, and with a few calculations and component changes, the regulator can easily be converted from a 3.3 V output to a 5 V output and vice-versa.

## Conclusion
The DC-DC BUCK-BOOST Converter is an excellent solution for battery-powered devices that require specific voltage and current requirements. The TPS63000 regulator IC is an ideal choice for this project, offering efficiency, affordability, and ease of use. The project's simplicity also allows for a straightforward PCB layout, making it a suitable choice for hobbyists and professionals alike.
