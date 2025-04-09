# 🧭 MAC Address – Explained

A **MAC address** (Media Access Control address) is a unique identifier assigned to a **network interface card (NIC)** for communications at the **data link layer (Layer 2)** of the OSI model.

---

## 🔍 What is a MAC Address?

- A **MAC address** is a **hardware address** that uniquely identifies each device on a local network (LAN).
- It is **assigned by the manufacturer** and stored in the NIC.
- It is also known as a **physical address**, **hardware address**, or **burned-in address (BIA)**.

---

## 🧱 Structure of a MAC Address

- Consists of **48 bits** or **6 bytes**
- Usually written in **hexadecimal**, separated by colons or hyphens:
  
---

```powershell
Example: 00:1A:2B:3C:4D:5E or 00-1A-2B-3C-4D-5E
```


### 📦 Format:
- **First 3 bytes (24 bits)**: Organizationally Unique Identifier (**OUI**) – identifies the manufacturer
- **Last 3 bytes (24 bits)**: Device-specific identifier – uniquely identifies the device

---

## 🧭 Types of MAC Addresses

| Type                | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Unicast**         | Identifies a single network interface                                       |
| **Multicast**       | Sent to a group of devices on a LAN                                         |
| **Broadcast**       | Sent to all devices in a network segment (e.g., `FF:FF:FF:FF:FF:FF`)         |

---

## 🔎 How to Find MAC Address

### 🔹 On Windows
```powershell
ipconfig /all
```
