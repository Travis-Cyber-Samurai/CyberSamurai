# How to get started with CyberPatriot. 

So this is going to be a little intro guide to getting started with not only cyberpatriot, but key concepts in cybersecurity and computer science that will be transferable to many other fields. Hope this information is helpful :) 

KEY NOTE: 

You will struggle and be googling and researching a lot, it is just apart of being apart of tech so becoming a self learner is extremely important to your overall success. 

# Preface
Hi, my name is Daniel, known online as "Mambo" and sometimes Kitan. I have been competing in CyberPatriot for 2 years now and started at a school that did not have a CyberPatriot team till my sophmore your of high school, where we became a platinum competeting team and would be able to compete along side college students at CCDC, a Cyber Defense competition against active red team members at the regional level. I have a deep passion and focus for computer science, and software and AI/ML development as well as, an interest in red teaming and cybersecurity. I hope that the following information can help whoever is reading this become successful in taking on the daunting task of learning Cybersecurity in CyberPatriot and on onwards. 

# What is CyberPatriot ? 
Clearly defining cyber patriot and the competition is going to be very important to your success with developing what the competition is trying to teach everyone: a high school incident response and remediation competition that tests your understanding of "The Security Mindset" and how you respond to challenges. Basically learning operating systems and being able to define and find vulnerabilities in your coroporate network scenerio. 

There are three sections to this introductory competition to cybersecurity: Linux, Windows, and CISCO (Networking). Linux is a operating system that is used by 90% of computers around the world. Windows and Windows Server is another operating system that is used by almost every user in the world. Lastly, Cisco sponsers this competiton so the networking trianing resources are tailored entirely towards Cisco resources and for good reason as they are a big player in the networking space.  These sections are important for everyone to know but having a deep focus in a specific area will overall be beneficial to your success in the competition. For me, I focus on Linux so this guide will provide mostly resources for Linux which I hope to expand in the future. 

#Approach for the Competition: 

As much as copying and using checklists and scripts would help you immensely going throughout the competition the main thing that is supposed to be taught and will happen numerous times throughout the competition is researching when you are stuck. It is going to be beneficial to reframe your thinking of this competition to a reserach competition that is present before the competition (preperationg, during the competition, (finding unkown vulnerabilities), and after the competition (debrief and review). This applies to most things within tech and its adjacent fields as research is so important. 

SO TO STRESS THIS, WHEN YOU RESEARCH ANG GOOGLE GO IN DEPTH, DISECT AND UNDERSTAND THE PROBLEM, AND KNOW YOU WILL GET STUCK. Your reserach shouldnt send at Ubuntu ssh security settings and copying them in to a script without knowing it works. UNDERSTAND, PLAN, SCRIPT, DISECT, and LEARN why and how it works. This will help you with actually learning and tackling harder to challenge problems. 

Some key protocols and applications to reserach and know when going into the competition are: 

HTTP/S: Apache2, IIS
DNS: Windows DNS, Bind9
Remote Management: OpenSSH, RDP
Database Technology: MySQL/MariaDB, MSSQL 
Mail: Exchange, MailEnable, Postfix, Sendmail
File Sharing: FTP (vsFTPd, Filezilla, etc.), SMB (Samba, Windows SMB)
CMS: WordPress, Joomla
VPN: OpenVPN
Identity Management: Active Directory Domain Services


# OS Familiarity

The majority of the competition tackles understanding the ins and outs of Linux and Windows (As well as Cisco).  Some key things to look into would be the Windows and Linux Checklists we have, other resources provided for practice, and actaul practice on the machine. 

Basic System Mechanisms to look into would be: 

Linux:

User and Password Management: /etc/passwd, /etc/group, /etc/shadow
Pluggable Authentication Modules (PAM)
Tunable Kernel Parameters (Sysctl)
Package Managers (APT/DNF)
CRON
Permissions
Systemd
Sudo
Polkit
UFW, Firewalld
SElinus, Fail2Ban 


Windows:

Windows User Management
Local Security Policy
Group Policy
Registry Editor
Task Scheduler
Windows Defender
Permissions
Service Manager


# Learn to Baseline 

An important thing to do during the competition that will help you learn and find vulnerabilities is to baseline as well as attack your system (hacking). More will be provided here later but understanding what a default system looks like compared to your messed up one will help you greatly in actaully finding what is wrong with your system. Some things to look into would STIGS on all systems linked here: [here](https://public.cyber.mil/stigs/downloads/)

