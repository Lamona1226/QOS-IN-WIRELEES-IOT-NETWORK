# Packet Analysis with Wireshark & Network Simulation with OMNeT++

this repository documents my work on network packet analysis using Wireshark and network simulation using OMNeT++. The goal was to inspect various protocols (DNS, IP, TCP, HTTP, and UDP) and analyze real network traffic while also leveraging OMNeT++ for controlled network scenario simulations.
🔍 Objective

    Capture and analyze real network traffic using Wireshark
    Identify and extract key details from DNS, IP, TCP, HTTP, and UDP packets
    Simulate network behavior using OMNeT++ for deeper insights into packet flow and network performance

📌 Captured Protocols with Wireshark
1️⃣ IP (Internet Protocol)

    Source & destination IP addresses
    Packet size & fragmentation details

2️⃣ TCP (Transmission Control Protocol)

    3-way handshake (SYN, SYN-ACK, ACK)
    Sequence & acknowledgment numbers
    Flags like RST, FIN, PSH

3️⃣ UDP (User Datagram Protocol)

    Connectionless data transfer
    Port numbers & payload size

4️⃣ DNS (Domain Name System)

    Query & response analysis
    IP resolution from domain names

5️⃣ HTTP (HyperText Transfer Protocol)

    Request & response headers
    GET and POST requests

🛠 Packet Capture with Wireshark

    Open Wireshark
    Select the appropriate network interface
    Start capturing traffic
    Use filters like:
        ip → Capture all IP packets
        tcp → Capture TCP packets
        udp → Capture UDP packets
        dns → Capture DNS queries and responses
        http → Capture HTTP traffic
    Analyze packet details in the Packet Details & Packet Bytes pane

🚀 Why OMNeT++ for Network Simulation?

I chose OMNeT++ due to its powerful capabilities in modeling and simulating network scenarios. Some key benefits include:

    Modular Design: Helps in designing complex network simulations efficiently
    Seamless Integration with INET Framework: Provides ready-to-use models for TCP/IP, routing, and wireless networks
    Custom Scenario Creation: Allows detailed network behavior simulation, such as congestion, delays, and protocol interactions
    Scalability: Suitable for small-scale and large-scale network modeling

🛠 Network Simulation with OMNeT++

    Install OMNeT++ and INET Framework
    Set up network topology (nodes, routers, links)
    Define simulation parameters (bandwidth, delay, packet size)
    Run simulation and analyze results
    Compare with real-world Wireshark captures

📊 Findings & Insights

    Real-world packet analysis (Wireshark) vs. controlled simulation (OMNeT++)
    Network delays, packet loss, and protocol behavior comparison
    Performance analysis of TCP vs. UDP in different scenarios


    
# Documentation 
[xc.pdf](https://github.com/user-attachments/files/18596952/xc.pdf)
