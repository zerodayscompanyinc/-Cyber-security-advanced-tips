# Cybersecurity Interview Notes

## Part 1: Most Asked Questions

### 1. What is cybersecurity?
Cybersecurity means keeping computers, networks, apps, and data safe from attacks and from people who shouldn't have access. It combines tools, processes, and good habits to stop breaches. Firewalls, antivirus software, and encryption are common examples. The overall aim is to protect confidentiality, integrity, and availability of information.

### 2. What is cryptography?
Cryptography is the science of protecting information by turning it into a form nobody can read without the right key. It covers data that is stored and data that is being sent. It relies on math-based algorithms and keys. You see it in secure messaging, online banking, and digital signatures.

### 3. What is encryption?
Encryption converts readable data (plaintext) into scrambled data (ciphertext) so only people with the proper key can read it. It is used in email, online banking, and secure websites. It protects data from being stolen, intercepted, or accessed without permission.

### 4. What is a threat?
A threat is anything that could take advantage of a weakness in a system and cause damage. Threats can come from hackers, malware, natural disasters, or people inside the organization. They can affect confidentiality, integrity, or availability. Spotting threats early is a key step when planning security.

### 5. What is a vulnerability?
A vulnerability is a flaw or weak spot in a system, application, or network that an attacker could use. Causes include software bugs, bad configuration, and weak controls. Vulnerabilities make unauthorized access and data breaches more likely. Regular assessments and keeping systems updated are the best ways to reduce them.

### 6. What is risk?
Risk is the possible loss or damage when a threat takes advantage of a vulnerability. It is judged by how likely an attack is and how bad the impact would be. Organizations run risk assessments to rank their problems. Good security aims to lower risk before something goes wrong.

### 7. What is a firewall?
A firewall is hardware or software that watches and controls network traffic. It sits between a trusted internal network and an untrusted outside network, and it allows or blocks traffic based on set rules. It is one of the basic building blocks of network security.

### 8. What is an IDS?
An Intrusion Detection System (IDS) watches network and system activity for suspicious behavior and alerts administrators. It does not block attacks; it helps catch them early. It works by studying traffic patterns and comparing them with known attack signatures.

### 9. What is an IPS?
An Intrusion Prevention System (IPS) finds malicious activity and blocks it. Unlike an IDS, it acts in real time and takes action automatically when it spots a threat. It is usually used together with firewalls and other security tools.

### 10. What is a botnet?
A botnet is a group of infected devices that criminals control remotely. The devices (called bots or zombies) do harmful tasks without their owners knowing. Botnets are often used for DDoS attacks, spam, and data theft. They are normally built using malware, so finding and removing malware helps prevent infections.

### 11. What is the CIA triad?
The CIA triad is the core model of information security:
- **Confidentiality:** only authorized people can see sensitive information.
- **Integrity:** data stays accurate and has not been altered.
- **Availability:** systems and data can be used when needed.

It is the foundation for designing secure systems.

### 12. What is symmetric encryption?
Symmetric encryption uses one shared secret key to both encrypt and decrypt. It is fast and works well for large amounts of data. Common algorithms are AES, DES, and Blowfish. Its main weakness is sharing the key safely between the two sides, but it is still widely used.

### 13. What is asymmetric encryption?
Asymmetric encryption uses a pair of keys: a public key and a private key. Data locked with the public key can only be unlocked with the private key. This makes it safer for exchanging data over networks you don't trust. RSA and Diffie-Hellman are well-known examples, and it is used in SSL/TLS certificates and secure email.

### 14. What is hashing?
Hashing turns data into a fixed-length value called a hash. Unlike encryption, it is one-way and can't easily be reversed. It is used for storing passwords and checking data integrity. Changing even a tiny part of the input produces a totally different hash. SHA-256 and SHA-512 are popular algorithms.

### 15. What is two-factor authentication (2FA)?
2FA requires two kinds of proof before giving access. Usually this is a password plus something else, like a one-time code (OTP) or a fingerprint or face scan. Even if the password is stolen, getting in is much harder. Many online services use it to protect accounts.

