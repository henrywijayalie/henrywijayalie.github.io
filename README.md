# Henry Wijaya | Online Resume

Personal portfolio and online resume for Henry Wijaya, a software developer focused on mobile applications, web development, and database-driven systems.

[![Live site](https://img.shields.io/badge/Live%20site-henrywijayalie.github.io-0f172a?style=flat-square&logo=github)](https://henrywijayalie.github.io/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.8-7952b3?style=flat-square&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![Static site](https://img.shields.io/badge/Website-static-16a34a?style=flat-square)](https://pages.github.com/)

[Overview](#overview) &bull; [Features](#features) &bull; [Run locally](#run-locally) &bull; [Deploy](#deploy-to-github-pages)

## Overview

This repository contains the source for Henry Wijaya's responsive online resume. The site presents professional experience, technical skills, and contact links in a single-page layout that works on desktop and mobile screens.

> [!NOTE]
> This is a dependency-light static website. CSS frameworks, icons, and fonts are loaded from public CDNs, so an internet connection is recommended when previewing the site locally.

## Features

- Responsive navigation with mobile collapse behavior
- Hero section with primary contact and experience actions
- Professional summary and skill proficiency sections
- Experience timeline covering professional roles and projects
- Contact links for WhatsApp, email, and LinkedIn
- Smooth scrolling and a scroll-to-top control
- Responsive styling for desktop and mobile viewports

## Technology

- HTML5 for page structure and content
- CSS3 for custom layout, color, typography, and responsive styling
- [Bootstrap 5.3.8](https://getbootstrap.com/) for grid and navigation behavior
- [Bootstrap Icons 1.13.1](https://icons.getbootstrap.com/) for interface icons
- [Google Fonts](https://fonts.google.com/) using Manrope and Newsreader
- GitHub Pages for hosting

## Run locally

No package installation, build step, or runtime is required.

Open `index.html` directly in a browser.

> [!TIP]
> In VS Code, the Live Server extension can optionally serve `index.html` while you edit the page.

## Deploy to GitHub Pages

The repository is already structured for GitHub Pages because the entry point is `index.html` at the repository root.

1. Push the latest changes to the `main` branch.
2. Open the repository's **Settings** on GitHub.
3. Select **Pages** under **Code and automation**.
4. Set the source to **Deploy from a branch**.
5. Select `main` and the `/ (root)` folder, then select **Save**.

After deployment completes, the site is available at:

<https://henrywijayalie.github.io/>

## Project structure

```text
.
├── index.html             # Page content and interactive behavior
├── style.css              # Custom styles and responsive layout
├── img/
│   ├── profile.jpeg       # Profile image asset
│   └── projects/         # Project image assets
└── README.md              # Project documentation
```

## Content updates

Most resume updates can be made directly in `index.html`:

- Edit the hero, summary, skills, experience, and contact sections.
- Adjust colors, spacing, typography, and responsive rules in `style.css`.
- Add or replace image assets under `img/` and update their paths in the HTML.

Keep external CDN versions and their `integrity` attributes in sync when upgrading frontend dependencies.
