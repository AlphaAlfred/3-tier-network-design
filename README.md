# 3-Tier Network Design

Note: This network design is a personal project and is meant to showcase interactions between features in Cisco Packet Tracer.

Topology: 3-Tier Infrastructure (access, distribution, core), partial-mesh

- Connectivity:
    - 4 Access VLANs (10 Finance, 20 Marketing, 30 IT, 40 Security) 
    - 4 Voice VLANs (11 Finance-Voice, 21 Marketing-Voice, 31 IT-Voice, 41 Security-Voice)
    - IPv4 addressing (multilayer switches with internal DHCP servers)
    - IPv4 routing (OSPFv2 and SVIs)
    
- Redundancy using L3 EtherChannels
- No STP, replaced with L3 switches (PortFast and BPDUGuard used)
- Additional clarity using interface descriptions
- Port Security enabled on access ports

- WIPs:
    - ACLs
    - External DHCP and DNS servers
    - DHCP snooping
    - DAI
    - HSRP
    - and more!

