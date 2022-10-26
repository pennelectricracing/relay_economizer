# relay_economizer

DESCRIPTION

This board (sponsored by JLCPCB) will allow us to have a higher power efficiency by creating a PWM signal to control our relay coils.

DETAILS

The Relay Economizer is a board that will be used to prevent power dissipation when the car is not active. It uses a DRV110 device to regulate the current through the relay terminals with a well-controlled waveform to reduce power dissipation. When the Relay Economizer is closed, there will be less current flowing through. To maximize battery performance, preventing unnecessary power dissipation is necessary.

Key components:

DRV110: The DRV110 device is a PWM current controller for solenoids. It is designed to regulate the current with a well-controlled waveform to reduce power dissipation. When the solenoid current is high, it will close the relay. After closing, it will keep the constant flow of the current to ensure correct operation of the connected relay and reduce power dissipation. 

![pasted image 0-2](https://user-images.githubusercontent.com/14287399/197921851-b9bbd16e-f49c-4608-8845-317d065fdfd1.png)


Features:

- Internal Zener Diode on Supply Pin for High-Voltage Operation

  - 120- and 230-V AC Supply Through Rectifier and RS Resistor

  - 24-V, 48-V, and Higher DC Supply Through RS Resistor  

- Drives an External MOSFET With PWM to Control Solenoid Current

  - External Sense Resistor for Regulating Solenoid Current

- Fast Ramp-Up of Solenoid Current to Ensure Activation

- Solenoid Current is Reduced in Hold Mode for Lower Power and Thermal Dissipation

- Ramp Peak Current, Keep Time at Peak Current, Hold Current, and PWM Clock Frequency Can Be Set Externally.

- Protection

  - Thermal Shutdown

  - Undervoltage Lockout (UVLO)

- Operating Temperature Range: –40ºC to +125ºC

See more @https://www.ti.com/product/DRV110#product-details##params
