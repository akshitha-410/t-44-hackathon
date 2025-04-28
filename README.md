SMART ATTENDANCE SYSTEM RFID USING RASPBERRY PI
What You’ll Need:
1.Raspberry Pi (any model, like 3, 4, or Zero)
2.RFID Reader (commonly used: MFRC522)
3.RFID Tags or Cards
4.Jumper wires
5.Breadboard (optional)
6.Python (installed by default on Raspberry Pi)

MFRC522 Pin | Connect to Raspberry Pi:
SDA | GPIO 8 (CE0)
SCK | GPIO 11 (SCLK)
MOSI | GPIO 10 (MOSI)
MISO | GPIO 9 (MISO)
IRQ | Not connected
GND | GND
RST | GPIO 25 (or any GPIO)
3.3V | 3.3V

Install the Library:
>sudo apt-get update
>sudo apt-get install python3-pip
>pip3 install spidev RPi.GPIO mfrc522

INSERT THE CODE>>>
RFID Access Control System — Overview

What it does:
-Waits for an RFID tag.
-Reads the tag’s unique ID.
-Compares it with a list of authorized IDs.
-Displays “Access Granted” or “Access Denied”.

Applications:
1.Door unlock system with servo
2.Attendance system
3.Inventory or library management
4.Cashless payments


