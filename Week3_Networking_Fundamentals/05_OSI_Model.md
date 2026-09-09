# Week 3: The OSI Model
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Identify and explain the seven OSI layers.
- Describe what happens to data at each layer.
- Recognize common protocols and devices associated with each layer.
- Explain encapsulation and decapsulation.
- Apply the OSI model to real-world networking scenarios.
- Use the OSI model as a framework for troubleshooting.

---

## 📘 Introduction
The **OSI (Open Systems Interconnection) Model** is a conceptual framework that divides network communication into **seven logical layers**. Each layer has specific responsibilities and interacts with the layers above and below it.

### The Seven Layers
1. **Physical** → Transmission of raw bits (signals, cables, connectors).  
2. **Data Link** → Local delivery, MAC addressing, framing, error detection.  
3. **Network** → Logical addressing, routing, packet forwarding.  
4. **Transport** → End-to-end delivery, TCP/UDP, port numbers.  
5. **Session** → Establishing, managing, and terminating communication sessions.  
6. **Presentation** → Data formatting, encoding, encryption, compression.  
7. **Application** → Network services used by applications (HTTP, DNS, SMTP, FTP).  

---

## 📑 Mnemonics
- **Top to Bottom**: *All People Seem To Need Data Processing*.  
- **Bottom to Top**: *Please Do Not Throw Sausage Pizza Away*.  

---

## 📘 Real-Life Analogy
Think of sending a parcel from Nguru to Lagos:
- **Application** → What are you sending?  
- **Presentation** → How is it packaged/labeled?  
- **Session** → Managing the delivery transaction.  
- **Transport** → Ensuring the delivery process.  
- **Network** → Determining the destination route.  
- **Data Link** → Local delivery between nearby points.  
- **Physical** → Road/vehicle carrying the parcel.  

---

## 📑 Layer Responsibilities
| Layer        | Responsibility                          | Example Device/Protocol |
|--------------|------------------------------------------|--------------------------|
| Application  | Network services for apps                | HTTP, DNS, SMTP          |
| Presentation | Data representation, encryption          | SSL/TLS, JPEG, ASCII     |
| Session      | Manage communication sessions            | APIs, NetBIOS            |
| Transport    | End-to-end delivery, ports               | TCP, UDP                 |
| Network      | Logical addressing, routing              | IP, Routers              |
| Data Link    | Local delivery, MAC addressing           | Switches, Ethernet       |
| Physical     | Transmission of bits                     | Cables, Hubs, Wi-Fi      |

---

## 🧪 Practical Exercise
Students should:
1. Map each OSI layer to a real-world example (e.g., cables, routers, browsers).  
2. Identify which layer handles:  
   - IP addressing.  
   - Port numbers.  
   - Encryption.  
   - MAC addresses.  
3. Use Wireshark to capture traffic and identify information at different layers.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- Explanation of each OSI layer.  
- Real-life analogies for each layer.  
- Identification of devices/protocols at each layer.  
- Wireshark screenshots showing encapsulation at different layers.  

Save in:  
Week3_Networking_Fundamentals/Assignments/OSI_Model_Practice.md
