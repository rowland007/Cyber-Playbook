## A

- **Advanced Persistent Threat (APT)** - An adversary that possesses sophisticated levels of expertise and significant resources which allow it to create opportunities to achieve its objectives by using multiple attack vectors (e.g., cyber, physical, and deception) (NIST, 2013).
- **Adversary Model (resources, capabilities, intent, motivation, risk aversion, access)** - The model that describes the type of adversary, the objective, the motivation, and the payload ramifications. The model described is extensible and the tactics are clear and concise (Invincea, 2015).
- **Asset** - Any software, hardware, data, administrative, physical, communications, or personnel resource within an IS (CNSS, 2003)
- **Attack Timing** - The measured and planned time that the cyber incident will be carried out. This could lead to a sequences of events that over a period of time are meant to weaken the defenses of the system by using planned timing sequences to carry out the attacks (Brocklehurst, 2014).
- **Attack Trees** - These provide a formal, methodical way of describing the security of systems, based on varying attacks. The structure is used represent attacks against a system, with the goal as the root node and different ways of achieving that goal as leaf (Saini, V., Duan & Paruchuri, 2008).
- **Attack Vectors** - The approach used to assault a computer system or network. A fancy way of saying "method or type of attack," the term may refer to a variety of vulnerabilities. For example, an operating system or Web browser may have a flaw that is exploited by a website. Human shortcomings are also used to engineer these. For example, a novice user may open an email attachment that contains a virus, and most everyone can be persuaded at least once in their life to reveal a password for some seemingly relevant reason (PC Magazine, 2018).

## B

- **Backdoor** - A secret way to take control of a computer. Also called "trap doors," these are built into software by the original programmer, who can gain access to the computer by entering a code locally or remotely. For example, in an application, this would enable a person to activate either normal or hidden functions within the software. In an operating system, it would provide access to all system functions in the computer (PC Magazine, 2018).
- **Bots**
    - A search engine program that indexes the Web;
    - A program on the Internet that performs a repetitive function such as posting a message on blogs, newsgroups and social networks, or searching for information. These reside in the background waiting to respond to certain conditions. The term is used for myriad "intelligent agents" that continuously or periodically perform some function. It is estimated that as much as 60% of Web traffic comes from these, not humans. (PC Magazine, 2018)
- **Brute Force (Password Guessing)** - The systematic, exhaustive testing of all possible methods that can be used to break a security system. For example, in cryptanalysis, trying all possible keys in the keyspace to decrypt a ciphertext (PC Magazine, 2018).

## C

- **Calculating Quantified Risk**
    - **Calculate the asset value (AV)** - An asset is anything of value to an organization. Assets can be tangible (buildings) or intangible (reputation). A first step in risk assessment is to determine all the organization’s assets and their valuethat is, the importance of each asset to the organization’s ability to meet its mission. Asset value should consider the replacement value of equipment or systems. It should also include factors such as lost productivity and loss of reputation or customer confidence.
    - **Calculate the exposure factor (EF)** - This represents the percentage of the asset value that will be lost if an incident were to occur. For example, not every car accident is a total loss. Insurance companies have actuaries who calculate the likely percentage loss for every claim. They know the cost of repairs for every make and model and can predict this value per claim. Their prediction won’t be right for any single claim (except by chance), but it will be right when grouped by the hundreds or thousands.
    - **Calculate the single loss expectancy (SLE)** - You can calculate the value of a single loss using asset value and exposure factor. If an actuary calculates that the EF of a late-model SUV is 20 percent, then every time he receives a claim, all he needs to do is look up the asset value, multiply by the EF, and he’ll have a very good prediction of the payout. This allows the actuary to calculate insurance premiums accurately and reduce the risk of the insurance company losing money. (Equation: SLE = AV * EF)
    - **Determine how often a loss is likely to occur every year (ARO)** - This is the annualized rate of occurrence, also called the risk likelihood. Some are greater than one. For example, a snowstorm in Buffalo or Berlin will happen many times per year. Others are likely to happen far less often. For example, a warehouse fire might happen once every 20 years. It is often difficult to estimate how often an incident will happen. Sometimes internal or external factors can affect that assessment. Historical data do not always predict the future. An incident such as one stemming from an internal threat is far more likely during times of employee unrest or contract negotiations than at other times.
    - **Determine annualized loss expectancy (ALE)** - This value is the SLE (the loss when an incident happens) multiplied by the ARO. It helps an organization identify the overall impact of a risk. For infrequent events, this value will be much less than the SLE. For example, if you expect an event to occur only once every 10 years, the value will be 0.10, or 10 percent. If the SLE is $1,000, this is only $100 ($1,000 × 0.10). On the other hand, if the ARO is 20, indicating that it is likely to occur 20 times every year, the value is $20,000 ($1,000 × 20). (Equation: ALE = SLE * ARO) (Kim & Solomon, 2013)
