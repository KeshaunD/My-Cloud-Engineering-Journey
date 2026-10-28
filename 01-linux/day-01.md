# Day 1 — Linux Fundamentals & Troubleshooting

## What I Learned

- Learned how to identify resource usage across running Linux processes.
- Practiced troubleshooting slow or unresponsive applications using process information and system logs.
- Learned how to investigate service failures and look for potential root causes.
- Learned the difference between an enabled service (configured to start at boot) and an active service (currently running).
- Learned that high CPU usage doesn't automatically mean an application is malfunctioning.

## Commands I Practiced

- `top` — Displays running processes and real-time CPU and memory usage.
- `ps` — Displays information about running processes, including their PIDs.
- `free -h` — Displays system memory usage in a human-readable format.
- `grep` — Searches and filters text, including process information.
- `systemctl` — Checks and manages Linux services, including their current state.
- `journalctl` — Reviews system and service logs to investigate errors.

## Troubleshooting Exercise

Used my Proxmox Linux server to inspect running processes, monitor resource utilization, and review service logs.

Also completed a simulated AWS EC2 troubleshooting scenario involving an unresponsive Python application. Investigated the application's service status and logs, which indicated a database connection failure.

Determined that checking the database service and its logs would be the next troubleshooting step before attempting a restart.

## Key Takeaways

This lesson introduced me to essential Linux troubleshooting commands and helped me understand how processes, services, and logs work together.

My biggest takeaway was the importance of investigating the evidence before restarting services or making changes to a system.