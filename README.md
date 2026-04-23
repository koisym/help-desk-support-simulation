# Help Desk Support Simulation

## Overview

I built this project to get more hands-on practice with the kinds of issues commonly handled in "everyday" IT support roles. The goal was to work through realistic support tickets in a Windows environment, use standard troubleshooting tools, and document the process clearly.

The focus of this lab was on common user problems such as slow performance, network connectivity, password reset/account assistance, and printer support.

---

## Objective

The objective of this project was to strengthen my troubleshooting process, become more comfortable with Windows support tools, and practice documenting issues the way they would be handled in a real support environment.

---

## Lab Environment

This lab was completed in a virtual machine using:

- Windows 11
- VirtualBox
- Command Prompt
- Task Manager
- Services
- Control Panel
- Windows Settings

---

## Support Scenarios Completed

### 1. Slow Computer

A user reported that the computer was running slowly.

**What I Checked**
- Opened Task Manager
- Reviewed CPU and memory usage
- Looked for applications using high resources <img width="763" height="568" alt="slow-computer-ticket" src="https://github.com/user-attachments/assets/ed1004ec-f3c5-43d5-88c9-7ba3e0557ec5" />
- Reviewed startup programs <img width="756" height="576" alt="slow-computer-ticket-2" src="https://github.com/user-attachments/assets/5e591ed4-b70d-4cf5-a71c-9eb0636db39b" />

**Resolution**
Closed unnecessary applications and reviewed startup items that could affect performance.

---

### 2. Network Connectivity Issue

A user reported internet problems.

**What I Checked**
- Verified the network adapter was connected <img width="709" height="184" alt="network-ticket-adapter-settings" src="https://github.com/user-attachments/assets/7fa1f920-0c42-435b-bff6-5742207b11eb" />
- Ran `ipconfig` <img width="711" height="304" alt="network-ticket-ipconfig" src="https://github.com/user-attachments/assets/5211f82f-bee4-42a4-a9f0-faccd71a2443" />
- Tested connectivity with `ping google.com` <img width="543" height="244" alt="network-ticket-ping" src="https://github.com/user-attachments/assets/f8862948-9aca-41b7-bfcc-d19f5f9573f0" />
- Verified DNS resolution with `nslookup google.com` <img width="390" height="327" alt="network-ticket-nslookup" src="https://github.com/user-attachments/assets/8afeaa77-f59b-4457-b659-27c78e1a96f8" />

**Resolution**
Confirmed the system had a valid IP address, active network connection, and working DNS.

---

### 3. Account Assistance

A user needed help with their account and resetting their password.

**What I Checked**
- Opened account settings
- Verified the local user account
- Reviewed password and account management options
- Reset password for user <img width="613" height="180" alt="password-reset-ticket" src="https://github.com/user-attachments/assets/6ec80850-4a15-4527-b3e4-b433e06ab033" />


**Resolution**
Confirmed the account was available and reviewed the appropriate management steps in order to reset end user password.

---

### 4. Printer Troubleshooting

A user reported printer issues.

**What I Checked**
- Opened Printers & Scanners
- Reviewed available printers <img width="611" height="58" alt="printer-ticket-devices" src="https://github.com/user-attachments/assets/6b2588a5-a4df-4ea8-a5b6-50d36d42fc66" />
- Checked the print queue <img width="218" height="56" alt="printer-ticket-queue" src="https://github.com/user-attachments/assets/37bc3e02-e40e-4532-92ae-fb7457b702da" />
- Opened the Print Spooler service <img width="340" height="284" alt="printer-ticket-spooler-service" src="https://github.com/user-attachments/assets/f3340c76-2456-44e5-8523-530945e3932b" />

**Resolution**
Confirmed printer services were available and reviewed common queue and printer checks.

---

## Results

This project gave me practical experience working through common support issues using built-in Windows tools. It also helped reinforce the value of using a clear troubleshooting process instead of guessing at solutions.

Just as important, it gave me more practice documenting work in a way that is easy to understand and useful to reference later.

---

## Skills Demonstrated

- Help desk troubleshooting
- Windows support
- Performance troubleshooting
- Network diagnostics
- DNS testing
- User account support
- Printer troubleshooting
- Service management
- Task Manager usage
- IT documentation

---

## Challenges I Ran Into

One challenge was getting the virtual machine running smoothly while testing different scenarios. Adjusting settings and resources was a useful reminder that environment setup matters.

Another challenge was creating realistic support situations without a live production environment. Building the scenarios manually still provided valuable troubleshooting practice.

---

## Key Takeaways

This project helped me get more comfortable with the day-to-day issues often seen in IT support. It also reinforced that troubleshooting is most effective when you follow a consistent process, verify each step, and document what was done.

---

## Future Improvements

In future versions of this project, I would like to add:

- Outlook troubleshooting scenarios
- VPN connection issues
- Software install requests
- Shared drive access problems
- Remote support examples
- Additional user support tickets

---

## Screenshots

The screenshots folder includes examples of:

- Performance checks in Task Manager
- Startup app review
- Network troubleshooting commands
- DNS testing
- Account management
- Printer queue checks
- Print Spooler service review

---

## Project Status

Completed as an entry-level IT support project and added to my technical portfolio.
