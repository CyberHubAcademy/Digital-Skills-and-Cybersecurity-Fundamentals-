# Week 4: Practical Network Troubleshooting
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Apply a structured approach to diagnosing network problems.
- Use basic troubleshooting tools (`ping`, `traceroute`, `netstat`, `ipconfig/ifconfig`).
- Identify common connectivity issues and their causes.
- Document troubleshooting steps and solutions.
- Connect troubleshooting skills to real-world cybersecurity practice.

---

## 📘 Structured Troubleshooting Approach
1. **Identify the Problem** → Gather symptoms, error messages, user reports.  
2. **Establish Scope** → Is the issue local, network-wide, or external?  
3. **Test Connectivity** → Use diagnostic tools to verify communication.  
4. **Isolate the Cause** → Hardware, software, configuration, or external factors.  
5. **Implement Solution** → Apply fixes (restart, reconfigure, replace).  
6. **Verify Resolution** → Confirm the issue is solved.  
7. **Document Findings** → Record steps for future reference.  

---

## 📑 Common Troubleshooting Tools
### `ping`
- Tests co
- nnectivity to another host.  
- Example:  
ping www.google.com


### `traceroute` / `tracert`
- Shows the path packets take to reach a destination.  
- Example:  
traceroute 8.8.8.8   # Linux/macOS
tracert 8.8.8.8      # Windows


### `ipconfig` / `ifconfig`
- Displays IP configuration.  
- Example:  
# Windows
ipconfig /all   
# Linux/macOS
ifconfig  

### `netstat`
- Shows active connections and listening ports.  
- Example:  
netstat -an

### `nslookup` / `dig`
- Tests DNS resolution.  
- Example:  
nslookup www.example.com
dig example.com


---

## 📘 Common Issues
- **No IP address** → DHCP failure.  
- **Cannot reach gateway** → Router issue.  
- **DNS not resolving** → Misconfigured DNS server.  
- **Slow connection** → Bandwidth congestion or faulty hardware.  
- **Intermittent connectivity** → Loose cables, Wi-Fi interference.  

---

## 📘 Cybersecurity Connection
- Troubleshooting helps detect:  
- Rogue devices on the network.  
- Suspicious connections (`netstat`).  
- DNS hijacking or spoofing.  
- Security analysts rely on troubleshooting tools to investigate incidents.  

---

## 🧪 Practical Exercise
Students should:
1. Use `ping` to test connectivity to their default gateway.  
2. Run `traceroute` to `8.8.8.8` and document the hops.  
3. Use `ipconfig` or `ifconfig` to check their IP configuration.  
4. Run `netstat` to view active connections.  
5. Use `nslookup` to resolve `www.google.com`.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- Connectivity test using `ping`.  
- Path analysis using `traceroute`.  
- IP configuration output.  
- Active connections using `netstat`.  
- DNS resolution using `nslookup` or `dig`.  

Save in:  
Week4_Networking_Services_and_Security/Assignments/Troubleshooting_Practice.md
