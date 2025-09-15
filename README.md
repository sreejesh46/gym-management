# 🏋️‍♂️ Gym Management System

A modern web-based **Gym Management System** built with **HTML, CSS, JavaScript, and Firebase**.  
This project enables **gym admins** to manage members, fee packages, bills, diet plans, and supplements while allowing **members** to securely log in and track their fitness-related services.

---

## ✨ Features

### 🔐 Admin Panel
- Secure admin login
- Add, update, and delete members
- Assign and manage **fee packages**
- Generate and manage **member bills**
  - Mark bills as **Paid / Unpaid**
  - Automatically update **Months Paid** (e.g., "October 2025")
- View billing history of each member
- Send notifications to individual members or broadcast to all
- Manage **supplement store** and **diet plans**
- Export reports for tracking

### 🙋 Member Panel
- Secure member login
- View **personal profile details**
- Track and download **bill receipts**
- See bill status with **Months Paid**
- Access assigned **diet plans** (if package allows)
- Explore available **supplements**
- Notification bell for **real-time updates**

---

## 🛠️ Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend & Database:** Firebase Firestore & Firebase Auth
- **Hosting (Optional):** Firebase Hosting / GitHub Pages

---

## 📂 Project Structure
/gym-management
│── /css
│ └── styles.css
│── /img
│ └── (images for coaches, dashboard, etc.)
│── /js
│ └── scripts.js
│── admin-dashboard.html
│── create-bills.html
│── view-members.html
│── fee-packages.html
│── diet-details.html
│── supplement-store.html
│── report-export.html
│── member-dashboard.html
│── view-bills.html
│── diet-plan.html
│── supplements.html
│── index.html
│── README.md


---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/gym-management-system.git
   cd gym-management-system
Set up Firebase:

Create a Firebase project

Enable Firestore and Authentication

Add your Firebase config in the scripts

Run the project:

Open index.html in your browser

Or deploy using Firebase Hosting or GitHub Pages

## 🔮 Upcoming Improvements

Member profile editing

Online payment integration

Attendance tracking

Role-based access control (multiple admins/trainers)

## 📜 License


© 2025 Sreejesh Mohan. All Rights Reserved.