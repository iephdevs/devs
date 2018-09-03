# VPSAutoScrptz
Tunneling Service:  

* OpenSSH : 22, 444   
* Dropbear : 443,80
* SSL : 442
* Squid3 : 80,8888,8000,8080,3128 (limit to IP SSH)     
* OpenVPN : TCP 1194 (client config : http://myip:81/client.ovpn)    
* badvpn : badvpn-udpgw port 7300    
* nginx : 81

# Installation
debian Only: wget https://raw.githubusercontent.com/iephdevs/devs/master/ieph.sh && chmod +x ieph.sh && ./ieph.sh


Original script by :
* Fornesia
* Rzengineer
* Fawzya
