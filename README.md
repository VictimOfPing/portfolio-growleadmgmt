# GrowLeadMGMT

![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=nextdotjs)
![React](https://img.shields.io/badge/React-19-149ECA?style=for-the-badge&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.6-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-11-0055FF?style=for-the-badge&logo=framer&logoColor=white)

GrowLeadMGMT needed a credible digital presence for a specialized casino, gaming, and betting influencer marketing agency.
I built a bilingual, SEO-ready Next.js website that turns the agency's talent network, campaign process, and proof of performance into a structured lead-generation experience.

**Live site:** [growleadmgmt.com](https://growleadmgmt.com)

## Screenshots

Real campaign insight assets are included in the repository and surfaced inside the case studies page.

<p>
  <img src="public/case_histories/IMG-20251013-WA0013.jpg" alt="GrowLeadMGMT campaign insight screenshot" width="260" />
  <img src="public/case_histories/IMG-20251013-WA0014.jpg" alt="GrowLeadMGMT audience insight screenshot" width="260" />
  <img src="public/case_histories/IMG-20251013-WA0020.jpg" alt="GrowLeadMGMT story performance screenshot" width="260" />
</p>

## Tech Stack

| Layer | Tools |
| --- | --- |
| Frontend | ![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=nextdotjs) ![React](https://img.shields.io/badge/React-19-149ECA?logo=react&logoColor=white) |
| Language | ![TypeScript](https://img.shields.io/badge/TypeScript-5.6-3178C6?logo=typescript&logoColor=white) |
| Styling | ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-38B2AC?logo=tailwindcss&logoColor=white) |
| Motion | ![Framer Motion](https://img.shields.io/badge/Framer_Motion-11-0055FF?logo=framer&logoColor=white) |
| SEO | Next Metadata API, custom SEO component, sitemap, robots, JSON-LD organization schema |

## Features

- Bilingual content system for Italian and English using a shared translation dictionary and language context.
- Multi-page App Router structure for Home, Services, Case Studies, About, Contact, and custom 404 routes.
- Case study section with real campaign metrics for Slott, Herospin, Tipster Bover, and AmonBet.
- Talent showcase with optimized `next/image` rendering and approved remote image domains.
- SEO foundation with canonical URLs, Open Graph metadata, Twitter cards, sitemap, robots rules, and JSON-LD structured data.

## Project Structure

The project is structured as a focused marketing site with a small component layer and centralized content.

```text
app/
  layout.tsx             Global metadata, providers, JSON-LD injection
  page.tsx               Homepage composition
  services/page.tsx      Service offering and campaign process
  case-studies/page.tsx  Campaign metrics, insight gallery, modal viewer
  about/page.tsx         Agency positioning, values, expertise
  contact/page.tsx       Lead form and contact channels
components/
  navbar.tsx             Responsive navigation and language controls
  hero-section.tsx       Primary positioning section
  influencers-showcase.tsx
  footer.tsx
  seo.tsx                Per-page SEO tags
contexts/
  language-context.tsx   Runtime language state
lib/
  translations.ts        English and Italian site copy, metrics, case data
public/
  logo.svg
  case_histories/        Campaign screenshots and performance media
```

## Results and Impact

- Built the agency's public website for `growleadmgmt.com`, replacing an offline or underdeveloped brand presence with a complete conversion path.
- Presented a network of 100+ talent partners, 200+ completed campaigns, and 10M+ generated impressions directly in the site experience.
- Turned private campaign proof into portfolio-grade case studies, including average click results such as 1,767 for Herospin, 1,675 for Tipster Bover, and 1,241 for Slott.
- Added dedicated contact paths for business inquiries, partnerships, and talent acquisition.

## Local Development

```bash
npm install
npm run dev
```

Production check:

```bash
npm run build
npm start
```

## Contact and Portfolio

- Live project: [growleadmgmt.com](https://growleadmgmt.com)
- General inquiries: [info@growleadmgmt.com](mailto:info@growleadmgmt.com)
- Partnerships: [partnerships@growleadmgmt.com](mailto:partnerships@growleadmgmt.com)
- Talent applications: [talent@growleadmgmt.com](mailto:talent@growleadmgmt.com)

