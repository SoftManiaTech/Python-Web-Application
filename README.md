# 🛡️ Flask Secure File Upload Portal

A secure, session-based file upload web portal built using **Flask**, **MySQL**, and **static IP hosting** — fully deployable on a local machine or intranet. Designed for internal document collection, resume submission, or academic applications.

---

## 🚀 Features

- 🔐 **User Authentication**
  - Signup/Login with strong password validation
  - Session-based authentication (auto-expire after 10 minutes)
  - Account lockout after 5 failed attempts

- 📂 **Secure File Uploads**
  - Upload resume (PDF only)
  - Upload bonafide certificate (JPG/PNG only)
  - Upload allowed only after both files selected

- 📡 **Hosting Setup**
  - Hosted on a **local Windows system** using **Flask**
  - Made externally accessible via **Static IP**

- 📊 **Logging**
  - Separate frontend & backend log files
  - Each session has a unique `session_id` for traceability
  - Actions like login, logout, signup, and uploads are logged

---

## 📁 Project Structure

Flask_Upload_Site/
│
├── app.py # Main Flask application
├── templates/ # HTML pages (login, signup, dashboard)
├── static/ # CSS files
├── details/ # Stores uploaded files (ignored in Git)
├── logs/ # Backend/frontend logs (ignored in Git)
├── .gitignore # Ignore logs/uploads
├── requirements.txt # Python package requirements
└── README.md # Project documentation



---

## ⚙️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** Python (Flask)
- **Database:** MySQL
- **Hosting:** Flask on Windows + Static IP

---

## 💻 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/flask-secure-upload.git
   cd flask-secure-upload
