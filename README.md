# Small Business Network Lab

## Overview
This project is a beginner networking lab built using Cisco Packet Tracer. It simulates a small office network with one router, one switch, and three PCs.

The goal was to practice basic network configuration, IPv4 addressing, and connectivity testing.

## Network Topology
- 1 Cisco router (R1)
- 1 Cisco switch (SW1)
- 3 PCs (PC1, PC2, and PC3)

The PCs connect to the switch, which connects to the router.

## IP Addressing

| Device | IP Address | Subnet Mask | Default Gateway |
|---|---|---|---|
| R1 | 192.168.10.1 | 255.255.255.0 | N/A |
| PC1 | 192.168.10.10 | 255.255.255.0 | 192.168.10.1 |
| PC2 | 192.168.10.11 | 255.255.255.0 | 192.168.10.1 |
| PC3 | 192.168.10.12 | 255.255.255.0 | 192.168.10.1 |

## Skills Practiced
- IPv4 addressing and subnet masks
- Router interface configuration
- Enabling interfaces with `no shutdown`
- Connecting devices in Cisco Packet Tracer
- Testing connectivity with `ping`
- Basic network troubleshooting

## Connectivity Testing
I used ping tests from PC1 to verify connectivity to:
- The router (R1)
- PC2
- PC3

The successful ping tests confirmed connectivity between devices on the local network.

## Tools Used
- Cisco Packet Tracer

## Project Files
- `small-business-network.pkt` — Packet Tracer lab file
- `2-screenshots/` — Screenshots documenting the configuration, connectivity tests, and final topology

## Learning Goals
This is an introductory hands-on project as I continue developing my networking skills and working toward networking and cybersecurity roles. Future projects will build on these fundamentals with network security and defensive security labs.
