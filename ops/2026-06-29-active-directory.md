# Operational Note

Date: June 29, 2026

Area: Active Directory

Status: Active 

Tags: infrastructure vm management IT support

---

## Objective

Learning Active Directory fundamentals such as:

- AD configuration
- DHCP
- DNS
- GPOs
- OUs
- Domains, Forests

for job-ready IT support skills.

---

## Context

I have a Windows Server 2022 virtual machine on my homelab, accessible via `virt-manager`.
Its roles are AD DS, DNS, DHCP, and File and Storage Services.

---

## Actions

- Configured DHCP for the server
- Promoted the server to domain controller
- Created custom OUs for testing purposes
- Created users and groups inside of those OUs
- Keep user accounts and user's computer separate, with separate computer OUs to prevent future issues
- Created and customized my own group policy and its GPOs, linking it to the OUs created

---

## Observations

- The Windows Server ecosystem is very rich; it's definitely going to take some getting used to at first, but I should get the hang of it within a few consistent days.

---

## Outcome

Things are working well, as I haven't directly touched any moving parts excluding DHCP/DNS during server promotion.

---

## References

Related documents:

- Incident:
- ADR:
- Runbook:
- Architecture:
