# Basic Network Scanning with Nmap

## Overview

This project demonstrates a basic network scanning exercise using **Nmap** to identify open ports and running services on a target system within a controlled virtual lab environment.

## Objective

* Verify network connectivity to the target system
* Scan for open TCP ports
* Identify running services (if any)
* Understand the security implications of exposed or closed ports

## Environment

* **Attacker Machine:** Kali Linux (Oracle VirtualBox)
* **Target IP:** 192.168.232.128
* **Tool Used:** Nmap (Network Mapper)

## Commands Used

* `ip a` – To verify network configuration
* `nmap -sS -sV 192.168.232.128` – To perform TCP SYN scan with service version detection

## Results

* The target host was reachable
* No open TCP ports were detected
* All scanned ports were in a closed state

## Security Significance

* Closed ports reduce the attack surface
* No unnecessary services are exposed
* Indicates a secure baseline configuration

## Conclusion

This project highlights the importance of regular network scanning to assess system exposure and maintain strong security practices.

**Note:** This scan was performed strictly for educational purposes in a controlled lab environment.
