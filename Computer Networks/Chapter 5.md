**SECTIONS 5.1–5.2**
##### R1. Consider the transportation analogy in Section 5.1.1. If the passenger is analagous to a datagram, what is analogous to the link layer frame?
##### R2. If all the links in the Internet were to provide reliable delivery service, would the TCP reliable delivery service be redundant? Why or why not?

No, the TCP reliable delivery **service** would not be redundant even if all the links in the Internet provided reliable delivery service. This is because TCP provides end-to-end reliable delivery, which means it ensures that data is delivered correctly and in order from the source to the destination across multiple links. While link-level reliability ensures that data is reliably delivered within a single link, TCP's reliable delivery service goes beyond that and provides reliability over the entire network.

##### R3. What are some of the possible services that a link-layer protocol can offer to the network layer? Which of these link-layer services have corresponding services in IP? In TCP?

Some possible services that a link-layer protocol can offer to the network layer include framing, physical addressing, error detection and correction, flow control, and access control.  
Of these link-layer services, framing and physical addressing have corresponding services in IP. Framing refers to the process of dividing a stream of data into frames for transmission, and IP also uses packets to transmit data. Physical addressing involves assigning unique addresses to devices on the network, and IP uses IP addresses for identifying devices.  
TCP, on the other hand, provides its own services such as reliable delivery, flow control, and congestion control, which are not directly provided by the link-layer protocol.

**SECTION 5.3**
##### R4. Suppose two nodes start to transmit at the same time a packet of length L over a broadcast channel of rate R. Denote the propagation delay between the two nodes as dprop. Will there be a collision if dprop < L/R? Why or why not?

##### R5. In Section 5.3, we listed four desirable characteristics of a broadcast channel. Which of these characteristics does slotted ALOHA have? Which of these characteristics does token passing have?

##### R6. In CSMA/CD, after the fifth collision, what is the probability that a node chooses K = 4? The result K = 4 corresponds to a delay of how many seconds on a 10 Mbps Ethernet?
##### R7. Describe polling and token-passing protocols using the analogy of cocktail party interactions.
##### R8. Why would the token-ring protocol be inefficient if a LAN had a very large perimeter?

**SECTION 5.4**

##### R9. How big is the MAC address space? The IPv4 address space? The IPv6 address space?

##### R10. Suppose nodes A, B, and C each attach to the same broadcast LAN (through their adapters). If A sends thousands of IP datagrams to B with each encapsulating frame addressed to the MAC address of B, will C’s adapter process these frames? If so, will C’s adapter pass the IP datagrams in these frames to the network layer C? How would your answers change if A sends frames with the MAC broadcast address?
##### R11. Why is an ARP query sent within a broadcast frame? Why is an ARP response sent within a frame with a specific destination MAC address?
##### R12. For the network in Figure 5.19, the router has two ARP modules, each with its own ARP table. Is it possible that the same MAC address appears in both tables?
##### R13. Compare the frame structures for 10BASE-T, 100BASE-T, and Gigabit Ethernet. How do they differ?
##### R14. Consider Figure 5.15. How many subnetworks are there, in the addressing sense of Section 4.4?
##### R15. What is the maximum number of VLANs that can be configured on a switch supporting the 802.1Q protocol? Why?
##### R16. Suppose that N switches supporting K VLAN groups are to be connected via a trunking protocol. How many ports are needed to connect the switches? Justify your answer.





**Terms:**
- **Node**: Any device that runs at the link-layer. They include hosts, routers, switches, and WiFi Access Point.
- **Links:** refer to the communication channels that connect adjacent nodes along the communication path.
- 