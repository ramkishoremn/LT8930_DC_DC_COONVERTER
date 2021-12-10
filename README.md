# LT8930_DC_DC_COONVERTER
LT8390 - HIGH EFFICIENCY, SYNCHRONOUS BUCK-BOOST CONTROLLER
This design is based on a LT8390 and has a wider operating voltage range, 6 to 60V input and 1 to 60V output.

In addition, it also has an accurate Under-voltage Lockout with programmable hysteresis, perfect for powering from battery systems.

It also includes output current limiting and Spread Spectrum Frequency Modulation for Low EMI.

This board has been designed to fit into a Hammond 1455C802 Enclosure.

DESIGN CONSIDERATIONS
The LT8390 is a synchronous 4-switch buck-boost DC/DC controller that allows the output voltage to be above, below or equal to the input voltage.

Not only does this provide an extremely flexible DC-DC, it is also ideal for battery operated systems where the battery terminal voltage can fluctuate depending upon the state of charge (SoC). For example, I have been using this converter with a QNAP NAS (Network Attached Storage) to obtain a stable 12.0V (as it directly feeds the HDDs) from a 12V battery that could range anywhere from 10.8V to 14.4V.

The LT8390 operates in current mode and senses the current flowing through the inductor via the inductor sense resistor (R6).
