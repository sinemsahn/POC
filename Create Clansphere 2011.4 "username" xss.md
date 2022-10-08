Description

A cross-site scripting (XSS) issue in the Clansphere version 2011.4 allows remote attackers to inject JavaScript via the "username" Parameter

XSS Payload: <script>alert("username_XSS")</script>

Vulnerable Parameter: username

Steps to Reproduce the Issue: POC: https://localhost/index.php?mod=buddy&action=create&id=925872

Screenshot: POC 1
![alt text](https://github.com/sinemsahn/POC/blob/main/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202022-10-08%20145652.png)
![alt text](https://github.com/sinemsahn/POC/blob/main/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202022-10-08%20145704.png)


Impact

With the help of xss attacker can perform social engineering on users by redirecting them from real website to fake one. Attacker can steal their cookies leading to account takeover and download a malware on their system, and there are many more attacking scenarios a skilled attacker can perform with xss.
