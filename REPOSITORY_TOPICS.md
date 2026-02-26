# Repository Topics Guide

> Полный список topics для всех публичных репозиториев CreatmanCEO

**Обновлено:** 2026-02-26  
**Цель:** SEO-оптимизация и улучшение видимости в GitHub поиске

---

## 🎯 Приоритет 1 — Flagship Projects

### [accu](https://github.com/CreatmanCEO/accu)
**Topics:**
```
ai, open-source, automation, github, curator, llm, developer-tools, python
```

**Description (English):**
```
AI-Curated Code Universe — ecosystem for reviving undervalued open-source projects through human-AI collaboration
```

---

### [smart-link-collector](https://github.com/CreatmanCEO/smart-link-collector)
**Topics:**
```
telegram-bot, ai, whatsapp, google-sheets, automation, nodejs, nlp, product-management
```

**Description (English):**
```
🔗 AI-powered Telegram & WhatsApp bot that analyzes product links and organizes them in Google Sheets automatically
```

---

### [joy-vision-calculator](https://github.com/CreatmanCEO/joy-vision-calculator)
**Topics:**
```
javascript, web-app, calculator, bitrix24, crm-integration, construction, glass-systems
```

**Description (English):**
```
Web application for calculating frameless glazing system components with Bitrix24 CRM integration
```

**Description (Russian) — вторичное:**
```
Веб-приложение для расчета комплектующих систем безрамного остекления с интеграцией Bitrix24
```

---

### [hebrew_doc_translator](https://github.com/CreatmanCEO/hebrew_doc_translator)
**Topics:**
```
translation, hebrew, russian, english, python, web-app, nlp, document-processing, flask
```

**Description (English):**
```
Web application for translating documents from Hebrew to Russian and English while preserving formatting
```

---

## 🤖 Telegram & Automation

### [telegram-bot-n8n-assistant](https://github.com/CreatmanCEO/telegram-bot-n8n-assistant)
**Topics:**
```
n8n, telegram-bot, llm, automation, documentation, ai, workflow, chatbot
```

**Description (English):**
```
Documentation and implementation guide for building intelligent Telegram bots on n8n platform with LLM integration
```

**Description (Russian) — вторичное:**
```
Документация по разработке интеллектуальных телеграм-ботов на платформе n8n с интеграцией LLM-моделей
```

---

### [telegram-user-api](https://github.com/CreatmanCEO/telegram-user-api)
**Topics:**
```
telegram, api, n8n, python, automation, mtproto, userbot, integration
```

**Description (English):**
```
n8n integration with Telegram User API (MTProto) for advanced automation and user account operations
```

**Description (Russian) — вторичное:**
```
Интеграция n8n с пользовательским API Telegram
```

---

### [telegram-personal-api](https://github.com/CreatmanCEO/telegram-personal-api)
**Topics:**
```
telegram, mtproto, api, python, n8n, messaging, automation
```

**Description (English):**
```
API for sending messages through personal Telegram account with n8n integration
```

**Description (Russian) — вторичное:**
```
API для отправки сообщений через личный аккаунт Telegram с интеграцией n8n
```

---

### [telegram-form-worker](https://github.com/CreatmanCEO/telegram-form-worker)
**Topics:**
```
cloudflare-workers, telegram, serverless, forms, javascript, edge-computing
```

**Description (English):**
```
Cloudflare Worker for processing web forms and sending notifications to Telegram
```

**Description (Russian) — вторичное:**
```
Cloudflare Worker для обработки форм и отправки в Telegram
```

---

### [notion-transfer-bot](https://github.com/CreatmanCEO/notion-transfer-bot)
**Topics:**
```
notion, telegram-bot, nodejs, automation, productivity, api-integration
```

**Description (English):**
```
Telegram bot for seamless synchronization and data transfer with Notion workspace
```

**Description (Russian) — вторичное:**
```
Telegram-бот для синхронизации с Notion
```

---

### [CreatmanTaskBot](https://github.com/CreatmanCEO/CreatmanTaskBot)
**Topics:**
```
telegram-bot, task-manager, python, productivity, todo, aiogram
```

**Description (English):**
```
Telegram-based task management bot for personal productivity and workflow organization
```

**Description (Russian) — вторичное:**
```
Telegram-бот для управления задачами
```

---

### [itPovarVkBot](https://github.com/CreatmanCEO/itPovarVkBot)
**Topics:**
```
vk-bot, python, chatbot, vk-api, russian, social-media
```

**Description (English):**
```
VKontakte chatbot for automated interactions and content management
```

**Description (Russian) — вторичное:**
```
VK бот для автоматизации
```

---

## 💰 Fintech & Mobile

### [crypto-wallet-mvp](https://github.com/CreatmanCEO/crypto-wallet-mvp)
**Topics:**
```
react-native, cryptocurrency, wallet, mobile-app, blockchain, fintech, cross-platform
```

**Description (English):**
```
Cross-platform mobile cryptocurrency wallet built with React Native
```

**Description (Russian) — вторичное:**
```
Кроссплатформенное мобильное приложение криптокошелька на React Native
```

