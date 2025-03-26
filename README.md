# 19CS419-Digital Forensics and Digital Investigations
## Workshop 1 - DIgital-Forensics

```
Name: RAJESH A
Reg No: 212222100042
Slot: 4U2-1
```

__________________________________________________________________________


# Installation of Kali Linux in VM:


How to Install Kali Linux on a Virtual Machine (VM) – Step-by-Step Guide
Step 1: Download Kali Linux ISO

1.Go to the official Kali Linux website:
👉  https://www.kali.org/get-kali/

2.Download the Kali Linux ISO file (choose 64-bit or 32-bit as per your system).

Step 2: Install & Set Up Virtual Machine Software
🔹 Install VMware Workstation Player (Recommended) or VirtualBox:

●Download VMware: https://www.vmware.com/go/getplayer

●Download VirtualBox: https://www.virtualbox.org/


Step 3: Create a New Virtual Machine

1.Open VMware / VirtualBox.

2.Click Create a New Virtual Machine.

3.Select "Install from ISO" and browse to the Kali Linux ISO file.

4.Choose Linux as the operating system and Debian 64-bit as the version.

Step 4: Configure VM Settings

1.Allocate RAM:

Minimum: 2GB

Recommended: 4GB or more

2.Assign CPU Cores:

Minimum: 2 cores

○Recommended: 4 cores

3.Create a Virtual Hard Disk:

Select Create a new virtual disk.

Allocate at least 20GB (Recommended: 50GB).


Step 5: Install Kali Linux

1.Start the VM and select Graphical Install.

2.Set Up User Information:

Choose Language, Region, and Keyboard Layout.

Set Username & Password.

3.Partitioning:

○Select "Use entire disk" (Recommended for beginners).

4.Install Base System:

Wait for installation (takes ~10-20 minutes).

5.Install GRUB Bootloader:

Select Yes to install the bootloader.

![image](https://github.com/user-attachments/assets/75de0c4a-2a65-4314-8fee-402e8a00139f)

![image](https://github.com/user-attachments/assets/da97e807-6bfd-4640-b5e2-955d8d6431fb)


# Installation of Autopsy:

Autopsy is a popular digital forensics tool used for analyzing disk images and investigating cybersecurity incidents. Here’s how you can install it on Windows and Linux:


## Installation Steps for Windows
### 1.Download Autopsy

Visit the official website: https://www.autopsy.com/download/

Click on Download Autopsy and get the latest Windows .exe
installer.


![image](https://github.com/user-attachments/assets/7b7a93ed-515a-470b-a5bf-674fffbc1c8f)




### 2.Run the Installer

Locate the downloaded .exe file and double-click to launch it.

![image](https://github.com/user-attachments/assets/e5b9485c-413f-43b5-a7cf-0c97cc7a405d)




### 3.Follow the Setup Wizard

Accept the license agreement.

Choose the installation directory.

Proceed with the installation by clicking Next until the process completes.


![image](https://github.com/user-attachments/assets/9ae1a90b-3275-4629-90d0-ba29485dd090)


![image](https://github.com/user-attachments/assets/87d4de61-c023-46e8-b34d-44ef678dbf54)

![image](https://github.com/user-attachments/assets/ff76b1a9-2118-4b0e-b5c8-8be39d1e6f02)


### 4.Launch Autopsy

Once installed, open Autopsy from the Start Menu.

The Graphical User Interface (GUI) should appear.

### 5.Verify Installation

Click on New Case to test if the software is working properly.
Step 1: Download Sleuth Kit for Windows

# Download of Sleuth Kit
1.Visit Sleuth Kit’s official download page.

2.Scroll to the Windows Binaries section.

3.Download the latest ZIP file (64-bit or 32-bit as per your system).

![image](https://github.com/user-attachments/assets/4fe44721-e9ce-4c5f-8e11-6bf6053aff5b)



Step 2: Extract & Move to Program Files
1.Locate the downloaded ZIP file in your Downloads folder.

2.Right-click and select Extract All....

3.Move the extracted folder to:

![image](https://github.com/user-attachments/assets/85e25b9b-d7db-48ed-a10b-312c160513ad)



Step 3: Set Up Environment Variables
1.Open System Properties:

Press Win + R, type sysdm.cpl, and hit Enter.

Go to the Advanced tab and click Environment Variables.

2.Edit the Path Variable:

Under System Variables, find and select Path, then click Edit.

Click New, and add:


![image](https://github.com/user-attachments/assets/3ce692e3-0bf0-4af4-a181-332aa3645ecb)




Step 4: Verify Installation
1.Open Command Prompt (cmd).

2.Type:

![image](https://github.com/user-attachments/assets/ae7caf0b-ca1c-4194-8977-ce7805332722)



3.To Check if it is installed.

![image](https://github.com/user-attachments/assets/8655ce32-35a2-4a69-8ed1-78244eb173d7)



