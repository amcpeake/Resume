# Education
## [Bachelor of Information Technology](http://www.bitdegree.ca/index.php?Program=NET) | Carleton University
> Ottawa, Canada | 2016–2021

Carleton University's Bachelor of Information Technology is a 4 year program, with courses held at both Carleton University and Algonquin College.

This allows for advanced theory courses to be offered through Carleton University, while maintaining access to Algonquin College's sophisticated networking labratory space.

Through this I gained several hundred hours of hands-on experience with networking hardware including Cisco Routers/Switches, Aruba APs, and Nokia Service-Aware Routers.

<!-- Let's make this like 5 courses tops -->
### Relevant Courses:
| Course Name | Course Description | Grade Achieved | Year Taken |
| ----------- | ------------------ | -------------- | -------------- |
| Networked Applications | APIs, RPC, RMI, p2p applications implemented in Java/Python | A | 4th Year |
| Advanced Network Switching | Advanced switching concepts; STP 802.1D/w/s, pVLANs, Switch security, etc.  | A+ | 3rd Year |
| IP Architecture and Solutions | Advanced routing concepts; MPLS (RSVP-TE/LDP), Services, ISP/Data Center operations | A+ | 3rd Year |
| Real-Time Systems | Assembly/C fundamentals; Designing and implementing Arduino microsystems | A | 3rd Year |
| Web Programming | PHP, JavaScript, HTML, and CSS | A+ | 3rd Year |

---

# Work Experience
## [Technical Support Engineer](https://jobs.lever.co/verkada/a2bf1453-2ec9-4f8e-8f9b-15c62f74eeaf) | Verkada
> San Mateo, CA | September 2021–Present

Having grown a weary of the brutal Ottawa winters, I was looking to move somewhere a little warmer. In that regard, Verkada serves as a great forray into the world of silicon valley.

I quite enjoy the dynamic nature of troubleshooting, getting to scratch that problem-solving itch without being constantly overwhelmed. Being a startup, there's also a certain level of inter-team collaboration afforded which I quite enjoy. Being able to isolate a bug and then speak directly to the engineer responsible is quite a luxury and greatly expediates the process.

On top of that, working with a product line I believe in is a great motivator. It's neat to find new functionality by chaining functionality of various products, like a lego set where your pieces are cameras, sensors, access control, etc.

---

## [Nuage 2LS Support Engineer](https://careers.nokia.com/jobs/nuage-2ls-support-engineer-1185) | Nokia
> Ottawa, Canada | May–August 2020

Having started the position during the intial COVID-19 lockdowns, working remotely (and subsequently not being able to meet my coworkers in person) was certainly an adjustment. Onboarding becomes a siginificantly more difficult process when you're unable to simply walk to your coworker's desk to ask a question.

That said, I was mostly able to overcome these challenges and found myself up to speed within a few short weeks. Being able to work with higher-level networking concepts than I was used to (such as SDN) and collaborating with colleagues on teams all across the world were definite highlights for me. My team had pretty frequent contact with engineering, so I also liked being able to work directly with engineering to debug software and deep dive on bugs.

---

## System Admin/Software Developer | [Canadian Centre for Cyber Security (CCCS)](https://cyber.gc.ca/en/)
> Ottawa, Canada | May–August 2018, January–December 2019

Working for the CCCS provided me with a breadth of experience in a variety of fields.

Given relative freedom to pursue projects which personally interested me, I made extensive use of my networking knowledge as well as programming expertise gained through several years of personal hobbyism and formal training to create tools which bridged my love of both software design and networking. [BearMetal]() is a great example of such a project.

Duties included network configuration and troubleshooting, VM management (ESXi, Docker), software design, ethernet cabling, VPN configuration, etc.

---

