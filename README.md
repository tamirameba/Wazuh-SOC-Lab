Wazuh SOC Lab

Personal hands-on lab built to practice threat monitoring and log analysis using Wazuh SIEM/EDR.

Lab Architecture:

Wazuh Server: 172.20.10.11

Monitored Endpoint: Windows 10 VM

Hypervisor: VirtualBox on macOS

Scenario 1: Authentication Monitoring

What I Did:
Simulated failed login attempts on the Windows 10 VM using wrong passwords, followed by a successful login.

Results in Wazuh:
Failed Logins: Captured as Level 5 severity (Rule ID: 60122).
Successful Login: Captured as Level 3 severity (Rule ID: 60118).

Screenshot
Authentication Logs (images/logon_events.
