# Portfolio Website

This repository contains the source code for my personal portfolio website built with HTML, CSS, and JavaScript, with a Python backend for content generation. The site is deployed on GitHub Pages.

## Overview

This is a responsive portfolio website showcasing my projects, skills, certifications, and contact information as an AI & Full Stack Engineer. The site features a clean, modern design with project carousels, lightbox modals, and smooth navigation.

## Structure

```
portfolio-website/
├── index.html                 # Main portfolio page with navigation and sections
├── cv.md                      # CV/resume content in Markdown
├── main.py                    # Python script for content generation
├── pyproject.toml             # Project dependencies and metadata
├── CNAME                      # Custom domain configuration
├── .gitignore                 # Files and directories ignored by Git
├── .nojekyll                  # Disables Jekyll processing on GitHub Pages
├── .python-version            # Specifies Python version
├── projects_html/             # Individual project detail pages
│   ├── pneumonia.html         # Pneumonia Detection project details
│   ├── climate.html           # Climate Data Imputation project details
│   └── rag.html               # RAG-Based AI System project details
└── src/                       # Static assets
    ├── profile.jpg            # Main profile image
    └── profile1.jpg           # Alternative profile image
```

## Features

- Fully responsive design that works on mobile, tablet, and desktop
- Interactive project and certification carousels
- Lightbox modal for viewing enlarged images
- Modern UI with smooth animations and transitions
- Skills and technology tags display
- Social media integration with contact options

## Setup

To run this project locally:

1. Clone the repository
2. Open `index.html` directly in your browser, or serve it using a local server:
   ```bash
   python -m http.server 8000
   ```
   Then navigate to `http://localhost:8000`

## Deployment

The site is deployed on GitHub Pages and can be viewed at [your-website-url].

## License

This project is open source and available under the MIT License.