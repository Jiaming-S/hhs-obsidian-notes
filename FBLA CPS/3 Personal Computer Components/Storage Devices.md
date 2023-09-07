Used to store and retrieve data

Examples:
- HDD (Hard Disk Drive)
- SSD (solid state drive): 
	- Sometimes uses [[SATA Cable]] 
	- [[NVMe]] created to match SSD throughput instead of legacy SATA
		- Uses [[M.2]] connectors; can connect to [[PCI Slot]]
- [[Optical Drives]]
	- CD, CD-ROM, DVD
	- Laser to read and write bumps
	- Note: CD-ROM is "read only" but rewritable versions exist
- [[Cartridge Drives]]
	- Basically hard drive but the medium is a cartridge that can be removed
	- Magnetic Tape drives, Magnetic disks, 
	- Floppy Disks 
- [[Flash Drives]]
	- Non-volatile, limited number of writes

[[RAID]]: redundant array of independent disks
- RAID 0:
	- Write all data evenly between multiple drives
	- Performance increase but failure breaks array
	- 0 = 0 redundancy
- RAID 1: 
	- Mirror data to multiple drives
	- Required disk drive is doubled
- RAID 5:
	- Put pieces of data across drives but additional drive per block used as parity
	- More efficient 
	- Can recover information using parity
- RAID 10: (1 + 0)
	- Mirror all RAID 0 arrays 
	- Needs at least 4x storage




