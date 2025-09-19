# Week 0 — Lab Setup

This folder contains documentation, screenshots, and notes for the initial lab environment setup.  
The goal of Week 0 is to prepare a working virtual lab with Windows Server (Domain Controller), Windows 10 clients, and proper networking.  

---

## 🎯 Objectives
- Install and configure a virtualization platform (VMware / VirtualBox / Hyper-V).  
- Deploy a Windows Server VM to act as the Domain Controller.  
- Deploy a Windows 10 Client VM.  
- Configure internal networking between all machines.  
- Take a baseline snapshot for rollback safety.  

---

## 🖥️ Step 1: Virtualization Platform Setup
1. Download and install VMware Workstation / VirtualBox.  
2. Verify installation.  

📸 **Screenshot to include**:  
- Virtualization software installed successfully.  
- New VM wizard screen (choosing Windows Server / Windows 10).  

_Save in `screenshots/vmware_install.png` and `screenshots/new_vm_wizard.png`._

---

## 🖥️ Step 2: Deploy Domain Controller VM (Windows Server 2022)
1. Create a new VM and allocate:  
   - 2 CPUs  
   - 4 GB RAM (minimum)  
   - 60 GB disk space  
2. Install Windows Server 2022.  
3. After first boot, rename the server and verify OS installation.  

📸 **Screenshot to include**:  
- VM settings page (CPU, RAM, storage).  
- First boot screen of Windows Server.  
- Desktop showing server name and OS.  

_Save in `screenshots/dc_vm_settings.png`, `screenshots/dc_firstboot.png`, `screenshots/dc_desktop.png`._

---

## 🖥️ Step 3: Deploy Windows 10 Client VM
1. Create a new VM and allocate:  
   - 2 CPUs  
   - 2 GB RAM (minimum)  
   - 40 GB disk space  
2. Install Windows 10 Pro.  
3. Verify desktop loads correctly.  

📸 **Screenshot to include**:  
- VM settings page (CPU, RAM, storage).  
- Windows 10 installation screen.  
- Windows 10 desktop after install.  

_Save in `screenshots/win10_vm_settings.png`, `screenshots/win10_install.png`, `screenshots/win10_desktop.png`._

---

## 🌐 Step 4: Networking Setup
1. Configure a private/internal network adapter in your virtualization software.  
2. Assign adapters to both Server and Client VMs.  
3. Confirm connectivity inside the Server VM:  
   - Open **Control Panel → Network Connections**.  

📸 **Screenshot to include**:  
- Virtual network adapter configuration.  
- Network connections panel inside Windows Server.  

_Save in `screenshots/network_adapter_vm.png`, `screenshots/network_connections_server.png`._

---

## 📸 Step 5: Create a Baseline Snapshot
1. Power off VMs.  
2. Take a snapshot of both Server and Client in their clean state.  
3. Name snapshots: `Baseline - Fresh Install`.  

📸 **Screenshot to include**:  
- Snapshot manager showing baseline snapshots.  

_Save in `screenshots/baseline_snapshot.png`._

---

## 📂 Folder Structure
