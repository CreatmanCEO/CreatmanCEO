<div align="right">

🇬🇧 English · <a href="#-на-русском">🇷🇺 На русском</a>

</div>

# Hi, I'm Nick.

> **Field geologist since 2007. Software engineer since 2020.**
> **Building AI-native developer tools and agent infrastructure — MNEMO (memory), Rotator (orchestration), and a growing ecosystem of Claude Code skills.**
>
> *Same craft, different terrain. Mapping the unseen on the ground; building what's missing on screen.*

---

[![Habr · top-5 of the day · 20K reads](https://img.shields.io/badge/Habr-top--5%20of%20the%20day%20%C2%B7%2020K%20reads-77a2b6)](https://habr.com/ru/articles/1013330/)
[![Featured in Graphify v5.0 roadmap](https://img.shields.io/badge/Graphify-v5.0%20roadmap-9d6cff)](https://github.com/safishamsi/graphify/issues/425)
[![Shipped to App Store](https://img.shields.io/badge/App%20Store-AviaWallet-000?logo=apple)](https://apps.apple.com/app/aviawallet/id6754718339)
[![dev.to](https://img.shields.io/badge/dev.to-cross--published-0a0a0a?logo=devdotto)](https://dev.to/creatman)
[![Public repos · stars](https://img.shields.io/badge/repos-37%20public%20%C2%B7%20%E2%AD%90%2056%2B-yellow)](https://github.com/CreatmanCEO?tab=repositories)
![Profile views](https://komarev.com/ghpvc/?username=CreatmanCEO&color=blue&style=flat)

---

I build tools I needed first, then ship to others — `diabot` for a sibling with type 1 diabetes, `security-scanner` after a friend's compromised phone, `claude-code-antiregression-setup` because my own refactors kept breaking. Engineering as craft, not as content — I don't buy attention. I build things substantial enough that the right people find them on their own.

---

## 🌍 Open-source

### [mnemo-showcase](https://github.com/CreatmanCEO/mnemo-showcase) — Personal event graph with semantic recall for AI agents
**Python · FastAPI · pgvector · bge-m3 · MCP · 135 tests**

14K events from 6 sources, semantic recall in <500ms. 5 sprints in 12 days on a 4GB VPS. The memory layer that makes AI agents remember between sessions.

### [rotator-showcase](https://github.com/CreatmanCEO/rotator-showcase) — Single-tenant voice co-pilot + MCP peripheral for Claude Code
**Python · FastMCP · voice pipeline · skill system**

Agent runtime with bounded loops, citation-grounded recall, eval-driven skill learning. The brain that orchestrates memory, voice, and tools.

### [cc-janitor](https://github.com/CreatmanCEO/cc-janitor) — Tidy up your Claude Code environment
**Python · Textual TUI · Typer · tiktoken · MIT**

*Phase 1 MVP — in active development.* Sessions, permissions, context, hooks. The chores no one else automates, in one tool.

### [claude-code-antiregression-setup](https://github.com/CreatmanCEO/claude-code-antiregression-setup) — Stop Claude Code from breaking your projects ⭐11
**Python · Bash · Claude Code · MCP · Subagents · Hooks**

Featured on [Habr top-5 of the day · 20K reads · Технотекст 8 entry](https://habr.com/ru/articles/1013330/). The four-layer setup that survives Claude's 1M context window — `CLAUDE.md` + isolated subagents + commit-blocking hooks + glob-scoped rules.

### [webtest-orch](https://github.com/CreatmanCEO/webtest-orch) — Token-efficient e2e orchestration for Claude Code
**Python · TypeScript · Playwright · axe-core · npm**

Explore once with Playwright MCP (ARIA snapshots, not images), replay deterministically with `npx playwright test`. Bug fingerprinting + run-diff. CI matrix Linux/macOS/Windows. 113 tests. Public beta.

### [claude-statusline](https://github.com/CreatmanCEO/claude-statusline) — Smart status line for Claude Code with VPS monitoring ⭐5
**Bash · jq · cache-decoupling design**

Featured on [Habr · 9.3K reads](https://habr.com/ru/articles/1013414/). Pure bash + `jq`, no Node.js. Auto-focuses the VPS you're working with by parsing the Claude Code transcript.

### [ai-context-hierarchy](https://github.com/CreatmanCEO/ai-context-hierarchy) — Three-level context system for AI coding agents ⭐3
**Python · Claude Code · Cursor · Codex · Gemini CLI**

Featured in the [Graphify v5.0 roadmap](https://github.com/safishamsi/graphify/issues/425) — external validation by the Graphify maintainer. Stops re-explaining your codebase every session.

### [notebooklm-claude-workflows](https://github.com/CreatmanCEO/notebooklm-claude-workflows) — Seven slash-commands for NotebookLM ⭐3
**Python · Bash · MCP · NotebookLM**

41K-message Telegram production test (12 topics, 586K words, 13 NotebookLM sources, under 2 minutes). Turns multi-step NotebookLM operations into one-liners.

---

## 💼 Commercial / commercial-intent

### [AviaWallet](https://github.com/CreatmanCEO/AviaWallet-showcase) — Cross-platform crypto wallet
**Flutter · FlutterFlow · Trust Wallet Core · Firebase · App Store**

[Shipped to App Store](https://apps.apple.com/app/aviawallet/id6754718339). Led the project from 0 to first release; current team maintains a UI redesign on the same architecture. Showcase: [`AviaWallet-showcase`](https://github.com/CreatmanCEO/AviaWallet-showcase) — architecture decisions, App Store screenshots, my role and timeline.

### [Sakhalin-Market](https://github.com/CreatmanCEO/sakhalin-market-showcase) — Cross-platform marketplace + admin
**Flutter · Flutter (admin) · Firebase · in production since 2024**

Designed solo from 0 to production with one in-house helper. Cross-platform marketplace client + Flutter admin panel, including catalogue, orders, payments, and merchant tooling. Showcase: [`sakhalin-market-showcase`](https://github.com/CreatmanCEO/sakhalin-market-showcase) — architecture, customer + admin screenshots. Source repos (archived after handoff): [`ffSakhalin-MarketClient`](https://github.com/CreatmanCEO/ffSakhalin-MarketClient) · [`ffSakhMrktAdm`](https://github.com/CreatmanCEO/ffSakhMrktAdm).

### 🔨 [ghost-showcase](https://github.com/CreatmanCEO/ghost-showcase) — Invisible AI assistant for Windows · *open to investment / acquisition*
**Electron · React · TypeScript · Python · Win32 · WebSocket JSON-RPC**

Phase 1 in active development. Real-time AI assistance that stays invisible during screen recordings via `WDA_EXCLUDEFROMCAPTURE`. Multi-provider LLM (Claude, GPT, Ollama, LM Studio) + STT (Deepgram, faster-whisper) + RAG (ChromaDB) + Silero VAD. The README is structured as a fundraising / exit-prep document.

### 🔨 [lingua-companion](https://github.com/CreatmanCEO/lingua-companion) — Voice-first English tutor for Russian-speaking IT professionals · *open to partnership*
**Next.js 16 · React 19 · FastAPI · Deepgram · Groq · ElevenLabs · 91 backend tests**

Private beta. Native Russian/English code-switching support, conversational memory, three companion personalities (Alex / Sam / Morgan), four voice variants, scenario practice (Daily Stand-up, Code Review, Tech Demo, Job Interview, Sprint Planning). Demo by request.

### [security-scanner](https://github.com/CreatmanCEO/security-scanner) — Mobile threat detection through VPN traffic analysis
**Python · Suricata · Zeek · JA3 · Threat Intel APIs · Telegram**

[`@secure_scanbot`](https://t.me/secure_scanbot) live 24/7. Detects RATs, stalkerware, crypto miners, backdoors. Phase 2: open-sourcing the full self-hosted Docker stack.

### [club-sbor.ru](https://club-sbor.ru) — Football club management platform
**Bubble.io · multi-tenant architecture · auto-balancing algorithms · in production since 2023**

Web platform with auto-balancing teams algorithm and rating system. *The project that pushed me from no-code to real code/frameworks.*

**More commercial work:** [`hebrew_doc_translator`](https://github.com/CreatmanCEO/hebrew_doc_translator) · [`joy-vision-calculator`](https://github.com/CreatmanCEO/joy-vision-calculator) (Bitrix24 CRM) · [`cian-parser-showcase`](https://github.com/CreatmanCEO/cian-parser-showcase) · [`rentscout`](https://github.com/CreatmanCEO/rentscout) · `vpn-commercial-bot` *(private)*

---

## ❤️ Personal · non-commercial

### [diabot](https://github.com/CreatmanCEO/diabot) — Type 1 diabetes nutrition bot
**Python · python-telegram-bot · LiteLLM (Gemini Vision) · aiosqlite · PolyForm Noncommercial**

For friends and family. Food photo → AI carb counting → bread units → diary. *I solve mine, then ship to others.*

**Other personal projects:** [`portfolio`](https://github.com/CreatmanCEO/portfolio) (creatman.site) · [`smart-link-collector`](https://github.com/CreatmanCEO/smart-link-collector) · `work-assistant` *(private)* · `vpn-key-bot` *(private)*

---

## 📚 More projects

| Project | Note |
|---|---|
| [`accu`](https://github.com/CreatmanCEO/accu) | AI-Curated Code Universe — ecosystem for reviving undervalued open-source projects |
| [`datn`](https://github.com/CreatmanCEO/datn) | Distributed AI Trading Network — multi-agent platform |
| [`notion-knowledge-assistant`](https://github.com/CreatmanCEO/notion-knowledge-assistant) | AI-powered Notion knowledge-base bot |
| [`CreatmanCEO.github.io`](https://github.com/CreatmanCEO/CreatmanCEO.github.io) | Personal landing page |
| [`telegram-form-worker`](https://github.com/CreatmanCEO/telegram-form-worker) | Cloudflare Worker · form → Telegram |
| `CREATMAN-Life-Hub` *(private)* | Personal life-management dashboard |

---

## 🔬 Deep dives

Architecture decisions, domain expertise, and impact metrics — projects where the story matters as much as the code.

### [hydrowatch](https://github.com/CreatmanCEO/hydrowatch) — Groundwater monitoring with an LLM agent
**Python · FastAPI · Next.js · LiteLLM · MapLibre · scipy · scikit-image · 154 tests**

Real hydrogeology, not a dashboard with cosmetic icons. Theis equation interference lines, marching-squares depression cones, an agent loop calling 7 MCP-style tools. Where 17 years of field geology meets software engineering.

More case studies coming in `case-studies/`.

---

## 🛠 Tech I work in

[![My Skills](https://skillicons.dev/icons?i=python,typescript,nextjs,react,fastapi,electron,flutter,nodejs,postgres,redis,docker,linux,bash,vscode,git,github,vercel,cloudflare&theme=dark)](https://skillicons.dev)

**Backend:** Python 3.11+ · FastAPI · WebSocket · Celery · LiteLLM · aiosqlite · pgvector
**Frontend:** Next.js · React 19 · TypeScript · Tailwind · shadcn/ui · Zustand
**Mobile:** Flutter (App Store-shipped) · React Native
**Desktop:** Electron + Win32 native (`koffi`)
**AI / ML:** Claude · Gemini · Groq · DeepSeek · Ollama · Deepgram · faster-whisper · ElevenLabs · ChromaDB · Silero VAD · pgvector · bge-m3 · MCP (Model Context Protocol)
**DevOps:** Docker · systemd · nginx · WireGuard · Tailscale · GitHub Actions · Coolify · 4 production VPS

[![Followers](https://img.shields.io/github/followers/CreatmanCEO?style=flat&label=followers&color=blue)](https://github.com/CreatmanCEO)
[![Stars](https://img.shields.io/github/stars/CreatmanCEO?style=flat&label=stars&affiliations=OWNER&color=yellow)](https://github.com/CreatmanCEO?tab=stars)
[![Public repos](https://img.shields.io/badge/public%20repos-37-22c55e)](https://github.com/CreatmanCEO?tab=repositories)

<img src="https://github-readme-stats.vercel.app/api?username=CreatmanCEO&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="GitHub Stats" height="165">

---

## 📫 Let's talk

**Open to:**
- 🌍 **Senior engineering / staff-level roles** — remote, open to relocation outside Russia
- 🤝 **Architectural / technical-lead partnerships** — for select product ventures
- 💬 **Investment / acquisition discussions** — for [GHOST](https://github.com/CreatmanCEO/ghost-showcase) and [lingua-companion](https://github.com/CreatmanCEO/lingua-companion) in particular

**Reach me:**
[![Email](https://img.shields.io/badge/Email-creatmanick%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:creatmanick@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-%40Creatman__it-2CA5E0?logo=telegram&logoColor=white)](https://t.me/Creatman_it)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-creatman-0077B5?logo=linkedin&logoColor=white)](https://linkedin.com/in/creatman)
[![Website](https://img.shields.io/badge/creatman.site-000?logo=google-chrome&logoColor=white)](https://creatman.site)
[![Habr](https://img.shields.io/badge/Habr-creatman-77a2b6)](https://habr.com/ru/users/creatman/)
[![dev.to](https://img.shields.io/badge/dev.to-%40creatman-0a0a0a?logo=devdotto)](https://dev.to/creatman)

---

<details>
<summary id="-на-русском"><b>🇷🇺 На русском</b></summary>

## Привет, я Ник.

> **Полевой геолог с 2007 года. Software engineer с 2020.**
> **Создаю AI-native инструменты и агентную инфраструктуру — MNEMO (память), Rotator (оркестрация) и растущую экосистему Claude Code skills.**
>
> *Одно ремесло на разном рельефе. Двадцать лет картографирую невидимое в земле; пять — собираю недостающее на экране.*

Я строю инструменты, которые сначала нужны были мне самому, потом передаю людям — `diabot` для родного человека с диабетом 1 типа, `security-scanner` после реального случая со взломанным телефоном друга, `claude-code-antiregression-setup` потому что мои собственные рефакторинги ломали рабочий код. Инжиниринг как ремесло, не как контент — я не покупаю внимание. Я делаю вещи достаточно содержательные, чтобы нужные люди находили их сами.

### 🌍 Open-source

- **[mnemo-showcase](https://github.com/CreatmanCEO/mnemo-showcase)** — граф событий с семантическим поиском для AI-агентов · 14K событий · pgvector · bge-m3 · 135 тестов · 5 спринтов за 12 дней
- **[rotator-showcase](https://github.com/CreatmanCEO/rotator-showcase)** — голосовой co-pilot + MCP-периферия для Claude Code · bounded loops · citation-grounded recall · eval-driven skill learning
- **[cc-janitor](https://github.com/CreatmanCEO/cc-janitor)** — TUI/CLI для гигиены среды Claude Code · Phase 1 MVP в активной разработке
- **[claude-code-antiregression-setup](https://github.com/CreatmanCEO/claude-code-antiregression-setup)** ⭐11 — [Habr топ-5 дня · 20K чтений](https://habr.com/ru/articles/1013330/)
- **[webtest-orch](https://github.com/CreatmanCEO/webtest-orch)** — token-efficient e2e orchestration · CI matrix · 113 тестов
- **[claude-statusline](https://github.com/CreatmanCEO/claude-statusline)** ⭐5 — [Habr · 9.3K чтений](https://habr.com/ru/articles/1013414/)
- **[ai-context-hierarchy](https://github.com/CreatmanCEO/ai-context-hierarchy)** ⭐3 — [в roadmap Graphify v5.0](https://github.com/safishamsi/graphify/issues/425)
- **[notebooklm-claude-workflows](https://github.com/CreatmanCEO/notebooklm-claude-workflows)** ⭐3 — 7 slash-команд · продакшн-тест на 41K сообщений Telegram

### 💼 Commercial

- **[AviaWallet](https://apps.apple.com/app/aviawallet/id6754718339)** — кросс-платформенный крипто-кошелёк · Flutter · в App Store · вёл проект с 0 до первого релиза
- **Sakhalin-Market** — кросс-платформенный маркетплейс + админка · спроектировал соло с 0 до продакшена с одним помощником в штате · в продакшене с 2024
- **🔨 [ghost-showcase](https://github.com/CreatmanCEO/ghost-showcase)** — невидимый AI-ассистент для Windows · Phase 1 · *открыт к инвестициям / acquisition*
- **🔨 [lingua-companion](https://github.com/CreatmanCEO/lingua-companion)** — voice-first English-tutor · приватная бета · *открыт к партнёрству*
- **[security-scanner](https://github.com/CreatmanCEO/security-scanner)** — детектор мобильных угроз через анализ VPN-трафика · `@secure_scanbot` LIVE · Phase 2 — open-sourcing
- **[club-sbor.ru](https://club-sbor.ru)** — платформа для футбольных клубов · в продакшене с 2023 · *проект, который вытолкнул меня из конструкторов в код*

**Ещё:** `hebrew_doc_translator` · `joy-vision-calculator` · `cian-parser-showcase` · `rentscout` · `vpn-commercial-bot` *(private)*

### ❤️ Personal · non-commercial

- **[diabot](https://github.com/CreatmanCEO/diabot)** — для близких с диабетом 1 типа · PolyForm Noncommercial · *своё решаю, потом отдаю*
- **Ещё:** `portfolio` (creatman.site) · `smart-link-collector` · `work-assistant` *(private)* · `vpn-key-bot` *(private)*

### 🔬 Deep dives

- **[hydrowatch](https://github.com/CreatmanCEO/hydrowatch)** — мониторинг подземных вод с LLM-агентом · уравнение Theis · 7 MCP-style tools · 154 теста · 17 лет полевой геологии → software engineering

Больше case studies в `case-studies/`.

### 📫 Открыт к

- 🌍 **Senior engineering / staff-level позициям** — remote, готов к релокации за пределы РФ
- 🤝 **Архитектурным / techlead-партнёрствам** — для отдельных продуктовых проектов
- 💬 **Инвестициям / acquisition** — для GHOST и lingua-companion в первую очередь

</details>

---

<sub>*Build, ship, share.*</sub>
