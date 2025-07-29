# 📘 Antonina Katskel API Documentation

Welcome to the **Antonina API** — a structured and reliable technical writer interface.  
Version: `v1.3.5`  
Status: 🟢 Operational

> I transform complex systems into clear, usable, and scalable documentation.  
> My code is Markdown, my logic — UX, and my fuel — curiosity.

---

## 📍 Base URL

```
https://github.com/antoninakatskel
```

---

## 🔗 Endpoints

### `GET /about`  
Returns general info about the writer.

```json
{
  "name": "Antonina Katskel",
  "role": "Technical Writer / UX Writer",
  "skills": [
    "B2B SaaS Docs",
    "API Documentation",
    "Release Notes",
    "UX Writing",
    "Style Guides"
  ],
  "stack": ["Markdown", "Confluence", "Figma", "Swagger", "Git", "Atlassian"],
  "location": "Remote / UK / EU",
  "status": "Available for collaboration"
}
```

---

### `GET /projects`  
Returns a list of documentation projects and writing samples.

```json
[
  {
    "title": "Monitoring Platform Docs",
    "industry": "Telematics / Logistics",
    "features": ["Admin Guide", "API Docs", "Release Notes"],
    "collaboration": ["Dev team", "QA", "BA"],
    "result": "Single source of truth for QA + reduced onboarding time"
  },
  {
    "title": "Design System Guidelines",
    "type": "Internal product",
    "content": ["UI Text Principles", "Dev Handoff Checklist", "Figma Tokens Guide"],
    "impact": "Faster dev cycles, fewer design inconsistencies"
  },
  {
    "title": "Educational UX Writing",
    "format": "Live & recorded sessions",
    "audience": "Beginner & mid-level designers",
    "tools": ["Notion", "Google Docs", "Interactive tasks"]
  }
]
```

---

### `POST /contact`  
Send a request to collaborate.

#### Request Body:

```json
{
  "name": "Your Name",
  "project": "API Documentation Revamp",
  "deadline": "Flexible",
  "message": "We need clear, user-friendly docs for our dev platform"
}
```

✅ Response:

```json
{
  "status": "200 OK",
  "message": "Let’s talk! Please connect via email or LinkedIn."
}
```

---

## ⚙️ Parameters

| Name             | Type     | Description                                                  |
|------------------|----------|--------------------------------------------------------------|
| `clarity`        | boolean  | Always `true`                                                |
| `structure`      | string   | `"logical"`, `"modular"`                                     |
| `experience`     | int      | `10+ years`                                                  |
| `worksRemotely`  | boolean  | `true`                                                       |
| `tools`          | array    | `["Figma", "Markdown", "Swagger", "Confluence", "Jira"]`     |
| `collaboration`  | string[] | `[Developers, QA, BA, Designers, Product Owners]`            |

---

## 🧪 Example Use Cases

- `GET /style-guide?product=B2B`  
- `GET /release-notes?version=3.4.2`  
- `PATCH /api-docs --optimize-readability`  
- `POST /project?type=SaaS&needs=Documentation+UX+Consistency`  
- `GET /sample?format=PDF`

---

## 🧭 My Process

1. **Kickoff** — выясняю цели, целевую аудиторию и формат.  
2. **Интервью и ресерч** — общаюсь с Dev/QA/PM, изучаю систему.  
3. **Архитектура** — создаю структуру документации, логическую навигацию.  
4. **Пишу** — понятно, без воды, с оглавлением, с примерами.  
5. **Внедряю** — Git, Pages, Wiki, CMS, внутренние порталы.  
6. **Поддерживаю** — обновляю, версионирую, адаптирую под новые релизы.

---

## 📝 Changelog

```
v1.3.5 – Refactored API structure, added new projects  
v1.3.0 – Updated UX writing samples  
v1.2.0 – Added system documentation for multi-role platforms  
v1.0.0 – Initial release  
```

---

## 💬 Fun facts

- 🧠 I’ve mentored designers transitioning into UX writing.  
- 📚 I’ve built documentation from scratch — and saved QA from chaos.  
- 🪄 I speak both design and developer — fluently.  
- 🧩 I love working with structured mess and making it crystal clear.

---

## 📫 Contact

- 📧 `antonina.katskel@example.com`  
- 🔗 [linkedin.com/in/antoninakatskel](https://linkedin.com/in/antoninakatskel)  
- 🗂️ [Portfolio Repositories Below ↓](#)

---

🧭 Built with clarity, tested by QA, approved by devs.
