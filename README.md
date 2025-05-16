# AbroadWork Indonesia

> 🇮🇩 Job portal tailored for Indonesian workers seeking legal, high-demand job opportunities abroad — part of the AbroadWork global ecosystem.

---

## 🌏 Overview

AbroadWork Indonesia is a modern job-matching platform designed to support Indonesian professionals and blue-collar workers in finding trusted overseas jobs in the Middle East, Asia, and Europe.  
It connects directly to the `abroadwork-core` backend, enabling resume uploads, job browsing, and employer interaction.

The portal is available in **Bahasa Indonesia + English**, and provides employer dashboards, AI matching, and interview scheduling.

---

## 🇮🇩 Key Features

- 🔍 Job listings filtered by Indonesia-eligible categories
- 📝 Resume builder with Bahasa support + Gulf templates
- 📩 Twilio WhatsApp alerts for new job matches
- 🎥 Record + upload video resumes for global recruiters
- 📅 Interview scheduling with Zoom integration
- 🧠 Smart filters (age, passport status, skills, religion)
- 🧳 Work visa process information & language-based resources
- 🧑‍💼 Recruiter dashboard for shortlist + notifications

---

## ⚙️ Tech Stack

- **Frontend:** Angular or React (i18n: English + Bahasa)
- **Backend:** abroadwork-core (.NET API)
- **Database:** MongoDB via core backend
- **Media CDN:** Cloudinary or AWS S3
- **APIs:** Twilio, Zoom, AI Matching (optional)

---

## 📁 Folder Structure

abroadwork-indonesia/
├── frontend/ # Angular or React frontend (Bahasa support)
├── public/ # Images, icons, translations
├── docs/ # Interview process, resume guides
├── config/ # API endpoints for abroadwork-core
└── README.md

---

## 🔧 Setup Instructions

### 🔗 Prerequisites

- Node.js / Angular CLI
- Git / VS Code
- Connected to `abroadwork-core` backend

---

### ▶️ Run Locally

```bash
# Clone the repo
git clone https://github.com/mahadgroup/abroadwork-indonesia.git

# Navigate & install
cd abroadwork-indonesia/frontend
npm install

# Start dev server
ng serve
API_BASE_URL = "https://api.abroadwork.com"
🌟 Live Features Coming Soon
🌐 Pre-departure guide for Indonesian candidates

📄 Resume export to PDF (POEA-style layout)

🔐 Verified employer badge for safe recruitment

📊 Job analytics dashboard for applicants

🧑‍💼 Maintained By
AbroadWork Indonesia Team
📍 Jakarta, Indonesia
🌐 www.abroadwork.id
📧 info@abroadwork.id
