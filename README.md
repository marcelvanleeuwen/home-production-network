# My HomeLab setup :house:

![Homelab_30-5-25](images/Homelab_30-5-25.jpeg)


#### Gear :gear:

  - UDM Pro SE
  - USW-Aggregation
  - 2x U6 Pro
  - G4 Instant
  - UNAS Pro
  - 3x Minisform MS-01 / i9-13900H, 96GB, 1TB NVMe (PVE)
  - 1x Minisform MS-01 / i5-12600H, 32GB, 1TB NVMe (PBS)
  - CyberPower UPS


#### Unifi :globe_with_meridians:

My network is built using Unifi devices, and for storage, I rely on a U-NAS Pro unit with a couple of 22TB drives." 

#### Minisforums :computer:

The Minisforum MS-01 is a compact, high-performance mini workstation/server designed for professional and homelab use. It's packed with powerful features like 2.5gbe ethernet, SFP+ that make it suitable for virtualization, containerization, and other homeLab stuff.


#### Software :toolbox:

- Unifi Network
- Unfi Drive
- Unifi Protect
- Proxmox Virtual Enviroment (Type 1 Hypevisor)
- Proxmox Backup Server


#### VM's (Virtual Machines) :package:

- Uptime Kuma
- Wazuh
- 8 Cumulus Nodes (Runonflux project expalined below)
- 6 Presearch nodes (Presearch project explained below)
- 1 Neoxa master node
- 1 Netsis master node
- Windows 11 Pro
  

#### Storage :floppy_disk:

- VM's run at the moment on local storage
- Data shares via NFS mounts to UNAS Pro
  

#### What is RunOnFlux? :white_check_mark:

RunOnFlux is a decentralized cloud computing platform that allows users to rent out their computing resources (like CPUs, GPUs, and storage) to run applications, host services, or perform tasks in a distributed network. It is part of the Flux ecosystem, which aims to create a decentralized infrastructure for Web3 and cloud-native applications.

The idea is to build a peer-to-peer network of nodes that provide computing power and resources in a decentralized way, removing the need for traditional centralized cloud providers like AWS, Google Cloud, or Azure.


#### What is Presearch? :white_check_mark:

Presearch is a decentralized search engine that prioritizes user privacy, transparency, and control over the search experience. Unlike traditional search engines like Google, which collect and monetize your search data through advertising, Presearch focuses on protecting your privacy and rewarding users for using the platform.

Presearch leverages blockchain technology and a community-driven model. Users can earn Presearch’s native token (PRE) by performing searches and can use these tokens within the ecosystem. The platform also supports independent content and advertisers without a centralized intermediary.


#### What is Neoxa? :white_check_mark:

Neoxa is a blockchain-based project that merges gaming with cryptocurrency. It allows gamers to earn Neoxa Coins (NEOX) by playing popular games. The idea is to bridge traditional gaming with the Web3 ecosystem, enabling players to "play and earn."


#### What is Netsis? :white_check_mark:

Netsis (NET) is a blockchain project focused on providing cybersecurity solutions. It aims to integrate blockchain technology with cybersecurity services, offering tools for endpoint protection, data security, and user behavior analytics. The project operates its own blockchain and has a maximum supply of 210 million NET tokens.


#### Hardware I like to add or change :moneybag:

- Pro Max 24
- Pro XG 10 PoE
- U7 Pro XG
- A second UNAS Pro with only SSD storage or a NVMe storage device.
- Upgrade the MS-01 from 96GB to 128GB memory
- Seperate Kubernetes cluster? :)