### Initial Enumeration
A TCP port scan was performed against the target machine to identify exposed services.

**Command:**
nmap -sV -sC -O -A -p- <TARGET_IP>

The scan was executed using default NSE scripts and service version detection to gather information about running services.
