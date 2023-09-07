
Basic Input Output System

Stored in ROM/Flash memory

then runs a [[POST]] 
then looks for a [[Bootloader]]

[[CMOS]]:
- Complementary metal oxide semiconductor
- Now replaced with flash memory 
- Needs battery on older devices to maintain date/time 
	- Can reset BIOS by removing and reinserting the battery
	- Modern computers can reset by shorting two pins

[[Legacy BIOS]]:
- unable to add anything
[[UEFI Bios]]
- Unified Extensible Firmware Interface
- Replaces legacy BIOS
- Most computers use this
- Secure Boot:
	- Verify signature of bootloader to ensure OS isn't modified by comparing with a public key
	- Password protect starting operating system

[[TPM]]:
- Trusted platform module
- Cryptography 

Setup:
- Special keys to access BIOS config:
	- Del, F1, F2, Ctrl-S, Ctrl-Alt-S
- Note: Fast Startup on windows 8, 10, 11 doesn't actually reboot
	- Hold shift when clicking restart
	- Or change msconfig





