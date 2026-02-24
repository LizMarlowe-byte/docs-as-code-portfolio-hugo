---
title: About this Site
# layout: not required in Hugo unless you’ve defined custom kinds
# nav_order: not used by Hugo; navigation is controlled by your layouts/menus
---

Welcome to the third project in my **Docs‑as‑Code Portfolio Series**, where I’m building and publishing documentation sites using four different static site generators: **MkDocs**, **Hugo**, **Docusaurus**, and **Jekyll**.

This site represents my work with **Hugo** and demonstrates how I approach modern documentation workflows—from information architecture and content strategy to automated builds and publishing.

---

## 🎯 Purpose of This Project

As a Sr. Technical Writer, I use git‑based workflows and developer‑centric tooling.  
This portfolio series is my opportunity to:

- Strengthen and demonstrate my docs‑as‑code skills  
- Explore and compare popular SSGs used in engineering teams  
- Showcase real examples of my technical writing  
- Build documentation sites end‑to‑end using best practices  
- Create a curated, public‑facing writing and tooling portfolio  

> **Tip:**  
> In Hugo, the file `content/_index.md` serves as the site’s homepage (this page). Section landing pages use `content/<section>/_index.md`.

---

## ⚙️ What I Built Using **Hugo**

### 🔧 Workflow & Architecture
- Section‑based IA using **Hugo’s content sections** (`content/user-guides`, `content/api-guides`, etc.) with clean section landing pages (`_index.md`)  
- Markdown authoring and **Git‑based reviews**  
- **Accessibility‑minded** content (alt text on images, clear headings)

### 🚀 Build & Delivery
- **GitHub Actions** workflow that installs **Hugo Extended**, builds the site, and deploys to **GitHub Pages**  
- **Project‑site**‑safe URLs using Hugo’s URL helpers (e.g., `{{ "assets/img/foo.png" | relURL }}`), so links and assets work under `/<repo>/`  
- Assets stored under `static/assets/…` (served at `/assets/...` in the built site)

> **Build & Hosting Notes**  
> - This is a **GitHub Pages *project* site** (not `username.github.io`). The site is hosted under a subpath, so links and images are generated with Hugo’s URL helpers to honor the configured `baseURL`.  
> - Using **GitHub Actions** to deploy keeps the build environment consistent and avoids local toolchain issues; every push to `main` rebuilds and deploys automatically.

### 📚 Organized Documentation Examples
- **User Guides** → `/user-guides/`  
- **API Guides** → `/api-guides/`  
- **How‑to Articles** → `/how-to-articles/`  
- **Technical Reference Guides** → `/technical-reference-guides/`  

---

## 🧱 Tech Stack
- **Hugo (Extended)** for static generation (Markdown + Go templates)  
- **GitHub Actions** to build/deploy  
- **GitHub Pages** project‑site hosting; URLs generated with Hugo helpers for subpath safety

**Source & CI (this site):**  
[Repository](https://github.com/LizMarlowe-byte/docs-as-code-portfolio-hugo) · [Actions](https://github.com/LizMarlowe-byte/docs-as-code-portfolio-hugo/actions)

---

## 🚧 All 4‑SSG Series Completed
1. **MkDocs** — ✔️ Completed  
2. **Hugo** — ✔️ Completed 
3. **Docusaurus** — ✔️ Completed  
4. **Jekyll** — ✔️ Completed

---
