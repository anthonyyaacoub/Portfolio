# Anthony Yaacoub - Portfolio Website

[![Quarto Publish](https://github.com/anthony-yaacoub/portfolio/actions/workflows/publish.yml/badge.svg)](https://github.com/anthony-yaacoub/portfolio/actions/workflows/publish.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

Production-grade personal portfolio built with Quarto, showcasing the intersection of Computer Science and Data Analytics. This website demonstrates engineering rigor through modular architecture, CI/CD automation, and bilingual content delivery.

**Live Site:** [https://anthony-yaacoub.github.io](https://anthony-yaacoub.github.io)

## Features

- 🚀 **Automated Deployment**: GitHub Actions CI/CD pipeline
- 📊 **Interactive Projects**: Embedded Streamlit apps and live demos
- 🌐 **Bilingual Support**: English/Spanish content for Madrid market
- 🎨 **Custom Design**: SCSS theming with professional color palette
- 📱 **Responsive**: Mobile-first design approach
- 🔍 **SEO Optimized**: Meta tags, sitemap, and structured data

## Tech Stack

- **Static Site Generator**: Quarto 1.4+
- **Styling**: SCSS + Custom CSS
- **Deployment**: GitHub Pages
- **CI/CD**: GitHub Actions
- **Analytics**: Google Analytics (optional)

## Project Structure

```
portfolio-website/
├── .github/workflows/      # CI/CD automation
├── blog/                   # Technical blog posts
├── projects/              # Case studies (STAR format)
├── styles/                # Custom SCSS and CSS
├── assets/                # Images and downloadable files
├── _quarto.yml            # Global configuration
└── *.qmd                  # Page content files
```

## Local Development

### Prerequisites

- Quarto 1.4+ ([Install](https://quarto.org/docs/get-started/))
- Python 3.11+
- Git

### Setup

```bash
# Clone the repository
git clone https://github.com/anthony-yaacoub/portfolio.git
cd portfolio

# Install Python dependencies
pip install jupyter matplotlib pandas plotly scikit-learn

# Preview the site
quarto preview

# Build the site
quarto render
```

The site will be available at `http://localhost:4200`

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch. The CI/CD workflow:

1. Checks out the repository
2. Sets up Quarto and Python
3. Installs dependencies
4. Renders the site
5. Deploys to `gh-pages` branch

### Manual Deployment

```bash
quarto publish gh-pages
```

## Content Guidelines

### Blog Posts

Place new posts in `blog/posts/YYYY-MM-DD-title/index.qmd`:

```markdown
---
title: "Your Post Title"
description: "Brief description"
author: "Anthony Yaacoub"
date: "2024-12-16"
categories: [python, machine-learning]
---

Your content here...
```

### Project Case Studies

Follow the STAR format (Situation, Task, Action, Result):

```markdown
---
title: "Project Title"
description: "One-line summary"
date: "2024-12-16"
categories: [fastapi, docker, mlops]
image: images/system-diagram.png
---

## Situation
Business context...

## Task
Technical challenges...

## Action
Engineering solution...

## Result
Impact and metrics...
```

## Contributing

This is a personal portfolio, but feedback is welcome! Please open an issue for:

- Broken links
- Rendering issues
- Content suggestions

## License

MIT License - feel free to use this structure for your own portfolio.

## Contact

- **Email**: ayaacoub@student.ie.edu
- **LinkedIn**: [anthony-yaacoub](https://linkedin.com/in/anthony-yaacoub-37590a1a6)
- **GitHub**: [@anthony-yaacoub](https://github.com/anthony-yaacoub)

---

Built with [Quarto](https://quarto.org) | Hosted on [GitHub Pages](https://pages.github.com)
