# **Internet Protocol (IP)**

## **Introduction to IP**

IP (Internet Protocol) is a fundamental communication protocol in the Internet and local networks. It assigns a unique numerical label to each device within a network, ensuring proper data transfer and routing.

### **Functions of IP:**

- Identifies devices on a network.
- Enables data packet transmission between devices.
- Supports addressing and routing to ensure efficient communication.

## **Versions of IP**

There are two primary versions of IP:

1. **IPv4 (Internet Protocol Version 4)**
2. **IPv6 (Internet Protocol Version 6)**

## **IPv4 Address Structure**

- IPv4 is a **32-bit** addressing system.
- It is divided into **four sections** (also called octets).
- Each section consists of **8 bits**.
- Uses **decimal notation**, where each section ranges from **0 to 255**.
- Example of an IPv4 address: **192.168.1.1**

### **Range of IPv4 Addresses:**

- The minimum address: **0.0.0.0**
- The maximum address: **255.255.255.255**

### **Total Number of IPv4 Addresses:**

Each IPv4 address consists of 32 bits, and since each bit has 2 possible values (0 or 1), the total number of unique IPv4 addresses is:

```math
2^{32} = 4,294,967,296
```

(approximately **4.3 billion** addresses)

### **Assignment of IPv4 Addresses (Example Sequence):**

- 0.0.0.0
- 0.0.0.1
- 0.0.0.2
- 0.0.0.3
- 0.0.0.9
- 0.0.0.10
- 0.0.0.255
- 0.0.1.0
- … (continues sequentially)

## **IPv6 Address Structure**

- IPv6 is a **128-bit** addressing system.
- Uses **eight groups of four hexadecimal digits**.
- Example of an IPv6 address: **2001:0db8:85a3:0000:0000:8a2e:0370:7334**
- Provides a significantly larger number of addresses:

```math
2^{128}
```

(approximately **340 undecillion** addresses).

## **IP Address Classes**

IPv4 addresses are categorized into five classes: A, B, C, D, and E. Each class has a specific range and purpose.

### **Class A**

- **Range:** 0.0.0.0 to 127.255.255.255
- **First bit:** 0 (ON), remaining bits for network and host.
- **Network bits:** 8
- **Host bits:** 24
- **Purpose:** Assigned to large networks, often used by government organizations.
- **Bit Representation:** `0XXXXXXX.XXXXXXXX.XXXXXXXX.XXXXXXXX`

### **Class B**

- **Range:** 128.0.0.0 to 191.255.255.255
- **First two bits:** 10 (ON), remaining bits for network and host.
- **Network bits:** 16
- **Host bits:** 16
- **Purpose:** Used by medium-sized businesses and universities.
- **Bit Representation:** `10XXXXXX.XXXXXXXX.XXXXXXXX.XXXXXXXX`

### **Class C**

- **Range:** 192.0.0.0 to 223.255.255.255
- **First three bits:** 110 (ON), remaining bits for network and host.
- **Network bits:** 24
- **Host bits:** 8
- **Purpose:** Assigned to small networks, such as local businesses and private organizations.
- **Bit Representation:** `110XXXXX.XXXXXXXX.XXXXXXXX.XXXXXXXX`

### **Class D**

- **Range:** 224.0.0.0 to 239.255.255.255
- **First four bits:** 1110 (ON), used for multicast groups.
- **Purpose:** Reserved for multicast networking.
- **Bit Representation:** `1110XXXX.XXXXXXXX.XXXXXXXX.XXXXXXXX`

### **Class E**

- **Range:** 240.0.0.0 to 255.255.255.255
- **First four bits:** 1111 (ON), used for experimental purposes.
- **Purpose:** Reserved for research and development.
- **Bit Representation:** `1111XXXX.XXXXXXXX.XXXXXXXX.XXXXXXXX
