# 🔐 OTP Generation System – Python Capstone Project

**Author:** Manish Kumar Singh (S7616)  
**Project Title:** One-Time Password (OTP) Generator and Verifier  
**Platform Used:** Google Colab  
**IDE:** Jupyter / Colab Notebook  
**Language:** Python  

---

## 📌 Project Overview

This Python-based capstone project implements an OTP (One-Time Password) verification system. It simulates sending a randomly generated 6-digit OTP to a user's email and validates it upon entry. The user is given **three attempts** to enter the correct OTP before access is denied.

---

## 🎯 Objectives

- Generate a 6-digit OTP using Python.
- Simulate sending the OTP via email to a user.
- Prompt the user to enter the received OTP.
- Verify the input against the generated OTP.
- Allow only three attempts for OTP verification.
- Ensure robust error handling and clear user prompts.

---

## 🛠️ Features

- Random OTP generation
- Email sending simulation
- OTP verification logic with attempt limits
- Simple and interactive command-line interface
- Clean and modular code structure

---

## 📦 Libraries Used

```python
import random     # For generating OTP
import smtplib    # For sending OTP via email (SMTP protocol)

🧩 Functions Implemented
generate_otp() – Generates a 6-digit numeric OTP.

send_otp(email, otp) – Simulates sending the OTP to the specified email.

verify_otp(expected_otp) – Prompts user input and verifies with generated OTP. Limits retries to 3 attempts.

🚀 How to Run
Clone or download the repository.

Open the notebook in Google Colab or Jupyter.

Set your email configurations (if real sending is enabled).

Run all cells to test the full OTP flow.
