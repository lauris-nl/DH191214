# DH191214
Laser controller board from k4 Bluetooth 3000mW Laser engraving machine from aliexpress

3000mw CNC Bluetooth Laser Engraver DIY Logo Mark Printer Cutter Laser Engraving Machine Woodworking 80x80mm Engraving Ranges


I used my engraver via the Android app. (this worked great) But when I installed the windows software and connected the engraver to my USB. 

The machine stopped working permanently. 

The laser went off and the big fan also stopped. 
I think my SPI flash got corrupted... I need to restore a backup. My PCB date code is 20190613
I think this device is some how GRBL32 compatible?... let's see...


Identfication:

SKUA20539-20492184
U7 = STM32F103c8t6
U13 = 25Q32JVS10 (4MBytes of Winbond SPI flash)
U1-2 = ATD5988 (Stepper drivers)
U3 = CH340C (USB uart ttl)

P5 = programmer USB??
P2 and P4 = Laser+minifan port
P3 = Big Fan port
P6 = power port
P1 = USB port

B1-5 = Buttons
BLE1=some bluetooth module?
