# Encrypted-Bind-Shell
This Python program creates a bind shell after being executed on a target server. This was made as part of TCM Security's Python 201 for Hackers course!

# Purpose
This tool is used to execute commands on a server that is hosting the server portion of this bind shell program. This is more secure than a typical bind shell as it uses encryption to encrypt commands and output across the network.

# Requirements
All required libraries are in requirements.txt.

# Usage
This Python script is designed exclusively for authorized security testing and penetration testing purposes to assess the strength of Windows systems, and should only be used with explicit permission from the system owner; any unauthorized or illegal use for malicious hacking attempts is strictly prohibited and may result in severe legal consequences. To use this tool, run `python Encrypted-Bind.py -l` in a terminal to set up a listener. You will then be given a key. To connect to the server hosting the shell, run `python Encrypted-Bind.py -c <SERVER_IP> -k <KEY_FROM_SERVER>`.
