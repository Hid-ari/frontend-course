## Introduction to the Internet

The internet works by connecting devices and computer systems together using standardized protocols, such as IP and TCP.

A network is a group of computers or other devices which are connected to eachother. For example, you at your home might have a network of computers and devices. Your friend living next door might have a similar network of devices. Their neighbor might have a similar network of devices. All these networks when connected together form the internet.

> The internet is a network of networks.

### When we going to talk about a new subject it's good to know about its history.

- 1960s: Beginnings and ARPANET - The concept of a global communication network that could continue to operate even in the aftermath of a nuclear war began in the 1960s. In 1969, the Advanced Research Projects Agency Network (ARPANET), funded by the U.S. Department of Defense, connected four universities: UCLA, Stanford, UC Santa Barbara, and the University of Utah, marking the birth of what would eventually become the Internet.

- 1970s: Development of Protocols - During the 1970s, key protocols such as TCP/IP (Transmission Control Protocol/Internet Protocol) were developed by Vinton Cerf and Bob Kahn. These protocols allowed multiple networks to interconnect, forming a "network of networks."

- 1980s: Expansion and Adoption - In 1983, ARPANET adopted TCP/IP, and shortly afterward began to expand beyond military and academic institutions. During this decade, the Domain Name System (DNS) was also established, facilitating Internet navigation.

- 1990s: Birth of the World Wide Web - Tim Berners-Lee invented the World Wide Web in 1989 while working at CERN. The web utilized hypertext for accessing information and navigation, revolutionizing how the Internet was used. In 1993, the Mosaic browser was released, popularizing the Internet among the general public.

- 21st Century: Expansion and Globalization - The advent of new technologies such as fiber optics and advances in telecommunications have enabled massive expansion of the Internet. The adoption of mobile devices and the development of social media have further transformed how we interact online.

- Current Era: Internet of Things and Beyond - Today, the Internet connects not just computers and smartphones, but a wide array of devices through the Internet of Things (IoT). This has opened up new dimensions of interconnectivity and raised new challenges in terms of security and privacy.

## Basic Concepts and Terminology

- TCP is a communication protocol that enables the transmission of data between computers on a network. It was developed as part of the Internet protocol suite, known as TCP/IP, and is used by applications that require reliable, ordered delivery of data.

- IP (Internet Protocol) is a fundamental protocol in the suite of Internet protocols. It is responsible for addressing and routing packets of data so they can travel across networks and arrive at the correct destination.
  
- Packet: A small unit of data that is transmitted over the internet.

- Router: A device that directs packets of data between different networks.

- IP Address: A unique identifier assigned to each device on a network, used to route data to the correct destination.

- Domain Name: A human-readable name that is used to identify a website, such as google.com.

- DNS: The Domain Name System is responsible for translating domain names into IP addresses.

- HTTP: The Hypertext Transfer Protocol is used to transfer data between a client (such as a web browser) and a server (such as a website).

- HTTPS: An encrypted version of HTTP that is used to provide secure communication between a client and server.

- SSL/TLS: The Secure Sockets Layer and Transport Layer Security protocols are used to provide secure communication over the internet.

## The internet

The internet works by connecting devices and computer systems using a set of standardized protocols. These protocols define how information is exchanged between devices, ensuring that data is transmitted reliably and securely. At the core of the internet is a global network of interconnected routers that direct traffic between different devices and systems. Data sent over the internet is broken into small packets, which are sent from one device to a router and then to the next router in the path until they reach their final destination.

To ensure packets are sent and received correctly, the internet uses various protocols, including the Internet Protocol (IP) and the Transmission Control Protocol (TCP). IP is responsible for routing packets to their correct destination, while TCP ensures that packets are transmitted reliably and in the correct order.

The Domain Name System (DNS), Hypertext Transfer Protocol (HTTP), and Secure Sockets Layer/Transport Layer Security (SSL/TLS) are other crucial protocols for the internet's operation. DNS translates domain names into IP addresses, while HTTP and HTTPS (a secure version of HTTP using SSL/TLS to encrypt data) are used to transfer data between clients and servers.

