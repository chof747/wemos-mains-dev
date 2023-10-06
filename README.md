## Board to combine a Wemos D1 Mini with a mini power supply

This is a small board that can take a Wemos D1 Mini  together with a 5V mini power supply to obtain a W-Lan microcontroller board with IO pins able to put e.g. in a switch box and power it
directly from mains

It contains the following elements:

- WeMos D1 Mini (or any other microcontroller board that has the same pin configuration)
- A 600mA/5V (3W) power supply 
- A 2x12 pinheader providing all GPIO Pins of the D1 mini in a suitable configuration
- Pull-Up Resistors for the SDA and SCL line
- Jumper Pins to select if the pullups should be used or not
- ByPass Capacitors for the 3V3 and GND lines in vicinity to the One-Wire and analog pin
- Screw Terminal to connect the board to mains

## Revision History:

- **v1.0**: Initial version (filed for fabrication: 19.04.2023)
- **v1.1**: Revision 1 with corrected orientation of power supply and reduced ground plane to avoid collision with high voltage (filed for fabrication: 17.7.2023; First Assembly 06.10.2023)


