# Personal Portfolio — Adil Mohammad

A clean, responsive personal portfolio website showcasing projects, skills, and contact information. This repository contains the static source files (HTML, CSS, JS, images) used to build and host the portfolio.

---

## At a glance

- Purpose: Present professional work, projects, and contact details in a focused, accessible way.
- Layout: Single-page responsive design with sections for hero, about, services, projects, testimonials, blog/contact, and footer.
- Tech: HTML, CSS (Sass partials included), JavaScript, and common frontend libraries (Bootstrap, AOS, Owl Carousel).

## Preview

Include a screenshot or live demo link here.

![Portfolio screenshot](images/screenshot.svg)

Live demo: (add your GitHub Pages or deployed URL here)

---

## Features

- Responsive layout (mobile-first)
- Smooth scrolling and section animations (AOS)
- Project carousel (Owl Carousel)
- Contact form front-end (replace with server or service for form handling)
- Sass source files for easy customization

## Project structure

Top-level files and folders:

- `index.html` — main entry page
- `css/` — compiled CSS and vendor styles
- `js/` — JavaScript libraries and main scripts
- `images/` — images and icons used on the site
- `scss/` — Sass source files (partials and main `style.scss`)

Project photos and thumbnails

 - Store polished project images inside `images/projects/` (example: `images/projects/project-1.png`).
 - Keep images optimized for web (max width ~1600px) and provide smaller thumbnails for lists (e.g., `project-1-thumb.jpg`).

## Local development

1. Clone the repo:

```powershell
git clone https://github.com/adil-mohammad-dev/personal-portfolio.git
cd personal-portfolio
```

2. Open `index.html` directly in your browser for a quick preview. Modern browsers will load the local assets without a server.

3. Optional — run a local static server (recommended for testing relative paths and service integrations):

```powershell
# Using Python 3 (if installed)
python -m http.server 5500
# Then open http://localhost:5500
```

Or use VS Code Live Server extension for an instant reload experience.

## Build / Customize

- Edit styles in `scss/` and recompile with your preferred Sass tool. Example (Dart Sass):

```powershell
# install sass globally or use your package manager
sass scss/style.scss css/style.css --no-source-map --style=expanded
```

- Update content directly in `index.html` for sections, projects, and links.

## Deployment (GitHub Pages)

1. Push your branch to GitHub (this repo already uses `main`):

```powershell
git add .
git commit -m "Add portfolio site"
git push origin main
```

2. Enable GitHub Pages in the repository settings — choose the `main` branch and `/ (root)` folder.

3. After a minute, the site will be available at `https://<your-username>.github.io/<repo-name>/`.

Tip: If using custom domain, add a `CNAME` file with your domain and configure DNS accordingly.

## Contact

- Email: addil@example.com (replace with your email)
- Twitter / LinkedIn: add your social links in the footer and here

## Accessibility & Performance

- Images: optimize images in `images/` for web (use WebP where possible)
- Lighthouse: run audits in Chrome DevTools and apply improvements for accessibility and performance

## License

This project is open for reuse. Add a license file (e.g., MIT) if you want to allow others to use the code.

---

If you'd like, I can:

- Add a polished README badge row (build/deploy/status)
- Generate a screenshot and add it to `images/screenshot.png`
- Add a `CNAME` or GitHub Actions workflow to auto-deploy to GitHub Pages.

Replace placeholder text (live demo URL, your email, social links) before publishing.