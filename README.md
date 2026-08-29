# Portfolio Demos — Three Professional Web Concepts

Three independent, fully self-contained web demos built with modern HTML, CSS, and vanilla JavaScript. Conceptual portfolio projects demonstrating front-end design and development capabilities. No frameworks, no backend, no dependencies.

## Project Structure

```
portfolio-demos/
├── demo-01-nexus/         # Tech/AI project showcase
├── demo-02-restaurant/    # Restaurant brand website
└── demo-03-studio/        # Creative studio portfolio
```

---

## Demo 01: Nexus — AI Automation Platform

**Tech/AI project showcase** — Futuristic, dark-themed landing page for an artificial intelligence automation platform.

- **Technologies**: HTML5, CSS3, vanilla JavaScript (Canvas particles)
- **Key Features**:
  - Hero with interactive particle network animation (Canvas API)
  - Features grid with 3 distinct capability cards (AI, Automation, Dev Tools)
  - Capabilities progress bars (Software, Infrastructure, Data Science, QA)
  - Projects showcase with 3 conceptual projects using real photography
  - Technology stack display
  - Vision timeline (2024–2026)
  - Smooth scroll navigation with active section highlighting
  - Mobile-responsive menu
  - Scroll-reveal animations (IntersectionObserver)
  - Accessible focus states
- **Design**: Dark minimalist, tech/futuristic aesthetic, mint green accent (#5ee2a8), modern sans-serif (Inter), subtle gradients, glassmorphism cards
- **Breakpoints**: 1920px, 1366px, 768px (tablet), 375px (mobile)

---

## Demo 02: Ember — Wood-Fired Restaurant

**Restaurant brand website** — Premium warm-themed restaurant focusing on wood-fired cuisine.

- **Technologies**: HTML5, CSS3, vanilla JavaScript
- **Key Features**:
  - Hero with real restaurant interior photography and parallax effect
  - Restaurant history timeline (2018–2024)
  - 4 signature dishes with name, description, and price
  - Full menu categorized (Entrantes, Principales, Brasa, Postres, Bebidas)
  - Gallery with 6 real food/restaurant photographs
  - Location section with Google Maps link and map mockup
  - Reservation CTA throughout
  - Smooth scroll navigation
  - Mobile-responsive menu
  - Scroll-reveal animations
- **Design**: Warm editorial aesthetic, amber/gold accent (#d4a753), serif typography (Playfair Display), rich composition, food photography as protagonist
- **Breakpoints**: 1920px, 1366px, 768px, 375px

---

## Demo 03: Noir Studio — Creative Studio

**Creative studio portfolio** — Editorial, black/white/grey studio with subtle accent color.

- **Technologies**: HTML5, CSS3, vanilla JavaScript
- **Key Features**:
  - Hero with full-bleed studio photography background
  - About section with statistics (12+ projects, 8 industries, 5+ years)
  - Services grid (Photography, Branding, Creative Direction, Video Production)
  - Selected work gallery with 6 projects, each with unique photography
  - Creative process steps (Discovery → Concept → Production → Delivery)
  - Studio space gallery (4 images)
  - Client testimonials with real portrait photography
  - Contact section
  - Parallax scroll effects
  - Mobile-responsive menu
  - Scroll-reveal animations
- **Design**: Minimalist editorial, black/white/grey palette with beige accent (#9b8c6a), large typography, asymmetric layouts, high contrast
- **Breakpoints**: 1920px, 1366px, 768px, 375px

---

## Common Features (All Three Demos)

- Responsive design for desktop, tablet, and mobile
- Smooth scroll navigation with active section highlighting
- Hover states and microinteractions
- Scroll-reveal animations (IntersectionObserver)
- Accessible HTML structure (semantic tags, ARIA where needed)
- Favicon (SVG) and meta tags (description, viewport)
- **No external dependencies** — vanilla JS only, no frameworks
- **No lorem ipsum** — original professional content
- **No backend requirements** — fully frontend demos
- Commercial-use free stock photography (Pexels, CC0 license)

## How to Run

Each demo is standalone. Open any `index.html` file in a browser:

```bash
# From the portfolio-demos directory
open demo-01-nexus/index.html
open demo-02-restaurant/index.html
open demo-03-studio/index.html
```

Or serve locally with a simple HTTP server:

```bash
cd portfolio-demos
python3 -m http.server 8000
# Then visit http://localhost:8000/demo-01-nexus/
```

## Images

All images sourced from **Pexels** under **CC0 / Free to Use** license (commercial use allowed, no attribution required). Image files located in each project's `assets/images/` folder.

## Design Priorities

1. **Visual Quality** — Custom graphics, typography, composition
2. **UX** — Intuitive navigation, smooth interactions, clear hierarchy
3. **Responsive** — Perfect display at 1920×1080, 1366×768, tablet, and mobile
4. **Clean Code** — Maintainable HTML/CSS/JS structure
5. **Performance** — Minimal scripts, no render-blocking resources
6. **Accessibility** — Semantic HTML, color contrast, keyboard navigation

## Important Notes

- **These are conceptual/demo projects** for portfolio purposes
- All names, brands, projects, and content are fictional and original
- No client work is represented as real
- Images are free for commercial use (Pexels CC0)
- No external libraries or frameworks are used
- Each demo is fully self-contained and can be deployed independently

## License

MIT