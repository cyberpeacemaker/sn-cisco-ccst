# 1.Ethernet
- Nowaday only 2 LAN {ethernet[802.2, 802.3]/WLAN}
- Ethernet standards make sure network cards from different manufacturers can work together seamlessly.
- MAC Address(OUI+ID)

# 2.Frame
- Data-link [LLC(**work with upper layer to add app infro, Control the NIC**), MAC(implement in hardware)] sublayer
- MAC(data encapsulation and accessing the media)[Frame, Addressing, **Error Detecion**], (Ethernet LANs of today use switches that operate in full-duplex. Full-duplex communications with Ethernet switches **do not require access control through CSMA/CD.**)
- [64-1518], -18 > [46-1500] bytes, [collision fragment, runt frame], [jumbo, baby giant]
- [preamble, SFD, Dst MAC, Src Mac, type/length(**upper layer protocal encapsulated in**), Data, FCS]

# 3.MAC Address
- [224-239.255.255.255, ff00::/8] multicast ip > MAC [**01-00-5E, 33-3**3]
- **STP, LLDP**
- 100Base-T [**speed in Mbps, basedband transmission, twiwted-pair cable**]
