# Network Security

## Overview

Network Security is the practice of protecting computer networks, connected devices, and data from unauthorized access, cyber attacks, misuse, and service disruptions. It combines hardware, software, policies, and monitoring techniques to ensure secure communication between devices while maintaining the confidentiality, integrity, and availability of information.

As organizations increasingly depend on cloud computing, remote work, and Internet-connected devices, network security has become one of the most critical components of cybersecurity. A secure network not only protects sensitive data but also ensures business continuity and compliance with security standards.

---

# Objectives of Network Security

The primary objectives of network security are:

- Prevent unauthorized access
- Protect sensitive information
- Detect and stop cyber attacks
- Ensure secure communication
- Maintain network availability
- Monitor network activities
- Reduce security risks

---

# Network Security Architecture

A secure enterprise network consists of multiple security layers.

```text
                Internet
                    │
                    ▼
             ┌────────────┐
             │   Firewall │
             └────────────┘
                    │
                    ▼
             Intrusion Detection
                    │
                    ▼
               Secure Router
                    │
        ┌───────────┴───────────┐
        ▼                       ▼
   Internal LAN             DMZ Server
        │                       │
        ▼                       ▼
 Employee Devices         Public Web Server
```

Each security layer provides additional protection against cyber threats.

---

# Firewall

A firewall is a security device that monitors and controls incoming and outgoing network traffic based on predefined security rules.

Firewalls act as the first line of defense between trusted internal networks and untrusted external networks such as the Internet.

### Types of Firewalls

- Packet Filtering Firewall
- Stateful Inspection Firewall
- Proxy Firewall
- Next-Generation Firewall (NGFW)
- Cloud Firewall

### Functions

- Blocks unauthorized traffic
- Allows legitimate communication
- Filters malicious packets
- Monitors network connections
- Enforces security policies

---

# Intrusion Detection System (IDS)

An Intrusion Detection System monitors network traffic for suspicious or malicious activities.

Unlike firewalls, IDS does not block attacks; instead, it generates alerts for administrators.

### Types

- Network IDS (NIDS)
- Host IDS (HIDS)

### Advantages

- Detects attacks quickly
- Generates security alerts
- Monitors network behavior
- Helps identify policy violations

---

# Intrusion Prevention System (IPS)

An Intrusion Prevention System not only detects malicious activities but also automatically blocks them.

### Functions

- Block malicious packets
- Prevent exploitation
- Stop malware communication
- Detect suspicious traffic
- Prevent brute-force attacks

---

# Virtual Private Network (VPN)

A Virtual Private Network creates an encrypted communication tunnel between users and a network.

VPNs protect sensitive information while using public networks.

### Benefits

- Secure remote access
- Data encryption
- Privacy protection
- Safe public Wi-Fi usage
- Prevents packet interception

---

# Network Segmentation

Network segmentation divides a network into smaller, isolated sections.

This limits the spread of malware and reduces the impact of cyber attacks.

### Advantages

- Improved performance
- Better access control
- Reduced attack surface
- Easier monitoring
- Stronger security

---

# Access Control

Access control determines who can access network resources.

Common authentication methods include:

- Username and Password
- Multi-Factor Authentication (MFA)
- Smart Cards
- Biometrics
- Security Tokens

Organizations often implement the **Principle of Least Privilege**, ensuring users receive only the permissions necessary for their roles.

---

# Secure Network Protocols

Secure communication depends on encrypted protocols.

| Protocol | Purpose |
|----------|---------|
| HTTPS | Secure web communication |
| SSH | Secure remote login |
| TLS | Encrypts network communication |
| SFTP | Secure file transfer |
| IPsec | VPN communication |
| WPA3 | Secure wireless networking |

---

# Common Network Attacks

### Denial-of-Service (DoS)

Overloads a server with excessive requests, making services unavailable.

### Distributed Denial-of-Service (DDoS)

Uses thousands of compromised devices (botnets) to overwhelm a target system.

### Man-in-the-Middle (MITM)

Intercepts communication between two parties without their knowledge.

### ARP Spoofing

Redirects network traffic by sending fake Address Resolution Protocol (ARP) messages.

### DNS Spoofing

Redirects users to malicious websites by altering DNS responses.

### Packet Sniffing

Captures network packets to obtain confidential information.

---

# Wireless Network Security

Wireless networks require additional protection because communication occurs through radio signals.

### Best Practices

- Enable WPA3 encryption
- Change default router passwords
- Disable WPS
- Use strong Wi-Fi passwords
- Regularly update router firmware
- Restrict unauthorized devices

---

# Zero Trust Network Security

Zero Trust follows the principle:

> **"Never Trust, Always Verify."**

Instead of automatically trusting users inside a network, every user, device, and application must be continuously authenticated and authorized.

### Core Principles

- Verify identity continuously
- Least privilege access
- Device verification
- Continuous monitoring
- Micro-segmentation

Zero Trust has become one of the most widely adopted enterprise security models.

---

# Real-World Case Study

## Target Data Breach (2013)

Attackers gained access to Target's internal network through compromised credentials belonging to a third-party vendor.

Once inside, they moved across the network and stole payment card information from millions of customers

---

# Key Takeaways

- Network security protects communication between devices and systems.
- Firewalls, IDS, IPS, VPNs, and network segmentation are essential security controls.
- Secure protocols prevent attackers from intercepting sensitive information.
- Zero Trust Architecture is becoming the modern standard for enterprise security.
- Continuous monitoring and regular updates significantly reduce cyber risks.

---

## Summary

Network security is a critical component of cybersecurity that protects organizations from unauthorized access, malware, data breaches, and service disruptions. By implementing layered security controls such as firewalls, intrusion detection systems, VPNs, secure protocols, and Zero Trust principles, organizations can build resilient networks capable of defending against modern cyber threats while ensuring secure and reliable communication.
