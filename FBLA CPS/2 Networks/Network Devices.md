
[[Router]]
- Forwards traffic between different IP subnets
- Layer 3 OSI
- Connect different types of networks together

[[Switch]]
- Forwards traffic based on MAC address
- Multilayer switch: has router capabilities
- Usually unmanaged switch: no way to query information
	- Low price, just connects everything together
- Managed switch:
	- Traffic prioritization
	- Connects to other switches: [[VLAN]]
		- Connects using 802.1Q
	- Port mirroring: capture packets to other port
- In large office: connects to Patch Panels which permanently connects to desks
	- Shorter cable between Patch Panel to switch
	- RJ-45

[[Hub]]:
- "Multi port repeater"
	- Just copy pastes into other ports
	- Everything half-duplex
- Less efficient
- 10 megabit/s

[[Modem]]:
- "Same cable for TV as internet"
- Transmission across multiple frequencies: [[Broadband]]
	- Video for TV, Phone Lines, Internet
- [[DOCIS]]: Data Over Cable Interface Specification
	- 1 gigabit/s available
- Connect to Data, Voice, or Video

[[DSL Modem]]: Digital Subscriber Line
- Uses telephone lines instead of TV lines 
- Sometimes called [[ADSL]]: Asymmetric ""
	- Download faster than upload 
- Signal too weak if 10,000 feet away
	- 52 mb/s to 16 mb/s 

[[ONT]]: Optical network terminal
- Fiber optic -> copper
- [[Demarc]]: splitting from ISP to personal network
	- Wires outside of Demarc is ISP responsibility
	- Wires inside of Demarc is your responsibility

[[Wireless Access Point]]
- Connects wireless network to wired network
- Often called bridge
- Also based on MAC address

[[Firewall]]
- Layer 4 OSI
- Can encrypt traffic in/out of network
- Can proxy traffic
- Basically sits at the "front" of network

[[Long Range Fixed Wireless]]
- Antenna
- Frequency use limited
- Power is regulated

[[Gateway]]:
- Acts as a node connecting two networks with different protocols

[[Bridge]]:
- Divides a LAN into multiple segments
- Used to reduce traffic
- Chooses to either send or not send traffic depending on MAC address
	- Useful for bridge networks

[[RFID]]
- Access badges, tracking etc

