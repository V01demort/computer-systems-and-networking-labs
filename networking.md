# Classroom networking and DHCP

[Back to overview](README.md)

## Context

Practices 4–6 covered classroom LAN setup, switch management, IP cameras, DHCP, FTP and IIS. My designated role in Practice 6 was **DHCP Expert**. The following notes summarize the networking work reported during the course.

## Practical work

- Configured dynamic IP addressing in the classroom LAN.
- Checked host IP configuration using `ipconfig`.
- Used `ping` to check connectivity and PuTTY/Telnet for switch management exercises.

## Diagnostic reference

| Tool or concept | Purpose |
| --- | --- |
| `ipconfig` | View IPv4 configuration. |
| `ipconfig /all` | Inspect adapter details, DHCP state and addressing information. |
| `ping` | Test IP reachability to a specified host. |
| DHCP lease list | Check assigned addresses and associated client identifiers. |
| PuTTY / Telnet | Access supported management interfaces in an authorized lab. |

A typical classroom troubleshooting workflow is to check the physical connection, inspect IP settings, confirm the addressing scheme and then test reachability. A failed ping alone does not establish that a device is offline; firewall rules or routing can also affect the result. Telnet is a legacy plaintext protocol; SSH is preferred for modern management where supported.

## Evidence

These notes are a retrospective summary, not a reproduced session log. No verified DHCP lease table or successful connectivity screenshot is available for publication. Actual lab addresses and credentials are omitted. FTP, IIS and camera configuration are not presented as independently demonstrated achievements.
