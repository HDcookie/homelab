# Homelab
Self-hosted infrastructure for learning networking, cybersecurity, and DevOps, documented as I build it.


# Goals/Plans
These are my goals and plans for my own homelab

### Future Projects
- DNS server for local domain names, split-horizon DNS, and ad blocking.  
- VPN for remote management, and wiregaurd on a remote VM for public access.  
- Backup management for my VMs
- Create my own docker image for my discord bot and deploy it myself.  
- Self hosted password manager
- NAS with redundency for backups, jellyfin, and my own persional storage.  


### IaC
My current plan is to use my Minecraft minigame server to test this architecture.  I plan to have nodes that can scale up and down with demand, a custom load balancer, and a CI/CD for configuration files and custom minigame code.  

### Security Audit
After I get a lot of basic services and systems running on my homelab, I plan to audit the security myself from both the inside and outside, document all findings and vulnerabilities, and then fix them.  I'd imagine this could include a stronger firewall, VLANs, and more.  





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