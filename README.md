# 🩺 CarePath AI — Clinical Intelligence Platform

A full-stack healthcare management platform built as a single deployable HTML file. No server required.

![CarePath AI](https://img.shields.io/badge/CarePath-AI%20Platform-blue?style=for-the-badge&logo=heart)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

---

## 🌐 Live Demo

Deployed via GitHub Pages: **[https://varadsapkal.github.io/carepath-ai](https://carepathai.netlify.app/)**

---

## ✨ Features

| Module | Description |
|---|---|
| 🏠 **Dashboard** | Real-time stats, alert feed, risk distribution charts |
| 👥 **Patients** | Full patient registry with risk levels, vitals, adherence |
| 🔔 **Alerts** | Auto-generated clinical alerts with acknowledge workflow |
| 📅 **Appointments** | Book, manage and track patient appointments |
| 🩺 **AI Booking Assistant** | Conversational AI to book appointments by symptoms |
| 🤖 **AI Clinical Assistant** | Claude-powered clinical decision support per patient |
| 🗺️ **Care Pathways** | Cardiac, Metabolic, Ortho, Pulmonary, Stroke pathways |
| 📊 **Vitals Monitor** | Real-time vitals grid with threshold alerts |
| 💊 **Medications** | Full medication registry with adherence tracking |
| 📈 **Analytics** | Charts for adherence, pathway enrollment, risk trends |
| 👤 **Users & Roles** | Admin, Physician, Nurse, Coordinator roles |

---

## 🚀 Getting Started

### Option 1 — GitHub Pages (Recommended)
1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your site will be live at `https://carepathai.netlify.app/`

### Option 2 — Run Locally
Just open `index.html` in any modern browser. No build step, no dependencies, no server needed.

### Option 3 — Netlify Drop
Drag & drop `index.html` at [netlify.com/drop](https://app.netlify.com/drop) for an instant public URL.

---

## 🔑 Login Credentials

| Role | Email |
|---|---|
| Admin | admin@carepath.ai | 
| Physician | physician@carepath.ai | 
| Nurse | nurse@carepath.ai | 
| Coordinator | coordinator@carepath.ai | 
---

## 🤖 AI Setup (Required for AI features)

The AI Assistant and AI Booking Assistant require an **Anthropic API key**.

1. Get your key at [console.anthropic.com](https://console.anthropic.com)
2. Log in to CarePath AI
3. Go to **Settings → AI Configuration**
4. Paste your `sk-ant-...` key and click **Save**

> New Anthropic accounts receive **$5 free credits** — sufficient for hundreds of consultations.

---

## 🏗️ Tech Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES2020+)
- **Charts:** Chart.js 4.4.1
- **AI:** Anthropic Claude Sonnet 4 (claude-sonnet-4-20250514)
- **Storage:** In-memory DB simulation (no backend required)
- **Fonts:** DM Sans, DM Mono, Fraunces (Google Fonts)

---

## 👥 Team

| Name | Role |
|---|---|
| **Varad Sapkal** | Admin & Project Lead |
| **Dr. Bhure** | Physician |
| **Sonal Sharma** | Nurse |
| **Kunal Gupta** | Care Coordinator |

---

## 📁 Project Structure

```
carepath-ai/
├── index.html          # Complete app (frontend + backend simulation)
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── LICENSE             # MIT License
```

---

## 📄 License

MIT License — free to use, modify and distribute.

---

> ⚠️ **Disclaimer:** CarePath AI is a demonstration platform. It is not a certified medical device. All clinical decisions must be made by qualified healthcare professionals.
