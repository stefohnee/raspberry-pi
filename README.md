# raspberry-pi
This repo is for me to play around with the Raspberry Pi. Here's what I did to get mine up and running without needing to connect it to an external monitor/keyboard/mouse. All you need is your Raspberry Pi, an ethernet connection, and OSX terminal window.

## Headless setup
### Log in using SSH and update
```
ssh pi@xxx.xxx.xxx.xxx
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install tightvncserver
tightvncserver
```

###Connect using VNC
Open Finder, and from the "Go" menu, select "Connect To Server..."
Enter vnc://xxx.xxx.xxx.xxx:5901

### TODO
* Get [WiFi](http://raspberrypihq.com/how-to-add-wifi-to-the-raspberry-pi/) working!

#### References
https://www.raspberrypi.org/forums/viewtopic.php?f=91&t=74176

