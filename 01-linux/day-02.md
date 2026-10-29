
# Day 2 — Linux Administration & Permissions

## Lab Environment
- Platform: Proxmox VE
- Container: cloud-lab
- Operating System: Debian 13
- CPU: 2 cores
- RAM: 2 GB
- Storage: 16 GB
- Networking: vmbr0 (DHCP)

## What I Learned

### 1. Linux Networking
- Used `ip addr` to identify network interfaces and IP addresses.
- Tested connectivity using `ping`.
- Learned how DNS resolves domain names into IP addresses.
- Explored Linux networking and Proxmox bridges.

### 2. Logs & SSH Troubleshooting
- Explored `/var/log` and system logs.
- Used `journalctl` to investigate service activity.
- Checked SSH status using `systemctl status ssh`.
- Learned that a running service doesn't guarantee network connectivity.

### 3. File Permissions
- Learned how Linux uses read (4), write (2), and execute (1) permissions.
- Used `chmod` to configure file permissions.
- Practiced permission values `777` and `640`.
- Learned why excessive permissions can create security risks.

### 4. User Management & Ownership
- Created a Linux user named `developer`.
- Used `id` and `whoami` to inspect user information.
- Used `chown` to change file ownership.
- Used `su - developer` to switch users.
- Verified that Linux enforces directory permissions.

## Challenges & Troubleshooting
- Corrected command syntax errors using `--help`.
- Investigated SSH service logs.
- Learned why a user can own a file but still be denied access to its parent directory.
- Tested file access as a non-root user.

## Key Takeaway
Linux administration involves understanding how users, permissions, services, and networking interact. I practiced troubleshooting problems rather than simply memorizing commands.

## Status
Completed
