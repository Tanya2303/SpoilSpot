# 🥦 SpoilSpot

> **Know it. Map it. Stop it.**  
A food spoilage intelligence platform that helps users track food expiration, report waste hotspots, learn food safety tips, and explore eco-friendly ways to reuse or discard spoiled food.

---

## 🌍 Live Demo

🔗 [Click here to try the live demo](https://your-live-demo-url.com)  
⚠️ *Use demo login to explore features without signing up.*

---

## 🎯 Problem Statement

1/3 of all food produced globally goes to waste — causing hunger, economic loss, and environmental damage. SpoilSpot aims to combat food spoilage at the **individual and community level** through awareness, tracking, and action.

---

## 💡 What It Does

SpoilSpot provides a centralized platform to:

- Track your food inventory and receive expiry alerts
- Report and visualize local food waste on a heatmap
- Get AI-based recipe and reuse suggestions
- Learn safe storage and spoilage signs
- Track personal impact through data analytics

---

## 🖥️ Features

### 🔐 Authentication
- Secure signup/login via Firebase Auth
- Google OAuth (optional)

### 📦 Food Expiry Tracker
- Add items manually or via receipt image (OCR)
- Color-coded freshness indicators: 🟢 Fresh | 🟡 Expiring | 🔴 Spoiled
- Notification reminders (via Firebase Functions)

### 🗺️ Spoilage Heatmap
- Report food waste in your area
- View crowd-sourced map of food waste hotspots
- Filter by type, severity, and cause

### ♻️ Recipes & Reuse
- Suggests recipes based on ingredients about to expire (AI-powered)
- Static tips for repurposing spoiled food (compost, masks, cleaners)

### 📚 Food Safety Education
- Searchable database: shelf life, spoilage signs, storage tips
- Gemini/GPT-based Q&A chatbot

### 📊 Personal Analytics
- Weekly/monthly reports of food saved or wasted
- Charts showing top wasted items, money and CO₂ saved

---

## 🧑‍💻 Tech Stack

| Layer      | Tech                                      |
|------------|-------------------------------------------|
| Frontend   | React.js, Tailwind CSS                    |
| Routing    | React Router                              |
| Backend    | Firebase (Auth, Firestore, Cloud Functions) |
| AI & OCR   | Gemini Pro API, Google Vision OCR         |
| Mapping    | Mapbox GL JS / Leaflet.js                 |
| Charts     | Chart.js / Recharts                       |
| Hosting    | Firebase Hosting / Vercel / Netlify       |

---

