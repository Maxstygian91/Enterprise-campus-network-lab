# Enterprise Campus Network Lab

## Overview

This project simulates a small-to-medium enterprise campus network using Cisco Packet Tracer.

The network consists of multiple departments connected through VLAN segmentation, redundant multilayer switches, and OSPF dynamic routing.

## Features

- VLAN Segmentation
- Inter-VLAN Routing
- OSPF Area 0
- Redundant Core Architecture
- DHCP Server
- DNS Server
- FTP Server
- Web Server
- Wireless LAN

## Network Architecture

The design follows a hierarchical campus network model with:

- Access Layer
- Distribution/Core Layer
- WAN Layer

## VLAN Structure

| VLAN | Department | Subnet |
|--------|-----------|---------|
| 10 | HR | 192.168.1.0/24 |
| 20 | Office | 192.168.2.0/24 |
| 30 | Library | 192.168.3.0/24 |
| 40 | Printer | 192.168.4.0/24 |
| 50 | IT | 192.168.5.0/24 |
| 60 | Server Room | 192.168.6.0/24 |

## Technologies Used

- Cisco Packet Tracer
- VLAN
- IEEE 802.1Q Trunking
- Inter-VLAN Routing
- OSPF
- DHCP
- DNS
- FTP
- Wireless Networking

## Validation

- End-to-end connectivity verified
- OSPF neighbor relationships established
- Inter-VLAN communication tested
- Server accessibility verified

## Network Topology

[Topology](Topology.png)

## Author

Abdul Razzaq
Data Center Technician
