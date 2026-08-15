# autheo.dev DevHub — UI

**Green Lightning Theme** | Local-first Serverless Dashboard

This is the standalone Next.js UI for autheo.dev DevHub with the new **green lightning developer theme**.

## 🎨 Theme Highlights

- **Light Mode:** Sage green backgrounds, deep green text, pure white cards
- **Dark Mode:** Deep green-black, bright neon green accents ⚡
- **Accent Green:** #22C55E → #6DF55E (automatically switches by theme)
- **Interactive Elements:** Green scrollbars, links, buttons
- **Focus:** Automating developer workflows, simplicity, edge compute

## Quick Start

### Local Development

```bash
npm install
npm run dev
```

Visit `http://localhost:3000` to see the green lightning theme!

### Environment Setup

Copy `.env.example` to `.env.local`:

```bash
cp .env.example .env.local
```

## Deploy to Vercel

### Via Vercel CLI

```bash
npm i -g vercel
vercel
```

### Via GitHub

1. Push this to GitHub
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import from GitHub
4. Click Deploy!

## Tech Stack

- Next.js 16 — React framework
- TypeScript — Type-safe code
- Tailwind CSS — Green theme styling
- Tremor — Charts & components
- Clerk — Authentication (optional)

## File Structure

```
.
├── app/                    # Next.js app router with green theme
├── components/             # Reusable React components
├── public/                 # Static assets
├── tailwind.config.ts      # Tailwind + green color config
├── next.config.mjs
├── package.json
├── vercel.json             # Vercel deployment config
└── README.md
```

## License

Open BSL — See parent repo
