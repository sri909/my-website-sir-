it-nanbargal-website/
│
├── index.html
│ → Main visiting-card website (hero, trust, CTA, app redirection)
│
├── privacy-policy.html
│ → Privacy Policy page (matches mobile app policy)
│
├── terms-and-conditions.html
│ → Terms & Conditions page
│
├── README.md
│ → Project documentation & structure reference
│
├── css/
│ │
│ ├── base.css
│ │ → CSS reset, root variables, fonts, color system
│ │
│ ├── layout.css
│ │ → Section layout, grids, spacing, page structure
│ │
│ ├── components.css
│ │ → UI components (cards, buttons, badges, CTA)
│ │
│ ├── animations.css
│ │ → All animation & motion rules (scroll, hover, reveal)
│ │
│ └── responsive.css
│ → Mobile-first responsiveness & breakpoints
│
├── js/
│ │
│ ├── main.js
│ │ → Entry point: initializes scroll engine & UI components
│ │
│ ├── utils/
│ │ │
│ │ ├── raf.js
│ │ │ → requestAnimationFrame helper for smooth motion
│ │ │
│ │ └── clamp.js
│ │ → Utility to limit values (used in velocity & motion)
│ │
│ ├── core/
│ │ │
│ │ ├── velocity.js
│ │ │ → Detects scroll speed & user intent
│ │ │
│ │ ├── section-lock.js
│ │ │ → Locks / unlocks sections during scroll animations
│ │ │
│ │ └── scroll-engine.js
│ │ → Scroll-as-timeline engine (core system logic)
│ │
│ └── components/
│ │
│ ├── reveal-text.js
│ │ → Intent-aware text reveal animations
│ │
│ ├── magnetic-cards.js
│ │ → Cursor gravity / magnetic hover effect
│ │
│ ├── edge-light.js
│ │ → Edge glow & light interaction effects
│ │
│ ├── depth-cards.js
│ │ → Parallax depth illusion for cards
│ │
│ └── cta-breathing.js
│ → Subtle breathing animation for CTA buttons
cards
index.html
logo.png
