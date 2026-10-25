# Kisii Dreadlocks Parlor

A premium salon and beauty website for a dreadlocks-focused business in Kisii Town, Kenya. The project is designed as a modern landing page for showcasing services, contact details, gallery, location information, and direct WhatsApp booking.

## Overview

This repository contains a single-page website for a professional dreadlocks parlor with:

- Hero section and brand messaging
- About/founder section
- Service cards with pricing
- Work gallery and lightbox
- Opening hours and location details
- WhatsApp and phone call CTAs
- Instagram/TikTok links
- PWA install prompt support
- SEO metadata and business schema markup

## Live site

The project is configured for Netlify deployment and is intended for a business-facing landing page experience.

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Vite
- Netlify
- Progressive Web App (PWA) support

## Project Structure

```text
.
├── index.html              # Main landing page markup
├── style.css               # Global styling and responsive design
├── script.js               # Interactions, gallery logic, UI behavior
├── vite.config.ts          # Vite configuration
├── tsconfig.json           # TypeScript config
├── package.json            # Scripts and dependencies
├── netlify.toml            # Netlify build configuration
├── public/
│   ├── logo.png            # App logo
│   ├── manifest.json       # PWA manifest
│   ├── sw.js               # Service worker
│   ├── robots..txt         # Bot directives
│   ├── sitemap.xml         # Sitemap
│   └── images/             # Business and gallery assets
├── .gitignore
├── package-lock.json
└── README.md
