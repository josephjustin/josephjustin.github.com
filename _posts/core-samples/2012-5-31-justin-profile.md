
Cell: +91-8129166455
Email: justinATjosephjustin.com

Justin Joseph

Profile
-------
Linux Systems Engineer with 9 years experience on Linux kernel based operating systems
including mobile/tablet versions of Android, desktop/server (PC Based) operating systems like
Redhat, Debian, Ubuntu etc.. DD-WRT/Open-WRT based network embedded device firmwares.
Domain expertize in networking and C system programming on Linux. Computer science and
engineering graduate(B.Tech), worked extensively on Linux with practical knowledge of TCP/IP
networking stack, networking applications and C programming. Experience in networking
capabilities of linux including Netfilter framework and applications implementing features like
IDS/IPS, VRRP, IPSec VPN etc. Experience in tool chain building and microcontroller
programming. Proficient in using development tools on linux including gcc, gdb, diff, make, gprof,
repo, git, svn etc. Experience in writing device drivers. Experience in Android development
including custom ROM(CyanogenMod, AOSP based) building from sources, kernel space and
userspace programming.

Technical Skills
----------------

Operating System : System Programming skills on Linux - knowledge of system calls, IPC
mechanisms (shared memory, semaphores), POSIX threads, device driver writing.

Programming Languages : Skilled in C.

Unix Tools: make, gcc, diff, patch, gdb, gprof, svn, git, git-svn, repo.

Microcontroller: ATMEL ATMega8.

Networking: TCP/IP Networking stack and applications.

Android: Custom ROM building, kernel/userspace programming and configuration.

Work Experience (9 years)
-------------------------
Presently working as freelance consultant helping business solve problems in the field of Free and
Opensource systems.  Industry Experience: Worked in challenging roles at startups like Elina Networks 
Pvt Ltd(IIMB incubated), Bangalore (Sr. R&D Engineer) ,Solidcore Techsoft (Acquired by McAfee, Trainee
Software Engineer). Intel Bangalore (contracted in role of Linux Consultant), Wipro Technologies
(Senior consultant).

Academic Qualification
----------------------
Bachelor of Technology in Computer Science & Engineering, from MES College of Engineering,
Kuttipuram, under University Of Calicut (1999-2003).

Roles and Achievements
----------------------
As a freelance consultant, I have been instrumental in helping businesses solve problems enabling
them to start new product lines, fix critical bugs, secure IT infrastructure and this has helped them
in delivering more value to their existing customers and increasing their existing customer base.


As Senior Consultant working at Intel in the Low Power IA(Power and Performance) team, I was
responsible for providing solutions aiding in Power and Performance improvements for Android
and Meego O.S running on Intel Medfield platform.

As Sr. R&D Engineer working at Elina Networks(product start-up company), I was responsible for
implementing network functionality on Elina router/firewall. Being part of a technology start up
which incubated at IIM Bangalore, I worked on a broad range of requirements in a tight schedule.
Was responsible in adhering to short release cycles targeting multiple features thereby enabling
Elina to meet new client requirements.

My career involved usage of Open source software and collaboration with the Open source
community at large. Worked with different Open source communities in India and is the founder
member of FSMK www.fsmk.org and computerclub.in http://computerclub.in/ComputerClubIndiaAtFossIn2009

Projects Summary
----------------

ISDB stack implementation/integration with BCM7424
--------------------------------------------------

Description

Worked on developing and integrating Wipro ISDB-T/S stack with
Broadcom set-top box platform.

Contribution

Maintained the abstraction layer used by all the ISDB layers for
system services (sys calls), IPC related tasks(mutex,
semaphores, message queues etc..). Wrote the build system for
integrating different ISDB layers like hardware abstraction
layer, browser markup language layer, OS Synchronization layer,
ISDB middle ware. Implemented the persistent storage
component(part of the Hardware abstraction layer). Implemented
BML layer APIs.

Technology Skills

Proficiency in Linux systems programming environment.
Proficiency in maintaining large code base. Understanding of
Linux build system(Makefiles).

Intel low power IA (power and Performance team)
------------------------------------------------

Description

