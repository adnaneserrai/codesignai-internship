# Website

[← Back](../README.md)

Live: **[codesignai.ca](https://codesignai.ca)**

The site presents CoDesignAI in English and French.

## Stack

- **React 19**, **TypeScript**, **Vite 6**, React Router: four pages per
  language (home, about, demo, contact), plus legal pages and an error page.
- **three.js** for the 3D journey on the home page, loaded on that page only.
- **Lenis** for smooth scrolling. A single animation loop drives the scroll
  reveals and text effects, and `prefers-reduced-motion` is respected.
- **Plain CSS** in a single file, no framework. Fonts are self-hosted.
- Overview and demo videos with English and French subtitles (WebVTT).
- A contact form on a static site, through a third-party service. If the
  service is not configured, the site offers to write by email instead.

## Approach

- Every page exists in both languages, and each one links to its
  counterpart in the other language.
- Visual and content choices were validated step by step with the company.
  Each step was checked with screenshots at several widths (mobile, tablet,
  desktop) and mobile Lighthouse audits.
- Privacy policy and terms of use written for the site.
- Static hosting on Render, with fallback configurations for other hosts.
