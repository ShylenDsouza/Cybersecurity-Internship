# Network Traffic Capture Using Wireshark

## Overview

This project demonstrates how to capture and analyze live network traffic using **Wireshark** and identify HTTP-based web traffic through display filtering.

## Objective

* Capture live network packets
* Generate HTTP web traffic
* Filter and analyze HTTP packets
* Understand security implications of unencrypted traffic

## Environment

* **Operating System:** Kali Linux
* **Platform:** Oracle VirtualBox
* **Tool Used:** Wireshark
* **Network Interface:** eth0

## Traffic Analysis

* Website accessed: [http://neverssl.com](http://neverssl.com)
* Display filter used: `http`
* Observed HTTP GET requests and server responses

## Security Significance

* Demonstrates how unencrypted HTTP traffic can be inspected
* Highlights the importance of HTTPS encryption
* Builds foundational skills for SOC and DFIR roles

## Conclusion

This task highlights the importance of packet capture and analysis in understanding network behavior and identifying potential security risks.


**Note:** This activity was performed in a controlled lab environment for educational purposes only.
