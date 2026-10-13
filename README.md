# MedIT-Lab

Windows Server infrastructure homelab focused on Active Directory, DNS, DHCP, Group Policy, domain workstations, SMB file services, and database infrastructure.

**Environment:** Oracle VirtualBox | Windows Server 2025 | Windows 11 Enterprise  
**Domain:** `medlab.test`

## Featured Presentation

### Secure Resource Sharing in Corporate Networks (SMB)

**[View SMB Case Study — UBB 2026 (PDF)](Presentations/MedIT_Lab_SMB_SOII.pdf)**

Academic presentation for *Operating Systems II*, documenting SMB shares, Active Directory group-based permissions (AGDLP), NTFS ACLs, and access-control tests performed in MedIT-Lab.

## Current Infrastructure

| System | Role |
|---|---|
| **DC01** | Active Directory Domain Services, DNS, DHCP, GPO |
| **CLIENT01** | Windows 11 Enterprise domain workstation |
| **FS01** | Windows Server file server with SMB and NTFS permissions |
| **SQL01** | Windows Server 2025 with SQL Server 2025 and SSMS 22 |

## Project Status: Work in Progress

**Current focus:** SQL Server administration, SMB access control, and infrastructure maintenance.

**2026-09-01:** Selected screenshots documenting major infrastructure implementation milestones.

**2026-09-09:** Added SQL01, joined it to `medlab.test`, configured MEDLAB-LAN connectivity, and verified DNS/DC communication.

**2026-09-10:** Organized implementation evidence into VM- and snapshot-based timelines. Restored SQL01 domain trust and verified Group Policy operation.

**2026-09-10:** Completed SQL Server 2025 and SSMS 22 deployment. Verified Windows Authentication and administrative access to the SQL Server instance.

**2026-10-12:** Completed SMB access-control documentation, including AGDLP, share permissions, NTFS ACLs, and user access tests.

**2026-10-13:** Finalized the SMB presentation for UBB. DC01 is currently undergoing AD DS recovery diagnostics; a recovery copy has been prepared.

## Documentation

- [Implementation Evidence](Evidence/Timelines/)
- [SMB Presentation (PDF)](Presentations/MedIT_Lab_SMB_SOII.pdf)

---

**MedIT-Lab** — Windows Infrastructure · Active Directory · Networking · Security

*Independent educational project | UBB 2026*