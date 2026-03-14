# Network Enumeration

The first step was to scan the target machine to identify open ports and services.

Command used:

nmap -sC -sV -p- TARGET_IP

Results:

22/tcp  open  ssh
80/tcp  open  http

This indicates that the target machine exposes:

- SSH service
- Web server

Next step was to add the provided hostname to the hosts file.

Command used:

sudo nano /etc/hosts

Entry added:

TARGET_IP cherryontop.thm
