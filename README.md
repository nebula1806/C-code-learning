PROGRAM -1:
1. A . Aim: Introduction to Packet tracer and networking device components.
Theoretical Description: Packet Tracer is a powerful network simulation tool developed by Cisco,
widely used for learning, teaching, and simulating network setups. It allows users to design, configure,
and troubleshoot virtual networks. Packet Tracer offers a graphical user interface where users can drag
and drop networking devices, configure them, and simulate various network scenarios without
needing physical hardware.
Algorithm: Not Applicable
Source Code: Not applicable
Description: Components of Networking Devices in Packet Tracer:
1. Routers:
o Routers are used to forward data packets between different networks. They operate at the
network layer (Layer 3) of the OSI model and make decisions based on the destination IP
address. Packet Tracer allows configuration of various router features like routing
protocols (RIP, OSPF, EIGRP, BGP), NAT, ACLs, and more.
2. Switches:
o Switches are network devices that operate at the data link layer (Layer 2). They are used
to connect devices within the same network (LAN) and make decisions based on MAC
addresses. In Packet Tracer, switches can be configured for VLANs, STP, and trunking
protocols.
3. End Devices (PCs, Laptops, Servers):
o End devices in Packet Tracer include PCs, laptops, and servers, which represent the user
devices in a network. These can be connected to switches and routers, and users can
configure IP addresses, simulate web services, FTP, DHCP, and more.
4. Access Points and Wireless Devices:
o Wireless routers and access points in Packet Tracer allow for the simulation of Wi-Fi
networks. These devices enable wireless communication between PCs and other network
devices, providing features such as SSID configuration, security protocols (WPA, WPA2),
and DHCP services.
5. Cables and Connectors:
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
9
o Various types of cables (Ethernet, Fiber, Serial) can be used to connect networking devices
in Packet Tracer. Each cable type has specific properties and limitations, allowing users
to simulate accurate network topologies.
Output: This experiment demonstrates the basic use of Packet Tracer for configuring a simple
network with basic components.
Conclusion: This experiment demonstrates the basic use of Packet Tracer for configuring a simple network
with basic components.




Aim
1 B. To study the NetSim network simulation environment and understand the various networking device components
available for designing and simulating computer networks.
Theoretical Description
NetSim is a comprehensive network simulation and emulation software developed by Tetcos. It is widely used in academia,
research, and industry for designing, simulating, analyzing, and evaluating communication networks. NetSim enables users to
create realistic network topologies, configure networking devices, analyze protocol behavior, and measure network
performance without requiring physical hardware.
NetSim supports multiple networking technologies such as Ethernet, Wi-Fi (IEEE 802.11), MANET, LTE/5G, IoT, Sensor
Networks, Satellite Networks, Software Defined Networks (SDN), and TCP/IP-based communication. It also provides detailed
packet-level analysis, event tracing, graphical visualization, and performance metrics including throughput, delay, jitter, packet
delivery ratio, and packet loss.
The graphical interface allows users to drag and drop network devices, configure protocol parameters, connect devices using
different media, execute simulations, and analyze generated results.
Algorithm
Not Applicable
Source Code
Not Applicable
Description: Components of Networking Devices in NetSim
1. Routers
• Routers are Layer-3 networking devices responsible for forwarding packets between different networks based on IP
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
10
addresses.
• NetSim supports static routing as well as dynamic routing protocols.
• Routers can be configured with multiple interfaces, routing tables, and protocol parameters.
2. Switches
• Switches operate at the Data Link Layer (Layer 2) and connect devices within a Local Area Network (LAN).
• They forward Ethernet frames based on MAC addresses.
• NetSim supports Ethernet switching, VLAN implementation, and switching behavior analysis.
3. End Devices (PCs, Servers, Workstations)
• End devices act as communication sources and destinations.
• These devices generate application traffic such as HTTP, FTP, Email, Voice, Video, and File Transfer.
• Users can configure IP addressing, applications, and transport layer protocols.
4. Wireless Access Points and Mobile Nodes
• Wireless devices simulate IEEE 802.11 Wi-Fi communication.
• Mobile nodes can move according to mobility models.
• Access Points provide wireless connectivity to laptops, smartphones, and IoT devices.
5. Links and Communication Media
NetSim provides different communication media, including:
• Ethernet Links
• Wireless Links
• Fiber Optic Links
• Point-to-Point Links
• Serial Links
Each communication medium has configurable bandwidth, propagation delay, packet loss probability, and transmission
characteristics.
6. Internet Cloud
• Represents the Internet or Wide Area Network (WAN).
• Used for connecting geographically distributed networks.
• Supports Internet-based communication scenarios.
7. Traffic/Application Generator
NetSim provides several built-in applications:
• FTP
• HTTP
• Email
• Video Streaming
• Voice over IP (VoIP)
• Custom Traffic Generation
These applications generate realistic network traffic for protocol performance evaluation.
8. Simulation Engine
The simulation engine executes the designed network topology by processing discrete networ events.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
11
It performs:
• Packet generation
• Routing
• Queue management
• Collision handling
• Protocol execution
• Performance metric calculation
9. Performance Analyzer
After simulation completion, NetSim automatically generates various performance statistics, including:
• Throughput
• End-to-End Delay
• Packet Delivery Ratio (PDR)
• Packet Loss
• Jitter
• Network Utilization
• Queue Length
• Energy Consumption (Wireless Networks)
These statistics are displayed as tables and graphs for easy analysis.
Procedure
1. Launch the NetSim software.
2. Create a new simulation workspace.
3. Select the required network scenario.
4. Drag and place networking devices (Router, Switch, PC, Server).
5. Connect the devices using Ethernet links.
6. Configure IP addresses and network parameters.
7. Select the desired application traffic.
8. Save the simulation project.
9. Run the simulation.
10. Observe packet transmission during execution.
11. View the generated performance graphs and statistical reports.
12. Analyze the simulation results.
Output
• Successful creation of a simple network topology in NetSim.
• Packet transmission between network devices.
• Performance graphs showing throughput, delay, packet delivery ratio, and packet loss.
• Simulation event logs and packet traces generated successfully.
Result
The basic network topology was successfully designed and simulated using NetSim. The communication between end devices
was established, and the generated performance metrics were analyzed successfully.



