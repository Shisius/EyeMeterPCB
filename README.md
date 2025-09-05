# EyeMeterPCB
This is the Interface board for radxa cm5.

This board contains VL805 PCI to USB hub, CS42L42 audio codec, DSI, HDMI, Ethernet, USB, microSD and GPIO connectors.
This board is developed for embedded applications, so the connectors

# Special connectors
1. USB connectors are special but available for purchase (MCS-PN-R100-110-55-LR-IPX).
2. HDMI is compatible with waveshare 20 pin HDMI connector.

# Problems and tests
See TODO.md file for more details
1. USB3 and VL805 works well but appropriate firmware should be loaded into flash. The diode should added for good operation.
2. Ethernet has not been tested.
3. The biggest Inductor should be changed to B82477R4562M100 for better performance.
4. CS42L42 do not work yet. I can see it by i2cdetect but cannot read the register values. I do not know where the problem is.



