# 🚀 Homelab Branding Kit

This repository contains the **branding system** for all homelab and IaC projects.  
It provides consistency, saves time, and ensures every repo shares a recognizable identity.

---

## 🎯 Purpose
A centralized, lightweight design kit for:
- Logos and icons  
- Color palettes and fonts  
- Repo banners and badges  
- Diagrams and templates  

Stop hunting for SVGs — build once, reuse everywhere.

---

## ✅ Coverage
With this kit, you now cover:
- **Logos** → Orbitron  
- **Fonts** → Inter (UI) + FiraCode Nerd Font (code)  
- **Colors** → `colors/palette.md`  
- **Repo Banners** → Figma/Excalidraw templates  
- **Code-as-Design** → Ray.so snippets  

---

## 📦 Repo Structure

```text
branding-kit/
├── logos/
│ ├── homelab-logo.svg
│ ├── homelab-logo-dark.png
│ └── favicon.ico
├── colors/
│ └── palette.md # HEX/RGB values + usage notes
├── typography/
│ └── fonts.md # Links + usage rules
├── icons/
│ ├── service-icons/
│ └── ui-icons/
├── repo-assets/
│ ├── repo-banner-template.fig
│ └── badges/
├── diagrams/
│ ├── template.fig
│ └── sample-architecture.png
└── README.md # This file
```

---

## 🖼️ Core Components

### 1. Logos
- **Primary Logo** (SVG, PNG)
- **Variants**: light/dark, wordmark, simplified icon
- Export formats: SVG (scalable), PNG (docs), ICO (dashboards)

### 2. Color Palette
- **Primary colors**: `#000000`, `#FFFFFF`, `#FF00FF` _(replace with yours)_
- **Secondary colors**: shades + neutrals
- Define usage rules: headers, accents, backgrounds

### 3. Typography
- **Primary font**: [Insert font name + link]
- **Secondary font (optional)**: monospace/code
- Open-source (Google Fonts recommended)

### 4. Iconography
- Consistent style (line, filled, pixel — choose one)
- Saved here for reuse across repos
- Sources: Figma Community, Feather, Material Icons, etc.

### 5. Repo Assets
- **Repo banner template**: 1280×640 or 1920×1080
- **Badges**: custom shields.io style
- **README embeds**: logos + consistent color accents

### 6. Diagram Templates
- Architecture + cluster diagrams
- Flowcharts and workflows
- Export: SVG for docs, PNG for GitHub READMEs

---

## ⚡ Usage Guidelines
- **Consistency over perfection**: stick to palette + logo even if simple  
- **Automation-friendly**: keep exports in predictable folders  
- **Lightweight**: embed only what’s needed in each repo  

---

## 🛠️ Tools
- **Design Hub**: Figma (preferred), Canva, or Excalidraw  
- **Idea Generation**: AI tools for logos/icons (refine in Figma)  
- **Source of Truth**: This repo  

---

## 🔮 Roadmap
- Repo-specific logo variants (e.g., `nomad-cluster-logo.svg`)  
- Dark/light diagram sets  
- Auto-generated shields.io badges from palette  
- Integration with docs site (Bookstack, MkDocs, etc.)  

---

## ✅ Next Steps
1. Define your **core palette** (`colors/palette.md`).  
2. Pick your **primary logo** and add it to `/logos/`.  
3. Decide on **fonts** and document in `/typography/fonts.md`.  
4. Start a **diagram template** in `/diagrams/`.  
5. Generate your first **Ray.so snippet** and save under `/code-snippets/examples/`.  
6. Export and embed a **repo banner** in one of your active repos.  
7. Document this workflow in `/repo-assets/README.md` for repeatability.  
