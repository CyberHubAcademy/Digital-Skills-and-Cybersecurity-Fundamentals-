# Week 3: Network and Broadcast Addresses
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Define network and broadcast addresses.
- Calculate the network number for a given IP.
- Calculate the broadcast address for a given IP.
- Understand why these addresses cannot be assigned to devices.
- Apply formulas to determine usable host ranges.

---

## 📘 Network Address
- Ends with **binary 0s** in all host bits.  
- Also known as the **wire address**.  
- **Never used** as a device IP address.  
- Used by routers to forward data.  

### Example
- IP: `152.21.2.3` (Class B).  
- First two octets = network number.  
- Last two octets = host numbers.  
- **Network address**: `152.21.0.0`.

---

## 📘 Broadcast Address
- Ends with **binary 1s** in all host bits.  
- Used to send data to **all devices** on a network.  
- **Never used** as a device IP address.  

### Example
- IP: `152.21.2.3` (Class B).  
- First two octets = network number.  
- Last two octets = host numbers.  
- **Broadcast address**: `152.21.255.255`.

---

## 📑 Key Rule
- **All 0s in host bits** = Network Address.  
- **All 1s in host bits** = Broadcast Address.  
- These two addresses are **reserved** and cannot be assigned to hosts.  
- Usable host addresses = **Total addresses – 2** (subtract network & broadcast).  

---

## 🧪 Practical Exercise
Students should:
1. Find the **network address** for:  
   - `194.78.112.6` → `194.78.112.0`  
   - `117.23.8.3` → `117.0.0.0`  
   - `156.132.64.12` → `156.132.0.0`  
   - `208.150.112.16` → `208.150.112.0`  
   - `91.118.125.2` → `91.0.0.0`  

2. Find the **broadcast address** for:  
   - `194.78.112.6` → `194.78.112.255`  
   - `117.23.8.3` → `117.255.255.255`  
   - `156.132.64.12` → `156.132.255.255`  
   - `208.150.112.16` → `208.150.112.255`  
   - `91.118.125.2` → `91.255.255.255`  

3. Calculate the number of **usable hosts** for each network.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- Calculation of network addresses.  
- Calculation of broadcast addresses.  
- Host count calculations.  
- Verification using `ipcalc` or manual binary conversion.  

Save in:  
Week3_Networking_Fundamentals/Assignments/Network_Broadcast_Practice.md
