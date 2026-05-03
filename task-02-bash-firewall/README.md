# Task 02 – Bash Scripts and Firewall Configuration

## Overview
This task includes Bash scripting and Ubuntu firewall configuration.

## Bash Scripts

### timer.sh
- Countdown script using while loop
- Accepts user input

### deployer.sh
- Installs multiple packages using apt
- Checks root privileges

### create_user.sh
- Creates user with password validation
- Uses useradd and chpasswd

## Firewall (UFW)

```bash
sudo ufw allow ssh
sudo ufw deny http
sudo ufw enable
sudo ufw status
```

## Result
- Scripts created and tested successfully
- Firewall configured for basic security
