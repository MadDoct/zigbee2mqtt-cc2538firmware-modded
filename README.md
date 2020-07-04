# zigbee2mqtt-cc2538firmware-modded
Here you can find a modded version of the coordinator firmware provided originaly by modkamru for the cc2538, to be able to maintain bootloader active to reflash if you set PA7 low during boot (by connecting to gnd)
Based on the work found here:
https://pluspda.ru/blog/aliexpress/79984.html
You can flash it using UART - https://github.com/JelmerT/cc2538-bsl

You should flash this firmware as soon as you get your CC from factory because if you flash another one, the bootloader will be locked and you'll only be able to flash using JTAG...
