# Penetration-Testing-Labs


-----

# Penetration Testing Labs 🧪

A collection of detailed walkthroughs and case studies from various penetration testing labs and vulnerable machine exercises. This repository documents the process of identifying, exploiting, and hardening systems.

## About This Project

This repository serves as a personal portfolio and educational resource, showcasing practical applications of ethical hacking techniques. Each lab folder contains a detailed report on how a target machine was compromised, from initial reconnaissance to privilege escalation and post-exploitation analysis. The goal is to provide clear, step-by-step documentation of the security assessment process.

-----

## Labs & Walkthroughs

This section contains all completed lab write-ups. Each directory includes a detailed `README.md` file explaining the specific attack chain for that machine.

  * ### [FTP Vulnerability & Password Cracking](https://www.google.com/search?q=./FTP-Vulnerability-Walkthrough/README.md)
      * **Description**: A detailed walkthrough on compromising a Linux VM by exploiting an anonymous FTP login. The process covers network scanning, service enumeration, cracking a hashed password found in a backup file, and gaining user-level shell access via SSH. The report concludes with hardening recommendations to mitigate the identified vulnerabilities.
      * **Key Vulnerabilities**: Anonymous FTP Access, Weak Password Hashing, Information Disclosure, Password Cracking.

*(As you complete more labs, you can add them to this list.)*

-----

## Common Tools Used

While each lab uses a specific set of tools, the most common ones featured in this repository include:

  * **Kali Linux**: The primary attacker machine environment.
  * **Nmap**: For network scanning and service enumeration.
  * **John the Ripper**: For cracking password hashes.
  * **FTP Client**: For interacting with File Transfer Protocol services.
  * **Netcat**: For network connections and data transfer.
  * **Metasploit Framework**: For exploiting known vulnerabilities.
  * **Burp Suite**: For web application analysis.

-----

## 📜 Disclaimer

All information and techniques demonstrated in this repository are for **educational and research purposes only**. The labs are performed in a controlled, isolated virtual environment on machines that I own.

Attempting these techniques on any system without explicit, prior authorization from the owner is **illegal**. The author is not responsible for any misuse or damage caused by the information provided. Please act responsibly and ethically.
