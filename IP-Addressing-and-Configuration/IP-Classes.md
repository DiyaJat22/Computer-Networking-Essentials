# 🌐 IP Address Classes – Explained

In IPv4 addressing, IP addresses are divided into **five classes** (A to E) to define the range and purpose of addresses used in a network. Each class serves different types of networks, from small LANs to large organizations.

---

## 📘 What is an IP Address?

An **IP (Internet Protocol) address** is a 32-bit numerical label assigned to each device connected to a network. It consists of:
- **Network ID**: Identifies the network.
- **Host ID**: Identifies the specific device (host) on the network.

---

## 🏷️ IP Address Classes

IPv4 addresses are divided into 5 classes:

| Class | Range                  | Default Subnet Mask   | Network Size           | Usage                         |
|-------|------------------------|------------------------|------------------------|-------------------------------|
| A     | 1.0.0.0 to 126.255.255.255 | 255.0.0.0              | Supports ~16 million hosts | Large organizations           |
| B     | 128.0.0.0 to 191.255.255.255 | 255.255.0.0            | Supports ~65,000 hosts     | Medium-sized organizations    |
| C     | 192.0.0.0 to 223.255.255.255 | 255.255.255.0          | Supports 254 hosts         | Small networks                |
| D     | 224.0.0.0 to 239.255.255.255 | N/A (Multicast)         | N/A                        | Multicast groups              |
| E     | 240.0.0.0 to 255.255.255.255 | Reserved                | N/A                        | Research and experimental use |

> ⚠️ Note: `127.0.0.0` to `127.255.255.255` is **reserved for loopback testing** and belongs to Class A.

---

## 🔢 Binary Representation

Each IP class is identified by the **starting bits** of the first octet:

| Class | Starting Bits | First Octet Range |
|-------|----------------|-------------------|
| A     | 0xxxxxxx       | 1 – 126           |
| B     | 10xxxxxx       | 128 – 191         |
| C     | 110xxxxx       | 192 – 223         |
| D     | 1110xxxx       | 224 – 239         |
| E     | 1111xxxx       | 240 – 255         |

---

## 🛡️ Private IP Address Ranges

These are **non-routable** addresses used for internal networks:

| Class | Private Range              |
|-------|----------------------------|
| A     | 10.0.0.0 – 10.255.255.255  |
| B     | 172.16.0.0 – 172.31.255.255|
| C     | 192.168.0.0 – 192.168.255.255 |

---

## 🧪 Classful vs Classless

- **Classful Addressing**: Uses fixed boundaries based on class (A, B, C).
- **Classless (CIDR)**: Uses **subnet masks** like `/24`, `/16` to allow more flexible IP allocation.

Example:  
- Classful: `192.168.1.0` with subnet `255.255.255.0` (Class C)  
- Classless: `192.168.1.0/26` (subnetted for smaller groups)

---

## 🧾 Summary

- **Class A**: Large networks, millions of hosts  
- **Class B**: Medium networks, thousands of hosts  
- **Class C**: Small networks, few hundred hosts  
- **Class D**: Multicast communication  
- **Class E**: Experimental and reserved  

> ✅ Most modern systems now use **CIDR (Classless Inter-Domain Routing)** instead of strict IP classes.

---
