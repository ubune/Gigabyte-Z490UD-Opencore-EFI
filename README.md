# EFI Opencore 0.6.5 for Gigabyte Z490UD
I created an EFI folder for a Hackintosh with a Gigabyte Z490UD Motherboard.

- You must adapt your Platform info (Serial Number, MLB, ROM, UUID) if you want to use Facetime/Imessage.
# Bios Settings

|  |  |
| ------------- | ------------- |
| CSM  | Disable  |
| Serial Port  | Disable |
| Internal Graphic  | Enable  |

# Operating system

| Tested On | 
| ------------- |
| Mac Os Big Sur 11.2 | 
| Mac Os Big Sur 11.1 | 

# Bootloader
| BootLoader | 
| ------------- |
| Opencore 0.6.5 |


# Hardware Info
| Component | Info |
| ------------- | ------------- |
| Motherboard |Gigabyte Z490UD |
| CPU  | Intel i7 10700K  |
| iGPU  | Intel® UHD Graphics 630 |
| RAM  | 2x8Go DDR4 3200 MHZ  |
| SSD Nvme  | Samsung 970 Evo  |
| Lan  | Realtek  |
| Audio | Realtek  |
| SMBIOS | Imac 20,1 |


# Dedicated GPU
- If you have a dedicated GPU (like the AMD 5700XT) you must :  
		- Disable the serial port on bios setting to avoid a blackscreen at boot  
		- Add "agdpmod=pikera" boot-arg  
		- Replace in config.plist AAPL,ig-platform-id from 07009B3E to 0300C89B   
		
# Credit
- [Acidanthera](https://github.com/acidanthera) 
- [Dortania](https://github.com/dortania)
- [WEB] Some discussions, Forum...

# If you like this depo, buy me a Coffee ! =)
- [Paypal](https://paypal.me/pools/c/8wGwagGlFS) 


