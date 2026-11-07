# Homelab
Self-hosted infrastructure for learning networking, cybersecurity, and DevOps, documented as I build it.


# Goals
These are both long term and short term goals I plan to complete using my own homelab
### Short term goals
- Install a program like Uptime Kuma for a central monitoring system.
- VPN for remote access.
- Reverse Proxy or Tunnel for public access to my internal services (ex. port forwarding my mc server)
- Minecraft server & jellyfin server
- Backups for all VM's in a centalized location
- Create my own docker image for my discord bot.  
- Setup infrustructure as code?  Either for basic vms, for pre-configured minecraft vms, etc.   
- Create a Dev server for MC, compleate with a pipeline from my IDE -> test enviorment.  
### Long term goals
- Harden the homelab: firewall, VLAN separation, key-only SSH, etc.
- Minecraft server network with Kubernetes.
- Password manager for all my devices. 
- Custom tuned pi-hole for blocking ads.
- Local AI model and custom AI harness connected to all of my data and services to keep my personal data centralized.  

# Hardware & Networking
### Hardware:
- NetGear GS110TPv3 8-Port Gigabit Smart Managed Pro Switch with PoE+ and 2 SFP Ports
- Raspberry pi 4 as a router, running OpenWRT
- Custom built desktop PC/server with Intel i7-6700, 32GB DDR4, GeForce GTX 1060 6GB, 256GB Samsung SSD, 
- GL.Net wireless router running in AP mode

### IP's:
- router's internal IP: 192.168.1.1
- AP: 192.168.1.113
- Switch: 192.168.1.202
- Main server/homelab: 192.168.1.129

# Repo structure
/docs is the documentation of what is in my homelab, updated as I go.

/logs is almost like blog posts.  They document every major project I undertake, including the thought behind the plan, the steps I took, issues I faced, how I solved them, and conclusions from the projects.

/configs is where config files such as VM templates and infustructure as code will live.  