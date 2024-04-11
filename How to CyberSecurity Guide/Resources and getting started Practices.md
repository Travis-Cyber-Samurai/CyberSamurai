# Step By step on different things to learn :)

#VMware 

So at first you should download VMWare Player 17 on your Windows or Linux Computer. 
VMware Player is a hypervisor allowing us to use virtiualization software, basically it lets you runs machines, or images inside your computer. So you are running an operating system inside your operating system and they are working sepeartly so we do not affect the main computer. 

Follow [this video](https://www.youtube.com/watch?v=EEEMKwqD7Yk) to download VMware player on your home computer. Make sure you computer has the proper requirements to download the software. 

Now to use virtual machines, we will provide you with virtual machines to use but here are where you can download Linux and Windows images to use on VMWare Player 
These are all the most recent versions of the product, if you want an older version, just google to find the specific version or ask us. 

[Ubuntu](https://ubuntu.com/) - Beginner friendly 

[Debian](https://www.debian.org/) - Main Branch for Ubuntu, widely used

[Alma](https://almalinux.org/)

[Rocky](https://rockylinux.org/download)

[Fedora](https://fedoraproject.org/workstation/download) - also appered in cyberpatriot 

[CentOS](https://www.centos.org/download/#sources) - used in some comps

[Arch](https://gitlab.archlinux.org/archlinux/arch-boxes/-/packages/1375) - really customizable

[Kali](https://www.kali.org/) - the hacking OS 

[Parrot](https://parrotlinux.org/download/) - another hacking OS but is more privacy based 



Windows Server VMs:

[Windows Server 2014](https://drive.google.com/file/d/15ZlhfcHLvO0EhsJPaj3CBt9vTAcdz_0N/view?usp=sharing)

[Windows Server 2016](https://drive.google.com/file/d/1kKYo8C_T0Xs4d_lZWpu-OO1ApYWcenUu/view?usp=sharing)

[Windows Server 2019](https://drive.google.com/file/d/1yxeHNphxZwmdMr_FFPS08XkvLy1i_a7I/view?usp=sharing)

Default credentials for Server VMS:

User: Administrator

Password: Cyb3rPatr1ot!@
 
Password to unzip: Cyb3rPatr1ot!@


# Capture the Flags Resources

Capture the flags are a fun way to learn hard and convulated cyber security skills through creative challanges. The main one that you should start off with is [PicoCTF](https://picoctf.org/). Create an account and then start practicing! That is all I will leave you with since you are supposed to go into this blind. 

note: I recommend getting familiar with kali linux and learning how to use its tools as it will help alot with downloading tools and completing the challenge.

More info on CTFs in the Canvas.

Here are some resources to help however: 

[PicoCTF Primer](https://primer.picoctf.com/#_general)

[Stegnagraphy Online](https://georgeom.net/StegOnline/upload) 

[MetaData](https://www.metadata2go.com/result#j=96caba54-723d-41ed-9010-9351770167e2)

[Visual Studio Code](https://code.visualstudio.com/)

[A CTF Playbook](https://fareedfauzi.gitbook.io/ctf-playbook/a-few-tips)

[John Hammond's CTF Playbook](https://github.com/JohnHammond/ctf-katana?tab=readme-ov-file#apk-forensics)

[Another Playbook](https://github.com/apsdehal/aWEsoMe-cTf?tab=readme-ov-file#bruteforcers)

[Anddd Another Playbook](https://github.com/uppusaikiran/awesome-ctf-cheatsheet?tab=readme-ov-file#netdiscover-scanning)

[ANDDDDD ONE MORE PLAYBOOK](https://github.com/Slothkrew/ctf-playbook?tab=readme-ov-file#web-security)

[Archived CyberStart Forensics](https://github.com/alphyos/CyberStart-2024)

Good Luck! 

# Cyber Patriot Curriculum 

Not mine but the resources are good you should know all of this stuff that is linked here for the competition.

note: Not all of it but for your specific target of security, or all of it, up to you. 

[here](https://tirefire.org/posts/cyberpatriot-curriculum/)

# Learning Linux 

So to learn Linux(the best OS) honestly just start doing it, it is definetly going to be hard to get used to but by doing you will learn far more than trying to read about it and never actually attempting to learn how Linux works. Again, 90% of computers use a version of Linux, if you continue in tech YOU WILL ENCOUNTER LINUX, learn it. 

[Start off with Linux Journey:](https://linuxjourney.com/)

[then TryHackMe Courses](https://tryhackme.com/module/linux-fundamentals) 

[To get even mroe familar with the Linux terminal do OvertheWire](https://overthewire.org/wargames/)

At this point you can do the practice images, start scripting everything :3

While at this stage PLEASE PLEASE, research what you dont know using google, StackOverFlow, and more. YOU WONT KNOW EVERYTHING SO PLEASE CONTINUE LEARNING. 

[Do NCAE Videos to get a more advanced grasp of Linux](https://www.ncaecybergames.org/tutorials/)

[As well as follow these videos when learning concepts]() 



# Learning Windows 

[To learn Powershell on Windows do UndertheWire](https://underthewire.tech/century)

[Windows AD Basics](https://tryhackme.com/r/room/winadbasics)

# Learning Cisco 

# Scripting

# Hacking Resources :) 

# Programming 

# Git and Github 

Git and GitHub are tools widely sued by all cybersecurity specialsists, software developers and more. this is due to the fact that both of these contribute to the Version Control System, allowing people to collabortively store and work on code, see in depth changes, review code, and make test branches of the main code without messing up the main project. Overall, you will encounter Git and GitHub and they are amazing tools you should learn. 

[Heres a tutorial on Git and GitHub]()

# Baselining and STIGS

Baselining is important as it bascially checks your system and goes, "hey how are you different from default or secure settings." Developing baseline scripts will overall make finding about 40-50% of points/vulnerabilities so much easier SO DO IT. 

Note on Baselining for Linux: 

use third party tools and system package utilities to flag what files’ default content has been changed. scan for permission issues by comparing a list of world-writable files on a clean system to the one on the challenge image, flagging any differences. This can be extended to other possible permission issues like SUIDs. There are countless other parts of the system that can be baselined, such as default systemd units, scheduled jobs, processes, and more. By baselining in the first hour, you will get a good understanding of what is actually wrong with the system. 

[Lynis - Securitiy auditing and hardening tool for Linux/Unix](https://cisofy.com/lynis/)

[Stig Viwer - Security settings machines](https://www.stigviewer.com/)

[Meld - VIsual diff and merge tool (really good to make a script and then edit insecure files all at once](https://meldmerge.org/)

[CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks)

[Debain Family CIS Benchmark](https://www.cisecurity.org/benchmark/debian_family)

[Securing Debian](https://www.debian.org/doc/manuals/securing-debian-manual/index.en.html)

[Alma Linux CIS Benchmark](https://www.cisecurity.org/benchmark/almalinuxos_linux)

[DOD Stig List (USE TRUST)](https://public.cyber.mil/stigs/downloads/)

[Mitre Attack Framework (learn about all different types of cyber attacks)](https://attack.mitre.org/)

[Hack Tricks - Use this as a checklist to hack into systems or secure them (know evil to do good :3)](https://book.hacktricks.xyz/linux-hardening/linux-privilege-escalation-checklist)

[Old CIS Benchmarks (They are archived good place to find older system info)](https://github.com/cismirror/old-benchmarks-archive)

[Hardening Ubuntu Script (REALLY NICE PLEASE USE)](https://github.com/konstruktoid/hardening)

[Windows 10 Hardening](https://github.com/0x6d69636b/windows_hardening)

[Privellage Escalation vuln scan script for Linux and Windows ( LinPeas and WinPeas OP use)](https://github.com/peass-ng/PEASS-ng)



# Planning 

# Practice Images

**Magistrate**
Magistrate hosts images on their website check them out as they are good for practice. 
[Magistrate](https://magistrate.shiversoft.net/)

**Linux**

Here are some practice images that you can use to prepare for the competition, test out your scripts or hone your skills. 

[Mr.Robot Fedora Practice Image](https://ln5.sync.com/dl/3e4ff83c0/u2wyn5b9-yuthhkgw-dqhghbr4-qme8tqjx)

 - [or here](https://drive.google.com/file/d/1QQYUdp1Qu1-0NXf7VHyiIMl2QY4X_izp/view)

 - [more about the Fedora Image here (talks about some errors in the image, a writeup, and checksums)](https://tirefire.org/posts/fedora-practice/)


[Bloom TD 6 Theme - Debian 10](https://www.mobmaker.xyz/cypat-images)


[Ubuntu 18 Image - No Answer Key](https://drive.google.com/file/d/1ZLKf-DAij1VN6aFz6T5Z3fpGEpfxJWzo/view)


[House On the Borderland - Ubuntu 20](https://drive.google.com/file/d/1MaEmGrTFMZIcG2S0DPCLDfWffThndkGk/view?usp=sharing)

- md5sum: 9a7229c3d178d6e7e7180da18c448d6f


[System Hardening 6 - Narnia Minecraft Server (Ubuntu 22, Easy)](https://drive.google.com/file/d/12x8aYXIpGwO47MIvUCB6G3bqV-8npVUx/view?usp=sharing)

- [README Link](https://eth007.me/cypat/syshardening6/)
- [Writeup of the image](https://github.com/Quasar0147/Syshardening-6-Writeup)


[System Hardening 7 - rooReaper Strikes Back (Ubuntu 22, Easy)](https://drive.google.com/file/d/1gyshPKjhQ2o907LQpwB_gq3BeqwmN2ko/view?usp=sharing)

 - [README Link](https://eth007.me/cypat/syshardening7/)


[System Hardening 8 - The Fellowship of the Ring (Fedora 38, Hard)](https://drive.google.com/file/d/1N6fpGL-ZlT5C8nvf4Y68nSKz65CqyfBH/view)

 - [README](https://eth007.me/cypat/syshardening8/)
 - [Writeup of the image](https://github.com/Brycen-walker/CTF-Writeups/blob/main/imaginaryCTF-2023/syshardening-8/README.md)


[Aperture Science Ubuntu](https://drive.google.com/file/d/1_ZDn7K4Xy6pQ5YXWroqBkZoIdYfSivkT/view)

 - [Answer Key](https://drive.google.com/file/d/1FZvMhCCAt78CQvEpawQVtCBdh4umK-0f/view?usp=sharing)


[Nevermore - Ubuntu 22.04](https://drive.google.com/file/d/1EW3hsjZMM--UtoFJuYBVbAMhUwU4Z8gn/view?usp=sharing)


 
**Windows**

[My Little Pont Windows 10 Practice Image](https://cybervoid.me/projects/mlp/)


[Cinncinatti Zoo Windows 10](https://cybervoid.me/projects/cincinnati/)


[Baldi's Basics Windows Server 2022](https://cybervoid.me/projects/baldi/)


[King Arthur's Castle Server 2019](https://drive.google.com/file/d/13OBAXsv408TQJ-WtNMc-mUEe2IBvI-UV/view?usp=share_link)
 - Main user Password CyberPatriot1!
 - [YT Video Walkthrough](https://www.youtube.com/watch?v=6DjIExkbVoE)
 -[Answer Key](https://docs.google.com/presentation/d/1zO4cRpTY2b6SQK55EVPe7XSQKe2YqA8pwq7TOeYOvxg/edit#slide=id.g1e0329b4e58_0_0)


[Windows 10 Practice Image - no answer key](https://drive.google.com/file/d/1FzzYG7haDwrz4D69MtKGDifDpqNWcg5q/view)


[Princeton-Plainsboro Teaching Hosptial Windows 11](https://ejinnis.ca/practice-images/princeton-plainsboro-teaching-hospital/)


[System Hardening 9 - Return of the King (Windows Server 2022, Medium)](https://drive.google.com/file/d/1gYM366G8HG_WSEGIR90widby_XoVkDxK/view)

 - [README](README Link)


[Aperture Science Windows Part 1](https://drive.google.com/file/d/1mN8yucgD31tVIJgWRkfYyRvegLsFHLS2/view?usp=sharing)

[Aperture Science Windows Part 2](https://drive.google.com/file/d/1Gp22ccrHR680o9Gdi52SvZEliBRpm0G8/view?usp=sharing)

[Aperture Science Windows Part 3](https://drive.google.com/file/d/1mo-r28xlR7aN4TUlEJGuHAkHss8W5lt1/view?usp=sharing)

 - [Answer Key](https://drive.google.com/file/d/11yk-ylOE7zancN6HCudMC8zP1zb9hCBc/view?usp=share_link)



[Windows 10: Alphabet Soup](https://drive.google.com/file/d/1zTLpm26kZowc4mdNwrDv33RsCV-fj4-i/view?usp=drive_link)

 - md5:    EC82C40B7036B0802E0556B3977F2596
 - sha256: 67A1A73535D52E592FFAC95F6224F67ABBF176AAEA9F2ACF76698C774ACBDAC6




# Creating Your Own Images

To create your own images use and develop your own vulnerabilites with these tools from Cyber Aegis, the number 1 team in Cyber Patriot like every year. 

[Elysium Suite](https://elysium-suite.netlify.app/)

# Tools and programs to use 

[Cyber Chef: its for de/encryption and de/encoding](https://gchq.github.io/CyberChef/)





