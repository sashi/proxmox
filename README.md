# System
Fractal Design Define R5  
ASUS X99-A LGA 2011-V3  
Xeon E5-2687W V4 3GHz 3.5GHz Max Turbo 12 Core 24 Threads  
94GB DDR4 ECC  
GT710 - OS GPU   
NVIDA Telsa P4 - VM vGPU  
LSI 9207-8i
Zigbee2Mqtt USB Dongle  

# NAS Drive Breakdown
- OS BTRFS Mirror
  - 2x Intel SSDSC2KB240G7 DC S4500 240GB SATA SSD
- ZFS Pool Mirror - Containers
  - 2x Intel SSDSC2BX800G4 S3610 800GB SATA SSD
- ZFS Pool Mirror - Docker
  - Samsung 970 EVO Plus 250GB NVME M.2
  - Samsung 850 EVO 250GB SATA SSD
- ZFS Pool - Downloads 
  - TOSHIBA X300 5TB SATA HDD HDWE150
- ZFS Pool Mirror - Photos 
  - 2x Micron 1300 512GB SATA SSD
- ZFS Pool RaidZ2 - Media
  - 2x Seagate Barracuda 10TB SATA HDD ST10000DM0004-1ZC101
  - 2x Western Digital 10TB SATA HDD WD100EMAZ-00WJTA0
  - Seagate Barracuda 10TB SATA HDD ST10000DM005-3AW101
  - HGST Ultrastar 12TB SATA HDD HUH721212ALN600  
- ZFS Pool Mirror - Backups
  - Crucial MX500 1TB SATA SSD
  - Samsung PM863 960 SATA SSD  

# Future Upgrades
5060TI  - Replace with P4 - ~$500 CAD  
Remove 6TB SATA for Container backup and replace with 1x1TB Cruical & 1x 960GB SSD  
Place 1x Intel 800GB into containers 
