# 🔐 VulnBlog — A Secure Blogging Platform (Flask)

**VulnBlog** is a simple, security-aware blogging web application built using Python's Flask framework. It demonstrates key concepts of secure web development, including user authentication, session handling, input sanitization (to prevent XSS), and basic database operations using SQLAlchemy.

---

## 🚀 Features

- ✅ User Registration & Login (Session-based Authentication)
- 📝 Create, View, and Search Blog Posts
- 🔐 XSS Protection using `bleach` sanitization
- 🧾 Form validation with Flask-WTF and CSRF protection
- 📃 Search functionality by blog title
- ⚠️ Custom 404 Error Handling

---

## 🔧 Tech Stack

- **Python 3**
- **Flask** (Web Framework)
- **Flask-WTF** (Forms & CSRF)
- **SQLite** (Database)
- **SQLAlchemy** (ORM)
- **Bleach** (HTML Sanitization)
- **Jinja2** (Templating)

---

## 🛡 Security Highlights

- Content input is sanitized using the `bleach` library to prevent stored XSS attacks.
- CSRF protection enabled using Flask-WTF's built-in CSRF token.
- Session-based user authentication using Flask's `session`.
- Easily extendable for password hashing using `werkzeug.security`.

---

## 🧪 How to Run Locally

### 🔁 Clone the Repo
```bash
git clone https://github.com/PrasadKakpure/vulnblog.git
cd vulnblog
