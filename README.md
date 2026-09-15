# 🗄️ AI ERD Generator

Generate comprehensive **Entity Relationship Diagrams** through warm, conversational AI interviews.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-0.2.0-blue.svg)]()

> Inspired by advanced prompting techniques from Claude Fable 5, Cursor, Lovable, and Devin.

## ✨ Features

- 🗣️ **Conversational Interview** — AI asks questions one by one, like talking to a friend
- 🇮🇩 **Indonesian & English** — Natural bilingual support
- 🎯 **Fable 5 Style** — Warm, friendly, no AI-isms
- 📝 **Non-Technical Summary** — Simple explanation at the end
- 🔧 **Multi-Tool** — Works with Claude Code, Codex, OpenCode, Hermes Agent

## 📦 Installation

### Claude Code
```bash
git clone https://github.com/Vann4799/ai-erd-generator.git ~/.claude/ai-erd-generator
```

### Codex
```bash
git clone https://github.com/Vann4799/ai-erd-generator.git ~/.codex/ai-erd-generator
```

### OpenCode
```bash
git clone https://github.com/Vann4799/ai-erd-generator.git ~/.opencode/skills/ai-erd-generator
```

### Hermes Agent
```bash
hermes skills install Vann4799/ai-erd-generator
```

## 🎯 Usage

Simply say:

```
"Buat ERD untuk aplikasi kasir toko"
```

## 📋 Interview Questions

| # | Question (ID) | Question (EN) |
|---|--------------|---------------|
| 1 | Apa nama aplikasinya? | What's the project name? |
| 2 | Jenis aplikasinya apa? | What type of project? |
| 3 | Data apa aja yang mau disimpan? | What data to store? |
| 4 | Apa aja 'benda utama' di aplikasi? | What are the main entities? |
| 5 | Gimana 'benda-benda' ini saling berhubungan? | How are entities related? |
| 6 | Ada aturan khusus untuk data? | Any database constraints? |
| 7 | Mau Bahasa Indonesia atau English? | Language preference? |


## 📄 Output Structure

1. Entity Descriptions
2. Relationship Descriptions
3. Visual Diagram (Mermaid)
4. SQL Schema (PostgreSQL)
5. Migration Plan
6. Non-Technical Summary

## 🤝 Contributing

PRs welcome!

## 📄 License

MIT License

---

Made with ❤️ by [Vann4799](https://github.com/Vann4799)
