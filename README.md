## What is a rubber ducky you ask?

USB Rubber ducky is an HID (Human Interface Device ) that looks similar to a USB Pen drive. HIDs include anything that is an interface between a computer and a human, such as keyboards, joystick, graphic tablet and moulse. By default, a computer always allows an HID device, because it thinks that it is a keyboard, mouse or something similar.
What a Rubber ducky does is, it exploits this trust. It is used to inject keystroke into a system, used to hack a system, steal victims essential and credential data can inject payload to the victim’s computers. The main important thing about USB Rubber ducky is that it cannot be detected by any Anti-Virus or Firewall as it acts as an HID device.

# what is the difference between an actual rubber ducky and arduino rubber ducky?
1. Actual rubber ducky is more stealthy, looks just like a usb pendrive
2. Actual rubber ducky is much faster. However, speed won't matter much since the size of payloads is small in most of the cases.
3. Code has to be stored on an micro SD card in the actual thing, so it can be easily updated/changed, whereas in this case, changing the payload is a tedious task and requires more time.


## Advantages:
1. CHEAPER
2. You make something on your own rather than buying something, making something yourself is always better since it teaches a lot, and you can customize it.
3. Arduino Rubber Ducky(s) can be reused as a normal arduino later, so no arduinos go to waste.

'''
This is to demonstrate the working, this is a good alternative to the actual rubber ducky in most of the cases (except the fact that it does not look like a pen drive)
This is for eduational purpose only
'''
# Arduino_rubber_ducky
This repo contains all the firmware files needed to make a USB rubber ducky / hid device / bad usb with an arduino uno board
You need to have Arduino IDE (latest recommended) From the official [Arduino Website](https://www.arduino.cc/en/software)
You need to download ATMEL FLIP software [from here](https://www.microchip.com/en-us/development-tool/FLIP)
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