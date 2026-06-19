# REvil Walkthrough

> Simple ransomware investigation walkthrough built from the CyberDefenders REvil lab.

`Splunk` `DFIR` `Ransomware` `Threat Intel`

---

## Overview

This walkthrough shows how to investigate a REvil ransomware infection step by step using log analysis and threat intelligence.

It covers:

- finding the ransom note
- tracing the process behind it
- locating the executable
- identifying the shadow copy deletion command
- validating the malware hash
- finding the attacker onion domain

---

## Skills Used

- Splunk log analysis
- Windows event investigation
- Process tracing
- Base64 decoding with CyberChef
- Hash validation with VirusTotal
- IOC review with ANY.RUN

---

## Walkthrough

| Step | Objective |
| --- | --- |
| 1 | Identify the ransom note filename |
| 2 | Find the ransomware process ID |
| 3 | Locate the ransomware executable |
| 4 | Decode the recovery-disruption command |
| 5 | Extract and verify the SHA256 hash |
| 6 | Identify the onion domain |

---

## Lab Assets

- Screenshots: [REvil/images](REvil/images)

---

## Why This Write-Up Matters

- Easy for learners to follow
- Shows practical investigation workflow
- Documents evidence clearly
- Useful as a simple portfolio project
