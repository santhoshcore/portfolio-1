# Santhosh — Portfolio

A minimal, editorial personal portfolio for Santhosh — Aspiring Data Analyst & Computer Science Engineering student.

Single self-contained `index.html` — no build step, no dependencies to install. Fonts (Google Fonts) and animation (GSAP) load from CDN at runtime.

## Live Preview

Open `index.html` directly in any browser, or deploy with GitHub Pages (see below).

## Features

- Oversized editorial typography with staggered text-reveal hero animation
- Animated SVG line-chart trace (data-analyst signature detail)
- Custom magnetic cursor (desktop only)
- Scroll-triggered reveals via GSAP ScrollTrigger
- Dark / light theme toggle
- Filterable project grid (Excel / SQL / Python / Power BI)
- Client-side validated contact form
- Fully responsive, mobile full-screen nav menu
- Respects `prefers-reduced-motion`

## Before you publish — replace placeholders

- [ ] Swap the "Photo — add yours" box for a real photo (`.photo-frame`)
- [ ] Link the résumé PDF — update `#resume-link` href and the Resume section download link
- [ ] Update GitHub / LinkedIn / email links (search for `github.com/`, `linkedin.com/`, `hello@santhosh.dev`)
- [ ] Add real GitHub/live-demo URLs for each project in the `projects` array in the `<script>` section
- [ ] Update Certifications with your real dates/issuers in the `certs` array

## Deploy on GitHub Pages

1. Create a new repository on GitHub and push this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
2. In your repo: **Settings → Pages → Source** → select `main` branch, `/ (root)` folder → **Save**.
3. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Deploy on Vercel

1. Push this repo to GitHub (steps above).
2. Go to [vercel.com/new](https://vercel.com/new), import the repo.
3. Framework preset: **Other** (static). No build command needed — Vercel will serve `index.html` as-is.
4. Deploy.

## Tech

- Plain HTML/CSS/JS (no framework, no bundler)
- [GSAP](https://gsap.com/) + ScrollTrigger for animation (via cdnjs)
- Google Fonts: Fraunces, Inter, JetBrains Mono

## License

Personal portfolio — content and code free to reuse/adapt for your own site.
