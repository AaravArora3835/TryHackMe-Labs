# Room 05 — Intro to LAN

**Date:** 2026-02-01  
**Path:** Pre Security  

## What I did
- Learned how local area networks are structured

## Key concepts
- Switches, routers, and end devices
- How devices communicate within a LAN
- Ring Topology: Devices are connected to each other, however one device gone means packets gone to another device as well and most likely the whole network is gone,
however it is very cost efficient.
- Bus Topology: All devices are on a single cable (backbone). Data gets sent left and right down the backbone until it reaches the target.
However, it cannot handle a large amount of data.
- Star Topology: All devices are connected to a single switch/hub with their own cable attached. Every packet is sent towards this switch,
meaning once the switch is down the network is down.
- Subnetting is a splliting up the network into smaller networks, which provides efficiency, security, and full control.
- 32 bits in a subnet mask.
- Network address is used to idenity the start of a network.
- Host Address is used for idenitfying devices in a network.
- Default Gateway is used to idenitfy the device responsible for sending data to another network.
- ARP or Address Resolution Protocol is the techonolgy that allows devices to idenitfy themselves, so they could keep their own MAC address or IP address with themselves.
- Devices use ARP to help find other devices that they want to communicate with.
- ARP Request: message is sent on the network asking to other devices "What is the mac address that owns this IP address"
- ARP Reply: Once that message is received on the devices in the network then the respond with a ARP Reply which has the MAC address.
- Now once the device which asked for the ARP contains the information in it's ARP cache for future use.  
- DHCP is the Dynamic Host Configuartion Protcol which automatically assigns IP addresss.
- When a device has not ebeen manueally assigned a IP address then they send a request to the DHCP Discover to see if any DHCP are on the network.
Then the DHCP server responds and gives a DHCP offer with the IP Address. The device which wants the IP Address sents the DHCP Request asking for the IP.
Lastly the DHCP sends a reply knowing its done and the device can use the IP which is DHCP ACK.
## One takeaway
- LANs allow devices to communicate efficiently within a local network
