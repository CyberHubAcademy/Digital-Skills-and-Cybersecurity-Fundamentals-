# Week 4: VPNs and Tunneling
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Explain the concept of Virtual Private Networks (VPNs).
- Understand tunneling and encryption in secure communication.
- Identify common VPN protocols (IPSec, SSL, PPTP, L2TP).
- Recognize the role of VPNs in cybersecurity and remote work.
- Configure and test a basic VPN connection.

---

## 📘 What is a VPN?
- A **Virtual Private Network (VPN)** creates a secure, encrypted connection over an untrusted network (e.g., the Internet).  
- It allows users to access private resources remotely as if they were physically connected to the internal network.  
- VPNs protect data confidentiality and integrity during transmission.  

---

## 📑 Tunneling
- **Tunneling** is the process of encapsulating one type of network traffic inside another.  
- Provides secure passage for data across untrusted networks.  
- Often combined with encryption for confidentiality.  

### Example
- A company employee connects from home to the office network.  
- Their traffic is encapsulated inside a secure tunnel and encrypted.  
- Outsiders cannot read or tamper with the communication.  

---

## 📘 Common VPN Protocols
| Protocol | Description | Use Case |
|----------|-------------|----------|
| **PPTP** | Point-to-Point Tunneling Protocol, older, less secure | Legacy systems |
| **L2TP/IPSec** | Layer 2 Tunneling Protocol with IPSec encryption | Secure corporate VPNs |
| **SSL/TLS VPN** | Uses HTTPS for tunneling, works in browsers | Remote access via web |
| **OpenVPN** | Open-source, highly secure, flexible | Widely used in enterprises |
| **WireGuard** | Modern, lightweight, fast | Emerging VPN standard |

---

## 📘 Cybersecurity Connection
- VPNs protect against:  
  - **Eavesdropping** on public Wi-Fi.  
  - **Man-in-the-middle attacks**.  
  - **Data theft** during transmission.  
- VPNs also enable:  
  - Secure remote work.  
  - Access to restricted resources.  
  - Bypassing censorship or geo-blocks.  

---

## 🧪 Practical Exercise
Students should:
1. Install a VPN client (e.g., OpenVPN).  
2. Connect to a test VPN server.  
3. Verify the new IP address using:  
curl ifconfig.me
4. Test secure browsing over the VPN.  
5. Document the difference between direct and tunneled traffic.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- VPN client installation.  
- Successful connection to a VPN server.  
- Verification of IP address change.  
- Explanation of tunneling and encryption.  

Save in:  
Week4_Networking_Services_and_Security/Assignments/VPN_Tunneling_Practice.md
