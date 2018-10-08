Intruder: The automated Wi-Fi Intrusion Script.
-----------------------------------------------

Prerequisites:
--------------
SSID and Password of WiFi,
Python2,
Termcolor(will install if you don't have),
Linux,

How to setup:
--------------
chmod +x setup.sh
./setup.sh

Usage:
--------------
intruder -random (picks a random host and mac spoofs),
intruder -choice (lets you choose),
intruder stop (Cleanly disconnects you from network and stops mac spoofing)

What it does:
--------------
It will ask you to input the login details to the target access 
point. Then it will connect (obviously). Following connection, 
it will search for hosts on your network, and collect them as a 
list. Following that, it will either select a random one for you 
to macspoof, or allow you to choose, based on the argument you 
provide. When you have successfully spoofed your mac address, 
Intruder has finished it's job and will close.

Issues:
--------------
Please report any issues to the Issues tab or email me at 
odinsecurity@protonmail.com

