# Week 4: Routing and Switching Basics
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Differentiate between routing and switching.
- Explain how routers and switches operate at different OSI layers.
- Understand static vs dynamic routing.
- Recognize common routing protocols (RIP, OSPF, BGP).
- Apply switching concepts such as MAC tables and VLANs.

---

## 📘 Switching Basics
- Operates at **Layer 2 (Data Link)**.  
- Uses **MAC addresses** to forward frames within a local network.  
- Builds a **MAC address table** to know which port leads to which device.  
- Provides **local delivery** only (within the same LAN).  

### Example
- PC1 → Switch → PC2.  
- Switch checks MAC address of PC2 and forwards the frame to the correct port.  

### VLANs (Virtual LANs)
- Logical segmentation of a switch into multiple networks.  
- Improves security and efficiency.  
- Example: separating staff and student traffic on the same physical switch.  

---

## 📘 Routing Basics
- Operates at **Layer 3 (Network)**.  
- Uses **IP addresses** to forward packets between different networks.  
- Maintains a **routing table** to decide the best path.  
- Provides **internetwork delivery** (LAN → WAN → Internet).  

### Example
- PC1 (192.168.1.10) wants to reach Server (8.8.8.8).  
- Router checks its routing table and forwards the packet toward the destination.  

---

## 📑 Static vs Dynamic Routing
### Static Routing
- Manually configured by administrator.  
- Simple but not scalable.  
- Example:  
ip route add 192.168.2.0/24 via 192.168.1.1


### Dynamic Routing
- Routers exchange information automatically.  
- Adapts to network changes.  
- Common protocols:  
- **RIP (Routing Information Protocol)** → simple, distance-vector.  
- **OSPF (Open Shortest Path First)** → link-state, scalable.  
- **BGP (Border Gateway Protocol)** → used on the Internet.  

---

## 📘 Router vs Switch
| Feature         | Switch (Layer 2)        | Router (Layer 3)           |
|-----------------|-------------------------|-----------------------------|
| Addressing      | MAC addresses           | IP addresses                |
| Scope           | Local network (LAN)     | Between networks (WAN/Internet) |
| Data Unit       | Frame                   | Packet                      |
| Example Device  | Ethernet switch         | Home/enterprise router      |

---

## 🧪 Practical Exercise
Students should:
1. Use `ip route` (Linux) or `route print` (Windows) to view their routing table.  
2. Configure a static route on a test system.  
3. Observe how a switch forwards traffic using MAC addresses.  
4. Create a VLAN on a managed switch (if available).  
5. Compare routing vs switching in a lab setup.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- Routing table inspection.  
- Static route configuration.  
- Explanation of dynamic routing protocols.  
- VLAN configuration example.  
- Comparison of router vs switch functionality.  

Save in:  
Week4_Networking_Services_and_Security/Assignments/Routing_Switching_Practice.md