- **Capability** - In information security, an indicator (token, semaphore, etc.) that authorizes an access mode to an object such as a file or a device for a specific user or process (PC Magazine, 2018)
- **CIA Triad** - A widely used formulation of the INFOSEC mission of the U.S. military. Also known as the "Classic Triad," the three concepts fail to include important problems intuitively seen as breaches of security, forgeries or counterfeits; mislabeling of data; and problems of data usability (PC Magazine, 2018).
- **Covert Channels** - An unintended or unauthorized intra-system channel that enables two cooperating entities to transfer information in a way that violates the system's security policy but does not exceed the entities' access authorizations (CNSS, 2003)
- **Cross-Site Scripting (XSS)** - Causing a user's Web browser to execute a malicious script. There are several ways this is done. One approach is to hide code in a "click here" hyperlink attached to a URL that points to a non-existent Web page. When the page is not found, the script is returned with the bogus URL, and the user's browser executes it (PC Magazine, 2018).
- **Cyber Threats Motivations and Techniques (EXAMPLES: fraud, sabotage, vandalism, theft)**
    - **Fraud** - a deliberate action taken to benefit oneself or a collaborator at the expense of the organization;
    - **Sabotage** - a deliberate action taken to cause a failure in an organizational asset or process, generally carried out against targeted key assets by someone possessing or with access to inside knowledge;
    - **Vandalism** - the deliberate damaging of organizational assets, often at random;
    - **Theft** - Taking something that doesn’t belong to you that you have not paid for (Cebula, Popeck, & Young, 2014)
    - **Denial-of-Service Attacks** - An assault on a network that floods it with so many requests that regular traffic is either slowed or completely interrupted. Unlike a virus or worm, which can cause severe damage to databases, this interrupts network service for some period (PC Magazine, 2018).

## D

- **Data-at-rest** - Inactive data stored in any form (for example, on hard drives or in offsite cloud backup). Data at rest is in a stable state, not currently being transmitted across a network or actively being read or being used by any application (Saltzer & Schroeder, 1975).
- **Data-in-motion** - Data that is currently traveling across a network or has been accessed by computer’s RAM ready to be read, updated, or processed (Saltzer & Schroeder, 1975).
- **Data-in-use** - Data that is actively being generated, updated, viewed or erased. It also includes data being viewed by users accessing it through various endpoints. (Saltzer & Schroeder, 1975).
- **Denial-of-Service Attacks** - An assault on a network that floods it with so many requests that regular traffic is either slowed or completely interrupted. Unlike a virus or worm, which can cause severe damage to databases, this interrupts network service for some period (PC Magazine, 2018).

## E

## F

