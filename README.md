## Lab List:

1. [20211122_InterVLAN Routing](https://github.com/ccconnected/PT_Labs#1-20211122_intervlan-routing)
2. [20211124 L2 EtherChannel, HSRP, OSPF](https://github.com/ccconnected/PT_Labs#2-20211124-l2-etherchannel-hsrp-ospf)
3. [20211201 DHCPrelay, NTP](https://github.com/ccconnected/PT_Labs#3-20211201-dhcprelay-ntp)
4. [20211220 VoIP, PortSec, DHCP](https://github.com/ccconnected/PT_Labs#4-20211220-voip-portsec-dhcp)


---

## 1. 20211122_InterVLAN Routing

**Description:** Practice Inter-VLAN Routing using Layer 3 switch, start from the initial state with default configurations or check out how i finished the lab.

Read more about Inter-VLAN Routing on [Cisco Press](https://www.ciscopress.com/articles/article.asp?p=3089357&seqNum=6).

**Direct Download:** 
- [20211122_InterVLAN Routing - empty.pkt](https://github.com/ccconnected/PT_Labs/raw/main/20211122_InterVLAN%20Routing%20-%20empty.pkt)
- [20211122_InterVLAN Routing - finished.pkt](https://github.com/ccconnected/PT_Labs/raw/main/20211122_InterVLAN%20Routing%20-%20finished.pkt)

**IMPORTANT:** Install the latest version (at least 8.0.1.0064) of [Packet Tracer](https://www.netacad.com/courses/packet-tracer) to be able to open these .pkt files.

**Proof of Concept:**

![Solved Lab JPG](https://i.imgur.com/5LloSaL.jpg)

---

## 2. 20211124 L2 EtherChannel, HSRP, OSPF

**Task Description:** 
1. Implement LACP L2 EtherChannel between A-SW1, A-SW2, D-SW1, D-SW2.
2. Implement HSRP on C-RT1 and C-RT2 toward PC clients in VLANs 10, 20, 30.
3. Implement OSPF throughout the network so all PCs can ping each other and the DC Server and open a web page on the server.
4. a) For VLAN 10 and 20: configure D-SW1 as the root bridge, and C-RT1 as the active router in the group,
   b) For VLAN 30: configure D-SW2 as the root bridge, and C-RT2 as the active router in the group.

Read more about HSRP on [Cisco.com](https://www.cisco.com/c/en/us/support/docs/ip/hot-standby-router-protocol-hsrp/13780-6.html).

**Direct Download:**
- [20211124 L2 EtherChannel, HSRP, OSPF - empty.pkt](https://github.com/ccconnected/PT_Labs/raw/main/20211124%20L2%20EtherChannel%2C%20HSRP%2C%20OSPF%20-%20empty.pkt)
- [20211124 L2 EtherChannel, HSRP, OSPF - finished.pkt](https://github.com/ccconnected/PT_Labs/raw/main/20211124%20L2%20EtherChannel%2C%20HSRP%2C%20OSPF%20-%20finished.pkt)

**IMPORTANT:** Install the latest version (at least 8.0.1.0064) of [Packet Tracer](https://www.netacad.com/courses/packet-tracer) to be able to open these .pkt files.

For in-between details not mentioned here or shown in the .pkt, choose for yourself.
Additionally use this topology to practice other networking concepts: HSRP interface tracking, use of ACLs, NATting, spanning-tree protocol standard and priority change, PAgP EtherChannel, port security, etc.

**Proof of Concept:**

![Solved Lab JPG](https://i.imgur.com/WOZBhdg.jpg)

---

## 3. 20211201 DHCPrelay, NTP

**Task Description:** 
1. First configure static IP addressing for all PCs, routers' interfaces and Server1.
2. Configure dynamic routing (for example OSPF) in the network, ping should now work between all PCs. After that, configure DHCP pool on Server1, then make all switches (int VLAN 1) and transfer all PCs to be it's DHCP clients;
3. Define DNS A record on Server1 for R1 as "router1" and ssh (version 2) to it from PC4 by it's name. Let the username be "admin" ssh password "admin", enable md5 password "lab".
4. Define Router 2 as NTP master clock 3 and all other routers to be it's NTP clients, then check NTP status on them all.

Read more about configuring SSH on [Cisco.com](https://www.cisco.com/c/en/us/support/docs/security-vpn/secure-shell-ssh/4145-ssh.html).

**Direct Download:**
- [20211201 DHCPrelay, NTP - empty.pkt](https://github.com/ccconnected/PT_Labs/raw/main/20211201%20DHCPrelay%2C%20NTP%20-%20empty.pkt)
- [20211201 DHCPrelay, NTP - finished.pkt](https://github.com/ccconnected/PT_Labs/raw/main/20211201%20DHCPrelay%2C%20NTP%20-%20finished.pkt)

**IMPORTANT:** Install the latest version (at least 8.0.1.0064) of [Packet Tracer](https://www.netacad.com/courses/packet-tracer) to be able to open these .pkt files.

For in-between details not mentioned here or shown in the .pkt, choose for yourself. Additionally, use this topology to practice other networking concepts.

**Proof of Concept:**

![Solved Lab JPG](https://i.imgur.com/Dju626A.jpg)

---

## 4. 20211220 VoIP, PortSec, DHCP

**Task Description:** 
I created this lab with the goal to practice establishing calls in Packet Tracer at the CCNA level. The lab has no strict requrements, use provided free resource, practice what you studied to configure DHCP pools, telephony service, and port security.

For in-between details not mentioned here or shown in the .pkt, choose for yourself. Additionally, use this topology to practice other networking concepts.

**Direct Download:**
- [20211220 VoIP, PortSec, DHCP - empty.pkt](https://github.com/ccconnected/PT_Labs/raw/main/20211220%20VoIP%2C%20PortSec%2C%20DHCP%20-%20empty.pkt)
- [20211220 VoIP, PortSec, DHCP - finished.pkt](https://github.com/ccconnected/PT_Labs/raw/main/20211220%20VoIP%2C%20PortSec%2C%20DHCP%20-%20finished.pkt)

**Read more** on configuring telephony service, voice VLAN, DHCP pools on a router, and port security:
1. Cisco Packet Tracer sample .pkt files under File -> Open Samples ... -> (PT installation location\PT version\) saves -> Voice_IPPhone
2. packettracernetwork.com Packet Tracer tutorials ["IP telephony devices"](https://www.packettracernetwork.com/tutorials/voip-devices.html) and ["IP telephony basic configuration"](https://www.packettracernetwork.com/tutorials/voipconfiguration.html)
3. resources.intenseschool.com CCNA Voice prep exercises ["VoIP in Packet Tracer ??? Basic Labs"](https://resources.intenseschool.com/voip-in-packet-tracer-basic-labs/) and ["VoIP in Packet Tracer pt 2 ??? Intermediate Labs"](https://resources.intenseschool.com/voip-in-packet-tracer-a-little-more-advanced-labs/)
4. ciscopress.com CCNA Voice Lab Manual sample chapter ["Establishing Network Connectivity and Understanding IP Phone Registration"](https://www.ciscopress.com/articles/article.asp?p=2013217)
5. cisco.com Cisco IOS Software Configuration Guide, Release 12.2SX sample chapter ["Configuring Port Security"](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst6500/ios/12-2SX/configuration/guide/book/port_sec.pdf)
6. cisco.com Catalyst 2960 Switch Software Configuration Guide sample chapter ["Configuring Voice VLAN"](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst2960/software/release/12-2_40_se/configuration/guide/scg/swvoip.pdf)
7. packetlife.net [Cheat Sheets](https://packetlife.net/library/cheat-sheets/)

**IMPORTANT:** Install the latest version (at least 8.0.1.0064) of [Packet Tracer](https://www.netacad.com/courses/packet-tracer) to be able to open these .pkt files.

**Proof of Concept:**

![Solved Lab JPG](https://i.imgur.com/HuCN1mj.jpg)

