# AI Intel

**AI × Accounting & Finance Intelligence**
*"All the intelligence that's fit to print."*

A daily AI-generated newspaper for accounting and finance professionals — covering artificial intelligence in tax, audit, financial services, and the tools shaping the profession. Published as a static GitHub Pages site.

---

## What This Is

AI Intel is a personal daily briefing produced using Claude (Anthropic) as an editorial intelligence engine. Each edition is a fully designed, broadsheet-style HTML newspaper covering:

- **Above the Fold** — One lead story with editorial weight
- **Today's Headlines** — 3–5 intelligence dispatches with practitioner and founder angles
- **Tool Spotlight** — One AI tool reviewed in depth for CPA firm use cases
- **The Agentic Corner** — Strategic analysis for builders in the accounting/AI space
- **Regulatory Radar** — IRS, AICPA, PCAOB, SEC, and state AI guidance
- **Resource of the Day** — One worth-your-time article, paper, or report
- **Editor's Dispatch** — 2–3 sharp analytical observations

**Audience:** CPAs, EAs, tax professionals, firm partners, and founders building AI products for the accounting and finance vertical.

**Beat:** Artificial intelligence in accounting, tax, audit, finance, and financial services.

---

## Live Site

**https://unclejim7.github.io/ai-intel**

| URL | Content |
|---|---|
| `/` or `/index.html` | Today's edition |
| `/YYYY-MM-DD.html` | Permanent dated archive copy |
| `/archive.html` | Full archive index |

---

## How It's Generated

Each edition is triggered by typing **`run AI`** in a Claude conversation configured with the AI Intel system prompt. Claude then:

1. Searches the web for the last 7 days of relevant news across accounting, tax, AI, and finance
2. Generates a complete HTML edition in broadsheet newspaper style
3. Outputs three files: `index.html`, `YYYY-MM-DD.html`, and an updated `archive.html`

Files are manually uploaded to this repository after each run. GitHub Pages serves them immediately.

**No build step. No framework. No dependencies beyond Google Fonts.** Pure HTML/CSS.

---

## Repository Structure

```
/
├── index.html          ← Today's edition (overwritten each run)
├── archive.html        ← Edition archive index (updated each run)
├── 2026-05-28.html     ← Edition No. 1
├── 2026-05-29.html     ← Edition No. 2
└── README.md
```

Each dated file is a permanent, standalone HTML page. The archive page links to all of them.

---

## Edition Navigation

Every edition includes a nav bar with:
- **← Previous date** — links to the prior edition
- **📁 Archive** — always links to `archive.html`
- **Next date →** — shown as disabled until the next edition is published; the prior edition's file is updated on the next run to activate the forward link

---

## Publishing Workflow

1. Open Claude with the AI Intel system prompt active
2. Type `run AI`
3. Wait for Claude to complete web searches and generate all three files
4. Download the three output files
5. Upload to this repository (replacing `index.html` and `archive.html`; adding the new dated file)
6. GitHub Pages publishes automatically — no build required

---

## Design

The newspaper uses a deliberate broadsheet aesthetic:

- **Typography:** Playfair Display (headlines), Libre Baskerville (body), IBM Plex Mono (labels/metadata)
- **Color:** Aged newsprint palette (`#f5f0e8` paper, `#0f0e0c` ink, `#8b1a1a` accent)
- **Archive page:** Inverted dark mode for contrast with the editorial pages
- **Layout:** Single-column broadsheet with two-column tool/agentic sections; mobile-responsive

---

## Editorial Standards

- **Web search on every run.** No edition relies on training data for current headlines.
- **No fabricated links or tools.** If a section has nothing material, it says so.
- **Practitioner-first framing.** Every item connects to what a CPA firm does with it.
- **Founder-aware.** Secondary lens on every item for someone building an AI product for tax/accounting.
- **All editions AI-generated.** Verify before acting professionally.

---

## Sources Monitored

*Journal of Accountancy · CPA Practice Advisor · Accounting Today · Thomson Reuters Blog · Bloomberg Tax · Tax Notes · AICPA.org · IRS.gov · TechCrunch · Anthropic / OpenAI / Google / Microsoft blogs · VentureBeat AI · The Information · Bloomberg Technology*

---

*AI Intel. Est. 2025. All editions AI-generated. Verify before acting professionally.*
