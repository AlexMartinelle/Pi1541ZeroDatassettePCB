# Pi1541ZeroDatassettePCB
PCB design for a Pi11541 hat for the Raspberry Pi Zero with additional datassette IO support.

I wanted a Pi1541 hat for the Raspberry Pi Zero that had proper serial ports
and the pins to support my datassette support for the Pi1541.
Datasette code available at: https://github.com/AlexMartinelle/Pi1541DatassetteSupport

This PCB is designed to be used with the Pi1541 Option B settings but with one extra tweak,
the i2cBusMaster setting should be zero since it uses pin 27 for SDA, and pin 28 for SCL.

The design is loosely based on the https://github.com/hackup/Pi1541io PCB and the components used on that PCB.
