# CTF@CIT 2026 Writeups

This repository contains my writeups for challenges from **CTF@CIT 2026**.

The focus of this repo is not just solving challenges, but breaking down:
- How vulnerabilities were identified  
- How solutions were derived  
- What techniques can be reused in real-world scenarios  

---

## 🧠 Skills Demonstrated

- Web Exploitation (IDOR, SSRF, Cookie Forgery)
- Cryptography (RSA attacks, hashing, encoding layers)
- Reverse Engineering (ELF analysis, optimization, runtime debugging)
- Forensics (file analysis, metadata extraction, hidden data)
- Steganography (zero-width Unicode, embedded data, file abuse)

---

## 📂 Challenge Categories

### 🕵️ Web Exploitation
- Intern Portal (IDOR)
- Flask Cookie Forgery (Session manipulation + SSRF)

### 🔐 Cryptography
- Baby Exponent (Low exponent RSA attack)
- The Onion (Multi-layer Base64 + MD5 cracking)
- SAM, I Am (NTLM brute-force)

### 🧬 Reverse Engineering
- Escape Room (Binary logic + GDB runtime extraction)
- Faultline (Algorithmic optimization / hill climbing)

### 🧾 Forensics
- Larping 101 (PPTX XML extraction)
- The Evil Files (Email header analysis)

### 🖼️ Steganography
- There’s No Room Left (Zero-width Unicode encoding)
- Image Stego (Plaintext inside binary data)

### ⚙️ Misc / Warmups
- Discord (OSINT / navigation)
- Robots.txt (hidden content discovery)

---

## 🧪 Methodology

Across challenges, a consistent approach was followed:

1. **Recon First**
   - `strings`, `file`, `exiftool`, `binwalk`
2. **Understand the Hint**
   - Titles often directly indicate technique
3. **Break Assumptions**
   - Hidden ≠ encrypted
   - Simple ≠ obvious
4. **Automate When Needed**
   - Python scripts for decoding and brute-force
5. **Validate, Don’t Guess**
   - Every exploit is confirmed (not assumed)

---

## 👤 Author

Tanish Panwar  
B.Tech CSE (AI/ML)  
  
---

## ⭐ Note

Some challenges are intentionally simple (warmups), while others involve deeper exploitation or reverse engineering. The goal is to show **range**, not just difficulty.
