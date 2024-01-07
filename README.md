# NetPractice (42 - lvl 4)

## 1. Overview

This is a genral exercise to learn the magic of networking.

## 2. Networking basics

### 2.1 What is an IP address?

An IP address is like a unique identifier for a device on a computer network. Just like your home address helps mail get to the right place, an IP address helps data find its way to the correct device on the internet or a local network.

IP stands for "Internet Protocol," and an IP address is a series of numbers separated by dots (like 192.168.1.1). Every device connected to a network, such as your computer, smartphone, or router, has its own unique IP address. This address allows devices to communicate with each other by sending and receiving data.

Think of it as a way for devices to know where to send and receive information in the vast network of connected devices we call the internet.

### 2.2 What is IPv4?

IPv4, or Internet Protocol version 4, is a specific version of the Internet Protocol that is used to assign unique numerical addresses to devices on a network. In simpler terms:

1. **Numerical Identifiers:** IPv4 uses a 32-bit numerical address, expressed as a series of four groups of numbers separated by dots (for example, 192.168.1.1).

2. **Limited Number of Addresses:** The 32-bit address space allows for approximately 4.3 billion unique addresses. 

3. **Format:** Each of the four groups in an IPv4 address can range from 0 to 255. For example, in the address 192.168.1.1, "192" is in the first group, "168" is in the second, "1" is in the third, and "1" is in the fourth.

4. **Binary Representation:** Internally, IPv4 addresses are represented in binary. The conversion to dotted-decimal format (using decimal numbers and dots) makes it easier for people to read and work with.

5. **Address Classes:** IPv4 addresses are divided into classes (A, B, C, D, and E) for various purposes. Classes A, B, and C are commonly used for assigning addresses to devices on networks, while D and E have specialized uses.

### 2.3 What is subneting?

Subnetting is a technique used in computer networking to divide and allocate a single, large network into smaller, more manageable sub-networks or subnets. This process offers several benefits, including efficient use of IP addresses, improved network performance, and enhanced security. Here's a simple explanation:

1. **Efficient Resource Allocation:** Subnetting allows network administrators to break down a large network into smaller, more manageable sections. This is especially useful when the original network has more IP addresses than are needed for each department or group of devices.

2. **Reduced Broadcast Domain:** In a subnetted network, the number of devices that receive and process broadcast messages is limited to the devices within the same subnet. This helps reduce network congestion and improves overall efficiency.

3. **Enhanced Security:** Subnets can act as security boundaries. Devices within the same subnet can communicate more easily with each other, while communication between devices in different subnets may be restricted or filtered. This helps in isolating and securing different parts of a network.

4. **IP Address Conservation:** Subnetting allows for more efficient use of IP addresses. Instead of assigning a unique network address to each department or group, smaller subnets can share a common network address, saving IP address space.

5. **Routing Flexibility:** Subnets enable the use of routers to manage traffic between different subnets. Routers can be configured to control the flow of data between subnets, providing a more organized and controlled network environment.

6. **Organizational Structure:** Subnetting aligns well with the organizational structure of a company or institution. Different departments or floors can be assigned to different subnets, making it easier to manage and troubleshoot network issues.

To implement subnetting, administrators divide the original network into subnets by borrowing bits from the host portion of the IP address. This process involves creating a subnet mask, which is used to distinguish between the network and host portions of an IP address. Subnet masks help devices on the network determine which devices are part of the same subnet and which devices are in different subnets.

### Router and Switch

Routers and switches are both devices used in computer networks, but they serve different purposes.

**Router:**
A router is a networking device that connects different networks together. Its primary function is to forward data packets between computer networks. Routers operate at the network layer (Layer 3) of the OSI (Open Systems Interconnection) model.

**Switch:**
A switch, on the other hand, operates at the data link layer (Layer 2) of the OSI model. It is a device that connects devices within the same local network. 

## 3. The Exercise

This project consists of 10 levels of different situations of subnetting. Here is an example:

![Screenshot 2024-01-07 at 11 40 09](https://github.com/inesalves44/NetPractice/assets/105734074/15300f4b-2d92-41b6-93c6-cc1cfe50ac82)

The objective is to give the correct addresses to each of the components.

## 4.Links
[What is Subnetting Playlist](https://www.youtube.com/watch?v=BWZ-MHIhqjM&list=PLIFyRwBY_4bQUE4IB5c4VPRyDoLgOdExE)
[You suck at subnetting Playlist](https://www.youtube.com/watch?v=5WfiTHiU4x8&list=PLIhvC56v63IKrRHh3gvZZBAGvsvOhwrRF)
