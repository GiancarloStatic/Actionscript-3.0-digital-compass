# Actionscript-3.0-digital-compass-hscdtd008a-

Parts list instructions:

Computer: Arduino Nano

Dock: N/A (used mini usb male to microusb female)

Component: hscdtd008a

wires: solder the connections for the compass to work accurate.


Wiring instructions:
Arduino Nano vcc  - hscdtd008a vcc
Arduino Nano gnd -  hscdtd008a gnd
Arduino Nano A5 - hscdtd008a scl
Arduino Nano A4 - hscdtd008a sda


Software instructions:

1.) Connect arduino nano to the usb port & open "compass_testing/compass_testing.ino" in the arduino IDE & click upload to program the board.

2.)Start "usb pipe 57600 baud.exe"

3.)Start "test compass 57600.fla" in the Actionscript 3.0 IDE & it shouled trace connected if the COM port of the Arduino Nano is 7 for this line: "sock.connect("127.0.0.1",45055+7);"

4.) The 3d compass in the .swf should rotate exactly to where the Arduino Nano with the compass module is facing if you are holding the compass strictly on the earths x-axis. Future versions will allow you to hold the compass in a more realistic manner to still face the correct way in the movieclip.
