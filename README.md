Cyber Lab 01 – Network Reconnaissance & SSH Attack
Overview

This project simulates a real-world cybersecurity scenario involving:

Network reconnaissance
SSH brute force attack
Log analysis
Defensive mitigation using Fail2Ban

The lab demonstrates both offensive and defensive security techniques in a controlled environment.

Lab Setup
Attacker: Kali Linux
Target: Ubuntu Server (CLI)
Access: SSH from host machine
Network: Internal lab network
Attack Phase
Identified target machine on network
Performed port scanning using Nmap
Simulated SSH brute force attack using Hydra
Detection Phase
Analyzed system logs using:
journalctl
Identified:
multiple failed login attempts
successful authentication after brute force
Defense Phase
Installed and configured Fail2Ban
Set automatic banning after multiple failed attempts
Successfully blocked attacker IP
Key Learnings
Weak credentials are a critical vulnerability
Brute force attacks are easily detectable via logs
Automated defense tools can mitigate attacks effectively
Understanding both attack and defense is essential in cybersecurity
Project Structure
notes.md → analysis and observations
commands/ → all commands used in each phase
Skills Demonstrated
Network scanning (Nmap)
Brute force attack simulation (Hydra)
Log analysis (Linux)
Security hardening (Fail2Ban)
Linux system administration
Disclaimer

This project was conducted in a controlled lab environment for educational purposes only.
