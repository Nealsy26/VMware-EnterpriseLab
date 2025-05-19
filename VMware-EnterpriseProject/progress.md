## 🏗️ Project Development Phases

---

- ✅ Completed  
- 🟡 In Progress or Planned  
- ❌ Not Started

---

### ✅ PHASE 1: Strengthen Core Infrastructure  
*Simulating basic enterprise IT functions*

- ✅ Domain Controller (`WIN-DC01`): Active Directory + DNS roles configured  
- ✅ Member File Server (`WIN-MEMBER01`): File sharing and test member setup  
- ✅ User Accounts: HR, IT, and Accounting department users created  
- ✅ Role-Based GPOs: Applied to groups like `Managers`, `Interns`, etc.  
- ✅ Shared Folders & Permissions: NTFS and share-level permissions configured  

---

### 🛠️ PHASE 2: Expand with Essential Services  
*Building out automation, security, and realistic enterprise policies*

- ✅ DHCP Server: Automates IP address assignment (`Client-Scope`)
- ✅ Organizational Units (OUs): Better structure for GPOs and access control (`IT, ACC, HR`) 
- ✅ Fine-Tuned GPOs: Drive mapping, desktop lockdown, restrictions (``)
- 🟡 Logon Scripts / PowerShell Automation: Automate logon tasks like drive mapping  
- 🟡 Audit Policies + Event Logging: Monitor user activity and login events  
- ❌ BitLocker Encryption via GPO: Enable encryption on endpoints 
- 🟡 Printer Deployment via GPO: Distribute shared printers  
- 🟡 Password Policies + Account Lockouts: Strengthen login security  

---

### 🔒 PHASE 3: Cybersecurity & Compliance Simulation  
*Securing access and demonstrating industry-aligned configurations*

- ❌ Firewall Config + Defender GPO: Add endpoint protection by role  
- ❌ Restricted Admin Access: Role-based access control (RBAC) via groups  
- ❌ Security Baseline Templates (`CIS`/`SCB`): Enforce compliance configurations  
- ❌ Scheduled Backups: Use Windows Server Backup to simulate recovery  

---

### 📡 PHASE 4: Networking & Enterprise Services Expansion  
*Simulating real-world failover, patching, and remote services*

- ❌ Secondary DNS Server: Add DNS redundancy  
- ❌ Time Server (`NTP`): Ensure accurate logging and Kerberos sync  
- ❌ `WSUS` (Windows Server Update Services): Manage updates internally  
- ❌ VPN Setup (`RAS`): Simulate secure remote access  
- ❌ `IPSec` / SMB Signing: Encrypt and protect SMB traffic  

---

### 🧰 PHASE 5: Dev/Test Automation & Documentation  
*Adding portfolio-quality polish and automation tools*

- ❌ Self-Written PowerShell Tools: Scripts to automate reports or account tasks  
- 🟡 Documentation & GitHub Changelog: Track changes, diagrams, and screenshots  
- ❌ Internal Web Portal (`Apache` or `IIS`): Host HR announcements or internal helpdesk  

---