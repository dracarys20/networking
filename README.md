# Networking CCNA

When two or more devices are connected together through physical/logical connection for resource sharing or services, that forms a **network**

- LAN enables devices within small geographical area to connect and communicate with each other. 
- WAN enables a large geographical area connect each other, often covering multiple LAN's.
- Internet is a global network that connect billions of devices together through WAN.
- Intranet is a private network that exsists in the internet, typically uses LAN infrastructure to create a controlled and secure enviromnet for services and resource sharing. (VPN is diffrent, it provides an encrypted secure channel to communicate. it can connect to an intranet from remote location through public network (internet))

Wi-Fi (Wireless Fidelity) uses radio waves to transmit data wirelessly between devices.
Ethernet typically uses copper cables for wired connection. 

**Internetworking** is a technique of connecting different networks or network segments by using network devices such as router, switches, access points and more.

## Hub
Hub is a basic networking device that operates at physical layer (1) of OSI model. It simply connects multiple devices, when a device sends data through hub, it broadcasts that data to all the connected devices. This inefficeincy results in network congestion (taking up bandwidth). As hub runs in half duplex transmission mode, only one device can communicate at a time, There is no simultaneous transmission and receiving while using a hub. Since all traffic are shared, an attacker can eavesdrop on the communication through a compromised device or through physical port connection. Through further escalations, the attacker can ARP poison the network for MAC and IP for spoofing and MTM, this is an inherent security risk. 

Speed- 10Mbps, Ports- 4/12,  Transmission type- Frame flodding unicast, broadcast or multicast

_unicast-one to one, multicast- one to many or many to many, broadcast- one to all communication_

## Switch
Switch is an advanced networking device that operates at Data Link layer (2) of the OSI model. It is responsible for receiving, processing, and forwarding network traffic based on destination MAC addresses. They provide both half & full duplex transmisssion mode, increasing network transmission speed, elliminating collisions and the need for Carrier Sense Multiple Access with Collision Detection (CSMA/CD) protocol. This means every switch port is its own collision domain that provides its own independent bandwidth.

Speed- 10/100Mbps, Ports- 4 and 48,  Transmission type- First broadcast, unicast and/or multicast



In **Half-duplex communication**, the cable uses only one wire pair with a digital signal running in both directions on the wire. Both are responsible for transmitting and receiving, which is why we end up with collisions. **Full-duplex communication** uses two pairs of wires at the same time instead of a single wire pair. One pair of wires is used for transmitting and the other pair for receiving. This increases network transmission and eliminates collisions altogether since the wires are separated.

*In **CSMA/CD**, a node senses if the wire is busy. If another node happens to be transmitting at that moment, the node will wait a few milliseconds and rechecks the wire. If the wire is free, the node can send out its frame. The wire is essentially first-come-first-serve. When a collision is detected on the wire, all nodes stop transmitting and random “backoff” algorithms determine how long each node must wait in milliseconds before they can retransmit again. The node with the lowest random number will get to transmit first, but once the timers run out, all nodes have equal priority to retransmit.*

*Network Interface Card is a circuit board that is installed on a computer to connect to the network. Network adapter encompasses both hardware (NIC) and driver components responsible for network communication*



