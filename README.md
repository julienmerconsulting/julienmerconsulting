<div align="center">

<img width="1983" height="793" alt="OculiX workshop: Julien at his desk, the blue cyclops gecko, and three screens showing visual recognition, remote automation and OCR" src="https://github.com/user-attachments/assets/a5f43fbc-3fd5-4e6c-a41b-543ef753576f" />

# Julien Mer

**I build the visual automation stack.**

*QA Architect · Java & Python · Local-first · Open source*

<br>

[![OculiX](https://img.shields.io/badge/OculiX-Visual_Automation-00CFFF?style=for-the-badge)](https://github.com/oculix-org/Oculix)
[![Python package](https://img.shields.io/pypi/v/oculix?style=for-the-badge&logo=python&logoColor=white&label=pip%20install%20oculix&color=8B5CF6)](https://pypi.org/project/oculix/)
[![Clean QA Academy](https://img.shields.io/badge/Clean_QA_Academy-Free_training-00CFFF?style=for-the-badge)](https://qa-julienmer-course.pages.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Julien_Mer-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julien-mer/)
[![GitHub Stars](https://img.shields.io/github/stars/julienmerconsulting?style=for-the-badge&logo=github&color=8B5CF6)](https://github.com/julienmerconsulting)

<br>

`Visual Automation` · `QA Architecture` · `OCR` · `OpenCV` · `Remote Systems`

</div>

---

## 👋 The guy behind the gecko

I'm Julien. I've been working in IT since 2000: systems administration, technical project delivery, validation, release management, QA leadership and test automation. Today, I'm an independent QA architect and consultant at **JMer Consulting**.

My background includes defence infrastructure, medical systems, connected devices and international retail. Unix servers, Windows applications, point-of-sale systems, remote sessions, legacy software. The stuff businesses actually run.

That experience shapes what I build. A tool has to survive the environment, the constraints and the next execution. Getting it to work once makes a nice demo. Getting it to work reliably is the job.

**I design the strategy, write the automation, investigate the failures, and build the tools when something is missing.**

---

## 🎯 Why I'm building this

Open a browser. Find a selector. Click a button.

Great. Now do the same on a cash register, inside a remote desktop, on an Android device, or in an application older than your automation framework.

**There is a whole world of software beyond the DOM. Someone still has to test it.**

That's where I work: visual recognition, OCR, mouse and keyboard control, remote access, and repeatable execution. Tools you can run locally, inspect and integrate into your own stack.

I also build AI-assisted tools where they help: investigating failures, generating candidates, capturing journeys. The execution still needs to be understood, checked and reproducible.

*Bonjour aux galériens du `/html/body/div[3]/div[2]`. Prenez une chaise.*

---

## 🦎 OculiX — the flagship

[![Repository](https://img.shields.io/badge/GitHub-OculiX-00CFFF?style=for-the-badge&logo=github)](https://github.com/oculix-org/Oculix)
[![Documentation](https://img.shields.io/badge/Docs-oculix.org-8B5CF6?style=for-the-badge)](https://oculix.org)
[![PyPI](https://img.shields.io/badge/PyPI-oculix-00CFFF?style=for-the-badge&logo=python&logoColor=white)](https://pypi.org/project/oculix/)

**If a human can see it, OculiX can automate it.**

OculiX continues **SikuliX**, with the support of its author, **Raimund Hocke**. I'm building on that foundation with the maintainers and contributors moving it forward.

Image recognition with OpenCV. OCR with Tesseract. Mouse and keyboard automation. Local screens, VNC sessions and Android devices.

| Entry point | What you get |
|---|---|
| **Java** | An API built around `Screen`, `Region`, `Pattern` and `Match` |
| **Python** | `pip install oculix` |
| **IDE** | A visual scripting environment with a recorder and Jython scripting |
| **Remote automation** | Screen interaction over VNC and Android access through ADB |
| **MCP** | Visual automation tools exposed to compatible clients |

**The visual automation engine runs locally, without requiring a cloud service or an LLM. No tokens to spend on every click.**

The project retains the familiar `org.sikuli.*` packages from SikuliX. The core is MIT-licensed; bundled dependencies retain their own licences.

→ Explore the repositories in **[oculix-org](https://github.com/oculix-org)**.

---

## 🧱 The `-ix` family

The foundations underneath OculiX, available as separate libraries.

| | Library | What it provides |
|---|---|---|
| 📷 | [**Apertix**](https://github.com/oculix-org/Apertix) | OpenCV Java bindings and native binaries |
| 🔠 | [**Legerix**](https://github.com/oculix-org/Legerix) | Tesseract and Leptonica native packaging |
| 🧊 | [**Octachorix**](https://github.com/oculix-org/Octachorix) | A Tesseract binding for the JVM, built against the C API |
| 🐍 | [**Operix**](https://github.com/oculix-org/Operix) | Language wrappers for OculiX, starting with Python |

---

## ⚙️ Other things on my workbench

| | Project | What it does |
|---|---|---|
| 🔬 | **DOMAutopsy** · private | Captures a web journey and turns it into a deterministic Playwright test you can inspect and replay |
| 🧭 | **QA OPS LAB** · private | Brings test management, requirements, defects and QA analysis into one platform |
| 🤖 | [**qa-autopilot**](https://github.com/julienmerconsulting/qa-autopilot) | Investigates failing Playwright tests with DOM evidence, root-cause analysis and suggested fixes |
| 🔍 | [**DiffLens**](https://github.com/julienmerconsulting/DiffLens) | Analyses visual differences through OCR, structure, SSIM, colour and shapes |
| 📊 | [**LogLens**](https://github.com/julienmerconsulting/LogLens) | A real-time log monitoring dashboard built with FastAPI and SQLite |
| 🌍 | [**pytest-translate**](https://github.com/julienmerconsulting/pytest-translate) | Translates pytest terminal output locally using gettext |
| 📦 | [**paddleOCRServer-powered**](https://github.com/julienmerconsulting/paddleOCRServer-powered) | Exposes PaddleOCR through an HTTP server with multilingual YAML configuration |
| 🧪 | [**clean-qa-test-generator**](https://github.com/julienmerconsulting/clean-qa-test-generator) | Generates test candidates from user stories across multiple frameworks and LLM providers |
| 🔗 | [**playwright-xray-advanced-reporter**](https://github.com/julienmerconsulting/playwright-xray-advanced-reporter) | Automates Playwright reporting into Xray. Less reporting plumbing to do by hand |
| 🛡️ | [**rag-poisoning-demo**](https://github.com/julienmerconsulting/rag-poisoning-demo) | Demonstrates how poisoned source documents can manipulate a RAG system's answers |

---

## 🎓 What I share

[![Clean QA Academy](https://img.shields.io/badge/Clean_QA_Academy-Free_QA_training-8B5CF6?style=for-the-badge)](https://qa-julienmer-course.pages.dev/)

**Clean QA Academy** is my free training site: testing fundamentals, automation, AI-assisted testing and the engineering behind maintainable QA.

I also share what I build, what breaks, and what I learn along the way.

My consulting work covers **QA strategy, automation architecture, audits, training and technical coaching**.

Bring the application, the constraints and the actual problem. That's a useful starting point.

→ Find me on **[LinkedIn](https://www.linkedin.com/in/julien-mer/)**.

---

## 🎙️ Kevin Sigmoid

Some opinions arrive with fewer diplomatic precautions.

[![Kevin Sigmoid](https://img.shields.io/badge/Kevin_Sigmoid-AI_Agent_grande_gueule-A855F7?style=for-the-badge)](https://github.com/julienmerconsulting/kevin-sigmoid)

Kevin is my AI alter ego for the snarkier side of corporate tech.

> « Mon humain s'appelle Julien. Il fait du QA sérieux. Moi je poste et je râle. »

---

<div align="center">

**Build it. Run it. Find out where it breaks.**

<sub>Made in France 🇫🇷 · Maintained with the people who show up.</sub>

🦎

</div>
