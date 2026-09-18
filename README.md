# App Enterprises

Five static websites for the App Enterprises family of businesses.

## Sites & domains

- `landing/` — "Dispatch Board" hub page → **app-enterprises.com**. Real design, links to the 4 businesses below.
- `pressure-washing/` — Home, Gallery, Contact → **app-pressurewashing.com**
- `sales-consignments-rentals/` — Home, Sales (with subtabs for each represented brand), Consignments, Rentals, Contact → **app-salesrentals.com**
- `customs/` — Home, Metal Fab, Audio, Contact → **app-customs.com**
- `app-luxe/` — Home, Gallery, Contact → **app-luxe.com**. Marketing company (brand strategy, campaigns, content).

Each site is plain HTML/CSS/JS with no build step. In this repo they live as sibling folders, but each is meant to be deployed to the root of its own domain above — so cross-site links use the full domain (e.g. the footer "App Enterprises" link points at `https://app-enterprises.com`, not a relative path), while links *within* a site stay relative.

## Status

- All 5 sites now use the **real, unified logo set** (`<site>/assets/logo.png`) — gunmetal + bronze/copper, shared across every business instead of each having its own distinct color. This replaced an earlier logo/palette set where each business had a different accent color (blue/bronze/red/gold).
- All 5 sites' color palettes (`styles.css` `:root` variables) were updated to match: `--bg: #0a0c0d`, `--surface: #1b2020`, `--accent: #B87840` (bronze), `--accent-dark: #8A5A28`, `--text: #f2f4f3`, `--muted: #9aa3a3`, `--border: #313737`.
- The landing page keeps its original "Dispatch Board" design/structure as provided, with only its logo image and accent color (`--amber`) updated to match the new bronze, and a 4th bay added for App Luxe.
- All 4 business sites still use placeholder body copy, sample "brand" tabs on the Sales page (currently "Brand One/Two/Three"), and placeholder photo tiles (dashed boxes) instead of real photos.

Upholstery & Refurbishment has been dropped as a Customs service line (confirmed) — its page and nav link were removed, and Customs is now down to 4 pages: Home, Metal Fab, Audio, Contact.

**Still needed:**

1. Real business names/copy, contact info, and photos for each site.
2. Actual names of the brands represented on the Sales page.
