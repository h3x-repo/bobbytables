## Pwnagotchi + PiSugar 2 Force Manual Button

I just got my PiSugar 2 battery the other day and after spending the better part of a week figuring out how to get bluetooth tethering to work, I didn't see much use to constantly having to plug the device into the USB data port in order to send handshakes to wpa-sec, so I wanted to make a double press of the battery button reset the pwnagotchi to manual mode. Tried several different things, but with the help of <a href=https://www.reddit.com/user/noxiouskarn/>/u/noxiouskarn</a> I managed to figure out the right commands and build a simple shell script to accomplish exactly what I wanted.

Just clone `restart_manu.sh` to the `/home/pi/` directory on your pwnagotchi, then insert the following into the appropriate space on the PiSugar manager UI, reboot the device and it should work as intended.

`sudo /home/pi/restart_manu.sh`
