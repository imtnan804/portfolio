# Imtnan Khawar Maan — Developer Portfolio

Production-ready, high-performance portfolio website for **Imtnan Khawar Maan**, Full-Stack & Mobile Application Developer specializing in web platforms, mobile apps, and IoT hardware integration.

---

## ⚡ Tech Stack & Architecture

- **Framework**: React 19 + TypeScript + Vite
- **Styling**: Tailwind CSS v4 + Custom Glassmorphism System
- **Icons**: Lucide React
- **Typography**: Outfit (Headings), Plus Jakarta Sans (Body), JetBrains Mono (Code / Tabular Numerals)
- **State & Theme**: Custom React Context with LocalStorage persistence (Dark mode default with Light toggle)
- **SEO & Social**: OpenGraph, Twitter Cards, Semantic HTML5, Schema.org `Person` JSON-LD structured data, Sitemap, and Robots.txt.

---

## 📂 Project Architecture & Data Configuration

All portfolio content is decoupled into strongly-typed TypeScript configuration files for frictionless updates:

```
├── /public
│   ├── cv.pdf               # Downloadable resume file
│   ├── robots.txt           # Crawler instructions
│   └── sitemap.xml          # Search engine sitemap
├── /src
│   ├── /assets/images       # High-fidelity project showcase imagery
│   ├── /components
│   │   ├── Navbar.tsx       # 3-Zone Top Bar with active section spy & mobile drawer
│   │   ├── Hero.tsx         # Typing headline animation & live IoT simulator
│   │   ├── About.tsx        # Profile summary, academic snapshot & 4-column KPI strip
│   │   ├── Skills.tsx       # Categorized toolkit with interactive filter tabs
│   │   ├── Projects.tsx     # Featured capstone spotlight + 2/3-col project grid
│   │   ├── ProjectModal.tsx # Fullscreen modal with architecture notes & live simulator
│   │   ├── Education.tsx    # Academic timeline card (BS Computer Science, BGNU)
│   │   ├── Contact.tsx      # Validated message form & one-click clipboard copy
│   │   ├── CVModal.tsx      # Printable / copyable text resume modal
│   │   └── Footer.tsx       # Back-to-top button & quick links
│   ├── /context
│   │   └── ThemeContext.tsx # Dark / light mode state provider
│   ├── /data
│   │   ├── site.ts          # Core profile, contacts, statistics, and education info
│   │   ├── skills.ts        # Languages, mobile, web, IoT, and backend skill taxonomies
│   │   └── projects.ts      # Structured projects data, tech stacks, and metrics
│   ├── App.tsx              # Single-page section assembler
│   ├── index.css            # Tailwind theme, typography tokens & glass surfaces
│   └── main.tsx             # DOM entry point
└── README.md                # Deployment and setup guide
```

---

## 🚀 Local Development Setup

1. **Clone & Install Dependencies**:
   ```bash
   npm install
   ```

2. **Start Development Server**:
   ```bash
   npm run dev
   ```
   Open `http://localhost:3000` in your browser.

3. **Production Build & Verification**:
   ```bash
   npm run build
   ```

---

## 🌐 Vercel Deployment Instructions

### Method 1: Deploy with Vercel Web Dashboard (Recommended)

1. Push this repository to GitHub or GitLab.
2. Navigate to [vercel.com/new](https://vercel.com/new).
3. Import the repository.
4. Select **Vite** as the Framework Preset (Vercel automatically detects Vite):
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
   - **Install Command**: `npm install`
5. Click **Deploy**. Your portfolio will be live in under 60 seconds with automatic HTTPS and edge CDN caching.

### Method 2: Deploy using Vercel CLI

```bash
# 1. Install Vercel CLI globally
npm i -g vercel

# 2. Login to your Vercel account
vercel login

# 3. Deploy to production
vercel --prod
```

---

## 🎯 Lighthouse 90+ & Accessibility Checklist

- [x] **Zero Broken Images**: Resilient image fallbacks with styled SVG gradient containers.
- [x] **Tabular Numerals**: All metrics aligned with `font-mono tabular-nums`.
- [x] **Single-Line Controls**: `whitespace-nowrap shrink-0` across all badges, tags, and tabs.
- [x] **No AI Slop**: Clean unboxed metadata with `·` separators; no `//` code comment headers, no fake telemetry tickers, no arbitrary scorecards.
- [x] **Keyboard Navigation & ARIA**: Escape key listeners on modals, aria labels on icon buttons, visible focus rings.
- [x] **Semantic Schema**: `Person` JSON-LD schema with education, contacts, and skill ontology.

---

## 📝 Contact Information

- **Developer**: Imtnan Khawar Maan
- **Email**: [kingmaan2004@gmail.com](mailto:kingmaan2004@gmail.com)
- **Phone**: `0325 4733410` (+92 325 4733410)
- **Location**: Nankana Sahib, Pakistan
