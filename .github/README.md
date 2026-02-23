# Fajar — Portfolio Website

A clean, recruiter-friendly portfolio website built with **HTML + CSS + JavaScript**.

## 🚀 Quick Start

1. Open `index.html` in a browser (use a local server for JSON loading)
2. Or deploy to GitHub Pages

### Local Dev Server

```bash
# Using Python
python -m http.server 8080

# Using Node.js
npx serve .
```

## ✏️ How to Update Content

All content is stored in JSON files inside the `data/` folder. Edit these files to update your portfolio:

| File | Content |
|------|---------|
| `data/profile.json` | Name, role, about text, contact links, CV link |
| `data/skills.json` | Skill categories and items |
| `data/experience.json` | Work history with contributions |
| `data/projects.json` | Projects and certifications |

### Adding a Project Screenshot

1. Add your image to `assets/images/`
2. Update the `screenshot` field in `data/projects.json`

## 📁 Folder Structure

```
portfolio/
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   └── images/
├── data/
│   ├── profile.json
│   ├── skills.json
│   ├── experience.json
│   └── projects.json
└── README.md
```

## 🌐 Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, folder `/`
4. Your site will be live at `https://yourusername.github.io/portfolio/`

## 🛠 Tech Stack

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox, Glassmorphism)
- Vanilla JavaScript (ES6+)
- Google Fonts (Inter)
- Font Awesome 6 (icons)
