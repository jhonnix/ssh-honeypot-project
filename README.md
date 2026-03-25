# SSH Honeypot Project

## Overview
This project demonstrates the deployment of an SSH honeypot to monitor and capture unauthorized login attempts. The honeypot records attacker IP addresses, usernames, passwords, and commands used during attacks.

## Objective
The goal of this project is to understand how attackers attempt to access systems and analyze the captured data for cybersecurity learning.

## Tools Used
- Kali Linux
- Cowrie SSH Honeypot
- Linux Terminal
- GitHub

## Project Setup
1. Install Cowrie honeypot
2. Configure the honeypot settings
3. Start the honeypot service
4. Monitor attacker activity through logs

## Sample Commands

Clone Cowrie repository

```
git clone https://github.com/cowrie/cowrie.git
```

Start the honeypot

```
bin/cowrie start
```

View attack logs

```
tail -f var/log/cowrie/cowrie.log
```

## Attack Data Collected
The honeypot captures the following data:

- Attacker IP Address
- Username attempts
- Password attempts
- Commands executed

## Learning Outcome
From this project I learned:

- How SSH brute force attacks work
- How honeypots capture attacker activity
- Basic log monitoring and analysis
- How to deploy cybersecurity monitoring tools

## Screenshots
Screenshots of the honeypot running and captured logs can be found in the **screenshots** folder.

## Author
Jhonn Peter Capz  
Cybersecurity Enthusiast | Ethical Hacking Learner

https://github.com/user-attachments/assets/604d7dfb-bfe6-4ebe-88d9-c791613278e5

