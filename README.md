# NETWORKWALKS-Komal-BO84-WK3-Password-Cracking-Hash-Analysis
This repository documents my Week 3 practical tasks, focusing on password auditing, hash analysis, dictionary-based attacks, and password security.


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

# W3-PM1: Password Cracking using John the Ripper (GUI)

### Objective
To recover the password of a provided encrypted PDF using John the Ripper GUI by extracting its password hash and processing it through the tool.

### Tools Used
- John the Ripper (GUI)
- John.exe
- OnlineHashCrack PDF Hash Extractor
- Notepad

### Practical Methodology

**Step 1: Installation and Configuration**
- Installed and launched John the Ripper GUI.
- Opened the Settings section.
- Browsed and configured the location of the `john.exe` executable file.

**Step 2: PDF Hash Extraction**
- Downloaded the provided encrypted PDF file.
- Opened the OnlineHashCrack PDF Hash Extractor.
- Uploaded the encrypted PDF to extract its password hash.

Tool: https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php

**Step 3: Hash File Creation**
- Copied the extracted hash value.
- Opened Notepad and saved the hash in a text file named `hash1.txt`.

**Step 4: Password Cracking**
- Opened the hash file using John the Ripper GUI.
- Executed the password-cracking process.
- Retrieved the recovered PDF password.

**Step 5: Flag Extraction**
- Opened the encrypted PDF using the recovered password.
- Accessed the document contents.
- Retrieved the flag provided inside the PDF.

**Step 6: Flag Extraction**
- Did the same for other two provided encrypted file.
- Retrieved the flag provided inside the PDF

### Result
Successfully recovered the password of the encrypted PDFs using John the Ripper GUI and extracted the flags.

---

# W3-PM2: Password Cracking using NetworkWalks Tools

### Objective
To explore browser-based PDF hash extraction and password-cracking utilities using NetworkWalks tools.

### Tools Used
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- Encrypted PDF file

### Practical Methodology

**Step 1: PDF Hash Extraction**
- Accessed the NetworkWalks Hash Calculator.
- Uploaded the provided encrypted PDF file.
- Generated and extracted the PDF password hash.

Tool: https://networkwalks.com/hash-calculator/

**Step 2: Password Cracking**
- Copied the extracted hash value.
- Opened the NetworkWalks Password Cracker.
- Submitted the hash for password recovery.
- Executed the password-cracking process.
- Retrieved the recovered password.

Tool: https://networkwalks.com/password-cracker/

**Step 3: Flag Extraction**
- Opened the encrypted PDF using the recovered password.
- Accessed the document contents.
- Retrieved the flag contained inside the PDF.

### Result
Successfully recovered the encrypted PDF password using NetworkWalks tools and extracted the flag.

---

## Technical Comparison

| Parameter | W3-PM1: John the Ripper | W3-PM2: NetworkWalks |
|---|---|---|
| Platform | Desktop GUI | Web-based |
| Hash Extraction | OnlineHashCrack | NetworkWalks Hash Calculator |
| Password Cracking | John the Ripper GUI | NetworkWalks Password Cracker |
| Hash Input | `hash1.txt` | Direct hash submission |
| Final Objective | PDF password recovery | PDF password recovery |
| Outcome | Flag extracted | Flag extracted |

## Key Learnings

- Understanding PDF password hashes and hash extraction.
- Configuring John the Ripper GUI with its executable.
- Managing extracted hashes using text files.
- Exploring browser-based password recovery tools.
- Understanding the password recovery workflow.
- Accessing protected files after successful password recovery.
- Recognizing the importance of strong PDF passwords.

## Disclaimer

These practical exercises were performed for educational purposes using the encrypted PDF files provided for the internship tasks.

---

**Week 3 Submission | Password Cracking & Hash Analysis**
