
![[osi_info.png]]

# OSI Model — Summary Points & Interview Questions

The OSI (Open Systems Interconnection) Model is a reference model that explains how data travels from one device to another over a network. It consists of 7 layers, and each layer has a specific responsibility.

## 1. The 7 layers of the OSI Model

Layer 7 — Application

Provides network services to user applications.

Examples: HTTP, HTTPS, DNS, SMTP, FTP

![Protected document](https://images.openai.com/static-rsc-4/kRCoKfqpiVPBob7MTcbrLL_WV88yowLADgmEE0HeJNPSn1zoUszF2TlaILZFLW2F_lS6tur3NBwcmfANQFQJNErn98Yd3Hhcgjft-VR3T9tcS-MvxdF-U9C4wPZOnPZlTgpfyUqqNc3KZRfnSlM0GWhKgRiksv2fIgywflTY-SyWUx3wR1l1aKuI6Ndb6dl6?purpose=inline)

Add to Favorites

Layer 6 — Presentation

Data formatting, encryption/decryption, and compression.

Examples: TLS/SSL concepts, JPEG, character encoding

![Computer connecting icon. Vector illustration. EPS 10.](https://images.openai.com/static-rsc-4/K_0uuga20vAfduoq3Da3CRiPeuwmtbcvTJtR1sZ66qH-4Lebe878WJAJX7fpkgKWq-PelhSSkYxTTT2igVEzMFjfaXpGFK7aROlPd0mfSfszro8VSIUyBgHbdjvxkmzT5hplgVPjW9SF97XQZPvUChdK2F_Z9NMh9yjwdS47oYOCvd8jkjc4_oypTZaUnk3_?purpose=inline)

Add to Favorites

Layer 5 — Session

Establishes, manages, and terminates communication sessions.

![Telecommunications](https://images.openai.com/static-rsc-4/r2LMNq7CRi6-Q7JLimNloAuVAWsWZAeNCOQP6Lugf0flO4xEoUMTOO8M81pDU7hal-YuuIcEzuOAQvvei_ZYjGp0718kRLdcyAA5LR-NHuWmOgoBCPhcAr_PGN2Drc6ura05ugIbiNvXmB490_FqiBjAruzyvSZmQot6TzbjxOY?purpose=inline)

Add to Favorites

Layer 4 — Transport

End-to-end delivery, segmentation, reliability, and flow control.

Examples: TCP, UDP · PDU: Segment (TCP), Datagram (UDP)

![router, internet modem line icon](https://images.openai.com/static-rsc-4/qhF0rfuKIG2eV5iTG6SHmTeTwaPuoJwTq2biNZSSHfd3oWpR9CZaCWRnutjaXcXD_tT7fSpkw8yWa8qe3LvJHfoTpKlUJE3QqorM9Q3dOURE4pu1JCisXeicpjiypxQzrJvsZsLUHUu73kYLnakaXh_bWpCczhITY3FFNV8ocKUST3geaFDhCY99HquqRvHA?purpose=inline)

Add to Favorites

Layer 3 — Network

Logical addressing and routing packets between networks.

Examples: IP, ICMP · Device: Router · PDU: Packet

![Capas Física y Enlace de Datos](https://images.openai.com/static-rsc-4/g7CcyDqFqRRWItmmNt0STkv06jiy6KI17F64ZTXxRIZrNubgjWh1WnoInjjllrovOZruViEZLatqeQrXaOx5Z8B4iDDj6MLdtywpTsvDLgnBq1tfVyKWDCWrqaoaH4NzSpCVxGwGJczp16UM8lQrEngEWD9YYIkZNzoQQ_L3K9g?purpose=inline)

Add to Favorites

Layer 2 — Data Link

Transfers frames over a local link using MAC addresses; handles error detection.

Examples: Ethernet, Wi-Fi MAC · Device: Switch · PDU: Frame

![Ethernet, Wi-Fi, Fiber, Coaxial & Radio: Transmission Media Compared - DEV Community](https://images.openai.com/static-rsc-4/Ibnal-uraLwMOmAqMa4XW-m_N-DkbXFhbtVvTDN7JMvHJkp7S258ayRFSFtfVwVgLYqxhX1wqJzS7zyb1c8Y8Iw4IgKoQSCh0xWr-EA2wPxvPkoPfZanVKqgOF92ue2ZUGYXHIrsPn5ipIIXwmi8mQ9ZWxJX2Ro_rEZVGJRH_Q4?purpose=inline)

Add to Favorites

Layer 1 — Physical

Transmits raw bits through electrical, optical, or radio signals.

Examples: Cables, connectors, radio signals · PDU: Bits

## 2. Easy way to memorize the layers

From Layer 7 down to Layer 1:

All People Seem To Need Data Processing.

|Layer|Name|Main function|
|---|---|---|
|7|Application|Network services|
|6|Presentation|Format, encrypt, compress|
|5|Session|Manage sessions|
|4|Transport|Deliver data end-to-end|
|3|Network|Route packets|
|2|Data Link|Frames and MAC addresses|
|1|Physical|Transmit bits|

Another common mnemonic from Layer 1 up to Layer 7 is: Please Do Not Throw Sausage Pizza Away.

## 3. Important interview points to remember

- OSI has 7 layers, while the TCP/IP model is commonly represented with 4 layers.
    
- Data travels from Layer 7 to Layer 1 at the sender.
    
- At the receiver, data travels from Layer 1 to Layer 7.
    
- This process is called encapsulation at the sender and decapsulation at the receiver.
    
- Each layer adds or processes information needed for communication.
    
- IP address works at Layer 3; MAC address works at Layer 2.
    
- TCP is connection-oriented and provides reliable delivery; UDP is connectionless and has lower overhead.
    
- A router mainly operates at Layer 3; a traditional Ethernet switch mainly operates at Layer 2.
    
- The OSI model is a conceptual reference model used to understand networking and troubleshoot problems.
    

### PDU (Protocol Data Unit) — memorize this!

|Layer|PDU|
|---|---|
|Application, Presentation, Session|Data|
|Transport|Segment (TCP) / Datagram (UDP)|
|Network|Packet|
|Data Link|Frame|
|Physical|Bits|

## 4. Common OSI interview questions with answers

Here are 15 questions, from beginner to intermediate level.

1

What is the OSI model?

Answer

The Open Systems Interconnection model is a seven-layer reference model that explains how network communication works between devices.

2

Why do we use the OSI model?

Answer

It standardizes the way we describe network functions, helps different systems communicate, and makes troubleshooting easier by dividing communication into layers.

3

Name the seven layers.

Answer

Application, Presentation, Session, Transport, Network, Data Link, and Physical.

4

What is encapsulation?

Answer

Encapsulation occurs when each layer adds its own protocol information as data moves down the sender's protocol stack.

5

What is decapsulation?

Answer

Decapsulation occurs when the receiving device processes and removes the relevant protocol information as data moves up its stack.

6

What is the difference between TCP and UDP?

Answer

TCP provides reliable, ordered delivery with connection management. UDP has lower overhead and does not guarantee delivery or ordering.

7

What is the difference between an IP address and a MAC address?

Answer

An IP address is a logical network-layer address used for routing. A MAC address identifies a network interface at the data-link layer on a local link.

8

Which OSI layer does a router operate at?

Answer

Primarily Layer 3, the Network layer, where it forwards packets based on IP routing information.

9

Which OSI layer does a switch operate at?

Answer

A traditional Ethernet switch mainly operates at Layer 2 and forwards frames using MAC addresses. Some multilayer switches also perform Layer 3 routing.

10

What is the function of the Transport layer?

Answer

It supports end-to-end transport, segmentation, port addressing, and, depending on the protocol, reliability, retransmission, and flow control.

11

What is the function of the Presentation layer?

Answer

It handles data representation, such as formatting, character encoding, encryption/decryption, and compression in the OSI model.

12

What is the function of the Session layer?

Answer

It manages communication sessions, including establishing, coordinating, and terminating them.

13

What are the PDU names at different layers?

Answer

Upper layers: data; Transport: TCP segment or UDP datagram; Network: packet; Data Link: frame; Physical: bits.

14

What happens when you open a website?

Answer

The browser uses application protocols such as HTTP or HTTPS. DNS may resolve the domain name, transport protocols carry the data, IP routes packets, the data-link layer sends frames over each link, and the physical layer transmits signals.

15

How does the OSI model help with troubleshooting?

Answer

It helps isolate problems by layer: cable or signal at Layer 1, switching or MAC issues at Layer 2, IP routing at Layer 3, TCP/UDP and ports at Layer 4, and application or service issues at higher layers.



## 5. Practical scenario questions

These are particularly useful for technical interviews.

Q1. You cannot access a website. How would you troubleshoot it using the OSI model?

A:

1. Layer 1: Check the cable, Wi-Fi signal, and network adapter.
    
2. Layer 2: Check the local connection, switch port, and VLAN.
    
3. Layer 3: Check the IP address, subnet mask, default gateway, and routing.
    
4. Layer 4: Check whether the required TCP/UDP port is reachable.
    
5. Layers 5–7: Check session behavior, TLS configuration, DNS, browser settings, and the application server as appropriate.
    

Q2. If you can ping an IP address but cannot open a website, what could be wrong?

A: Possible causes include DNS resolution, blocked TCP port 80 or 443, TLS errors, proxy settings, or a problem with the web server. A successful ping alone does not prove that the website service is working.

Q3. What is the difference between a hub, switch, and router?

- Hub: Layer 1; repeats incoming signals to other ports.
    
- Switch: Primarily Layer 2; forwards Ethernet frames based on MAC addresses.
    
- Router: Layer 3; forwards IP packets between networks.
    

Q4. At which layer does HTTPS work?

A: HTTPS is an application-layer protocol built on HTTP and protected by TLS. TLS does not map perfectly to one OSI layer, although its encryption function is often associated with the Presentation layer in simplified OSI explanations.

Q5. What happens to a packet when it passes through a router?

A: The router examines the destination IP address and selects a route. It removes the incoming link-layer framing and sends the packet in new link-layer framing for the next link. The IP packet generally remains the same apart from changes such as the TTL or Hop Limit and associated checksums where applicable.

## 6. Quick self-test

1. Which layer is responsible for routing?
    

Data Link

Network

Transport

Session

Correct!

2. Which address is used by a traditional switch to forward Ethernet frames?
    

IP address

Port number

MAC address

URL

Correct!

3. Which transport protocol provides reliable, ordered delivery?
    

UDP

TCP

IP

ARP

Correct!

4. What is the PDU at Layer 2?
    

Bits

Packet

Frame

Segment

Correct!

5. Which layer transmits raw bits?
    

Physical

Network

Presentation

Application

Correct!

Score: 5/5



Final interview tip: If you remember only five things, remember the seven layer names, their order, TCP vs UDP, IP vs MAC, and the difference between a router and a switch. These are excellent foundations for OSI interview questions.