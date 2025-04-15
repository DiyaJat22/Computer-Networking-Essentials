
# Installation of Window-7

Here's a **step-by-step guide to installing Windows 7** on a Virtual-Box

win 7  bit iso - [https://tech-latest.com/download-windows-7-iso/](https://tech-latest.com/download-windows-7-iso/)

### Steps 

Step 1:
1. Install the window 7 ultimate iso from archive website 

![1 1](https://github.com/user-attachments/assets/87f16d6a-862f-4007-9cf8-c41fca3b4b57)

2. Virtual Box Setup -
3. Click **New**.

![1](https://github.com/user-attachments/assets/048c3a67-a68f-4c23-905b-6d0177ff718b)

Step 2:  Name it something like `Windows-7`.
  - - Set:
    - **Type:** Microsoft Windows
    - **Version:** Windows 7 (32-bit or 64-bit depending on your ISO)
    - Click **Next**.

![2](https://github.com/user-attachments/assets/f4e52604-4ae0-444d-968e-52f6e54b490d)

Step 3: Allocate RAM
- Minimum: 4096 MB (4 GB) 
- Set Boot Order 

![3](https://github.com/user-attachments/assets/7a504212-d7ab-4e83-8bce-43e2a563b690)

![4](https://github.com/user-attachments/assets/450b9ae2-f472-4463-bf7a-8d0c71c31b3b)

Mount Windows 7 ISO
1. Select your new VM, click **Settings**. 
2. Go to **Storage**.
3. Under **Controller: IDE**, click the empty disc icon.
4. On the right, click the disc icon and choose **Choose a disk file**.
5. Select your **Windows 7 ISO file**.
6. Click **OK**.

![5](https://github.com/user-attachments/assets/acda4436-c631-4728-870e-1f9e44ab839b)

Step 4: Create a Virtual Hard Disk
- Choose **Create a virtual hard disk now**.
-  Choose format **VDI (VirtualBox Disk Image)**.

![6](https://github.com/user-attachments/assets/2660038b-5940-4184-ae3a-701b933a9ef4)

- Choose **Dynamically allocated**.
-  Set size: at least **40 GB**.
-  Click **Create**.

![7](https://github.com/user-attachments/assets/c5506ec2-fdb2-48ba-b76b-7bd8777bfe66)

![8](https://github.com/user-attachments/assets/686a1c20-5fd3-460d-81b9-5cee72775b31)

![9](https://github.com/user-attachments/assets/9c1dbb6c-be7a-4d62-afae-47b674a654f3)

 Step 5: Start the VM
1. Select the VM and click **Start**.
2. It will boot from the ISO.
Choose your preferred **language**, **time and currency format**, and **keyboard or input method**.

![10](https://github.com/user-attachments/assets/6568ad15-a812-4b56-aeb1-0b22427e8c11)

![11](https://github.com/user-attachments/assets/08318703-96a7-4ca6-8756-225693be9ea6)

Accept license > **Next**.

![12](https://github.com/user-attachments/assets/31c9f79b-c4ad-4ce9-a92e-bcce053031ea)

Choose **Custom (Advanced)**.

![13](https://github.com/user-attachments/assets/fc7c1fa9-d4c7-48c5-8e56-c8c81c53c0b5)

![14](https://github.com/user-attachments/assets/27aad58d-f7e8-40e6-a7fa-a64102c48ef2)

Select the virtual hard disk > **Next**.

![15](https://github.com/user-attachments/assets/f40f3435-dc34-4b52-a3bd-0f7dedbd792b)

![16](https://github.com/user-attachments/assets/40f73190-73d0-4d7d-9faa-9d25a49f183a)

![17](https://github.com/user-attachments/assets/05876511-e9b3-4f25-8e9d-4885ab9b5867)

![18](https://github.com/user-attachments/assets/0e22214d-c391-4a43-99b4-89baf38779a3)

Step 6: Complete Setup
1. Enter a username and computer name.

![19](https://github.com/user-attachments/assets/b05aaa15-f38a-41a5-957f-ab7c19a80220)


Set a password (optional).

![20](https://github.com/user-attachments/assets/e59db9c1-3654-4b76-8ddd-683945b0b2a8)

Enter product key (or skip to activate later).

![21](https://github.com/user-attachments/assets/d01e780d-b780-4c2e-9295-9f9a27310ba0)

![22](https://github.com/user-attachments/assets/05869df4-086f-4ebf-b9fc-087cfa1fcfa4)

Choose update settings, set time, etc.

![23](https://github.com/user-attachments/assets/cb233034-9c97-492c-871b-754bb90dc618)

![24](https://github.com/user-attachments/assets/2b0091a6-50ad-403a-b1a7-c26b84e38e8e)

![25](https://github.com/user-attachments/assets/0992086c-dc23-4e91-9643-ea3dd601425a)

 Step 7: Install VirtualBox Guest Additions (Optional but recommended)
1. While Windows is running, click **Devices > Insert Guest Additions CD image…** in VirtualBox menu.

![26-install-driver](https://github.com/user-attachments/assets/aea53ecb-e271-4f8d-a86c-224425915043)

2. Open the virtual CD inside Windows and run the installer.   

![27](https://github.com/user-attachments/assets/ae392a70-7261-48b7-b8d5-6777539d0155)

![28](https://github.com/user-attachments/assets/f285b359-1483-4593-8982-a37d217e6c16)

![29](https://github.com/user-attachments/assets/f5aa796b-46f9-4b77-ba87-8ce8bc5452dc)

![30](https://github.com/user-attachments/assets/59347abb-6fcc-4435-9b47-ca42a760b1fb)

![31](https://github.com/user-attachments/assets/efb37330-f2b7-478d-94b5-3d01f17b0f07)

![32](https://github.com/user-attachments/assets/b4a12ce8-2146-4cd3-b9b5-2304b544b278)

![33](https://github.com/user-attachments/assets/7616e658-f101-4ace-b964-f4ebe1d836cf)

2. Reboot when done — this improves graphics, enables shared clipboard, etc.

![34](https://github.com/user-attachments/assets/8fdf7bc1-b8c5-458f-9890-90441080994c)

Done! 🎉 You now have a working **Windows 7 virtual machine**.
