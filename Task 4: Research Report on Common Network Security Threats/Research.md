# Task 4 – Research Report on Common Network Security Threats

## 1. Introduction

In today’s highly connected digital world, computer networks form the backbone of communication, business operations, financial systems, and critical infrastructure. As organizations increasingly rely on networked systems to store, process, and transmit sensitive information, the risk posed by network security threats has grown significantly. Cyber attackers continuously develop new techniques to exploit vulnerabilities, disrupt services, and gain unauthorized access to confidential data.

Network security threats can lead to severe consequences, including financial losses, data breaches, legal penalties, reputational damage, and loss of customer trust. Understanding how these threats operate and how they can be mitigated is therefore a crucial aspect of cybersecurity. Effective network security requires a combination of technical controls, continuous monitoring, and user awareness.

This report focuses on three common and impactful network security threats: **Denial of Service (DoS) attacks**, **Man-in-the-Middle (MITM) attacks**, and **Spoofing attacks**. Each threat is discussed in detail, including its working mechanism, impact, real-world relevance, and mitigation strategies. The aim of this report is to provide a clear and comprehensive understanding of these threats and highlight best practices for protecting modern networks.

---

## 2. Denial of Service (DoS) Attacks

### 2.1 Description

A Denial of Service (DoS) attack is a type of cyberattack that aims to make a system, service, or network unavailable to legitimate users. This is achieved by overwhelming the target with excessive traffic, requests, or resource-intensive operations. When the system’s resources such as bandwidth, memory, or CPU are exhausted, it becomes incapable of responding to genuine user requests.

In more advanced scenarios, attackers use multiple compromised systems, known as a **Distributed Denial of Service (DDoS)** attack. These systems, often part of a botnet, simultaneously send traffic to the target, making the attack more powerful and difficult to mitigate.

### 2.2 How It Works

In a typical DoS attack, the attacker sends a massive volume of packets or repeated requests to a target server or network device. These requests may appear legitimate, making it difficult for the target to distinguish between genuine users and malicious traffic. As the volume of traffic increases, the system becomes overloaded, leading to slow performance or complete service disruption.

DDoS attacks amplify this effect by using thousands or even millions of compromised devices to flood the target. Common techniques include SYN floods, UDP floods, and application-layer attacks such as HTTP request flooding.

### 2.3 Impact

The impact of DoS and DDoS attacks can be severe and far-reaching:

* Prolonged website or service downtime
* Loss of business revenue due to service unavailability
* Degradation of network and system performance
* Increased operational costs for mitigation and recovery
* Damage to organizational reputation and customer trust

For critical services such as banking, healthcare, and e-commerce, even a short downtime can result in significant losses.

### 2.4 Mitigation Techniques

Organizations can reduce the risk of DoS attacks by implementing multiple defensive measures:

* Deploying firewalls and intrusion prevention systems (IPS)
* Implementing rate limiting and traffic filtering
* Using load balancers and redundant infrastructure
* Employing DDoS protection services from cloud providers
* Continuously monitoring network traffic for anomalies

### 2.5 Real-World Example

Several major online platforms and service providers have experienced large-scale DDoS attacks that caused temporary outages, affecting millions of users worldwide. These incidents highlight the importance of proactive defense mechanisms and scalable infrastructure.

---

## 3. Man-in-the-Middle (MITM) Attacks

### 3.1 Description

A Man-in-the-Middle (MITM) attack occurs when an attacker secretly intercepts communication between two parties who believe they are directly communicating with each other. The attacker can monitor, modify, or manipulate the data being transmitted without the knowledge of either party.

MITM attacks are particularly dangerous because they compromise the confidentiality and integrity of communication, often without leaving obvious signs of intrusion.

### 3.2 How It Works

In a MITM attack, the attacker positions themselves between the client and the server. This can be achieved using various techniques such as:

* Address Resolution Protocol (ARP) spoofing
* Domain Name System (DNS) spoofing
* Rogue or malicious Wi-Fi access points

Once positioned, the attacker can capture sensitive information such as usernames, passwords, session cookies, and financial data. In some cases, the attacker may also alter the transmitted data, leading to unauthorized transactions or data manipulation.

### 3.3 Impact

MITM attacks can have serious consequences, including:

* Theft of sensitive information and credentials
* Unauthorized access to systems and accounts
* Data tampering and manipulation
* Loss of confidentiality and data integrity
* Potential financial fraud and identity theft

### 3.4 Mitigation Techniques

Effective mitigation of MITM attacks includes:

* Using encrypted communication protocols such as HTTPS and TLS
* Avoiding unsecured public Wi-Fi networks
* Implementing strong authentication and certificate validation
* Using Virtual Private Networks (VPNs) for secure communication
* Regularly updating systems and applications

### 3.5 Real-World Example

MITM attacks are commonly observed on unsecured public Wi-Fi networks, such as those in airports or cafes, where attackers intercept user traffic to steal login credentials and sensitive data.

---

## 4. Spoofing Attacks

### 4.1 Description

Spoofing attacks involve an attacker impersonating a trusted entity by falsifying identity information. This may include IP addresses, MAC addresses, email headers, or domain names. By pretending to be a legitimate source, attackers can deceive users and bypass security controls.

Spoofing attacks are often used as a precursor to more complex attacks such as phishing, malware distribution, or MITM attacks.

### 4.2 How It Works

In a spoofing attack, the attacker modifies packet headers or identity details to appear as a trusted system or user. For example, in IP spoofing, the attacker alters the source IP address of packets to impersonate a legitimate device. In email spoofing, attackers forge email headers to make messages appear as though they were sent by a trusted organization.

This deception can trick victims into trusting malicious communications or granting unauthorized access.

### 4.3 Impact

The impact of spoofing attacks includes:

* Unauthorized access to networks and systems
* Data theft and manipulation
* Distribution of malware
* Successful phishing and social engineering attacks
* Loss of trust in network communications

### 4.4 Mitigation Techniques

To prevent spoofing attacks, organizations can implement the following measures:

* Strong authentication and access control mechanisms
* Packet filtering and ingress/egress filtering
* Network monitoring and intrusion detection systems
* Email authentication technologies such as SPF, DKIM, and DMARC
* Regular audits of network traffic and logs

### 4.5 Real-World Example

Email spoofing is widely used in phishing campaigns, where attackers impersonate banks or trusted organizations to trick users into revealing sensitive information such as passwords and credit card details.

---

## 5. Conclusion

Denial of Service, Man-in-the-Middle, and Spoofing attacks represent significant threats to modern computer networks. Each attack exploits different weaknesses in network design, configuration, or user behavior, but all can result in serious security incidents if not properly addressed.

By understanding how these attacks work and implementing appropriate mitigation strategies, organizations can significantly reduce their exposure to network-based threats. Regular monitoring, secure configurations, encryption, strong authentication, and user awareness are essential components of an effective network security strategy.

---

## 6. References

* NIST Cybersecurity Framework
* OWASP Security Documentation
* General Internet Security Best Practices
