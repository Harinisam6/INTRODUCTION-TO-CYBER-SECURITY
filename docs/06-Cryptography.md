# Cryptography

## Overview

Cryptography is the science of protecting information by converting readable data (plaintext) into an unreadable format (ciphertext). Only authorized users possessing the correct decryption key can recover the original information. It plays a fundamental role in modern cybersecurity by ensuring secure communication, protecting sensitive data, verifying identities, and maintaining data integrity.

Today, cryptography is used in almost every digital service, including online banking, e-commerce, cloud storage, messaging applications, VPNs, and secure websites. Without cryptography, confidential information transmitted over the Internet would be vulnerable to interception and misuse.

---

# Objectives of Cryptography

The primary objectives of cryptography are:

- Protect sensitive information
- Secure communication over public networks
- Prevent unauthorized access
- Verify the identity of users
- Ensure data integrity
- Support digital signatures and certificates

---

# Basic Terminology

| Term | Description |
|------|-------------|
| Plaintext | Original readable data |
| Ciphertext | Encrypted unreadable data |
| Encryption | Process of converting plaintext into ciphertext |
| Decryption | Converting ciphertext back into plaintext |
| Key | Secret value used during encryption and decryption |
| Cipher | Mathematical algorithm used for encryption |

---

# Encryption Process

```text
        Plaintext
            │
            ▼
     Encryption Algorithm
            │
            ▼
       Secret/Public Key
            │
            ▼
        Ciphertext
            │
            ▼
     Decryption Algorithm
            │
            ▼
        Original Data
```

---

# Types of Cryptography

Modern cryptography is divided into three major categories.

## 1. Symmetric Cryptography

Symmetric encryption uses the **same key** for both encryption and decryption.

### Working

```text
Shared Secret Key
        │
        ▼
Encrypt --------> Decrypt
```

### Advantages

- Fast encryption
- Efficient for large files
- Less computational overhead

### Disadvantages

- Secure key sharing is difficult.
- If the key is compromised, all encrypted data becomes vulnerable.

### Popular Algorithms

- AES (Advanced Encryption Standard)
- DES (Data Encryption Standard)
- Triple DES
- Blowfish
- Twofish

### Applications

- Disk encryption
- File encryption
- Database encryption
- VPN communication

---

# 2. Asymmetric Cryptography

Asymmetric encryption uses **two different keys**:

- Public Key
- Private Key

The public key encrypts data, while the private key decrypts it.

### Working

```text
Public Key
     │
Encrypt
     │
Ciphertext
     │
Decrypt
     │
Private Key
```

### Advantages

- Secure key exchange
- Digital signatures
- Authentication
- Non-repudiation

### Disadvantages

- Slower than symmetric encryption
- Higher computational cost

### Popular Algorithms

- RSA
- ECC (Elliptic Curve Cryptography)
- Diffie-Hellman
- ElGamal

### Applications

- HTTPS
- SSL/TLS
- Email encryption
- Digital certificates

---

# 3. Hash Functions

Hashing converts data into a fixed-length value known as a **hash** or **message digest**.

Unlike encryption, hashing is **one-way** and cannot be reversed.

### Characteristics

- Fixed output length
- Fast computation
- Collision resistant
- One-way operation

### Popular Algorithms

- SHA-256
- SHA-3
- Bcrypt
- Argon2

### Applications

- Password storage
- Digital signatures
- File verification
- Blockchain

---

# Comparison

| Feature | Symmetric | Asymmetric | Hashing |
|----------|-----------|------------|----------|
| Keys Used | One | Two | None |
| Reversible | Yes | Yes | No |
| Speed | Fast | Slower | Very Fast |
| Main Purpose | Encryption | Secure Key Exchange | Integrity Verification |

---

# Digital Signatures

A digital signature verifies both the authenticity and integrity of digital information.

### Benefits

- Authentication
- Integrity
- Non-repudiation

Common applications include:

- Online banking
- Software distribution
- Electronic contracts
- Government documents

---

# Digital Certificates

Digital certificates verify the identity of websites, organizations, or individuals.

Certificates are issued by trusted organizations called **Certificate Authorities (CA)**.

Examples include:

- SSL Certificates
- TLS Certificates
- Code Signing Certificates

---

# Public Key Infrastructure (PKI)

PKI is a framework used to manage digital certificates and encryption keys.

Major components include:

- Certificate Authority (CA)
- Registration Authority (RA)
- Digital Certificates
- Public Keys
- Private Keys

PKI enables secure online communication through trusted certificate management.

---

# Real-World Example

## HTTPS Secure Communication

When users visit an HTTPS website, their browser performs a TLS handshake with the web server.

During this process:

1. The server presents its digital certificate.
2. The browser verifies the certificate.
3. A secure encryption key is generated.
4. All communication becomes encrypted.

This protects sensitive information such as passwords, credit card details, and personal data from attackers.

---

# Cryptographic Attacks

Attackers attempt to break encryption using various methods.

Common attacks include:

- Brute Force Attack
- Dictionary Attack
- Birthday Attack
- Man-in-the-Middle Attack
- Side-Channel Attack
- Replay Attack

Organizations reduce these risks by using strong algorithms, long encryption keys, and secure authentication mechanisms.

---

## Summary

Cryptography forms the backbone of secure digital communication by protecting confidentiality, ensuring integrity, and enabling authentication. From secure web browsing to online banking and cloud computing, cryptographic techniques safeguard information against unauthorized access and cyber threats. A strong understanding of encryption, hashing, digital signatures, and PKI is essential for every cybersecurity professional and software engineer.
