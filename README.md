# 🛡️ Active Directory End-to-End Project (6 Weeks)

This repository documents my journey of building and securing an **Active Directory (AD) environment** from scratch.  
The project is structured over **6 weeks**, showcasing both **offensive (Red Team)** and **defensive (Blue Team)** security skills, with professional documentation and deliverables.

---

## 🎯 Project Goals
- Build a functioning AD domain (`cyberopopo.local`).
- Simulate **real-world misconfigurations**.
- Perform **attacks against AD** (Kerberoasting, Pass-the-Hash, etc).
- Implement **defensive monitoring & hardening** with SIEM tools.
- Explore **hybrid AD with Azure AD**.
- Package into a **portfolio-ready showcase**.

---

## 📅 Weekly Roadmap

### **Week 0 — Lab Setup**
- Configure virtualization environment (VMware).
- Create isolated network for lab.
- Install base OS (Windows Server, Windows 10, Windows 11, Kali Linux).

### **Week 1 — Company is Born (Foundation)**
- Deploy Windows Server as Domain Controller (`cyberopopo.local`).
- Add Windows 10 client(s) to the domain.
- Create OUs (HR, IT, Finance).
- Add sample users & groups.
- Apply basic GPOs (password policy, lock screen, drive mapping).

**Deliverables:**
- Setup scripts + screenshots
- `summary.md`: Setup notes
- Optional LinkedIn post: *“Building a Company AD Lab”*

---

### **Week 2 — Company Expands (Misconfigurations)**
- Add users with weak passwords.
- Misconfigure groups & permissions.
- Enable SMBv1, NTLM.
- Create a vulnerable file share.
- Document attack paths.

**Deliverables:**
- Misconfiguration notes
- `summary.md`: Weakness report
- LinkedIn post: *“Common AD Security Mistakes”*

---

### **Week 3 — Red Team Arrives (Offensive Testing)**
- Run BloodHound to map attack paths.
- Use Mimikatz / Rubeus (Kerberoasting, Pass-the-Hash, Golden Ticket).
- Simulate lateral movement.
- Capture “flags” (Domain Admin).

**Deliverables:**
- Attack scripts + screenshots
- `summary.md`: Attack report
- Blog/LinkedIn: *“Active Directory Attacks in My Lab”*

---

### **Week 4 — Blue Team Responds (Defense)**
- Collect AD logs with SIEM (Splunk / Wazuh / ELK).
- Build alerts (failed logins, privilege escalation, odd login times).
- Harden AD (LAPS, disable NTLMv1, enforce GPOs).
- Re-run attacks → show detection/blocking.

**Deliverables:**
- Defense configs
- SIEM dashboard screenshots
- `summary.md`: Detection report
- LinkedIn: *“Defending AD Like a SOC Analyst”*

---

### **Week 5 — Modernization (Hybrid/Cloud AD)**
- Integrate on-prem AD with Azure AD.
- Test SSO & Conditional Access.
- Compare on-prem vs cloud attacks.
- Document improvements.

**Deliverables:**
- Hybrid configs & scripts
- `summary.md`: Cloud notes
- LinkedIn: *“Hybrid Active Directory Security Lab”*

---

### **Week 6 — Final Showcase (Portfolio)**
- Consolidate documentation.
- Create final **PDF report** (*Active Directory Enterprise Security Lab*).
- Polish GitHub repo (README, screenshots, scripts).
- Record optional demo video.

**Deliverables:**
- Complete GitHub repo
- Final PDF report
- LinkedIn portfolio posts
- Optional video demo

---

## 🛠️ Toolset

**Core Infrastructure**
- VMware Workstation / VirtualBox / Hyper-V
- Windows Server 2019/2022 (Domain Controller)
- Windows 10/11 Pro (Clients)
- Kali Linux (Attacker)

**Red Team Tools**
- BloodHound + SharpHound
- Mimikatz / Rubeus
- Impacket, Responder, CrackMapExec, Evil-WinRM
- nmap / Metasploit

**Blue Team Tools**
- Splunk / Wazuh / ELK
- Sysmon (Sysinternals)
- Windows Event Viewer
- Azure Sentinel

**Admin Tools**
- RSAT, ADUC, GPMC, PowerShell
- ADExplorer, ldapsearch

**Documentation**
- GitHub (this repo)
- VS Code / Obsidian / Notion
- Draw.io / Lucidchart
- Markdown → PDF reports

---

