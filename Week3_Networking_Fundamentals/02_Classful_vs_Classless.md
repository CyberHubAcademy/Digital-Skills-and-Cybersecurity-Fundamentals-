# Week 3: Classful vs Classless Addressing
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Differentiate between classful and classless addressing.
- Identify Class A, B, and C IP ranges.
- Understand CIDR (Classless Inter-Domain Routing).
- Apply Variable Length Subnet Masking (VLSM).
- Calculate network and host portions of IP addresses.

---

## 📘 Classful Addressing
- Divides IP addresses into **five classes**: A, B, C, D (multicast), and E (reserved).  
- Each class has a **default subnet mask**.  
- All networks are the same size within a class.  
- Subnet information is not sent.  

### Class A
- Range: **1 – 126** in the first octet.  
- Default mask: `255.0.0.0` (/8).  
- Example: `124.95.44.15`.  
- Reserved: `127.x.x.x` for loopback.  
- Possible hosts: ~16 million per network.  

### Class B
- Range: **128 – 191** in the first octet.  
- Default mask: `255.255.0.0` (/16).  
- Example: `151.10.13.28`.  
- Possible hosts: ~65,000 per network.  

### Class C
- Range: **192 – 223** in the first octet.  
- Default mask: `255.255.255.0` (/24).  
- Example: `201.110.213.28`.  
- Possible hosts: 256 per network.  

---

## 📘 Classless Addressing (CIDR)
- **CIDR = Classless Inter-Domain Routing**.  
- Allows networks of different sizes.  
- Subnet information is included.  
- Supports **VLSM (Variable Length Subnet Masking)**.  
- More efficient use of IP address space.  

### Example
- `192.168.1.0/28` → 16 addresses (14 usable).  
- `192.168.1.0/30` → 4 addresses (2 usable).  

---

## 📑 Network & Host Number Formulas
- **N = Network Number** → assigned by registry (ARIN).  
- **H = Host Number** → assigned by administrator.  

| Class   | Octet Structure | Example Formula |
|---------|-----------------|-----------------|
| Class A | N.H.H.H         | 117.0.0.0       |
| Class B | N.N.H.H         | 156.132.0.0     |
| Class C | N.N.N.H         | 194.78.112.0    |

---

## 🧪 Practical Exercise
Students should:
1. Identify the class of the following IPs:  
   - `117.23.8.3`  
   - `156.132.64.12`  
   - `208.150.112.16`  
   - `91.118.125.2`  
2. Write the default subnet mask for each.  
3. Convert each subnet mask into **slash notation**.  
4. Calculate the number of usable hosts for each network.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- Identification of IP classes.  
- Calculation of default subnet masks.  
- Conversion to slash notation.  
- Host count calculations.  

Save in:  
Week3_Networking_Fundamentals/Assignments/Classful_vs_Classless_Practice.md
