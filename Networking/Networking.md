--------------------------------
# Protocols
Protocols in networking are a set of rules that define how devices or applications communicate with each other over a network.

--------------------------------

# Packets
Packets are small units of data that are sent over a network. They help to break up large amounts of data into smaller.
They contain information such as source and destination addresses, data.
Packets are stream of bits. 
packet structure:
header: 
contains information such as the source and destination addresses, packet sequence number, checksum, and other control information.
payload: 
contains the actual data being transmitted, which could be a file, an email message, a web page, or any other type of digital content.

--------------------------------

# OSI (Open Systems Interconnection) Model
The OSI (Open Systems Interconnection) model is a conceptual framework that describes the communication functions of a telecommunication or computer system. It consists of seven layers, each with a specific role in the communication process:
1.  Physical Layer: This layer is responsible for transmitting raw data bits over the physical medium such as copper wire, fiber optic, or wireless signals.
2.  Data Link Layer: This layer provides error-free transmission of data between two devices on the same network, using protocols such as Ethernet.
3.  Network Layer: This layer provides the means for routing data packets between networks, using protocols such as IP.
4.  Transport Layer: This layer ensures the reliable transfer of data between end-to-end systems, using protocols such as TCP and UDP.
5.  Session Layer: This layer manages the connections between applications on different devices, establishing, managing, and terminating sessions.
6.  Presentation Layer: This layer is responsible for formatting, encrypting, and compressing data to be sent across the network, ensuring that data is presented correctly to the application layer.
7.  Application Layer: This layer provides network services to applications, enabling them to interact with the network, using protocols such as HTTP, FTP, and SMTP.
**************************************
Here are some of the most common protocols used for each layer of the OSI model:
1.  Physical Layer: Ethernet, Wi-Fi, Bluetooth, USB, HDMI, RS-232
2.  Data Link Layer: Ethernet, Wi-Fi, PPP, HDLC, ATM
3.  Network Layer: IP, ICMP, ARP, OSPF, BGP
4.  Transport Layer: TCP, UDP, SCTP, DCCP
5.  Session Layer: NetBIOS, SAP, SOCKS
6.  Presentation Layer: SSL, TLS, ASCII, EBCDIC
7.  Application Layer: HTTP, FTP, SMTP, DNS, DHCP, Telnet, SSH, SNMP

--------------------------------

# TCP/IP
TCP/IP is a set of communication protocols used for transmitting data over networks.
-   Link layer (> Data Link layer)
-   Internet layer (> Network layer of OSI)
-   Transport layer
-   Application layer (> Session + Presentation + Application layer of OSI)

--------------------------------

# Encapsulation
Encapsulation in TCP/IP refers to the process of adding headers and trailers to data as it is transmitted through the network. Each layer of the TCP/IP protocol stack adds its own headers and trailers to the data, forming a packet. Encapsulation is important because it allows data to be transmitted over a network that may use different technologies and protocols at different layers.
![[encapsulation.jpg]]


--------------------------------
# Internet Protocol (IP)
The IP protocol routes data packets (IP datagrams) between hosts on a network using IP addresses to identify the hosts. It is connectionless and does not establish a dedicated connection. The protocol also handles packet fragmentation, reassembly, and error detection.
## IPv4 Addresses
IPv4 addresses are unique identifiers for devices on the internet and are made up of 32-bit integers. They can be represented in either hexadecimal or dotted decimal notation, with the format being x.x.x.x, where x can be any value from 0 to 255. IPv4 is still widely used today and handles the majority of internet traffic. An IPv4 address is made up of four bytes or octets, with each byte consisting of 8 bits.
## IPv6 Addresses
IPv6 is the successor to IPv4 and uses 128-bit addresses, allowing for a significantly larger address space than IPv4. IPv6 addresses are typically represented in hexadecimal notation and separated into eight groups of four hexadecimal digits, separated by colons. For example, 2001:0db8:85a3:0000:0000:8a2e:0370:7334 is a valid IPv6 address. IPv6 is designed to address the limitations of IPv4, including the limited number of unique addresses and the increasing demand for internet-connected devices. Despite its advantages, IPv6 adoption is still relatively low compared to IPv4.
## IPv4 vs IPv6 
![[IPv4-vs-IPv6.png]]

---------------------------
# subnet mask
A network mask, or subnet mask, is a 32-bit binary number that is used to divide an IP address into network and host addresses. It determines which part of the IP address identifies the network and which part identifies the host, allowing devices to communicate with each other on a network.