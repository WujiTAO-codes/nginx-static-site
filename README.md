# nginx-static-site
A simple static website served with Nginx, deployed via Netlify to learn Docker and web hosting fundamentals.

# Static Website with Nginx & Netlify

This project is a simple static website served using **Nginx** in Docker, then deployed to **Netlify** for free public hosting. It's part of my learning journey into Docker, web development, and deployment.

## 🔧 Features
- Minimal HTML landing page
- Served via Nginx container (for local testing)
- Deployed using Netlify (Git-based CI/CD)

## 🐳 Local Preview with Docker

```bash
docker build -t nginx-site .
docker run -d -p 8080:80 nginx-site
