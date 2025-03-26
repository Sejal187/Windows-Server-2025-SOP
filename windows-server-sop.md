# Standard Operating Procedure (SOP)

# Windows Server 2025 Preperation

**Company Name:** MITT
**Address:** 130 Henlow Bay
**Contact:** 204-998-6500

**Version:** 1.0
**Written by:** Sejal
**Approved by:** Felix Liang
**Date:** 26/03/2025

---

## Purpose
1. This document summarizes the steps required for preparing and congiguring a Windows Server 2025 efficiently.
2. It ensures consistency, security, and compliance across all installations.

## Application
1. This SOP is applicable to IT administrators responsible for deploying Windows Server 2025 in a production or test environment.

## Definations
- **Active Directory (AD)**: A directory service for user authentication and management.
- **Domain controller (DC)**: Aserver managing security authentication in an AD environment.
- **Group Policy (GPO)**: A tool for configuring and managing Windows Settings across a network.
- **Dynamic Host Configuration Protocol (DHCP)**: Assign IP addresses to network devices.

---

## Procedure Steps

### **Step 1: System Requirement Check**
- **Processor:** 64-bit
- **RAM:** Minimum 16 GB
- **Network Adapter:** 1 Gbps or higher
- **Storage:** 100 GB

### **Step 2: Download and Install Server 2025**
1. Download the latest Windows Server 2025 ISO Image from the **Microsoft Website**

### **Step 3: Configure Initial Settings**
1. Set an administrator password.
2. Assign Unique hostname
3. Enable Remote Desktop Proocol (RDP) and configure Firewall rules.

### **Step 4: Network Configuration**
1. Set up a static IP address or Configure DHCP.
2. Configure DNS Settings.
3. Ensure firewall rules allow necessary services.

### **Step 5: Install and Configure Roles**
1. Open Server Manager > "Add Roles and Features."
2. Install required roles:
   - Active Directory Domain Services (AD DS)
   - File and Storage Services
3. Promote server to a Domain Controller.

### **Step 6: Apply Security Best Practices**  
1. Enable Windows Defender Antivirus
2. Enforce MFA for administrator accounts.
3. Disable unnecessary services and ports.
4. Set up regular backups and store them securely

---

## Resources
1.  [Microsoft Windows Server 2025 Documentation](https://docs.microsoft.com)
2.  [Active Directory Setup Guide](https://learn.microsoft.com/en-us/windows-server/identity/active-directory-domain-services)

---

**END OF DOCUMENT**


