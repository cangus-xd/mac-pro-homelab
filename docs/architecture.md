# Homelab Architecture

## Host

The 2013 Mac Pro will serve as the primary virtualization host.

### Hypervisor

Proxmox VE

## Planned Virtual Machines and Services

### Home Assistant

Used for home automation and IoT device management.

### Linux Server

Used for Linux administration practice, Docker containers, automation, and server experimentation.

### Storage Services

Used for network-accessible storage, backup testing, and file-sharing experiments.

### Networking Lab

Used to practice:

- DHCP
- DNS
- Routing
- Firewall rules
- VLANs
- Network monitoring

## Planned Architecture

Internet

↓

Router

↓

Home Network

↓

Mac Pro

↓

Proxmox VE

↓

- Home Assistant
- Linux Server
- Storage Services
- Networking Lab

## Future Improvements

- VLAN segmentation
- Automated backups
- Monitoring dashboards
- Remote administration
- Infrastructure automation
