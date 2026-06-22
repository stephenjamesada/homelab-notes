# homelab-notes

## Purpose

Operational and architectural documentation for my personal Linux homelab.

The purpose of this repository is to track how this system is designed, operated, and maintained.

---

## What this is / isn't

### This is

Documentation for:

- Architecture
- Operational runbooks
- Incident reports
- Troubleshooting logs
- Architecture Decision Records (ADRs)
- Retrospectives and change tracking

### This is not

- IaC / Infrastructure-as-Code (see [homelab-infrastructure](https://github.com/stephenjamesada/homelab-infrastructure))
- Scripts/automation tooling (see [scripts](https://github.com/stephenjamesada/scripts))
- System configuration files (see [dotfiles](https://github.com/stephenjamesada/dotfiles))

---

## How to use this repo

### Writing new document

1. Copy a template from `_templates`
2. Place into the right folder
3. Follow the format strictly, but keep the content concise

Example:

```bash
cp _templates/incident.md incidents/2026-06-ssh-lockout.md
```
