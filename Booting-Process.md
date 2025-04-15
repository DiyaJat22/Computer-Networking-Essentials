# Booting Process

The booting process refers to the sequence of steps a computer system follows to load the operating system into memory and start functioning. It is a critical component of system startup.

---

## 🔁 Types of Booting

- **Cold Boot (Hard Boot):**
  - Starting the computer from a completely powered-off state.
- **Warm Boot (Soft Boot):**
  - Restarting the computer without turning off the power (e.g., using Ctrl+Alt+Del or Restart).

---

## 🧭 Booting Process Steps

### 1. Power On
- Power is supplied to the motherboard.
- Power Supply Unit (PSU) checks voltage levels (Power Good signal).
- CPU is reset and takes control.

### 2. POST (Power-On Self-Test)
- Performed by BIOS/UEFI.
- Checks:
	- RAM
	- CPU
	- Keyboard
	- Storage devices
	- Errors are reported via beep codes or messages.

### 3. BIOS/UEFI Execution
- BIOS/UEFI is firmware stored on the motherboard.
- Looks for a bootable device based on boot priority.
- Loads the **bootloader** from the MBR/GPT.

### 4. Bootloader
- Examples: GRUB (Linux), Windows Boot Manager.
- Responsibilities:
  - Load the OS kernel.
  - Pass control to the kernel.
- GRUB may offer a menu to select OS/version.

### 5. Kernel Load
- The kernel is loaded into memory.
- Initializes:
  - Memory management
  - Device drivers
  - File system

### 6. Init/Systemd
- Launches the first user-space program (init or systemd).
- Initializes system services and targets.

### 7. Login Manager
- GUI: GDM, LightDM, SDDM
- CLI: login prompt
- Accepts user credentials and starts user session.

---

## 🧠 Key Components in Booting

| Component       | Role                                                                 |
|----------------|----------------------------------------------------------------------|
| BIOS/UEFI       | Initializes hardware, locates and runs the bootloader                |
| Bootloader      | Loads the kernel into memory                                         |
| Kernel          | Core of the OS, manages hardware and system processes                |
| Init/Systemd    | Initializes and manages services and user-space processes            |
| Shell/Desktop   | Provides user interface (CLI/GUI)                                    |

---

## 💡 Additional Notes

- **MBR (Master Boot Record)**:
  - Found on first sector of bootable disk.
  - Contains bootloader and partition table.

- **UEFI vs BIOS**:
  - UEFI is modern, supports larger drives, secure boot.
  - BIOS is older and being phased out.

- **Dual Boot**:
  - Multiple OS installed.
  - Bootloader presents a menu to choose.

---

## Booting Process Diagram

![image](https://github.com/user-attachments/assets/f34b7ff3-3928-41ae-9cd4-e3e14a7172c5)


---