- **Fundamental Design Principles**
    - **Separation (of Domains)** - The division of power within a system. No one part of a system should have complete control over another part. There should always be a system of checks and balances that leverage the ability for parts of the system to work together (Tjaden, 2015).
    - **Isolation** - Individual processes or tasks running in their own space. This ensures that the processes will have enough resources to run and will not interfere with other processes running (Tjaden, 2015).
    - **Encapsulation** - The ability to only use a resource as it was designed to be used. This may mean that a piece of equipment is not being used maliciously or in a way that could be detrimental to the overall system (Tjaden, 2015).
    - **Least Privilege** - The assurance that an entity only has the minimal amount of privileges to perform their duties. There is no extension of privileges to senior people just because they are senior; if they don’t need the permissions to perform their normal everyday tasks, then they don’t receive higher privileges (Tjaden, 2015).
    - **Simplicity (of Design)** - The straightforward layout of the product. The ability to reduce the learning curve when analyzing and understanding the hardware or software involved in the Information System (Tjaden, 2015).
    - **Layering** - Having multiple forms of security. This can be from hardware or software, but it involves a series of checks and balances to make sure the entire system is secured from multiple perspectives (Tjaden, 2015).
    - **Abstraction** - Removal of clutter. Only the needed information is provided for an object-oriented mentality. This is a way to allow adversaries to see only a minimal amount of information while securing other aspects of the model (Tjaden, 2015).
    - **Information Hiding** - Users having an interface to interact with the system behind the scenes. The user should not be worried about the nuts and bolts behind the scenes, only the modes of access presented to them. This topic is also integrated with object-oriented programming (Tjaden, 2015).
    - **Modularity** - The breaking down of larger tasks into smaller, more manageable tasks. This smaller task may be reused, and therefore the process can be repurposed time and time again (Tjaden, 2015).
    - **Minimization of Implementation (Least Common Mechanism)** - Mechanisms used to access resources should not be shared (Bishop, 2003).
    - **Open Design** - The security of a mechanism should not depend on the secrecy of its design or implementation (Bishop, 2003).
    - **Complete Mediation** - All accesses to objects should be checked to ensure that they are allowed (Bishop, 2003).
    - **Fail-Safe Defaults / Fail Secure** - The theory that unless a subject is given explicit access to an object, it should be denied access to that object (Bishop, 2003).
    - **Least Astonishment (Psychological Acceptability)** - Security mechanisms should not make the resource more difficult to access than when security mechanisms were not present (Bishop, 2003).
    - **Minimize Trust Surface (Reluctance to Trust)** - The ability to reduce the degree to which the user or a component depends on the reliability of another component (Bishop, 2003)
    - **Usability** - How easy hardware or software is to operate, especially for the first-time user. Considering how difficult applications and websites can be to navigate through, one would wish that all designers took usability into greater consideration than they do (PC Magazine, 2018).
    - **Trust Relationships** - A logical connection that is established between directory domains so that the rights and privileges of users and devices in one domain are shared with the other (PC Magazine, 2018)

## G

## H

- **Human Attack Surface** - Humans have a range of complex vulner¬abilities that are frequently exploited. One of the great strengths of highly secure organizations is their emphasis on communicating security awareness and safety principles to their employees, partners, supply chain and even their customers (as when using the web to gain secure access to a bank or 401K accounts) (Brocklehurst, 2014).

## I

- **Insider Problem** - The threat that an insider will use their authorized access, wittingly or unwittingly, to do harm to the security of the United States. This threat can include damage to the United States through espionage, terrorism, unauthorized disclosure, or through the loss or degradation of departmental resources or capabilities (CNSS, 2003).
- **IP Security (IPsec)** - A security protocol from the IETF that provides authentication and encryption over the internet. Unlike SSL, which provides services at layer 4 and secures two applications, this works at layer 3 and secures everything in the network. Also unlike SSL, which is typically built into the web browser, this requires a client installation. It can access both web and non-web applications, whereas SSL requires workarounds for non-web access such as file sharing and backup (PC Magazine, 2018).
- **IPv4 Addressing (Internet Protocol Version 4)** - The previous version of the IP protocol, which was introduced in 1981 and continues to be used alongside the subsequent Version 6 (PC Magazine, 2018).
- **IPv6 Addressing (Internet Protocol Version 6)** - The latest generation of the IP protocol. The specification was completed in 1997 by the Internet Engineering Task Force (IETF) and first deployed in 2004 when the Internet Corporation for Assigned Names and Numbers (ICANN) added IPv6 records to its DNS root servers for Japan and Korea. IPv6 is backward compatible with IPv4 and was designed to fix its shortcomings, such as data security and maximum number of user addresses (PC Magazine, 2018).

## J

## K

## L

- **Layer 3 Security Issues** - In networking, the communications protocol that contains the logical address of a client or server station. It is called the "network layer" and contains the address (IP, IPX, etc.) inspected by a router that forwards it through the network. It contains a type field so that traffic can be prioritized and forwarded based on message type as well as network destination. Since this provides more filtering capabilities, it also adds more overhead than layer 2 processing (PC Magazine, 2018).

## M

- **MAC Spoofing**
    - Faking the sending address of a transmission to gain illegal (unauthorized) entry into a secure system;
    - The deliberate inducement of a user or resource to take incorrect action. Note: Impersonating, masquerading, piggybacking, and mimicking are forms of this (CNSS, 2003).
- **Man-in-the-Middle (MITM) Attacks** - An unauthorized interception of network traffic. The packets are viewed or modified by the perpetrator and sent on to the recipient, who is unaware of the intrusion. This can be used to intercept an encrypted message exchange and spoof the recipient into thinking the message is intact from a legitimate sender. In such a case, the attackers replace the public key from the original sender with their own public key in order to decrypt the message that will be sent back from the unsuspecting recipient (PC Magazine, 2018).
- **Malware Attacks** - Software designed to destroy data, steal information or aggravate the user (PC Magazine, 2018)

