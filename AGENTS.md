# AGENTS.md

## Project Overview
This is a simple static one page website project.

The site is deployed via **Netlify** and the production URL is:  
👉 https://www.valhalla-run.de

---

## File Structure Rules

The agent must strictly follow this structure when creating or modifying files:

### 1. HTML
- All HTML must live in a **single file**:
  - `index.html`
- Do **not** create additional HTML files unless explicitly instructed.

### 2. JavaScript
- All JavaScript must be written **directly inside `index.html`**
- Use `<script>` tags within the HTML file
- Do **not** create separate `.js` files

### 3. CSS (Styling)
- All styles must be placed in:
  - `styles.css`
- Link this file inside `index.html`
- Do **not** inline large CSS blocks inside HTML unless explicitly required

### 4. Media Assets
- All images, videos, or other media must go into:
  - `/media`
- Use relative paths when referencing media (e.g. `media/image.png`)

---

## Development Guidelines

- Keep the project **simple and maintainable**
- Avoid unnecessary abstractions or additional files
- Prefer **readability over cleverness**
- Ensure all paths work correctly with Netlify deployment
- Assume this is a **static site** (no backend)

---

## Deployment Context

- Hosting: Netlify
- Production URL: https://valhalla-run.lamine-dia.de
- The site should always be compatible with static hosting
- Avoid anything that requires a server runtime

---

## When Making Changes

- Do not restructure the project unless explicitly asked
- Respect the single HTML file rule
- Ensure any new features fit within the existing constraints
- Double-check that all links, scripts, and assets resolve correctly