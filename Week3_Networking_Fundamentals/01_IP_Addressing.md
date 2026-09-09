# Week 3: IP Addressing
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION  & IRIAD

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Understand addressing schemes (flat vs hierarchical).
- Explain the concept of an IP address and its role in networking.
- Differentiate between static and dynamic IP addressing.
- Recognize the role of IANA and regional registries.
- Identify the components required for an IP to be routable.

---

## 📘 Addressing Schemes
### Flat Addressing
- Used in **intranetworks** (Layer 2).  
- Examples: **MAC addresses**.  
- Assigned statically, often sequentially or randomly.  
- Analogy: Social Security Number, your name.  
- Example: `C0:AD:00:23:4F:89`.

### Hierarchical Addressing
- Used in **internetworks** (Layer 3).  
- Examples: **IP addresses**.  
- Assigned dynamically based on location.  
- Analogy: Phone system, ZIP code.  
- Example: `182.157.63.219`.

---

## 📑 Internet Protocol Address (IP Address)
- A unique numerical label assigned to each device on a network.  
- Every device on the Internet must have a unique IP address.  

### IANA (Internet Assigned Numbers Authority)
- Manages global IP address allocations.  
- Delegates blocks to **Regional Internet Registries (RIRs)**.  
- RIRs allocate addresses to ISPs and organizations.  

### Requirements for a Routable IP
- **IP address**  
- **Subnet mask**  
- **Default gateway**  
- **DNS address** (for domain name resolution)

---

## 📦 Types of Addressing
### Static IP Address
- Manually assigned by an administrator.  
- Constant and does not change.  
- Useful for servers and devices requiring fixed addresses.  

### Dynamic IP Address
- Assigned automatically each time a device connects.  
- Uses **DHCP (Dynamic Host Configuration Protocol)**.  
- Requires less human intervention.  
- Enabled by default on most systems.  

---

## 🧪 Practical Exercise
# Windows
ipconfig   
# Linux/macOS
ifconfig   
2. Determine whether their IP is static or dynamic.  
3. Configure a static IP on their system.  
4. Verify connectivity using `ping www.google.com`.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- Identification of your current IP address.  
- Explanation of whether it is static or dynamic.  
- Configuration of a static IP address.  
- Verification of connectivity.  

Save in:  
Week3_Networking_Fundamentals/Assignments/IP_Addressing_Practice.md
Students should:
1. Identify their current IP address using:  
