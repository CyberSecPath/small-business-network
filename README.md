# Small Business Network — Cisco Packet Tracer

## Overview

This project demonstrates the design, configuration, and connectivity testing of a small business network using Cisco Packet Tracer. The simulated network consists of a router, a switch, and three end devices connected through a local area network (LAN).

The project documents the network topology, IPv4 addressing, subnet configuration, and connectivity verification using ICMP ping tests.

## Network Topology

The network includes the following components:

- **R1:** Router providing the default gateway for the LAN.
- **SW1:** Switch connecting the end devices.
- **PC1:** First end device.
- **PC2:** Second end device.
- **PC3:** Third end device.

The devices communicate over the `192.168.10.0/24` IPv4 network.

## Network Configuration

| Device | IP Address | Subnet Mask | Default Gateway |
|---|---|---|---|
| R1 — FastEthernet0/0 | `192.168.10.1` | `255.255.255.0` | N/A |
| PC1 | `192.168.10.10` | `255.255.255.0` | `192.168.10.1` |
| PC2 | `192.168.10.11` | `255.255.255.0` | `192.168.10.1` |
| PC3 | `192.168.10.12` | `255.255.255.0` | `192.168.10.1` |

### Subnet Details

- **Network address:** `192.168.10.0`
- **CIDR notation:** `/24`
- **Subnet mask:** `255.255.255.0`
- **Usable IPv4 host range:** `192.168.10.1`–`192.168.10.254`
- **Broadcast address:** `192.168.10.255`
- **Default gateway:** `192.168.10.1`

## Configuration and Testing

The project covers basic network setup and connectivity verification, including:

- Connecting the router, switch, and end devices.
- Assigning IPv4 addresses and subnet masks.
- Configuring the default gateway on end devices.
- Verifying device and interface connectivity.
- Testing communication between PCs using ICMP ping.
- Reviewing the topology and connectivity results in Packet Tracer.

## Connectivity Verification

ICMP ping tests were used to verify communication between devices on the LAN.

Successful ping responses help confirm that the tested devices can communicate over the configured network.

Connectivity testing can help identify problems involving IP addressing, subnet masks, interface status, or network connectivity.

## Project Files

- **Packet Tracer file (`.pkt`):** Contains the simulated network topology and device configuration.
- **Screenshots:** Show the network topology, interface status, and connectivity test results.

## Technologies and Concepts

- Cisco Packet Tracer
- Cisco router and switch fundamentals
- Local area network (LAN) design
- IPv4 addressing and subnetting
- Default gateway configuration
- ICMP ping testing
- Basic network troubleshooting

## Scope and Limitations

This project is a simulated networking lab created in Cisco Packet Tracer. It demonstrates basic network design, IPv4 configuration, and connectivity verification.

The project does not represent a production network deployment or demonstrate advanced enterprise routing, firewall configuration, or production network security controls.

