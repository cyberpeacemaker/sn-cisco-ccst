# 1. ICMP
- [TTL, Hop limit]
- ICMPv6, Stateless Address Acutoconfiguration (SLAAC), duplicate address detection (DAD)
    - [Router Solicitation, Router Advertisement]
    - [Neighbor Solicitation, Neighbor Advertisement]

| ICMP Version | Code | Description                                                    |
|--------------|------|----------------------------------------------------------------|
| **ICMPv4**   | 0    | Net unreachable                                                |
|              | 1    | Host unreachable                                               |
|              | 2    | Protocol unreachable                                           |
|              | 3    | Port unreachable                                               |
| **ICMPv6**   | 0    | No route to destination                                        |
|              | 1    | Communication with the destination is administratively prohibited |
|              | 2    | Beyond scope of the source address                             |
|              | 3    | Address unreachable                                            |
|              | 4    | Port unreachable                                               |


# 2. ping
- loopback "it didn't indicate anything about the status of the lower layer of the network stack. This simply tests IP down through the network layer of IP."

q10