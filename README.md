# DukeX Web Templates

8 production-ready HTML/CSS/JS web templates. No frameworks, no build tools — open in VS Code and go.

**License:** MIT · **Stack:** HTML5 / CSS3 / Vanilla JS · **Requirements:** VS Code + Live Server

---

## Quick Start

1. Clone the repo: `git clone https://github.com/yourname/dukex-web-templates`
2. Open any project folder in VS Code
3. Install the **Live Server** extension (by Ritwick Dey)
4. Right-click `index.html` → **Open with Live Server**
5. Visit `http://127.0.0.1:5500`

---

## Templates

| # | Template | Description |
|---|----------|-------------|
| 1 | [Portfolio](#1-dukex--responsive-portfolio) | Personal portfolio with editorial ink-and-cream aesthetic |
| 2 | [Business Landing](#2-dukex--business-landing-page) | Dark-mode SaaS landing page with pricing |
| 3 | [E-Commerce](#3-dukex--e-commerce-demo) | Luxury home goods store with cart sidebar |
| 4 | [Blog](#4-dukex--blog-platform) | Newspaper-style editorial blog |
| 5 | [Restaurant](#5-dukex--restaurant-website) | Dark, fire-lit restaurant site with reservations |
| 6 | [Real Estate](#6-dukex--real-estate-showcase) | Premium property listings with search |
| 7 | [Admin Dashboard](#7-dukex--admin-dashboard) | Dark-mode analytics dashboard with charts |
| 8 | [API Demo](#8-dukex--api-integration-demo) | Live API integration demo |

---

## File Structure

```
dukex-web-templates/
├── 1-portfolio/
│   ├── index.html
│   └── README.md
├── 2-business-landing/
│   ├── index.html
│   └── README.md
├── 3-ecommerce/
│   ├── index.html
│   └── README.md
├── 4-blog/
│   ├── index.html
│   └── README.md
├── 5-restaurant/
│   ├── index.html
│   └── README.md
├── 6-real-estate/
│   ├── index.html
│   └── README.md
├── 7-admin-dashboard/
│   ├── index.html
│   └── README.md
├── 8-api-demo/
│   ├── index.html
│   └── README.md
├── README.md   ← You are here
└── LICENSE
```

---

## 1. DukeX — Responsive Portfolio

A refined, editorial-style personal portfolio for DukeX with an ink-and-cream aesthetic.

### Features
- Fixed navigation with blend-mode effect
- Split-screen hero section
- Scroll-triggered fade-up animations (IntersectionObserver)
- Filterable project grid with hover overlays
- Contact form (front-end only)
- Fully responsive (mobile, tablet, desktop)

### Customise
| What | Where |
|------|-------|
| Name & bio | `index.html` — `.hero-name`, `.hero-bio` (set to DukeX) |
| Skills | `.skills-grid` section |
| Projects | `.projects-grid` cards |
| Colors | `:root` CSS variables at top of `<style>` |
| Fonts | Google Fonts `<link>` tag |

### Tech Stack
- Google Fonts — Playfair Display + DM Mono

---

## 2. DukeX — Business Landing Page

A dark-mode SaaS landing page for DukeX — a growth intelligence platform.

### Features
- Fixed glass-morphism navbar
- Gradient hero with animated badge
- Stats bar and logo trust section
- 3-column feature grid
- 3-tier pricing cards with featured state
- CTA section
- Responsive (mobile collapses to 1 column)

### Customise
| What | Where |
|------|-------|
| Brand name | `.logo` in nav — replace with DukeX |
| Hero headline | `h1` in `.hero` |
| Feature cards | `.features-grid` cards |
| Pricing | `.pricing-grid` cards |
| Colors | `:root` CSS variables |

### Tech Stack
- Google Fonts — Syne + Instrument Sans

---

## 3. DukeX — E-Commerce Demo

DukeX e-commerce demo — a luxury home goods store with a warm editorial aesthetic.

### Features
- Promo top bar
- Sticky navigation with cart icon and badge
- Hero banner split layout
- Dynamic product grid (JS-rendered from data array)
- Sliding cart sidebar with overlay
- Hover product actions (Add to basket / Wishlist)
- Sale price display and multi-column footer
- Fully responsive

### Customise
| What | Where |
|------|-------|
| Products | `products` array in `<script>` |
| Hero text | `.hero-content` section |
| Brand name | `.nav-brand` and `.footer-brand` — set to DukeX |
| Colors | `:root` CSS variables |
| Promo bar text | `.top-bar` div |

### Extend with a Backend
- Connect to **Stripe** for real payments
- Use **Supabase** or **Firebase** for product data
- Add **Next.js** + **Shopify Storefront API** for full e-commerce

### Tech Stack
- Google Fonts — Cormorant Garamond + Jost

---

## 4. DukeX — Blog Platform

DukeX blog platform — a newspaper-style editorial blog with a classic typographic aesthetic.

### Features
- Traditional masthead with date line and double-rule borders
- Category navigation bar
- Lead story with large image
- 2-column article grid and numbered article list
- Sidebar with newsletter signup, most-read, and topic tags
- Fully responsive (stacks on mobile)

### Customise
| What | Where |
|------|-------|
| Publication name | `.masthead-title` and `footer .footer-title` — set to DukeX |
| Nav categories | `<nav>` links |
| Lead article | `.lead-story` |
| Grid articles | `.articles-grid` cards |
| Sidebar articles | `.sidebar-item` elements |

### Extend to a Real Blog
- Use **Jekyll** or **Hugo** for static site generation
- Use **Ghost CMS** for a full blog backend
- Use **Next.js + MDX** for a React-based blog with markdown

### Tech Stack
- Google Fonts — Libre Baskerville + Source Sans 3

---

## 5. DukeX — Restaurant Website

DukeX restaurant website — a dark, fire-lit site for a modern African kitchen in Nairobi.

### Features
- Gradient hero with animated scroll indicator
- Brand story two-column section
- Tabbed menu section (JS-rendered)
- Reservation form with date/time/party picker
- Opening hours table and social links footer
- Fully responsive

### Customise
| What | Where |
|------|-------|
| Restaurant name | `.nav-logo`, `footer`, `<title>` — set to DukeX |
| Menu items | `starters` array in `<script>` |
| Opening hours | `.hours` section |
| Location | address `<p>` in `.reserve-info` |
| Colors | `:root` CSS variables |

### Extend
- Connect reservation form to **OpenTable API** or **Resy**
- Use **EmailJS** to send confirmation emails
- Add a photo gallery section with lightbox

### Tech Stack
- Google Fonts — Spectral + Space Grotesk

---

## 6. DukeX — Real Estate Showcase

DukeX real estate showcase — a premium property listing site localised for Nairobi, Kenya.

### Features
- Sticky navigation
- Hero with integrated property search bar and quick-filter tags
- Dynamic property listing grid (JS-rendered)
- Featured property "of the month" full-width banner
- Agent showcase grid and multi-column footer
- Fully responsive

### Customise
| What | Where |
|------|-------|
| Properties | `properties` array in `<script>` |
| Featured property | `.large-feature` section |
| Agents | `.agents-grid` cards |
| Location filters | `.hero-tags` buttons |
| Currency/locale | price strings in `properties` array |

### Extend
- Integrate **Google Maps API** for property location pins
- Connect to a property database (Supabase / Firebase)
- Add a filter sidebar with price range slider

### Tech Stack
- Google Fonts — Fraunces + Inter

---

## 7. DukeX — Admin Dashboard

DukeX admin dashboard — a dark-mode analytics dashboard with sidebar navigation, stat cards, charts, data tables, and activity feeds.

### Preview
```
┌─────────────┬──────────────────────────────────────────────┐
│  ⬡ DukeX  │  Dashboard                    🔍  🔔  🌙     │
├─────────────┼──────────────────────────────────────────────┤
│  ◉ Dashboard│  [ 7D ] [ 30D ] [ 90D ] [ 1Y ]              │
│  📊 Analytics│                                             │
│  👥 Users   │  $84,230   12,840   3,461   4.2%            │
│  📦 Products│  Revenue   Users    Orders  Conv.Rate        │
│  🛒 Orders  │                                              │
│  ─────────  │  ┌─ Revenue Chart ──┐  ┌─ Traffic Sources ─┐│
│  💳 Payments│  │  Bar Chart       │  │  Donut Chart       ││
│  📈 Revenue │  └──────────────────┘  └────────────────────┘│
│  🧾 Invoices│                                              │
│  ─────────  │  ┌─ Recent Orders ────────────────────────┐ │
│  ⚙️ Settings│  │  #ORD | Customer | Product | Status... │ │
│  🔒 Security│  └────────────────────────────────────────┘ │
│  AO Admin   │  ┌─ Activity ───┐  ┌─ Top Products ───────┐ │
└─────────────┴──┴─────────────┴──┴──────────────────────-┘ │
```

### Features
- **Fixed sidebar** with grouped navigation, active state, and user info panel
- **Sticky topbar** with search bar, notification bell, and dark mode toggle
- **4 stat cards** — Revenue, Users, Orders, Conversion Rate with % change
- **Bar chart** — 12-month revenue overview (pure CSS + JS)
- **Donut chart** — Traffic source breakdown (pure SVG)
- **Data table** — Recent orders with colour-coded status badges
- **Date range filter** — 7D / 30D / 90D / 1Y toggle
- **Activity feed** — Real-time event log with icons and timestamps
- **Top products** — Horizontal progress bars per product
- **Responsive** — Sidebar collapses to icon-only on mobile

### Customise
| What | Where |
|------|-------|
| Brand name | `.sidebar-brand` → `<span>DukeX</span>` |
| Chart data | `months` and `data` arrays in `<script>` |
| Orders table | `orders` array in `<script>` |
| Activity feed | `activities` array in `<script>` |
| Colors | `:root` CSS variables |

### Responsive Behaviour
| Screen Width | Layout |
|---|---|
| > 1100px | Full layout — 4 stat cards, 2-column charts |
| 768px–1100px | 2 stat cards per row, charts stack vertically |
| < 768px | Sidebar collapses to icon-only (60px), search hidden |

### Extend with Real Data
```js
async function loadOrders() {
  const res  = await fetch('https://your-api.com/orders');
  const data = await res.json();
  // render table rows...
}
loadOrders();
```

### Recommended Backend Pairings
| Need | Tool |
|------|------|
| Simple database | Supabase (free tier) |
| Authentication | Firebase Auth / Supabase Auth |
| Real-time updates | Supabase Realtime / Socket.io |
| Charts library | Chart.js / Recharts (React) |
| Full framework | Next.js + Tailwind + Shadcn/ui |

### Tech Stack
- Google Fonts — Geist + Geist Mono
- SVG donut chart — no library required

---

## 8. DukeX — API Integration Demo

DukeX API integration demo — live API calls with fetch, dynamic rendering, loading states, and error handling.

### Features
- Fetch data from a public REST API
- Loading spinner and error state UI
- Dynamic card rendering from JSON response
- Search and filter controls
- Fully responsive

### Customise
| What | Where |
|------|-------|
| API endpoint | `fetch()` call in `<script>` |
| Card layout | `.card` elements in render function |
| Colors | `:root` CSS variables |

---

## Global Tech Stack

Every template uses:

- **HTML5** — semantic markup
- **CSS3** — custom properties, grid, flexbox, transitions
- **Vanilla JavaScript** — no jQuery, no frameworks
- **Google Fonts** — each template has its own font pairing
- **No build tools** — no npm, no webpack, no compilation step

---

## License

MIT © 2026 DukeX — free to use in personal and commercial projects. Keep the copyright notice in the code.
