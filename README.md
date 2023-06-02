# Arduino_rubber_ducky
This repo contains all the firmware files needed to make a USB rubber ducky / hid device / bad usb with an arduino uno board


You need to download ATMEL FLIP software
This software uploads the .hex firmware file to the arduino


1. Write the arduino code with the payload of your choice and upload it
2. Set the Arduino UNO to DFU mode by momentarily bridging the ground and reset pins
3. The lights should flicker. This means that firmware can now be uploaded
4. Select the firmware
    hid firmware file --> for use as rubber ducky
    normal firmware file --> for use as normal Arduino UNO
5. upload the firmware and unplug the Arduino UNO
6. The ARDUINO UNO is HOT AND READY TO ENGAGE
7. If you want to reprogram, plug it into the usb port after temporarily bridging the ground and reset pins