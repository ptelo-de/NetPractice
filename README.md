# NetPractice
 Discovering the basics of networking.
 
 Layers of data transfer through a network.
 
![image](https://github.com/user-attachments/assets/f13375ba-4f6f-4339-bbbe-abeb93b72f7e)

# TCP
Transmission Control Protocol (or TCP) is a communication standard protocol that enables nodes to communicate with each other. TCP is responsible for "breaking" data into small pieces (or *packets*), sending them over the network, and then **"rebuilding"** them all back again while ensuring no data is lost in the process.

How does it know where to send those pieces? It does so by utilizing an Internet Protocol Address (or IP address), a series of numbers used to identify any device connected to a network, either public or private.

TCP and IP are not the same thing, but rather two separate protocols that work together in order to ensure data transfer between different devices.

There are two different versions of IP Addresses: IPv4 and IPv6. For this project, we will only need to know about IPv4, the oldest and most broadly used protocol model. From now on, in this guide, we will use the terms IP and IPv4 interchangeably.

# IPv4
An IPv4 address is a 32-bit number divided into four **8-bit blocks**.

Each of these blocks ranges from 0 to 255 or, in binary, 00000000 to 11111111.

It is fundamental to learn how to visualize each IP Address in its binary form. The reason for it is that every IP Address can be split into two separate pieces of information: the **Network** and the **Host** address.

**Network Address** is the identifier of the network in which the devices are connected. In order to communicate with each other, the nodes must all be in the same network and, therefore, have the same Network Address portion of their respective IPs.

**Host Address** is the individual identifier of the device. Each node in the same network must have a singular, unique Host Address.

In order to identify which part of the full IP Address correspond to the Network and which correspond to the Host, we musk apply to it a **Network Mask** (or **Subnet Mask**).

A Mask is also a 32-bit number divided into four 8-bit blocks. However, its purpose is to identify which bits are actively part of the Network identification. To do so, it marks with 1s the network bits.

There are two ways to represent a mask: by a full **IP Mask** or by **CIDR**.

Let's look at an example:

IP Address:		153.172.250.12
Subnet Mask:	255.255.255.0
CIDR:			/24

In binary, respectively, we have:

IP Address:		10011001.10101100.11111010.00001100
Subnet Mask:	11111111.11111111.11111111.00000000

source: https://github.com/caroldaniel/42sp-cursus-netpractice