# Skills
### Programming Languages (In order of proficiency)
| Language | Total time of practical use | Relevant Projectss |
| -------- | --------------------------- | ----------------- |
| Bash | 5 years | [PyDE](https://github.com/amcpeake/PyDE), [IPList](https://github.com/amcpeake/Resume#iplist--may-2018---august-2018) | 
| Python | 4 years | [Tony Spark](), [CodePoints](https://github.com/amcpeake/CodePoints), [PyFib](https://github.com/amcpeake/PyFib) |
| JavaScript | 2.5 years | [FileX](https://github.com/amcpeake/FileX), [amcpeake.com](https://github.com/amcpeake/amcpeake.com) |
| Java | 1 year | [BearMetal](https://github.com/amcpeake/Bear-Metal), [FXGames](https://github.com/amcpeake/FXGames) | 
| PHP | 10 months | [FileX](https://github.com/amcpeake/FileX) |
| C | 8 months | |
| C++ | 4 years |
| M68K Assembly | 4 months | |

### Networking Protocols
* BGP
* OSPF
* MPLS
* STP

### Other Technologies
* Linux CLI | 5 years
* Docker Containerization | 3.5 years
* Hardware/Software/Network Troubleshooting | 2 years
* ESXi | 2 years

---

# Hobbies
* PCB design
* 3D printing
* [QMK/Custom mechanical keyboards](https://docs.qmk.fm/#/)
* [Urban exploration](https://en.wikipedia.org/wiki/Urban_exploration)
* Cycling
* Hiking

---

# Projects
### IoT Gate | December 2021–Ongoing
IoT Gate is a recent micro-project I've been tinkering with in an effort to get myself to work on more hardware projects.

The building I currently live in has a garage door opener to get onto the premises. I was planning to go back home for the holidays, with a few coworkers of mine offering to watch my cat, but then a problem arises: with only one garage door opener, how do I grant access to multiple users? Admittedly perhaps an overdramatic problem statement, but it's a relatively trivial problem to solve so I figured why not.

I took apart the garage door opener and soldered some jumpers across the button, wired into a 5V relay, which is in turn connected to some GPIO pins on a raspberry pi. The pi runs an API which, when it receives a web request, will power the relay, shorting the button, and finally opening the gate.

Next steps for this project are getting some stronger auth, like placing the API behind a cloudflare argo tunnel and building a nicer frontend.


### [FileX](https://github.com/amcpeake/FileX) | February 2020–Ongoing
FileX - a spiritual successor to the idea I had for [PyFib](https://github.com/amcpeake/PyFib) - is a JS/PHP web-based file browser, primarily used as a media player for files on a NAS.

I was in the process of setting up a NAS at work and I found that most network file sharing protocols (Samba, NFS, etc.) struggle to be seamless in a multi-OS environment. Since I was setting up a NAS of my own at home, I thought I could do better.

HTTP is supported by virtually anything with an ethernet connection - I use FileX from my smart TV all the time - and grants the ability to create your own UI and functionality on top of it. 
First I started with basic file sharing, but I decided expand to add a built-in media player and simulcast client for livestreaming content with friends.

Since this is a piece of software I use nearly daily, I'm regularly adding new tweaks and functionality.

### [Bear Metal](https://github.com/amcpeake/Bear-Metal) | July–November 2019
Between April 2019 and December 2019, I was employed by the Canadian Center for Cyber Security (CCCS). 

Within the CCCS are several teams devoted to malware analysis and malware reverse engineering. In a typical scenario, malware analysis is done within a virtual machine, for isolation and convenience of deployment. However a problem arises when you are attempting to analyze malware sophisticated enough to shut itself off when it knows it is being analyzed in a virtual environment. 

To combat this, a baremetal environment with the same level of isolation and convenience of deployment is required. Enter project Bear Metal, a restlet (Java) API used to deploy operating system images to physical hardware over iSCSI and control power/user IO via IPMI.

### Tractyl | May 2019–Ongoing
Tractyl is an ongoing project between myself and a friend and is an attempt to build a custom mechanical keyboard with an integrated trackball.

The idea arose from a desire to have complete mouse/keyboard control without moving your hands between two distinct devices.
In its current state we have a custom 3D-printed housing and custom PCBS, and are specifically working on feeding the trackball input into the microcontroller (ProMicro) used for the keyboard logic.

### Tony Spark (TSpark) | January 2018–Ongoing
Tony Spark is a hobby project, created by myself and [@ehrenjn](https://github.com/ehrenjn). It's only intended for use in our personal discord server (hence the repo is now private), but serves as a catalogue of various interesting ideas implemented in python. This includes cloud storage, a bandcamp/soundcloud downloader, and an enhanced search function (Discord's built-in search function leaves something to be desired) to name a few.

### [Personal Website](https://www.amcpeake.com) | July 2018–Ongoing (Currently offline for maintenance)
My personal website mostly serves as my testing grounds for various projects. There is more going on in the background on hidden pages than is displayed from the main url. That said it serves as a view of some of my smaller hobby projects (i.e. meme generator)

### [FXGames (Java FX Games)](https://github.com/amcpeake/FXGames) | February–April 2019
FXGames is a small collection of simple games written in Java, using JavaFX for graphics.
Used as a more entertaining means of improving my Java/JavaFX knowledge.

Includes Pong, Atari Breakout, Snake, Chess, etc.

### [Python Development Environment (PyDE)](https://github.com/amcpeake/PyDE) | January–February 2019
PyDE began as an online Python IDE, but has evolved into an expansive multi-language IDE.
It currently consists of a single ~300 line script, and has facilitated my attempted mastery of Bash.
This has been used for CodePoints, and Tony Spark, however I also plan to integrate it into my personal website as well.

### [CodePoints](https://github.com/amcpeake/CodePoints) | January–February 2019
CodePoints is an add-on to PyDE which functions as a programming-based game. Users are given a series of challenges, and must write code to solve them. Though the application is currently limited in scope, it is an ongoing project, and expansion is to be expected.

### [Python File Browser (PyFib)](https://github.com/amcpeake/PyFib) | November 2018–February 2019
My website is run off of a Raspberry Pi running at home, and while I was using it as a local network drive (NFS and Samba), I wanted to extend the utility of the network drive with the goal of never having to carry a USB drive with me again. The result is PyFib, which will eventually be implemented on my website and server as a web portal for personal cloud storage.

<!--### IPList | May 2018 - August 2018
IPList, written while working for the Government of Canada, is a ~200 line bash script for gathering info about devices on the local network. Understanding of the office network address space was lacking, (i.e. which ip addresses were used) and IPList was created to remedy this. Initially it only pinged each IP in a series of given subnets to determine if they were used or not. However, I realized that by creating a non-sudo account on each device I could gather further information, such as uptime, available storage, RAM, hostname, etc.

In the end, this became a fundamental piece of software for IT administrators in the environment, and remains in use.-->
