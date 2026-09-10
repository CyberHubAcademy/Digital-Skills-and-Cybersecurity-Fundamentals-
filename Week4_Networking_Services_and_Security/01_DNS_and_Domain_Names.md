# Week 4: DNS and Domain Names
# ALGURAWY CYBERHUB ACADEMY  
# Sponsored by DR. BUKAR USMAN FOUNDATION & IRIAD  

---

## 🎯 Learning Objectives
By the end of this session, students should be able to:
- Explain the purpose of the Domain Name System (DNS).
- Understand how domain names are resolved into IP addresses.
- Identify common DNS record types (A, MX, CNAME, etc.).
- Use basic DNS tools (`nslookup`, `dig`) for troubleshooting.
- Recognize the role of DNS in networking and cybersecurity.

---

## 📘 What is DNS?
- **DNS (Domain Name System)** is the “phonebook of the Internet.”  
- It translates **human-readable domain names** (e.g., `www.google.com`) into **IP addresses** (e.g., `142.250.190.78`).  
- Without DNS, users would need to remember numeric IP addresses.  

---

## 📑 How DNS Works
1. User enters a domain name in the browser.  
2. The request goes to a **DNS resolver** (usually provided by ISP).  
3. Resolver queries **root servers** → **TLD servers** → **authoritative servers**.  
4. The IP address is returned to the client.  
5. Browser connects to the server using the IP address.  

### Example
- Input: `www.example.com`  
- DNS resolves to: `93.184.216.34`  
- Browser connects to that IP.  

---

## 📘 Common DNS Records
| Record | Purpose                          | Example                  |
|--------|----------------------------------|--------------------------|
| **A**  | Maps domain → IPv4 address       | `example.com → 93.184.216.34` |
| **AAAA** | Maps domain → IPv6 address     | `example.com → 2606:2800:220:1:248:1893:25c8:1946` |
| **MX** | Mail exchange (email servers)    | `mail.example.com`       |
| **CNAME** | Canonical name (alias)        | `www → example.com`      |
| **NS** | Nameserver for the domain        | `ns1.example.com`        |
| **TXT** | Text records (SPF, DKIM, notes) | `v=spf1 include:_spf.google.com` |

---

## 📘 DNS Tools
- **nslookup** → Query DNS records.
  # nslookup www.google.com

  - **dig** → Advanced DNS queries.  
    dig example.com MX

    - **ping** → Verify connectivity after resolution.  
     ping www.example.com

---

## 📘 Cybersecurity Connection
- DNS can be abused in attacks:  
- **DNS spoofing** → Fake responses redirect users.  
- **DNS tunneling** → Hidden data exfiltration.  
- **Phishing domains** → Lookalike names trick users.  
- Securing DNS is critical for safe communication.  

---

## 🧪 Practical Exercise
Students should:
1. Use `nslookup` to resolve `www.google.com`.  
2. Use `dig` to query MX records for `yahoo.com`.  
3. Identify the IP address returned.  
4. Ping the domain to verify connectivity.  
5. Discuss how DNS could be exploited in phishing attacks.  

---

## 📜 Assignment
Prepare a demonstration log showing:
- DNS resolution using `nslookup` and `dig`.  
- Identification of different DNS record types.  
- Verification of connectivity using `ping`.  
- Explanation of one DNS-related security risk.  

Save in:  
Week4_Networking_Services_and_Security/Assignments/DNS_Practice.md
  
