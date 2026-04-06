# Contributing to IEEE BUC Exhibition Projects

Thank you for representing the IEEE BUC Student Branch. This guide explains exactly how to submit your exhibition project to this repository.

---

## Before You Start

- You must be an **active IEEE BUC member**
- Your project must have been **presented at an official IEEE BUC Exhibition**
- Each team submits **one folder** per project

---

## Submission Steps

### 1. Fork the Repository

Click **Fork** at the top-right of this page. This creates your own copy.

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/exhibition-projects.git
cd exhibition-projects
```

### 3. Create Your Project Folder

Copy the template into the correct expo year folder:

```bash
cp -r projects/template projects/2025-expo/your-project-name
```

Use **kebab-case** for folder names. Examples:
- `smart-irrigation-system`
- `robotic-arm-control`
- `ai-medical-diagnostics`

### 4. Fill in Your Project

Edit `projects/2025-expo/your-project-name/README.md` using the template.

Add your files:
```
your-project-name/
├── README.md          ← Required
├── src/               ← Your source code
├── hardware/          ← Schematics, CAD, PCB files
├── docs/              ← Report, poster (PDF)
└── media/             ← Photos, screenshots
```

**File size limit:** Keep individual files under **50MB**. For large assets (videos, datasets), use a Google Drive link in your README.

### 5. Commit Your Work

```bash
git add .
git commit -m "feat: add [Project Name] — [Team Name] — 2025 Expo"
git push origin main
```

### 6. Open a Pull Request

- Go to your fork on GitHub
- Click **"Compare & Pull Request"**
- Use the **Project Submission** template
- Tag the Technical Director for review

---

## Review Process

| Step | Responsible | Timeline |
|------|------------|---------|
| PR Submitted | Team | — |
| Initial Review | Vice Technical Director | 2–3 days |
| Merge Approval | Technical Director | 1–2 days |
| Published | Maintainers | Same day |

---

## File Naming Conventions

| Type | Convention | Example |
|------|-----------|---------|
| Project folder | kebab-case | `smart-farm-monitor` |
| Source files | snake_case | `main_controller.py` |
| Documentation | Title Case | `Technical_Report.pdf` |
| Media | descriptive | `demo_overview.jpg` |

---

## What NOT to Include

- API keys, passwords, or credentials (use `.env.example`)
- Large binary files over 50MB
- Copyrighted materials without permission
- Unrelated personal files

---

## Questions?

Open an [Issue](../../issues) with the `question` label, or reach out to the IEEE BUC Technical Committee directly.

---

*IEEE BUC Student Branch — Badr University in Cairo*
