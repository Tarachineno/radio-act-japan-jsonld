# Japanese Radio Act in JSON-LD

This repository provides a machine-readable version of the Japanese Radio Act in [JSON-LD](https://json-ld.org/) format. It includes Japanese and English translations of the legal text for use in legal informatics, research, and AI training purposes.

## 📁 Structure
- Each chapter is stored in a separate JSON file (e.g., `chapter_001.json`).
- Chapters contain one or more sections, even if untitled.
- Sections include a list of articles.
- Each article includes:
  - `articleNumber` in both Japanese and English
  - `title` in both Japanese and English
  - `text` in both Japanese and English (`original`, `translation`)
  - Optional `items`, with individual `number_ja`, `number_en`, `original`, and `translation`

## 📘 Context Definition
The context is defined in `context/radio-act-context.json` and includes:
- Terms such as `chapterNumber`, `sectionNumber`, `articleNumber`, `title`, `text`, `original`, `translation`, `items`, `number_ja`, `number_en`
- Structures such as `sections` and `articles`

## 🔗 Source
- Japanese: 総務省法令（https://www.soumu.go.jp）
- English: [Japanese Law Translation Database System](https://www.japaneselawtranslation.go.jp/)

## 🚀 Goals
- Create a high-quality legal dataset for multilingual processing
- Enable integration with knowledge graphs, AI reasoning, and NLP tasks

## 🤝 Contribution
Suggestions, issues, and pull requests are welcome!

---

Made with 💖 by Tsune & Manne (つね＆まんねー)