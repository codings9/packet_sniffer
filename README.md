On your Linux machine.
Just type: ifconfig.
Then change the network interface on the script: eth0, lo, or wlan0
Last line in the code.
sniff("wlan0")

So if it is eth0, 

You would change to 

sniff("eth0")

Then:
python packet_sniffer.py

Video here:
https://www.youtube.com/watch?v=rys-wmsZS70
