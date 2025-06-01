# Japanese Radio Act JSON-LD

This repository provides a structured, machine-readable representation of the Japanese Radio Act using the JSON-LD format.

## 🎯 Purpose

- Represent and publish provisions of the Japanese Radio Act in both Japanese and English using JSON-LD.
- Promote reuse as open data for searching, comparison, legal processing, and AI training.
- Establish a model case for legal data structuring in compliance with international standards.

## 📁 Project Structure

```
radio-act-japan-jsonld/
├── README.md
├── context/
│   └── radio-act-context.json     # JSON-LD @context definition
├── chapter/
│   ├── chapter_001.json          # Chapter I: General Provisions
│   └── chapter_002.json          # Chapter II: ...
```

## 📘 Naming Conventions

- Chapter file names follow: `chapter_001.json` (3-digit index)
- Chapter numbers: `chapterNumber.ja`, `chapterNumber.en`
- Article numbers: `articleNumber.ja`, `articleNumber.en`
- Clause numbers: `number_ja`, `number_en` (e.g., "一" and "(i)")

## 🌐 JSON-LD Context

```json
"@context": "https://tarachineno.github.io/radio-act-japan-jsonld/context/radio-act-context.json"
```

Vocabulary IRI definition:
```json
"law": "https://tarachineno.github.io/radio-act-japan-jsonld/ontology#"
```

## 🔧 Usage

- Use with JSON-LD compatible tools such as `jsonld.js` or `pyld`
- Supports AI/ML training and knowledge graph generation

## 🤝 Contributing

- Please open an Issue or Pull Request if you find any structural or translation issues
- PRs with properly formatted JSON are highly appreciated

## 📚 Sources

- Ministry of Internal Affairs and Communications (Japanese): https://www.soumu.go.jp/menu_hourei/s_shourei.html
- Ministry of Justice (English translation): https://www.japaneselawtranslation.go.jp/en/laws/view/3205

---

A future-proof legal AI infrastructure project by Tsune & Mannee ✨