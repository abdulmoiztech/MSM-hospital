# 🏥 MSM Hospital Website

A modern, fully responsive hospital web app built with vanilla HTML, CSS & JavaScript.

## 🌐 Live Pages

| Page | Description |
|------|-------------|
| `index.html` | Main hospital website |
| `admin.html` | Admin portal (protected) |

---

## ✨ Features

### Patient Side (`index.html`)
- **Home** — Hero, stats, featured departments & doctors, testimonials
- **About** — Hospital history, mission/vision, why choose MSM
- **Departments** — 6 departments, each with assigned doctors
- **Doctors** — Searchable & filterable doctor cards
- **Appointment Booking** — Modal form, saves to `localStorage`

### Admin Portal (`admin.html`)
- 🔐 Protected login (email + password)
- 📊 Dashboard with live stats (Total / Today / Pending / Confirmed)
- 📋 All bookings table with search & status filter
- ✅ Confirm / Cancel / Delete bookings
- ➕ Manually add new bookings
- 🔄 Auto-syncs with patient bookings via `localStorage`

---

## 🏥 Departments & Doctors

| Department | Doctors |
|------------|---------|
| Cardiology | Dr. Arif Hussain, Dr. Sana Mirza |
| Neurology | Dr. Kamran Sheikh, Dr. Ayesha Raza |
| Orthopedics | Dr. Tariq Mahmood, Dr. Hina Baig |
| Pediatrics | Dr. Usman Ali, Dr. Nadia Khan |
| Dermatology | Dr. Bilal Ahmed, Dr. Rafia Siddiqui |
| Gynecology | Dr. Sobia Qureshi, Dr. Maryam Farooq |

---

## 🛠 Tech Stack

- HTML5, CSS3, Vanilla JavaScript
- Font Awesome (icons)
- Google Fonts — DM Serif Display + DM Sans
- localStorage (data persistence)

---

## 🚀 Getting Started

```bash
git clone https://github.com/abdulmoiztech/MSM-hospital
cd msm-hospital
# Open index.html in browser
```

No build tools. No dependencies. Just open and run.

---

## 📁 Project Structure

```
msm-hospital/
├── index.html      # Main hospital website
├── admin.html      # Admin portal
└── README.md
```

---

## 📄 License

MIT — free to use and modify.
