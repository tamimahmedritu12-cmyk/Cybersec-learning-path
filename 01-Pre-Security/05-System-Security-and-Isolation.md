# System Security & Environment Isolation

**Path:** Pre-Security / Core Infrastructure  
**Status:** Completed  

---

##  Rooms Covered
* Operating System Security
* Virtualisation Basics

---

## Key Technical Concepts

### 1. Operating System Security & SSH Authentication
Securing an OS involves protecting system assets from unauthorized manipulation or exposure.
* **Authentication vs Authorization:** Authentication verifies *who* you are; Authorization specifies *what* you can access.
* **SSH (Secure Shell):** Used for secure remote access to systems. 
  * Implements cryptographic keys rather than weak passwords.
  * Private/Public key pair mechanics ensure data confidentiality over untrusted channels.

### 2. Virtualisation Basics
Virtualization enables a single physical machine to run multiple isolated virtual machines (VMs), maximizing hardware efficiency.
* **Hypervisor:** The software layer that abstracts hardware resources.
  * *Type 1 (Bare-Metal):* Runs directly on physical hardware (e.g., ESXi, Proxmox).
  * *Type 2 (Hosted):* Runs on top of an existing OS (e.g., VirtualBox, VMware Workstation).
* **Isolation:** If a VM gets compromised by malware, the threat is safely contained within that virtual container and cannot easily damage the host machine.

---

##  Key Takeaway for Cybersecurity
Virtualization is the backbone of malware analysis and safe security testing. Creating sandbox environments via VMs prevents malware from spreading to the production network.
