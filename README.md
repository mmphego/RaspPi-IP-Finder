# RaspPi-IP-Finder
The Pi IP Finder is intended to work with the [latest version of Raspbian][1],
so please make sure you have installed Raspbian on your SD card before continuing.

You have your brand new Raspberry Pi, and you are ready to get hacking...  Only
problem is, you dont have an extra HDMI monitor and keyboard.  So how can you
find out the IP network address? PI IP FINDER TO THE RESCUE!  Run this
cross-platform application to locate your Raspberry Pi's IP address.

[1]: http://www.raspberrypi.org/downloads/

## Step 1 on local PC
- Copy Raspbian image to SD card
- Open terminal and go to your SD card directory

## Step 2 on local PC

- sudo cp rc.local to /mnt/sd_card/etc/rc.local
- Add your details on whats_my_ip.py script
- cp whats_my_ip.py to /mnt/sd_card/home/pi
- umount sd_card
## Step 3 on RPi
- Insert SD card and boot
- Wait for the magic to happen, if no magic happens,
- Shutdown, insert SD card to local pc, access SD card and on root directory you should notice a file 'my_ip.txt'
- Done
