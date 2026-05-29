# 📰 AI Intel — AI × Accounting & Finance Intelligence

> *"All the intelligence that's fit to print."*

A daily AI-powered briefing publication for accounting and finance professionals, delivered in the aesthetic of a classic financial newspaper. Built on Claude + web search. Run it once a day. Stay ahead of the profession.

---

## What It Is

**AI Intel** is a Claude Project + React application that produces a fully formatted, newspaper-style daily intelligence brief covering:

- AI tool launches and product news in accounting/tax/finance
- Agentic AI workflow developments for CPA firms
- IRS, AICPA, and regulatory guidance touching AI
- Deep-dive tool spotlights
- Curated daily resources
- Strategic takes for practitioners and founders building in this space

---

## Quick Start

### Option 1 — Claude Project (Recommended, No Code)

1. Open [claude.ai](https://claude.ai)
2. Create a new **Project**
3. Name it: `AI Intel`
4. Paste the contents of [`CLAUDE_PROJECT_INSTRUCTIONS.md`](./CLAUDE_PROJECT_INSTRUCTIONS.md) into the Project Instructions field
5. Each morning, open the project and type:

```
run AI
```

That's it. Claude runs a full web-searched brief and formats it as a newspaper edition.

---

### Option 2 — React App (Full Newspaper UI)

The `src/AIIntel.jsx` file is a standalone React component that renders the brief in a full broadsheet newspaper layout with live Claude API calls.

**Deploy to StackBlitz (fastest — no install):**

1. Go to [stackblitz.com/fork/react](https://stackblitz.com/fork/react)
2. Delete `App.jsx`
3. Create new file `App.jsx` → paste contents of `src/AIIntel.jsx`
4. Done — live in ~10 seconds

**Run locally:**

```bash
git clone https://github.com/YOUR_USERNAME/ai-intel
cd ai-intel
npm install
npm run dev
```

---

## Project Structure

```
ai-intel/
├── README.md                          # This file
├── CLAUDE_PROJECT_INSTRUCTIONS.md     # Paste into Claude Project settings
├── src/
│   └── AIIntel.jsx                # React newspaper app
├── public/
│   └── favicon.ico
├── package.json
├── vite.config.js
└── .github/
    └── workflows/
        └── ai-intel-daily.yml            # Optional: GitHub Actions daily trigger
```

---

## Trigger Word

In any Claude Project using these instructions, type:

```
run AI
```

Claude will execute the full daily brief — no preamble, no filler, straight to the edition.

---

## Design Philosophy

AI Intel is styled after classic financial broadsheets — *Financial Times*, *Wall Street Journal*, *The Economist* — with:

- Masthead with edition number and date
- Multi-column broadsheet layout
- Serif body typography (Playfair Display + EB Garamond)
- Above-the-fold lead story
- Section dividers and column rules
- Ink-on-newsprint color palette (cream, charcoal, deep navy)

---

## Stack

| Layer | Tech |
|---|---|
| AI | Claude Sonnet 4 via Anthropic API |
| Search | web_search_20250305 tool |
| Frontend | React + Tailwind-compatible CSS |
| Fonts | Playfair Display, EB Garamond (Google Fonts) |
| Deploy | StackBlitz / Vite / Vercel |

---

## License

MIT — fork it, build on it, publish your own edition.

---

*AI Intel is not affiliated with any existing publication. All briefs are AI-generated and should be independently verified before acting on them professionally.*