## N

- **Netstat (Network Statistics)** - A command-line utility that reports the status of TCP/IP and Ethernet connections. It comes with all major operating systems, but the Linux/Unix versions provide the most command options. GUI-based versions for Windows, such as NetStat Live and X-NetStat, are also available.
- **Network Application**
    - **Hypertext Transfer Protocol (HTTP)** - The communications protocol used to connect to web servers on the internet or on a local network (intranet). Its primary function is to establish a connection with the server and send HTML pages back to the user's browser. It is also used to download files from the server either to the browser or to any other requesting application that uses HTTP (PC Magazine, 2018).
    - **Secure Shell (SSH)** - A security protocol for logging into a remote server. It provides an encrypted session for transferring files and executing server programs. Also serving as a secure client/server connection for applications such as database access and email, it supports a variety of authentication methods.
    It was developed in the mid-1990s by Helsinki University researcher Tatu Ylönen as a secure alternative to non-secure telnet, rlogin, and rsh programs for Unix servers. SSH2, a more advanced version introduced in 1998, was standardized by the IETF and is not compatible with SSH1 (PC Magazine, 2018).
    - **Simple Mail Transfer Protocol (SMTP)** - The standard email protocol on the internet and part of the TCP/IP protocol suite, as defined by IETF RFC 2821. It defines the message format and the message transfer agent (MTA), which stores and forwards the mail. It was originally designed for only plain text (ASCII text), but MIME and other encoding methods enable executable programs and multimedia files to be attached to and transported with the email message (PC Magazine, 2018).
    - **Voice Over IP (VoIP)** - A digital telephone service that uses the internet for transport, as well as private IP networks. IP stands for "internet protocol." In order for calls to originate and terminate from regular telephones, connections to the public telephone network (PSTN) are also provided. Telephone companies, cable companies, and dedicated providers offer this type of calling for a fixed monthly fee or low per-minute charge. Customers must have existing internet access (PC Magazine, 2018).
- **Network Architectures**
    - **Demilitarized Zone (DMZ)** - A middle ground between an organization's trusted internal network and an untrusted, external network such as the internet. Also called a "perimeter network," it is a subnetwork (subnet) that may sit between firewalls or off one leg of a firewall. Organizations typically place their web, mail, and authentication servers in it. It is a military term that refers to the area between two enemies (PC Magazine, 2018).
    - **Local Area Network (LAN)** - A communications network that is typically confined to a building or premises. The "clients" are user workstations running the Windows, Mac, or Linux operating systems, while the "servers" hold programs and data shared by the clients. Servers come in a wide range of sizes, from PC-based servers to mainframes (PC Magazine, 2018).
    - **Network Address Translation (NAT)** - The technology that maintains the privacy of the addresses of the computers in a home or business network when accessing the internet. It converts the private addresses that are assigned to the internal computers to one or more public addresses that are visible on the internet. It is an IETF standard that is implemented in a router or firewall as well as in any user's machine that is configured to share its internet connection. 
    It assigns a number to the packet headers of the messages going out to the internet and keeps track of them via an internal table that it creates. When responses come back from the internet, it uses the table to perform the reverse conversion to the private IP address of the requesting client machine (PC Magazine, 2018).
    - **Personal Area Network (PAN)** - Transmitting data wireless over a short distance. Bluetooth and Wi-Fi Direct are examples of this (PC Magazine, 2018).
    - **Protected Enclaves** - Subdivision of the internal network so that it is not one large zone with no internal protections. This architectural approach to information security defense in depth can be accomplished in a number of ways, including network admissions control, firewalls, VLANs, and VPN (Northcutt, n.d.).
    - **Subnetwork (Subnet)** - A logical division of a local area network, which is created to improve performance and provide security. To enhance performance, it limits the number of nodes that compete for available bandwidth. Instead of one network handling all the traffic, the network is divided into groups of clients and servers that interact with each other most of the time. For security, the divisions can be based on servers that have restricted applications. Routers are bridges used to traverse network segments. In an IP network, the subnet is identified by a subnet mask (PC Magazine, 2018).
    - **Supernetting** - Combining several IP network addresses into one IP address. It reduces the number of entries in a routing table and is done in CIDR addressing as well as in internal networks. 
    In the following example, a group of networks with contiguous numbers starting with 172.16.8.0 and ending with 172.16.16.0 are supernetted into the subnet mask of 255.255.224.0. The subnet mask is derived by comparing the binary of the first and last addresses. The last bit location on the right that is the same in both addresses marks the end of the mask. The CIDR notation for this is /19, because there are 19 1 bits in the subnet mask. For example, the IP address 172.16.8.1 would be 172.16.8.1/19 (PC Magazine, 2018).
    - **VLAN** - A logical subgroup within a local area network that is created via software rather than by manually moving cables in the wiring closet. It combines user stations and network devices into a single unit regardless of the physical LAN segment they are attached to and allows traffic to flow more efficiently within populations of mutual interest. 
    These are implemented in port-switching hubs and LAN switches and generally offer proprietary solutions. They reduce the time it takes to implement moves, adds, and changes. 
    VLANs function at layer 2. Since their purpose is to isolate traffic within the VLAN, in order to bridge from one VLAN to another, a router is required. The router works at the higher layer 3 network protocol, which requires that network layer segments are identified and coordinated with the VLANs. This is a complicated job, and VLANs tend to break down as networks expand and more routers are encountered. The industry is working toward "virtual routing" solutions, which allow the network manager to view the entire network as a single routed entity (PC Magazine, 2018).
    - **Wide Area Network (WAN)** - A long-distance communications network that covers a wide geographic area, such as a state or country. The telephone companies and cellular carriers deploy these to service large regional areas or the entire nation. Large enterprises have their own private WANs to link remote offices, or they use the internet for connectivity. Of course, the internet is the world's largest WAN (PC Magazine, 2018).
