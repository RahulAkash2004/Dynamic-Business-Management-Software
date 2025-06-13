![MIT License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-blue)
![Tech Stack](https://img.shields.io/badge/Tech-Electron.js%20%7C%20Node.js%20%7C%20Python-orange)


# 🧾 Dynamic Business Management Software

A complete, on-premise business management solution designed for manufacturing and service businesses. The solution offers real-time inventory tracking, GST supported billing payrollm and ledger management, artificial intelligence(Artificial Intelligence) powered analytics and strong offline data sync with auto backup and recovery.

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


---

## ⚙️ Setup & Installation

### 💻 Prerequisites

- Node.js v16+
- Python 3.10+
- Git


### 📦 Install Dependencies

To install all required Node.js packages, run:

```
npm install


### ▶️ Run Application

To start the Electron-based desktop application:

```
npm start


### 🧠 AI Modules (Optional)

If you'd like to run the Python-based AI analytics (e.g., for sales trends or stock predictions), navigate to the AI module directory and run:

```
cd ai-modules
python run_analysis.py

---

## 🧠 AI Modules

- Uses cleaned business data (billing, stock, customer purchases)
- Predicts low stock trends and monthly revenue estimates
- Generates visual analytics using Matplotlib and Python libraries
- Helps businesses make data-driven decisions through visual dashboards

---

## 🚧 Future Enhancements

- ☁️ Cloud sync and multi-device access
- 🧑‍💼 Advanced payroll with tax & leave tracking
- 🎛️ Graphical drag-and-drop dashboard interface
- 📦 QR/barcode generation for inventory entries
- 📲 Mobile companion app for quick access

---

## 📅 Project Timeline

- **Start Date:** March 2024  
- **Status:** 🛠 Ongoing Development  
- **Last Updated:** June 2025

---

## 👤 Contributions

👨‍💻 Developed and maintained by **Rahul Akash**  
📧 Contact: [rahulsaravanan71@gmail.com](mailto:rahulsaravanan71@gmail.com)  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/rahul-akash-494103212)

---

## 📄 License

This project is open-source and available under the **MIT License**.  
See the [LICENSE](LICENSE) file for full details.

---
