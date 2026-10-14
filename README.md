# Adin Comara — Personal Portfolio Website (Astro & Tailwind CSS)

Personal developer portfolio website of **Adin Comara**, Software Engineer specializing in Laravel, PHP, and Applied AI. Built with **Astro** for ultra-fast static rendering, zero-JS overhead, and maximum SEO performance.

## 🚀 Features & SEO Optimization
- **Built with Astro v5**: 100% static HTML generation (SSG) with zero framework JavaScript bloat.
- **Maximum SEO Score**: Pre-rendered OpenGraph, Twitter Cards, Canonical links, and **Schema.org Person** JSON-LD structured data.
- **Native Tailwind CSS Build**: Pre-compiled and minified styles (no slow CDN runtime scripts).
- **Automated Sitemaps & Robots**: Automated `sitemap.xml`, `sitemap-index.xml`, and crawler-friendly `robots.txt`.
- **High-Tech Aesthetic**: Light/Dark mode with no FOUC (default light), modern tech-grid patterns, and smooth Spring Reveal animations.
- **Google Search Console Ready**: Includes live ownership verification token.

## 📂 Project Structure
- `src/layouts/Layout.astro`: Base layout with dynamic SEO meta tags, Google Fonts, and Schema.org metadata.
- `src/components/`: Modular Astro components (`Header.astro`, `Hero.astro`, `Skills.astro`, `Projects.astro`, `Footer.astro`).
- `src/pages/index.astro`: Main portfolio page entry point.
- `src/styles/global.css`: Tailwind directives and custom animation styles.
- `public/`: Static root assets (`profile.jpg`, `robots.txt`, `sitemap.xml`, `googlee35499776b5a7ee6.html`).
- `dist/`: Pre-rendered production build served on port 8088 via Cloudflare Tunnel.

## 💻 Development & Build Commands
```bash
# Install dependencies
npm install

# Start local Astro dev server
npm run dev

# Build production static bundle to dist/
npm run build
```
