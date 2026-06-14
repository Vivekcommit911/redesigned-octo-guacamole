# Automated Markdown Portfolio Generator

> A production-ready CLI tool that transforms Markdown files with YAML front matter into a beautiful static portfolio website.

## 🚀 Overview

Automated Markdown Portfolio Generator is an open-source developer tool that scans a directory of Markdown files, extracts metadata from YAML front matter, converts Markdown content to HTML, and generates a complete static portfolio website.

Perfect for developers, technical writers, students, and creators who want to maintain their portfolio using simple Markdown files.

---

## ✨ Features

* 📂 Recursive Markdown file discovery
* 📝 YAML Front Matter support
* ⚡ Fast Markdown → HTML conversion
* 🎨 Responsive portfolio layout
* 🏷 Metadata-driven content generation
* 🔍 Automatic slug generation
* 📄 Static HTML output
* 🧩 Modular architecture
* 🛡 TypeScript type safety
* 🚀 Ready for GitHub Pages deployment

---

## 📁 Project Structure

```text
markdown-portfolio-generator/
├── content/
│   ├── project-1.md
│   ├── project-2.md
│   └── blog-post.md
│
├── dist/
│   ├── index.html
│   ├── project-1.html
│   └── project-2.html
│
├── src/
│   ├── core/
│   │   ├── builder.ts
│   │   ├── parser.ts
│   │   ├── scanner.ts
│   │   └── logger.ts
│   │
│   ├── templates/
│   │   ├── home.ts
│   │   ├── layout.ts
│   │   └── post.ts
│   │
│   ├── types/
│   │   └── content.ts
│   │
│   ├── utils/
│   │   ├── fs.ts
│   │   └── slug.ts
│   │
│   └── index.ts
│
├── package.json
├── tsconfig.json
└── README.md
```

---

## 📦 Installation

### Clone Repository

```bash
git clone https://github.com/Vivekcommit911/markdown-portfolio-generator.git
cd markdown-portfolio-generator
```

### Install Dependencies

```bash
npm install
```

### Run Development Build

```bash
npm run dev
```

### Build Production Version

```bash
npm run build
```

---

## ✍ Example Markdown File

```markdown
---
title: Portfolio Generator
description: Static site generator built with TypeScript
date: 2026-06-14
tags:
  - typescript
  - markdown
  - cli
---

# Portfolio Generator

This project converts Markdown content into a complete static portfolio website.
```

---

## ⚙️ Generated Output

```text
dist/
├── index.html
├── portfolio-generator.html
└── assets/
```

---

## 🛠 Technology Stack

* TypeScript
* Node.js
* Gray Matter
* Marked
* HTML5
* Tailwind CSS

---

## 🏗 Architecture

```text
Markdown Files
       │
       ▼
Directory Scanner
       │
       ▼
YAML Parser
       │
       ▼
Markdown Converter
       │
       ▼
HTML Generator
       │
       ▼
Static Portfolio Website
```

---

## 🚀 Future Roadmap

* [ ] RSS Feed Generation
* [ ] Sitemap Support
* [ ] Search Index Generation
* [ ] Theme System
* [ ] Plugin Architecture
* [ ] Incremental Builds
* [ ] Watch Mode
* [ ] GitHub Actions Integration
* [ ] Asset Optimization Pipeline
* [ ] Markdown Extensions

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/amazing-feature
```

3. Commit your changes

```bash
git commit -m "Add amazing feature"
```

4. Push to GitHub

```bash
git push origin feature/amazing-feature
```

5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License.

See `LICENSE` for more information.

---

## 👨‍💻 Author

**Vivek**

GitHub: https://github.com/Vivekcommit911

---

⭐ If you find this project useful, consider giving it a star.
