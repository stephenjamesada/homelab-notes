# Operational Note

Date Started: June 25th, 2026

Date Finished:

Area: Provisioning

Status: Active

Tags: cloud-init libvirt vm networking

---

## Objective

Set up cloud-init for Linux VM first boot provisioning, making for faster initial setup on the VM environment.

---

## Context

cloud-init is a command-line tool used for provisioning Linux virtual machines upon their first boot into the system after installation, allowing it to do things such as:

- Running commands
- Installing, upgrading, updating packages

---

## Actions

1. Installed:
    - `cloud-image-utils`
    - `libguestfs-tools`
    - `qemu-utils` (already installed)
2. Created `cloud-init` directory in my home directory and made a subdirectory specifically for the VM.
3. Inside VM directory, created:
    - `meta-data.yml`
    - `network-config.yml`
    - `user-data.yml`
4. Within `user-data.yml`, initialized:
    - Hostname
    - Users (name, groups, shell, and SSH keys)
    - Package update and upgrade
    - Packages to install
    - Timezone
    - Commands to run
