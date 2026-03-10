<div align="center">

<img src="https://img.shields.io/badge/Status-Active-00c16a?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/License-MIT-b8f04a?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Version-1.0.0-00c16a?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Agile-Development-0a9?style=for-the-badge"/>

<br/><br/>

```
  ███████╗      ██╗    ██╗ █████╗ ███████╗████████╗███████╗
  ██╔════╝      ██║    ██║██╔══██╗██╔════╝╚══██╔══╝██╔════╝
  █████╗  █████╗██║ █╗ ██║███████║███████╗   ██║   █████╗  
  ██╔══╝  ╚════╝██║███╗██║██╔══██║╚════██║   ██║   ██╔══╝  
  ███████╗      ╚███╔███╔╝██║  ██║███████║   ██║   ███████╗
  ╚══════╝       ╚══╝╚══╝ ╚═╝  ╚═╝╚══════╝   ╚═╝   ╚══════╝
```

# ♻️ E-Waste Management System

### *A Smart Digital Platform for Responsible Electronic Waste Disposal*

<br/>

> **"Every device recycled is a step toward a cleaner, greener planet."**

<br/>

[![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

---

## 📋 Table of Contents

- [🌍 About the Project](#-about-the-project)
- [🚨 The Problem](#-the-problem)
- [💡 Our Solution](#-our-solution)
- [✨ Features](#-features)
- [🏗️ System Architecture](#️-system-architecture)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 Getting Started](#-getting-started)
- [📊 How It Works](#-how-it-works)
- [📈 Benefits & Future Scope](#-benefits--future-scope)
- [🏢 Industry Context](#-industry-context)
- [👥 Team](#-team)
- [📚 References](#-references)

---

## 🌍 About the Project

<table>
<tr>
<td>

**E-Waste Management System** is a full-stack web and mobile platform developed at **Bansal College of Engineering, Mandideep**, designed to revolutionize how electronic waste is collected, tracked, and recycled.

Electronic waste (e-waste) is one of the **fastest-growing waste streams** in the world — yet less than **20% is formally recycled**. Our system bridges the gap between everyday users and certified recyclers through a seamless digital experience.

</td>
<td>

```
📊 Global E-Waste Stats (2023)
┌─────────────────────────────┐
│  Generated : 53.6M tonnes   │
│  Recycled  : ~20% formally  │
│  Value Lost: $57B annually  │
│  Growth    : +2.5M t/year   │
└─────────────────────────────┘
```

</td>
</tr>
</table>

---

## 🚨 The Problem

E-waste causes severe harm when improperly handled:

| Problem | Impact |
|--------|--------|
| ☠️ **Toxic Chemicals** | Lead, mercury & cadmium pollute soil and groundwater |
| 🏥 **Health Hazards** | Neurological damage, cancer risk from informal recycling |
| 🔐 **Data Breaches** | Unwiped devices expose personal & corporate data |
| 🗑️ **Landfill Overflow** | Valuable materials buried, wasting finite resources |
| 📉 **Resource Loss** | Gold, silver, copper lost worth billions every year |

---

## 💡 Our Solution

```
 USER ──► WEB/APP ──► DATABASE ──► ADMIN/RECYCLER ──► ♻️ RECYCLING PLANT
   │          │            │              │
  📝        🔐            📊            📦
Register  Secure      Analytics     Certified
& Book    Login       Dashboard     Processing
```

A comprehensive digital ecosystem that connects:
- 👤 **Users** — Schedule pickups, track their waste, earn rewards
- 🚚 **Collectors** — Receive assignments, optimize routes
- 🏭 **Recyclers** — Manage intake, report processing outcomes
- 🏛️ **Authorities** — Monitor compliance, view city-wide analytics

---

## ✨ Features

### 🔐 Authentication & Security
- Role-based access control (User / Collector / Recycler / Admin)
- Encrypted login with JWT authentication
- Secure data wipe confirmation for disposed devices

### 📅 Pickup Scheduling
- Easy booking interface for home/office pickups
- Real-time slot availability and confirmation
- Support for bulk corporate pickups

### 📡 Real-Time Tracking
- Live status updates from pickup to processing
- Push notifications and SMS alerts
- GPS tracking for collection vehicles

### 📊 Analytics Dashboard
- Visual charts for collection volumes by category
- Environmental impact metrics (CO₂ saved, materials recovered)
- City-wide and user-level reporting for authorities

### 🛒 Refurbishment Marketplace
- Buy/sell verified refurbished electronics at lower cost
- Extend device lifecycle, reduce demand for new production

### 🎁 Reward System *(Future Scope)*
- Earn points per kg of e-waste disposed
- Redeem for discounts, coupons, and sustainability badges

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                     PRESENTATION LAYER                      │
│              React.js  |  HTML  |  CSS  |  JS               │
└───────────────────────────┬─────────────────────────────────┘
                            │ REST APIs
┌───────────────────────────▼─────────────────────────────────┐
│                     APPLICATION LAYER                       │
│            Node.js  |  Python (Django)  |  APIs             │
└───────────────────────────┬─────────────────────────────────┘
                            │ ORM / SQL
┌───────────────────────────▼─────────────────────────────────┐
│                       DATA LAYER                            │
│                    MySQL Database                           │
│        Users | Pickups | Items | Reports | Transactions     │
└─────────────────────────────────────────────────────────────┘
```

### Key Modules

```
src/
├── 📁 frontend/
│   ├── components/         # Reusable UI components
│   ├── pages/              # Route-level pages
│   ├── dashboard/          # Admin & user dashboards
│   └── marketplace/        # Refurbished device store
│
├── 📁 backend/
│   ├── api/                # REST API endpoints
│   ├── auth/               # Authentication & JWT
│   ├── tracking/           # Real-time tracking logic
│   └── analytics/          # Reports & data processing
│
└── 📁 database/
    ├── models/             # MySQL table schemas
    ├── migrations/         # DB version control
    └── seeds/              # Sample data
```

---

## 🛠️ Tech Stack

<table>
<tr>
  <th>Layer</th>
  <th>Technology</th>
  <th>Purpose</th>
</tr>
<tr>
  <td>🎨 <strong>Frontend</strong></td>
  <td>React.js, HTML5, CSS3, JavaScript</td>
  <td>User Interface & Web App</td>
</tr>
<tr>
  <td>⚙️ <strong>Backend</strong></td>
  <td>Node.js, Python, Django</td>
  <td>Server Logic & REST APIs</td>
</tr>
<tr>
  <td>🗄️ <strong>Database</strong></td>
  <td>MySQL</td>
  <td>Data Persistence & Queries</td>
</tr>
<tr>
  <td>🔌 <strong>APIs</strong></td>
  <td>REST APIs, Frameworks</td>
  <td>Client-Server Communication</td>
</tr>
<tr>
  <td>💻 <strong>IDE</strong></td>
  <td>VS Code</td>
  <td>Development Environment</td>
</tr>
<tr>
  <td>🔄 <strong>Methodology</strong></td>
  <td>Agile Software Development</td>
  <td>Iterative, Sprint-based Delivery</td>
</tr>
</table>

---

## 🚀 Getting Started

### Prerequisites

```bash
node >= 18.x
python >= 3.10
mysql >= 8.0
npm >= 9.x
```

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/shubhamnarware67-cmd/ewaste-management-system.git
cd ewaste-management-system

# 2. Install frontend dependencies
cd frontend
npm install

# 3. Install backend dependencies
cd ../backend
pip install -r requirements.txt

# 4. Configure environment variables
cp .env.example .env
# Edit .env with your DB credentials and API keys

# 5. Setup the database
mysql -u root -p < database/schema.sql

# 6. Run the backend server
python manage.py runserver

# 7. Run the frontend (new terminal)
cd frontend
npm start
```

### Environment Variables

```env
# Database
DB_HOST=localhost
DB_PORT=3306
DB_NAME=ewaste_db
DB_USER=your_user
DB_PASSWORD=your_password

# Auth
JWT_SECRET=your_jwt_secret_key
JWT_EXPIRY=7d

# App
PORT=8000
FRONTEND_URL=http://localhost:3000
```

---

## 📊 How It Works

```
STEP 1 ──► STEP 2 ──► STEP 3 ──► STEP 4 ──► STEP 5
   │           │           │           │          │
Register   Schedule    Real-Time    Certified  Report &
& Login     Pickup     Tracking    Recycling  Analytics
   │           │           │           │          │
User fills  Choose      Get SMS/    Plant     Impact
device info  date &     push noti   confirms  dashboard
            location   on status   receipt   updated
```

---

## 📈 Benefits & Future Scope

### ✅ Current Benefits

- 🌿 Reduces environmental hazards and toxic pollution
- 🔄 Promotes a circular economy through recycling and reuse
- 📋 Supports CPCB & government compliance requirements
- 📱 Digital-first, accessible experience for all users
- 🔒 Ensures data security for discarded devices

### 🔮 Future Scope

| Feature | Description |
|---------|-------------|
| 🤖 **AI Waste Sorting** | ML models to automatically categorize and sort e-waste at plants |
| 📡 **IoT Smart Bins** | Connected bins that detect fill levels and auto-schedule pickups |
| 🛒 **Refurb Marketplace** | Full marketplace to buy/sell certified refurbished electronics |
| 🎁 **Rewards App** | Gamified reward system with points, badges, and redeemable offers |
| 🌐 **Multi-language** | Hindi and regional language support for wider adoption |
| 📲 **Mobile App** | Native iOS & Android application with offline support |

---

## 🏢 Industry Context

> Leading companies demonstrating that e-waste management is a massive opportunity:

<table>
<tr>
  <th>Company</th>
  <th>Founded</th>
  <th>Headquarters</th>
  <th>Highlight</th>
</tr>
<tr>
  <td>🏆 <strong>Attero Recycling</strong></td>
  <td>2008</td>
  <td>Noida, India</td>
  <td>Target: ₹2,000 Cr annual revenue</td>
</tr>
<tr>
  <td>🌱 <strong>E-Parisaraa</strong></td>
  <td>2005</td>
  <td>Bengaluru, India</td>
  <td>India's 1st govt-authorized recycler</td>
</tr>
<tr>
  <td>🔄 <strong>Karo Sambhav</strong></td>
  <td>2017</td>
  <td>India</td>
  <td>₹40+ Cr, EPR compliance leader</td>
</tr>
</table>

---

## 👥 Team

<div align="center">

| Role | Name | Enrollment |
|------|------|------------|
| 👨‍💻 **Developer** | Shubham Narware | `0127CS231159` |
| 👩‍💻 **Developer** | Vaishnavi Vishwakarma | `0127CS231187` |
| 🧑‍🏫 **Guide** | Prof. M. Farooqui | — |

**Institution:** Bansal College of Engineering, Mandideep

</div>

---

## 📚 References

- 📄 [WHO Report on E-Waste (2021)](https://www.who.int/news-room/fact-sheets/detail/electronic-waste-(e-waste))
- 🏛️ [Central Pollution Control Board (CPCB), Govt. of India](https://cpcb.nic.in/)
- 🌐 [UNEP — United Nations Environment Programme Reports](https://www.unep.org/explore-topics/resource-efficiency/what-we-do/responsible-industry/e-waste)

---

<div align="center">

---

**⭐ If this project helped you, give it a star on GitHub!**

Made with 💚 for a Sustainable Future · Bansal College of Engineering, Mandideep

</div>
