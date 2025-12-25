# Windows Cross-Domain Mail System
Enterprise style Windows Server 2022 mail infrastructure using two virtual machines acting as separate organizations. Includes Active Directory, DNS, and Exchange Server 2019 with verified cross domain email delivery using SMTP, POP3, and IMAP4.
## Key Features

- Two Windows Server 2022 virtual machines simulating separate organizations
- Independent Active Directory forests and DNS infrastructure
- Microsoft Exchange Server 2019 deployed on each server
- Cross-domain email delivery using SMTP
- Client access tested using POP3 and IMAP4
- Mail flow verified using Outlook Web Access (OWA) and Thunderbird

## Architecture Overview

- VM 1: Windows Server 2022  
  - Active Directory Domain Services  
  - DNS  
  - Exchange Server 2019  

- VM 2: Windows Server 2022  
  - Active Directory Domain Services  
  - DNS  
  - Exchange Server 2019  

Each virtual machine represents a separate organization with no shared domain or forest.

This project demonstrates real world enterprise concepts such as cross domain mail flow, isolated directory services, and multi protocol email access. It reflects practical system administration skills used in corporate environments rather than single-server lab setups.
