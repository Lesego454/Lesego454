# Hi — I’m Lesego Mohuba 👋

Front-end / full-stack web developer based in South Africa. I design and build fast, accessible, SEO-ready websites and web apps end-to-end.

- 🧱 Stack: React · TypeScript · TanStack Start · Vite · Tailwind CSS
- 🎬 Focus: motion-driven interfaces, design systems, production-ready SEO
- 📫 Email: lbmohuba@gmail.com
- 💼 LinkedIn: https://www.linkedin.com/in/lesego-mohuba-bba326134/

---

## Table of contents
- [Projects](#projects)
- [What I bring](#what-i-bring)
- [Screenshots](#screenshots)
- [Contact & availability](#contact--availability)

---

## 🚀 Projects

### Kindera
**Live:** https://kindera.co.za

A production website built and shipped for the web — responsive layout, clear information architecture and fast first paint.

Tech (author-provided): React · TypeScript · Tailwind CSS

Highlights / Notes
- Production site with focus on performance and accessibility.

Kindera — case study
Built the front-end for Kindera, a preschool discovery platform: focused on fast load, accessible search UX, and clear listing details. Implemented verified‑badge UI for providers and a secure provider dashboard.

Performance & accessibility (high-level)
- Fast, whitespace-first layout — keep images optimized and use lazy-loading for below-the-fold images.
- Ensure the search input has a visible label or aria-label for screen readers and the primary CTA uses an accessible name.
- Consider adding an accessible skip link and verifying color contrast for any UI text over images.

---

### Veld Mining Machines and Supplies — concept build
**Live:** https://veld-mining-portfolio.lovable.app · **Case study:** https://veld-mining-portfolio.lovable.app/case-study

A concept, multi-page marketing site built to demonstrate front-end, motion-design and SEO capability.

Highlights:
- Scroll-driven 180-frame canvas sequence scrubbed to scroll position (smoothed with requestAnimationFrame)
- Object-fit math so the sequence stays full-bleed with no zoom across viewports
- Fixed backdrop that persists across route changes
- Per-route SEO (title, description, Open Graph, canonical)
- Keyboard-reachable UI, mobile drawer, and prefers-reduced-motion fallback

Tech: TanStack Start · React · TypeScript · Vite · Tailwind CSS · Canvas API

> Veld Mining Machines and Supplies is fictional — a portfolio concept (not trading).

Veld — case study
Concept build demonstrating high-fidelity motion design: implemented a 180-frame canvas sequence, per-route SEO, and reduced-motion fallbacks. Focused on smooth cross-route transitions and accessible navigation.

Performance & accessibility (high-level)
- Large hero images and canvas sequences can impact Largest Contentful Paint; use optimized images and consider using a low-quality image placeholder (LQIP) for the hero.
- Provide clear reduced-motion fallbacks and ensure the canvas animation is controllable via prefers-reduced-motion.
- Add semantic headings and ARIA roles for the nav and interactive controls to improve screen-reader navigation.

---

| Area | Detail |
| --- | --- |
| Front-end | React, TypeScript, component architecture, design systems |
| Motion | Canvas, scroll-driven animation, requestAnimationFrame, reduced-motion support |
| Performance | SSR, lazy loading, fast first paint, bundle splitting |
| SEO | Semantic HTML, per-page metadata, Open Graph, canonical URLs |
| Delivery | Concept → design → build → deploy, able to deliver solo or as part of a team |

---

## 📷 Screenshots

The screenshot files referenced below should live in `assets/screenshots/`. For best results, convert to WebP and optimize sizes (≈1200px width, ≤250 KB for stills).

![Veld hero](assets/screenshots/veld-hero.webp "Veld Mining — hero showcasing the canvas-driven, full-bleed sequence and primary CTAs")

![Kindera hero](assets/screenshots/kindera-hero.webp "Kindera — focused hero with clear CTA: search for preschools by city or suburb")

Notes about screenshots
- These reference files in `assets/screenshots/`. If the images are currently in the repository root, move them to `assets/screenshots/` and rename to `veld-hero.webp` and `kindera-hero.webp`.
- For motion previews, include short MP4 clips (≤2 MB) named `veld-preview.mp4` or similar.

---

## 📬 Contact & availability

Open to junior/mid front-end roles, contract work and freelance projects (local or remote).

Email: lbmohuba@gmail.com · LinkedIn: https://www.linkedin.com/in/lesego-mohuba-bba326134/

If you're hiring or want a quick chat about a project, please get in touch — happy to share case studies, code samples, and deploy metrics.

---

## Next steps (what I will do / what I need from you)
- I will open (or have opened) a pull request with these README improvements from the `update/readme-improvements` branch.
- Optional: I can move and optimize screenshots into `assets/screenshots/` if you confirm the exact filenames are present in the branch. If the optimized images don't exist yet, please upload them or tell me the filenames to rename.
- If you want, I can convert the inline HTML figures to Markdown image syntax (already done here) and tidy any remaining formatting.
