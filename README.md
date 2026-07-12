# Tayo Na — Landing Page

Marketing landing page for [tayona.app](https://tayona.app), built with Astro and deployed to Cloudflare Pages at [travel.tayona.app](https://travel.tayona.app).

## Stack

- **Framework:** Astro (static)
- **Deploy:** Cloudflare Pages (auto-deploy on push to `main`)
- **Live URL:** `travel.tayona.app`

## Project Structure

```text
/
├── public/              # Static assets (images, fonts, favicon)
├── src/
│   ├── components/      # Page sections (Hero, Features, HowItWorks, etc.)
│   ├── layouts/         # Base HTML layout
│   ├── pages/           # Routes (index.astro, privacy.astro)
│   └── styles/          # Global CSS variables and base styles
└── package.json
```

## Commands

| Command           | Action                                      |
| :---------------- | :------------------------------------------ |
| `npm install`     | Install dependencies                        |
| `npm run dev`     | Start local dev server at `localhost:4321`  |
| `npm run build`   | Build production site to `./dist/`          |
| `npm run preview` | Preview build locally before deploying      |

## Related

- **App repo:** `~/code_repo/tayona` — the Tayo Na PWA
- **App URL:** `tayona.app`
