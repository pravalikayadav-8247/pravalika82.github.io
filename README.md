# Developer Portfolio Quick Guide

Your starter portfolio is ready at:
`C:\Users\ASUS\.gemini\antigravity\scratch\portfolio`

---

## 📸 Step 1: Add Your Photo
1. Take a professional or clean headshot photo of yourself (e.g., `my-photo.jpg` or `profile.png`).
2. Copy the image into the `assets/` folder:
   `C:\Users\ASUS\.gemini\antigravity\scratch\portfolio\assets\my-photo.jpg`
3. Open `index.html` and find line 93:
   ```html
   <img id="profile-picture" src="assets/avatar-placeholder.svg" alt="Portrait" />
   ```
4. Change `src` to your filename:
   ```html
   <img id="profile-picture" src="assets/my-photo.jpg" alt="Portrait of Your Name" />
   ```

---

## 💻 Step 2: Add Your Projects & Source Code
1. Push your project code to GitHub if you haven't already.
2. In `index.html`, find the `<section class="section projects" id="projects">` area.
3. For each project card:
   - Change the **Project Title** and **Description**.
   - Update tech stack tags (e.g., React, Python, PostgreSQL).
   - Update the **Live Demo** link:
     ```html
     <a href="https://your-live-demo.com" target="_blank">Live Demo</a>
     ```
   - Update the **Source Code** link to your GitHub repo:
     ```html
     <a href="https://github.com/your-username/your-repo-name" target="_blank">Source Code</a>
     ```

---

## 🌐 Step 3: Publish for Free on GitHub Pages
1. Create a new repository on GitHub named:
   `<your-github-username>.github.io`
2. Push the files (`index.html`, `style.css`, `script.js`, and `assets/`) to that repository.
3. In GitHub, go to **Settings** -> **Pages**.
4. Set source to **Deploy from a branch** -> `main` / `root`.
5. Your portfolio will be live at:
   `https://<your-github-username>.github.io`!
