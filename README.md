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
- Recommended additions for the README: one hero screenshot and a 1–2 sentence case study (goal, role, outcome).

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

Performance & accessibility (high-level)
- Large hero images and canvas sequences can impact Largest Contentful Paint; use optimized images and consider using a low-quality image placeholder (LQIP) for the hero.
- Provide clear reduced-motion fallbacks and ensure the canvas animation is controllable via prefers-reduced-motion.
- Add semantic headings and ARIA roles for the nav and interactive controls to improve screen-reader navigation.

---

## 🛠️ What I bring

| Area | Detail |
| --- | --- |
| Front-end | React, TypeScript, component architecture, design systems |
| Motion | Canvas, scroll-driven animation, requestAnimationFrame, reduced-motion support |
| Performance | SSR, lazy loading, fast first paint, bundle splitting |
| SEO | Semantic HTML, per-page metadata, Open Graph, canonical URLs |
| Delivery | Concept → design → build → deploy, able to deliver solo or as part of a team |

---

## 📷 Screenshots

<!-- Using the files you uploaded to the repository (raw URLs point to main branch uploaded files). -->

<figure>
  <img src="https://raw.githubusercontent.com/Lesego454/Lesego454/main/assetsscreenshotsveld-hero.webp.jpg" alt="Veld Mining homepage hero: yellow mining truck in a rocky quarry with large overlaid headline 'QUALITY MINING MACHINERY' and red accent CTAs." style="max-width:100%;">
  <figcaption><em>Veld Mining — hero showcasing the canvas-driven, full-bleed sequence and primary CTAs.</em></figcaption>
</figure>

<figure>
  <img src="https://raw.githubusercontent.com/Lesego454/Lesego454/main/assetsscreenshotskindera-hero.webp.jpg" alt="Kindera homepage hero: centered headline 'Find the Perfect Preschool Near You', short description and a prominent rounded search bar with blue search button." style="max-width:100%;">
  <figcaption><em>Kindera — focused hero with clear CTA: search for preschools by city or suburb.</em></figcaption>
</figure>

Notes about screenshots
- The images above reference the files you uploaded to the repository root. If you prefer them stored under assets/screenshots/, rename or move the files to that path (assets/screenshots/kindera-hero.webp, assets/screenshots/veld-hero.webp) and update the paths here accordingly.
- For best results convert to WebP (still) and MP4 (short motion preview) and keep sizes optimized (~1200px width, ≤250 KB for stills, ≤2 MB for short MP4 previews).

---

## 📬 Contact & availability

Open to junior/mid front-end roles, contract work and freelance projects (local or remote).  
Email: lbmohuba@gmail.com · LinkedIn: https://www.linkedin.com/in/lesego-mohuba-bba326134/

If you're hiring or want a quick chat about a project, please get in touch — happy to share case studies, code samples, and deploy metrics.

---

## Next steps I completed and what's left
- Completed: tightened README copy, added project notes, embedded the images you uploaded (via raw URLs), added high-level performance & accessibility notes.
- Remaining (optional): move images into assets/screenshots/, add a short MP4 preview for Veld, run Lighthouse and paste scores here so I can include exact metrics in the README.

When you're ready I can prepare the PR title+body and open the PR for review (or give the gh CLI command for you to open it).