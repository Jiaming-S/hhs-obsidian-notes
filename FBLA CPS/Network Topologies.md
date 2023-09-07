
[[Bus Topology]]:
- Computers connect to one central cable
- If one computer sends a packet, all other computers can listen to it but only destination accepts it based on MAC address
- Less cabling required 
- Limited on signal strength
- Security risk
- Poor redundancy
- Data collision (can be avoided using access control protocol)

[[Star Topology]]:
- Computers connected to central device ([[Hub]] / [[Switch]])
- Data routed to central device which broadcasts / unicasts information towards to other devices 
	- Hub broadcasts (unnecessary traffic), Switch unicasts (uses switch table)
	- Data has destination MAC address
- Less expensive
- Easy to reconfigure
- Good redundancy
- If central device fails, entire network fails
- Limited by interfaces on central device

[[Ring Topology]]:
- Computers connected to adjacent devices where data travels in one direction
- Easy installation and connection
- Less chance of data collisions
- Easy to troubleshoot
- Data has to travel between multiple computers to reach destination
- Closed loop paralyzes entire network
- Difficult to reconfigure
- [[Token Ring Topology]]:
	- Physical topology: star
	- Logical topology: ring

[[Mesh Topology]]:
- Each device has point to point link to every other device
- Difficult to manage
- Increases cost
- Eliminates traffic problems
- Good fault tolerance
- Requires many slots


