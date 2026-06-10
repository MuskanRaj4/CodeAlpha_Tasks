##**Basic Network Sniffer**

## **Project Overview**
This project is a **Python-based Network Sniffer** that captures network packets and displays **Source IP**, **Destination IP**, and **Protocol** information.

## **Objective**
The objective of this project is to understand **Network Traffic Analysis** and **Packet Capturing** using **Python** and **Scapy**.

## **Tools Used**
- **Python**
- **Scapy**
- **Npcap**
- **VS Code**

## **Features**
- **Capture Network Packets**
- **Display Source IP Address**
- **Display Destination IP Address**
- **Display Protocol Information**
- **Real-Time Packet Monitoring**

## **How to Run**

### **Step 1: Install Scapy**
```bash
pip install scapy
```

from scapy.all import *

def packet_callback(packet):
    if packet.haslayer(IP):
        print("\n----- Packet Captured -----")
        print("Source IP:", packet[IP].src)
        print("Destination IP:", packet[IP].dst)
        print("Protocol:", packet[IP].proto)

sniff(prn=packet_callback, store=False)


### **Step 2: Run the Program**
```bash
py network_sniffer.py
```

## **Sample Output**
```text
----- Packet Captured -----
Source IP: 10.86.222.168
Destination IP: 48.218.104.163
Protocol:6
```

## **Conclusion**
This project helped me learn **Packet Sniffing**, **Network Monitoring**, and **Protocol Analysis** using Python.

## **Author**
**Muskan Raj**

