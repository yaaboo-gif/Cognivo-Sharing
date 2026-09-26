# Cognivo-Sharing

> **Mirror of WeChat public code snippets · 元言·Cognivo 微信公众号**
> [中文版 README](README.zh.md)

---

## About This Repository

This repository is a **mirror of code snippets shared publicly by the WeChat account 元言·Cognivo 微信公众号**.

Whenever a WeChat article requires publicly-shareable example code, a **desensitized, fully-runnable version** is published here — so readers can download, learn, and experiment.

**This is not a project source-code repository. It is a curated collection of teaching examples.**

---

## Directory Layout

```
Cognivo-Sharing/
├── README.md                     # This file (English, default)
├── README.zh.md                  # 中文版 README
├── LICENSE                       # MIT
└── articles/                     # One subdirectory per article
    └── <article-slug>/
        ├── README.md             # Article walkthrough (Chinese + English)
        ├── code snippet(s)       # Desensitized example code
        ├── METADATA.yaml         # Metadata + desensitization audit
        └── sample-card.png       # WeChat article card with QR code
```

> **Tip**: Browse the `articles/` directory and pick a topic that interests you. Each article's README contains a full code walkthrough.

---

## How to Use

### Option 1 · Download a Single Article Directory

1. Navigate to `articles/<article-slug>/`
2. Click **Code → Download ZIP** in the top right
3. Extract and follow the run instructions in that directory's README

### Option 2 · Clone the Whole Repository

```bash
git clone https://github.com/yaaboo-gif/Cognivo-Sharing.git
cd Cognivo-Sharing/articles/<article-slug>/
# Follow the README in that directory
```

### Option 3 · Scan a QR Code (WeChat Readers)

Every WeChat article ends with a card image containing a QR code. Scanning it takes you directly to the matching GitHub article directory.

---

## Content Principles

- ✅ **Fully Desensitized** — Every code snippet passes a 6-point audit:
  - API keys removed
  - Internal URLs removed
  - Personal / character names removed
  - Project IDs removed
  - Internal architecture references removed
  - Manual human review passed
- ✅ **Independently Runnable** — Every example runs without any external private service
- ✅ **Bilingual Walkthroughs** — Every directory includes Chinese + English README explaining what the code does and why
- ❌ **No Internal Information** — This repository **does not contain** any internal project structure, code names, or organizational information

---

## License

MIT — You are free to use, modify, and redistribute the code snippets in this repository (see the `LICENSE` file for details).

If you reference this work in WeChat articles or videos, attribution is appreciated.

---

## Feedback

- **WeChat Account**: 元言·Cognivo 微信公众号
- **GitHub Issues**: Use the Issues tab (English or Chinese both welcome)
- **WeChat Group / Discord**: See the bottom of any WeChat article for invitations

---

*Last updated: 2026-09-26*