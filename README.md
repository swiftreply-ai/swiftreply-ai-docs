# SwiftReply AI — Documentation

This repository contains the **public documentation** for SwiftReply AI, including guides, API reference, and high-level architecture.

---

## 📘 Sections

### 📚 Guides  
- `guides/getting-started.md`  
- `guides/authentication.md`  
- `guides/rate-limits.md`  
- `guides/errors.md`  

### 🏗 Architecture  
- `architecture/overview.md`  
- High-level diagrams (safe, non-sensitive)

### 🧬 API Specification  
- `openapi.yaml` — Official OpenAPI 3.1 schema  
Works with Swagger, Postman, Redoc, Stoplight.

---

## 🌐 Documentation Website

Hosted version (recommended):

➡️ https://docs.swiftreply.ai  
(*Or GitHub Pages until production launch.*)

Built using **Docusaurus**.

---

## 🏛 High-Level Architecture (Safe)

We expose a **high-level** but non-sensitive view of the system:

- Client SDK  
- Public API Gateway  
- Task Orchestrator  
- Reply Engine  

Internal services, infrastructure, and sensitive topology are not shown.

---

## 🛠 Development

```bash
npm install
npm run start
```

## 🤝 Contributing

Fixes, clarity improvements, and example expansions are appreciated.  
Before contributing, read `CONTRIBUTING.md`.
