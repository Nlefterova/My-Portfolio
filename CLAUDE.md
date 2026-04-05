# Portfolio — Natalia Lefterova

## About
Single-page portfolio website for UX/UI designer Natalia Lefterova. Built as a static HTML file (`index.html`) with inline CSS, hosted on GitHub Pages.

**Live URL:** https://nlefterova.github.io/My-Portfolio/
**GitHub Repo:** https://github.com/Nlefterova/My-Portfolio

## Important Rules
- **NEVER push changes to GitHub.** Tell the user to push manually via GitHub Desktop. You have no permission to run git push, git remote, or any git commands that affect the remote.
- **NEVER touch the kartelboats-site repo or any other repo.** Only work within this Portfolio folder.
- The `main` branch is the live site the client can see. Do not modify it without explicit approval.

## Tech Stack
- Single HTML file with inline CSS (no external stylesheets, no build tools)
- Fonts: Cormorant Garamond (headings) + Raleway (body) via Google Fonts
- Language: Russian (lang="ru")
- Fixed width: 1440px
- No JavaScript frameworks — vanilla JS only (smooth scroll, modal, hash cleanup)

## Color Palette
- Sage green: `#A4B494` (primary accent)
- Dark sage: `#8fa882`
- Light sage: `#c8d4bb`
- Beige/Nevada Sand: `#EAD3B8`
- Dark text: `#1B1B1B`
- Body text: `#4A4A4A`
- Light grey text: `#747373`
- Light background: `#F5F5F5`
- Page background: `#E8E8E8`

## Structure (Sections/Frames)
1. **Hero** — Name, title, description, CTA buttons, isometric iMac mockup with Kartel Boats site
2. **About** — Bio, skills/tools tags, languages
3. **Organa Health** — Mobile app project (login screens, onboarding)
4. **Paws Up** — Web redesign (nav before/after, footer before/after, custom icons, UI pages)
5. **Place De Paris** — Branding + web design (identity: logos, typography, palette, brand book, printable materials, price list; UI pages)
6. **Kartel Boats** — Web design + AI (site screenshots, AI-generated photos, branded photos)
7. **My Process** — Design lifecycle visual (5 circles with wave SVG)
8. **Research Materials** — Personas, empathy maps, pains & gains, affinity map
9. **Prototyping Process** — Wireframes → Low-fi → High-fi progression
10. **Deliverables** — What the client receives (5 icon cards)
11. **Contacts** — Email, phone, Telegram, WhatsApp

## Navigation
- Dropdown menus for "Проекты" (4 projects) and "Обо мне" (About, Process, Deliverables)
- "Контакты" links to footer
- "Смотреть проекты" button scrolls to Organa Health
- "Связаться" opens contact modal popup
- All links use smooth scroll, hash is cleared after navigation so refresh goes to top

## Images
- All images stored in `images/` folder
- Large images are resized to 800-1920px width using `sips` before adding
- Project screenshots use `object-fit: cover` with consistent card heights
- Identity cards use `object-fit: contain` to avoid cropping

## Contact Info
- Email: nlefterova445@gmail.com
- Phone: +352 691 123 623
- Telegram & WhatsApp on the same number