### 16. What is penetration testing?
Penetration testing, also called ethical hacking, means simulating attacks on a system, network, or app to find weaknesses before real attackers do. Security professionals use specialized tools and techniques, and the results help the organization strengthen its defenses. It is an important part of security assessments.

### 17. What is a vulnerability assessment?
A vulnerability assessment is the process of finding, analyzing, and ranking security weaknesses in systems and networks. It shows an organization where it stands security-wise. Automated scanners usually look for known vulnerabilities, and the report includes recommended fixes. Doing it regularly lowers the chance of a successful attack.

### 18. What is XSS?
Cross-Site Scripting (XSS) is a web vulnerability that lets attackers put malicious scripts into a website. The scripts then run in the visitor's browser without them knowing. They can steal cookies, session tokens, or personal data. Input validation and output encoding help prevent it. It is one of the most common web app flaws.

### 19. What is SQL injection?
SQL injection is an attack on database-driven applications where the attacker enters malicious SQL through input fields. It can expose private data or change database records. It usually happens because of poor input validation. Using parameterized queries is the main defense.

### 20. What is phishing?
Phishing is a social engineering attack in which the attacker pretends to be a trusted source to steal sensitive information. It usually comes through emails, messages, or fake websites, aiming to get usernames, passwords, or financial details. Attackers often create urgency to rush the victim. Security awareness training reduces the risk.

### 21. What is a DDoS attack?
A Distributed Denial of Service (DDoS) attack overwhelms a server, network, or application with too much traffic. Many compromised devices send huge numbers of requests, so real users can't use the service. It can cause long downtime and financial loss. Traffic filtering and DDoS protection services help reduce the impact.

### 22. What is CSRF?
Cross-Site Request Forgery (CSRF) is a web attack that tricks a logged-in user into doing something they didn't intend. It abuses the trust a web app has in the user's browser. Victims may unknowingly change a password or transfer money. CSRF tokens are the usual defense, and secure session management also helps.

### 23. What is port scanning?
Port scanning is checking a system to find which ports are open and what services are running. Security professionals use it for network analysis and vulnerability assessments, but attackers also use it to learn about targets. Nmap is a widely used tool. Open ports that aren't properly secured can expose weaknesses.

### 24. What is DNS monitoring?
DNS monitoring means tracking and analyzing Domain Name System activity. It confirms domain names resolve to the correct IP addresses, and it helps catch unauthorized changes and suspicious behavior. It also supports service reliability and availability. Organizations use it to strengthen network security.

### 25. What is salting?
Salting means adding random data to a password before hashing it. This makes every hash unique, even if two users have the same password. It helps defend against rainbow table attacks and greatly improves password security. Modern login systems combine salting with strong hashing algorithms.

### 26. What is a VPN?
A Virtual Private Network (VPN) creates a secure, encrypted connection over the internet. It protects data from eavesdropping and interception and hides the user's IP address, which helps with privacy. VPNs are often used to reach company networks remotely and are common in both personal and business settings.

### 27. What is SSL?
Secure Sockets Layer (SSL) is a protocol for securing communication between clients and servers. It encrypts data in transit and uses certificates to verify a website's identity. It protects things like login details and payment information. Today SSL has mostly been replaced by the more secure TLS protocol.

### 28. What is SIEM?
Security Information and Event Management (SIEM) is a central security monitoring solution. It gathers logs and security events from many systems and devices, then analyzes them to spot suspicious activity and threats. Security teams use it for investigating incidents and for compliance reports. It gives better visibility across the organization's IT environment.

---

## Part 2: Coding Questions (Python)

### 1. Password strength checker
**Task:** Check whether a password is strong.

```python
password = input("Enter Password: ")

if (len(password) >= 8 and
        any(c.isupper() for c in password) and
        any(c.islower() for c in password) and
        any(c.isdigit() for c in password)):
    print("Strong Password")
else:
    print("Weak Password")
```

