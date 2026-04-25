# 🛡️ DOCSHIELD

### *Emergency Safety Alert System for Doctors During Night Duty*

## 📌 Overview

**DocShield** is a healthcare safety web application designed to protect doctors and medical staff during emergency or vulnerable situations, especially during night duty. The platform enables instant SOS alerts, emergency contact notifications, and location-enabled distress support.

It acts as a **digital safety shield for healthcare professionals** by providing fast emergency communication and response assistance.

---

## 🚨 Problem Statement

Doctors, especially those working late shifts, often face:

* Safety risks during night duty
* Delayed emergency communication
* Lack of immediate support during threats or distress
* Difficulty notifying trusted people instantly

**DocShield** addresses this by creating a rapid-response personal safety network.

---

# ✨ Features

## 🔐 Authentication System

* Secure Sign Up / Login for doctors
* User profile management
* Department and contact registration
* Session-based authentication using Supabase

## 🆘 One-Tap SOS Emergency Alert

* Instant emergency trigger button
* Sends distress alerts immediately
* Logs alert activity
* Quick-response emergency support mechanism

## 👥 Emergency Contacts Management

Users can register up to 4 trusted contacts such as:

* Hospital Security
* Colleagues
* Superintendent / Duty Officer
* Family Members

Features:

* Add contacts
* Edit contacts
* Delete contacts
* Categorized emergency support network

## 📍 Safety Dashboard

Dashboard includes:

* Registered emergency contacts count
* Last alert status
* Safety indicator monitoring
* Centralized emergency access

## 👤 Doctor Profile Management

* Update personal details
* Manage phone number
* Department details
* Secure sign out

---

# 🏗️ Tech Stack

## Frontend

* React + TypeScript
* Vite
* Tailwind CSS
* ShadCN UI

## Backend / Database

* Supabase
* Authentication Services
* PostgreSQL (via Supabase)

## Additional Tools

* Lucide Icons
* Git & GitHub

---

# ⚙️ System Workflow

1. User registers/login
2. Adds trusted emergency contacts
3. Monitors safety through dashboard
4. In emergency, taps SOS button
5. Alert is triggered and emergency network is notified
6. Alert logs are maintained for tracking

---

# 📂 Project Structure

```bash
DOCSHIELD/
│── src/
│   ├── pages/
│   ├── components/
│   ├── hooks/
│   └── lib/
│
│── public/
│── supabase/
│── package.json
│── vite.config.ts
```

---

# 🔍 Key Modules

## Authentication Module

Handles:

* Registration
* Login
* Session management
* User authorization

## Emergency Alert Module

Responsible for:

* SOS trigger
* Alert logging
* Distress signaling

## Contact Management Module

Responsible for:

* Contact storage
* Emergency routing
* Trusted support network

---

# 💡 Unique Highlights

✅ Doctor-focused safety platform
✅ Real-time emergency alert support
✅ Simple one-tap SOS system
✅ Emergency contact categorization
✅ Lightweight and responsive interface
✅ Healthcare safety-oriented solution

---

# 🚀 Installation

```bash
git clone https://github.com/yourusername/DOCSHIELD.git
cd DOCSHIELD
npm install
npm run dev
```

---

## 🔑 Environment Variables

Create a `.env` file:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_key
```

---

# Future Enhancements

* Live GPS location sharing
* SMS-based emergency alerts
* Hospital security integration
* Voice activated SOS
* AI-based risk detection
* Mobile app deployment

---

# 📖 Use Case

Designed for:

* Doctors
* Resident physicians
* Night duty medical staff
* Hospitals and emergency departments

---

# 👩‍💻 Author

**Vaishnavi**
Built with a vision to improve **doctor safety through technology.**

---

## ⭐ Support

If you like this project:

* Star the repository
* Fork the project
* Contribute improvements

---

## 📜 License

This project is for academic and innovation purposes.

---

> **DocShield — Protecting those who protect lives.** 🩺🛡️
