# How to get started with CyberPatriot. 

So this is going to be a little intro guide to getting started with not only cyberpatriot, but key concepts in cybersecurity and computer science that will be transferable to many other fields. Hope this information is helpful :) 

KEY NOTE: 

You will struggle and be googling and researching a lot, it is just apart of being apart of tech so becoming a self learner is extremely important to your overall success. 

NOTE 2: 

This first seciton is about how to approach the competition and an overview.

Go [here](#General-Resources) for general resources

Go [here] for linux resources 

Go [here] for Windows resources 

Go [here] for Cisco Resources 

# Preface
Hi, my name is Daniel, known online as "Mambo" and sometimes Kitan. I have been competing in CyberPatriot for 2 years now and started at a school that did not have a CyberPatriot team till my sophmore your of high school, where we became a platinum competeting team and would be able to compete along side college students at CCDC, a Cyber Defense competition against active red team members at the regional level. I have a deep passion and focus for computer science, and software and AI/ML development as well as, an interest in red teaming and cybersecurity. I hope that the following information can help whoever is reading this become successful in taking on the daunting task of learning Cybersecurity in CyberPatriot and on onwards. 

# What is CyberPatriot ? 
Clearly defining cyber patriot and the competition is going to be very important to your success with developing what the competition is trying to teach everyone: a high school incident response and remediation competition that tests your understanding of "The Security Mindset" and how you respond to challenges. Basically learning operating systems and being able to define and find vulnerabilities in your coroporate network scenerio. 

There are three sections to this introductory competition to cybersecurity: Linux, Windows, and CISCO (Networking). Linux is a operating system that is used by 90% of computers around the world. Windows and Windows Server is another operating system that is used by almost every user in the world. Lastly, Cisco sponsers this competiton so the networking trianing resources are tailored entirely towards Cisco resources and for good reason as they are a big player in the networking space.  These sections are important for everyone to know but having a deep focus in a specific area will overall be beneficial to your success in the competition. For me, I focus on Linux so this guide will provide mostly resources for Linux which I hope to expand in the future. 

# Approach for the Competition: 

As much as copying and using checklists and scripts would help you immensely going throughout the competition the main thing that is supposed to be taught and will happen numerous times throughout the competition is researching when you are stuck. It is going to be beneficial to reframe your thinking of this competition to a reserach competition that is present before the competition (preperationg, during the competition, (finding unkown vulnerabilities), and after the competition (debrief and review). This applies to most things within tech and its adjacent fields as research is so important. 

SO TO STRESS THIS, WHEN YOU RESEARCH ANG GOOGLE GO IN DEPTH, DISECT AND UNDERSTAND THE PROBLEM, AND KNOW YOU WILL GET STUCK. Your reserach shouldnt send at Ubuntu ssh security settings and copying them in to a script without knowing it works. UNDERSTAND, PLAN, SCRIPT, DISECT, and LEARN why and how it works. This will help you with actually learning and tackling harder to challenge problems. 

**Some key protocols and applications to reserach and know when going into the competition are:** 

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

**Basic System Mechanisms to look into would be:**

**Linux:**

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


**Windows:**

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

# Automation 

Key thing to notes when scripting and automating is to focus on what you can script consistently instead of scripting things that could change depending on how the competition is. EX: configuring kernal params would be good to script, as well as Nmap scripts etc, but scripting services configs that aren't default/security settings wouldn't be smart as you might break your system. (Not what we want .-.)

# Overall Gameplan when approaching the competition 

As we go throughout the year we will develop our own gameplan but in general here is how the competition will go at least for Linux :3. Idea is though that we should get every single point on the system, though that does not usually happen in the later rounds. So, it is okay to miss 1-2 points for the 2nd and 3rd rounds but aim for 100% security. 

1. README
2. Forensic Questions
3. Initialize script and fix potential issues that may affect script features (e.g., reset APT repositories, removed immutable permissions, reset $PATH variable, etc.)
5. Baselining
6. Users & Groups
7. Backdoor & Malware hunting
8. Updates
9. Reboot to apply kernel updates
10. Package and service management
11. System hardening (PAM, Sysctl, Sudoers, Polkit, Bootloader, etc.)
12. Critical Service security
13. File and directory permissions
14. Point Scrounging (Searching for the points that we do not get)

# Team Composition

As our team develops to a full team of 6, there are different roles that you should envision for yourself if you are going to compete so you can tailor yourself for the competition. 

2 dedicated Windows competitors
  - Windows consistently emerges as the most time-consuming and demanding component of the competition     (Excluding CyberPatriot 15 Fedora).
  - The first three qualification rounds, teams encounter two Windows images in comparison to a single     Linux image.
  - Certain intricacies commonly related to general Windows security mostly prove to be less amenable       to automation than Linux machines.
  - The Windows challenges tend to be more plagued with issues (broken PowerShell, disabled access to       system mechanisms, etc.) that require more time to analyze and rectify.

    
1 dedicated Linux competitor
  - While Linux is also a demanding aspect of competition rounds it tends to be more manageable by a     - single competitor than Windows. Despite its challenges, I consider it to be more tractable for         individual competitors.
  - As previously mentioned, Linux plays a smaller role in the first three qualification rounds.
  - Due to its configuration file-based and command-centered structure, Linux lends itself more           readily to automation compared to Windows machines which makes it more manageable in competition       rounds.
    
1 Linux/Extra Challenge competitor
  - The responsibility of this competitor is to provide assistance to the primary Linux competitor.         They will complete Linux-related tasks directed by the primary Linux competitor, this would            likely include Forensic Questions, troubleshooting, or completing certain checklist sections on        the challenge images.
  - The other responsibility of this competitor is to pursue points in any extra challenges that may       be included in the competition round. It is important that this competitor is well-versed in a         variety of cybersecurity topics and technologies as the Extra challenges often encompass a diverse      range of skills and scenarios.
    
1 dedicated Cisco competitor
  - This competitor should be exclusively focused on Cisco throughout the competition season. Cisco is     an integral component of the competition that can be easily mastered with dedication, resulting in     consistently high results that optimize the team’s overall score.
    
1 “Jack of All Trades” competitor (likely substitute)
  - The “Jack of All Trades,” is a versatile competitor with a skillset that spans all facets of the       CyberPatriot competition. While not needing to be a master in any specific area, this individual       serves as an invaluable asset, providing essential assistance at critical junctures and acting as       a valuable sanity-checker for the team.
  - For example, since Cisco is a competition component which demands precision without live feedback,     another competitor with a Cisco background reviewing the primary Cisco individual’s work is             immensely valuable and can eliminate or minimize any possible minor mistakes which could have         significant consequences.
  -  Another advantages of this competitor include their fresh perspectives, solutions, and/or             assistance. This could include identifying workarounds for a broken system mechanism on the Linux       machine or offering to assist with more mundane, yet important tasks, allowing specialized             competitors to focus on more complex matters.


# General Resources