- **Network Attack Surface**
    - This presents exposure related to ports, protocols, channels, devices (from routers and firewalls to laptops and smartphones), services, network applications (SaaS) and even firmware interfaces;
    - Depending on your infrastructure, you may need to include cloud servers, data, systems and processes in this (Brocklehurst, 2014).
- **Network Mapper (Nmap)** - A free, open-source security scanner for auditing networks that runs on most platforms and is written by Fyodor (a person). When aimed at a particular host, it can determine which ports are open, which operating system and version is running, what services are offered, and what firewalls are used (PC Magazine, 2018).
- **Network Media**
    - **Optical** - Communications between computers, telephones, and other electronic devices using light. This type of network is far more reliable and has far greater potential transmission capacity than networking in the electrical domain (PC Magazine, 2018).
    - **Wired** - Connected via cable (PC Magazine, 2018)
    - **Wireless** - Transmission through the air. Although all forms of radio transmission over the air (AM, FM, TV, cordless phones, cell phones, etc.) are naturally wireless, there is a tendency for the term to refer only to Wi-Fi or to cellular data services (PC Magazine, 2018).
- **Network Naming**
    - **Border Gateway Protocol (BGP)** - The routing protocol that is used to span autonomous systems on the internet. It is a robust, sophisticated, and scalable protocol that was developed by the Internet Engineering Task Force (IETF). BGP4 supports the CIDR addressing scheme, which increased the number of available IP addresses on the internet. A path vector protocol, it was designed to supersede EGP, the original exterior gateway protocol (PC Magazine, 2018).
    - **Classless Interdomain Routing (CIDR)** - An expansion of the IP addressing system that allows for a more efficient and appropriate allocation of addresses. The original class-based method used fixed fields for network IDs, which was wasteful. For example, Class A and B networks can address 16 million and 65 thousand hosts respectively, and most organizations given those addresses never had intentions of putting that many computers on the internet (PC Magazine, 2018).
    - **Domain Name System (DNS)** - The internet's system for converting alphabetic names into numeric IP addresses. For example, when a web address (URL) is typed into a browser, these servers return the IP address of the web server associated with that name. In this made-up example, it converts the URL “www.company.com” into the IP address 204.0.8.51. Without this, you would have to type the series of four numbers and dots into your browser to retrieve the website, which you actually can do (PC Magazine, 2018).
    - **Dynamic Host Configuration Protocol (DHCP)** - The automatic assigning of IP addresses to client machines logging into an IP network. The same address, although technically temporary, may remain with a machine indefinitely unless a conflict arises with other devices on the network. The software, which resides in the router or a server, eliminates the need to manually assign permanent "static" IP addresses to devices. In a home network, it is typically in the wireless router (PC Magazine, 2018).
    - **Dynamic IP** - A temporary numeric identification assigned to a node in a TCP/IP network. When computers and devices in the network are turned on for the first time, they are assigned an IP address by a DHCP server (PC Magazine, 2018).
    - **Firewall** - The primary method for keeping a computer secure from intruders. It allows or blocks traffic into and out of a private network or the user's computer. These are widely used to give users secure access to the internet as well as to separate a company's public web server from its internal network. They are also used to keep internal network segments secure; for example, the accounting network might be vulnerable to snooping from within the enterprise (PC Magazine, 2018).
    - **Gateway** - A device that converts one protocol or format to another. A network gateway converts packets from one protocol to another. An application gateway converts commands and/or data from one format to another. An email gateway converts messages from one mail format to another (PC Magazine, 2018).
    - **Hosts** - A source of information or signals. The term can refer to a computer, smartphone, tablet, or any electronic device. In a network, clients (users' machines) and servers are hosts because they are both sources of information in contrast to network devices, such as routers and switches, which only direct traffic (PC Magazine, 2018).
    - **NetBIOS** - The original networking protocol for DOS and Windows PCs. These packets did not contain a network address and were not easily routable between networks. As a result, the interface to NetBIOS and the transport part of NetBIOS were later separated so that NetBIOS applications could use routable protocols such as TCP/IP and SPX/IPX (PC Magazine, 2018).
    - **NetFlow** - A network protocol developed by Cisco for the collection and monitoring of network traffic flow data generated by NetFlow-enabled routers and switches (Rouse, 2014)
    - **Open Systems Interconnection Model (OSI Model)** - This International Organization of Standardization model serves as a standard template for describing a network protocol stack (PC Magazine, 2018).
    - **Port Address Translation (PAT) Protocol** - The most common way network address translation is implemented. Also called "NAT overloading," "network address port translation" (NAPT) and "NAT/PAT." It assigns a different TCP port number to each client session with a server on the internet. When responses come back from that server, the source port number becomes the destination port number and determines which user to route the packets to. It also validates that the incoming packets were indeed requested (PC Magazine, 2018).
    - **Port Forwarding** - Also called "port mapping," this is directing traffic from the outside world to the appropriate server inside a local TCP/IP network. Internet services are identified by a standard port number; for example, web traffic uses port number 80. If the local network hosts a web server that is accessible on the public internet, the port forwarding panel in the router would be configured to direct web/HTTP packets (port 80 traffic) to the IP address of the web server in the local network (LAN) (PC Magazine, 2018).
    - **Routing** - Forwarding data to its destination (PC Magazine, 2018)
    - **Static IP** - A permanent numeric identification assigned by the network administrator to a node in a TCP/IP network. These addresses are used for shared resources such as web servers, PBXs, and webcams (PC Magazine, 2018).
    - **Switching** - A mechanical or electronic device that directs the flow of electrical or optical signals from one side to the other. Those with more than two ports, such as a LAN switch or PBX, are able to route traffic (PC Magazine, 2018).
    - **Virtual Private Network (VPN)** - A private network configured within a public network such as the internet or a carrier's network. Years ago, this obsoleted private lines between company branches. Using data encryption to maintain privacy, they also allow mobile users access to the company LAN. In the past, common carriers used their vast networks to "tunnel" traffic between customer locations to give the appearance of a private network while sharing backbone trunks, no different than the way the internet works. Prior to the internet's IP protocol, these were built over X.25, Switched 56, frame relay, and ATM technologies (PC Magazine, 2018).
- **Network Protocols**
    - **Internet Control Message Protocol (ICMP)** - A TCP/IP protocol used to send error and control messages. For example, a router uses this to notify the sender that its destination node is not available. A ping utility sends ICMP echo requests to verify the existence of an IP address (PC Magazine, 2018).
    - **Internet Protocol (IP)** - The communications technology used worldwide in local networks, wide area networks, and the internet. It is the network layer in the TCP/IP protocol suite, which is used to route packets from one network to another (PC Magazine, 2018).
    - **Transmission Control Protocol (TCP)** - The reliable transport protocol within the TCP/IP protocol suite. It ensures that all data arrive accurately and 100% intact at the other end. It is "connection oriented" and requires a handshake before the session can begin (PC Magazine, 2018).
    - **User Datagram Protocol (UDP)** - A TCP/IP protocol that is widely used for streaming of audio and video, voice over IP (VoIP), and videoconferencing. It is considered an unreliable delivery protocol because it does not check for errors. When transmitting voice and video, there is no time to retransmit erroneous or dropped packets. In contrast, when financial and other data are transmitted, TCP is used, which does check for errors (PC Magazine, 2018).
- **Network Services**
    - **Network Time Protocol (NTP)** - A TCP/IP protocol used to synchronize the real-time clocks in computers, network devices, and other electronic equipment that is time-sensitive. It is also used to maintain the correct time in NTP-based wall and desk clocks (PC Magazine, 2018).
- **Network Switching (Ethernet)**
    - **Address Resolution Protocol (ARP)** - A TCP/IP protocol used to obtain a node's physical address. A client station broadcasts this request onto the network with the IP address of the target node it wishes to communicate with, and the node with that address responds by sending back its physical address so that packets can be transmitted. This returns the layer 2 address for a layer 3 address (PC Magazine, 2018).
    - **Layer 2 Security Issues** - In networking, the communications protocol that contains the physical address of a client or server station. It is called the "data link layer" or "MAC layer" and contains the address inspected by a bridge or switch. Layer 2 processing is faster than layer 3 processing because less analysis of the packet is required (PC Magazine, 2018).
    - **Reverse ARP (RARP)** - A TCP/IP protocol used by a diskless workstation to obtain its IP address. Upon startup, the client station sends out this request in an Ethernet frame to the RARP server, which returns the layer 3 address for a layer 2 address (performing the opposite function of an ARP) (PC Magazine, 2018).

## O

## P

- **Packet Internet Groper (Ping)** - An internet utility used to determine whether a particular IP address is reachable online by sending out a packet and waiting for a response. It is used to test and debug a network as well as see if a user or server is online (PC Magazine, 2018).
- **PCI DSS** - A document library that includes framework of specifications, tools, measurements and support resources to help organizations ensure the safe handling of cardholder information (PCISSC, 2018).
- **Phishing Attacks** - This is a scam to steal valuable information such as credit card and social security numbers, user IDs and passwords. Also known as "brand spoofing," this process involves an official-looking email being sent to potential victims and pretending to be from their bank or retail establishment. Emails can be sent to people on selected lists or any list, expecting some percentage of recipients will actually have an account with the organization (PC Magazine, 2018).

## Q

## R

- **Routing Table** - A database in a router that contains the current network topology (PC Magazine, 2018).

## S

- **Session Hijacking** - Seizing unauthorized control of a computer or communications session in order to steal data or compromise the system in some manner (PC Magazine, 2018).
- **Sniffing** - This allows individuals to capture data as it is transmitted over a network. This technique is used by network professionals to diagnose network issues, and by malicious users to capture unencrypted data, like passwords and usernames (PC Magazine, 2018).
- **Spoofing**
    - Faking the sending address of a transmission in order to gain illegal entry into a secure system;
    - Creating fake responses or signals in order to keep a session active and prevent timeouts. For example, mainframes continuously poll their terminals. If the lines to remote terminals are temporarily suspended because there is no traffic, a local device spoofs the host with "I'm still here" responses;  
    - The most common forms of spoofing are:
        - **DNS server**: Modifies a DNS server in order to redirect a domain name to a different IP address. It's typically used to spread viruses;
        - **ARP**: Links a perpetrator’s MAC address to a legitimate IP address through spoofed ARP messages. It's typically used in denial of service (DoS) and man-in-the-middle assaults;
        - **IP address**: Disguises an attacker’s origin IP. It's typically used in DoS assaults. (PC Magazine, 2018)
- **Social Engineering** - Using deception to obtain confidential information from someone by phone or in person. For example, these attackers may persuade someone to reveal an ID or password for a supposedly benign purpose. ("My computer is down; can I use yours in the meantime?") They can even walk in off the street and pretend to be from IT doing a routine inspection (PC Magazine, 2018).
- **Software Attack Surface**
    - This is comprised of the software environment and its interfaces. These are the applications and tools available to authorized (and unauthorized) users;
    - This is calculated across a lot of different kinds of code, including applications, email services, configurations, compliance policy, databases, executables, DLLs, web pages, mobile apps, device OS, etc. (Brocklehurst, 2014)
- **SQL Injection Attacks (SQLi)** - An exploit that takes advantage of database query software that does not thoroughly test the query statement for correctness. Along with cross-site scripting, this is used by worms to break into websites and extract data or embed malicious code (PC Magazine, 2018).

## T

- **T1 Line** - A 1.544-Mbps point-to-point, dedicated, digital circuit provided by the telephone companies. With the monthly cost typically based on distance, these are widely used for connecting an organization's PBX to the telephone company or a local network (LAN) to an internet provider (ISP). They are also used for internet access in buildings that have no DSL, cable, or fixed wireless coverage (PC Magazine, 2018).
- **Threat Actor** - An individual or entity that poses a threat to the security of an organization. Also called a "malicious actor" (PC Magazine, 2018).
- **Threat Information Sources (e.g., CERT)** - Analytical insights into trends, technologies, or tactics of an adversarial nature affecting information systems security (CNSS, 2003).
- **Trojan Horse** - The term comes from Greek mythology, in which the Greeks battled the Trojans (people of Troy). After years of being unable to break into the fortified city, the Greeks built this, filled it with soldiers and pretended to sail away. After the Trojans brought this into the city, the Greek soldiers crept out at night and opened the gates of Troy to the returning soldiers, and Troy was destroyed (PC Magazine, 2018).
- **Trojan Virus** - A program that appears legitimate but performs some illicit activity when run. It may be used to locate password information or make the system more vulnerable to future entry or simply destroy the user's stored software and data. This is similar to a virus, except that it does not replicate itself. Often sneaking in attached to a free game or other supposedly worthwhile utility, it remains in the computer doing damage or allowing someone from a remote location to take control (PC Magazine, 2018).

## U

## V

- **Virus** - Software used to infect a computer. After the code is written, it is buried within an existing program. Once that program is executed, the code is activated and attaches copies of itself to other programs in the computer and other computers in the network. Infected programs continue to propagate it, which is how it spreads (PC Magazine, 2018).

## W

- **Web Application Attacks** - These attacks are considered by security experts to be the greatest and often the least understood of all risks related to confidentiality, availability, and integrity. The purpose of a this attack is significantly different from other attacks; in most traditional penetration testing exercises, a network or host is the target of attack. These attacks focus on an application itself and function on layer 7 of the OSI (Desmond, 2004).
- **Wireless Attacks** - A malicious action against wireless system information or wireless networks; examples can be denial of service attacks, penetration, and sabotage (Khosrow-Pour, 2005).

## X

## Y

## Z

- **Zero-Day Exploits** - An attack that exploits a previously unknown hardware, firmware, or software vulnerability (CNSS, 2003)

## References

Bishop, M. (2003). Computer security: Art and Science (1st ed.). Boston, MA: Addison-Wesley Professional.

Brocklehurst, K., (2014). Understanding what constitutes your attack surface. Retrieved from https://www.tripwire.com/state-of-security/featured/understanding-constitutes-attack-surface-2/

Cebula, J. J., Popeck, M. E., & Young, L. R. (2014). A taxonomy of operational cyber security risks version 2. Pittsburgh, PA: Software Engineering Institute.

CNSS. (2003). National information assurance (IA) glossary. Retrieved from https://www.ecs.csus.edu/csc/iac/cnssi_4009.pdf

Desmond, P. (2004). All-out blitz against web app attacks. Retrieved from http://www.networkworld.com/techinsider/2004/0517techinsidermain.html

Invincea. (2015). Know your adversary: An adversary model for mastering cyber-defense strategies. Retrieved from http://www.ten-inc.com/presentations/invincea1.pdf

Khosrow-Pour, M. (Ed.). (2015). Encyclopedia of information science and technology (3rd ed.). Hershey, PA: IGI Global.

Kim, D., & Solomon, M. G. (2013). Fundamentals of information systems security (2nd ed.). Burlington, MA: Jones & Bartlett Publishers.

NIST. (2013). Security and privacy controls for federal information systems and organizations. Retrieved from http://dx.doi.org/10.6028/NIST.SP.800-53r4

Northcutt, S. (n.d.). Security laboratory: Defense in depth series. SANS Technology Institute. Retrieved from https://www.sans.edu/cyber-research/security-laboratory/article/372

PCISSC. (2018). Document library. Retrieved from https://www.pcisecuritystandards.org/document_library

PC Magazine. (2018). Encyclopedia. Retrieved from https://www.pcmag.com/encyclopedia

Rouse, M. (2014). NetFlow. WhatIs.com. Retrieved from https://whatis.techtarget.com/definition/NetFlow-Cisco

Saini, V. K., Duan, Q., & Paruchuri, V. (2008). Threat modeling using attack trees. Journal of Computing Sciences in Colleges, 23(4), 124-131.

Saltzer, J., & Schroeder, M. (1975). The protection of information in computer systems. Proceedings of the IEEE, 63(9), 1278-1308. doi:10.1109/proc.1975.9939

Tjaden, B. C. (2015). Appendix 1  Cybersecurity first principles. Retrieved from https://users.cs.jmu.edu/tjadenbc/Bootcamp/0-GenCyber-First-Principles.pdf
