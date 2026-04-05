# Homelab
In this page, I have created an overwiev of everything thats running (and not running) in my homelab.

##Hardware
### My Proxmox server
As an primary server i run an ** Dell Optiplex 3060 mini **. This fits nicely in my 10 inch rack and has everything i need for running light tasks. I am planning to create a Proxmox cluster using 4 of these systems, but I am holding that project. The main reason being that in Finland one of these at a reasonable price (100€ is my base) is kind of hard to find and i would propably need a new rack for all of this.

Specs:
-120gb SSD

### My NAS
As my NAS i bought a really cheap system only for 40€. This is an ** HP Elitedesk G1 800 MT **. I needed a NAS for important backups such my big coding projects (my friend almost his kernel he has been building for half an year) and as storage for Jellyfin running on the Optilex (I know, it is janky). It is not the fastest, but it has upgradibly options for me. Whit no PCIE cards now installed, i could easily put a NVME drive adapter or faster networking. My setup is less than ideal becouse currently I have only an boot SSD and one 4tb HDD storage drive. If this fails, all my data goes away, but that SSD came whit the PC and i had one of those 4tb HDD in hand. 4tb is kind of overkill, whit my primary laptop having 1tb it is 4 times the storage (TOTALLY overkill for Jellyfin and one or two C# scripts) , but it works.

NAS OS: TrueNas

Upgrades I have done:
-Noctua fan swap
-Added 4tb HDD

Specs:
-120gb SSD (boot drive)
-4tb HDD (storage)


### Pi's and stuff
After all, my rack is a minirack and whit my primary source of inspiration beeing Jeff Geerling, of course i have to have some Pi's! 
I have a Raspberry Pi 5 running Home Assistant. While it dosen't do anything becouse my smart home is the Tapo ecosystem i am planning to make some custom IOT devices whit Pico's and ESP32's, this will work whit them. Also i am going to put a Pico based display in the rack showing performance from the servers and it will get the data from Home Assistant. 
In addition, i am planning on adding a Raspberry Pi Zero just for some whatsapp messaging to remind my guests to water my flowers while i am away!

