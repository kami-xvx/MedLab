@"
# MedLab

Windows Server infrastructure homelab focused on Active Directory, DNS, DHCP, Group Policy, domain workstations and SMB file services.

## Current infrastructure

- DC01 - Active Directory Domain Services, DNS, DHCP, GPO
- CLIENT01 - Windows 11 Enterprise domain workstation
- FS01 - Windows Server file server with SMB and NTFS permissions

Domain: medlab.test
"@ | Set-Content ".\README.md"