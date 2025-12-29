# 1.Charateristic
- [connectionless, media independant (**fragmentation, MTU  the maximum size of the PDU that each medium can transport**), best effot]

# 2.v4 Packet
- significant header field[version, **DS(ToS) (DSCP, ECN) Priority**, TTL, Protocal, header checksum, src IP, dst IP]

# 3.v6 Packet
- header [fixed 40 bytes , 8 fields] , [version, traffic class, flow label, payload len, next header, hop limit, src IP, dst IP]

**[fe80, ff:fe, ff02] > [link-local, EUI-64, Multicast]**

**IPv4 soon depleted > correct in quiz**
**network layer > specify the packet strcuture and processing used to carry the data from one host to another**
q5, q11