
# AI Without Boundaries – Interactive Workshop Platform

An interactive web platform designed for **AI workshops, webinars, and training sessions**.
This platform allows students to **join a live workshop using their mobile phones**, perform **hands-on AI labs**, participate in **quizzes and challenges**, and view a **real-time leaderboard**.

The system is built using **HTML, JavaScript, Firebase Realtime Database, and Netlify hosting**.

---

## 🎯 Project Purpose

Traditional workshops are mostly lecture-based.
This platform converts a workshop into a **live interactive experience** where participants:

* Join using a link shared by the resource person
* Enter their name and academic stream
* Perform hands-on AI activities
* Participate in quizzes and challenges
* See real-time results and leaderboard updates

The platform also helps the resource person **collect workshop evidence and analytics**.

---

## 👩‍🏫 Resource Person

**Dr. C V Krishnaveni**
Lecturer in Computer Science
SKR & SKR Government College for Women (Autonomous), Kadapa

Workshop Theme:

> **Artificial Intelligence Without Boundaries: Practical Insights Across Disciplines**

---

## 🧩 System Architecture

The system contains two main web interfaces:

### 1️⃣ Admin Dashboard

File: `admin.html`

Used by the **resource person** to manage workshops.

Features:

* Admin login authentication
* Create workshop sessions
* Generate session links for participants
* Monitor live student participation
* View session statistics
* Export student data (CSV)
* View detailed session reports

Admin password is defined inside the file:

```javascript
const ADMIN_PASSWORD = "DrKrishnaveni2026";
```

You can change this password for security.

Example admin page:

```
https://your-domain/admin.html
```

---

### 2️⃣ Student Workshop Interface

File: `index.html`

Students open a session link and join the workshop.

Features:

* Join using name and academic stream
* Participate in hands-on AI labs
* Use real AI tools
* Complete interactive challenges
* Attempt AI knowledge quiz
* View real-time leaderboard
* Access curated AI resources

Example workshop link:

```
https://your-domain/?session=SESSION_ID
```

Students can join using **mobile phones**.

---

## 🧠 Workshop Learning Activities

The platform includes interdisciplinary AI labs:

### 🌿 Life Sciences

* Plant disease detection
* Wildlife species recognition

### 🛒 Commerce

* Customer sentiment analysis
* Recommendation engine simulation

### 📖 Humanities

* Language translation experiments
* AI bias exploration

### ⚛️ Math & Physical Sciences

* Data pattern analysis
* AI prediction models

### 💻 Computer Science

* Prompt engineering
* AI-assisted coding

---

## 🏆 Interactive Components

The platform includes multiple engagement features:

* Hands-on AI Labs
* Grand Challenge
* AI Knowledge Quiz
* Live Leaderboard
* QR Codes for AI tools
* Real-time analytics using Firebase

---

## ⚙️ Technologies Used

Frontend

* HTML5
* CSS3
* JavaScript

Backend

* Firebase Realtime Database

Hosting

* Netlify (or GitHub Pages)

Libraries

* Firebase Web SDK
* QRCode.js

Example Firebase initialization used in the project:

```javascript
import { initializeApp } from "firebase-app";
import { getDatabase } from "firebase-database";
```

The database stores:

* workshop sessions
* student participants
* quiz scores
* challenge points

---

## 🚀 Deployment

You can deploy this project using **any static hosting platform**.

Recommended:

* Netlify
* GitHub Pages
* Firebase Hosting

Steps:

1. Upload project to GitHub
2. Deploy repository to Netlify or GitHub Pages
3. Configure Firebase database
4. Update Firebase credentials inside both files

```
admin.html
index.html
```

---

## 📊 Workshop Workflow

1️⃣ Admin opens the dashboard
2️⃣ Creates a workshop session
3️⃣ Platform generates a session link
4️⃣ Students open the link on their phones
5️⃣ Students complete labs and quizzes
6️⃣ Results appear live in the admin dashboard

---

## 📷 Use Case

This platform is designed for:

* AI awareness workshops
* International webinars
* Faculty development programs
* Undergraduate training sessions
* interdisciplinary AI education

---

## 🔒 Security Notes

* Admin password is stored in the frontend code
* For production systems, secure authentication should be implemented
* Firebase rules should restrict unauthorized database access

---

## 📄 License

© 2026 Dr. C V Krishnaveni
All rights reserved.

This platform is designed for **academic workshop use only**.

Unauthorized copying or redistribution is prohibited.

---

## ⭐ Acknowledgement

Developed as part of the **AI Without Boundaries Workshop Initiative**
to promote **hands-on Artificial Intelligence education across disciplines**.

---

## 📬 Contact

Dr. C V Krishnaveni
Department of Computer Science
SKR & SKR Government College for Women (Autonomous), Kadapa

