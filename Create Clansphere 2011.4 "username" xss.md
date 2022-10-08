Description

A cross-site scripting (XSS) issue in the Clansphere version 2011.4 allows remote attackers to inject JavaScript via the "username" Parameter

XSS Payload: <script>alert("username_XSS")</script>

Vulnerable Parameter: username

Steps to Reproduce the Issue: POC: https://localhost/index.php?mod=buddy&action=create&id=925872

Screenshot: POC 1



Impact

With the help of xss attacker can perform social engineering on users by redirecting them from real website to fake one. Attacker can steal their cookies leading to account takeover and download a malware on their system, and there are many more attacking scenarios a skilled attacker can perform with xss.
