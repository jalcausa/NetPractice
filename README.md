_This project has been created as part of the 42 curriculum by jalcausa._

# NetPractice

## Description

NetPractice is a 42 School project designed to provide practical training in networking fundamentals through an interactive web-based interface. The project focuses on understanding and configuring TCP/IP networks, requiring students to solve 10 progressive levels of increasing complexity.

The main goal is to gain hands-on experience with network configuration by correctly setting up IP addresses, subnet masks, and routing tables to ensure proper communication between network devices. Each level presents a different network topology challenge that must be solved by configuring the network parameters correctly.

Through this project, students develop a solid understanding of how networks function at the IP layer, including concepts such as IP addressing, subnetting, routing, and the interaction between different network devices.

## Instructions

### How to Run

1. Open the `index.html` file in your web browser
2. The training interface will load automatically
3. Navigate through the 10 levels sequentially by solving each network configuration challenge
4. Each level must be completed successfully before proceeding to the next

### How to Export Configurations

Once you have successfully solved a level:

1. Click the export button provided in the interface
2. The configuration will be automatically downloaded as a JSON file
3. Save each configuration file with a descriptive name (e.g., `level1.json`, `level2.json`, etc.)

### Submission Requirements

For project submission, you must include:

- **10 exported configuration files** (one per level) placed at the root of your Git repository
- Each configuration file should be named appropriately to identify its corresponding level
- All configurations must be valid and demonstrate correct network setup

**Note:** The `run.sh` script is not required for this project as the interface runs directly in the browser.

## Resources

### References

- **Behrouz A. Forouzan** - _Data Communications and Networking_
  - A comprehensive textbook covering fundamental networking concepts, TCP/IP protocol suite, and network architectures
- **University Course Materials** - Redes y Sistemas Distribuidos (Networks and Distributed Systems)
  - Lecture notes and materials from university coursework covering network fundamentals and distributed computing concepts

### Networking Concepts Studied

This project covers the following essential networking concepts:

- **TCP/IP Addressing**: Understanding IPv4 address structure, address classes, and binary-to-decimal conversion
- **Subnet Masks**: Calculating network and host portions, CIDR notation, and subnet boundaries
- **Subnetting**: Dividing networks into smaller subnetworks and calculating usable host ranges
- **Default Gateway**: Configuring gateway addresses for inter-network communication
- **Routing**: Understanding routing tables, next-hop addresses, and packet forwarding
- **Network Devices**:
  - **Routers**: Layer 3 devices that forward packets between different networks
  - **Switches**: Layer 2 devices that forward frames within the same network
- **OSI Model Layers**: Focus on Layer 2 (Data Link) and Layer 3 (Network)
- **Network Topology**: Understanding point-to-point connections, network segments, and device interconnection
- **IP Packet Routing**: Path determination and packet forwarding decisions
- **Network Address Translation (NAT)**: Basic concepts of private vs. public addressing

### AI Usage

**No artificial intelligence tools were used in the completion of this project.** All configurations and solutions were developed through manual study of networking concepts, analysis of network topologies, and application of theoretical knowledge to practical scenarios. The only part of the project where I was helped by AI was in the drafting of this document.

## Project Structure

```
.
├── README.md
├── level1.json
├── level2.json
├── level3.json
├── level4.json
├── level5.json
├── level6.json
├── level7.json
├── level8.json
├── level9.json
└── level10.json
```

## Key Learning Outcomes

- Practical understanding of IPv4 addressing and subnetting
- Ability to calculate network addresses, broadcast addresses, and usable host ranges
- Configuration of routing tables for proper packet forwarding
- Understanding of how routers make forwarding decisions
- Recognition of common network configuration errors and how to troubleshoot them
- Application of binary mathematics to networking problems
