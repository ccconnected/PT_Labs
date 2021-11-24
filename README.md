## Lab List:

1. [20211122 InterVLAN Routing](https://github.com/ccconnected/PT_Labs#1-20211122_intervlan-routing)
2. [20211124 L2 EtherChannel, HSRP, OSPF](https://github.com/ccconnected/PT_Labs#2-20211124-l2-etherchannel-hsrp-ospf)


---

## 1. 20211122_InterVLAN Routing

**Description:** Practice Inter-VLAN Routing using Layer 3 switch, start from the initial state with default configurations or check out how i finished the lab.

Read more about Inter-VLAN Routing on [Cisco Press](https://www.ciscopress.com/articles/article.asp?p=3089357&seqNum=6).

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

For in-between details not mentioned here or shown in the .pkt, choose for yourself.
Additionally use this topology to practice other networking concepts: HSRP interface tracking, use of ACLs, NATting, spanning-tree protocol standard and priority change, PAgP EtherChannel, port security, etc.

Read more about HSRP on [Cisco.com](https://www.cisco.com/c/en/us/support/docs/ip/hot-standby-router-protocol-hsrp/13780-6.html).

**IMPORTANT:** Install the latest version (at least 8.0.1.0064) of [Packet Tracer](https://www.netacad.com/courses/packet-tracer) to be able to open these .pkt files.

**Proof of Concept:**

![Solved Lab JPG](https://i.imgur.com/WOZBhdg.jpg)
