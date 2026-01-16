# HomeLab
Windows domain lab - DC01 + CLIENT01 - Screenshots and documentation
# HomeLab – Windows Domain Lab

This repository contains my self-directed home lab demonstrating a **Windows Server Domain Controller (DC01)** and a **Windows 10 Pro client (CLIENT01)** joined to the domain.  

---

## Lab Overview

- **Virtualization Platform:** Oracle VirtualBox  
- **Domain Controller:** DC01 – Windows Server 2019/2022  
- **Client Machine:** CLIENT01 – Windows 10 Pro  
- **Domain Name:** homelab.local  
- **Network:** Host-Only network with static IPs and DNS pointing to DC01  

---

## Objectives

1. Build and configure a Windows Server Domain Controller.  
2. Configure DNS on DC01 for proper name resolution.  
3. Build a Windows 10 client VM and join it to the domain.  
4. Verify connectivity and domain membership.  
5. Document all steps with screenshots.  

---

## Screenshots / Evidence

| Step | Screenshot | Description |
|------|------------|-------------|
| 1 | Screenshots/Windows_installation.png | Initial Windows installation in VirtualBox, showing the base operating system setup for the lab environment |
| 2 | Screenshots/DC01_Domain_controller.png | Windows Server configured and promoted to a **Domain Controller** for the `homelab.local` domain |
| 3 | Screenshots/Creating_administrator_account.png | Creation and configuration of the **Domain Administrator account** during Active Directory setup |
| 4 | Screenshots/Users_setup_on_domain.png | Domain user accounts configured within **Active Directory** |
| 5 | Screenshots/CREATED_New_Users&Groups.png | Additional users and groups created in **Active Directory Users and Computers (ADUC)** |
| 6 | Screenshots/CLIENT01_IP_DNS.png | CLIENT01 configured with a **static IP address** and **DNS pointing to DC01** |
| 7 | Screenshots/CLIENT01_DOMAIN_Properties.png | CLIENT01 successfully joined to the `homelab.local` domain (System Properties → Domain) |
| 8 | Screenshots/DC01_ADUC_CLIENT01.png | CLIENT01 computer account visible in **Active Directory Users and Computers**, confirming successful domain join |

---

## Lab Summary

A full **lab summary PDF** is included with detailed steps, architecture, and skills demonstrated:

**File:** `Home LabSummary_Finlay.pdf`  

---

## Skills Demonstrated

- Active Directory installation and management  
- DNS configuration for domain clients  
- Windows networking with static IPs and Host-Only network  
- Domain join and verification  
- VirtualBox virtualization and VM setup  
- Documentation and professional lab reporting  

---

## Usage

You can download the screenshots and lab summary PDF for reference. This portfolio demonstrates practical IT skills relevant for **IT support, system administration, and cybersecurity applications**.

---

