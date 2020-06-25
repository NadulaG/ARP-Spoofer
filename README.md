# ARP-Spoofer
An easy-to-use ARP Spoofer that sends falsified ARP messages over a local network. (Debian Linux)

Before using, enter the appropriate target_ip & gateway_ip values (on lines 26 & 27). You can find these using my [Network Scanner](https://github.com/NadulaG/Network-Scanner) and by running the route -n command. Then, run the following command in terminal: `echo 1 > /proc/sys/net/ipv4/ip_forward`

Usage: `python arp_spoof.py`
