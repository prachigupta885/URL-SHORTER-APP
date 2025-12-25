# 🔗 URL Shortener Web App

A **full-stack URL Shortener application** built using **Node.js (Backend)** and **HTML, CSS, JavaScript (Frontend)**.
This project allows users to convert long URLs into short, easy-to-share links using a simple and clean interface.

---

## 🚀 Features

* Shorten long URLs instantly
* Custom short code support
* Frontend + Backend fully integrated
* Backend built using **pure Node.js (no Express)**
* Simple, clean, and beginner-friendly UI

---

## 🛠️ Tech Stack

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Node.js (HTTP module)

---

## 📂 Project Structure

```
url-shortener/
│
├── public/
│   ├── index.html   # Frontend (HTML + JS)
│   └── style.css    # Styling
│
├── server.js        # Backend server
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

---

## ▶️ How to Run Locally

1. Clone the repository

```bash
git clone https://github.com/USERNAME/url-shortener.git
```

2. Go to project directory

```bash
cd url-shortener
```

3. Install dependencies

```bash
npm install
```

4. Start the server

```bash
node server.js
```

5. Open browser and visit

```
http://localhost:3002
```

---

## 📌 How It Works

1. User enters a long URL and optional short code
2. Frontend sends data to backend using `fetch()`
3. Backend processes the request and generates a short URL
4. Shortened URL is returned to the user

---

## 🎯 Learning Outcomes

* Understanding client–server communication
* Handling HTTP requests without Express
* Working with forms and Fetch API
* Structuring a full-stack project

---

## 👩‍💻 Author

**Prachi Gupta**

---

## ⭐ Future Improvements

* Database integration (MongoDB)
* Redirect functionality
* URL expiry feature
* Authentication system
