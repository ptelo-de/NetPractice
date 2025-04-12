# NetPractice
 Discovering the basics of networking.
 
 Layers of data transfer through a network.
 
![image](https://github.com/user-attachments/assets/f13375ba-4f6f-4339-bbbe-abeb93b72f7e)

# TCP
Transmission Control Protocol (or TCP) is a communication standard protocol that enables nodes to communicate with each other. TCP is responsible for "breaking" data into small pieces (or *packets*), sending them over the network, and then *"rebuilding"* them all back again while ensuring no data is lost in the process.

How does it know where to send those pieces? It does so by utilizing an Internet Protocol Address (or IP address), a series of numbers used to identify any device connected to a network, either public or private.

TCP and IP are not the same thing, but rather two separate protocols that work together in order to ensure data transfer between different devices.

There are two different versions of IP Addresses: IPv4 and IPv6. For this project, we will only need to know about IPv4, the oldest and most broadly used protocol model. From now on, in this guide, we will use the terms IP and IPv4 interchangeably.

# IPv4
An IPv4 address is a 32-bit number divided into four *8-bit blocks*.

Each of these blocks ranges from 0 to 255 or, in binary, 00000000 to 11111111.

It is fundamental to learn how to visualize each IP Address in its binary form. The reason for it is the fact that every IP Address can be split into two separate pieces of information: the *Network* and the *Host* address.



