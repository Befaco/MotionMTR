# Motion Meter v1
Firmware for Molten Modular & Befaco [Befaco](http://befaco.org) Motion meter module.

## Requirements
You need Arduino >= 1.6.3. 

Additionally you will need the following libraries installed (see the [Arduino Guide](https://www.arduino.cc/en/Guide/Libraries) on how to do this):

* [Adafruit NeoPixel](https://github.com/adafruit/Adafruit_NeoPixel) 



## Uploading the firmware


1. Get an ICSP Programmer 
We normally use an USBasp programmer like this one https://www.ebay.com/itm/USBASP-USB-ISP-Programmer-for-Atmel-AVR-ATMega328-ATMega32U4-Arduino-/322662323277

2. Download Arduino IDE
Go to the official Arduino website https://www.arduino.cc/en/Main/Software and download the latest version of Arduino IDE for your operating system and install it.

3. Download the firmware 
Go to https://github.com/Befaco/MotionMTR and press "clone or download" to download the repository to your computer. Extract the zip file and copy "firmware" folder to your sketchbook folder. 

4. Install the libraries
Download the libraries and copy them into your library folder.
 
5. Connecting the module
Connect the programmer to the ICSP conector in the back of the module. Pay special attention to the pinout when you plug the module. You can check this link for more information about ICSP https://www.arduino.cc/en/Tutorial/ArduinoISP

6. Upgrading
Press "Open" and search the file "MoltenMotionMeter.ino" located on the "MoltenMotionMeter" folder. Select "Tools > Board > Arduino/Genuino Uno". Go to "Sketch" and hit "Upload using programmer".

If everything goes well you should see a "Done uploading" message in a few seconds. If something happens during the upgrade, check your Arduino settings following the instructions of this link https://www.arduino.cc/en/Guide/Troubleshooting

## Credits

Motion MTR was coded by nilodude:
https://github.com/nilodude






