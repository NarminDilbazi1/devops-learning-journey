# Task 01 – SSH Setup and Basic Linux Commands

## Overview
This task demonstrates setting up an Ubuntu virtual machine, configuring SSH access, and practicing essential Linux commands.

## Environment
- VirtualBox
- Ubuntu VM
- NAT Network with Port Forwarding

## SSH Configuration
Port forwarding was configured as:

- Host Port: 2222
- Guest Port: 22

SSH service was verified with:

```bash
systemctl status ssh
```

SSH connection command:

```bash
ssh -l user-1 -p 2222 127.0.0.1
```

## Commands Practiced

```bash
whoami
lpstat -p
top
ping google.com
apt-get update && apt-get upgrade
```

## Result
- Successfully connected to Ubuntu VM via SSH
- Verified internet connectivity
- Practiced basic Linux system commands
