# Actionscript-3.0-digital-compass-9DOF

Parts list instructions:
Computer: Arduino Nano
Dock: N/A (used mini usb male to microusb female)
Component: 9DOF
wires: solder the connections for the compass to work accurate.


Wiring instructions:
Arduino Nano vcc  - 9DOF vcc
Arduino Nano gnd -  9DOF gnd
Arduino Nano A5 - 9DOF scl
Arduino Nano A4 - 9DOF sda


Software instructions:
1.)Connect arduino nano to the usb port & open "read_compass/read_compass.ino" in the arduino IDE & click upload to program the board.

2.)Start "usb pipe 57600 baud.exe"

3.)Start "9DOF compass 57600.fla" in the Actionscript 3.0 IDE & it should trace connected if the COM port of the Arduino Nano is 7 for this line: "sock.connect("127.0.0.1",45055+7);"

4.)Rotate the 9DOF module around to see it move in 3D.
