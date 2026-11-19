# PopKing Popcorn — Premium Redesign Concept

A visually stunning, high-end redesign concept for PopKing Popcorn (popking.in) — India's premier gourmet popcorn brand since 1996.

## 🎨 Design Philosophy

This redesign transforms the basic Shopify store into an extraordinary, modern, visually immersive experience that positions PopKing as a leading premium D2C food brand. Built with:

- **Bold, playful, energetic** aesthetic
- **Premium but approachable** visual language
- **Visually rich & immersive** with layered imagery
- **Extremely appetising** product presentation
- **Modern, experimental & memorable** interactions

## ✨ Features

### Hero Section
- Massive bold headline: "LET THE GOOD TIMES POP!"
- 3D animated product packaging stack
- Floating popcorn particle system
- Scroll-triggered entrance animations
- Dynamic CTA buttons with micro-interactions

### Product Showcase
- All 17 authentic PopKing flavors with real data
- Category filtering (All / Savoury / Sweet)
- Grid ↔ Carousel view toggle
- Beautiful product cards with hover reveals
- Sold-out states, badges, quick actions
- Flavor personality legend

### Brand Story
- Interactive timeline (1996 → 2024)
- Animated timeline markers
- Core values grid with hover effects
- Glassmorphism cards

### Lifestyle Section
- Mosaic grid of immersive scenes
- Movie night, Party, Work break, Gifting
- Flavor pairing recommendations by occasion
- Shop-by-vibe experience

### CTA Section
- Gradient hero with floating elements
- Featured flavor pills
- Dual CTA (Shop / Subscribe)
- Trust indicators

### Footer
- Complete navigation
- Contact info (verified from source)
- Social links
- Certifications

## 🛠 Tech Stack

- **React 18** + **Vite 5**
- **Tailwind CSS 3.4** (custom design system)
- **Framer Motion 11** (animations)
- **React Scroll** (smooth navigation)
- **ES Modules** (modern build)

## 🎨 Design System

### Colors
```css
--popking-yellow: #F5C000
--popking-yellow-light: #FFE066
--popking-yellow-dark: #D4A000
--popking-cream: #FFF8E7
--popking-cream-dark: #F5E6C8
--popking-red: #C41E3A
--popking-red-light: #E8455D
--popking-red-dark: #9B172E
--popking-charcoal: #1A1A2E
--popking-charcoal-light: #2D2D44
```

### Typography
- **Display**: Space Grotesk (headlines, numbers, CTAs)
- **Body**: DM Sans (body copy, UI)
- **Accent**: Poppins (special accents)

### Animations
- Spring-based transitions (stiffness: 100-300, damping: 10-20)
- Staggered entrance animations
- Hover micro-interactions
- Infinite ambient animations (floating, pulsing, rotating)
- Scroll-triggered reveals

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📁 Project Structure

```
popking-redesign/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Hero.jsx
│   │   ├── ProductShowcase.jsx
│   │   ├── ProductCard.jsx
│   │   ├── BrandStory.jsx
│   │   ├── Lifestyle.jsx
│   │   ├── CTA.jsx
│   │   ├── Footer.jsx
│   │   └── FloatingPopcorn.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
└── README.md
```

## 📸 Assets

All product images use authentic PopKing CDN URLs from `cdn.shopify.com/s/files/1/0798/6538/1174/`. Lifestyle photography sourced from Unsplash (food/lifestyle categories).

## ♿ Accessibility

- Semantic HTML5 structure
- ARIA labels and roles
- Focus-visible states
- Color contrast compliance
- Reduced motion support (via `prefers-reduced-motion`)
- Keyboard navigation

## 📱 Responsive Breakpoints

- Mobile: `< 640px`
- Tablet: `640px - 1024px`
- Desktop: `1024px - 1280px`
- Large: `> 1280px`

## 🎯 Performance

- Lazy-loaded images
- Code-split vendor chunk
- Optimized animations (transform/opacity only)
- Minimal dependencies
- Tree-shaken build

## 📝 License

This is a **design concept/demo** created for portfolio/educational purposes. Not an officially commissioned website for PopKing Popcorn. All brand assets, product data, and imagery belong to PopKing Popcorn.

## 🙏 Credits

- **Original Brand**: PopKing Popcorn (popking.in)
- **Product Data & Images**: Sourced from popking.in
- **Lifestyle Photography**: Unsplash contributors
- **Fonts**: Google Fonts (Space Grotesk, DM Sans, Poppins)
- **Icons**: Custom SVG / Heroicons style

---

Built with ❤️ and lots of popcorn.