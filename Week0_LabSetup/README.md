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

✅ At this point, all three virtual machines are created.  
Next, we will proceed with installing **Windows Server 2022 on the Domain Controller (DC1.cyberopopo.local)**, then install and configure the **Windows 10 and 11 client machines**.  
