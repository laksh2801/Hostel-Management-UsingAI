# 🏨 AI-Enhanced Hostel Management System

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Tech](https://img.shields.io/badge/Built%20With-PHP%20%7C%20MySQL%20%7C%20HTML%20%7C%20CSS-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Author](https://img.shields.io/badge/Author-Laksh%20Kadyan-orange)

> 🎓 Developed by **Laksh Kadyan**, Jain University  
> 💡 A full-featured hostel management web app with AI chatbot integration and dynamic billing — crafted with originality and functionality in mind.

---

## 📋 Project Description

This is a smart **Hostel Management System** tailored for academic use. It handles everything from **student registration**, **admin management**, and **room allocation** to **automated chatbot responses**, **bill calculation**, and a **mock payment system** — all wrapped in a clean, responsive interface.

> ✅ All branding replaced with **original work by Laksh Kadyan**  
> ✅ Includes chatbot integration, multi-role login, and dynamic UI elements  

---

## 🌟 Key Features

- 🔐 Student & Admin Login
- 🧑‍💼 Admin can manage student records
- 📚 Student can register, book rooms, and view bills
- 🛏️ Dynamic year-based room booking (1st, 2nd, 3rd year)
- 💬 AI-powered chatbot with 30+ instant responses
- 🧾 Smart payment module with calculated totals
- 📄 Bill summary display and printing option
- 🧠 Chatbot resumes flow after payment
- 🖼️ Screenshot-ready layout
- 📦 No dependencies or branding from external templates

---

## 🤖 AI Chatbot Overview

The chatbot is custom-coded in **JavaScript**, designed to simulate smart responses without backend processing.

### 💬 Topics it can answer:

- Room types & facilities  
- Rules and regulations  
- Water, electricity & Wi-Fi  
- Fees and canteen info  
- Security & visitor policy  
- Payment instructions  

> It appears fixed in the footer on every page  
> Automatically resumes with “Hi, how can I help?” after payments  
> Built without any database — fast and lightweight

---

## 🖼️ Screenshots

> Below are key screens from the Hostel Management System:

### 🔐 Login Pages

| Student Login | Admin Login |
|---------------|-------------|
| ![](./screenshots/student-login.jpg) | ![](./screenshots/admin-login.jpg) |

### 📊 Dashboard

| Dashboard View |
|----------------|
| ![](./screenshots/dashboard.jpg) |

### 💳 Payment & Bill

| Payment Page |
|--------------|
| ![](./screenshots/payment.jpg) |

### 🤖 Chatbot

| AI Chatbot in Footer |
|----------------------|
| ![](./screenshots/chatbot.jpg) |

---

## 🗂️ Project Structure

```plaintext
HostelManagement/
│
├── admin/                      # Admin dashboard pages
│   ├── dashboard.php
│   ├── manage-students.php
│   └── ...
│
├── student/                    # Student interface
│   ├── index.php
│   ├── register.php
│   └── ...
│
├── chatbot/                    # AI chatbot logic (JS)
│   └── chatbot.js
│
├── includes/                   # Configuration files
│   └── config.php
│
├── images/                     # QR code, icons, etc.
│   └── qr.jpg
│
├── screenshots/                # Screenshots for README
│   └── *.jpg
│
├── database.sql                # MySQL database schema
├── index.php                   # Main landing page
└── README.md                   # Project documentation
