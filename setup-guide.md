# Setup Guide

## Step 1: Install Ubuntu Server  
1. Download the Ubuntu Server ISO from [ubuntu.com](https://ubuntu.com/download/server).  
2. Install VirtualBox from [virtualbox.org](https://www.virtualbox.org/).
3. Open VirtualBox and click "New" to create a new virtual machine.  
   - Set the name (e.g., "Ubuntu Server"), type as "Linux", and version as "Ubuntu (64-bit)".
4. Allocate memory (RAM) to the VM. For Ubuntu Server, 2GB (2048MB) is sufficient.
5. Create a virtual hard disk:
   - Choose "Create a virtual hard disk now", "VDI" as the disk type, and "Dynamically allocated" for storage.
   - Set the disk size (10GB or more is recommended).
6. Configure the VM:
   - Under "System", ensure the boot order has the optical drive at the top.
   - Under "Storage", click the empty disk icon and select the Ubuntu Server ISO.
7. Start the VM and follow the on-screen instructions to install Ubuntu Server.
   - Choose language, keyboard layout, and time zone.
   - Set up user account and password.
   - Use "Guided - Use entire disk" for partitioning.
   - Optionally, select OpenSSH for remote access.
8. After installation completes, reboot the VM. Remove the ISO from the optical drive to avoid booting from it again.

## Step 2: Initial System Update  
1. Log into Ubuntu Server with the username and password you created.
2. Run the following commands to update the system:
   sudo apt update
   sudo apt upgrade
