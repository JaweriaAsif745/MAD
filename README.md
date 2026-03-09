**Lab 1:  First Virtual Machine**

**Objective**

To understand the concept of virtualization and create the first virtual machine using VirtualBox or VMware.

**Virtualization**

Virtualization is a technology that allows a single physical computer to run multiple operating systems at the same time. These operating systems run inside isolated environments called Virtual Machines (VMs).
Each VM behaves like a separate computer with its own CPU, memory, storage, and network interface. The physical system running the virtualization software is called the Host System, while the operating system running inside the virtual machine is called the Guest System.
Virtualization platforms such as VirtualBox and VMware provide virtual hardware including virtual processors, memory, hard drives, and network adapters. This allows users to test operating systems, run servers, or experiment with software safely without affecting the main system.
Ubuntu Server is commonly used in virtual labs because it is lightweight, secure, and widely used for server environments.

**Lab Tasks**

1.	Install VirtualBox or VMware Workstation.
2.	Download the Ubuntu Server 22.04 LTS ISO.
3.	Create a new Virtual Machine named Fast-Lab-1.
4.	Configure the VM with the following settings:
o	RAM: 2 GB
o	CPU: 1 Processor
o	Disk Size: 20 GB
5.	Mount the Ubuntu ISO file in the virtual machine.
6.	Start the VM and begin the Ubuntu installation.
7.	Select a minimal installation option.
8.	Create a user with the following credentials:
Username: student
Password: pass123
9.	Complete the installation and reboot the VM.
    
**Discussion Questions**

1.	What is the difference between a Host Operating System and a Guest Operating System?
2.	Why is virtualization used instead of installing multiple operating systems directly on hardware?
3.	Which hardware resources are shared between the host and the guest system?
________________________________________



