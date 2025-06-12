---
title: "Lab Challenges"
permalink: /labs/
layout: single
classes: wide
---

## 🧪 Challenge 1: Web Exploitation - SQL Injection

**Problem:** Exploit a vulnerable login form  
**Tools:** Burp Suite, SQLMap  
**Approach:** Used `' OR '1'='1` to bypass auth  
**Lessons:** Input validation is critical  


---

## 🔐 Challenge 2: Password Cracking - Hashcat

**Problem:** Crack SHA256 hash with wordlist  
**Tools:** Hashcat, rockyou.txt  
**Result:** Password cracked in 2 minutes  
**Lessons:** Importance of salting


---

## 🔍 Challenge 3: Network Sniffing - Wireshark

**Problem:** Capture and analyze login credentials over HTTP  
**Tools:** Wireshark  
**Outcome:** Able to extract plaintext credentials  
**Lessons:** Avoid HTTP for sensitive data  
**Screenshot:**  
![SQLi Screenshot](/assets/images/sql-lab.png)
