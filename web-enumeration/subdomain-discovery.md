# Subdomain Enumeration

Further investigation of the web application suggested the existence of hidden subdomains.

A fuzzing tool was used to discover them.

Command used:

ffuf -w /usr/share/seclists/Discovery/DNS/subdomains-top1million-110000.txt \
-u http://TARGET_IP \
-H "Host: FUZZ.cherryontop.thm"

Discovered subdomain:

nano.cherryontop.thm

This subdomain hosted another web application with additional functionality.
