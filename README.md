# 🎨 Slidev Chess Creativity

![Deploy Slides](https://github.com/apulito/slidev-chess-creativity/actions/workflows/deploy.yml/badge.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📚 About 
This repository contains the project used for the seminar using [Slidev](https://sli.dev/) for a dynamic and interactive presentation. The slides highlight:

- Chess creativity and its evolution.
- Insights into defense, strategic structures and creative decision-making.

🛑 **Note:** The seminar is taught in Italian IT.

## 🚀 Demo 
- [Intro](https://apulito.github.io/slidev-chess-creativity/intro)
- [Essence](https://apulito.github.io/slidev-chess-creativity/essence)

> Additional sessions will be added.

## 🛠️ Setup 
To start the slide show:
```bash
- npm install
```

Each folder (e.g., intro, essence) contains its own slides.md. To run a specific session:
```bash
- npm run dev -- ./[session]/slides.md
```
And then visit <http://localhost:3030>

## 🌐 Deployment
The slides are automatically deployed using GitHub Actions. Each session is available under its specific route:

- https://apulito.github.io/slidev-chess-creativity/[session-name]/

The deployment workflow is configured to:

- Build the slides for each session.
- Export PDFs if configured.
