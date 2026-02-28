# 🖼️ Repo Assets

This folder contains **branding assets** for GitHub repositories, including repo banners, badges, and templates.

---

## 📌 Structure

```text
repo-assets/
├── templates/
│ └── banner.html # HTML source template
├── exports/
│ ├── repo-banner.png # Ready-to-use PNG export
│ └── repo-banner.svg # Ready-to-use SVG export
└── README.md # This file
```


- **`templates/`** → Source files (HTML, Figma, Excalidraw). These are **not embedded directly** in repos.  
- **`exports/`** → Final PNG/SVG files ready for embedding in GitHub READMEs, docs, or dashboards.  

---

## 🛠️ Workflow

### 1. Edit Template
Modify the source in `templates/banner.html`.  
Update:
- **Title** → Repo/project name  
- **Subtitle** → Short description  
- **Code block** → Small snippet (Terraform, Ansible, Nomad, etc.)

### 2. Export Banner
You can export to PNG/SVG via:

**Browser Screenshot (Easy)**
1. Open `banner.html` in Chrome/Firefox.  
2. Capture full page screenshot (1280×360 recommended).  
3. Save as PNG.  

**CLI Export (Automated)**
```bash
# Export PNG from HTML
wkhtmltoimage --width 1280 --height 360 templates/banner.html exports/repo-banner.png
```

Or with Puppeteer:

```bash
node export-banner.js
```

### 3. Use in Repos

Copy from exports/ into your repo’s /assets/ folder.

Embed in README.md:

```bash
![Nomad Cluster Banner](./assets/repo-banner.png)
```
---
### 🎨 Notes

Fonts: Orbitron (title), Inter (subtitle), FiraCode Nerd Font (code).

Colors: Defined in ../colors/palette.md.

Code Snippets: Can be stylized with Ray.so
 for extra polish.

---

### 🚀 Future Ideas

Auto-generate banners via Taskfile (task banner).

Repo-specific variants (e.g., nomad-banner.png, consul-banner.png).

Dark/light mode exports.