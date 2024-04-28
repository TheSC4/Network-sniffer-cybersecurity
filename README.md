# Network Analyzer

## Overview

This Python script is a network traffic analyzer tool that captures and analyzes network packets in real-time. It provides detailed information about Ethernet frames, IPv4 packets, ICMP packets, TCP segments, and UDP segments.

## Features

- **Ethernet Frame Analysis**: Analyze Ethernet frames including destination MAC address, source MAC address, and protocol.
- **IPv4 Packet Analysis**: Extract information from IPv4 packets such as version, header length, TTL, protocol, source IP address, and destination IP address.
- **ICMP Packet Analysis**: Decode ICMP packets including type, code, and checksum.
- **TCP Segment Analysis**: Interpret TCP segments including source port, destination port, sequence number,        acknowledgement number, and flags (URG, ACK, PSH, RST, SYN, FIN).
- **UDP Segment Analysis**: Parse UDP segments including source port, destination port, and length.
- **Real-time Packet Capture**: Capture network traffic in real-time using a raw socket.
- **Command-Line Interface (CLI)**: Intuitive command-line interface for easy interaction and scripting.

## Installation

 1. ****Clone the Repository**:**

      `git clone https://github.com/C-cube-community/Network-Analyser-Sniffer-Cybersecurity.git` 

 2. ****Install Dependencies**:**

    `pip install -r requirements.txt`

## Usage
 1. ****Make sure to open the terminal in Administrator mode**:**

 2. ****Run the Script**:**

    `python main.py`

## Contributing

We welcome contributions from the community! If you'd like to contribute, please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m 'Add my feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a Pull Request
