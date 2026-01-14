# Basic Firewall Configuration Using UFW

## Overview

This project demonstrates the configuration of a basic firewall on a Linux system using **UFW (Uncomplicated Firewall)** to control incoming network traffic.

## Objective

* Allow secure remote access using SSH
* Block unnecessary services such as HTTP
* Enforce firewall rules to improve system security

## Environment

* **Operating System:** Kali Linux
* **Platform:** Oracle VirtualBox
* **Tool Used:** UFW (Uncomplicated Firewall)

## Commands Used

* `sudo ufw status`
* `sudo ufw allow ssh`
* `sudo ufw deny http`
* `sudo ufw enable`
* `sudo ufw status verbose`

## Results

* Firewall status: Active
* Default policy: Deny incoming, Allow outgoing
* SSH (Port 22) allowed
* HTTP (Port 80) blocked

## Security Significance

* Ensures secure administrative access
* Reduces attack surface
* Follows firewall security best practices

## Conclusion

This task highlights the importance of firewall configuration in securing Linux systems and protecting them from unauthorized network access.


**Note:** This configuration was performed in a controlled lab environment for educational purposes only.
