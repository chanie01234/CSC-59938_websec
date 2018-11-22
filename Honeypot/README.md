# Project 9 - Honeypot

Time spent: 6 hours spent in total

> Objective: Stand up a basic honeypot and demonstrate its effectiveness at detecting and/or collecting data about an attack

### Overview
- My overall approach to Honeypots is to first understand the functionalities and uses of the Honeypot. There are multiple honeypots for most languages and almost every purpose according to the developer. From the resources provided, honeypots are a great way to analyze, attack, and prevent threats toward a user, organization, etc. Implementing a Honeypot is fairly easy and provide the flexibility of serving the purpose of the developer. For this assignment, I set up two honeypots, Dionea and SNORT, using the Google Cloud service. Through this, I can use my honeypots to detect types of attacks, ports, country of origin of any attack placed on the honeypot. Using nmap, a hacking tool that sends malicious packets and records the responses of the a system, web app, etc., I was able to launch an attack on my honeypots. I was able to witness the power of a honeypot and it's use in everyday security tasks. Of course, there are ways to conceal your identity via IP address and country of origin via "proxy servers" so that the attacker remains anonymous. After the attack was launched, I was able to keep track of my attacks using the Attacks Report page on the MHN server. Here, lists date/time of detection, country of origin, source IP address, destination port, protocol, type of honeypot that detected the attack. Analyzing this report can reveal tremendous information about the attack and attacker. There are multiple honeypots you can use at a time to gather various information about an attack and to prevent it from appearing in your crosshairs ever again.


### Summary of data collected: number of attacks, number of malware samples, etc.
- Dionea: 1530
- SNORT: 21 Alerts

### Main Screen
<img src='http://i.imgur.com/7i7HRbj.png' title='Video Walkthrough' width='500px' alt='Video Walkthrough'/>


### SNORT Alerts
<img src='http://i.imgur.com/BeS2M2Q.png' title='Video Walkthrough' width='500px' alt='Video Walkthrough'/>


## Describe any challenges encountered while doing the project
- I had only one challenge setting up my mhn admin instance on Google Cloud. It seemed that the last working mhn repo was deprecated and has been updated.
