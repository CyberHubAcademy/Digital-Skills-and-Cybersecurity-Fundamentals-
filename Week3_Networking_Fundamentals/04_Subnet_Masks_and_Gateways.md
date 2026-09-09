# Week 3: Subnet Masks and Gateways
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Define a subnet mask and its purpose.
- Identify default subnet masks for Class A, B, and C networks.
- Convert subnet masks into slash notation (/8, /16, /24).
- Understand the role of a default gateway in networking.
- Apply subnet mask calculations to determine usable host ranges.

---

## 📘 Subnet Mask
- Formal name: **Extended Network Prefix**.  
- Tells devices which part of an IP address is the **network field** and which part is the **host field**.  
- Always **32 bits long** (4 octets), just like an IP address.  

### Steps to Determine Subnet Mask
1. Express the IP address in binary.  
2. Replace the network portion with all **1s**.  
3. Replace the host portion with all **0s**.  
4. Convert back to dotted-decimal notation.  

---

## 📑 Default Subnet Masks
| Class   | Formula   | Slash Notation | Default Mask     |
|---------|-----------|----------------|------------------|
| Class A | N.H.H.H   | /8             | 255.0.0.0        |
| Class B | N.N.H.H   | /16            | 255.255.0.0      |
| Class C | N.N.N.H   | /24            | 255.255.255.0    |

### Examples
- IP: `117.23.8.3` → Class A → Mask = `255.0.0.0` (/8).  
- IP: `156.132.64.12` → Class B → Mask = `255.255.0.0` (/16).  
- IP: `194.78.112.6` → Class C → Mask = `255.255.255.0` (/24).  

---

## 📘 Default Gateway
- A **port on a router** that connects a local network to external networks.  
- Acts as the **exit point** for traffic destined outside the local subnet.  
- Must be part of the same network as the host.  
- Typically the **first or last usable IP address** in the subnet.  

### Example
- Network: `192.168.1.0/24`.  
- Usable range: `192.168.1.1 – 192.168.1.254`.  
- Default gateway: `192.168.1.1` or `192.168.1.254`.  

---

## 🧪 Practical Exercise
Students should:
1. Identify the default subnet mask for the following IPs:  
   - `117.23.8.3`  
   - `156.132.64.12`  
   - `194.78.112.6`  
2. Convert each subnet mask into slash notation.  
3. Determine the usable host range for each network.  
4. Assign a default gateway for each network.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- Identification of default subnet masks.  
- Conversion into slash notation.  
- Calculation of usable host ranges.  
- Assignment of default gateways.  

Save in:  
Week3_Networking_Fundamentals/Assignments/Subnet_Gateway_Practice.md
