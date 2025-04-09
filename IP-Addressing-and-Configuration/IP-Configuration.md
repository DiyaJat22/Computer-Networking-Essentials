# 🌐 IP Configuration Guide

Configuring an IP address is essential to ensure a device can communicate within a network and with the internet. This process can be **manual (static)** or **automatic (dynamic via DHCP)**.

---

## 🧭 What is IP Configuration?

IP configuration refers to the process of assigning an IP address and other network settings (subnet mask, gateway, DNS) to a device so it can participate in a network.

---

## 🛠️ IP Configuration Types

### 🔹 Static IP Configuration
- Manually assign:
  - IP address
  - Subnet mask
  - Default gateway
  - DNS server
- Suitable for:
  - Servers
  - Printers
  - Network infrastructure devices

### 🔸 Dynamic IP Configuration (DHCP)
- Uses **DHCP server** to automatically assign network settings.
- Suitable for:
  - Laptops
  - Mobile devices
  - Temporary client devices

---

## 💻 IP Configuration in Windows

### 🔍 View Current IP Configuration
```powershell
ipconfig
```

# 🖥️ Manual IP Configuration on Windows – Step-by-Step Guide

This guide will help you manually configure a static IP address on a Windows machine using the **Control Panel**.

---

## 🪜 Steps to Follow

### 1. Open Control Panel
- Go to the **Search bar** and type **Control Panel**.
- Once it appears, **double-click** on it.
- A dialog box will open.

---

### 2. Go to Network Settings
- In the Control Panel window, click on **"Network and Internet"**.

---

### 3. Open Network and Sharing Center
- A new menu will appear.
- Click on **"Network and Sharing Center"** on the left-hand side.

---

### 4. Change Adapter Settings
- In the left panel, click on **"Change adapter settings"**.

---

### 5. Select the Desired Network
- Right-click on the network connection you want to configure.
  
  If you're unable to find the desired network:
  - ✅ Ensure the **router is powered on**.
  - ✅ Check that the **Ethernet cable** is properly connected.
  - ✅ If using a **mobile hotspot**, make sure the device is visible under hotspot settings on your phone.

---

### 6. Open Properties
- Right-click the desired network connection and select **"Properties"**.

---

### 7. Select IPv4
- In the list of networking options, click on **Internet Protocol Version 4 (TCP/IPv4)**.
  
  > ℹ️ IPv4 is a 32-bit addressing protocol that is still widely used, despite the newer IPv6.

---

### 8. Manually Configure IP Address
- Click on the **"Properties"** button.
- Select **"Use the following IP address"** radio button.

---

### 9. Enter IP Configuration Details
Fill in the following values as provided by your **ISP (Internet Service Provider)**:

- **IP Address**:
  - A unique identifier for your device on a local or public network.
- **Subnet Mask**:
  - Separates the IP address into **network** and **host** portions.
- **Default Gateway** *(optional)*:
  - The IP of the router or gateway for internet access.
- **DNS Server**:
  - Maps domain names (like google.com) to IP addresses, acting like the internet’s phonebook.

---

## ✅ Done!
Your device will now use the manually configured IP settings to communicate within your network and access the internet (if connected properly).

---



