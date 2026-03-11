# Muhammad Moin Raza — Personal Portfolio

> *"Piloting your journey to digital success"*

A modern, single-page personal portfolio for **Muhammad Moin Raza** — Digital Strategist, Aviation Professional, and Founder of [Marketus Marshal LLC](https://marketusmarshal.com).

---

## Live Demo

Deployed via Vercel — see [`vercel.json`](./vercel.json) for configuration.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | Pure CSS3 (custom properties, grid, flexbox, animations) |
| Scripting | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Inter, Poppins |
| Deployment | Vercel (static) |

No frameworks. No build tools. No dependencies. Zero npm installs required.

---

## Features

- **Fully responsive** — mobile, tablet, and desktop layouts
- **Custom cursor** — smooth lagged ring follower (desktop only)
- **Scroll reveal animations** — staggered fade-in on viewport entry
- **Animated counters** — numbers count up when scrolled into view
- **Skill bar animations** — progress bars animate on scroll
- **Sticky navigation** — blur backdrop on scroll, mobile hamburger menu
- **Live ad dashboards** — styled campaign result cards (Google, Meta, LinkedIn)
- **Ad results collage** — 12-tile gallery with blurred client identifiers
- **Tabbed portfolio** — toggle between Digital Marketing and Qatar Airways projects
- **Working contact form** — client-side with success state
- **Marquee ticker** — pauses on hover

---

## Project Structure

```
moin-portfolio/
├── index.html        # Complete single-page portfolio (all HTML + CSS + JS inline)
├── vercel.json       # Vercel deployment configuration
├── .gitignore        # Git ignore rules
└── README.md         # This file
```

---

## Deployment on Vercel

### Option A — Vercel Dashboard (Recommended)

1. Push this repository to GitHub
2. Go to [vercel.com](https://vercel.com) → **New Project**
3. Import your GitHub repository
4. Framework Preset: **Other** (or leave as auto-detected Static)
5. Root Directory: `/` (leave default)
6. Click **Deploy**

Done — Vercel will detect `vercel.json` automatically.

### Option B — Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy from project root
cd moin-portfolio
vercel

# For production deployment
vercel --prod
```

### Custom Domain

After deploying on Vercel:
1. Go to your project dashboard → **Settings → Domains**
2. Add your domain (e.g. `moinraza.com` or `moinraza.vercel.app`)
3. Update your DNS records as instructed

---

## Local Development

No build step needed. Simply open `index.html` in any browser:

```bash
# Using Python (if installed)
python3 -m http.server 3000

# Using Node.js (if installed)
npx serve .

# Or just double-click index.html
```

---

## Customization

All content, colors, and styles are in `index.html`:

| What to change | Where to find it |
|---|---|
| Colors / brand | `:root` CSS variables at top of `<style>` block |
| Profile photo | `<img src="data:image/png;base64,..."` in hero section |
| Contact details | `#contact` section |
| Ad dashboard metrics | `.dsh` cards in `#ads` section |
| Project cards | `.pc` cards in `#work` section |
| Testimonials | `revs` array in `<script>` block |
| Timeline entries | `.tli` items in `#journey` section |

---

## Contact

**Muhammad Moin Raza**
- Email: [moinraza496@gmail.com](mailto:moinraza496@gmail.com)
- Phone: +974 3358 8448
- LinkedIn: [linkedin.com/in/moinraza496](https://www.linkedin.com/in/moinraza496/)
- Agency: [marketusmarshal.com](https://marketusmarshal.com)

---

*© 2026 Muhammad Moin Raza. All Rights Reserved.*
