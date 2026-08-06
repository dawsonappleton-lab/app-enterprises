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
- `pressure-washing/`, `sales-consignments-rentals/`, and `customs/` now use color palettes matched to their real badge logos (black + icy blue, black + bronze, black + red, respectively), and nav/hero copy updated to match each badge's category list. They still use placeholder body copy, sample "brand" tabs on the Sales page (currently "Brand One/Two/Three"), and placeholder photo tiles (dashed boxes) instead of real images.

**Still needed:**

1. The actual logo image files (PNG/SVG). The 4 badge logos were shared as images in chat, but images sent inline aren't saved to disk in this environment the way an uploaded file is — please attach them as files so they can be added as real `<img>` assets instead of text/emoji lockups.
2. Real business names/copy, contact info, and photos for each site.
3. Actual names of the brands represented on the Sales page.
