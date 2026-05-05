# Profile README design — 2026-05-05

> Design document for the rewrite of `CreatmanCEO/CreatmanCEO` profile README. Approved by Nick on 2026-05-05.

## Three audiences, one document

The profile README must work simultaneously for three audiences without compromising any of them:

1. **OSS audience** — followers, star-givers, contributors. Cares about: substance, original voice, project that solves a real itch, helper-pattern.
2. **Architectural / technical-lead partners** — looking for someone who can lead a non-trivial system end-to-end. Cares about: depth, cross-stack range, completed real-world delivery.
3. **HR / CTO at international companies** — looking to hire. Cares about: engineering discipline, English-fluent communication, relocation readiness, anti-vibecoder credibility.

The same README serves all three because the unicorn positioning (geologist → engineer) is the **anti-vibecoder credential** for HR/CTO, the **systems-thinking signal** for partners, and the **interesting-personality magnet** for OSS audience.

## Hero — single approved formulation

```markdown
# Hi, I'm Nick.

> **Field geologist since 2007. Software engineer since 2020.**
>
> *Same craft, different terrain. Mapping the unseen on the ground; building what's missing on screen.*
```

Date-based wording (`since 2007 / since 2020`) instead of fragile year counts. Hero carries the unicorn pairing (geologist + engineer) and the systems-thinking craft framing as **one block** — no commodity skill list.

## Section order

| # | Block | Purpose | Approx. length |
|---|---|---|---|
| 1 | EN/RU language toggle | English default · Russian collapsible | 1 line |
| 2 | Hero | Unicorn positioning | 2 lines |
| 3 | Recognised-by row | Evidence in first screen — Habr top-5, Graphify v5.0 roadmap, App Store, dev.to, 56 stars | 1 line of badges / icons |
| 4 | "How I work" — 2 sentences | Helper-pattern + substance-over-hype, woven, no manifesto | 2-3 sentences |
| 5 | 🌍 Open-source · Featured | 7 cards | grid |
| 6 | 💼 Commercial / commercial-intent | 6 hero cards + compact "More commercial work" list | grid + list |
| 7 | ❤️ Personal · non-commercial | 1 hero card (diabot) + "Other personal projects" compact list | 1 card + list |
| 8 | 📚 More projects | Compact roll-up of remaining repos (public + key private) | table |
| 9 | 📊 GitHub stats | Single widget — top languages | 1 row |
| 10 | 📫 Let's talk | 3 explicit "Open to" lines + contacts | 6-8 lines |
| 11 | 🇷🇺 Collapsible Russian mirror | Same content, condensed, in Russian | `<details>` block |

## "How I work" — exact sentences

```
I build tools I needed first, then ship to others — diabot for a sibling with type 1
diabetes, security-scanner after a friend's compromised phone, claude-code-anti-
regression-setup because my own refactors kept breaking. Engineering as craft,
not as content — I don't buy attention. I build things substantial enough that the
right people find them on their own.
```

Helper-pattern (first sentence with three concrete examples) + substance-over-hype (second/third sentences). Non-manifesto length.

## Featured Open-source — 7 cards

In order:

1. **`hydrowatch`** — Theis-equation-based groundwater monitoring · 7 MCP-style tools · LiteLLM router · 154 tests · the gold-standard README that anchors the rest of the portfolio.
2. **`claude-code-antiregression-setup`** ⭐11 — Featured on Habr top-5 (20K reads, Технотекст 8 entry).
3. **`webtest-orch`** — npm@beta · CI matrix Linux/macOS/Windows · 113 tests.
4. **`claude-statusline`** ⭐5 — Featured on Habr (9.3K reads).
5. **`ai-context-hierarchy`** ⭐3 — Featured in Graphify v5.0 roadmap (external validation by upstream maintainer).
6. **`notebooklm-claude-workflows`** ⭐3 — 7 slash commands · 41K-message Telegram production test.
7. **🔨 `cc-janitor`** — Phase 1 MVP — TUI/CLI for Claude Code environment hygiene (sessions / permissions / context). MIT.

## Featured Commercial — 6 hero cards + compact list

**Hero (6):**

1. **AviaWallet** — Shipped to App Store · Flutter · led from 0 to first release; current team maintains a UI redesign on the same architecture. *Public showcase repo coming soon.*
2. **Sakhalin-Market** — Cross-platform marketplace + admin · designed solo from 0 to production with one in-house helper · `ffSakhalin-MarketClient` + `ffSakhMrktAdm`.
3. **`ghost-showcase`** — Phase 1, **open to investment / acquisition** — invisible AI assistant for Windows.
4. **`lingua-companion`** — **Private beta, open to partnership** — voice-first English tutor for Russian-speaking IT pros · 91 backend tests.
5. **`security-scanner`** — `@secure_scanbot` LIVE · Phase 2 self-hosted Docker open-sourcing.
6. **`club-sbor.ru`** — In production since 2024 · Bubble.io · the project that pushed Nick from no-code to real code/frameworks.

