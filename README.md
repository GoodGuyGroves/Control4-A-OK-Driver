Two Control4 drivers needed to interface A-OK manufactured curtain and blind motors and their AV Transmitter to your Control4 home automation system.

One driver is required for the AV Transmitter/RS-485 and one for the motor itself. Only one "bus" driver is added per project with one motor driver added per physical motor. The AV Transmitter and some A-OK motors are actually RS-485 but Control4 controllers only have RS-232 so a RS-485 to RS-232 converter is required. I highly recommend the ADAM-4520. Make sure you select in the driver if you're using the AVT or just straight RS-485.

The drivers are packaged as .c4i which is basically XML embedded with Lua. To edit make sure you have Control4's DriverEditor.

This driver is provided without warranty or support. Good luck.

Extra info:
A-OK AVT - http://www.aokmotors.co.uk/40-20-av-transmitter-interfaces-audio-visual-interface.html
ADAM-4520 - http://www.advantech.com/products/data_acquisition_modules/adam-4520/mod_8dcee4b7-fbde-4c5d-9752-ed2f2fbd00bf
