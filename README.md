<div align="center">

# 🏫 Hazariganj Secondary School
## Admin Panel

**A complete, secure, and fully responsive school management dashboard**

[![Firebase](https://img.shields.io/badge/Firebase-Realtime_DB-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)

</div>

---

## 📖 About The Project

The **Hazariganj Secondary School Admin Panel** is a web-based administration dashboard built to digitize and streamline the school's day-to-day operations. It serves as the backend management interface for the [Hazariganj Secondary School](https://hazariganj.edu.bd) website.

Powered by Firebase's Realtime Database, administrators can manage students, teachers, notices, applications, and much more — all from a single, unified interface.

---

## ✨ Features

### 🔐 Secure Authentication
Firebase Email & Password authentication ensures only authorized personnel can access the dashboard.

### 📊 Real-Time Dashboard
Get a live overview of key statistics — total students, teachers, pending applications, and active notices — updated in real time.

### 📝 Application & Complaint Management
View, approve, reject, or resolve student applications and complaints with ease.

### 👥 User Management
Full **CRUD** (Create, Read, Update, Delete) operations for managing Teachers, Employees, and Student records.

### 📢 Notice & Holiday Board
Publish school notices and manage the holiday calendar directly from the panel.

### 🖼️ Gallery Management
Create albums and dynamically add or remove photos from school events.

### ⚙️ Dynamic Settings
Update homepage sections, school information (EIIN, Code), top bar text, and image sliders — all without touching any code.

### 🛡️ Security & Backup
- Change the admin password at any time
- **Export** the entire database as a JSON backup file
- **Import** a previous backup to restore data instantly

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5 / CSS3** | Core structure and base styling |
| **JavaScript (ES6+)** | Full frontend logic and interactivity |
| **Tailwind CSS** | Rapid, responsive UI development (via CDN) |
| **Firebase Realtime Database** | Real-time backend and data storage |
| **Firebase Authentication** | Secure user login and access control |
| **Google Fonts** | Hind Siliguri & Noto Serif Bengali typography |

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge)
- A [Firebase](https://console.firebase.google.com/) account
- (Optional) VS Code with the Live Server extension

### Step 1 — Clone the Repository

```bash
git clone https://github.com/your-username/hazariganj-admin-panel.git
cd hazariganj-admin-panel
```

### Step 2 — Set Up Firebase

1. Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project.
2. Under **Authentication**, enable the **Email/Password** sign-in method.
3. Create a **Realtime Database** and configure your security rules.
4. Copy your Firebase configuration from the project settings.

### Step 3 — Add Your Firebase Config

Open `admin.html` and replace the placeholder `firebaseConfig` object with your own credentials:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  databaseURL: "YOUR_DATABASE_URL",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

### Step 4 — Run the App

Open `admin.html` directly in your browser, or use the **Live Server** extension in VS Code for a better development experience.

---

## 🔑 Demo Login Credentials

> ⚠️ **Warning:** These credentials are for demo purposes only. Change your password immediately before using this in production.

| Field | Value |
|---|---|
| **Email** | `admin@hazariganj.edu.bd` |
| **Password** | `admin12345` |

---

## 📁 Project Structure

```
hazariganj-admin-panel/
│
├── admin.html          # Main admin panel (all logic lives here)
├── README.md           # Project documentation
└── assets/             # (Optional) Images and local resources
```

---

## 🤝 Contributing

Contributions are always welcome!

1. **Fork** the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. **Commit** your changes (`git commit -m 'Add some feature'`)
4. **Push** to the branch (`git push origin feature/your-feature-name`)
5. Open a **Pull Request**

---

## 👨‍💻 Developer

<div align="center">

**Sahin Enam**

*Self-Taught Web Developer & UI/UX Enthusiast*
*SSC Batch 2026, Hazariganj Secondary School*

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username)

</div>

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — you are free to use, modify, and distribute it.

---

<div align="center">

If you find this project helpful, please consider giving it a ⭐ on GitHub!

*Made with ❤️ for Hazariganj Secondary School*

</div>
