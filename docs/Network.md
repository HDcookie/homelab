# Network 

Currently, the entire network structure is very flat and basic, with everything connected to the same switch and on the same subnet.  The router gets the interet from my family's wifi network (WAN), and talks to the LAN through the ethernet port.   

### Hardware
- NetGear GS110TPv3 8-Port Gigabit Smart Managed Pro Switch with PoE+ and 2 SFP Ports
- Raspberry pi 4 as a router, running OpenWRT
- Custom built desktop PC/server with Intel i7-6700, 32GB DDR4, GeForce GTX 1060 6GB, 256GB Samsung SSD, 
- GL.Net wireless router running in AP mode


### IP's
- router's internal IP: 192.168.1.1
- router's external IP: 10.0.0.185 (likely to change, as it's acting as a regular DHCP client to the external network)
- AP: 192.168.1.113
- Switch: 192.168.1.202
- Macbook: 192.168.1.142
- Main server/homelab: 192.168.1.129




