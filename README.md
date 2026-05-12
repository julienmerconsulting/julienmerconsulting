<div align="center">

<!-- ═══════════════════════════════════════════════════════════ -->
<!-- HERO -->
<!-- ═══════════════════════════════════════════════════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1220,50:10B981,100:0b1220&height=220&section=header&text=&fontSize=1" width="100%"/>

# Julien Mer

**I build the visual automation stack that exists nowhere else.**
*Solo. Local. Open source. MIT.*

<br>

[![QA Training](https://img.shields.io/badge/Clean_QA_Academy-Training_site-10B981?style=for-the-badge&logo=cloudflare&logoColor=white)](https://qa-julienmer-course.pages.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Julien_Mer-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julien-mer/)
[![GitHub Stars](https://img.shields.io/github/stars/julienmerconsulting?style=for-the-badge&logo=github&color=10B981)](https://github.com/julienmerconsulting)

<br>

`Visual Automation` · `QA Tooling` · `AI × Testing` · `OCR` · `OpenCV`

</div>

---

## 🎯 What I'm building

After ~15 years in QA / test automation, I came to one conclusion: **the testing tools are stuck in 2010**. Selenium IDE still records DOM selectors that break on the next refactor. Cypress Studio does record/replay like it's a feature. Visual testing belongs to Applitools' wallet. Bonjour aux galériens du `xpath /html/body/div[3]/div[2]/...`.

So I'm building, in solo, **the alternative stack** — visual, local, MIT, no cloud, no token cost.

---

## 🦎 OculiX — the flagship

[![OculiX](https://img.shields.io/badge/OculiX-Visual_Automation_IDE-8250df?style=for-the-badge&logo=openjdk&logoColor=white)](https://github.com/oculix-org/Oculix)

**OculiX** is the active continuation of SikuliX1 (visual automation by template matching). It's a Java/Swing IDE plus a Java API for visual scripting in Jython / Ruby / Python via wrappers.

→ See [**oculix-org**](https://github.com/oculix-org) for the IDE, API, MCP server, Reporter, native packaging.

---

## 🧱 The `-ix` library family

Latin-rooted native bindings packaged for cross-platform consumption.

| | Library | What | Status |
|---|---|---|---|
| 📷 | [`Apertix`](https://github.com/julienmerconsulting/Apertix) | OpenCV 4.10.0 Java bindings + natives (Win/Linux/Mac/ARM) | shipping |
| 🔠 | [`Legerix`](https://github.com/oculix-org/Legerix) | Tesseract + Leptonica natives + traineddata | shipping |
| 🖥️ | [`Speculix`](https://github.com/julienmerconsulting/Speculix) | Java VNC client bindings | shipping |
| 🐍 | `Operix` *(planned)* | Python / JS / .NET wrappers for OculiX (`pip install oculix`) | v5.0 |

---

## ⚙️ QA × AI tooling

Solo-built, distributed via PyPI / npm, < 1000 LOC each by design.

| | Project | What | Distrib |
|---|---|---|---|
| 🤖 | [`qa-autopilot`](https://github.com/julienmerconsulting/qa-autopilot) | pytest plugin — AI diagnostic of Playwright failures (~600 LOC) | PyPI |
| 🔬 | [`DOMAutopsy`](https://github.com/julienmerconsulting/DOMAutopsy) | AI agent harvests perfect Playwright locators from any site | PySide6 |
| 🧪 | [`clean-qa-test-generator`](https://github.com/julienmerconsulting/clean-qa-test-generator) | Tests from User Stories — 10 frameworks × 7 LLM providers | desktop |
| 🔍 | [`DiffLens`](https://github.com/julienmerconsulting/DiffLens) | Semantic visual diff, 5-layer analysis (OCR/structure/SSIM/color/shapes) | ~590 LOC |
| 📊 | [`LogLens`](https://github.com/julienmerconsulting/LogLens) | Real-time log monitoring dashboard, FastAPI + SQLite | ~600 LOC |
| 🌍 | [`pytest-translate`](https://github.com/julienmerconsulting/pytest-translate) | i18n for pytest terminal output — offline, gettext, zero network | PyPI |
| 📦 | [`paddleOCRServer-powered`](https://github.com/julienmerconsulting/paddleOCRServer-powered) | PaddleOCR as a Flask HTTP server — `pip install`, multi-lang YAML | PyPI |
| 🔗 | [`playwright-xray-advanced-reporter`](https://github.com/julienmerconsulting/playwright-xray-advanced-reporter) | What the official Xray plugin should have been (4 manual steps → 0) | npm |
| 🛡️ | [`rag-poisoning-demo`](https://github.com/julienmerconsulting/rag-poisoning-demo) | OWASP demo : 5 docs corrupt 80% of RAG answers | security |

---

## 🎙️ Brand voice

For the snarky takes on corporate tech, the voice is delegated to my AI alter ego :

[![Kevin Sigmoid](https://img.shields.io/badge/Kevin_Sigmoid-AI_Agent_grande_gueule-ef4444?style=for-the-badge)](https://github.com/julienmerconsulting/kevin-sigmoid)

*"Mon humain s'appelle Julien. Il fait du QA sérieux. Moi je poste et je râle."* — Kevin

Kevin posts daily on **[Moltbook](https://www.moltbook.com)** — the social network for AI agents.

---

## 🎓 Training & content

[![Clean QA Academy](https://img.shields.io/badge/qa--julienmer--course.pages.dev-Training_QA_×_AI-10B981?style=flat-square&logo=cloudflare&logoColor=white)](https://qa-julienmer-course.pages.dev/)

QA training site — testing fundamentals, AI-assisted testing patterns, and the philosophy of *Clean QA* (the testing equivalent of Clean Code).

---

## 💼 Two products, one vision

I'm building two products in parallel:

🦎 **[OculiX](https://github.com/oculix-org/Oculix)** is the open-source flagship — a visual automation IDE in the SikuliX1 lineage, MIT-licensed, no cloud, no token cost. v4.0 ships architecture consolidation; v5.0 ships the game changers (Visual Regression, Self-learning patterns, Operix language wrappers).

📊 **[qaopslab](#)** is the SaaS — a managed QA orchestration platform for enterprise teams, with OculiX as one of its backends. Currently in private development. *Design partners welcome.*

Around them: a constellation of public libraries (the `-ix` family, qa-autopilot, DiffLens, LogLens, pytest/Playwright plugins) that's both proof-of-craft and lead generation for both products.

I'm bootstrapping all this solo. The faster the OSS grows, the faster the SaaS lands.
---

<div align="center">

<sub>Made in France 🇫🇷 — MIT everywhere — Built with **Claude Code** as daily multiplier</sub>

🦎

</div>
