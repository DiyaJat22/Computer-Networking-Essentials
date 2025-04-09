# 🌐 Private vs Public IP Addresses

In IP networking, addresses are categorized into **public** and **private** based on their accessibility over the internet. Both types play a crucial role in how devices communicate within local and global networks.

---

## 📘 What is an IP Address?

An **IP address** is a unique identifier assigned to each device on a network. It allows devices to locate and communicate with each other.

---

## 🔒 Private IP Address

### ✅ Definition:
A **private IP address** is used within a **local area network (LAN)** and **not routable** over the internet. These are reserved IP ranges meant for internal communication.

### 🔐 Private IP Ranges:

| Class | IP Range                        | Subnet Mask        |
|-------|----------------------------------|---------------------|
| A     | 10.0.0.0 – 10.255.255.255        | 255.0.0.0           |
| B     | 172.16.0.0 – 172.31.255.255      | 255.240.0.0         |
| C     | 192.168.0.0 – 192.168.255.255    | 255.255.0.0         |

### 🧰 Uses:
- Home and business LANs
- Wi-Fi routers and internal devices
- Virtual machines and Docker containers

### 🛡️ Features:
- Cannot access the internet directly
- Requires **NAT (Network Address Translation)** for internet access
- No need to register or pay for usage

---

## 🌍 Public IP Address

### ✅ Definition:
A **public IP address** is assigned to a device that is directly accessible over the internet. It must be **unique globally**.

### 🌐 Characteristics:
- Assigned by **ISPs** (Internet Service Providers)
- Routable over the internet
- Identifies your network to the outside world

### 🧰 Uses:
- Websites and servers
- Routers facing the internet
- Direct online communication

---

## 🔁 Comparison Table

| Feature                 | Private IP Address                   | Public IP Address                      |
|-------------------------|--------------------------------------|----------------------------------------|
| Scope                   | Local network (LAN)                  | Global internet                        |
| Accessibility           | Not accessible from the internet     | Accessible from anywhere               |
| NAT Required            | ✅ Yes                               | ❌ No (already public)                 |
| Assigned By             | Network administrator or router      | ISP or IANA                            |
| Cost                    | Free                                 | May incur charges                      |
| IP Uniqueness           | Not globally unique                  | Must be globally unique                |
| Example                 | 192.168.1.1                          | 203.0.113.5                            |

---

## 🧪 How to Check Your IP

### 🔍 Private IP:
Use in Command Prompt or Terminal:
```bash
ipconfig         # Windows
ifconfig / ip a  # Linux/macOS
```
