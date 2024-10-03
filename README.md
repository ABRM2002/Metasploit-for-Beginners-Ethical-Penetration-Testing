# Metasploit-for-Beginners-Ethical-Penetration-Testing

## Objective:-

The Metasploit-for-Beginners-Ethical-Penetration-Testing is a guided project offered by coursera which has guided me to acquire immense knowledge about the following objectives:-

Metasploit Framework: Dive into the world of exploiting vulnerabilities using Metasploit, the world-renowned penetration testing tool. Learn to identify and leverage weaknesses in system security, and conduct responsible disclosure.

Nmap Scanning: Master the art of network discovery with Nmap, a pivotal tool for scanning networks and uncovering open ports. Understand how to create detailed network maps and identify potential entry points for exploitation.

Exploiting Vulnerable Machines: Through controlled exercises, learn to assess, penetrate, and secure vulnerable systems. Engage with real-world scenarios, where you will practice identifying and exploiting vulnerabilities safely within a lab environment.


## Skills Learned:-

- Utilize an exploit using Metasploit to gain access to a vulnerable system.
- Perform a Vulnerability Scan Analysis to enable effective vulnerability reporting.
- Author comprehensive penetration testing reports with results that will enable a company to fix their vulnerabilities.   

## Tools Used:-

- Metasploit Framework: A penetration testing tool used to identify and leverage weaknesses in system security.
- Nmap: Powerful tool for scanning vulnerable systems.


## What you will need:-

1. VMWare or Virtual Box
2. Kali Linux OS [Attacking Machine]
3. A metasploitable 2 Machine [Victim Machine]
4. Knowledge of basic linux commands

---

# Steps

## Step 1: Use Nmap to Scan for Vulnerable Services


![Screenshot 2024-09-27 235513](https://github.com/user-attachments/assets/e8d7a855-ad48-48be-bc2b-dd20a24d476f)


 - Ports with outdated services often host vulnerabilities

 - -sC Stands for Scripting helps check all vulnerable and exposed ports

 - -sV Stands for Version helps us check if its outdated 

 - -nmap-h Stands for help and it gives a list of all possible commands

---

## Step 2: Perform  Vulnerability Research


![Screenshot 2024-09-28 002442](https://github.com/user-attachments/assets/134f46c6-80ea-4f09-8268-03afae5ef105)


 - Google Dorking is an effective way to enhace searches

 - Sites like Rapid7 and exploit.db act as powerfull tools

---

## Step 3: Perform More Active Reconaissance



![Screenshot 2024-09-28 003822](https://github.com/user-attachments/assets/57eb754b-1eb8-4556-be70-703e706c6019)


 - The msfconsole is the command used to start up metasploit

 - The help command gives a complete detail of every command and their discriptions

 - The exit command is used to exit metasploit

---

## Step 4: Intro To Metasploit

 
![Screenshot 2024-09-28 005012](https://github.com/user-attachments/assets/6720e3c4-c8f4-46d9-bd78-ea10b3a70189)

 - The show options command and search command were essential to uncover all desired vulnerabilities 

 - Use 0 command is used to exploit the payload

---

## Step 5: Load Your First Metasploit Module

![Screenshot 2024-09-28 005825](https://github.com/user-attachments/assets/1cc33b4b-833e-486d-9da6-e2bfe9526856)


 - show displays the current configuration of the module

 - rhost is the victim machine

 - rport is the port we are attacking

 - we set the rhost to the ip address of the metasploitable module

---

## Step 6: Exploit a Vulnerable Machine


![Screenshot 2024-09-28 011622](https://github.com/user-attachments/assets/f5c1a14b-c630-4598-a249-7c71141cbd05)



 - Created a backdoor account using the adduser command

 - Allows us to easily get back into the machine without the need of the long metasploit
   process

 - As a blue team monitoring for unauthorized accounts is essenrtial

---

## Step 7: Create a Penetration Testing Report


![Screenshot 2024-06-06 223055](https://github.com/user-attachments/assets/d3ad1733-4e03-4699-9f24-e69e85379278)


![Screenshot 2024-06-06 223136](https://github.com/user-attachments/assets/f68affe6-f2ca-41c4-9d22-ddd7236215b3)


 - A pen testing report should always include scope, findings and remediation steps 
 
 - The severity was measured with the help of CVSS

---

# Certificate:-

![Metasploit for Beginners Ethical Penetration_page-0001](https://github.com/user-attachments/assets/bca29a04-33f9-4b00-bd37-c0019a42f25a)
