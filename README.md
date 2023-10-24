# Learning to use Arduino without the IDE

Install Dependencies `sudo apt install avr-libc avrdude binutils-avr gcc-avr`

Change your device in your make file if needed. `/dev/ttyUSB0` might be different for you check your `/dev` & `dmesg | grep usb` to see what you got.

Look at the assemby with `avr-objdump  -d -S led.o`
