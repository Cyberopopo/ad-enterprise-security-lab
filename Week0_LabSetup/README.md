# Week 0 — Lab Setup  
## 🖥️ Step 1: Virtual Machine Creation (VMware Workstation)

This step covers creating new Virtual Machines (VMs) for our Active Directory lab environment using **VMware Workstation**.  
We will set up:  
- **Windows Server 2022** → Domain Controller (`DC1.cyberopopo.local`)  
- **Windows 10 Pro** → Client 1  
- **Windows 11 Pro** → Client 2  

---

### 1. Open VMware Workstation
- Launch **VMware Workstation**.  
- On the home screen, click **Create a New Virtual Machine**.  
 
![New VM Wizard Screen](https://i.imgur.com/4OWsnHc.png)

---

### 2. Choose Configuration  
- Select **Typical (recommended)**.  
- Click **Next**.  
 
![New VM Wizard - Typical Configuration](https://i.imgur.com/tCw9PhX.png)


---

### 3. Select Installation Method  
- Choose **I will install the operating system later**.  
- Click **Next**.  
  
![Select Installation Method - Install Later](https://i.imgur.com/iSAh1C0.png)


---

### 4. Select Guest Operating System  
- Guest OS: **Microsoft Windows**  
- Version: **Windows Server 2022**  
- Click **Next**  

![Select Guest Operating System - Windows Server 2022](https://i.imgur.com/Mr7nubq.png)


---

### 5. Name the VM & Choose Location  
- Use clear names for each VM:  
  - `DC1-cyberopopo.local` → Domain Controller  
- Choose storage locations for VM files.  
- Click **Next**  
 
![Name the VM and Choose Location](https://i.imgur.com/7bk0ysO.png)


---

### 6. Specify Disk Capacity  
- Recommended sizes:  
  - **20 GB** → Windows Server 2022 (DC)   
- Select: **Split virtual disk into multiple files**  
- Click **Next**  
  
![Disk Size Setup](https://i.imgur.com/L2zYDkc.png)


---

### 7. Finish & Customize Hardware  
- Click **Finish** to create VM.  
- (Optional) Adjust hardware before powering on:  
  - **DC1 (Server 2022)** → 4 GB RAM, 2 CPU cores    
 
![VM Hardware Settings](https://i.imgur.com/VutLCvg.png)

---

## 🖥️ Creating Windows 10 Pro Client VM  

### 1. Start New Virtual Machine Wizard  
- Open VMware Workstation / VirtualBox.  
- Select **Create a New Virtual Machine**.  

![New VM Wizard - Start](https://i.imgur.com/dRyv2Yf.png)

---

### 2. Choose Configuration  
- Select **Typical (recommended)**.  
- Click **Next**.  

![New VM Wizard - Typical Configuration](https://i.imgur.com/lRqaled.png)


---

### 3. Select Installation Method  
- Choose **I will install the operating system later**.  
- Click **Next**.  

![Install Later Option](https://i.imgur.com/FlTwdgz.png)

---

### 4. Select Guest Operating System  
- Guest OS: **Microsoft Windows**  
- Version: **Windows 10 X64**  
- Click **Next**
 
![Select Windows 10 Pro](https://i.imgur.com/AldgJAX.png)


---

### 5. Name the VM & Location  
- Suggested name: `Win10-Client1`  
- Choose VM file storage location.  
- Click **Next**.  
  
![Name the VM & Location](https://i.imgur.com/bZsuF6b.png)


---

### 6. Specify Disk Capacity  
- Recommended: **20 GB** (since client PCs will need more than DC).  
- Select: **Split virtual disk into multiple files**.  
- Click **Next**.  
 
![Windows 10 Disk Setup](https://i.imgur.com/EbgiQ96.png)


---

  ### 7. Customize Hardware  
- Adjust hardware before powering on:  
  - **RAM** → 2 GB  
  - **CPU** → 2 cores  
  - **Network Adapter** → Host-Only  
  - **Add ISO** → Windows 10 Pro ISO  
 
![Windows 10 Hardware Settings](https://i.imgur.com/jj7JXs0.png)


---

### 8. Finish & Power On  
- Click **Finish** to complete VM creation.  
- Insert Windows 10 ISO and start the installation.  

![Windows 10 Installation Start](https://i.imgur.com/54TsE2r.png)

---
## Repeat this procedure to create Windows 11 Client VM



✅ At this point, all three virtual machines are created.  
Next, we will proceed with installing **Windows Server 2022 on the Domain Controller (DC1.cyberopopo.local)**, then install and configure the **Windows 10 and 11 client machines**.  
