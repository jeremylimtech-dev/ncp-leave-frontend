# 📘 NCP Leave Request System

A lightweight, web-based leave request and approval system built using **HTML, CSS, JavaScript, and Google Apps Script**.  
This system allows employees to submit leave requests and administrators to approve or reject them using a centralized Google Sheet as the database.

---

## 🚀 Live Demo

- **Employee Portal:**  
  https://bit.ly/ncpleaverequestform
  https://jeremylimtech-dev.github.io/NCP-Leave-Request/

- **Admin Login:**  
  https://jeremylimtech-dev.github.io/NCP-Leave-Request/admin-login.html

---

## 🧩 Features

### 👤 Employee
- Submit leave requests without logging in
- Auto-filled employee name and leave balance
- Select start and end dates
- Automatic leave duration calculation
- Clean, distraction-free UI

### 🛠 Administrator
- Secure admin login
- View **pending requests only**
- Approve or reject leave requests
- Visual feedback on actions
- Requests disappear once resolved
- Admin name is recorded on approval/rejection

---

## 🏗️ System Architecture

```text
Frontend (GitHub Pages)
        ↓
Google Apps Script (API)
        ↓
Google Sheets (Database)
