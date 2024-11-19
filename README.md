# NetworkPackekAnalyser_PRODIGY_CS_05

# Network Packet Analyser

This is a simple packet sniffer tool developed in Python using the **scapy** library. The tool captures and analyzes network packets in real time, displaying information such as source and destination IP addresses, protocols, and payload data.

### Features:
- Captures network packets and displays information including:
  - **Source IP**: The IP address of the packet sender.
  - **Destination IP**: The IP address of the packet recipient.
  - **Protocol**: The protocol used (e.g., TCP, UDP, ICMP).
  - **Payload**: Displays the payload data of the packet.
- The tool works with **Layer 3 (IP level)** packet sniffing.
  
### Requirements:

- Python 3.x: Ensure Python 3 is installed on your system.
- scapy: A Python library used to capture and manipulate network packets.
  
  Install it via `pip`:
  pip install scapy

  Npcap (Windows only):
   This is required for packet sniffing on Windows machines.

Run the Packet Sniffer: After setting up, run the Python script:

python NetworkPacketAnalyser.py
