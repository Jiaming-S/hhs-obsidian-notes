Integral files that allow a system to run

Examples:
- Bootloader
	- Contains necessary code to initialize system and start booting
- Kernel
- Drivers
- Config data
- Desktop File (Linux)
	- Database of information about files and icons

Mac:
- mach_kernel (aka Macintosh HD)
	- root directory
- boot.efi
	- Mac Bootloader 
- com.apple.boot.plist
	- Config settings, startup options
- Finder.app
	- applications

Windows:
- Note: root == %SystemRoot%\\... == C:\\Windows\\...
- ntoskrnl.exe
	- Windows NT Operating System Kernel
	- In root\\System32 directory
- bootmgr 
	- Windows boot manager
	- In root directory
- winload.exe
	- root\\System32
	- Loads windows kernel and drivers
- Registry Hives
	- root\\System32\\config
	- Windows registry data
- explorer.exe
	- file explorer
	- In root directory


