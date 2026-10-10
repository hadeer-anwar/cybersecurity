![[intro_info.png]]

# Introduction to Computer Networks — Summary & Interview Questions

This infographic covers the fundamentals of computer networks: transmission media, networking devices, transmission modes, network categories, network topologies, and network administration types.

## 1. Summary points to study

### A. Transmission media

Transmission media are the paths through which data travels between network devices. They are divided into two main types.

![Ethernet Ports Explained: A Beginner's Guide](https://images.openai.com/static-rsc-4/PpyIyeHUPw8-nR9dFHGxC89X2wKortX0zXzplg35M4Ni_j43izEErmwb1_i_kjhAArHhChGB5iWmqPDmkNgb0D3MIRsrd9hLMJbAz0fQ3x88cAFe_BeSBc4Dn_7Hc17SiMscE1aD50eI36Q-gtDbNzfO7CX5S95wza47Bfk783E?purpose=inline)

Add to Favorites

1. Guided / Wired media

- Twisted-pair cable: UTP and STP; commonly used in Ethernet LANs.
    
- Coaxial cable: Used in cable TV, broadband, and some specialized networks.
    
- Fiber-optic cable: Transmits data as light; supports high bandwidth and long distances and is resistant to electromagnetic interference.
    

![Преимущества и возможности беспроводной локальной сети | новости | компания ZSC](https://images.openai.com/static-rsc-4/nCNQ4inXuEEZi2_X5J5NoxcotTWw_t1y2jGtxJxMEo6_nW_mfzXm-jokzYcz_1A37LYjihmU6xFEjmD8fla_dtzGtDe1sZkU8inaznZu1dG6z7AyuTKKL32iNr-yJUMJ-3eMzLLh9xavu9W2bZOpEWHsD-Xgpul6AiWfZMUPj18?purpose=inline)

Add to Favorites

2. Unguided / Wireless media

- Uses electromagnetic waves through the air.
    
- Examples: Wi-Fi radio waves, microwave links, and satellite communication.
    
- Advantages: Mobility and fewer cables.
    
- Limitations: Interference, coverage constraints, and security considerations.
    

Important cable facts

- UTP = Unshielded Twisted Pair.
    
- STP = Shielded Twisted Pair.
    
- RJ45 is the common name for the 8-position modular connector used with Ethernet twisted-pair cables.
    
- Fiber is often preferred for backbone links because of its high capacity and long-distance performance.
    
- Ethernet cable categories (Cat5e, Cat6, Cat6A, etc.) support different performance levels depending on the cable and installation.
    

### B. Networking devices

![TP-LINK Tg-3468 v1 Ενσύρματη Κάρτα Δικτύου Gigabit (1Gbps) Ethernet PCI-e | Skroutz.gr](https://images.openai.com/static-rsc-4/3yU46kLvnfE2fsWpzhsRow-HyIpt6rlcXEnXM922rhOcs-sJ3AYU9YMMfDD0IFHkEnbv5GJwQSmvhzHgKCs7i4LWyco4OxJm7owxpBcHTMWcZYjbCVQEZf9aLdaLqdSGcp2dldtTim7QEEVfCoJIW1XQ1IMnwJsZiIhjxSARHV8?purpose=inline)

Add to Favorites

NIC — Network Interface Card

Connects a computer or other device to a network. It may provide a wired Ethernet or wireless interface and has link-layer addressing capabilities.

![EDIMAX - Legacy Products - Hubs / USB Hubs - 5 Port Desktop Ethernet HUB](https://images.openai.com/static-rsc-4/QBcxdPXlUiGWznP1XNLeArk2aCWZXvwh5WSt-f-W8muE-cayF-_bSwgq-425MlfYb1rKN3KSTnG53VAu_3D_SujMV76uJJQieg7NMdvAoAOC8uPreJA-3MmoOHQbveAqrth7kPPg6kHh-US7xkpNN3oSxi9Tjv38MgFj2CykGug?purpose=inline)

Add to Favorites

Hub

A basic Layer 1 device that repeats incoming signals to its other ports. It does not intelligently filter traffic by MAC address.

![16-Port Gigabit Intelligent Ethernet Switch](https://images.openai.com/static-rsc-4/HPJMty0L71sw1NnFKW8eXNP0i11CO573Ymr73vqvtcXVxvBGvXSTFcWPmuzzoTRwXIkyST7oakxjps-tiqj4egmhavy5qATe9NOADf5m2zew6nRba48zpL5l-teox1sMr-r1q2fO3DoQRdEy9NA8jCrbcKCfOUorELIJR0zzskc?purpose=inline)

Add to Favorites

Switch

Primarily a Layer 2 device that forwards Ethernet frames using MAC address information. It reduces unnecessary traffic compared with a hub.

![Venta Caliente 2.4G&5g Router Inalámbrico WiFi de Doble Banda WiFi6 con 4 Antenas Externas para una Señal Más Fuerte y Mayor Cobertura - China Router, Router 4G](https://images.openai.com/static-rsc-4/d6odklNorFo5qx7KOMM1O3A1Ud3Dq01pY89nvVySwuPLy1RmCiGfm1p25GTR69qjTO2d_znlwhrv-PT8VMWUHMqWtLCdsc88e20FRdUiFZz5nakDYgf0VT3hG1jpfhF0YA9RndB_7xOmDVIxT72uzaAPKmqzlT1VtZ2CsA1tTfk?purpose=inline)

Add to Favorites

Router

Primarily a Layer 3 device that forwards IP packets between different networks, such as a home LAN and the internet.

![Ubiquiti UAP-AC-Lite Punto de Acceso Dual Band 2.4 GHz | PcComponentes.com](https://images.openai.com/static-rsc-4/LaVLhV7_oAYJMoMuzCfoXvibCZVdlv0QRSNYWY8T29KoW1hx_BLVO7cyoF4Qick0kEVCha1a9KSpXjOgLqxjmU_LwllfdRr31vyGAgWwst0w_u1_r1FC9jHFWV0rmPmjkOTtguEyTT45HFJ9TVeYzh7o5NPxiA6yBLYJVLvr-0c?purpose=inline)

Add to Favorites

Access Point (AP)

Provides wireless devices with access to a network, typically bridging Wi-Fi clients to a wired LAN.

### C. Transmission modes

Transmission mode describes the direction in which data can flow between two communicating devices.

![Networking and Telecommunications Class 10 Computer Science Chapter 1](https://images.openai.com/static-rsc-4/pnVNThGD9veDkKgwUa_xEkD2BIeO_M7rZ-PM4BXRugbEosenivXLeMtqVioih_25rQEdpoC6j1rlDb5IDxdyFMVYhq20zN59uEv3X5KBUOyL-9u8ZmUVuCZsRJdZKOfnRiee7_YB4SLtgMaBBr5kzhem72Qo5xg4Ywui83bLEco?purpose=inline)

Add to Favorites

Simplex — One-way

Data flows in one direction only.

Example: A traditional broadcast receiver receiving a transmission.

![Is Half-Duplex Communication Really That Bad?Industry dynamics_Blog](https://images.openai.com/static-rsc-4/eZkXRJvMmChy_NmNLclpvaXe2QjZ-B1LP0bFebn71qfTxcYt8DbCM3IFjcWI2VvAyTyNEk-N6yldW8Qa5a5cmgjxb94rUzbqDzwrD7jH8s7YWSoB1P33weOloaMsJk1YuyKmkZ9bUkuhF9bVCKgnsGyQL7vgHGO89sUjaQ8yu68?purpose=inline)

Add to Favorites

Half-duplex — Both directions, one at a time

Each side can transmit, but not simultaneously.

Example: A walkie-talkie.

![Half-Duplex vs Full-Duplex: What are the Differences?](https://images.openai.com/static-rsc-4/9USlbUhajHvQ7rvKKoykei18N3CzTL0E5PvEaz0A5dW_sLcqnn5ZVyZKhmJqgu4XiZpJJnOp3Sy1wvaINBkMTXSuqpP8HOZtM1SyNYRB7IJdwVjA4I6gOp-9-8i7PWoXqbSOxDT2PVaYkuwkbCXKUNlA04b2EMLLtkI9NpY0EoA?purpose=inline)

Add to Favorites

Full-duplex — Both directions simultaneously

Both sides can send and receive at the same time.

Example: A modern full-duplex Ethernet link.

### D. Network categories by geographical area

|Network|Full name|Coverage / example|
|---|---|---|
|PAN|Personal Area Network|Very short range, such as Bluetooth between personal devices|
|LAN|Local Area Network|Home, lab, office, or campus building|
|MAN|Metropolitan Area Network|A city or metropolitan area|
|WAN|Wide Area Network|Large geographical areas; the internet is a major example|

Remember: LAN generally covers a smaller area than MAN, and MAN generally covers a smaller area than WAN. These are useful general distinctions, not strict distance limits.

### E. Network topologies

Topology describes how network devices are arranged physically or logically.

![How WAN Connects Your Business to Success](https://images.openai.com/static-rsc-4/OwHZ71S-MU-pGjdb3D-KkLhRfFykgcNxPYNpLc4VyRljJ1l2N-uHGfnT6kHH4LYD-MgygQFvIJ_gfmEYHGQDhkTRRBoa3FcGaF4nlGIbPvH7ILmj7nADoKNbKxs7NpaEbcmwdZkUe1DQf-e12t_4bfhPQ2dLe77IgWCMycf1F3w?purpose=inline)

Add to Favorites

1. Point-to-Point

A direct connection between two devices.

- Simple and easy to understand.
    
- Common in direct communication links.
    

![Network Topologies - Computer Network](https://images.openai.com/static-rsc-4/iMw6hrXDa1xdazgf79P3JAYW7WRrSe1dtjDSbyrce22TMlPkiQZaEAkoPBzqaU1RZ0SR-DwRN1htxo73rv06IsDMa9MUavvZlgbqly-t57Odf2U32KFryNRO-XIDQwTrNudO5gSS8J5d87vm-BELaIETcZe-i8TEFu9xr8QV6I4?purpose=inline)

Add to Favorites

2. Bus

All devices share a common backbone cable.

- Simple and inexpensive in older networks.
    
- A backbone failure can disrupt the network.
    
- Troubleshooting and scaling can be difficult.
    

![Desain Jaringan - Topologi Ring | WarnetBiz](https://images.openai.com/static-rsc-4/gxIWYTIXTpjOSqoHjcoYjRiqBLwSyddwnT0yE2waEWVFS7gKVHF-EGi-ePpZJWuiKxpqOCm13QPAWFIQ5k_5vFeFjFwYj8O83_T1sZqa9q3OI6Adz8CDPKnN9j3jJsRifnOPILKvZt4fhjFvl8Hh5Dz75OU0rHokJJ5Q7pmq8v8?purpose=inline)

Add to Favorites

3. Ring

Each device connects to neighboring devices in a closed loop.

- Data follows a defined path around the ring.
    
- A single failure can disrupt a simple ring without redundancy or bypass mechanisms.
    

![Introducing LAN Topologies](https://images.openai.com/static-rsc-4/j4RuLCMQM7WWyYu7UvR7CEXvXy7U5sGucafsAhgKps9fnKl57slmta2-7buUZlCIUwE2kPOor_nbPuhe6gIMDyg37bU_KUMXJWmTBdkrMpjEgyU3HwBY_JlgdBj9S-9MMPHOZK5BdMAJyY9hAWskuE0vHrmtf7cQlRPa-z8lNak?purpose=inline)

Add to Favorites

4. Star

Every device connects to a central switch or hub.

- Easy to manage and expand.
    
- A single endpoint cable failure usually affects only that endpoint.
    
- Failure of the central device can disrupt the connected network.
    

![Mesh Networking: Cover your home with Wi-Fi in every corner | HardwareZone Singapore](https://images.openai.com/static-rsc-4/wUdxKd10YyoNiWTfCiA9nKQyRAfiaIsEYUXCMxfPO_0LaGbK5yjBAqx__qgmyPCqTIp4h1sEOHQpdCqgcywC7re0RfZS5nIEQiqMok7Gleipd7xvNgmItkN7oshFen3BulgmOEZk78GXN8C0uvxxiRihTwtbGhcfjX3Svpuc2tg?purpose=inline)

Add to Favorites

5. Mesh

Devices have multiple interconnections or alternative paths.

- Can provide high reliability and redundancy.
    
- More expensive and complex to deploy.
    

### F. Network administration types

|Feature|Client–Server|Peer-to-Peer (P2P)|
|---|---|---|
|Structure|Central server provides services|Devices share resources directly|
|Management|Centralized|Decentralized|
|Security|Easier to enforce central policies|Depends on individual devices and configuration|
|Cost|May require dedicated server infrastructure|Often cheaper for small setups|
|Best suited for|Businesses, universities, large organizations|Small groups and simple file sharing|
|Main drawback|Server failure may disrupt dependent services|Management and security become harder as the network grows|

Remember: Client–server does not mean the server must perform every task; it means clients request services from servers. In P2P, a device can act as both a client and a provider of resources.

## 2. Common interview questions and answers

These are the most important questions to practice for a beginner networking interview.

1

What is a computer network?

Suggested answer

A computer network is a group of interconnected devices that communicate and share data, services, or resources.

2

What are the main types of transmission media?

Suggested answer

Guided media, such as twisted-pair, coaxial, and fiber-optic cables; and unguided media, such as radio waves, microwaves, and satellite links.

3

What is the difference between UTP and STP?

Suggested answer

UTP has no additional shielding around the pairs. STP includes shielding to reduce electromagnetic interference, depending on its construction and installation.

4

Which cable is best for long-distance, high-speed communication?

Suggested answer

Fiber-optic cable is often preferred because it supports high bandwidth, long distances, and immunity to electromagnetic interference.

5

What is the difference between a hub and a switch?

Suggested answer

A hub repeats incoming signals to other ports at Layer 1. A switch forwards Ethernet frames based on MAC addresses, primarily at Layer 2.

6

What is the difference between a switch and a router?

Suggested answer

A switch primarily connects devices within a LAN using MAC addresses. A router forwards IP packets between networks using IP addresses.

7

What is a NIC?

Suggested answer

A Network Interface Card or controller provides a device with a network interface, such as Ethernet or Wi-Fi.

8

What is an access point?

Suggested answer

An access point allows wireless clients to connect to a network, commonly bridging Wi-Fi traffic to a wired LAN.

9

Explain simplex, half-duplex, and full-duplex.

Suggested answer

Simplex allows one-way communication; half-duplex allows both directions but one at a time; full-duplex allows simultaneous communication in both directions.

10

What is the difference between LAN and WAN?

Suggested answer

A LAN connects devices over a relatively limited area, while a WAN connects networks over larger geographical distances.

11

What is network topology?

Suggested answer

Network topology is the physical or logical arrangement of network devices and their connections.

12

Name five network topologies.

Suggested answer

Point-to-point, bus, ring, star, and mesh.

13

What happens if the central switch fails in a star topology?

Suggested answer

Devices relying on that switch may lose connectivity through it, although other independent network paths may continue working.

14

What is the main advantage of mesh topology?

Suggested answer

Multiple paths can provide redundancy and improve resilience if a link or device fails.

15

What is the difference between client–server and peer-to-peer?

Suggested answer

Client–server uses servers to provide services to clients. Peer-to-peer allows devices to share resources directly without requiring a central server for every exchange.

16

What is electromagnetic interference (EMI)?

Suggested answer

EMI is unwanted electromagnetic energy that can disrupt signals in communication systems. Shielding, suitable cable selection, and correct installation can help reduce its effects.

17

Why is fiber-optic cable resistant to EMI?

Suggested answer

It transmits information using light rather than electrical signals in a copper conductor, so external electromagnetic interference does not affect the optical signal in the same way.

18

What is the difference between physical and logical topology?

Suggested answer

Physical topology describes the actual device and cable arrangement. Logical topology describes how data flows through the network.

Hide all answers

## 3. Practical scenario questions

Q1. Your computer is connected to a network, but there is no internet access. What would you check?

Suggested answer:

1. Check the Ethernet cable or Wi-Fi connection.
    
2. Check the NIC and link status.
    
3. Verify the IP address, subnet mask, default gateway, and DNS configuration.
    
4. Test connectivity to the gateway and an external IP address.
    
5. Check DNS resolution, router status, and possible firewall restrictions.
    

Q2. Several computers lose connectivity at the same time. What could be the cause?

Possible causes include a failed switch, an uplink problem, a power failure, or an issue with shared network configuration. In a star topology, check the central switch and its uplinks first.

Q3. Which transmission medium would you choose for connecting two distant buildings?

Fiber-optic cable is often a strong choice because it supports long distances, high bandwidth, and electrical isolation between endpoints. The final choice depends on distance, cost, installation requirements, and network design.

Q4. Which topology would you choose for a modern computer lab?

A star topology using a central Ethernet switch is common because it is easy to manage, expand, and troubleshoot.

Q5. A company needs centralized user accounts, security policies, and shared files. Which network administration model is more suitable?

Client–server, because centralized services and administration make it easier to manage users, permissions, and shared resources.

## 4. Quick self-test

1. Which device primarily forwards frames using MAC addresses?
    

Hub

Switch

Router

Repeater

Correct!

2. Which transmission mode supports sending and receiving simultaneously?
    

Simplex

Half-duplex

Full-duplex

Broadcast

Correct!

3. Which medium transmits data using light?
    

Coaxial cable

UTP cable

Fiber-optic cable

Radio cable

Correct!

4. Which topology uses a central connecting device?
    

Bus

Ring

Star

Point-to-point

Correct!

5. Which model is typically easier to manage centrally?
    

Peer-to-peer

Client–server

Bus topology

Simplex

Correct!

6. What does NIC stand for?
    

Network Internet Cable

Network Interface Card

Node Internal Connection

Network Information Center

Correct!

7. Which is an example of unguided media?
    

Twisted pair

Coaxial cable

Fiber optic

Radio waves

Correct!

Score: 7/7

Try again

## 5. Last-minute revision sheet

Memorize these before your interview:

- Transmission media: Twisted pair, coaxial, fiber optic, and wireless.
    
- Networking devices: NIC connects a device; hub repeats signals; switch forwards frames; router connects networks; access point provides Wi-Fi access.
    
- Transmission modes: Simplex = one-way; half-duplex = two-way, one at a time; full-duplex = two-way simultaneously.
    
- Network categories: PAN, LAN, MAN, WAN.
    
- Topologies: Point-to-point, bus, ring, star, mesh.
    
- Administration types: Client–server and peer-to-peer.
    
- Key distinction: MAC addresses are used for local Ethernet frame forwarding; IP addresses support routing between networks.
    

Interview answers are strongest when you give a clear definition, explain the main function, and add one practical example.