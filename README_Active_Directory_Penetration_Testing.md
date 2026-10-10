# Active Directory Penetration Testing with Impacket

**Author:** Pedro Gonçalves  
**Category:** Active Directory Security · Ethical Hacking · Penetration Testing  
**Environment:** Authorized, isolated cybersecurity laboratory

## Project overview

This hands-on project documents the assessment of an Active Directory environment using Kali Linux and the Impacket toolkit. It explores domain enumeration, computer-account creation permissions, resource-based constrained delegation (RBCD), Kerberos ticket workflows, and AS-REP roasting, alongside defensive configuration checks.

The report contains terminal screenshots, PowerShell examples, findings and laboratory observations. All exercises are presented as work conducted in a controlled training environment.

## Laboratory architecture

| Component | Role |
| --- | --- |
| Kali Linux | Assessment workstation running Impacket |
| Windows Server / Active Directory | Domain controller and identity services |
| Kerberos, LDAP, SMB, RPC | Protocols assessed in the lab |
| PowerShell | Configuration review and defensive validation |

## Topics documented

- Active Directory account, group, computer and SID enumeration
- Understanding `ms-DS-MachineAccountQuota` and its security implications
- Review and mitigation of computer-account creation permissions
- Resource-based constrained delegation (RBCD) concepts and lab testing
- Kerberos S4U workflows and service-ticket handling
- Remote execution and privilege-context validation in the lab
- AS-REP roasting exposure and pre-authentication controls
- Detection and hardening considerations for Active Directory

## Security lessons

The exercises illustrate why delegated permissions, machine-account quotas, Kerberos configuration and privileged access should be audited regularly. The report includes both offensive demonstrations and defensive configuration examples. Some lab steps reflect intentionally insecure settings and must **not** be used as production configuration guidance.

## Technical report

[View the full PDF report](Active_Directory_Penetration_Testing_Impacket_Pedro_Goncalves.pdf)

> **Publication note:** The PDF has been reformatted to remove the institutional page headers and footers. Review the embedded terminal screenshots before public release; they may still contain lab account names, example credentials, or other identifying information.

## Tools and technologies

`Active Directory` · `Impacket` · `Kali Linux` · `Windows Server` · `Kerberos` · `LDAP` · `SMB` · `RPC` · `PowerShell` · `RBCD` · `AS-REP Roasting`

## Responsible use

This project is intended exclusively for education and authorized security testing. Never apply these techniques to systems without explicit permission.

## Author

**Pedro Gonçalves** — Networking & Cybersecurity Portfolio  
[GitHub profile](https://github.com/PedroGoncalves28286)
