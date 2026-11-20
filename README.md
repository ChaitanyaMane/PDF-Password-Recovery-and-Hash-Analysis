# PDF Password Recovery & Hash Analysis 🔐

## 👨‍💻 About Me

**Name:** Chaitanya Mane

**Program:** NetworkWalks Cybersecurity Internship

**Focus:** Cybersecurity, Ethical Hacking, Networking, and Security Testing

## 📌 Project Information

| Field | Details |
|---|---|
| Portfolio | Cybersecurity Internship Portfolio |
| Organization | NetworkWalks |
| Current Completed Project |  Password Cracking |
| Primary Lab OS | Kali Linux |
| Host OS | Ubuntu Linux |


## Overview
A hands-on cybersecurity project focused on exploring password storage mechanisms, cryptographic hashing, and vulnerability assessment. In a controlled environment, I extracted the cryptographic hash from an encrypted PDF document and utilized offline password-cracking techniques to recover the credentials and evaluate password strength.

---

## 🛠️ Tools & Environment
* **John the Ripper (CLI & GUI):** Configured and linked the graphical interface to the command-line core to execute hash-cracking attacks.
* **Online Hash Crack Workspace:** Used to extract the underlying password hash from the encrypted PDF file.
* **Notepad / Text Editor:** Formatted and stored the extracted hash data for processing.

---

## ⚙️ Methodology & Workflow

1. **Environment Setup:** Installed both the CLI and GUI versions of John the Ripper, configuring the GUI to interface directly with the CLI engine.
2. **Hash Extraction:** Analyzed the encrypted PDF using the Online Hash Crack workspace to isolate and extract its underlying password hash (as modern systems store hashes rather than plaintext credentials).
3. **Hash Formatting:** Transferred the extracted hash into a clean text file to prepare it for offline auditing.
4. **Password Auditing:** Loaded the hash file into John the Ripper and initiated a cracking session against the extracted hash.
5. **Verification:** Successfully recovered the plaintext password and verified access by unlocking the target PDF document.

---

## 💡 Key Security Takeaways
* **Hashing ≠ Invulnerability:** While hashing protects plaintext passwords at rest, weak, short, or predictable passwords remain highly vulnerable to offline dictionary and brute-force attacks using tools like John the Ripper.
* **Defense-in-Depth:** Securing sensitive data requires enforcing strong password policies (length, complexity, and uniqueness) paired with Multi-Factor Authentication (MFA) and modern, salted key-derivation functions.

---

## ⚠️ Disclaimer
*This project was conducted strictly within a controlled, authorized environment for educational and defensive research purposes. Unauthorized password cracking or accessing systems without explicit permission is illegal and unethical.*
