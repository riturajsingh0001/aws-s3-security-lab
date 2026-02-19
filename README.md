# 💡 Hands-on AWS S3 misconfiguration lab demonstrating real-world cloud security risk & mitigation.


👨‍💻 Author: **Rituraj Singh**

---

## 📌 Overview

This project shows how an AWS S3 bucket can become public due to misconfiguration and how to fix it.

---

## ⚙️ Steps

### 1. Created S3 Bucket
- Disabled Block Public Access

---

### 2. Uploaded File

File: hello.txt

---

### 3. Enabled Static Website Hosting

❌ Got Error:
403 AccessDenied

---

## 🧠 Problem

Bucket was not public because:
- No Bucket Policy

---

## 🛠️ Fix

Added Bucket Policy to allow public access.

---

## ✅ Result

File became accessible in browser

---

## 🔐 Defense

- Enabled Block Public Access again

---

## 📚 Learning


## 📄 Detailed Report

✅ The complete report has been uploaded in PDF format.
- Static hosting ≠ public access  
- Bucket policy is important  
