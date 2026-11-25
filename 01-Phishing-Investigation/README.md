# Project 01: Phishing Email Investigation

## Project Overview
- Platform: TryHackMe
- Lab: Phishing Emails 1
- Completion Date: November 25, 2026
- Difficulty: Beginner
- Environment: Guided cybersecurity training lab
- Status: Completed

## Objective
Investigate suspicious emails, identify potential phishing indicators, examine email headers, and analyze encoded attachments.

## Tools Utilized
| Tool | Purpose |
|---|---|
| Thunderbird | Email and message source analysis |
| CyberChef | Base64 decoding |
| Mousepad | Raw email content inspection |
| TryHackMe | Controlled investigation environment |

## Investigation Methodology

### 1. Email Analysis
- Examined sender and recipient information.
- Reviewed suspicious subject lines and email content.
- Identified potential brand impersonation.

### 2. Email Header Analysis
- Inspected raw email message sources.
- Identified originating IP addresses.
- Examined authentication-related headers.

### 3. Attachment Analysis
- Identified attachment filenames and content types.
- Examined Base64-encoded attachment data.
- Practiced decoding attachments using CyberChef.

### 4. Indicator of Compromise Identification
- Identified suspicious sender domains.
- Examined originating IP addresses.
- Defanged IP addresses for safe reporting.

## Key Findings
- Sender display names can impersonate legitimate organizations.
- Email headers provide additional information about message origins.
- Base64 encoding can be used to transmit email attachments.
- Suspicious links and unexpected order confirmations are potential phishing indicators.

## Security Recommendations
- Implement SPF, DKIM, and DMARC.
- Conduct employee phishing awareness training.
- Analyze suspicious attachments in isolated environments.
- Verify unexpected emails through trusted communication channels.
- Report suspicious emails to security personnel.

## Skills Developed
- Phishing email analysis
- Email header inspection
- Indicator of compromise identification
- Base64 decoding
- IP address defanging
- Cybersecurity investigation fundamentals

## Lessons Learned
This exercise provided practical experience applying cybersecurity concepts to simulated phishing investigations. It reinforced the importance of examining technical evidence rather than relying solely on an email's appearance.

## Training Reference
[TryHackMe - Phishing Emails 1](https://tryhackme.com/room/phishingemails1tryoe)

## Disclaimer
This project documents a guided training exercise conducted in an authorized lab environment. Lab answers, flags, and sensitive investigation artifacts have been excluded.
