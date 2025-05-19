# VMware Enterprise Project 🖥️
This project simulates a small enterprise IT environment using **VMware Workstation** and **Windows Server 2022**. It includes a fully configured **Active Directory domain**, DNS server, file sharing, organizational units, GPOs, and mapped drives.

The goal of this project is to **learn system administration, domain infrastructure, and Windows-based enterprise networking** in a virtual lab environment.

---

## 📁 Lab Overview

| VM Name          | Role                          | OS                 | IP Address     | Notes                                      |
|------------------|-------------------------------|--------------------|----------------|--------------------------------------------|
| WIN-DC01         | Domain Controller, DNS        | Windows Server 2022| 192.168.50.10  | Primary DC for lab.local domain            |
| WIN-MEMBER01     | File Server, Test Member      | Windows Server 2022| 192.168.50.11  | Shared folders with GPO mapped drives      |
| WIN11P-ADMIN01   | Admin Workstation             | Windows 10 Pro     | 192.168.50.12  | RSAT, scripting tools, admin user          |
| WIN11P-HR01      | HR Workstation                | Windows 10 Pro     | 192.168.50.13  | HR department user                         |
| WIN11P-ACC01     | Accounting Workstation        | Windows 10 Pro     | 192.168.50.14  | Accounting domain user                     |
| WIN11P-IT01      | IT Workstation                | Windows 10 Pro     | 192.168.50.15  | IT department domain user                  |
| Linux-Web01      | Web Server                    | Ubuntu Server 22.04| 192.168.50.16  | Apache server, SSH                         |
| Linux-Client01   | Testing, Scripts, Monitoring  | Debian/CentOS      | 192.168.50.17  | SSH enabled, test crons, logging, scripts  |
---------------------------------------------------------------------------------------------------------------------------------------

📄 Full details: [`docs/VMware_Lab_Spreadsheet.xlsx`](docs/VMware_Lab_Spreadsheet.xlsx)

## ⚙️ Features Implemented so far

- ✅ Active Directory Domain (`lab.local`)
- ✅ DNS and DHCP setup on `WIN-DC01`
- ✅ File server with shared folders (`AdminShare$`)
- ✅ GPOs for mapped drives and folder redirection
- ✅ OU and group-based permissions (`HR_Folder_Access`, etc.)
- ✅ User accounts for HR, IT, Accounting
- ✅ Workstations domain-joined and tested
- ✅ PowerShell scripts for automation (coming soon)

> 📂 See `progress.md` folder for more detail

---

## 🖼️ Screenshots

> 📂 See `screenshots/` folder for setup images


---

## 🧠 Skills Demonstrated

- System Administration (AD, DNS, GPOs)
- Network Configuration and Testing
- VMware Workstation & NAT Networking
- Windows Server Roles and Features
- User/Group Management
- PowerShell Scripting (in progress)
- Documentation and IT Project Management

---

## 🔗 GitHub Repository Contents

| Folder          | Description                             |
|-----------------|-----------------------------------------|
| `/docs/`        | Lab spreadsheet and documentation       |
| `/screenshots/` | Images of server setup and configuration|
| `/scripts/`     | PowerShell/automation scripts (coming)  |
| `README.md`     | Current File opened                     |
| `progress.md`   | Progress File (Work in progress / Done) |
-------------------------------------------------------------

## 📬 Contact

**Daniel Guerra**  
Aspiring Systems Engineer | Dominican University
[LinkedIn Profile](www.linkedin.com/in/daniel-guerra-7a542b360)  
Email: danielguerra11@att.net

---