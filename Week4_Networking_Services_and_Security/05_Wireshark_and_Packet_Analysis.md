# Week 4: Wireshark and Packet Analysis
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD 

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Install and use Wireshark for packet capture.
- Understand the structure of packets at different OSI layers.
- Identify protocols such as Ethernet, IP, TCP/UDP, DNS, and HTTP.
- Apply packet analysis to troubleshoot network issues.
- Recognize how packet analysis connects to cybersecurity.

---

## 📘 What is Wireshark?
- **Wireshark** is a free, open-source tool for capturing and analyzing network traffic.  
- It allows students to see what is happening “on the wire” in real time.  
- Provides visibility into protocols, headers, and payloads.  

---

## 📑 Packet Structure
Packets contain information from multiple OSI layers:
- **Ethernet Frame (Layer 2)** → Source & destination MAC addresses.  
- **IP Packet (Layer 3)** → Source & destination IP addresses.  
- **TCP/UDP Segment (Layer 4)** → Port numbers, sequence numbers.  
- **Application Data (Layer 7)** → HTTP requests, DNS queries, etc.  

---

## 📘 Using Wireshark
### Installation
- Download from: [https://www.wireshark.org](https://www.wireshark.org).  
- Available for Windows, Linux, and macOS.  

### Capturing Traffic
1. Open Wireshark.  
2. Select a network interface (e.g., Wi-Fi, Ethernet).  
3. Start capture.  
4. Stop capture after a few seconds.  

### Filtering Traffic
- Use filters to focus on specific protocols:  
  - `ip.addr == 8.8.8.8` → Show traffic to Google DNS.  
  - `tcp.port == 80` → Show HTTP traffic.  
  - `dns` → Show DNS queries.  

---

## 📘 Cybersecurity Connection
- Packet analysis helps detect:  
  - **Suspicious traffic** (e.g., unknown IPs).  
  - **Malware communication**.  
  - **Phishing attempts**.  
- Security analysts use Wireshark to investigate breaches and monitor networks.  

---

## 🧪 Practical Exercise
Students should:
1. Install Wireshark on their system.  
2. Capture traffic while browsing `www.google.com`.  
3. Apply filters to view:  
   - DNS queries.  
   - HTTP requests.  
   - TCP connections.  
4. Identify source/destination IP addresses.  
5. Document findings with screenshots.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- Installation and setup of Wireshark.  
- Packet capture during a browsing session.  
- Use of filters to isolate DNS, HTTP, and TCP traffic.  
- Explanation of packet structure at different OSI layers.  

Save in:  

Week4_Networking_Services_and_Security/Assignments/Wireshark_Packet_Analysis_Practice.md
