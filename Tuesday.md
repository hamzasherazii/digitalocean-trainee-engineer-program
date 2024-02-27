# Virtualization

Virtualization enables the hardware resources of a single computer to be divided into multiple virtual computers, called virtual machines (VMs).

Types of Virtualization

- Type 1: A physical computer runs a "hypervisor". It talks directly to the computer's hardware, usually dedicated to running virtual machines. Amazon EC2 and other clour providers use this method.

- Type 2: Hosted Hypervisor. Personal computer mai virtualization krna. Jese apke computer mai windows hai or aap us k saath Virtual Machine mai Linux install kr lo.

---

chapter 4

# SSH ((Secure Shell)

Secure protocol to connect to your servers
program: ssh


It's a text-based program that allows direct access to the server


Three Layers of SSH
- Transport Layer: Ensures that the connection between you and the target is secured. It also does caching of data and data compression.
- Authentication Layer: This is where authentication is performed before the connection is allowed
- Connection Layer: Manages the communication once authentication has been performed

---

# Installing & Updating Software in Linux

High level of access is required
The root user has the most access of any user
It can run any command or update any file

Best practice is to not use the root user directly. For security purposes, you should never log in as that user.


You can use sudo command to raise your permission as that of a root user
Each time sudo command is used, it is logged in system logs for tracking and audit

You can use sudo cmd to install a program
For example, you want to install the program Vim for Red-hat-Style distributions

sudo dnf install vim ((to install latest distributions))
sudo yum install vim ((Red Har Enterprise 7 [and CentOS 7] and earlier distributions))

To update

sudo dnf update 
sudo yum update


[For Ubuntu and Debian Distributions]
The sudo apt update updates the change database. Do this first, then update or install.

sudo apt update
sudo apt install vim

To update all the programs with bug fixes or latest versions

sudo apt update
sudo apt upgrade



---

# Docker

Open-source containerization platform
Designed for running small containers or images of your software


Container in the docker world is a package of code that includes everything needed to run a program

# Vagrant

It's a tool used for building and managing virtual machine environments in a single workflow













