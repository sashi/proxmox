# System
Fractal Design Define R5  
ASUS X99-A LGA 2011-V3  
Xeon E5-2687W V4 3GHz 3.5GHz Max Turbo 12 Core 24 Threads  
94GB DDR4 ECC  
GT710 - OS GPU   
NVIDA Telsa P4 - VM vGPU  
LSI SAS  
Zigbee2Mqtt USB Dongle  

# NAS Drive Breakdown
- OS BTRFS Mirror
  - 2x Intel SSDSC2KB240G7 DC S4500 240GB SATA SSD
- ZFS Pool - Containers
  - Intel SSDSC2BX800G4 S3610 800GB SATA SSD
- ZFS Pool Mirror - Docker
  - Samsung 970 EVO Plus 250GB NVME M.2
  - Samsung 850 EVO 250GB SATA SSD
- ZFS Pool Mirror - Downloads 
  - Seagate Barracuda 6TB SATA HDD ST6000DM003
  - TOSHIBA X300 5TB SATA HDD HDWE150
- ZFS Pool - Photos 
  - Crucial MX500 1TB SATA SSD CT1000MX500SSD1
- ZFS Pool RaidZ2 - Media
  - 2x Seagate Barracuda 10TB SATA HDD ST10000DM0004-1ZC101
  - 2x Western Digital 10TB SATA HDD WD100EMAZ-00WJTA0
  - Seagate Barracuda 10TB SATA HDD ST10000DM005-3AW101
  - HGST Ultrastar 12TB SATA HDD HUH721212ALN600



# Future Upgrades
X399 AORUS Gaming 7  
AMD Ryzen Threadripper 1950X 3.4GHz 4GHz Boost 12C/32T or AMD Ryzen Threadripper 1920X  3.5GHz 4 GHz Boost 12C/32T  

PCIe to Quad U.2 Card  
2x 1.2TB U.2 Drives  
Move containers to 2x 1.2TB mirrored  
Remove Toshiba 5TB  
Use Seagate 6TB ZFS Single for Downloads (zfs detach downloads device, zpool remove downloads device)  
Get another 256GB NVME M.2 - Gives me 2x 256GB NVME M.2 - Use that for Docker ZFS Mirror  
Remove 250GB Sasmung 850 EVO  
Move Intel SSDSC2BX800G4 S3610 800GB & add to photos for ZFS mirror (zfs attach pool drive1 drive2)  
GTX 5060ti  