IP addresses are unique identifiers assigned to each device on a network, used to route data to the correct destination. Domain names are human-readable names used to identify websites and other internet resources, translated into IP addresses by DNS.

When building applications with TCP/IP, understanding concepts like ports, sockets, and connections is essential. Ports identify the applications or services running on a device, sockets combine an IP address and a port number to represent a communication endpoint, and connections are established between sockets to transfer data between devices.

SSL/TLS is used to secure internet communications by encrypting transmitted data. Applications handling sensitive data should use SSL/TLS to protect information and maintain the integrity and confidentiality of communications.

Finally, it’s crucial to stay updated with emerging trends like 5G, the Internet of Things (IoT), Artificial Intelligence (AI), Blockchain, and edge computing to build innovative and effective applications and services.

The functioning of networks, including the internet, relies on a variety of devices and cables that facilitate the connection and communication between different components. Here are some of the key devices and cables that make this possible:

The functioning of networks, including the internet, relies on a variety of devices and cables that facilitate the connection and communication between different components.

## Devices And Cables

# Key Devices:

1. **Routers:**
   - **Function:** Direct traffic between different networks, ensuring that data packets reach their correct destination.
   - **Usage:** Found in both homes and businesses to connect local networks to the internet.

2. **Switches:**
   - **Function:** Connect devices within a single network, such as a local area network (LAN), and manage data traffic to ensure efficient communication.
   - **Usage:** Commonly used in network setups to link multiple devices like computers, printers, and servers.

3. **Modems:**
   - **Function:** Convert digital data from a computer into analog signals for transmission over telephone or cable lines and vice versa.
   - **Usage:** Essential for connecting to internet service providers (ISPs) through DSL, cable, or fiber connections.

4. **Network Interface Cards (NICs):**
   - **Function:** Provide the hardware interface between a computer and a network, allowing for both wired and wireless connections.
   - **Usage:** Built into most computers and other devices, or available as add-on cards.

5. **Wireless Access Points (WAPs):**
   - **Function:** Allow wireless devices to connect to a wired network using Wi-Fi.
   - **Usage:** Common in both home and business environments to provide wireless network access.

6. **Firewalls:**
   - **Function:** Monitor and control incoming and outgoing network traffic based on predetermined security rules, providing a barrier between a trusted internal network and untrusted external networks.
   - **Usage:** Essential for network security, found in both hardware and software forms.

# Key Cables:

1. **Ethernet Cables (Cat5, Cat5e, Cat6, Cat6a, Cat7):**
   - **Function:** Used for wired connections between network devices such as routers, switches, and computers.
   - **Specifications:** Different categories (Cat) support varying speeds and bandwidths, with Cat6 and above supporting higher speeds and better performance.

2. **Fiber Optic Cables:**
   - **Function:** Transmit data as light pulses, allowing for extremely high-speed and long-distance data transmission.
   - **Usage:** Used in backbone networks, data centers, and internet infrastructure to support high bandwidth requirements.

3. **Coaxial Cables:**
   - **Function:** Used for transmitting television and internet signals.
   - **Usage:** Commonly used by cable internet providers to connect modems to the ISP network.

4. **Telephone Cables (Twisted Pair, RJ11):**
   - **Function:** Used for DSL internet connections and traditional telephone services.
   - **Usage:** Connects modems and telephones to telephone lines.

# How They Work Together:

- **Home Network Example:** 
  - A **modem** connects to the internet via a coaxial or telephone cable, converting the signal for use by home devices.
  - The modem is connected to a **router** via an Ethernet cable, which then distributes the internet connection to various devices.
  - **Wireless access points** or the wireless capability of the router allows devices like smartphones and laptops to connect wirelessly.
  - **Switches** can be used to extend the network, connecting additional wired devices through Ethernet cables.

- **Business Network Example:**
  - **Routers** manage traffic between the internal network and the internet, while **firewalls** ensure security.
  - **Switches** connect a large number of devices within the internal network.
  - **Wireless access points** provide Wi-Fi access for mobile devices.
  - **Fiber optic cables** may be used for high-speed connections between different parts of the network or to connect to the ISP.
