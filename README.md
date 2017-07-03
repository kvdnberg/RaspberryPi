# RaspberryPi
Dashboard setup on Raspberry Pi

This repo contains some configuration files to have the Raspberry Pi startup with Chrome in kiosk mode. It also contains a fix for the Restore popup Chrome displays when Chrome wasn't shutdown properly (which happens when you cut the power from the Raspberry Pi instead of doing a normal shutdown, which is often the case if it's hooked up to a TV using USB power). 

Files:

~/.config/lxsession/LXDE-pi/autostart

~/chrome_startup.sh
