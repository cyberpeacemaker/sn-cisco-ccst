# 1. Routes
- `netstat -r`, `route print`
- IPv4:subnet, IPv6: router advertise the local network address(prefix)
- **loopback** test TCP/IP stack on the device

# 2. Routing Table
- learn by [manually, dynamically{**dynmaic routing protocal**: Routing Information Portocal (**RIP**), Open Shortest Path First (**OSPF**), Enhanced Interior Gateway Routing Protocal (**EIGRP**)}]
| Order | Destination / Prefix  | Category            | What it does                                                                 | NextHop                 |
|-------|-----------------------|---------------------|-----------------------------------------------------------------------------|-------------------------|
| 1     | 255.255.255.255/32     | Limited Broadcast   | Shouts to everyone on the physical wire, regardless of their IP settings.   | 0.0.0.0 (Direct)        |
| 2     | 224.0.0.0/4           | Multicast           | Used for device discovery (like finding a printer) or streaming to a group. | 0.0.0.0 (Direct)        |
| 3     | 172.16.15.255/32      | Directed Broadcast  | Shouts specifically to every device within your subnet only.                 | 0.0.0.0 (Direct)        |
| 4     | 172.16.6.213/32       | Host Route (You)    | Identifies your own IP. Ensures traffic to "yourself" never leaves the computer. | 0.0.0.0 (Internal)      |
| 5     | 172.16.0.0/20         | Local Subnet Route  | Defines your neighborhood. Identifies which IPs are local and don't need a router. | 0.0.0.0 (On-link)       |
| 6     | **0.0.0.0/0**             | Default Route (**Last Resort**)       | The "Exit Ramp." If no other route matches, traffic is sent here to reach the Internet. | 172.16.15.254 (Router)  |
- **Cisco IOS Router `show ip route`**

q2, q4, q5, q7, q10

---
**q3 q4 q5**, q7, q13