**More commercial work** (compact list, no individual cards):
`hebrew_doc_translator` · `joy-vision-calculator` (Bitrix24 CRM) · `cian-parser-showcase` · `rentscout` · `vpn-commercial-bot` (private)

## Featured Personal — 1 hero card + compact list

**Hero:** `diabot` — type 1 diabetes nutrition · for friends and family · PolyForm Noncommercial · *I solve mine, then ship to others.*

**Other personal projects:** `portfolio` (creatman.site) · `smart-link-collector` · `work-assistant` (private) · `vpn-key-bot` (private).

## Active-development indicator

Not a separate "Currently building" section. Instead, a **🔨 badge embedded in the relevant cards** in the existing buckets:

- `cc-janitor` — 🔨 Phase 1 MVP (in Open-source bucket)
- `ghost-showcase` — 🔨 Phase 1 (in Commercial bucket, with "open to investment" tag)
- `lingua-companion` — 🔨 v1.0 beta (in Commercial bucket, with "open to partnership" tag)

## More projects (compact roll-up)

```
accu · datn · notion-knowledge-assistant · CreatmanCEO.github.io ·
telegram-form-worker · CREATMAN-Life-Hub (private) ·
diabot-vps · scanner-vps · vpn-commercial-vps · vpn-lab-reference (read-only)
```

Public + key private repos with explicit `private` tag.

## "Let's talk" — exact wording

```
**Open to:**
- 🌍 Senior engineering / staff-level roles — remote, open to relocation outside Russia
- 🤝 Architectural / technical-lead partnerships — for select product ventures
- 💬 Investment / acquisition discussions — for GHOST and lingua-companion in particular

**Reach:** Email · Telegram · LinkedIn · creatman.site
```

## What is removed in this rewrite

1. **Internal strategy documents from the public repo** — `CAREER_ANALYSIS.md`, `GITHUB_GROWTH_STRATEGY.md`, `REPOSITORY_TOPICS.md`. Three files that should never have been public. Removed in the same PR. Content preserved locally / in private memory if needed.
2. **n8n mentions** in description and tech-stack — no longer represents current work (per `feedback_no_n8n.md` memory).
3. **Outdated featured projects** — generic `joy-vision-calculator` / `crypto-wallet-mvp` / `notion-transfer-bot` no longer in Featured (they live in More projects table).
4. **Generic skill-list hero** ("Full-Stack Developer | Automation Engineer | AI Integration Specialist") — replaced with the unicorn pairing.
5. **"Open to: Full-Stack Developer roles, Automation Engineer positions, AI Integration projects"** — too generic. Replaced with three precise audience-targeted "Open to" lines.

## What is added in this rewrite

1. Unicorn-pairing hero (`Field geologist since 2007. Software engineer since 2020.`)
2. Recognised-by evidence row in first screen
3. "How I work" — helper-pattern + substance-over-hype, two sentences
4. Three explicit buckets (Open-source / Commercial / Personal) instead of one undifferentiated "Featured Projects" list
5. 🔨 active-development badges embedded in relevant cards
6. cc-janitor placeholder card with link to GitHub repo
7. Sakhalin-Market and AviaWallet (with showcase-coming-soon note) explicitly featured in Commercial — both real shipped products previously underweighted in the README
8. hydrowatch as the first OSS card — was missing from the previous README despite being the gold-standard project

## Adjacent operations (in the same PR)

These are not README-content but happen alongside the rewrite:

1. **Delete** `CAREER_ANALYSIS.md`, `GITHUB_GROWTH_STRATEGY.md`, `REPOSITORY_TOPICS.md` from the public repo.
2. **Update GitHub `description`** field on the profile — remove "n8n", reflect current positioning.
3. **Fill the GitHub `bio`** field (separate from description) — currently `null`.
4. **Pin 6 repos** to replace the current pinned set:
   - Recommended pins: `claude-code-antiregression-setup`, `hydrowatch`, `webtest-orch`, `ghost-showcase`, `security-scanner`, `lingua-companion` (or `cc-janitor` once it has Phase 1 MVP shipped).

## Out of scope for this PR

- **AviaWallet-showcase repo creation** — separate follow-up task.
- **Russian Habr article writing** for any of the projects — separate content tasks.
- **Default branch renames** (`master → main`) for `diabot` and `security-scanner` — deferred.
- **Removing 3 internal docs from git history** (with `git filter-repo` / BFG) — only deleting from current state. The history-rewrite is a separate consideration if leak severity warrants it.

## Approval log

- **2026-05-05** — Hero formulation approved by Nick (D3-derived, then α+δ blend, then date-based final).
- **2026-05-05** — Body structure approved (philosophy + 2 buckets pattern).
- **2026-05-05** — Tier-list approved with corrections: hydrowatch added to OSS Featured (was missed), Sakhalin-Market added to Commercial Featured, cc-janitor recognised as real (not vapor) and added to OSS Featured with 🔨 badge.
- **2026-05-05** — Active-development badge pattern (🔨 embedded in cards) approved over a separate "Currently Building" section.