---

## 🛠 Utilities & Tools

### [TestCRM](https://github.com/CreatmanCEO/TestCRM)
**Topics:**
```
crm, python, web-app, customer-management, flask
```

**Description (English):**
```
Custom CRM system for customer relationship management
```

---

### [CreatmanCEO.github.io](https://github.com/CreatmanCEO/CreatmanCEO.github.io)
**Topics:**
```
portfolio, personal-website, github-pages, static-site, html, css
```

**Description (English):**
```
Personal portfolio and project showcase website
```

---

## 📋 Profile Repository

### [CreatmanCEO](https://github.com/CreatmanCEO/CreatmanCEO)
**Topics:**
```
profile, readme, github-profile, portfolio, automation-engineer
```

**Description (English):**
```
Profile README - Growth story of a creator and automation engineer
```

**Description (Russian) — вторичное:**
```
Profile README - История роста создателя
```

---

## 📝 Как добавить topics

### Метод 1: Через веб-интерфейс
1. Открыть репозиторий на GitHub
2. Нажать ⚙️ (Settings) справа от "About"
3. В поле "Topics" ввести теги (через пробел или Enter)
4. Нажать "Save changes"

### Метод 2: Через gh CLI
```bash
# Установить gh CLI
# https://cli.github.com/

# Добавить topics
gh repo edit CreatmanCEO/accu --add-topic "ai,open-source,automation,github,curator,llm,developer-tools,python"
```

### Метод 3: Bulk update (все сразу)
```bash
#!/bin/bash

# accu
gh repo edit CreatmanCEO/accu --add-topic "ai,open-source,automation,github,curator,llm,developer-tools,python"

# smart-link-collector
gh repo edit CreatmanCEO/smart-link-collector --add-topic "telegram-bot,ai,whatsapp,google-sheets,automation,nodejs,nlp,product-management"

# joy-vision-calculator
gh repo edit CreatmanCEO/joy-vision-calculator --add-topic "javascript,web-app,calculator,bitrix24,crm-integration,construction,glass-systems"

# hebrew_doc_translator
gh repo edit CreatmanCEO/hebrew_doc_translator --add-topic "translation,hebrew,russian,english,python,web-app,nlp,document-processing,flask"

# telegram-bot-n8n-assistant
gh repo edit CreatmanCEO/telegram-bot-n8n-assistant --add-topic "n8n,telegram-bot,llm,automation,documentation,ai,workflow,chatbot"

# telegram-user-api
gh repo edit CreatmanCEO/telegram-user-api --add-topic "telegram,api,n8n,python,automation,mtproto,userbot,integration"

# telegram-personal-api
gh repo edit CreatmanCEO/telegram-personal-api --add-topic "telegram,mtproto,api,python,n8n,messaging,automation"

# telegram-form-worker
gh repo edit CreatmanCEO/telegram-form-worker --add-topic "cloudflare-workers,telegram,serverless,forms,javascript,edge-computing"

# notion-transfer-bot
gh repo edit CreatmanCEO/notion-transfer-bot --add-topic "notion,telegram-bot,nodejs,automation,productivity,api-integration"

# CreatmanTaskBot
gh repo edit CreatmanCEO/CreatmanTaskBot --add-topic "telegram-bot,task-manager,python,productivity,todo,aiogram"

# itPovarVkBot
gh repo edit CreatmanCEO/itPovarVkBot --add-topic "vk-bot,python,chatbot,vk-api,russian,social-media"

# crypto-wallet-mvp
gh repo edit CreatmanCEO/crypto-wallet-mvp --add-topic "react-native,cryptocurrency,wallet,mobile-app,blockchain,fintech,cross-platform"

# TestCRM
gh repo edit CreatmanCEO/TestCRM --add-topic "crm,python,web-app,customer-management,flask"

# CreatmanCEO.github.io
gh repo edit CreatmanCEO/CreatmanCEO.github.io --add-topic "portfolio,personal-website,github-pages,static-site,html,css"

# Profile repo
gh repo edit CreatmanCEO/CreatmanCEO --add-topic "profile,readme,github-profile,portfolio,automation-engineer"

echo "✅ Topics added to all repositories!"
```

---

## 🎯 Best Practices

### Topics лимиты
- **Максимум:** 20 topics на репозиторий
- **Рекомендуется:** 5-8 для лучшей фокусировки

### Topic naming
- ✅ Lowercase, kebab-case: `telegram-bot`
- ✅ Широкие + узкие: `python` + `fastapi`
- ✅ Технологии + use-case: `ai` + `automation`
- ❌ Не использовать пробелы
- ❌ Не дублировать описание

### Приоритет topics
1. **Технологии:** `python`, `nodejs`, `react-native`
2. **Use-case:** `automation`, `chatbot`, `crm`
3. **Платформы:** `telegram`, `n8n`, `cloudflare-workers`
4. **Индустрия:** `fintech`, `ai`, `blockchain`

---

*Создано с помощью Claude Code | Последнее обновление: 2026-02-26*
