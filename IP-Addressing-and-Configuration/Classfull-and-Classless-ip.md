# 🌍 Classful vs Classless Addressing – Explained

In IPv4 networking, **Classful** and **Classless Addressing** are two methods used for allocating and identifying IP addresses. Understanding the difference between them is essential for network design and subnetting.

---

## 📘 What is IP Addressing?

An **IP address** is a 32-bit number that identifies a device on a network. Addressing schemes define how IP addresses are distributed and used.

---

## 🏷️ Classful Addressing

### ✅ Description:
- Introduced in the early days of IP networking.
- Divides IP address space into **fixed classes**: A, B, C, D, and E.
- The **class of the IP address** determines the **default network and host split**.

### 📐 Structure:
| Class | Network Bits | Host Bits | Default Subnet Mask |
|-------|--------------|-----------|----------------------|
| A     | 8            | 24        | 255.0.0.0            |
| B     | 16           | 16        | 255.255.0.0          |
| C     | 24           | 8         | 255.255.255.0        |

### ⚠️ Limitations:
- Wastes IP addresses (e.g., assigning a Class A to a small network).
- Rigid boundaries — no flexibility.
- No efficient subnetting.

---

## 🧮 Classless Addressing (CIDR)

### ✅ Description:
- **CIDR (Classless Inter-Domain Routing)** introduced in 1993 to solve classful limitations.
- Allows IP addresses to be divided based on **custom subnet masks**.
- Uses a **slash notation** (e.g., `192.168.1.0/24`).

### 📐 Example:
- `192.168.1.0/26` → Subnet mask: `255.255.255.192`
- More flexible allocation and **efficient use of IPs**.

### 🛠️ Advantages:
- Reduces waste of IP addresses.
- Enables better **route aggregation**.
- Supports **VLSM (Variable Length Subnet Masking)**.
- Essential for modern networking and the internet.

---

## 🔁 Comparison Table

| Feature               | Classful Addressing        | Classless Addressing (CIDR)      |
|------------------------|----------------------------|----------------------------------|
| Introduced In          | 1981                       | 1993                             |
| IP Classes Used        | Yes (A, B, C)              | No (CIDR instead)                |
| Subnet Mask            | Fixed by class             | Defined by `/n` notation         |
| Address Utilization    | Inefficient                | Efficient                        |
| Routing                | More complex               | Simplified through aggregation   |
| Flexibility            | Low                        | High                             |
| Supports VLSM          | ❌ No                      | ✅ Yes                           |

---

## 🧾 Summary

- **Classful Addressing**: Uses fixed IP classes with default subnet masks.
- **Classless Addressing (CIDR)**: Allows flexible subnetting and efficient IP usage.
- Classless is widely used today for **subnetting, routing, and IP conservation**.

---
