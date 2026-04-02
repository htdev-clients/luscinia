# Luscinia Eco-jardin — Website

> **Work in progress** — the site is currently in development.

Brochure website for **Luscinia**, a Belgian eco-gardening and biodiversity consultancy operating in Wallonia and Brussels. The client helps homeowners rewild their gardens and restore local biodiversity through design, planting, and naturalist follow-up services.

## Tech Stack

| Tool | Role |
|---|---|
| [Jekyll](https://jekyllrb.com/) | Static site generator |
| [Tailwind CSS](https://tailwindcss.com/) (CDN) | Utility-first styling |
| [Lucide Icons](https://lucide.dev/) | UI iconography |
| Google Fonts — Lato & Playfair Display | Typography |
| GitHub Pages | Hosting & deployment |

## Pages

- **Accueil** — Hero section, mission statement, key values
- **Services** — Three core offerings: design & creation, naturalist follow-up, gentle maintenance coaching
- **Réalisations** — Portfolio grid of completed projects
- **Philosophie** — Brand values and ecological impact
- **Contact** — Contact details and inquiry form (Formspree-ready)

## Notable Features

- **Custom Tailwind theme** — Earth-tone palette (`earth-dark`, `sage`, `clay`, `sand`, `loam`) configured via `tailwind.config`
- **Jekyll includes** — Navbar and footer extracted into `_includes/` for DRY templating
- **Active nav highlighting** — JavaScript resolves the current path against `site.baseurl` to apply an animated underline to the active link
- **Responsive portfolio grid** — Hover reveals an overlay with title and description; on mobile the overlay is always visible
- **Page entry animation** — CSS `fadeInUp` keyframe applied site-wide via the default layout
- **Static contact form** — Form is UI-complete; email handling will be implemented via [Resend](https://resend.com/) once the site migrates to Cloudflare Pages
- **SVG social icons** — Custom SVG assets served locally rather than via an icon font CDN
