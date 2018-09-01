# VPSAutoScrptz
Tunneling Service:  
OCS Panel: 85   
OpenSSH : 22, 444   
Dropbear : 143, 3128    
SSL : 443     
Squid3 : 8000, 8080 (limit to IP SSH)     
OpenVPN : TCP 1194 (client config : http://myip:81/client.ovpn)    
badvpn : badvpn-udpgw port 7300    
nginx : 81

# Installation
debian Only: wget https://raw.githubusercontent.com/iephdevs/devs/master/ieph.sh && chmod +x ieph.sh && ./ieph.sh


Original script by :
* Fornesia
* Rzengineer
* Fawzya
