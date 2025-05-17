# 🏥 Hospital Management System

![GitHub repo size](https://img.shields.io/github/repo-size/KPhanindraReddy/hackerthon6021_project)
![GitHub last commit](https://img.shields.io/github/last-commit/KPhanindraReddy/hackerthon6021_project)
![License](https://img.shields.io/github/license/KPhanindraReddy/hackerthon6021_project)

> A full-stack **Hospital Management System** built with HTML, CSS, JavaScript, Node.js, and SQLite. This system streamlines hospital operations such as patient management, doctor assignments, bed availability, medicine dispensation, inventory management, and more — all via a responsive and interactive web interface.

## 🎯 Features

✨ **Frontend (HTML/CSS/JS)**
- Login & Role-Based Navigation (Receptionist, Doctor, Pharmacist)
- Patient Admission & Tracking
- Bed Availability Dashboard
- Medicine Dispensation Records
- Inventory Management Module
- Doctor Scheduling
- Department Directory
- Interactive UI with visual cues and responsive design

🛠 **Backend (Node.js + Express)**
- REST APIs for CRUD operations
- SQLite database integration
- Real-time updates via fetch/XHR
- Organized folder structure (MVC-like)

📁 **Database**
- Two SQLite DBs:
  - `hospital.db` (Main)
  - `database.db` (Legacy/Testing)

## 📂 Project Structure

```

hackerthon6021\_project/
│
├── backend/
└── server.js
├── database.db                 # SQLite DB (secondary)
├── hospital.db                 # Primary DB
├── package.json                # Node dependencies
├── package-lock.json
└── .vscode/                    # VSCode config             # Express server with routes

├── frontend/
    ├── \*.html                  # All HTML pages
    ├── \*.js                    # JS files per module
    ├── images/                 # GIFs/screenshots
    └── styles.css              # Custom styles

````

---

## 🛠️ How to Run Locally

### ✅ Prerequisites
- Node.js & npm
- Git

### 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/KPhanindraReddy/hackerthon6021_project.git

# Navigate to backend folder
cd hackerthon6021_project/backend

# Install backend dependencies
npm install
# Run the server
node server.js
````

💡 *Open `frontend/index.html` in a browser to start using the application.*

---

## 🧑‍💻 Contributors

* [KPhanindraReddy](https://github.com/KPhanindraReddy)

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## 📣 Feedback

If you find a bug or want to contribute:

* Open an issue
* Submit a PR
* Or just ⭐ the repo!

---

> Made with 💻 by **KPhanindraReddy** as part of Hackathon 6021 Project

