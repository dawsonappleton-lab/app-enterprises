# App Enterprises

Four static websites for the App Enterprises family of businesses.

## Sites & domains

- `landing/` — "Dispatch Board" hub page → **app-enterprises.com**. Real design, links to the 3 businesses below.
- `pressure-washing/` — Home, Gallery, Contact → **app-pressurewashing.com**
- `sales-consignments-rentals/` — Home, Sales (with subtabs for each represented brand), Consignments, Rentals, Contact → **app-salesrentals.com**
- `customs/` — Home, Audio, Metal Fab, Upholstery & Refurbishment, Contact → **app-customs.com**

Each site is plain HTML/CSS/JS with no build step. In this repo they live as sibling folders, but each is meant to be deployed to the root of its own domain above — so cross-site links use the full domain (e.g. the footer "App Enterprises" link points at `https://app-enterprises.com`, not a relative path), while links *within* a site stay relative.

## Status

- `landing/` uses the real design and copy you provided, wired up to the real domains.
- `pressure-washing/`, `sales-consignments-rentals/`, and `customs/` still use placeholder content:
  - Placeholder business names, copy, and sample "brand" tabs on the Sales page (currently "Brand One/Two/Three").
  - Placeholder color palettes (blue for pressure washing, green for sales/consignments/rentals — `customs/` still needs to be restyled to match the landing page's industrial palette).
  - Placeholder photo tiles (dashed boxes) instead of real images.

**Still needed:**

1. Logos for the 3 business sites (landing page has no logo, just wordmark).
2. Color palettes for `pressure-washing/`, `sales-consignments-rentals/`, and `customs/` — likely should echo the landing page's industrial palette (ink/panel/concrete/steel/amber/rust).
3. Real business names, contact info, and photos for each site.
4. Actual names of the brands represented on the Sales page.