Worked local on-site at Intel in the Power and Performance team.
Worked on developing tools and enabling Performance
measurements/Optimizations on Meego mobile platform.

Contribution

Wrote code for SFI table parser, glibc profiler, made Linux
kernel modifications for enabling Performance benchmarking on
Medfield Intel Mobile platform at 1.6Ghz freq. Analyzed glibc
memory routine throughputs which led to performance improvement
of strcpy function on Meego/Medfield. Provided solution for
compiling Nokia compiler performance suite for Meego/Medfield
platform.

Technology Skills

Proficiency in Linux systems programming environment. CPUfreq
Linux Kernel subsystem, C programming, Intel SFI Specification.
Linux timer mechanism. Linux Driver development.

Router/Firewall functionality
------------------------------

Description

Network functionality implementation for Elina Router/Firewall

Contribution

Implemented various network functionalities, including Snort
based IDS/IPS, OpenSwan based IPSec VPN, Bind based DNS, c-icap
based ICAP functionality, Frox FTP Proxy, vsftp based FTP
Server, Netfilter/Iptables and Shorewall based firewall,
Inspector based chat proxy, Keepalive based VRRP support, QoS,
ISDN etc.

Provided Patches and bug reports to the Shoreline Firewall
project (www.shorewall.net ).

Technology Skills

TCP/IP Networking on Linux, C programming, Networking programs
on Linux.

Router hardware functionality Check
------------------------------------

Description

Hardware Program Suite to analyze the ENPAQ 2105 series router

Contribution

Designed and implemented the hardware suite (manufacturing
tests) for ENPAQ 2105 series router. The suite tested all the
hardware on the IBase IB798 SBC used by the router to function.
C program binaries are invoked to test the LED’s, RTL network
card (4 Ethernet ports), mouse, parallel port, serial port,
sensors, hard disk, flash disk.

Technology Skills

Linux systems programming. C programming, Ibase SBC Board
specification.

HDLC Driver development.
------------------------

Description

HDLC driver for Serocco PEB 20525 HDLC/PPP mini PCI card

Contribution

Wrote Linux kernel (V 2.6) driver for SEROCCO-H PEB20525
HDLC/PPP mini PCI card. The driver enabled leased line
connectivity for ENPAQ 2105 routers.

Technology Skills

Linux Network Driver development. C programming. Understanding
hardware (SEROCCO-H PEB20525) specifications.

VPD Programmer
---------------

Description

Realtek RTL8139 VPD(Vital Private Data) Programmer

Contribution

Designed and Implemented the RTL EEPROM programmer for storing
Elina Serial number and other details on the RTL8139 EEPROM
VPD. There are read/write/dump options. The program can write
serial numbers or read them or dump the VPD contents on
terminal. The code was modification and extension of the
rtl8139-diag GPL code.

Technology Skills

Linux systems programming. C programming.

LED and Watchdog timer programming

Description

Programmed the LED’s and Watchdog timer on the IBase IB798

Contribution

The LED’s on the IBase IB798, the LED’s were used to display
WAN, STATUS, FAIL on the ENPAQ 2105 router. Init scripts are
used as wrapper for the LED program to control the LED’s and
they indicate the status of the router. Programmed the WDT on
the W83697HF Winbound chip on the IBase board. The program is
invoked by init script and would reset the processor in case
the Linux kernel stalls.

Technology Skills

Linux systems programming. C programming. Bash scripting.

Philips I2C Protocol
--------------------

Description

Implementing Phillips I2C protocol

Contribution

The project involved data acquisition with the ATMega8 micro and
storing the same on 24C04 SEEPROM. The SEEPROM communicates
using the I2C protocol, and the ATMega end of the protocol was
implemented in C.

Technology Skills

Microcontroller GPIO Programming, I2C protocol specification. C
Programming. Microcontroller Tool chain building on Linux(Cross
compiler, Assembler). Parallel Port based microcontroller
programmer.

Hobby Kit Development
---------------------

Description

ATMega8 microcontroller based hobby kit (Similar to Arduino)

Contribution

Developed Hobby kit based on ATMega8 Microcontroller and Linux
based Opensource tool chain.

Technology Skills

Linux systems programming. C programming. Tool chain building.
Assembling hardware programmer.


