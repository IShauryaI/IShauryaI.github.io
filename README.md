# Shaurya's Portfolio Website

> **Performance-optimized portfolio showcasing UI/UX engineering, ML/AI development, and full-stack architecture.**

[![Deploy to GitHub Pages](https://github.com/IShauryaI/IShauryaI.github.io/actions/workflows/deploy.yml/badge.svg)](https://github.com/IShauryaI/IShauryaI.github.io/actions/workflows/deploy.yml)
[![Lighthouse Performance](https://img.shields.io/badge/Lighthouse-95+-green?style=flat&logo=lighthouse)
[![Accessibility](https://img.shields.io/badge/Accessibility-WCAG%202.1%20AA-blue?style=flat)]

## 🚀 Features

- **Performance First**: Lighthouse 95+ scores across all metrics
- **Accessibility**: WCAG 2.1 AA compliance with semantic HTML
- **Modern Stack**: Astro + Tailwind CSS + TypeScript
- **Responsive Design**: Mobile-first approach with dark/light themes
- **SEO Optimized**: Structured data, sitemap, and Open Graph meta tags
- **Fast Loading**: Zero-JS by default, optimized images, and efficient bundling

## 🛠️ Tech Stack

**Framework**: [Astro](https://astro.build/) - Zero-JS static site generator  
**Styling**: [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework  
**Language**: [TypeScript](https://www.typescriptlang.org/) - Type-safe JavaScript  
**Icons**: [Lucide](https://lucide.dev/) - Beautiful & consistent icon library  
**Deployment**: [GitHub Pages](https://pages.github.com/) - Automated via GitHub Actions

## 📁 Project Structure

```
/
├── public/                 # Static assets
│   ├── favicon.svg
│   ├── og-image.jpg
│   └── projects/          # Project screenshots
├── src/
│   ├── components/        # Reusable UI components
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── ProjectCard.astro
│   │   └── ThemeToggle.astro
│   ├── layouts/          # Page layouts
│   │   └── Layout.astro
│   ├── pages/            # Route pages
│   │   ├── index.astro   # Homepage
│   │   ├── projects.astro
│   │   ├── about.astro
│   │   └── contact.astro
│   └── styles/          # Global styles
├── astro.config.mjs     # Astro configuration
├── tailwind.config.mjs  # Tailwind configuration
└── package.json
```

## 🚦 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Local Development

```bash
# Clone the repository
git clone https://github.com/IShauryaI/IShauryaI.github.io.git
cd IShauryaI.github.io

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) to view the site.

### Build & Deploy

```bash
# Build for production
npm run build

# Preview production build
npm run preview

# Deploy (automated via GitHub Actions)
git push origin main
```

## ⚡ Performance Targets

| Metric | Target | Current |
|--------|--------|---------|
| Performance | 95+ | ✅ 98 |
| Accessibility | 100 | ✅ 100 |
| Best Practices | 100 | ✅ 100 |
| SEO | 100 | ✅ 100 |

**Core Web Vitals**:
- **LCP** (Largest Contentful Paint): < 1.2s
- **FID** (First Input Delay): < 100ms  
- **CLS** (Cumulative Layout Shift): < 0.1

## 🎨 Design System

**Colors**:
- Primary: `#0ea5e9` (Blue 500)
- Dark: `#111827` (Gray 900)
- Semantic color palette for light/dark themes

**Typography**:
- Primary: Inter (system fallbacks)
- Monospace: JetBrains Mono

**Spacing**: Tailwind's default scale (4px base)
**Breakpoints**: Mobile-first responsive design

## 🔧 Customization

### Adding New Projects
1. Add project images to `public/projects/`
2. Update project data in `src/pages/index.astro`
3. Create detailed project pages in `src/pages/projects/`

### Theme Customization
1. Modify colors in `tailwind.config.mjs`
2. Update CSS custom properties in `src/layouts/Layout.astro`
3. Adjust component styling as needed

### Content Updates
1. Edit page content in respective `.astro` files
2. Update metadata in Layout components
3. Modify navigation in `Header.astro`

## 📈 SEO & Analytics

**Included**:
- Semantic HTML structure
- Open Graph meta tags
- Twitter Card support
- Structured data (JSON-LD)
- XML sitemap generation
- Robots.txt

**Analytics Setup** (Optional):
- Add Plausible/Umami scripts to `Layout.astro`
- Configure privacy-focused analytics
- Implement user consent if required

## 🛡️ Security

- No external tracking by default
- CSP headers recommended for production
- Regular dependency updates via Dependabot
- Secure deployment via GitHub Actions

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/IShauryaI/IShauryaI.github.io/issues).

## 📫 Contact

**Shaurya** - [@IShauryaI](https://github.com/IShauryaI) - shauryapd@gmail.com

Project Link: [https://github.com/IShauryaI/IShauryaI.github.io](https://github.com/IShauryaI/IShauryaI.github.io)

---

⭐ **Star this repository if you found it helpful!**