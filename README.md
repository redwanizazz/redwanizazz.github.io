# 🌐 Sharzil Izaz Mahmud — Portfolio Website

A personal developer portfolio built with pure HTML & CSS. Showcases my projects, skills, experience, and achievements in a clean dark-themed design.

🔗 **Live Site:** [redwanizazz.github.io](https://redwanizazz.github.io)

---

## ✨ Features

- **Dark theme** with a GitHub-inspired color palette
- **Fully responsive** — works on mobile, tablet, and desktop
- **Smooth scroll navigation** with a sticky navbar
- **Sections:** Hero, Skills, Projects, Experience, Certifications & Competitions, Contact
- **Zero dependencies** — plain HTML & CSS, no frameworks or build tools needed

---

## 🗂️ Project Structure
```
redwanizazz.github.io/
├── index.html       # Main portfolio file (all HTML + CSS in one file)
├── photo.jpg        # Your profile photo (add this yourself)
└── README.md        # This file
```

---

## 🚀 Deployment (GitHub Pages)

1. Create a repository named exactly `redwanizazz.github.io`
2. Clone it locally:
```bash
   git clone https://github.com/redwanizazz/redwanizazz.github.io
```
3. Add `index.html` and `README.md` to the folder
4. Push to GitHub:
```bash
   git add .
   git commit -m "Initial portfolio deploy"
   git push origin main
```
5. Your site is live at **https://redwanizazz.github.io** within a few minutes

---

## 🖼️ Adding Your Profile Photo

1. Add your photo to the project folder and name it `photo.jpg`
2. Open `index.html` and find the avatar section:
```html
   <!-- Replace this -->
   👤

   <!-- With this -->
   <img src="photo.jpg" alt="Sharzil Izaz Mahmud" />
```

---

## ✏️ Customization

| What to change | Where to find it |
|---|---|
| Name, role, bio | `hero` section in `index.html` |
| Project links & descriptions | `projects-grid` section |
| Skills tags | `skills-grid` section |
| Social/contact links | `contact-grid` section and nav buttons |
| Accent color | `--accent` CSS variable at the top |
| Font | Google Fonts `<link>` tag in `<head>` |

To change the accent color from blue to any other color, update this line near the top of the `<style>` block:
```css
--accent: #58a6ff;  /* change this hex value */
```

---

## 🛠️ Built With

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)

---

## 📬 Contact

- **Email:** redwanizaz10@gmail.com
- **LinkedIn:** [linkedin.com/in/sharzilizaz](https://linkedin.com/in/sharzilizaz)
- **GitHub:** [github.com/redwanizazz](https://github.com/redwanizazz)

---

> ⭐ If you found this portfolio template useful, feel free to fork it and make it your own!
