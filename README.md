# Security Incident Report: yummyrecipesforme.com

## Overview
This project documents a website security incident involving `yummyrecipesforme.com`, which was compromised by a former employee through a brute force attack. The attacker gained access using the administrator's default password and modified the website to distribute malware.

## What Happened?
The attacker injected malicious JavaScript into the website, prompting visitors to download a fake browser update. When executed, the downloaded file redirected users to `greatrecipesforme.com`, a fraudulent website containing malware. Customers reported unexpected redirects and slow computer performance.

## Network Protocols
- **HTTP:** Used for communication between the browser and web server over TCP port 80.
- **TCP:** Established connections between the user's computer and the web server.
- **DNS:** Resolved the website domain names to IP addresses.

## Recommended Security Measure
Enable **Multi-Factor Authentication (MFA)** for administrator accounts to add an extra layer of security and make unauthorized access more difficult.

## Conclusion
This incident highlights the risks of weak default passwords and inadequate access controls. Strong authentication and proper security monitoring can help prevent similar attacks.