PROGRAM -2:
Aim: To understand and use various network utility commands such as PING, NETSTAT,
IPCONFIG, IFCONFIG, ARP, TRACE-ROUTE, NSLOOKUP, and PATHPING to monitor and
troubleshoot network configurations.
Theoretical Description:
Network utility commands are used to perform a variety of network-related operations. These
commands allow users to check network status, troubleshoot issues, and gather information about
devices and network routes. Here’s a brief description of each command:
• PING: Sends ICMP echo requests to a target IP address or hostname to verify connectivity.
• NETSTAT: Displays active connections, listening ports, routing tables, and network statistics.
• IPCONFIG (Windows) / IFCONFIG (Linux): Shows the IP configuration of network interfaces.
• ARP: Displays the ARP table (mapping of IP addresses to MAC addresses) used in a network.
• TRACE-ROUTE: Traces the route that packets take to reach a destination, displaying each hop.
• NSLOOKUP: Queries DNS servers for IP addresses corresponding to domain names.
• PATHPING: Combines PING and TRACE-ROUTE functionalities, showing packet loss and
latency over each hop.
Algorithm: For each command, the algorithm generally follows this pattern:
1. Open a Command Prompt (Windows) or Terminal (Linux).
2. Run the command with necessary parameters (e.g., IP address, hostname).
3. Observe the output for insights into network status or issues.
4. Interpret the results based on what the command outputs (e.g., latency for PING, route for TRACEROUTE).
Source Code:
This section describes the syntax and examples for each network utility command:
1. PING (Test connectivity):
ping google.com
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
13
ping 192.168.1.1
2. NETSTAT (View network connections):
netstat -a (Shows all active connections)
netstat -r (Displays routing table)
netstat -e (Shows Ethernet statistics)
3. IPCONFIG (Windows) / IFCONFIG (Linux):
ipconfig (Windows)
ifconfig (Linux)
ipconfig /all (Displays detailed info in Windows)
4. ARP (View ARP table):
arp -a
5. TRACE-ROUTE (Trace packet path to a destination):
tracert google.com (Windows)
traceroute google.com (Linux)
6. NSLOOKUP (Query DNS):
nslookup google.com
7. PATHPING (Check route and latency):
pathping google.com
Output:
1. PING:
Reply from 142.250.72.238: bytes=32 time=25ms TTL=55
Reply from 142.250.72.238: bytes=32 time=26ms TTL=55
2. NETSTAT:
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
14
Active Connections:
Proto Local Address Foreign Address State
TCP 192.168.1.10:49704 142.250.72.238:https ESTABLISHED
3. IPCONFIG (Windows):
Ethernet adapter Local Area Connection:
IPv4 Address: 192.168.1.10
Subnet Mask: 255.255.255.0
Default Gateway: 192.168.1.1
4. IFCONFIG (Linux):
eth0 Link encap:Ethernet HWaddr 00:1C:C0:AE:B4:89
inet addr:192.168.1.10 Bcast:192.168.1.255 Mask:255.255.255.0
5. ARP:
Interface: 192.168.1.10 --- 0x6
Internet Address Physical Address Type
192.168.1.1 00-14-22-01-23-45 dynamic
6. TRACE-ROUTE:
Tracing route to google.com [142.250.72.238]
1 1 ms 1 ms 1 ms 192.168.1.1
2 15 ms 15 ms 14 ms 10.100.20.1
3 25 ms 26 ms 25 ms 142.250.72.238
7. NSLOOKUP:
Server: dns.google
Address: 8.8.8.8
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
15
Name: google.com
Address: 142.250.72.238
8. PATHPING:
Tracing route to google.com [142.250.72.238]
Hop RTT Lost/Sent Address
1 <1ms 0/100 192.168.1.1
2 20ms 0/100 10.100.20.1
Conclusion: In this experiment, we explored different network utility commands that allow us to
check network configurations, trace routes, and troubleshoot network issues. Each command serves a
specific purpose, ranging from checking basic connectivity (PING) to analyzing network traffic
(NETSTAT) and route discovery (TRACE-ROUTE, PATHPING). These tools are vital for network
administrators to ensure proper network functionality and identify potential issues.






