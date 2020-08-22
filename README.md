# PlatformIOEspProgCatalina
Platform IO setup for Catalina Mac Pro setup

## Board

Board: Adafruit Feather 32

## Misc

Step that got ESP-PROG to connect:

Bizarrely it seemed that loading and then unloading these drivers are the change that caused it to work.


https://www.ftdichip.com/Drivers/VCP.htm
sudo kextunload /Library/Extensions/FTDIUSBSerialDriver.kext

### Helpful links to get the port connected

https://docs.platformio.org/en/latest/plus/debug-tools/esp-prog.html

https://community.platformio.org/t/esp-prog-debugging-on-a-mac-no-device-found/14658 


