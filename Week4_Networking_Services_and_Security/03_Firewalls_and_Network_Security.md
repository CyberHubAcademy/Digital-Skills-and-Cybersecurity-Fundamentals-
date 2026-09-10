# Week 4: Firewalls and Network Security
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Explain the purpose of firewalls in network security.
- Differentiate between hardware and software firewalls.
- Understand packet filtering, stateful inspection, and application-level gateways.
- Recognize common firewall rules and policies.
- Apply basic firewall configurations for securing a network.

---

## 📘 What is a Firewall?
- A **firewall** is a security system that monitors and controls incoming and outgoing network traffic.  
- It acts as a **barrier** between trusted internal networks and untrusted external networks (e.g., the Internet).  
- Firewalls enforce **security policies** by allowing or blocking traffic based on rules.  

---

## 📑 Types of Firewalls
### Hardware Firewalls
- Physical devices placed between a network and the Internet.  
- Provide high performance and centralized protection.  
- Common in enterprise environments.  

### Software Firewalls
- Installed on individual computers or servers.  
- Provide host-level protection.  
- Examples: Windows Defender Firewall, iptables (Linux).  

---

## 📘 Firewall Techniques
- **Packet Filtering** → Examines headers (IP, port, protocol) and allows/blocks traffic.  
- **Stateful Inspection** → Tracks active connections and ensures packets are part of valid sessions.  
- **Application-Level Gateway (Proxy Firewall)** → Inspects traffic at the application layer (e.g., HTTP, FTP).  
- **Next-Generation Firewalls (NGFW)** → Combine traditional firewall functions with intrusion prevention, deep packet inspection, and threat intelligence.  

---

## 📑 Common Firewall Rules
- Allow traffic on **port 80 (HTTP)** and **443 (HTTPS)** for web browsing.  
- Block traffic on unused or suspicious ports.  
- Restrict access to internal services from external networks.  
- Example (Linux `iptables`):  
YES
Here’s the complete content for 06_Encapsulation_and_Decapsulation.md in the same continuous, professional style as your Week Three repository. This file explains how data flows through the OSI layers during communication:

Code
# Week 3: Encapsulation and Decapsulation
ALGURAWY CYBERHUB ACADEMY  
Sponsored by DR. BUKAR USMAN FOUNDATION  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Define encapsulation and decapsulation in networking.
- Explain how data moves through the OSI layers.
- Identify the data units at each layer (bits, frames, packets, segments).
- Trace communication from sender to receiver.
- Connect encapsulation concepts to cybersecurity.

---

## 📘 Encapsulation
Encapsulation is the process of **adding protocol information** as data moves **down the OSI layers** from the sender.

### Process
1. **Application Layer** → Data is created (e.g., a message, web request).  
2. **Transport Layer** → Adds transport information (TCP/UDP headers, port numbers).  
3. **Network Layer** → Adds IP addressing and routing information.  
4. **Data Link Layer** → Adds MAC addressing and frame information.  
5. **Physical Layer** → Converts frames into bits/signals for transmission.  

### Data Units
- Application → Data  
- Transport → Segment/Datagram  
- Network → Packet  
- Data Link → Frame  
- Physical → Bits  

---

## 📘 Decapsulation
Decapsulation is the **reverse process** at the receiver. Each layer removes its corresponding header/trailer before passing data upward.

### Process
1. **Physical Layer** → Receives raw signals.  
2. **Data Link Layer** → Converts signals into frames, checks MAC address.  
3. **Network Layer** → Extracts packets, checks IP address.  
4. **Transport Layer** → Extracts segments, checks port numbers.  
5. **Application Layer** → Delivers the original data to the user.  

---

## 📑 Complete Communication Example
### Sending a WhatsApp Message
- **Sender (Umar)**: "Hello, how are you?"  
- Application → Message prepared.  
- Transport → TCP/UDP information added.  
- Network → IP information added.  
- Data Link → Frame information added.  
- Physical → Converted into radio/electrical signals.  

### Receiver
- Signals → Frames → Packets → Transport data → Application.  
- Final Output: "Hello, how are you?" displayed on recipient’s phone.  

---

## 📘 Cybersecurity Connection
Understanding encapsulation is critical for security:
- **Layer 1** → Physical tampering.  
- **Layer 2** → MAC spoofing, rogue devices.  
- **Layer 3** → IP-based attacks, routing abuse.  
- **Layer 4** → Port scanning, transport-level attacks.  
- **Layer 7** → Web attacks, phishing, application exploits.  

👉 A cybersecurity professional must understand how communication works before attempting to secure it.

---

## 🧪 Practical Exercise
Students should:
1. Use Wireshark to capture traffic while browsing a website.  
2. Identify encapsulation at each layer (Ethernet, IP, TCP/UDP, HTTP).  
3. Trace a packet from sender to receiver.  
4. Explain how headers are added and removed.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- Encapsulation of a web request.  
- Decapsulation of the response.  
- Identification of data units at each layer.  
- Wireshark screenshots highlighting headers at different layers.  

Save in:  
Week3_Networking_Fundamentals/Assignments/Encapsulation_Decapsulation_Practice.md
