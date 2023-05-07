---
title: "Some info about stuff I do in my free time."
date: 2022-08-22T10:54:44-05:00
draft: false
---

---

I've been interested in Computing since I was 5. The main drive for it was being able to jump into a different world from the one around us. 

It has evolved, -or devolved depending on who you ask- into having a miniature Datacenter in my basement. I currently have: ~~Dell R610, R620, three~~ Six Intel NUC's, and two Raspberry Pi's as compute, 
Then I have a Synology DS920+ dedicated to storage(32TB). 

---

3X node of NUCS running Proxmox VE as a hypervisor | Cluster name: Clusterfart

Hostname1: ClusterNode1

Hostname2: ClusterNode2

Hostname3: ClusterNode3

VM's:

- Ubuntu Server
	- Runs local Ubuntu software repository
- Arch Linux
	- Runs local AUR and Arch software repository
- Windows 10
	- To run my Windows software. I have a USB controller assigned to this VM so I can run some Amateur Radio software in tandem with radio control
- RHEL
	- Runs Schedulix ESP (Open Source Event Scheduler)
- Mumble Server
	- Voip server, Mainly for game chat.
- Ubuntu Server 20.04 whthin Docker containers for ease of updating.
	- Runs Plex Media Server, Sonarr, Radarr, Lidarr, NZBGet, Transmission, and Jackett. (Also known as the ARRRR stack)
- FreePBX
	- To connect to a private phone network
- Matrix Server on Alpine Linux
	- Chat Server for my friends and I. 
- Minecraft server on Alpine Linux
	- Obvious reasons
- Kali Linux
	- For playing around with
- Tailscale Jump Box on Alpine Linux
	- For friends to connect to to play Minecraft and use the Matrix server. 
- Windows 10 (With "uncomprimised" install snapshot)
	- Testing Windows Vulnerabilities with a VM that has `typical` applications installed initially.
- Ubuntu 20.04
	- Testing Linux software Vulnerabilities on a System that has the `typical` Web Server software installed.
- Roon Server on Ubuntu Server 20.04
	- High Res music server and stream integration service.
- LinuxGSM on Alpine Linux
	- Game Server Manager for 100+ multiplayer games.
---

NUC 1: Debian Stable | Hostname: MusicBox
- Volumio
	- Music player
		- Topping D90 / A90 stack

---

NUC 2: Compute agent for Schedulix | Hostname ForestGump

Main tasks include: 

- Recursively mirroring 10 websites daily and uploading to archive.org
	- Mower County Jail Roster
	- City Of Austin 
	- Austin Daily Herald
	- Various Twitter accounts
	- Winworld
	- RadioReference frequency databases organized by state.
	- Ham radio manufacturers, for purposes of service manuals. 
- Running backup jobs for my network configurations, and data to a Hetzner backup server.
	- Rsync endpoints to the NAS
		- Rsync NAS to Hetzner

---

NUC 3: High Avail / failover for NUC 2 | Hostname: Jenny

---

Raspberry Pi 4 4GB running Debian Stable | Hostname: ApplePie
- Agate (Gemini protocol server)
- Searx search engine
- RTLDump (Python program I wrote to constantly record a single radio station with the help of an RLT-SDR)
- Librespeedtest

---

Raspberry Pi 8gb running Ubuntu 20.04 | Hostname: Gibson
- (temporary) Plex testing server, to see how well it works on ARM
- TK4 System370 Mainframe emulator.
- Speedo: A tool I wrote to take an hourly speedtest.net and DSLreports.com speed test, and puts them in a LibreOffice spreadsheet to give me daily averages in charts for Latency, and bandwidth throughput.

---

All of this is tied to the internet via a multi-NIC machine running PFSense. 
It's a lack luster set up as my network is small. But the best feature allows me to wireguard VPN into my house so I don't have to expose any ports aside from two UDP ports. One for the Linode tunnel, and one for the Direct connection. 

---

# HRCC WIKI
[HRCC.WIKI](https://hrcc.wiki)

The other moderators of [Ham Radio Crash Course](https://hamradiocrashcourse.com) and I started the Ham Radio Crash Course Wiki, (Still a work in Progress as we all have full time + jobs and limited free time as it is) 
It's a central repository that will have a large base of knowledge for all things Ham Radio. 
This started due to us needing a centralized resource that wasnt tied to any resources we lacked full control over. 
the reason we chose Wiki.js as the platform is due to it's more modern interface compared to MediaWiki, ease of install / configuration, and it's portability to any other Wiki platform due to the use
of Markdown as the source material.

---

# Art Bell Live
[ARTBELLLIVE.COM](https://artbelllive.com)

I have insomnia. This radio program (Coast To Coast AM) talks about the parannormal, and spooky things of the world. 
I wrote up a 90's esque site, and offer a radio stream for other insomniacs. Almost 10k views. Kinda cool. 
It uses Icecast on the backend for the audio stream. I have spent years finding, buying tapes of the shows and digitizing them for listening. 
This also simulcasts on a Part 15 certified FM transmitter at my house So I can set a sleep timer on my alarm clock radio and listen to it as I fall asleep without headphones or network connected gear. 

---

# The Spoop
[THESPOOP.SUBSTACK.COM](https://thespoop.substack.com)

I have decided to culminate a few stories I see every day, save them to the Wayback Machine and then share them to readers. Subscribe if you're into Paranormal, Space, Aliens, and conspiracy stuff.

<center><iframe src="https://thespoop.substack.com/embed" width="480" height="320" style="border:1px solid #EEE; background:white;" frameborder="0" scrolling="no"></iframe></center>

---

```
  ________       ___    ___ ________    _____     
 |\   ____\     |\  \  /  /|\   ____\  / __  \    
 \ \  \___|_    \ \  \/  / | \  \___|_|\/_|\  \    
  \ \_____  \    \ \    / / \ \_____  \|/ \ \  \   
   \|____|\  \    \/  /  /   \|____|\  \   \ \  \ 
     ____\_\  \ __/  / /       ____\_\  \   \ \__\
    |\_________\\___/ /       |\_________\   \|__|
    \|_________\|___|/        \|_________|         
```

![Image](/img/vaporwav3.png)
