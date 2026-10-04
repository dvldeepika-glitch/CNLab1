# Computer Networks Lab - Experiment 1

## Aim
To study basic network devices and connect three computers in a LAN using a switch, Ethernet cables, and IP addressing.

## Network Devices Studied
- NIC
- Hub
- Switch
- Router
- Bridge
- Repeater
- Gateway

## LAN Topology
The LAN consists of:
- 3 PCs: PC0, PC1, PC2
- 1 Switch
- Copper Straight-Through Ethernet cables

## IP Address Configuration

| Device | IP Address | Subnet Mask | Default Gateway |
|---|---|---|---|
| PC0 | 192.168.1.10 | 255.255.255.0 | 192.168.1.1 |
| PC1 | 192.168.1.11 | 255.255.255.0 | 192.168.1.1 |
| PC2 | 192.168.1.12 | 255.255.255.0 | 192.168.1.1 |

## Connectivity Testing

From PC0:

```text
ping 192.168.1.11
ping 192.168.1.12
ipconfig