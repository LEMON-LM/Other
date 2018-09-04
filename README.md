# Other
#method to resolve some question
#################################
Ubuntu 16.04 after change python to python3.5,after Start system and login the system splash screen
#################################

sudo -dpkg –configure -a
报错：
Errors were encountered while processing:
	apport
	apport-gtk

sudo update-alternatives --config python 
-> change to python2.7 instead of 3.5

sudo apt install apport --reinstall

sudo apt-get install xserver-xorg-lts-utopic
sudo dpkg-reconfigure xserver-xorg-lts-utopic
reboot
