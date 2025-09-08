#My Personal Website
## 🚀 Project overview

A responsive portfolio site built with **HTML** and **CSS**. It includes an About section, projects showcase, and contact details.

---

## 🛠️ Tech stack

* HTML5
* CSS3 (Flexbox for layout)

---
## 📁 Project structure 

├── index.html          # Main page
├── script.js           # Javascript file
├── style.css           # Style sheet
└── assets/             # Contains Images and documents used in the portfolio

---

# 🧭 Local setup — step by step

1. **Clone the repo (if using GitHub)**


git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>


2. **Open the project in your editor**

bash
code .   # if you use VS Code

3. **Preview locally**

* Double-click `index.html` to open in a browser, or
* Install the VS Code extension **Live Server**, right-click `index.html`, and select *Open with Live Server*.

---

## 🌍 Deploying to GitHub Pages

Follow these steps carefully:

1. **Push your project to GitHub**

bash
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

2. **Enable GitHub Pages**

* Go to your repository on GitHub.
* Click on **Settings** (top menu).
* Scroll down to **Pages** in the left sidebar.
* Under **Source**, choose:
  - **Branch:** `main`
  - **Folder:** `/ (root)` (if your `index.html` is at the root)
- Click **Save**.

3. **Wait for deployment**
- GitHub will build your site (this takes about 1–2 minutes).
- Once ready, your site will be live at:
  `https://<your-username>.github.io/<repo-name>/`
