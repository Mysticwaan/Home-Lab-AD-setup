# 🧪 Home Lab: Active Directory Setup Using Oracle VirtualBox


This project documents my process of setting up a basic home lab to run **Active Directory** using **Windows Server** on **Oracle VirtualBox**. The goal was to create a learning environment to better understand Windows Server roles, Active Directory, DNS, and domain configurations in a virtualized setup.

![image](https://github.com/user-attachments/assets/feaedfe1-7d8e-4bb5-953a-7a81f15de258)

---

## 🖥️ Overview

I built a local virtual lab using Oracle VirtualBox and a Windows Server ISO to simulate an enterprise network environment. This setup allows for experimenting with:

- Active Directory Domain Services (AD DS)
- Domain Controller promotion
- DNS integration
- User and Organizational Unit (OU) management

---

## ✅ What I Did

### 🔽 Downloaded and Installed Tools

- Installed [Oracle VirtualBox](https://www.virtualbox.org/)
- Downloaded a Windows Server ISO (evaluation version from Microsoft)

### 💾 Created a Virtual Machine

- Allocated 4 GB RAM, 40 GB virtual hard disk
- Enabled networking (bridged/NAT) for external connectivity
- Mounted the Windows Server ISO to boot and install

  ![image](https://github.com/user-attachments/assets/0d63c273-0225-4914-998a-636b6a19dbea)


### 💡 Installed Windows Server

- Performed full installation via the ISO in VirtualBox
- Set up a local administrator account
- Applied basic Windows updates

### 🛠️ Configured Active Directory

- Installed **Active Directory Domain Services (AD DS)** role via Server Manager
- Promoted the server to a **Domain Controller**
- Created a new forest and domain 
- Configured integrated **DNS server**

![image](https://github.com/user-attachments/assets/7cac4f04-fb55-4cae-b417-fc1ea0e808f4)


### 🔍 Tested the Setup

- Created users and Organizational Units (OUs) in Active Directory
- Verified domain functionality and DNS resolution
- Logged in using a domain user to test connectivity

![image](https://github.com/user-attachments/assets/d6ae38b6-8000-45cd-82c8-2d23d4ffa90d)
![image](https://github.com/user-attachments/assets/cc390658-63d4-4148-8284-cff66e43250f)
![image](https://github.com/user-attachments/assets/43c5c3ce-5e63-4cf9-b743-4437aceb2892)


## 🧠 Lessons Learned

- Snapshots are critical for quick recovery from misconfigurations
- DNS configuration must be correct for AD to function
- VirtualBox's networking modes (bridged/NAT) can simulate real-world setups

---

