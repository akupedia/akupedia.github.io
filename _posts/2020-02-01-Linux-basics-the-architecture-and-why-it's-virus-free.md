---
title: Linux basics – the architecture, kernel and why it’s Virus free !
layout: post
category: Linux
date: 2020-2-4
---

## Linux basics – the architecture, kernel and why it’s Virus free !

Linux is nothing but a mutiuser and multi-tasking OS which was developed by Linux Torvalds in 1991 with a few loosely knit-team of hackers over the internet. Sometimes Linux is also conceived to be a kernel which is basically the core of the operating system. Unix on the other hand is again for muti-users and multi-tasking which was developed by few employees at AT&T at Bell Labs in 1969. During that time there was no GUI and it was totally on command line interface, something which we call now as virtual consoles or the terminal. Unix was completely recocded in C during 1973 and was split into various branches and was adopted by many commercial startups like SUN(solaris), HP(hp-ux), Darwin(by Apple inc.), BSD (university of california) etc..

--

#Things to remember about Unix/Linux:-

Both are muti-user and muti-tasking operating systems and Linux is not a clone of UNIX but rather a OS completely written from scratch by Linux Torvalds.
It’s case sensitive which means all(or most of it) commands are in small case.
Everything is a file or a process. Here files refers to all the digital media installed on computer from images, videos, folders, drivers, .exe files or whatever and process is nothing but a running application.
It does not bother about filename or file extension.
Inter-process communication (IPC) is the key factor, for example let’s take this command ls -l | less, here listing of the file is directly proportional to less command which is used for piping.
Design:-

As we know, the kernel(which is a mediator between hardware and the OS) is at the core and in order for it to communicate there are system calls which are nothing but software routines for communication. The kernel is protected by a shell(divided into 2 parts CLI and the GUI), above which resides the users which run applications. In Linux/Unix every running program has a process ID known as PID which are in the range from(0-65535). Every process is running under a user and each user has it’s own user id know as UID, and every user has its own group which again has a group id GID which is (2^32).

--

#Why is Linux so secured and Virus free?

There are many reasons for it, few of them are mentioned below:-

The market share for Linux desktop is mere 1%, so hardly any one bothers to make a virus or a malacious app for it.
There are more then 300+ linux distributions or flavors, so targetting any particular desktop won’t be easy in practical terms.
In Linux every thing running in the OS is a command, just like right click is a command, opening a file is a command, so there is lot of headache for malaware writers to consider coding and then for execution you need the root privileges, so authentication is a must.
There are about 300 system call in linux, these are nothing but software subroutines for communication from OS to hardware. This number is very less as compared to windows OS which has more then 100000 systems calls. Hence the less no. of system call the more secure is the operating system.
As we all know for an attacker or a hacker to invade the Linux system he/she must have the root password or root privileges without this invasion cannot be done, however this is not the case with windows..
The other technical point I would like to put forth is that the kernel runs in the high priority level(inner ring 0 of the micro-processor) whereas the applications run on lower priority level (that is ring 2 or 3) hence the kernel is   more secured and also there is shell for protection.
How to become a super-user?

Sudo is nothing but super user-do. The extreme level of privileges for all commands the user can run to do any task. You need to type su – in all the Linux distributions except Ubuntu.

For ubuntu you need to type sudo -i and then the password for authentication.

To logout just type exit or logout or press Ctrl + D.

--


#Types of Linux distributions:-

There are mainly 2 types of linux flavors generally however this may vary if Unix-like OS are taken into considerations like Free BSD, Arch Linux, Manjaro Linux etc.

So the 2 types are Debian know as .deb (file name or extension) most of them use apt (advance packaging kit) as a package manager to install software. The other one is RPM also know as Red Hat Package Manager (.rpm is the file name or file extension) and to install the packages there is package-kit (know as Add-Remove Software) or YUM (Yellow-dog updater modifier) to update and modify the rpm packages.

Some of the Debian based distros or distributions are Ubuntu, Linux Mint, Debian OS, Luninux OS, Lubuntu, Xubuntu etc…

Some of the RPM based flavors are Fedora, RHEL, Fuduntu, Opensuse, Mageia,etc…

--



#The terminal and virtual console:-

We all know that the time when unix and linux were created there were no GUI and hence people used to work on the command line interface which we call the terminal or the virtual console (VC).

To open virtual console which is nothing but black and white screen where we need to enter the commands to get the work done. Just hit Ctrl + Alt + F1 to enter and then to exit hit Ctrl + Alt + F6. Note that generally there are 6 VC’s ranging from F1 to F6 on a Linux desktop OS.

That’s it for now folks !

Njoy !

---