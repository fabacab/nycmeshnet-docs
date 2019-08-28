---
title: End-user Connectivity
weight: 100
---

Inidividual participants connect to the NYC Mesh network the same way as they might connect to any other Internet service, such as their home ISP or the Wi-Fi connection available at coffee shops and community centers around the city. They may use a laptop, smartphone, or any other computer capable of Internet connectivity to connect to the NYC Mesh network.

When an installation team proceeds with connecting a new node to the network, one of the devices they bring is what we call an *indoor router*. We like to use the [TL-WR841N](https://www.tp-link.com/us/home-networking/wifi-router/tl-wr841n/), a TP-Link branded 300Mbps Wireless N Router, although most typical small-office/home-office ("SoHo") routers will also work. The only requirement is that the indoor router supports the [IEEE 802.11](https://en.wikipedia.org/wiki/IEEE_802.11) protocol, often sold to consumers under the familiar industry trade name *Wi-Fi*. This router is given to the new node owner and is paid for as part of the volunteer-led installation fee. Since these are installed on-premises at a new node owner's physical location, we sometimes refer to these devices as part of Customer-Premises Equipment (CPE).

In the typical case, an end-user device such as a laptop or smartphone connects directly to the indoor router via Wi-Fi. This provides each node owner with their own, private, local-area network (LAN). Inside the owner's LAN, they are free to install and run any number of personal devices such as additional computers, smart home appliances, Internet of Things (IoT) devices, and any other network-capable product that they like.

All of these end-user devices except, in some cases, for the indoor router are the responsibility of their respective owners and are not managed by NYC Mesh. In fact, many of these devices are completely invisible to NYC Mesh volunteers because of the way the indoor router works. In essence, each home is yet another smaller network compared to NYC Mesh itself, just like NYC Mesh's mesh network itself is a smaller network compared to the Internet at large.

Each indoor router is, in turn, connected via physical wire to an *upstream* or [*outdoor router* so that it can connect to the rest of the NYC Mesh network]({{< relref "intra-mesh-connectivity" >}}). NYC Mesh recommends the use of the [Dynamic Host Configuration Protocol (DHCP)](https://en.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol) for automatically configuring the network settings of both end-user devices and their indoor routers in such a way as to enable them to access the rest of NYC Mesh's mesh network as well as the Internet. When NYC Mesh's volunteer install teams configure indoor routers initially, they are set to obtain their network settings from the outdoor router via DHCP. That said, individual participants are welcome to change the network settings of their devices or their indoor router, but we recommend that they refrain from doing so unless they have a specific reason and are aware of the possible impact to their connected devices.