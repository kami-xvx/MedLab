# MedIT-Lab

Windows Server infrastructure homelab focused on Active Directory, DNS, DHCP, Group Policy,
domain workstations, SMB file services and database infrastructure.

## Current infrastructure

- **DC01** - Active Directory Domain Services, DNS, DHCP, GPO
- **CLIENT01** - Windows 11 Enterprise domain workstation
- **FS01** - Windows Server file server with SMB and NTFS permissions
- **SQL01** - Windows Server 2025 database server with Microsoft SQL Server 2025 and SSMS 22

## Project status: Work in Progress

Current stage: SQL Server deployment and database administration

> **2026-09-01:** selected screenshots documenting major infrastructure implementation milestones.

> **2026-09-09:** added SQL01 (Windows Server 2025), joined to `medlab.test`, configured MEDLAB-LAN connectivity and verified DNS/DC communication.

> **2026-09-10:** organized full implementation evidence into VM- and snapshot-based timelines.

> **2026-09-10:** restored SQL01 domain trust and verified Group Policy operation after secure channel recovery.

> **2026-09-10:** completed SQL Server 2025 and SQL Server Management Studio 22 deployment on SQL01. Verified Windows Authentication using `MEDLAB\Administrator` and confirmed `sysadmin` access to the `MSSQLSERVER` instance.

Domain: `medlab.test`