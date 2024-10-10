# TECHNICAL_TASK-2
Task-2: Linux Based Task - Our task is to develop a Bash script that acts as a Linux command to manage
system resources effectively.

System Management Operations![IMG](https://github.com/user-attachments/assets/01869a64-1dfc-4d7d-bc23-db3b45334d8e)

Part 1 | Level Easy
• List Running Services:
o Command: $ sysopctl service list
o Expected Output: List of all active services, similar to systemctl list-units --
type=service.
• View System Load:
o Command: $ sysopctl system load
o Expected Output: Current system load averages, akin to the output from the
uptime command.
Part 2 | Level Intermediate
• Manage System Services:
o Start a service: $ sysopctl service start <service-name>
o Stop a service: $ sysopctl service stop <service-name>
o Expected Output: Status updates confirming the start or stop of services,
similar to systemctl start/stop.

• Check Disk Usage:
o Command: $ sysopctl disk usage
o Expected Output: Disk usage statistics by partition, similar to df -h.

Part 3 | Advanced Level
• Monitor System Processes:
o Command: $ sysopctl process monitor
o Expected Output: Real-time process activity, akin to top or htop.
• Analyze System Logs:
o Command: $ sysopctl logs analyze
o Expected Output: Summary of recent critical log entries, utilizing tools like
journalctl.
• Backup System Files:
o Command: $ sysopctl backup <path>

o Expected Output: Confirmation of backup initiation and status, potentially
using rsync for file transfers.
