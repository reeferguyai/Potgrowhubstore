# 🌱 REEFER DUDE — reeferdude.com

> **Hustle hard. Grow loud. Smoke smart.**
> A two-person, zero-budget, open-source-only cannabis culture hub for adults 21+.
> Everything cannabis-adjacent **except the flower** — glass, pipes, wax tools, storage, hemp, LED grow
> gear, nutrients, design tools, blueprints, consults and a 24/7 AI budtender.

[![Age](https://img.shields.io/badge/age-21%2B-critical?style=flat-square)](#age-policy)
[![Budget](https://img.shields.io/badge/budget-%240-brightgreen?style=flat-square)](#the-zero-dollar-rule)
[![Stack](https://img.shields.io/badge/stack-React%20%7C%20Vite%20%7C%20Tailwind%20%7C%20Base44-blueviolet?style=flat-square)](#tech-stack)
[![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-black?style=flat-square)](#license)
[![Humans](https://img.shields.io/badge/humans-2%20%2B%20one%20dog-ff69b4?style=flat-square)](#the-crew)

---

## 🧭 Table of Contents

| # | Section | # | Section |
|---|---------|---|---------|
| 1 | [About The Hustle](#about-the-hustle) | 11 | [Pages & Routes](#pages--routes) |
| 2 | [The Crew](#the-crew) | 12 | [Design System](#design-system) |
| 3 | [The Zero-Dollar Rule](#the-zero-dollar-rule) | 13 | [Voice & Persona](#voice--persona) |
| 4 | [Feature Modules](#feature-modules) | 14 | [Monetization Engine](#monetization-engine) |
| 5 | [Tech Stack](#tech-stack) | 15 | [SEO · AEO · Schema](#seo--aeo--schema) |
| 6 | [Quick Start](#quick-start) | 16 | [Domain Ownership & DNS Kit](#domain-ownership--dns-kit) |
| 7 | [PowerShell Hustle-Installer](#powershell-hustle-installer) | 17 | [Data Model](#data-model) |
| 8 | [Root Asset Files](#root-asset-files) | 18 | [Integrations](#integrations) |
| 9 | [Project Structure](#project-structure) | 19 | [Security & Privacy](#security--privacy) |
| 10 | [Accessibility](#accessibility) | 20 | [Roadmap](#roadmap) |

---

## 1. 🔥 About The Hustle

Reefer Dude exists because two broke people with a truck, a phone and a whole lot of hope decided that the
cannabis world deserved a corner of the internet that is honest, funny, useful and free.

We do not sell flower. We legally cannot. What we **can** do is everything else:

- Source the glass, the pipes, the wax tools, the storage, the hemp, the LED gear and the nutrients.
- Design the grow room, down to airflow and light spread.
- Write the blueprint, week by week, stage by stage.
- Name and profile the strain you dream up at 2am.
- Answer the question you are too embarrassed to ask a real budtender.
- Do it all without a single paywall, pop-up gate or "premium tier".

**Money in:** affiliate links, gear sourcing commissions, ads in reserved slots, members-only extras.
**Money out:** hosting, domain, coffee. That is the whole business plan.

## 2. 🧑‍🌾 The Crew

| Handle | Role | Responsibilities |
|--------|------|------------------|
| **Jessica** | Co-founder — Ops & Design | Design studio, blueprints, brand voice, customer care, the reason anything ships |
| **The OG** | Co-founder — Grow & Gear | Cultivation science, gear sourcing, ghost shop, consults, coffee consumption |
| **The Dog** | Morale Officer | Sleeping near the light rig, quality-assurance on smells |

Zero investors. Zero employees. Zero excuses.

## 3. 💸 The Zero-Dollar Rule

Every tool, library and service in this project must be **free and open source** for the build, or free at
the tier we use. No trials that expire into a bill. No credit-card-required anything.

| Layer | Free & Open Source Choice |
|-------|---------------------------|
| Frontend | React, Vite, Tailwind CSS |
| Backend / DB | Base44 (auth + entities + functions on the free tier) |
| Runtime | Node.js, npm, Python, pip |
| Version control | Git, GitHub Free |
| Terminal & shell | PowerShell 7, Windows Terminal, nano |
| Editor | VS Code + open-source extensions |
| Analytics | Plausible CE / Umami / Matomo (self-hosted) |
| Monetization | Google AdSense (free to join), Amazon Associates, Etsy Affiliate |
| Header bidding | Prebid.js (open source) |
| Design | Archivo Black, Space Grotesk, JetBrains Mono (Google Fonts, free) |
| Icons | Lucide (open source), emoji glyphs |
| Package manager (Windows) | Chocolatey (open source) |

## 4. 🧩 Feature Modules

| Module | Route | What it does | Status |
|--------|-------|--------------|--------|
| Home | `/` | Full pitch, six doors, proof, CTAs | ✅ Live |
| AI Budtender | `/budtender` | Chat with a no-upsell, no-judgment advisor | ✅ Live |
| Ghost Shop | `/ghost-shop` | No-inventory sourcing, eco-first, drop-ship routing | ✅ Live |
| Design Studio | `/design-studio` | AR/VR viewport + rotating orbital menu | ✅ Live |
| Strain Creation Lab | `/strain-lab` | Build a cross, get the full cultivar profile | ✅ Live |
| Grow Room Designer | `/grow-room` | Lights, air, feed, yield, power-cost math | ✅ Live |
| Blueprints | `/blueprints` | Plug-and-play room plans + request form | ✅ Live |
| Consultation | `/consultation` | Book the free 15-minute gut-check | ✅ Live |
| Testimonials | `/testimonials` | Public wall + submit your own | ✅ Live |
| About | `/about` | The two-person story | ✅ Live |
| FAQ | `/faq` | The questions people actually ask | ✅ Live |
| Legal | `/legal` | Terms, privacy, age policy, disclosures | ✅ Live |
| Crew Sign-Up | `/signup` | Join the list | ✅ Live |
| Onboarding | `/onboarding` | Five-step profile build | ✅ Live |
| Insider Bonus | Global | Dwell-time reward drop | ✅ Live |
| Age Gate | Global | 21+ confirmation, remembered locally | ✅ Live |
| Cookie Bar | Global | Consent with essential-only option | ✅ Live |

## 5. 🛠 Tech Stack

```text
Frontend      React 18 · Vite · Tailwind CSS · shadcn/ui primitives
Icons         lucide-react
Animation     CSS keyframes + transforms (reduced-motion aware)
Backend       Base44 entities + row-level security
AI            Base44 InvokeLLM (budtender, strain forge)
Data          Product · Testimonial · Consultation · Blueprint · CrewMember
Styling       Neo-brutalism + glassmorphism + claymorphism + retro-futurism
Palette       Deep Resin #0A0F0B · Ember #FF6B00 · Bud #A3E635 · Sky #0EA5E9
              Paper #F8FAFC · Soil #2B1D12 · Loam #6B4A2B · Copper #B4703A
```

## 6. ⚡ Quick Start

```bash
git clone <your-repo-url> reeferdude.com
cd reeferdude.com
npm install
npm run dev          # local preview
npm run build        # production build
npm run lint         # code check
```

## 7. 🪟 PowerShell Hustle-Installer

Copy `setup-reeferdude.ps1` **or** paste it straight into an elevated PowerShell window. It installs
Chocolatey, Git, Node.js, npm, Python, pip, nano, VS Code and PowerShell 7, creates the full
`C:\reeferdude.com` folder tree, writes every root asset file, installs the open-source Python and Node
toolchains, and initialises the repo.

```powershell
# one-liner to fetch and run
irm https://reeferdude.com/setup-reeferdude.ps1 | iex
```

## 8. 📁 Root Asset Files

| File | Purpose |
|------|---------|
| `index.html` | Full SEO · AEO · schema · analytics · verification head |
| `robots.txt` | Allow-all crawl policy, AI crawlers welcome, sitemaps declared |
| `sitemap.xml` | Every route on both domains + image extensions |
| `manifest.json` | PWA identity, shortcuts, icons, share target |
| `sw.js` | Service worker: core cache, image cache, offline, push |
| `ads.txt` | Authorized digital sellers |
| `humans.txt` | The humans, the standards, the thanks |
| `security.txt` + `.well-known/security.txt` | Vulnerability disclosure policy |
| `llms.txt` | Answer-engine briefing for AI assistants |
| `requirements.txt` | Open-source Python toolchain |
| `SEO.txt` · `AEO.txt` · `seo.md` · `aeo.md` · `META.md` | Search, answer-engine and social playbooks |
| `Branding-Bible.md` | Voice, colour, icon and copy law |
| `README.md` | This file |

## 9. 🗂 Project Structure

```text
reeferdude.com/
├─ index.html                  → the head that does the heavy lifting
├─ README.md                   → you are here
├─ Branding-Bible.md           → voice & visual law
├─ SEO.txt · AEO.txt · META.md → search / answer-engine / social playbooks
├─ seo.md · aeo.md             → same playbooks, readable markdown
├─ requirements.txt            → python toolchain
├─ setup-reeferdude.ps1        → copy-paste installer
├─ public/
│  ├─ robots.txt · sitemap.xml · manifest.json · sw.js · ads.txt
│  ├─ humans.txt · security.txt · llms.txt
│  ├─ .well-known/security.txt
│  ├─ icons/  social/  feed.xml  opensearch.xml  offline.html
├─ src/
│  ├─ App.jsx                  → router + gates
│  ├─ index.css                → design tokens & brutalist component layer
│  ├─ components/              → Nav, Footer, Layout, Brand primitives, gates, Seo
│  ├─ pages/                   → one file per route
│  ├─ hooks/                   → analytics, dwell reward, form state
│  └─ lib/                     → brand copy, links, helpers
└─ base44/
   └─ entities/                → Product · Testimonial · Consultation · Blueprint · CrewMember
```

## 10. ♿ Accessibility

- WCAG **AAA** contrast targets (`#F8FAFC` on `#0A0F0B` ≈ 18:1).
- Minimum **48×48px** touch targets on every control.
- Full keyboard path: skip link → nav → main → footer.
- `aria-label` on every icon-only button; `aria-expanded` on every disclosure.
- Age gate and cookie bar are real dialogs: `role="dialog"`, `aria-modal="true"`, focus contained.
- `prefers-reduced-motion` kills every animation.
- Semantic landmarks: `header`, `nav`, `main`, `footer`, `section`, ordered headings.
- Body text 18px/1.6 for readability.

## 11. 🧭 Pages & Routes

```text
/                /budtender       /ghost-shop      /design-studio
/strain-lab      /grow-room       /blueprints      /consultation
/testimonials    /about           /faq             /legal
/signup          /onboarding      *                → not-found page
```

## 12. 🎨 Design System

- **Neo-brutalism** — hard 2px ink borders, offset 8px shadows, no soft gradients on the frame.
- **Glassmorphism** — frosted, saturated panels over the Deep Resin background.
- **Claymorphism** — soft inset-shadow buttons and icon pods you want to squeeze.
- **Retro-futurism** — mono kickers, terminal spacing, orbital motion.
- **Floating elements** — a slow float on the live-status clay card.
- **Rotating orbital menu** — bong · pipe · bud · leaf · cartridge · wax orbs orbiting a seed pod.
- **Icons** — bud, leaf, bong, pipe, cartridge, wax jar, seed, hemp.
- **Type** — Archivo Black display, Space Grotesk body, JetBrains Mono labels.

## 13. 🗣 Voice & Persona

| Default copy | Reefer Dude copy |
|--------------|------------------|
| Buy Now | **GRAB THE BAG** |
| Submit | **SEND IT INTO ORBIT** |
| Contact Us | **HOLLER AT THE OGS** |
| Learn More | **SHOW ME THE GOODS** |
| Book Now | **LOCK IN MY SLOT** |
| 404 | **BRO, YOU'RE TOO HIGH. THIS PAGE DON'T EXIST.** |
| Invalid email | **THAT AIN'T A REAL PLUG. FIX YOUR EMAIL.** |
| Loading | **ROLLING IT UP…** |
| Empty state | **SHELF'S BARE. LET'S GO FIND SOMETHING.** |

## 14. 💰 Monetization Engine

| Stream | How it works | Where it lives |
|--------|--------------|----------------|
| Affiliate | Amazon Associates, Etsy, ShareASale, Impact links | Every gear tile, disclosed |
| Sourcing commission | Ghost agent routes buyers to vetted suppliers | `/ghost-shop` |
| Display ads | AdSense in reserved slots | Between sections, never over content |
| Header bidding | Prebid.js with open-source adapters | Reserved slots only |
| Members | Insider list: early drops, blueprint vault | `/signup` |
| Fans | Free consults → paid deep-dive blueprints | `/consultation` |
| Dwell reward | On-site time unlocks a bonus code | Global bonus timer |
| Sponsored placement | Clearly labelled "paid placement" tiles | `/ghost-shop` |
| Digital goods | Prints, plan bundles, strain profile packs | Future module |

## 15. 🔍 SEO · AEO · Schema

- One `<h1>` per page, strict heading order, semantic landmarks.
- Full head stack in `index.html`: verification tokens, robots directives, canonical, hreflang, Open
  Graph, Twitter cards, business contact data, geo signals, preconnects and analytic loaders.
- Schema.org **JSON-LD**: Organization, WebSite + SearchAction, Store, ItemList, FAQPage, HowTo,
  Service, SoftwareApplication, BreadcrumbList, Person, Offer, AggregateRating, Speakable.
- AEO: `llms.txt`, machine-readable answers, plain-question headings, direct answers in the first
  sentence, `Speakable` selector, AI crawlers explicitly allowed in `robots.txt`.

## 16. 🌐 Domain Ownership & DNS Kit

**You can prove you own the domain even with no website on it.** Add these at your registrar (or any DNS
provider) and any lookup tool on earth will show it is yours:

| Type | Name | Value | Why |
|------|------|-------|-----|
| `TXT` | `@` | `reeferdude.com` | Ownership claim, visible to any lookup |
| `TXT` | `@` | `v=spf1 include:_spf.google.com ~all` | Email authority |
| `TXT` | `_dmarc` | `v=DMARC1; p=quarantine; rua=mailto:holler@reeferdude.com` | Anti-spoofing |
| `TXT` | `google._domainkey` | `v=DKIM1; k=rsa; p=YOUR_KEY` | Mail signing |
| `TXT` | `@` | `google-site-verification=TOKEN` | Search Console |
| `TXT` | `@` | `MS=msTOKEN` | Bing Webmaster |
| `TXT` | `@` | `facebook-domain-verification=TOKEN` | Meta Business |
| `CNAME` | `www` | `potgrowhub.store` | Forward www to the mirror |
| `ALIAS`/`A` | `@` | `75.2.60.5` | Root forward / host |
| `CAA` | `@` | `0 issue "letsencrypt.org"` | Free SSL lock |
| `MX` | `@` | your mail provider | Mail delivery |
| `SRV`/`NS` | as issued | your nameservers | Delegation record |

**Forwarding `reeferdude.com → potgrowhub.store`:** use registrar-level **301 forwarding** (keeps the
domain yours, passes SEO value), or host-level redirect rules. Do **not** mask the redirect — masking
breaks SEO and hides the address bar.

## 17. 🗃 Data Model

| Entity | Key fields | Access rule |
|--------|-----------|-------------|
| `Product` | name, category, price, eco notes, affiliate link, tags, art | Public read · admin writes |
| `Testimonial` | author, rating, quote, approved, featured | Public read & submit · admin edits |
| `Consultation` | name, email, phone, topic, budget, timing, status | Public submit · admin only read |
| `Blueprint` | title, contact, space type, footprint, budget, goals | Public submit · admin only read |
| `CrewMember` | name, email, vibe, experience, interests, goals | Public submit · admin only read |

## 18. 🔌 Integrations

| Integration | Used for |
|-------------|----------|
| Base44 `InvokeLLM` | AI budtender chat, strain profile forge |
| Base44 entities | Products, testimonials, consults, blueprints, crew |
| Base44 analytics | Funnel events: page views, form submits, AI chats, gear clicks |
| Google Analytics 4 | Traffic and conversion reporting |
| Google Tag Manager | Tag deployment without code churn |
| Google Search Console | Indexing and query visibility |
| Google Business Profile | Local map presence and reviews |
| Google AdSense | Display monetization |
| Plausible / Umami / Matomo CE | Privacy-first open-source analytics |
| Amazon Associates / Etsy / ShareASale / Impact | Affiliate revenue |
| Prebid.js | Open-source header bidding |

## 19. 🔒 Security & Privacy

- No passwords, no accounts: nothing to leak but a name and an email you chose to give us.
- Consultation and crew records are **admin-only on read** — visitors can write, never read back.
- Private uploads use signed, expiring links; nothing sensitive is public.
- Security header posture: no-sniff, strict referrer, frame-ancestors, permissions policy.
- Full disclosure policy in `security.txt`; 72-hour reply pledge, safe harbour for good-faith research.
- No selling, renting or trading personal data. Ever.

## 20. 🗺 Roadmap

- [ ] Real affiliate IDs and AdSense publisher ID in `index.html` + `ads.txt`
- [ ] Generated icon set in `/icons/`, OG art in `/social/`
- [ ] Video walkthroughs of every blueprint
- [ ] Strain vault: save, share and vote on community-built cultivars
- [ ] AR try-on for glassware at real table scale
- [ ] Supplier partner portal on the mirror domain

## 📜 License

All rights reserved, **Reefer Dude**, 2026. Personal use of the tools is free. Copying the brand, the
copy or the design system for a competing site is not.

## 📮 Contact

**Holler at the OGs** — `holler@reeferdude.com` · `+1-000-000-0000` · Mon–Sun 8:00–22:00
21+ only. No cannabis flower, THC product or licensed good is sold on this site.

A small-team, static website starter for cannabis culture, cultivation ideas, and lawful non-cannabis projects. This project does not sell cannabis and does not include active payment, advertising, analytics, AI, AR/VR, shipping, booking, or supplier integrations.

## 🚀 Local preview
1. Install Node.js.
2. Open PowerShell in this folder.
3. Run `npm start`.
4. Visit `http://localhost:8080`.

No npm packages are required. `npm run check` checks the local preview server syntax.

## 📁 Project map
- `index.html` — accessible home page, visible FAQ, age prompt, and truthful structured data.
- `styles.css` — responsive visual system.
- `app.js` — age prompt and service-worker registration; no tracking.
- `manifest.json`, `icon.svg`, `sw.js` — installable-site metadata and basic offline caching.
- `pages/` — concept pages, not active products or services.
- `robots.txt`, `sitemap.xml` — crawler guidance and public-page list.
- `SEO.md`, `AEO.md`, `META.md`, `SEO.txt`, `AEO.txt` — practical publishing checklists.
- `security.txt`, `humans.txt`, `llm.txt` — project and contact metadata.

## 🌐 Domain and ownership
Domain ownership and DNS are controlled by the registrar, not these files. Add only the exact TXT/CNAME/A/AAAA records supplied by your registrar, hosting provider, or verification service. Do not invent verification tokens. Configure a registrar-side permanent redirect from `reeferdude.com` to `https://potgrowhub.store/` if that is your chosen canonical destination. Keep a real hosted site on the destination domain.

A redirect does not make private registrant details public and does not replace DNS-based verification.

## 🔎 Search and analytics
The site has no Google Analytics, Tag Manager, Search Console verification token, or AdSense code. Add these only after creating and controlling the corresponding accounts. Use privacy-respecting consent and disclose any tracking before enabling non-essential scripts.

## 🔐 Launch checklist
- Replace the sample contact email with one you control.
- Write real privacy, terms, accessibility, and jurisdiction-specific age information before launch.
- Confirm every page is accurate and remove unfinished pages.
- Add only genuine, visible FAQ or organization details to structured data.
- Set DNS, HTTPS hosting, redirects, and verification records with your registrar/host.
- Submit the sitemap to the search service you actually use.
- Populate `ads.txt` only with seller records issued for accounts you control.
- Test keyboard navigation, mobile layout, broken links, and page speed.

## 🎨 Brand tokens
Forest `#25391f` · Leaf `#496d39` · Moss `#a9bd76` · Cream `#f5f0df` · Clay `#c16b3c` · Sky `#b8d5d2`. Voice: plain-spoken, hopeful, neighborly, hardworking, transparent, and never pushy.
