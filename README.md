# cybersecurity-internship-task4

# Windows Firewall Configuration and Testing

## Overview

This project contains documentation and evidence of configuring and testing basic firewall rules on a Windows system using Windows Defender Firewall. The exercise demonstrates adding, testing, and removing firewall rules to block and allow specific network traffic.

## Features

- Add an inbound rule to block traffic on a specified port.
- Test the effectiveness of the blocking rule using PowerShell.
- Remove or disable the firewall rule to restore original settings.
- Document all steps with screenshots and command outputs.

## Files

- `/screenshots/` — Screenshots showing firewall rule setup, testing, and removal.
- `/report/` — Detailed report documenting the task procedure and results.

## How to Reproduce

1. Open Windows Defender Firewall with Advanced Security.
2. List current inbound and outbound firewall rules.
3. Create a new inbound blocking rule for a specific port (e.g., port 23).
4. Test the rule connectivity using PowerShell command `Test-NetConnection`.
5. Disable or remove the blocking rule after testing.
6. Document each step with screenshots.

## Outcome

By following this process, basic firewall management skills are developed, enabling control over inbound and outbound network traffic to enhance system security.

