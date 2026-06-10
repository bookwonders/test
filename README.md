# ColorBurst Studio v2

A professional dark-themed SVG coloring app built with Next.js 14.

## Stack
- **Next.js 14** (App Router)
- **React 18**
- **Syne** typeface (Google Fonts)
- Zero external UI dependencies

## Features
- 6 hand-crafted SVG illustrations
- 36-colour professional palette
- Click-to-fill with satisfying pop sound
- Undo history, Reset canvas
- Zoom 50%–175%
- Recent colours panel
- Scene switcher (switch illustration without leaving studio)
- Save artwork as 800×800 PNG download
- Fully responsive

## Local development

```bash
npm install
npm run dev
# → http://localhost:3000
```

## Deploy to Vercel

### Option A — CLI
```bash
npm i -g vercel
vercel
```

### Option B — GitHub → Vercel dashboard
1. Push this repo to GitHub
2. Go to vercel.com/new → Import the repo
3. Leave all settings as default (Next.js auto-detected)
4. Click **Deploy**

No environment variables required.

## Project structure

```
colorburst-pro/
├── app/
│   ├── layout.jsx        # Root layout — Syne font + metadata
│   ├── page.jsx          # Server entry point
│   ├── ColoringApp.jsx   # Full client component ("use client")
│   └── globals.css       # CSS reset + design tokens
├── public/
│   └── favicon.svg       # Brand favicon
├── next.config.js
└── package.json
```
