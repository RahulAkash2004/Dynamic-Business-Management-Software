# 🧾 Dynamic Business Management Software

A complete, on-premise business management solution designed for manufacturing and service businesses. The solution offers real-time inventory tracking, GST supported billing payrollm and ledger management, artificial intelligence(Artificial Intelligence) powered analytics and strong offline data sync with auto backup and recovery.

---

## 📌 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Architecture](#-architecture)
- [Setup & Installation](#-setup--installation)
- [Screenshots](#-screenshots)
- [AI Modules](#-ai-modules)
- [Future Enhancements](#-future-enhancements)
- [Project Timeline](#-project-timeline)
- [Contributions](#-contributions)
- [License](#-license)

---

## 🔧 Features

### 🧾 Billing & Invoicing
- GST-compliant invoice generator with tax breakdown
- Support for products, services, and customer-specific pricing

### 📦 Inventory Management
- Real-time stock monitoring with auto-decrement on billing
- Low-stock alerts and inventory reports

### 🧑‍💼 Payroll & Attendance
- Basic payroll calculator
- Manual and automatic employee attendance logging

### 📚 Ledger & Accounts
- Transaction tracking, cash flow management
- Exportable ledger reports

### 📊 AI-Driven Analytics
- Data insights using Python-based ML modules
- Trend prediction and performance charts

### 🔄 Offline Sync & Backup
- Local-first SQLite database
- Automated daily backups with restore capability

---

## 🧰 Tech Stack

| Layer         | Technologies Used                                           |
|---------------|-------------------------------------------------------------|
| Frontend      | Electron.js, HTML, CSS, JavaScript                          |
| Backend       | Node.js, Express.js                                         |
| Database      | SQLite (with data sync & restore support)                   |
| AI & Analytics| Python, Pandas, Scikit-learn, Matplotlib                    |
| Dev Tools     | Git, GitHub, Visual Studio Code, Postman                    |

---

## 🏗 Architecture

```text
[Electron UI]
    ↓
[Node.js + Express Backend]
    ↓
[SQLite DB]
    ↓
[Python ML Modules] → Analytics & Reports
