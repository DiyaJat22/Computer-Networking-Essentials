# Network Mask Structure (Subnet Mask Explained)

## What is a Network Mask?
A **network mask** (subnet mask) helps divide an IP address into two parts:

1. **Network portion** – Identifies the network.
2. **Host portion** – Identifies a specific device within the network.

## Structure of a Subnet Mask
A subnet mask is a **32-bit number** (like an IPv4 address) written in **dotted decimal notation** (e.g., `255.255.255.0`).

It consists of:
- **1s (network part)** – Defines the network.
- **0s (host part)** – Defines individual devices within the network.

### Example: IP Address and Subnet Mask
- **IP Address:** `192.168.1.10`
- **Subnet Mask:** `255.255.255.0`

#### Binary Representation:
```
IP Address:    11000000.10101000.00000001.00001010  (192.168.1.10)
Subnet Mask:   11111111.11111111.11111111.00000000  (255.255.255.0)
```

- **Network Portion:** `192.168.1.` (First 3 octets)
- **Host Portion:** `10` (Last octet)

👉 Devices in the **192.168.1.0/24** network will have IPs like: `192.168.1.1, 192.168.1.2, ... 192.168.1.254` (Total **254 devices**).

---

## Types of Subnet Masks

| **Subnet Mask**   | **CIDR Notation** | **No. of Hosts** | **Example Network** |
|------------------|----------------|----------------|-----------------|
| `255.0.0.0`      | `/8`            | 16,777,214     | `10.0.0.0/8`    |
| `255.255.0.0`    | `/16`           | 65,534         | `172.16.0.0/16` |
| `255.255.255.0`  | `/24`           | 254            | `192.168.1.0/24` |

---

## Why is the Subnet Mask Important?

1. **Defines the network size** – Determines how many devices can exist within the network.
2. **Helps routers understand IP routing** – Routers use subnet masks to direct traffic.
3. **Enhances security** – Supports network segmentation, reducing unnecessary communication.

## Conclusion
Understanding subnet masks is essential for effective network management. Proper subnetting enhances resource allocation, security, and performance.
