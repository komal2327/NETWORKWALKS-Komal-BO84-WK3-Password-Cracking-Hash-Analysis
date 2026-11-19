# NETWORKWALKS-Komal-BO84-WK3-Password-Cracking-Hash-Analysis
This repository documents my Week 3 practical tasks, focusing on password auditing, hash analysis, dictionary-based attacks, and password security.
# Week 3 – Password Cracking & Hash Analysis

## Cybersecurity Internship | Practical Submission

## ⭐ Project Highlights

![John the Ripper](https://img.shields.io/badge/John_the_Ripper-Password_Auditing-red?style=for-the-badge&logo=kalilinux&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-Lab_Environment-blue?style=for-the-badge&logo=kalilinux&logoColor=white)
![Hash Analysis](https://img.shields.io/badge/Hash_Analysis-MD5%20%7C%20SHA-orange?style=for-the-badge)
![Dictionary Attack](https://img.shields.io/badge/Dictionary_Attack-Wordlists-purple?style=for-the-badge)
![NetworkWalks](https://img.shields.io/badge/NetworkWalks-Online_Tools-green?style=for-the-badge)
![PDF Hash Extraction](https://img.shields.io/badge/PDF-Hash_Extraction-yellow?style=for-the-badge)
![Password Security](https://img.shields.io/badge/Password_Security-Analysis-informational?style=for-the-badge)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Hands--On_Practice-black?style=for-the-badge)



This repository documents my Week 3 practical tasks, focusing on password auditing, hash analysis, dictionary-based attacks, and password security.

The objective was to understand how password hashes work, explore password-cracking techniques, and gain practical experience with industry-relevant security tools.

---

## 📌 Tasks Overview

| Task ID | Practical | Tools |
|---|---|---|
| W3-PM1 | Password Cracking with John the Ripper | John the Ripper, Kali Linux |
| W3-PM2 | Password Cracking with NW Tools | NetworkWalks Hash Calculator, Password Cracker |

---

# W3-PM1: Password Cracking with John the Ripper

### Objective
To understand password-cracking techniques using John the Ripper and explore how dictionary attacks can identify weak passwords from their corresponding hashes.

### Tool Used
- John the Ripper
- Kali Linux
- Custom Wordlist

### Practical Activities
1. Installed and verified John the Ripper in Kali Linux.
2. Generated a sample password hash.
3. Created a custom wordlist containing test passwords.
4. Executed a dictionary-based password attack.
5. Observed the password recovery process.
6. Verified the recovered password.

### Commands Used

**Check installation**
```bash
john --version
```

**Generate a sample MD5 hash**
```bash
echo -n "Cyber123" | md5sum
```

**Create a wordlist**
```bash
printf "admin\npassword\nCyber123\nwelcome\n" > wordlist.txt
```

**Perform dictionary attack**
```bash
john --format=raw-md5 --wordlist=wordlist.txt hash.txt
```

**Display recovered password**
```bash
john --show --format=raw-md5 hash.txt
```

### Key Learnings
- Understanding password hashes.
- Dictionary-based password attacks.
- Wordlist creation and usage.
- Password recovery using John the Ripper.
- Importance of strong password policies.

---

# W3-PM2: Password Cracking with NetworkWalks Tools

### Objective
To explore online hashing and password-cracking utilities and understand how hash generation and dictionary-based password recovery work.

### Tools Used

**1. NetworkWalks Hash Calculator**

https://networkwalks.com/hash-calculator/

Used to explore hash generation and PDF password hash extraction.

**2. NetworkWalks Password Cracker**

https://networkwalks.com/password-cracker/

Used to understand dictionary-based PDF password recovery.

### Practical Activities

1. Explored the NetworkWalks Hash Calculator.
2. Generated hashes using sample input.
3. Created a password-protected test PDF.
4. Extracted the PDF password hash.
5. Used the Password Cracker to perform a dictionary attack.
6. Observed and verified the password recovery result.

### Key Learnings
- Understanding hash generation.
- Identifying different hash formats.
- PDF password hash extraction.
- Dictionary-based password recovery.
- Understanding password complexity and security.

---

## 🔍 Technical Comparison

| Feature | John the Ripper | NetworkWalks Tools |
|---|---|---|
| Platform | Kali Linux / CLI | Web-based |
| Main Purpose | Password auditing | Hash analysis and PDF password recovery |
| Attack Method | Dictionary and other supported modes | Dictionary attack |
| Custom Wordlist | Supported | Supported by Password Cracker |
| Practical Focus | General password auditing | PDF password recovery and hash generation |

---

## 🧠 Overall Learning Outcomes

Through these practical exercises, I gained knowledge of:

- Password hashing and hash formats.
- Dictionary-based password attacks.
- Password recovery methodologies.
- Usage of John the Ripper.
- Online hash analysis utilities.
- Importance of secure password storage.
- Common password weaknesses and security practices.

## 🔐 Security Recommendations

- Use long and unique passwords.
- Avoid commonly used passwords.
- Use multi-factor authentication (MFA).
- Store passwords using secure, salted password-hashing algorithms such as Argon2id.
- Perform password audits only with proper authorization.

## ⚙️ Lab Environment

- Operating System: Kali Linux
- Tool: John the Ripper
- Online Tools: NetworkWalks
- Attack Type: Dictionary Attack
- Testing: Self-created sample hashes and password-protected PDF

## ⚠️ Disclaimer

All practical exercises are intended for educational and authorized security-testing purposes. Only self-created sample passwords, hashes, and test files were used.

## 📚 References

- John the Ripper: https://www.openwall.com/john/
- NetworkWalks Hash Calculator: https://networkwalks.com/hash-calculator/
- NetworkWalks Password Cracker: https://networkwalks.com/password-cracker/

---

**Week 3 Submission | Cybersecurity Internship**

Learning through practical implementation and continuous exploration of cybersecurity concepts.
