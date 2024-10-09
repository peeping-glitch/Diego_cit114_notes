## Notes 05: Networking & Content Delivery

**Key Points**
+ There a multiple things that go into a network such as a Router, Switch, Hub, and a Bridge
+ There are also multiple layout patterns for networks such as star, mesh, daisychain, tree, point to point, ring, and hybrid
+ OSI- open systems interconnection it is a model the states the specific standards for communications protocols and also the functions of each layer 
+ there are a total of 7 layers layer 1 Physical, layer-2 Data link, layer-3 Network, layer-4-Transport, layer-5-Session, layer-6-Presentation, and layer-7-Application
+ Protocol is the set of rules or algorithms which define the way how two entities can communicate across the network and there exists different protocol defined at each layer of OSI model. Few of such protocols are TCP, IP, UDP, ARP, DHCP, FTP and so on
+  ip address To identify each device in the world-wide-web, Internet Assigned Numbers Authority (IANA) assigns IPv4 (Version 4) address as a unique identifier for each device on the Internet. However there is also an IPv6 (Version 6) scheme available that has more addresses available
+  Mac address are known as the physical address, is the unique identifier of each host and the network interface card

**Identify 2 Quotes that are intresting**
+ one of the quotes that i found intresting in this section is the subnetting section since i didnt really know what it did "A Class A, B, or C TCP/IP network can be further divided, or subnetted, by a system administrator. This becomes necessary as you reconcile the logical address scheme of the Internet (the abstract world of IP addresses and subnets) with the physical networks in use by the real world.

A system administrator who is allocated a block of IP addresses may be administering networks that are not organized in a way that easily fits these addresses. For example, you have a wide area network with 150 hosts on three networks (in different cities) that are connected by a TCP/IP router. Each of these three networks has 50 hosts. You are allocated the class C network 192.168.123.0. (For illustration, this address is actually from a range that is not allocated on the Internet.) This means that you can use the addresses 192.168.123.1 to 192.168.123.254 for your 150 hosts."(7.05, Understanding TCP/IP addressing and subnetting basics). The reason i found this very intresting is because of how it works it breaks down the already complicated ip address and makes them allocate and give you options on what address you can use for the hosts you are connecting

+ Another quote i found very intresting is the ARP "ARP stands for Address Resolution Protocol.

It is used to convert the IP address to its corresponding Physical Address(i.e.MAC Address).

ARP is used by the Data Link Layer to identify the MAC address of the Receiver’s machine"(7.02, Definitions for Computer Networking). The reason i found this to be very intresting is since it converts the ip address and give them physical address in order to indentify what machine is which physicaly

**Outline new facts that i learned from this section**
New facts i learned from thi section are ARP i have not heard of it before and it is very intresting that its whole intended pourpose is to convert ip address into physical address for every machine that connects to a network. Another fact that i have learned is that a socket is just the combination of an ip address and the port number. Another fact i learned in this section the diffrence between IPv4 and IPv6 and how IPv4 comes out on top when it come to being able to make private ips


**What question remain after reading the section**
A question that i have is in VPC can you also stup private networks so everyting is in intrnework?
