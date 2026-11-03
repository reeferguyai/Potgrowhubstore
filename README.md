# ReeferDude / PotGrowHub

A branded cannabis culture, education, grow guidance, and storefront project built as a static, multi-page web experience with Vite-based local tooling. This repository contains the public-facing site structure, product/education content, SEO metadata, legal pages, and supporting static assets used to present the brand and storefront experience.

> Important: This README reflects the current repository state. The project contains a large set of marketing, SEO, legal, and storefront content pages, but it should not be read as a fully implemented production commerce backend or a complete AI commerce platform unless those features are separately validated in deployment.

## Project status

This repository currently appears to be a front-end and content site project with:

- static HTML pages for home, about, shop, product pages, legal sections, and support content
- large catalog/content directories for products, strains, legal guidance, and educational material
- Vite-based local development tooling via `package.json`
- SEO and verification assets such as `robots.txt`, `sitemap.xml`, `manifest.json`, `ads.txt`, `llms.txt`, and Google/Bing verification metadata
- a marketing and brand system built around PotGrowHub and ReeferDude branding

This is best described as a static web storefront/content platform in active expansion, rather than a fully mature headless commerce stack or fully automated AI commerce engine.

## What is in this repo

The repository includes:

- root site metadata and SEO files
- static HTML pages for public sections
- product catalog directories and storefront routes
- legal/compliance pages for age, privacy, terms, accessibility, and jurisdictional guidance
- CSS and JS assets for styling and front-end behavior
- Vite tooling for development and build validation

## Tech stack

- HTML / CSS / JavaScript for static site content and interactivity
- Vite for local development and build pipeline
- React and related ecosystem packages in `package.json` (present in the front-end tooling)
- Search engine and analytics integrations embedded in site HTML metadata
- static hosting-friendly architecture for SEO and content files

## Repository structure

```text
.
├── README.md
├── package.json
├── index.html
├── style.css
├── script.js
├── public/ (or root-level metadata/SEO files)
├── css/
├── js/
├── assets/
├── about/
├── shop/
├── products/
├── strain-library/
├── strain-* /
├── legal-*/
├── privacy/
├── terms/
├── accessibility/
├── contact/
├── faq/
├── blog/
├── marketplace/
├── ai-budtender/
├── design-studio/
├── consultation/
├── membership/
├── cart/
├── checkout/
├── ads.txt
├── robots.txt
├── sitemap.xml
├── manifest.json
├── sw.js
├── llms.txt
├── humans.txt
├── security.txt
├── SEO.md
├── AEO.txt
├── Meta.md
├── Branding-bible.md
└── many content directories for legal, strain, terpene, and product guidance
```

## Runs locally

```bash
npm install
npm run dev
```

Then open the local Vite URL shown in the terminal.

### Useful scripts

```bash
npm run build
npm run preview
npm run lint
npm run typecheck
npm run verify
```

## Current implementation reality

The repo contains the following kinds of functionality and content as evidenced by the project files:

- branded home and landing pages
- product/category and store navigation pages
- education and guidance pages for cannabis culture and cultivation topics
- SEO and schema markup
- legal/privacy/accessibility pages
- analytics and verification code injection
- static front-end styles and scripts

The repo does not clearly show a complete production-grade implementation of all the more ambitious claims in some marketing materials, including:

- complete payment processing flow
- shipping fulfillment integration
- full supplier management portal
- live AI backend integration for every claimed feature
- robust checkout or inventory system
- production deployment configuration for all domains/services mentioned in the docs

Use the repo contents as the source of truth. Marketing language should be treated as product intent or roadmap unless supported by actual working code and deployment configuration.

## Brand and domain notes

The repository references multiple brand names and domain variants, including:

- ReeferDude
- PotGrowHub
- PotGrowHub.store
- reeferdude.com

This appears to be a multi-brand marketing structure. Before public launch or domain claims, confirm the canonical brand and canonical domain to avoid ambiguity between the storefront, brand identity, and legal/compliance messaging.

## Legal and compliance posture

This project includes age-gating, legal guidance, and educational content patterns. However, this repository alone does not constitute legal compliance advice.

Key points to validate before production:

- actual age restrictions and gating implementation in production
- local legal requirements for the jurisdictions you serve
- privacy and cookie consent compliance
- accessibility conformance claims
- claims around product and shipping eligibility
- any regulatory review for cannabis-adjacent content and commerce

The site includes disclaimers indicating that no cannabis is sold directly on the site, and that age restrictions apply. Confirm these statements remain accurate in the deployed environment.

## SEO and site metadata

The site includes many public-facing optimization and verification files, including:

- `robots.txt`
- `sitemap.xml`
- `manifest.json`
- `ads.txt`
- `llms.txt`
- `security.txt`
- verification markers for Google/Bing/Meta/Ahrefs
- structured data and schema blocks in HTML

These files are present and indicate a strong marketing and search optimization focus.

## Roadmap direction

Likely future work areas visible in the repo include:

- storefront expansion and product discovery improvements
- AI budtender and assistant experiences
- education and community content growth
- design studio / strain tools / cultivation guidance experiences
- legal and accessibility review and hardening
- analytics and conversion optimization

## Contributing

Use the normal GitHub flow for contributions:

1. fork the repo or create a branch
2. make focused changes
3. run validation commands
4. open a pull request with a clear explanation

## License

This repository does not currently appear to include a standard, explicit open-source license file. Before reuse, redistribution, or public commercial adoption, confirm the legal license and usage rights in writing.

## Contact

Repository owner: `reeferguyai`
Project: `Potgrowhubstore`

Use the repository issues and pull requests for code collaboration. For business and brand questions, confirm the currently authorized public contact routes in the live site.

## Summary

This repository is a brand-forward, content-rich storefront and marketing site with a lot of product and educational structure, plus strong SEO and compliance scaffolding. It is not a simple one-page landing page; it is a substantial static web project with significant content and branding work behind it.

The most accurate framing is:

- a multi-page storefront and education platform
- built around marketing, SEO, and brand architecture
- supported by Vite tooling and static assets
- still requiring clear validation of production claims, feature completeness, legal compliance, and deployment reality

