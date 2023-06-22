## What is A rubber ducky?
USB Rubber ducky is an HID device that looks similar to a USB Pen drive. It may be used to inject keystroke into a system, used to hack a system, steal victims essential and credential data can inject payload to the victim’s computers. The main important thing about USB Rubber ducky is that it cannot be detected by any Anti-Virus or Firewall as it acts as an HID device.
## HID?
HID stands for Human Interface Devices, it includes devices like keyboard, mouse, joystick. which acts as an interface between the computer and human beings. That is why it cannot get detected as the computer thinks its an interface.

# Arduino_rubber_ducky
This repo contains all the firmware files needed to make a USB rubber ducky / hid device / bad usb with an arduino uno board

You need to have Arduino IDE (latest recommended) From the official [Arduino Website](https://www.arduino.cc/en/software)
You need to download ATMEL FLIP software [click here](https://www.microchip.com/en-us/development-tool/FLIP)
>This software uploads the .hex firmware file to the arduino


1. Write the arduino code with the payload of your choice and upload it
2. Set the Arduino UNO to DFU mode by momentarily bridging the ground and reset pins
3. The lights should flicker. This means that firmware can now be uploaded
4. Select the firmware
    hid firmware file ---> for use as rubber ducky
    normal firmware file ---> for use as normal Arduino UNO
5. upload the firmware and unplug the Arduino UNO
6. The ARDUINO UNO is HOT AND READY TO ENGAGE! Be careful
7. If you want to reprogram, plug it into the usb port after temporarily bridging the ground and reset pins

### PLEASE NOTE:

Once the firware is updated, it will keep entering keystrokes unless the payload is successfully injected or until you put the arduino into DFU mode.
So basically it will always be active and ready to engage UNLESS you put it into DFU mode
Even if you try to reprogram it, it will execute the payload
# TO SOLVE THIS PROBLEM,
plug the arduino into the usb board and immediately enter into DFU mode by momentarily connecting ground and reset pins
Now upload the normal firmware for uno using the ATMEL FLIP software only
>Do not open the arduino ide, first update the firmware in order to reprogram it
Now this arduino can be used for other projects and is just like any Arduino UNO board cute and harmless :)
## DISCLAIMER
>By using this Repo, You agree that
'''
# This is for educational Purposes only
# I am not responsible for anything that you do with the contents of this repo
# you agree that you will be responsible for whatever happens with this
'''