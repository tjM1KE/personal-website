# Personal Website

Personal portfolio built with Astro and hosted on my self-managed homelab.

## Overview

This repository contains the source code for my personal website. Its purpose is to document projects, technical work, and the skills I am developing across software engineering, Linux infrastructure, data engineering, and systems administration.

The website is intentionally simple. The focus is on showcasing projects and technical work rather than frontend design.

## Technologies

* Astro
* TypeScript
* HTML
* CSS

## Hosting

The site is deployed to my homelab, which consists of a dedicated Ubuntu Server running Docker.

Current deployment path:

```text
GitHub
    ↓
Astro Build
    ↓
Docker
    ↓
nginx
    ↓
Caddy
    ↓
Cloudflare Tunnel
    ↓
Public Website
```

The deployment pipeline will later be automated using GitHub Actions.

## Current Features

* Responsive layout
* Light and dark mode
* Project showcase
* Homelab overview
* Fast static site generation with Astro

## Planned Features

* Individual project pages
* Live homelab metrics
* Automated CI/CD deployment
* Blog and technical notes
* Search functionality

## Local Development

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Create a production build:

```bash
npm run build
```

## Development Notes

The initial version of this website was created with assistance from AI language models to accelerate frontend development and reduce time spent on boilerplate code.

I have reviewed, customised, and maintain the project myself, including the content, layout, infrastructure integration, deployment, and security-related changes. AI is used as a productivity tool to speed up implementation, while I remain responsible for understanding and maintaining the codebase.

## License

MIT
