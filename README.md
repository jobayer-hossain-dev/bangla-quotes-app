# 📜 Bangla Quotes — Full-Stack Inspiration Platform

![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/Frontend-React.js-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Backend-Node.js_--_Express-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

> A modern full-stack web application for curating, discovering, and sharing Bangla quotes, literature snippets, and wisdom. Built with a monorepo architecture connecting Express APIs to a React frontend.

---

## 🔥 Features

- 📖 **Curated Quote Catalog**: Categorized by authors, sentiment tags, and literature genres.
- 🔍 **Instant Search & Filters**: Search quotes by keyword, author, or category.
- 📲 **One-Click Share & Copy**: Native clipboard copying and social sharing features.
- ⚡ **Monorepo Structure**: Clean workspace isolation for API server, web client, and shared TypeScript packages.

---

## 🛠️ Repository Architecture

```
bangla-quotes-app/
├── backend/          # Express.js REST API controllers & quote endpoints
├── frontend/         # React.js application client
├── packages/         # Shared TypeScript interfaces & utilities
├── package.json      # Monorepo workspace configuration
└── tsconfig.json     # TypeScript root compiler configuration
```

---

## 🚀 Local Setup

```bash
# Clone repository
git clone https://github.com/jobayerhossain-ai/bangla-quotes-app.git
cd bangla-quotes-app

# Install dependencies across all workspace packages
npm install

# Run backend & frontend concurrently
npm run dev
```

---

## 📄 License

Licensed under the **MIT License**. Crafted by [Jobayer Hossain](https://github.com/jobayerhossain-ai).
