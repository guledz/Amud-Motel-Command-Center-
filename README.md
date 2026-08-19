# Amud-Motel-Command-Center-
 a 30-room hotel management system with reservations, room status, guests, payments, housekeeping, maintenance, and reports. Built with HTML/CSS/JS, mobile-first, double-booking prevention. Prototype uses LocalStorage; production-ready for Supabase/PostgreSQL.
# 🏨 AMUD MOTEL COMMAND CENTER

**30-Room Hotel Management & Operations System**

> *"30 Rooms. One System. Complete Operational Visibility."*

A professional, responsive hotel/motel management system built for **Amud Motel**, a 30-room hospitality business. This application centralizes reservations, room management, guests, check-in/check-out, housekeeping, payments, revenue, expenses, maintenance, inventory, staff operations, complaints, and reporting — all in one practical daily operations tool.

---

## 🚀 Overview

This is **not just a booking website**. It is a complete operational command center designed for the daily workflow of a small motel. The system is built to be fast, intuitive, and mobile-friendly, enabling receptionists, managers, accountants, housekeeping, and maintenance staff to perform their tasks efficiently.

The prototype runs entirely in the browser using **LocalStorage** for data persistence. The architecture is designed to be migrated to a secure backend (Supabase/PostgreSQL) for production use.

---

## ✨ Key Features

### 📊 Dynamic Dashboard
- Real‑time statistics: total rooms, occupied, available, reserved, cleaning, maintenance
- Today’s check‑ins, check‑outs, revenue, and occupancy rate
- Actionable alerts (maintenance, low stock, pending payments, arrivals)

### 🚪 Visual 30‑Room Grid
- Color‑coded status indicators (Available, Occupied, Reserved, Cleaning, Dirty, Maintenance, Out of Service, Inspection)
- Room cards display guest name, rate, and checkout date
- One‑click room detail panel with quick actions (Check‑in, Check‑out, Reserve, Change Status, Report Maintenance)

### 📅 Reservation System
- Complete reservation lifecycle: Pending → Confirmed → Checked‑in → Checked‑out
- Calendar view (Day / Week / Month) with double‑booking prevention
- Fast 10‑step reservation wizard for receptionists
- Walk‑in customer support

### 👤 Guest Management
- Guest database with contact, ID, history, and spending totals
- Guest profile view including current stay, previous stays, payments, complaints

### 🏨 Check‑In / Check‑Out
- Guided workflows with automatic room status updates
- Payment and deposit recording
- Receipt generation (printable / PDF export ready)

### 💳 Payments & Receipts
- Multiple payment methods (Cash, Bank Transfer, Mobile Payment, Card)
- Payment tracking with references
- Configurable currency (default: ETB)
- Professional receipt generation

### 🧹 Housekeeping
- Housekeeping dashboard showing dirty, cleaning, ready rooms
- Task assignment and status tracking
- Room issue reporting

### 🔧 Maintenance
- Maintenance request module with categories, priority, and cost tracking
- Assignment, progress, and resolution workflows
- Maintenance dashboard with open issues and costs

### 📦 Inventory
- Inventory management with categories, quantities, and reorder levels
- Low‑stock / critical‑stock alerts
- Supplier and unit cost tracking

### 💰 Expense & Revenue Management
- Expense logging with categories and suppliers
- Revenue dashboard distinguishing **Revenue** from **Profit**
- Net operating result calculation

### 📝 Complaints & Feedback
- Customer complaint tracking with resolution workflow
- Feedback analytics placeholder

### 📋 Reports & Analytics
- Daily operations report
- Occupancy analytics (ADR, RevPAR, occupancy rate)
- CSV export for all major data entities

### 🔐 Role‑Based Access (UI Simulated)
- Owner / Manager / Receptionist / Cashier / Housekeeping / Maintenance / Viewer
- Prototype uses role switching, production requires backend authentication

### 📱 Mobile‑First Design
- Fully responsive interface optimized for low‑end Android devices
- Touch‑friendly controls and offline‑friendly UI

---

## 🧪 Demo Data

The application includes **safe, fictional demo data** to explore functionality without connecting to a backend. All demo guest names are clearly marked as “Demo Guest 01”, “Demo Guest 02”, etc. You can reset the data at any time from the Settings panel.

**Note:** The prototype stores data in your browser’s LocalStorage. Clearing browser data will delete all modifications.

---

## 🛠️ Technology Stack

| Layer        | Technology                          |
|--------------|-------------------------------------|
| Frontend     | HTML5, CSS3, Vanilla JavaScript     |
| Data Storage (Prototype) | LocalStorage             |
| Production Backend | Supabase / PostgreSQL (planned) |
| Authentication | Supabase Auth (planned)           |
| Icons         | Lucide (optional), Emoji             |
| Charts        | Chart.js (optional)                  |

---

## 📂 File Structure
amud-motel/
├── index.html          # Main application (single file prototype)
├── css/               # (Separate CSS files for production)
│   ├── styles.css
│   ├── dashboard.css
│   ├── rooms.css
│   └── responsive.css
├── js/                # (Modular JavaScript for production)
│   ├── app.js
│   ├── rooms.js
│   ├── reservations.js
│   ├── guests.js
│   ├── payments.js
│   ├── housekeeping.js
│   ├── maintenance.js
│   ├── inventory.js
│   ├── reports.js
│   ├── auth.js
│   └── storage.js
├── data/
│   └── demo-data.js
├── assets/
│   ├── images/
│   ├── icons/
│   └── logo/
└── README.md

> The current prototype is delivered as a single `index.html` file for simplicity. The production version should be modularized as shown above.

---

## 🚀 Getting Started

### Run Locally (Prototype)

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/amud-motel-command-center.git
   Role Key Actions
Owner / Admin Full access, manage rooms, users, prices, view financials, audit logs
Manager Manage reservations, staff tasks, maintenance, complaints, view reports
Receptionist Create reservations, check‑in/out, assign rooms, record payments
Cashier Record payments, issue receipts, track revenue, record expenses
Housekeeping View assigned rooms, update cleaning status, report issues
Maintenance View requests, update repair status, record completed work

---

🧭 Roadmap

☑ Core operations (rooms, reservations, guests, check‑in/out, payments)
☑ Housekeeping & maintenance modules
☑ Inventory, expenses, complaints, staff
☑ Revenue & occupancy analytics
☑ Daily report and CSV export
☐ Phase 4 – Production: Supabase/PostgreSQL integration, authentication, secure storage, backups
☐ Phase 5 – Growth: Online booking engine, payment gateway integration, SMS/WhatsApp notifications, public website

---

🔒 Security & Privacy

· Guest personal information (ID numbers, contact details) is treated as confidential
· Role‑based access controls (to be fully enforced in production)
· Audit logging of sensitive actions
· No public exposure of guest data
· Demo data does not use real personal information

---

📸 Screenshots

(Add your own screenshots of the dashboard, room grid, reservation calendar, etc. here)

---

🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request. For major changes, open an issue first to discuss what you would like to change.

---

📄 License

This project is licensed under the MIT License. See LICENSE for details.

---

🙏 Acknowledgements

· Inspired by the operational needs of small hospitality businesses in Ethiopia and similar markets.
· Built with simplicity and speed in mind.

---

🏨 AMUD MOTEL — 30 Rooms. One System. Complete Operational Visibilit
