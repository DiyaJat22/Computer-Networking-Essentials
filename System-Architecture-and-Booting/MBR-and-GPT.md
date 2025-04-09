# ⚙️ BIOS vs UEFI – Explained

This document provides an overview of **BIOS** and **UEFI**, two types of firmware interfaces responsible for initializing hardware and starting the operating system on a computer.

---

## 📘 What is Firmware?

**Firmware** is a small piece of software stored on a chip on the motherboard. It acts as a bridge between the computer's hardware and the operating system.

---

## 🧠 BIOS (Basic Input/Output System)

### 🔹 Definition:
BIOS is the **legacy firmware** used in older computers to initialize and test hardware components and load the operating system.

### 🔹 Key Features:
- Stored in **ROM** or flash memory.
- Performs **POST (Power-On Self Test)**.
- Uses **MBR (Master Boot Record)** for booting.
- Operates in **16-bit real mode**.
- Text-based interface (no mouse support).
- Bootable drive size limited to **2 TB**.
- Supports only **4 primary partitions**.

### 🔹 Access:
Press keys like `Del`, `F2`, or `F10` during system startup.

---

## 🚀 UEFI (Unified Extensible Firmware Interface)

### 🔹 Definition:
UEFI is the **modern replacement for BIOS**, offering better performance, security, and support for larger drives and advanced features.

### 🔹 Key Features:
- Stored in flash memory on the motherboard.
- Uses **GPT (GUID Partition Table)**.
- Supports drives **larger than 2 TB**.
- Operates in **32-bit or 64-bit mode**.
- Faster boot times and better graphics.
- Secure Boot support to prevent unauthorized OS loading.
- GUI-based interface with mouse and keyboard support.

### 🔹 Access:
Press `Del`, `Esc`, or `F2` during boot (varies by manufacturer).

---

## 📊 Comparison Table

| Feature                | BIOS                           | UEFI                                |
|------------------------|--------------------------------|-------------------------------------|
| Full Form              | Basic Input Output System      | Unified Extensible Firmware Interface |
| Boot Method            | MBR                            | GPT                                 |
| Drive Size Limit       | Up to 2 TB                     | More than 2 TB                      |
| Partition Limit        | 4 Primary                      | 128+ Partitions                     |
| User Interface         | Text-based                     | GUI + Mouse Support                 |
| Architecture           | 16-bit                         | 32/64-bit                           |
| Secure Boot            | ❌ Not Available               | ✅ Available                        |
| Speed                  | Slower                         | Faster                              |
| Modern Use             | Legacy Systems                 | Current and Future Systems          |

---

## 🔐 UEFI & Cybersecurity

- **Secure Boot** ensures only trusted operating systems can boot, reducing malware risks.
- UEFI supports **firmware-level encryption keys** and TPM integration.

---

## 📂 Booting Differences

| BIOS Boot               | UEFI Boot                    |
|-------------------------|------------------------------|
| Loads bootloader from MBR | Loads `.efi` file from EFI System Partition |
| No Secure Boot          | Secure Boot Supported         |
| Limited scripting       | Supports boot scripting (Shell) |

---

## 🧾 Summary

- **BIOS** is the traditional firmware still found on older systems.
- **UEFI** is the modern, more powerful alternative with enhanced security and performance.
- Most current systems support **UEFI with legacy BIOS mode** for backward compatibility.

---
