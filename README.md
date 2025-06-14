# Lab 3: PC to PC Communication via Router

This Cisco Packet Tracer lab connects two PCs through a router using different subnets.

## Devices
- 2 x PCs
- 1 x Cisco Router (2911)
- 2 x Copper Straight-Through Cables

## IP Details
| Device | Interface | IP            | Subnet Mask       |
|--------|-----------|---------------|-------------------|
| PC0    | Fa0       | 192.168.10.2  | 255.255.255.0     |
| Router | G0/0      | 192.168.10.1  | 255.255.255.0     |
| Router | G0/1      | 192.168.20.1  | 255.255.255.0     |
| PC1    | Fa0       | 192.168.20.2  | 255.255.255.0     |

## Result
Ping from PC0 to PC1 successful ✔️
