# Network Plan

## Current Network

### Internet Gateway / Router

- Router model:
- Router IP:
- DHCP range:
- Subnet:
- DNS servers:

### Physical Devices

| Device | Role | Connection | IP Address | Addressing |
|---|---|---|---|---|
| Mac Pro 2013 | Proxmox Host | Ethernet | TBD | Static |
| Synology DS412+ | Backup NAS | Ethernet | TBD | Static |
| Gaming PC | Administration Workstation | Ethernet/Wi-Fi | TBD | DHCP |
| Home Router | Gateway / Firewall | Ethernet | TBD | Static |

## Planned Virtual Infrastructure

| System | Purpose | Type | IP |
|---|---|---|---|
| Proxmox VE | Hypervisor management | Physical Host | TBD |
| Home Assistant | Home automation | VM | TBD |
| Linux Server | Docker / Linux services | VM | TBD |
| Storage Server | SMB / storage experiments | VM/LXC | TBD |
| Networking Lab | DNS / DHCP / firewall testing | VM(s) | TBD |

## Future Network Segmentation

Potential VLANs:

- Management
- Servers
- IoT
- Trusted Devices
- Guest Network
- Lab Network
