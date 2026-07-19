<div align="center">

# UniBoard Admin Panel
### Web-based Administration Dashboard for UniBoard Platform

[![React](https://img.shields.io/badge/React.js-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)

*React.js admin dashboard for managing the UniBoard student boarding finder platform.*

[Live Demo](https://uniboard-fd52f.web.app) • [Mobile App Repo](https://github.com/NavodPriyadarshana/UniBoard)

</div>

---

## 📋 About

The UniBoard Admin Panel is a React.js web application deployed on Firebase Hosting. It allows administrators to manage the entire UniBoard platform — verifying landlord applications, sending OTP emails, managing listings, and monitoring platform statistics.

---

## ✨ Features

- 📊 **Dashboard** — Real-time statistics (users, listings, bookings, applications)
- 📄 **Applications** — Review landlord documents, approve/reject, send OTP via EmailJS
- 👥 **Users** — Manage students and landlords with subscription plan badges
- 🏠 **Listings** — Verify/unverify boarding listings
- 📱 **Responsive** — Mobile-friendly with hamburger sidebar

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| React.js + Vite | Frontend framework and build tool |
| Firebase Firestore | Real-time database |
| Firebase Authentication | Admin login |
| Firebase Hosting | Deployment |
| EmailJS | Automated OTP email delivery |
| Lucide React | Icon library |

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- Firebase CLI
- EmailJS account

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/NavodPriyadarshana/UniBoard-Admin-Panel.git
cd UniBoard-Admin-Panel
```

2. **Install dependencies**
```bash
npm install
```

3. **Create .env file**
```
VITE_EMAILJS_SERVICE_ID=your_service_id
VITE_EMAILJS_TEMPLATE_ID=your_template_id
VITE_EMAILJS_PUBLIC_KEY=your_public_key
```

4. **Run development server**
```bash
npm run dev
```

5. **Build for production**
```bash
npm run build
firebase deploy --only hosting
```

---

## 🔗 Related

- 📱 **UniBoard Mobile App:** https://github.com/NavodPriyadarshana/UniBoard

---

## 👥 Team

Developed by **Nimna Kavishka (22UG3-0754)** as part of the UniBoard project.

**Institution:** SLTC Research University | **Module:** CIT310 Information Technology Project

---

<div align="center">
Made with ❤️ by Team UniBoard | SLTC Research University 2026
</div>