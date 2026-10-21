# homelab-active-directory

Active Directory lab on Windows Server 2022 running on Proxmox VE. Part of the [homelab](https://github.com/Canyanwu/homelab) project.

## Status

| Item | Status |
|---|---|
| Domain controller (Windows Server 2022, AD DS, DNS) | Built |
| OU structure and 90 users provisioned with PowerShell | Built |
| Windows 11 domain joined client | Built |
| Hardening baseline (SMB and LDAP signing, LLMNR and NetBIOS off, LAPS) | In progress |
| Second domain controller | Planned |
| Fine grained password policies | Planned |
| Wazuh monitoring of domain controllers | Planned |

## Contents

- [docs/hardening.md](docs/hardening.md): hardening checklist with evidence for each item
- scripts/: PowerShell used in this lab (add each script with a short README)

## Rules for this repo

- A box is ticked only when the change is applied and verified.
- No passwords, hostnames or addresses are committed.
