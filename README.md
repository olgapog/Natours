# 🌿 Natours

Natours is a front-end educational project developed as part of the course  
**“Advanced CSS and Sass: Flexbox, Grid, Animations and More!”**.

The project focuses on migrating from **pure CSS to a scalable SCSS architecture**, as well as configuring a **custom build process using npm scripts**.

---

## 🎯 Project Objectives

- Migration from **CSS to SCSS**
- Building a **modular Sass architecture**
- Setting up a **build workflow via `package.json`**
- Automating:
  - SCSS compilation
  - Vendor prefixing
  - CSS concatenation
  - CSS minification

---

## 🛠 Technology Stack

- HTML5  
- SCSS (Sass)  
- npm  
- PostCSS & Autoprefixer  
- Git & GitHub  

---

## 📂 Project Structure

```plaintext
Natours/
├── css/
│   ├── fonts/
│   ├── icon-font.css
│   ├── style.css
│   ├── style.css.map
│   ├── style.comp.css          # generated (ignored)
│   ├── style.comp.css.map      # generated (ignored)
│   ├── style.concat.css        # generated (ignored)
│   └── style.prefix.css        # generated (ignored)
├── img/
├── sass/
│   ├── abstracts/
│   ├── base/
│   ├── components/
│   ├── layout/
│   ├── pages/
│   └── main.scss
├── index.html
├── package.json
├── package-lock.json
├── .gitignore
└── README.md

⚙️ Build Process
The entire build process is managed via npm scripts and includes:

SCSS compilation

Automatic vendor prefixing

CSS concatenation

CSS minification

All intermediate generated files (*.prefix.css, *.concat.css, *.comp.css) are excluded from version control using .gitignore, keeping the repository clean and production-ready.

🚀 Getting Started
Install dependencies:

npm install

Run the build process:

npm run build

📌 Project Status
✅ Completed
🎓 Educational project prepared for portfolio demonstration

📄 License
This project is created for educational purposes only.

👤 Author Olga Pogrebna
Developed as part of a professional front-end development learning path.

