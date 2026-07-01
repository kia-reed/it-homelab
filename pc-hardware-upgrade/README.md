# PC Hardware Upgrade & Build Project

![Type](https://img.shields.io/badge/type-Hardware%20Build-1679A7)
![Focus](https://img.shields.io/badge/focus-CPU%20%C2%B7%20RAM%20%C2%B7%20Storage%20%C2%B7%20PSU-0F6E56)
![Skills](https://img.shields.io/badge/skills-Install%20%C2%B7%20BIOS%20%C2%B7%20Troubleshooting-534AB7)
![Status](https://img.shields.io/badge/status-Completed-1D9E75)

A hands-on project where I upgraded and stabilized a desktop PC end to end — replacing the CPU (Central Processing Unit — the computer's main processor), doubling the RAM (Random Access Memory — the short-term working memory a computer uses for active tasks), adding NVMe (Non-Volatile Memory Express — a fast type of solid-state storage) storage, swapping a failing power supply, and configuring the BIOS (Basic Input/Output System — the low-level firmware that starts the hardware before Windows loads). This is the hardware layer underneath everything my cloud and security labs run on: the physical machine.

> **Why this belongs in an IT/cloud portfolio:** my [it-homelab labs](../) build software and cloud skills *on top of* a machine; this project is the machine itself. Understanding how a computer works at the hardware level — processors, memory, storage, power, firmware — reinforces the infrastructure knowledge behind Infrastructure as a Service (IaaS) and any systems, cloud, or security role.

---

## Why this matters

Every server, virtual machine (VM — a computer running as software inside another computer), and cloud instance is, at the bottom, physical hardware — a processor, memory, storage, and power. Knowing how those pieces fit together, how to diagnose when one fails, and how to configure firmware is foundational IT support and systems knowledge. This project also involved real troubleshooting under uncertainty, which is the core skill of any technical role.

| Role | How this project applies |
|------|--------------------------|
| IT Support / Help Desk | Diagnosing and replacing failed hardware, managing storage, configuring BIOS |
| Systems Administrator | Understanding the physical layer beneath operating systems and virtualization |
| Cloud / Infrastructure Engineer | The same components (CPU, memory, storage, power) are what cloud providers rent as Infrastructure as a Service (IaaS) |

---

## What I did

**CPU (Central Processing Unit) upgrade.** Replaced a Ryzen 3 3100 with a Ryzen 5 5600 and verified the new processor was recognized in the BIOS (Basic Input/Output System). *What it shows:* comfort opening the machine, seating a processor correctly, and confirming the hardware change at the firmware level before booting Windows.

**RAM (Random Access Memory) upgrade.** Installed 32 GB of DDR4 (Double Data Rate 4 — a generation of RAM) as 2×16 GB, doubling the system's multitasking capacity. *What it shows:* matching and installing memory modules and confirming the capacity registered.

**Storage expansion.** Added a 2 TB NVMe (Non-Volatile Memory Express) SSD (Solid-State Drive — storage with no moving parts), then initialized and formatted it in Windows and redirected Downloads, OneDrive, Documents, Pictures, and Videos to the new D: drive. *What it shows:* storage management end to end — physical install, Windows disk initialization, and reorganizing where data lives so the system drive stays lean.

**Power supply (PSU — Power Supply Unit) replacement.** Replaced an unstable PSU that was causing random shutdowns, restoring system stability. *What it shows:* identifying power as the root cause of instability and safely swapping the component that feeds the whole system.

**System optimization.** Enabled DOCP (Direct Over Clock Profile — a setting that runs the RAM at its rated speed) for the memory, verified stable CPU (Central Processing Unit) temperatures, and configured new applications to install to the D: drive. *What it shows:* tuning firmware settings and managing where software lands to keep the primary drive free.

---

## Troubleshooting (the real diagnostic work)

This is the part that mattered most — real problems solved under uncertainty.

- **"No Signal" GPU (Graphics Processing Unit — the component that drives the display) issue.** After a hardware change the monitor showed no signal. I diagnosed and resolved it to get the display working again — the kind of "it won't even boot to a screen" problem that stops most people cold.
- **Unstable power supply causing shutdowns.** The system was randomly shutting down. I traced the instability to the PSU (Power Supply Unit) rather than software, and replacing it restored stability — correctly isolating a hardware root cause instead of chasing the wrong layer.
- **C: drive nearly full.** Expanded free space on the system drive from roughly 90 GB to 334 GB by reorganizing storage and redirecting data to the new 2 TB drive — turning a cramped, at-risk system drive into a healthy one.

---

## End result

| Drive | Role | Free space |
|-------|------|------------|
| **C: (500 GB SSD)** | Windows and applications only | Over 300 GB free |
| **D: (2 TB SSD)** | All storage — OneDrive, downloads, media, personal files | 2 TB |

The finished system is faster, more stable, and future-proofed: the failing power supply is gone, the processor and memory are upgraded, and storage is organized so the system drive stays healthy.

---

## Skills demonstrated

- Installing and verifying a CPU (Central Processing Unit)
- Installing and matching RAM (Random Access Memory) modules
- Physically installing and initializing an NVMe (Non-Volatile Memory Express) SSD (Solid-State Drive) in Windows
- Replacing a PSU (Power Supply Unit) and identifying power as a root cause of instability
- Configuring the BIOS (Basic Input/Output System), including enabling DOCP (Direct Over Clock Profile) for memory
- Storage management — redirecting user folders and expanding system-drive free space
- Hardware troubleshooting — diagnosing a "No Signal" display fault and an unstable power supply

## What I learned

- The physical layer underneath every operating system and cloud instance: processor, memory, storage, power, and the firmware that ties them together.
- How to isolate a hardware root cause — power instability, a display fault — rather than assuming the problem is software.
- How storage organization keeps a system healthy: a lean system drive plus a large data drive.
- The confidence to open a machine and change core components independently.

## How this connects

This is the hardware foundation beneath my [it-homelab labs](../) — those labs build identity, network, and security skills on virtual machines in the cloud, and this project is the physical machine those same skills run on. The components I installed here (CPU, memory, storage, power) are exactly what cloud providers rent out as Infrastructure as a Service (IaaS), so understanding them at the hardware level reinforces the cloud infrastructure knowledge behind an Identity and Access Management (IAM) or cloud security path.

