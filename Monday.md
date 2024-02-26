# Day 1

(( my personal progress))

CHAPTER 2

Redhat is a major supplier of linux operating systems
They describe linux as composed of THREE major sections:
1. The Kernel
2. The System User Space
3. Applications

---

## KERNEL:
Kernel is the base of the operating system (( almost the lowest layer ))
Kernel manages the hardwar eand its interactions with everything else

When the computer "boots" up 
It either
- runs BIOS (Basic Input/Output System) or
- runs UEFI (Unified Extendable Firmware Interface)

These run a bootloader that loads the Kernal image

From here, the Kernel initializes and starts up everything else that is required to run (e.g., drivers and software)

---

## Administrative Layer (system user space)
This is an administrative layer for the tasks like configuration and software installation
- It includes shell or command interpreter
- Also includes daemons (Daemons run in the background to manage things)
  Daemons are not visible to the users cuz they don't allow interaction but they ARE vital for the proper functioning of Linux
  
---

## Software (Applications)
jo normal applications hoti hain e.g., browser

---

# Distributions 
Ek cheez ki different versions ko distributions keh skte hain
Decide krna konsi distribution best hai quite difficult hota hai or totally apki needs pe depend krta hai

---

Shurru k dino mai Linux itna khaas nhi tha jitna aaj hai
Uss mai boht se maslay thay jese
- Use krne mai difficult tha
- Install krne mai bhi difficult tha
- Lack of "drivers" for hardware

Lekin ye sab 15-20 saal pehle hota tha, ab boht behtar hai Linux kyu k Kernel ki support agyi hai for most hardware in use

Ab linux boht reliable hai
Linux servers kaafi der tk chaltay rehte without rebooting unless kernel update krna parray

---


### Different Versions of Modern Linux

# Linux Distributions


 Linux distribution is a version of a software that's packaged up with everything needed to make it run
 Sab se pehli linux mai kuch khaas cheezein nhi included theen
 Toh boht saaray distributors ny apni apni versions bna li linux ki lekin Kernel ek hee raha, as a common factor    among all of them

 Package managers use hotay thay/hain to install new software, woh bhi change hotay gaye depending on distribution



The course will mostly discuss Linux from:
- Red Hat (which includes CentOS and Federa)
- Ubuntu (which is based on Debian)
- OpenSUSE (which comes from SUSE project)


If you're not sure which one to go with, go for Ubuntu or CentOS

Use "Current" distribution instead of Long Term Support

---

# Open Source
Open Source means the source code is available for use, examine, modify and share


Kernel is fully open source

---

# Other Popular Operating Systems
- Windows: can be used for servers and personal use
- MacOS: not used for servers and is supplied with Apple computers

---

chapter 3

# Server Linux

A server can be a physical computer or a virtual one in a cloud environment like Amazon EC2, or Google Cloud
With a server, you don't need a graphical interface, you can but it's more secure to connect with a secure terminal, SSH or some other method


Why server-specific linux then?
A server specific installation uses fewer resources. 
- No graphical interface is needed if there is no monitor
- Less software installed, less software means less things running
- Less software = less update


Dedicated servers are designed for throughtput and reliability
Computer designed for desktop use won't have server-specific items

Linux is good for
- Databases
- Web Servers
- Email Servers

  Most of them run on Linux because o its reliability


# Desktop Linux
You can use Linux for all your daily tasks
It isn't just for the servers in a data center, computer room, or the "cloud"

There are distributions specifically designed for use on the desktop
And there are some that are designed specifically for server use