PROGRAM -3:
Aim: Star Topology using HUB and Switch, IP configuration of end devices, show command, copy
command, password setting, hostname setting
Theoretical Description: A star topology for a Local Area Network (LAN) is one in which each node
is connected to a central connection point, such as a hub or switch. Whenever a node tries to connect
with another node then the transmission of the message must be happening with the help of the central
node.
Algorithm:
Step 1: We have taken a switch and linked it to six end devices.
Step 2: Link every device with the switch.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
17
Step 3: Provide the IP address to each device.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
18
Step 4: Transfer message from one device to another and check the Table for Validation.
Now to check whether the connections are correct or not try to ping any device and the image below
is doing the same.
To do ping one terminal of one device and run the following command:
Command:
"ping ip_address_of _any_device"
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
19
Output:
Conclusion:
In this experiment, we successfully simulated a Star Topology using both a HUB and Switch. We
assigned IP addresses to the PCs connected in the network and verified communication using the ping
command. Additionally, we configured the Switch by setting its hostname and password, and saved
the configuration using the copy command. We demonstrated the use of basic show commands to
view the switch status and configuration.



PROGRAM -4:
Aim: To configure Dynamic Host Configuration Protocol (DHCP) on a network device (such as a
router) to dynamically assign IP addresses to devices connected to the network and verify the correct
configuration.
Theoretical Description:
DHCP (Dynamic Host Configuration Protocol) is a network management protocol used to dynamically
assign IP addresses and other related network configuration information (like subnet mask, gateway, DNS)
to devices in a network. This eliminates the need for manually configuring each device with an IP address.
A DHCP server assigns IP addresses from a predefined range or pool of IP addresses to devices
(clients) requesting an address. This system ensures efficient and automated distribution of IP
addresses, reducing the risk of IP conflicts.
The basic process of DHCP includes four steps:
1. DHCP Discover: The client broadcasts a request to find a DHCP server.
2. DHCP Offer: The server responds with an IP address offer.
3. DHCP Request: The client requests the offered IP address.
4. DHCP Acknowledgment (ACK): The server confirms and assigns the IP address to the
client.
Algorithm:
1. Network Setup:
a. In Packet Tracer (or physical setup), place a router (or DHCP server), a switch, and
several end devices (PCs, laptops).
b. Connect the router to the switch, and connect the end devices to the switch using
straight-through cables.
2. DHCP Configuration on the Router:
a. Access the router's CLI.
b. Enter global configuration mode and configure a DHCP pool with a range of IP
addresses.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
21
3. Exclude Specific IP Addresses (Optional):
a. If certain IPs (like the router itself) should not be assigned dynamically
4. IP Configuration on End Devices:
a. On the PCs connected to the network, go to the Desktop tab in Packet Tracer, open IP
Configuration, and select DHCP.
b. The PCs should automatically obtain an IP address from the DHCP server.
5. Verification:
a. On the router, use the following command to verify the leased IP addresses:
i. Router# show ip dhcp binding
Output:
1. PC IP Configuration (Automatically Assigned):
a. IP Address: 192.168.1.11
b. Subnet Mask: 255.255.255.0
c. Default Gateway: 192.168.1.1
d. DNS Server: 8.8.8.8
2. DHCP Binding Output (On Router):
a. IP address Client-ID/Lease expiration Type
b. 192.168.1.11 0001.4a55.a3b7 Automatic
c. 192.168.1.12 0002.4b67.fad9 Automatic
3. DHCP Show Command Output:
a. Router# show ip dhcp binding
b. Router# show ip dhcp pool
c. Pool MY_POOL :
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
22
d. Utilization: 2 addresses in use, 246 available
e. Subnet size: 256
Conclusion: In conclusion, DHCP is a technology that simplifies network setup by automatically
assigning IP addresses and network configurations to devices. While DHCP offers convenience,
it’s important to manage its security carefully. Issues such as IP address exhaustion, and potential
data access through DNS settings highlight the need for robust security measures like firewalls
and VPNs to protect networks from unauthorized access and disruptions. DHCP remains essential
for efficiently managing network connections while ensuring security against potential risks.
Viva Questions:
1. What is the role of a DHCP server in a network?
2. Explain the DHCP Discover and DHCP Offer processes.
3. What is the significance of the default-router command in DHCP configuration?
4. Why would you use the ip dhcp excluded-address command in DHCP
configuration?
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
23
PROGRAM -5:
Aim: To understand the modes of operation in a Router and explore basic Router and Switch
commands for configuring and managing network devices.
Theoretical Description:
A Router operates in various modes, each allowing different levels of configuration and command
execution. The most common modes in a router are:
1. User EXEC Mode: This is the initial mode when accessing the router, which has limited
functionality, mainly for viewing basic information.
o Prompt: Router>
2. Privileged EXEC Mode: Provides access to all the show commands, debugging, and basic
device management commands. You can also enter global configuration mode from here.
o Prompt: Router#
o Command to enter: enable
3. Global Configuration Mode: Used to make system-wide configurations. You can configure
interfaces, routing protocols, and other features.
o Prompt: Router(config)#
o Command to enter: configure terminal
4. Interface Configuration Mode: Used to configure the individual interfaces (ports) of the router.
o Prompt: Router(config-if)#
o Command to enter: interface [type/number] (e.g., interface GigabitEthernet0/0)
Switches also have a similar hierarchy of command modes and allow management through
VLANs, port configurations, etc.
Algorithm:
1. Access the Router or Switch:
a. Open a terminal or console session to the Router/Switch.
2. Switch to Privileged EXEC Mode:
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
24
a. Enter the enable command to switch from user mode to privileged EXEC mode.
3. Enter Global Configuration Mode:
a. Use the configure terminal command to enter global configuration mode.
4. Configure Interfaces (For Routers):
a. Use interface commands to configure IP addresses, enable/disable interfaces, etc.
b. Example: interface GigabitEthernet0/0
5. View Status and Information:
a. Use commands like show ip interface brief, show running-config, etc., to view current
configurations.
6. Basic Switch Commands:
a. Set the hostname, password, and manage VLANs.
Output:
1. Router Hostname Configuration:
MyRouter(config)# hostname MyRouter
MyRouter#
2. Interface IP Configuration:
MyRouter(config-if)# ip address 192.168.1.1 255.255.255.0
MyRouter(config-if)# no shutdown
3. Switch VLAN Configuration:
MySwitch# show vlan brief
VLAN Name Status Ports
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
25
10 Sales active Fa0/1
4. Interface Status on Router:
MyRouter# show ip interface brief
Interface IP-Address OK? Method Status Protocol
GigabitEthernet0/0 192.168.1.1 YES manual up up
Conclusion: In this experiment, we explored the different modes of a router and basic switch
commands. We configured a router's hostname, IP address, and interfaces, and also set up VLANs
on a switch.
Viva Questions:
1. What is the difference between User EXEC Mode and Privileged EXEC Mode?
2. Why do we use the no shutdown command after configuring an interface?
3. What is the purpose of setting a default gateway on a router?
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
26
PROGRAM -6:
Aim: To configure Static Routing on a network using routers, ensuring data packets are directed to
the correct destination networks via predefined paths.
Theoretical Description: Static routing is a routing technique in which a network administrator
manually adds routes to a routing table. Unlike dynamic routing protocols, static routing does not
adjust automatically to network topology changes. It is commonly used in small, simple networks
or where specific routes need to be enforced due to security or performance requirements.
Algorithm:
1. Network Setup:
o Design the network topology with at least two routers, connected via serial or
Ethernet links, along with some end devices (PCs or switches) connected to each router.
2. Access Each Router's CLI:
o Open the terminal on each router and switch to Privileged EXEC Mode using the
enable command.
3. Assign IP Addresses to Router Interfaces:
o Configure IP addresses for the router interfaces that connect to each other and to
the local networks.
4. Define Static Routes:
o For each network, define the next-hop router IP address (or exit interface) for
routing traffic.
5. Test Connectivity:
o Use the ping and traceroute commands to verify that the devices in different
networks can communicate.
Output:
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
27
Conclusion: In this experiment, we successfully configured Static Routing between two routers.
By defining static routes, we manually instructed each router on how to reach the other network.
This allowed communication between devices in different networks.
Viva Questions:
1. What is the difference between static routing and dynamic routing?
2. What are the advantages and disadvantages of static routing?
3. Explain the next-hop IP address in static routing.
4. How can you verify that a static route has been correctly configured on a router?
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
28
PROGRAM -7:
Aim: To configure Routing Information Protocol (RIP) on a set of routers to enable dynamic routing
between multiple networks.
Theoretical Description: Routing Information Protocol (RIP) is a dynamic routing protocol used
in local and wide area networks. RIP is a distance-vector routing protocol that uses hop count as
the metric for path selection. RIP has two versions, RIPv1 and RIPv2, with some key differences:
• RIPv1: A classful routing protocol that does not support subnet information and works without
sending subnet masks, making it unsuitable for Variable Length Subnet Masking (VLSM) or
Classless Inter-Domain Routing (CIDR).
• RIPv2: A classless routing protocol that supports subnet masks and includes VLSM and CIDR
support. RIPv2 also supports authentication and multicast for route updates.
Algorithm:
1. Setup Network Topology:
o Design a network with at least two or more routers connected via serial or Ethernet
links. Configure IP addresses on each router’s interface.
2. Enter Global Configuration Mode:
o On each router, access the command-line interface (CLI) and switch to privileged
EXEC mode.
3. Enable RIP:
o Enable RIP on each router and specify the version (RIPv1 or RIPv2).
4. Advertise Networks:
o For each router, advertise the connected networks so RIP can propagate the routes
dynamically.
5. Verify Configuration:
o Check that the routers have dynamically learned the routes from other routers using
the RIP protocol.
Output:
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
29
Conclusion: In this experiment, we configured both RIPv1 and RIPv2. RIPv1 does not support
subnetting, which limits its usefulness in modern networks. RIPv2, however, is classless and
supports VLSM and CIDR, making it more flexible. By configuring RIP, we were able to
dynamically propagate routes between routers and verify communication between different
networks.
Viva Questions:
1. What is the maximum hop count allowed by RIP?
2. Explain the differences between RIPv1 and RIPv2.
3. Why is RIPv1 considered a classful routing protocol?
4. What are the limitations of RIPv1 in modern networks?
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
30
PROGRAM -8:
Aim: To configure Open Shortest Path First (OSPF) routing protocol on multiple routers in a
network and troubleshoot common OSPF configuration issues.
Theoretical Description: OSPF (Open Shortest Path First) is a link-state routing protocol used in
Internet Protocol (IP) networks to find the best path for data to travel. OSPF is more efficient and
scalable compared to distance-vector routing protocols like RIP. It is widely used in both small
and large enterprise networks and is part of the Interior Gateway Protocol (IGP) suite.
Algorithm:
1. Define Network Topology:
a. Create a network with at least two routers connected via serial or Ethernet links. Each
router should be connected to end devices like PCs or switches.
2. Configure IP Addresses:
a. Assign IP addresses to all router interfaces connecting them to each other and to local
networks.
3. Enable OSPF:
a. On each router, enable OSPF, assign a process ID, and specify the OSPF area (typically
Area 0).
4. Advertise Networks:
a. Use the network command to define the networks that OSPF will advertise to other
routers.
5. Verify and Troubleshoot:
a. Check OSPF neighbors, routing tables, and troubleshoot any connectivity issues.
Output:
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
31
Conclusion: In this experiment, we successfully configured OSPF on multiple routers and
dynamically propagated routes between them. OSPF's link-state nature ensures fast convergence
and efficient path selection based on the cost metric. Additionally, we troubleshooted common
OSPF configuration errors, such as incorrect network statements, mismatched OSPF timers, and
neighbor adjacency issues.
Viva Questions:
1. What is the main difference between OSPF and RIP?
2. How does OSPF calculate the best route?
3. What is the purpose of the OSPF area and why is Area 0 important?
4. Explain the difference between OSPF broadcast and non-broadcast networks.
5. What is the hello and dead interval in OSPF, and why are they important?
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
32
PROGRAM -9:
Aim: To configure VLAN (Virtual Local Area Network) on a switch and verify its functionality by
assigning ports to different VLANs. Additionally, troubleshoot VLAN-related issues to ensure proper
network segmentation.
Theoretical Description: VLAN (Virtual Local Area Network) is a logical grouping of devices
within a network that allows segmentation of a network into different broadcast domains. This
segmentation enhances security, improves network performance, and simplifies network management
by grouping devices logically instead of physically.
A VLAN operates at Layer 2 (Data Link Layer) of the OSI model, and each VLAN acts as a separate
network segment, even if the devices are connected to the same physical switch. Devices in the same
VLAN can communicate with each other, while devices in different VLANs require a Layer 3 device
(like a router) to communicate.
Common VLAN types:
• Default VLAN: All switch ports belong to VLAN 1 by default.
• Data VLAN: Carries user-generated traffic (e.g., VLAN 10 for HR, VLAN 20 for Sales).
• Voice VLAN: Carries voice traffic, typically prioritized over data traffic.
• Management VLAN: Used for network management traffic (e.g., SSH, Telnet).
Algorithm:
1. Define Network Topology:
a. Identify the switch and end devices (PCs) that need to be assigned to different VLANs.
2. Access Switch:
a. Log into the switch and enter global configuration mode.
3. Create VLANs:
a. Create and name VLANs as per the network requirements.
4. Assign Ports to VLANs:
a. Assign specific switch ports to the desired VLANs.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
33
5. Configure Trunk Ports (Optional):
a. If multiple switches are connected, configure trunking on the switch-to-switch link to
allow traffic from multiple VLANs to pass through.
6. Verify VLAN Configuration:
a. Verify VLANs and ensure devices within the same VLAN can communicate.
7. Troubleshoot VLAN Issues:
a. Check the VLAN configuration for any misconfigured ports or VLAN assignments.
Output:
Conclusion: In this experiment, we successfully configured VLANs on a switch, segmented the
network into different broadcast domains, and tested communication between devices within the
same VLAN. We also learned to troubleshoot common VLAN issues such as misconfigured ports
and trunk links.
Viva Questions:
1. How does a switch handle VLAN traffic?
2. What is the difference between an access port and a trunk port?
3. How do you configure inter-VLAN routing?
4. What command would you use to verify VLANs configured on a switch?
5. Why is trunking necessary when connecting multiple switches?
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
34
6. What is the difference between tagged and untagged VLAN traffic?
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
35
PROGRAM -10:
Aim: To implement and analyze the Network Address Translation (NAT) protocol in a simulated
network environment to understand its configuration, operation, and troubleshooting techniques.
Theoretical Description: Network Address Translation (NAT) is a technique used in networking
to translate private (non-routable) IP addresses to a public (routable) IP address and vice versa.
NAT is crucial for conserving the limited number of public IP addresses and enhancing security
by hiding internal IP addresses from external networks.
Types of NAT:
1. Static NAT: A fixed mapping between a private IP and a public IP, allowing external devices
to access internal servers.
2. Dynamic NAT: Maps private IPs to a public IP from a defined pool.
3. PAT (Port Address Translation): Allows multiple devices on a local network to be mapped
to a single public IP address, differentiated by unique port numbers.
Key Concepts:
• NAT Inside: Refers to the internal network.
• NAT Outside: Refers to the external network (internet).
• Translation Table: Maintains the mapping between private and public IP addresses.
Algorithm:
1. Define Access List:
a. Create an access list to identify internal IPs that should be translated.
2. Configure NAT Pool (for Dynamic NAT):
a. Define a pool of public IP addresses for translation.
3. Specify Interfaces:
a. Configure the router interfaces as NAT inside or outside.
4. Associate Access List with NAT Configuration:
a. Link the access list to the NAT pool or define overload for PAT.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
36
5. Test Connectivity:
a. Check if devices can access external networks and whether NAT translations are
happening.
6. Troubleshoot if Necessary:
a. Use commands to check NAT translations and statistics to diagnose issues.
Output:
• Successful translation of private IP addresses to a public IP address.
• Connectivity from devices on the private network to external networks.
• Display of NAT translation table showing active mappings between internal and external
addresses.
Conclusion:
The implementation of NAT demonstrates its critical role in modern networking by enabling
multiple devices to share a single public IP address while providing security by masking internal
IP addresses. Understanding NAT configuration and troubleshooting enhances network
management skills, ensuring efficient operation and connectivity in various network scenarios.
Viva Questions:
1. What is the primary purpose of NAT in networking?
2. Explain the difference between static NAT and dynamic NAT.
3. How does PAT work, and why is it useful?
4. What are the advantages and disadvantages of using NAT?
5. Describe the steps involved in configuring NAT on a router.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
37
PROGRAM -11:
Aim: To discover hosts and services on a network and assess security by identifying open ports
and running services.
Theoretical Description
Nmap (Network Mapper) is an open-source tool designed for network exploration and security
auditing. It works by sending specially crafted packets to the target host and analyzing the
responses. It can be used to perform tasks such as host discovery, port scanning, and OS detection.
Algorithm
1. Input Target(s): Specify the IP address or range of IPs to scan.
2. Send Packets: Send various types of packets (TCP, UDP) to the target.
3. Receive Responses: Analyze the responses to determine the state of ports (open, closed,
filtered).
4. Identify Services: Optionally probe open ports to identify running services and versions.
5. Output Results: Generate a report of the findings.
Output
• List of active devices and their IP addresses.
• Open ports and their states (open, closed, filtered).
• Identified services and versions running on open ports.
• Operating system and hardware details of the scanned devices.
Conclusion
Nmap is an essential tool for network administrators and security professionals. It provides
valuable insights into network configuration and security posture, enabling proactive management
and vulnerability assessment.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
38
2. Wireshark
Aim: To capture and analyze network traffic in real-time for troubleshooting, protocol analysis,
and security monitoring.
Theoretical Description
Wireshark is a widely used network protocol analyzer that captures packets traversing a network
interface and decodes the data for analysis. It supports hundreds of protocols and allows users to
view the details of each packet, including headers and payload data.
Algorithm
1. Select Network Interface: Choose the network interface to capture traffic from.
2. Start Capture: Begin capturing packets on the selected interface.
3. Apply Filters: Optionally apply capture or display filters to focus on specific traffic.
4. Analyze Packets: Inspect captured packets for relevant information, including protocols and
payloads.
5. Export Data: Save or export captured data for further analysis if needed.
Output
1. Real-time display of network packets with detailed information.
2. Statistics about captured traffic, including protocol distribution.
3. Exported data files in formats like PCAP for further analysis.
Conclusion
Wireshark is a powerful tool for network analysis, enabling users to troubleshoot issues, monitor
network performance, and analyze security incidents. Its detailed packet-level analysis helps in
understanding complex network behaviours.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
39
3. Network Scanner (General)
Aim: To discover devices on a network, identify their IP and MAC addresses, and assess the
services running on them.
Theoretical Description
Network scanners are tools used to identify devices on a network by sending requests and
analyzing responses. They help in mapping the network topology, checking for unauthorized
devices, and identifying vulnerabilities.
Algorithm
1. Specify IP Range: Define the IP address range to scan.
2. Send Discovery Requests: Send ARP requests or ICMP pings to each IP address in the
range.
3. Receive Responses: Collect responses from devices indicating their presence and status.
4. Scan Ports (Optional): For each discovered device, perform port scanning to check for open
ports.
5. Output Results: Compile and present the list of discovered devices.
Output
1. List of active devices with their IP addresses and MAC addresses.
2. Identified open ports and services for each device (if port scanning is performed).
3. Basic information about device manufacturers (if MAC addresses are resolved).
Conclusion
Network scanners play a crucial role in network management, security auditing, and
troubleshooting. They provide a clear view of the network landscape, enabling administrators to
monitor for unauthorized devices and assess vulnerabilities.
Viva Questions
1. What is the primary purpose of Nmap, and how does it work?
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
40
2. How does Wireshark differ from Nmap in terms of functionality?
3. Describe the steps involved in using a network scanner.
4. What types of information can Nmap provide during a scan?
5. How can you filter packets in Wireshark, and why is this useful?
6. Explain the significance of open ports in network security assessments.
7. What are some ethical considerations when using these network utility tools?
8. Discuss a scenario where Wireshark would be more beneficial than Nmap.
9. How can network utilities assist in penetration testing?
10. What are the limitations of using these tools in a corporate environment?
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
41
PROGRAM -12:
1. Security Threats and Vulnerabilities
Aim: To identify and understand various security threats and vulnerabilities that can affect
computer networks and devices, and to develop strategies for mitigating these risks.
Theoretical Description
Security threats are potential dangers that can exploit vulnerabilities in a network or device to
compromise its confidentiality, integrity, or availability. Vulnerabilities are weaknesses in systems
that can be exploited by threats. Common threats include malware, phishing, DDoS attacks, and
insider threats.
Algorithm
1. Identify Assets: Determine what needs to be protected (data, devices, networks).
2. Assess Vulnerabilities: Conduct vulnerability assessments to identify weaknesses in the system.
3. Analyze Threats: Identify potential threats that could exploit vulnerabilities.
4. Evaluate Impact: Assess the potential impact of these threats on the organization.
5. Prioritize Risks: Rank vulnerabilities based on their severity and likelihood of exploitation.
Output
1. A list of identified vulnerabilities and associated threats.
2. Risk assessment report outlining potential impacts and likelihood.
3. Prioritized list of security measures to mitigate identified risks.
Conclusion
Understanding security threats and vulnerabilities is crucial for organizations to protect their
assets. Regular assessments and proactive measures help to minimize risks and enhance overall
security.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
42
2. Network Attacks
Aim: To categorize and describe various types of network attacks that threaten the integrity,
availability, and confidentiality of information.
Theoretical Description
Network attacks are attempts to breach a network's security to access, steal, or disrupt data.
Common types of network attacks include:
• Denial of Service (DoS): Overwhelming a service with traffic to make it unavailable.
• Man-in-the-Middle (MitM): Intercepting and altering communications between two parties.
• Phishing: Deceiving users into providing sensitive information.
• Malware: Malicious software that can disrupt operations, steal data, or damage systems.
Algorithm
1. Identify Attack Types: List different network attack types.
2. Analyze Attack Mechanisms: Study how each attack is carried out.
3. Assess Impact: Evaluate the impact of each attack type on systems and data.
4. Document Examples: Provide real-world examples of each attack type.
Output
• Comprehensive report detailing various network attack types.
• Examples and case studies highlighting the impact of these attacks.
• Risk assessments associated with each attack type.
Conclusion
Awareness of network attacks is essential for organizations to implement appropriate defenses.
Understanding how attacks work enables proactive security measures to safeguard network
infrastructure.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
43
3. Network Attack Mitigation
Aim: To develop strategies and implement measures to protect networks against potential attacks.
Theoretical Description
Network attack mitigation involves implementing security measures to reduce the risk and impact
of attacks. Techniques include firewalls, intrusion detection/prevention systems (IDS/IPS), and
regular software updates.
Algorithm
1. Identify Vulnerabilities: Conduct vulnerability assessments to pinpoint weaknesses.
2. Implement Security Controls: Apply firewalls, IDS/IPS, and anti-malware solutions.
3. Develop Incident Response Plan: Create a plan to address and recover from security
incidents.
4. Regular Monitoring: Continuously monitor network traffic for suspicious activities.
5. Conduct Training: Educate staff on security best practices to prevent attacks.
Output
• Security policy documentation outlining mitigation strategies.
• Incident response plan for addressing potential security breaches.
• Monitoring reports highlighting suspicious activities and responses.
Conclusion
Effective mitigation strategies are essential for minimizing the risks associated with network
attacks. Continuous monitoring and employee training are key components of a robust security
posture.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
44
4. Device Security
Aim: To ensure that individual devices connected to a network are secure and protected against
vulnerabilities and attacks.
Theoretical Description
Device security involves protecting hardware and software from unauthorized access, misuse, or
damage. This includes implementing security measures like antivirus software, encryption, and
secure configurations.
Algorithm
1. Identify Devices: Inventory all devices connected to the network.
2. Assess Security Posture: Evaluate each device for security vulnerabilities.
3. Apply Security Measures: Implement security measures such as:
o Antivirus and antimalware software
o Regular software updates and patch management
o Encryption of sensitive data
o Secure configurations (e.g., changing default passwords)
4. Monitor Device Security: Regularly review device logs and security alerts.
5. Educate Users: Provide training on secure device usage and practices.
Output
1. Security assessment reports for each device.
2. Implementation of security measures and configurations.
3. User training materials on device security best practices.
Conclusion
Securing individual devices is crucial for the overall security of a network. Regular assessments
and proactive security measures ensure that devices remain resilient against threats.
Viva Questions
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
45
1. What are the main types of security threats faced by networks?
2. How do vulnerabilities differ from threats in the context of network security?
3. Explain the concept of a Denial of Service (DoS) attack and its impact.
4. What are some effective strategies for mitigating network attacks?
5. How can organizations protect their devices from security threats?
6. What role does user education play in enhancing security?
7. Describe the importance of an incident response plan in network security.
8. What tools can be used to detect and prevent network attacks?
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
46
Program:13
Aim: Case Study / Mini Project: Build a Small Network and Scale to Larger Networks,
Troubleshooting Scenarios.
Case Study:
Building and Scaling a Small Network to a Large Network with Troubleshooting
Objective:
To design a small network, scale it to a larger network, and troubleshoot common issues that
arise during network expansion.
Scenario:
A small startup requires a network for its office consisting of a few computers, a router, and a
switch. As the company grows, the network must scale to accommodate new departments,
additional users, and servers while ensuring reliable communication, security, and performance.
Phase 1: Small Network Design
The initial network was designed with the following components:
• One Router: Connected to the internet via a broadband modem.
• One Switch: Connected to two PCs and the router.
• PCs: Two employees need internet access and file sharing capabilities.
Configuration:
• The router was configured to assign IP addresses via DHCP.
• PCs were connected through the switch, and the network was tested using ping to verify
connectivity.
• Internet access was successfully established, and file sharing between PCs was tested.
Phase 2: Scaling the Network
As the company grew, the network needed to support:
• Two additional departments: Each requiring its own subnet.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
47
• A File Server: For centralized data storage and sharing.
• Backup Router: For redundancy and failover.
• Additional Devices: Including 20 more PCs, printers, and networked devices.
Scaling Approach:
• Routing Protocol (OSPF) was implemented to facilitate communication between different
subnets.
• VLANs were set up to segment traffic between departments.
• File Server was added, and secure access was configured.
• Redundancy was achieved by adding a backup router, ensuring continuous internet access
in case of a failure.
Phase 3: Troubleshooting
Several common issues were simulated during scaling, and solutions were implemented:
1. Connectivity Issue: One PC lost connectivity due to an incorrect VLAN assignment.
Troubleshooting with ping and traceroute helped identify the issue, and the PC was
reassigned to the correct VLAN.
2. IP Conflict: Two devices were assigned the same IP address, causing network disruptions.
This was resolved by manually reassigning IPs and adjusting DHCP scope.
3. Slow Network Performance: Excessive traffic on a single link caused delays. Quality of
Service (QoS) settings were configured to prioritize important traffic, improving
performance.
Outcome:
The network scaled smoothly, supporting over 50 devices across multiple departments with
secure, high-performance communication. Redundancy ensured uninterrupted service, and
troubleshooting processes kept the network running optimally.
Conclusion:
This case study demonstrates the challenges of scaling a small network to a larger one, highlighting
the importance of proper design, configuration, and troubleshooting techniques.
Computer Networks Lab (CSE3131) Lab Manual
Department of Computer Science & Engineering
48
The project provided a practical understanding of how to manage networks efficiently while
maintaining performance and security.