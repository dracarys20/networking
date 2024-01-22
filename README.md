# Networking CCNA

When two or more devices are connected together through physical/logical connection for resource sharing or services, that forms a **network**

- LAN enables devices within small geographical area to connect and communicate with each other. 
- WAN enables a large geographical area connect each other, often covering multiple LAN's.
- Internet is a global network that connect billions of devices together through WAN.
- Intranet is a private network that exsists in the internet, typically uses LAN infrastructure to create a controlled and secure enviromnet for services and resource sharing. (VPN is diffrent, it provides an encrypted secure channel to communicate. it can connect to an intranet from remote location through public network (internet))

Wi-Fi (Wireless Fidelity) uses radio waves to transmit data wirelessly between devices.
Ethernet typically uses copper cables for wired connection. 

Internetworking is a technique of connecting different networks or network segments by using network devices such as router, switches, access points and more.

##Hub
Hub is a basic networking device that operates at physical layer (1) of OSI model. It simply connects multiple devices, when a device sends data through hub, it broadcasts that data to all the connected devices. This inefficeincy results in network congestion (taking up bandwidth). As hub runs in half duplex mode, only one device can communicate at a time, There is no simultaneous transmission and receiving while using a hub. Since all traffic are shared, an attacker can eavesdrop on the communication through a compromised device or through physical connection. Through further escalations, the attacker can ARP poison the network for MAC and IP for spoofing and MTM, this is an inherent security risk. 
