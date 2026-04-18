# 🔐 Password Generator Web App

A simple web application built using Flask that generates secure random passwords based on user-defined length.

---

## 🚀 Features

* Generate random passwords instantly
* User-defined password length
* Includes:

  * Uppercase & lowercase letters
  * Digits
  * Special characters
* Clean and minimal UI

---

## 🛠️ Tech Stack

* Backend: Python, Flask
* Frontend: HTML, CSS
* Libraries: random, string

---

## 📂 Project Structure

```
project/
│── app.py
│── templates/
│     └── index.html
│── static/
│     └── style.css
```

---

## ▶️ How to Run

1. Install Flask:

```
pip install flask
```

2. Run the app:

```
python app.py
```

3. Open in browser:

```
http://127.0.0.1:5000/
```

---

## ⚙️ How It Works

* User enters desired password length
* Form sends request to Flask backend
* Backend generates password using Python libraries
* Password is displayed on the webpage

---

## 📸 UI Overview

* Input field for password length
* Generate button
* Output section showing generated password

---

## ⚠️ Limitations

* No password strength indicator
* No option to customize character types
* No copy-to-clipboard feature

---

## 🔧 Future Improvements

* Add password strength meter
* Add character selection options (symbols, numbers, etc.)
* Add copy button
* Improve UI with JavaScript

---

## 📌 Note

This is a beginner-level project focused on understanding Flask basics, form handling, and simple backend logic.

---
