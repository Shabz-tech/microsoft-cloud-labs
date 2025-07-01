# Lab 1: Create and Configure Azure Virtual Machines (Linux & Windows)

## Overview
This lab demonstrates how I created and configured Azure virtual machines for both Linux and Windows using the Azure Portal.

## Objectives
- Create a Linux VM (Ubuntu)
- Create a Windows Server VM
- Configure SSH and RDP access
- Verify remote access

## Resources Created
- Resource Group: `Lab1-RG`
- VNet: `Lab1-VNet`
- VMs: `linux-vm`, `windows-vm`
- NSGs with inbound rules for SSH and RDP

## Steps

### 1. Linux VM
- Ubuntu 24.04
- B1s size
- SSH enabled
- Connected via powershell  
![SSH Screenshot](screenshots/linux-ssh-success.png)

### 2. Windows VM
- Windows Server 2019
- B1s size
- RDP enabled
- Connected to Windows Server 2019 via Remote Desktop  
![RDP Screenshot](screenshots/windows-rdp-success.png)

## Notes
- Used free-tier B1s VM sizes
- Cleaned up all resources post-lab to avoid charges
