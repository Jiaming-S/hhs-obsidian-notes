
Connections between multiple devices or systems to facilitate communication. 

Protocols
- [[IP]] (internet protocol)
	- Addressing and routing packets across networks
	- IPv4:
		- 32 bits / address, 8 bits / section, 1 byte / section
		- eg. 192.168.0.1
			- Max num = 255
		- Gateway to communicate to outside: usually 192.168.1.1
		- Permanent usually ports 0-1023: usually well known
		- Temporary on port 1024-65535: determined in real-time
		- Note: port numbers not meant for security: port scanners
		- TCP 80 and UDP 80 works: diff protocols
	- IPv6:
		- 128 bits / address, 16 bits / section
		- Hexadecimal instead of number
		- eg. 2001:0db8:85a3:0000:0000:8a2e:0370:7334
			- First 4 sections usually network address, last 4 subnet address
	- Operates at network layer of OSI
- [[HTTP]] (hypertext transfer protocol)
	- Default port 80
	- Transferring hypertext resources on internet
	- Client server
	- GET, POST, etc
	- Stateless
- [[HTTPS]]
	- Port 443
- [[DNS]] (domain name service)
	- Default port 53
	- Translates domain names to IP addresses
	- Hierarchical, TLD's then sub path
- [[FTP]]: (file transfer protocol)
	- Default port 20/21
- [[SSH]]: secure shell
	- Default port 22
- [[Telnet]]: like SSH but not encrypted
	- Default port 23
- [[SMTP]]: simple main transfer protocol
	- Default port 25
- [[DHCP]]: dynamic host configuration protocol
	- Default port 67/68
	- Preconfigured pool of addresses to assign to people
	- Process: DORA to get new IP address
		- [D]iscover a DHCP server
		- server will [O]ffer an IP address
		- [R]equest to lock in offer
		- DHCP server [A]cknowledges  
- [[RDP]]: remote desktop protocol
	- Default port 3389
- [[SMNP]]: manage networking devices
	- Default port 161