### 2. Caesar cipher encryption
**Task:** Encrypt text using a Caesar cipher.

```python
text = input("Enter Text: ")
shift = 3

encrypted = ""
for char in text:
    encrypted += chr(ord(char) + shift)

print("Encrypted:", encrypted)
```

> Note: this simple version shifts every character, so letters near the end of the alphabet don't wrap around. A wrap-around version is shown in the extras at the end.

### 3. Caesar cipher decryption
**Task:** Decrypt the encrypted text.

```python
text = input("Enter Encrypted Text: ")
shift = 3

decrypted = ""
for char in text:
    decrypted += chr(ord(char) - shift)

print("Decrypted:", decrypted)
```

### 4. Generate a random password
**Task:** Generate a secure random password.

```python
import random
import string

length = 12
chars = string.ascii_letters + string.digits + "!@#$%"

password = ''.join(random.choice(chars) for _ in range(length))
print(password)
```

> Note: for real security, use the `secrets` module instead of `random` (see extras).

### 5. Hash a password using SHA-256
**Task:** Convert a password into a hash value.

```python
import hashlib

password = input("Enter Password: ")
hash_value = hashlib.sha256(password.encode()).hexdigest()

print(hash_value)
```

### 6. File integrity checker
**Task:** Generate the hash of a file.

```python
import hashlib

filename = "sample.txt"

with open(filename, "rb") as f:
    data = f.read()

hash_value = hashlib.md5(data).hexdigest()
print(hash_value)
```

> Note: MD5 is outdated and can be forged on purpose. SHA-256 is the better choice.

### 7. Simple port scanner
**Task:** Check whether a port is open.

```python
import socket

host = "google.com"
port = 80

s = socket.socket()
result = s.connect_ex((host, port))

if result == 0:
    print("Port Open")
else:
    print("Port Closed")

s.close()
```

> Only scan systems you own or have permission to test.

### 8. IP address validator
**Task:** Validate an IPv4 address.

```python
import ipaddress

ip = input("Enter IP: ")

try:
    ipaddress.ip_address(ip)
    print("Valid IP")
except ValueError:
    print("Invalid IP")
```

> Note: `ip_address` also accepts IPv6. To accept only IPv4, use `ipaddress.IPv4Address(ip)`.

### 9. Brute force simulation
**Task:** Find a password from a small list.

```python
correct_password = "admin123"
passwords = ["123456", "admin", "admin123", "password"]

for pwd in passwords:
    if pwd == correct_password:
        print("Password Found:", pwd)
        break
```

---

## Part 3: Additional Interview Coding Questions

1. Build a keylogger detector.
2. Create a password manager.
3. Build a network packet sniffer.
4. Create a URL phishing detector.
5. Detect malware signatures from files.
6. Build a login authentication system.
7. Create a vulnerability scanner.
8. Detect SQL injection patterns in input.
9. Build a file encryption/decryption tool.
10. Create a log monitoring system.

---

## Extras: Improved Versions

**Caesar cipher with wrap-around (letters only):**

```python
def caesar(text, shift):
    result = ""
    for ch in text:
        if ch.isalpha():
            base = ord('A') if ch.isupper() else ord('a')
            result += chr((ord(ch) - base + shift) % 26 + base)
        else:
            result += ch
    return result

encrypted = caesar("Hello, World!", 3)
decrypted = caesar(encrypted, -3)
print(encrypted, decrypted)
```

**Secure random password using `secrets`:**

```python
import secrets
import string

chars = string.ascii_letters + string.digits + "!@#$%"
password = ''.join(secrets.choice(chars) for _ in range(12))
print(password)
```

**File hash using SHA-256 (reads in chunks):**

```python
import hashlib

h = hashlib.sha256()
with open("sample.txt", "rb") as f:
    for block in iter(lambda: f.read(4096), b""):
        h.update(block)

print(h.hexdigest())
```
