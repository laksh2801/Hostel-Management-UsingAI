# 🏨 AI-Enhanced Hostel Management System

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Tech](https://img.shields.io/badge/Built%20With-PHP%20%7C%20MySQL%20%7C%20HTML%20%7C%20CSS-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Author](https://img.shields.io/badge/Author-Laksh%20Kadyan-orange)

> 🎓 Developed by **Laksh Kadyan**, Jain University  
> 🚀 A complete hostel management web application with an AI-powered chatbot, sleek design, and dynamic functionality — no templates, no prebuilt branding. 100% original.

---

## 📋 Project Description

This is a smart **Hostel Management System** that simplifies accommodation tasks for both **admin** and **students**. It handles room bookings, records, payments, and FAQs using a **custom-built AI chatbot** embedded directly in the footer for a seamless experience.

---

## 🌟 Key Features

- 🔐 **Admin & Student Login**
- 🧑‍💼 Admin can add, edit, delete student records
- 🛏️ Real-time **room booking** system
- 📅 Year-based accommodation (1st, 2nd, 3rd year)
- 💬 **AI Chatbot** (footer-based with static JS logic)
- 🧾 **Dynamic bill generation** with selected options
- 📸 Receipt view and print functionality
- 💳 **Demo payment window** with auto-calculated totals
- 🧠 30+ quick response triggers for common queries
- 🔁 Smart chatbot flow resuming after actions like "Payment Success"
- 🔒 Secure login forms with validation
- 📦 All **"CodeAstro"** references removed!

---

## 🧠 AI Chatbot Overview

> **"Hi, how can I help?"** 🤖  
This project includes a custom JavaScript-based AI Chatbot built without database integration. Instead, it uses keyword triggers to return crisp, predefined responses.

### 💬 Key Topics:
- Fees & structure  
- Canteen menu  
- Rules and regulations  
- Security & surveillance  
- Electricity, water, WiFi  
- Payment help  
- Room types  
- Year-specific options

> ✅ Chatbot resumes flow after payment  
> ✅ All responses are short, structured, and non-repetitive  
> ✅ Embedded cleanly in the footer for access from any page

---

## 🖼️ Screenshots

> Add your own screenshots in the `/screenshots/` folder.

| Login Page | Dashboard | Payment |
|------------|-----------|---------|
| ![Login](./screenshots/login.png) | ![Dashboard](./screenshots/dashboard.png) | ![Payment](./screenshots/payment.png) |

---

## 🗂️ File Structure

```plaintext
HostelManagement/
│
├── admin/                      # Admin dashboard files
│   ├── dashboard.php
│   ├── manage-students.php
│   └── ...
│
├── student/                    # Student-facing modules
│   ├── index.php
│   ├── register.php
│   └── ...
│
├── chatbot/                    # AI chatbot scripts
│   └── chatbot.js
│
├── includes/                   # Config and helper scripts
│   └── config.php
│
├── images/                     # Icons, hostel images, QR code
│   └── qr.png
│
├── screenshots/                # Your app screenshots (add yourself)
│   └── *.png
│
├── database.sql                # Import into phpMyAdmin
├── index.php                   # Landing page
└── README.md                   # You're reading this!
