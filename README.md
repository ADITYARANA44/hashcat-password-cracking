# 🔐 Hashcat Password Cracking – IIT Jammu Internship Project

This repository contains the internship project completed as part of the **Cybersecurity Summer Internship** at **IIT Jammu**. The project demonstrates ethical password cracking techniques using **Hashcat**, focusing on dictionary and brute-force attacks.

---

## 👨‍💻 Project Members

- **Aditya Singh Rana**  
- **Rahul Kumar**  
- **Aniket**

---

## 🎯 Project Objectives

- Understand real-world password vulnerabilities  
- Learn and implement Hashcat attacks (dictionary & brute-force)  
- Demonstrate password recovery using example hashes  
- Promote awareness on secure password practices  

---

## 🛠 Tools & Environment

- **OS:** Kali Linux  
- **Tool:** Hashcat v6.x  
- **Wordlist:** rockyou.txt  
- **Hash Algorithm:** MD5  
- **Shell:** Bash, md5sum utility

---

## 🚀 Attack Demonstrations

### 📘 Dictionary Attack Example

- **Password:** `dragon`  
- **Command:**  
  ```bash
  hashcat -m 0 -a 0 hashes.txt rockyou.txt
