# Cheat Sheet HTB
## nmap

**Description:** Tool to discover services on remote host by scanning ports of remote machines.  
**Usage:** 

  nmap [target]  
- -p: Specify ports  
- -sV: Version detection  
- -sC: Uses additional scripts to scan the ports   
- -T: Timing template e.g. T5  
- -v: Verbose output  

**Example:**   

``nmap -sV localhost -T5``


## Reverse Shell Generator

**Description:** Tool to automate the creation of scripts in various programming languages to establish reverse shell connections.  
**Usage:** https://www.revshells.com/

## John The Ripper
**Description:** Tool used to break hashes and crack various types of password encryptions.  

## Snyk CLI
**Description:** Security tool for finding and fixing vulnerabilities in open source libraries  
**Note:** Requires a license for full functionality.  
**Usage:**  

snyk [options]  
- test: Test for vulnerabilities  
- code test: Check for malicious code  


## Hack Tricks
**Description:** Online resource providing various hacking techniques and knowledge.  
**Usage:** https://book.hacktricks.xyz/  


## PEASS-ng

**Description:** Privilege escalation tool.Assists in identifying and exploiting privilege escalation vulnerabilities.  
**Usage:** https://github.com/carlospolop/PEASS-ng  

## Burp Suite

**Description:** Used for traffic interception, application security testing, and more.  
**Usage:** https://portswigger.net/burp  

## Gobuster

**Description:** Enumerates possible paths and files on a web server.  
**Usage:** gobuster [options]  
**Example:** 

``gobuster dir -u http://192.168.0.1:8080 -w /usr/share/wordlists/dirbuster/directory-list-2.3-small.txt``

## Metasploit

**Description:** Penetration testing framework. Offers a wide range of tools for penetration testing, including brute-forcing.  
**Note:** Installation may prompt attention from security departments due to its potential for misuse.  
**Usage:** msfconsole (to launch the Metasploit console)

## KalisList
**Description:** Word lists for password brute-forcing. Utilized with password cracking tools like John The Ripper.  
**Usage:** https://github.com/3ndG4me/KaliLists
