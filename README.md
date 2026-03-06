# ⚡ AI Without Boundaries — Live Workshop Platform

**Resource Person:** Dr. C V Krishnaveni  
**Designation:** Lecturer in Computer Science, IQAC Coordinator  
**Institution:** SKR & SKR Government College for Women (Autonomous), Kadapa  
**Live Site:** [https://vkchennuru.github.io/ai-workshop-platform/](https://vkchennuru.github.io/ai-workshop-platform/)

---

## 🚀 What This Is

A **fully free, Firebase-powered, mobile-first workshop platform** for conducting live AI workshops across colleges. Students join from their phones with a single link — no app download, no login required. The admin (resource person) controls everything from a password-protected dashboard.

**Zero hosting cost** — runs entirely on GitHub Pages (free static hosting) + Firebase Realtime Database (free tier).

---

## 📁 File Structure

```
ai-workshop-platform/
├── index.html        ← Student-facing workshop page
├── admin.html        ← Resource person admin dashboard (password protected)
└── README.md         ← This file
```

---

## ✅ Step-by-Step: Using the Platform at a Live Workshop

### BEFORE the Workshop (Do this at home / office)

**Step 1 — Open Admin Dashboard**
```
https://vkchennuru.github.io/ai-workshop-platform/admin.html
```
Password: `DrKrishnaveni2026`

**Step 2 — Create a Session**
- Enter the college name, city/district, date, and workshop type
- Click **"🚀 Create Session & Get Link"**
- A unique student link is generated — example:
  ```
  https://vkchennuru.github.io/ai-workshop-platform/index.html?session=gdc-avanigadda-2026-03-06
  ```

**Step 3 — Save the link**
- Click **"📋 Copy Link"** and save it to WhatsApp or your notes
- Optionally, create a QR code using [qr.io](https://qr.io) for projector display

---

### DURING the Workshop (Live, in the college)

**Step 4 — Share the link with students (3 methods)**

| Method | How |
|--------|-----|
| **WhatsApp** | Share in college WhatsApp group → students tap the link |
| **QR Code** | Display QR on projector → students scan with camera |
| **Projector** | Show short URL on projector — students type it |

**Step 5 — Students join**
- Students open link on their phone
- They enter their **Full Name** and **Group / Stream**
- They click **"Enter Workshop →"** — done!
- All 12 labs, 6 challenges, 10-question quiz and leaderboard load instantly

**Step 6 — Monitor live from Admin Dashboard**
- Keep admin.html open on your laptop
- Watch student count, average score update in real time
- Click **"👁️ View Details"** on any session to see the live leaderboard

---

### AFTER the Workshop

**Step 7 — Download evidence**
- In Admin Dashboard → click **"⬇️ Download CSV"** on the session
- Excel file includes: college name, date, all student names, groups, scores, quiz results
- Use this CSV as **evidence for NAAC/AQAR documentation**

---

## 🛡️ Admin Dashboard Features

| Feature | Details |
|---------|---------|
| 🔐 Password login | `DrKrishnaveni2026` (stored securely in localStorage) |
| ➕ Create sessions | College name, city, date, workshop type |
| 🔗 Student link | Auto-generated GitHub Pages URL with session ID |
| 📊 Live stats | Total colleges, students, sessions, average score |
| 👁️ View session | Per-session leaderboard, group breakdown, student table |
| ⬇️ Download CSV | Full evidence report with all student data |
| 🗑️ Delete session | Remove old sessions to free Firebase quota |

---

## 📱 Student Experience

Students get 6 sections inside the workshop:

| Tab | Content |
|-----|---------|
| 🏠 **Home** | Welcome, session info, personal score, 90-min flow |
| 🧪 **Labs** | 12 hands-on AI labs across 5 discipline groups |
| 🏆 **Challenge** | 6 fun mobile challenges worth 65 points |
| 🧠 **Quiz** | 10 MCQ questions, +5 pts each |
| 📊 **Leaderboard** | Live rankings + AI commentary |
| 🔗 **Tools** | All 16 free AI tools with QR codes |

---

## 🔧 How to Change the Admin Password

1. Open `admin.html` in any text editor
2. Find this line (near line 370):
   ```javascript
   const ADMIN_PASSWORD = "DrKrishnaveni2026";
   ```
3. Change the password string to anything you want
4. Save the file and push to GitHub

---

## ☁️ Firebase (No Changes Needed)

The Firebase project is already configured and connected. The free tier allows:
- **100,000 simultaneous connections**
- **10 GB data transfer / month**
- **1 GB storage**

This is more than enough for any number of workshops.

If you ever need to view or reset the database, go to:  
[https://console.firebase.google.com](https://console.firebase.google.com) → Project: `aai-drcvk-interactive-webapp`

---

## 🌐 GitHub Pages Settings (Already Done)

Your site is deployed from the `main` branch, root folder (`/`).  
URL: `https://vkchennuru.github.io/ai-workshop-platform/`

If you add new files, they go live within **1–2 minutes** of pushing to GitHub.

---

## 📋 Quick Workshop Checklist

```
□ Day before: Create session in admin.html, copy student link
□ Day before: Save link in WhatsApp Saved Messages
□ Workshop day: Share link in college WhatsApp group or show QR
□ During: Keep admin.html open on laptop to monitor
□ After: Download CSV from admin for NAAC evidence
□ After: Note session ID for records
```

---

## 📄 License & Copyright

© 2026 Dr. C V Krishnaveni · All rights reserved  
Platform designed for educational use. Unauthorised redistribution is strictly prohibited.

---

*Built with ❤️ for making AI education accessible across all disciplines.*
