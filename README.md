# 🔍 GitHub Profile Finder

A simple web app built with **HTML, CSS, and JavaScript** that allows users to search for any GitHub username and instantly view their public profile information and repositories — all using the **GitHub REST API**.

---

## 🚀 Live Demo

👉 **[Github Finder](https://lokeshnehete119.github.io/github-profile-finder/)**


---

## 🧠 Features

* Search any GitHub user by username
* Displays profile info: avatar, name, bio, location, join date, and followers
* Lists latest repositories (with stars, forks, and languages)
* Handles errors gracefully (e.g., user not found)
* Fully responsive and minimal UI

---

## 🛠️ Tech Stack

* **HTML5** – structure
* **CSS3** – styling and layout
* **Vanilla JavaScript (ES6+)** – logic and API handling
* **GitHub REST API** – for fetching live data

---

## ⚙️ How It Works

1. Enter any GitHub username in the search bar.
2. The app fetches data from `https://api.github.com/users/{username}`.
3. Displays user details and latest repositories dynamically.

---


## 📦 Folder Structure

```
github-profile-finder/
│
├── index.html
├── styles.css
├── script.js
└── README.md
```

---

## 🧩 API Reference

**GitHub User API**
`https://api.github.com/users/{username}`

**Example:**

```bash
https://api.github.com/users/octocat
```


---
