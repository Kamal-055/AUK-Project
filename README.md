<div align="center">

# 🛡️ AUK SafeHaven

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=28&pause=1000&color=FF4D4D&center=true&vCenter=true&width=800&lines=Community-Driven+Safety+Reporting+Platform;Report+Unsafe+Locations+with+Ease;Interactive+Safety+Mapping+System;Building+Safer+Communities+Together" />

<br>

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-Backend-green?style=for-the-badge)
![Express.js](https://img.shields.io/badge/Express.js-Framework-black?style=for-the-badge)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue?style=for-the-badge)
![Leaflet.js](https://img.shields.io/badge/Leaflet.js-Mapping-brightgreen?style=for-the-badge)

### Empowering Communities Through Collaborative Safety Reporting

</div>

---

# 📖 Overview

AUK SafeHaven is a community-driven web application designed to improve public safety by enabling users to report, monitor, and visualize unsafe locations through an interactive map interface.

The platform provides a centralized system where community members can submit safety concerns, helping create awareness and support informed decision-making. Through administrative verification and location-based visualization, SafeHaven ensures reliable and accessible safety information for everyone.

---

# 🎯 Problem Statement

Many unsafe locations remain unidentified due to the lack of a centralized reporting platform. Individuals often rely on personal experiences or word-of-mouth information, which may not always be accessible or accurate.

AUK SafeHaven addresses this challenge by providing:

- Real-time location reporting
- Community-driven safety awareness
- Interactive mapping of unsafe areas
- Administrative verification of reports
- Transparent report management

---

# ✨ Key Features

## 👤 User Management

- User Registration & Login
- Secure Authentication
- Session Management
- User Report Tracking

## 📍 Unsafe Location Reporting

- Submit unsafe locations
- Capture Latitude & Longitude
- Add detailed descriptions
- Upload supporting evidence

## 🗺️ Interactive Safety Map

- Dynamic marker visualization
- Location-based navigation
- Real-time map updates
- Community safety awareness

## 🛡️ Administrative Dashboard

- Review reports
- Approve submissions
- Reject invalid reports
- Manage report status

## 📊 Analytics Dashboard

- Total Registered Users
- Total Reports Submitted
- Approved Reports
- Pending Reports
- Rejected Reports

## 🔄 Report Tracking

- Monitor report status
- View approval progress
- Improve transparency

---

# 🏗️ System Architecture

```text
+----------------------+
|      User Portal     |
+----------+-----------+
           |
           v
+----------------------+
|  Frontend Interface  |
|  HTML | CSS | JS     |
+----------+-----------+
           |
           v
+----------------------+
| Node.js + Express.js |
|      Backend API     |
+----------+-----------+
           |
           v
+----------------------+
|      MySQL DB        |
+----------+-----------+
           |
           v
+----------------------+
|   Admin Dashboard    |
+----------------------+
```

---

# 🛠️ Technology Stack

| Category | Technologies |
|-----------|-------------|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | Node.js, Express.js |
| Database | MySQL |
| Mapping | Leaflet.js |
| Tools | VS Code, XAMPP, Git, GitHub |
| Hosting | Localhost / Future Cloud Deployment |

---

# 🚀 Application Workflow

```text
User Registration/Login
          ↓
Submit Unsafe Location
          ↓
Location Stored in Database
          ↓
Admin Verification
          ↓
Approval / Rejection
          ↓
Display on Interactive Map
          ↓
Community Awareness
```

---

# 📂 Project Structure

```text
AUK-SafeHaven
│
├── public
│   ├── css
│   ├── js
│   ├── images
│
├── uploads
│
├── routes
│
├── database
│
├── views
│
├── admin
│
├── server.js
├── package.json
├── .env
└── README.md
```

---

# ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/AUK-SafeHaven.git
```

### Navigate to Project

```bash
cd AUK-SafeHaven
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file:

```env
PORT=3000

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=safehaven

JWT_SECRET=your_secret_key
```

### Start Server

```bash
node server.js
```

or

```bash
nodemon server.js
```

### Access Application

```text
http://localhost:3000
```

---

# 🔒 Security Features

- Secure Authentication
- Protected Admin Access
- Input Validation
- Secure Database Operations
- Environment Variable Protection
- Controlled Report Verification

---

# 🌟 Future Enhancements

- Mobile Application Support
- Real-Time Notifications
- Emergency Contact Integration
- AI-Based Report Verification
- Heatmap Safety Analysis
- Route Safety Recommendations
- Community Safety Ratings
- Multi-Language Support
- Smart City Integration

---

# 🌍 Potential Applications

- Public Safety Monitoring
- Women's Safety Initiatives
- Smart City Solutions
- Community Crime Awareness
- Educational Institution Security
- Urban Planning & Analysis

---

# 👨‍💻 Project Team

### AUK Team

- Kamalakannan
- Aiman
- Ushnika

---



# 📄 License

This project was developed for educational and academic purposes.

---

<div align="center">

## ⭐ AUK SafeHaven

### "Building Safer Communities Through Technology"

Made with ❤️ by Team AUK

</div>
