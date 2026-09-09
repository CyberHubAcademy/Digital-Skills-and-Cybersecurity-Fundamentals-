# Week 3: Encapsulation and Decapsulation
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

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
