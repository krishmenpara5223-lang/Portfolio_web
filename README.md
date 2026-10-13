# Krish Menpara — Premium Light-Themed Portfolio

A classic, elegant, modern light-themed portfolio website built for **Krish Menpara**, Computer Engineering student at V.V.P. Engineering College, Rajkot (Gujarat Technological University).

Designed with Apple-inspired minimalism, modern technology startup aesthetics, refined editorial typography, and fluid motion animations.

---

## 🎨 Color Palette & Design System

- **Main Background**: `#FAFAF7` (Warm White)
- **Secondary Background**: `#F3F0E8` (Soft Ivory)
- **Primary Text**: `#202124` (Charcoal)
- **Secondary Text**: `#666B73` (Muted Gray)
- **Primary Accent**: `#3157D5` (Elegant Royal Blue)
- **Secondary Accent**: `#DCE8FF` (Soft Sky Blue)
- **Supporting Accent**: `#E9E2FF` (Muted Lavender)
- **Borders**: `#E7E7E3` (Subtle Light Gray)
- **Typography**: Plus Jakarta Sans (Headings) & Inter (Body)

---

## 🚀 Getting Started

Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

### 1. Install Dependencies
```bash
npm install
```

### 2. Start the Development Server
```bash
npm run dev
```
Open your browser and navigate to `http://localhost:5173`.

### 3. Build for Production
```bash
npm run build
```
The optimized production output will be generated inside the `dist/` directory.

### 4. Preview the Production Build
```bash
npm run preview
```

> **Note for Windows PowerShell users:** If PowerShell reports execution policy restrictions when running `npm`, run commands using `cmd.exe /c "npm run dev"` or execute `Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass` in your terminal session.

---

## 📂 Project Architecture

```
Portfolio/
├── index.html                   # HTML entry point with fonts & metadata
├── vite.config.ts               # Vite configuration with Tailwind CSS plugin
├── package.json                 # Project scripts and dependencies
├── src/
│   ├── main.tsx                 # React entry mount
│   ├── App.tsx                  # Main single-page application orchestrator
│   ├── index.css                # Tailwind CSS v4 styling & theme tokens
│   ├── data/
│   │   └── portfolioData.ts     # ⭐️ Single source of truth for all personal info,
│   │                            #    projects, skills, education, and achievements
│   └── components/
│       ├── Navbar.tsx           # Sticky nav with progress bar & active indicator
│       ├── Hero.tsx             # Two-column hero with layered 3D aesthetic
│       ├── About.tsx            # Personal story & verified academic data
│       ├── Skills.tsx           # Categorized cards & tags (no fake bars)
│       ├── Projects.tsx         # Filterable gallery, placeholders & details modal
│       ├── Education.tsx        # Vertical timeline with V.V.P. & GTU details
│       ├── Achievements.tsx     # Udemy course, Data Mining paper, quiz & event
│       ├── Interests.tsx        # Curiosity in software, web, DSA, emerging tech
│       ├── Contact.tsx          # Direct email, phone, location & validated form
│       ├── Footer.tsx           # Minimal footer with dynamic year & back-to-top
│       └── Icons.tsx            # Precise GitHub & LinkedIn SVG brand icons
```

---

## ✏️ How to Edit Your Details & Add Real Projects

All your personal information, links, and projects are centralized in one file:
👉 **`src/data/portfolioData.ts`**

- **Personal Information**: Change email, phone number, LinkedIn, GitHub, or career objective.
- **Projects**: Update `PROJECTS_DATA` with your real GitHub repositories, live demo URLs, screenshots, and descriptions.
- **Achievements & Certifications**: Update `ACHIEVEMENTS_DATA` to add new courses, certificates, or hackathons.
- **Skills**: Add or adjust programming languages and frameworks under `SKILL_CATEGORIES`.

---

## 🛡️ Key Features

- **Light-Themed Elegance**: Warm ivory and white backgrounds with royal blue and soft pastel highlights. No dark theme, neon, or cyberpunk clutter.
- **Verified Academic Data**: Accurately displays CPI (8.68/10), B.E. Computer Engineering at V.V.P. Engineering College (GTU, 2024–2028).
- **Interactive Experience**: Scroll progress indicator, smooth active-section indicator, category filters, interactive modals, and validated contact form with email client dispatch.
- **Accessibility & Reduced Motion**: Fluid animations with responsive performance across mobile, tablet, laptop, and 4K displays.
