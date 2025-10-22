    # 🧑‍💻 Frontend Wizards — Stage 0 Task: Testable Profile Card

Welcome to my submission for the Frontend Wizards Stage 0 Internship Task 🎯

This project is a responsive, accessible Profile Card built using semantic HTML, modern CSS, and vanilla JavaScript.  
It demonstrates frontend fundamentals like semantic structure, accessibility, responsive design, and automated test readiness via data-testid attributes.

---

## 🚀 Project Overview

The Profile Card displays a user’s:

- Name
- Short Biography
- Current Time (in milliseconds)
- Avatar Image
- Social Media Links
- Hobbies
- Dislikes

Every visible element includes a data-testid attribute to support automated testing and validation.

---

## 🧱 Features

- ✅ Semantic HTML structure using <article>, <header>, <figure>, <section>, and <nav>
- ✅ Accessible images with alt text and proper aria attributes
- ✅ Responsive design for mobile, tablet, and desktop
- ✅ Real-time display of the current time using Date.now()
- ✅ Keyboard navigable links with visible focus styles
- ✅ Social links that open in a new tab (target="\_blank" with rel="noopener noreferrer")
- ✅ Automated test-ready with all required data-testid attributes

---

## 🛠️ Technologies Used

- HTML5
- CSS3 (Flexbox/Grid)
- Vanilla JavaScript

---

## 🧩 Folder Structure

project-folder/ │ ├── index.html ├── style.css ├── script.js └── README.md

---

## ⚙️ How It Works

- The current time is dynamically rendered using JavaScript:  
  `js
  const timeElement = document.querySelector('[data-testid="test-user-time"]');
  timeElement.textContent = Date.now();

The layout adapts to different screen sizes using responsive breakpoints.

The card remains testable and accessible with proper semantics.

---

🌐 Live Demo

🔗 Live Link: View Project Here
💻 GitHub Repo: View Source Code

---

👨‍💻 Author

Taiwo Hungbeme
Frontend Developer | Passionate about building clean, accessible, and interactive user interfaces.

🌍 Portfolio

🐙 GitHub

💼 LinkedIn

🐦 X (Twitter)

---

📜 License

This project is open-source and free to use for learning and demonstration purposes.
