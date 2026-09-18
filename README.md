# App Enterprises

Five static websites for the App Enterprises family of businesses.

## Sites & domains

- `landing/` — "Dispatch Board" hub page → **app-enterprises.com**. Real design, links to the 4 businesses below.
- `pressure-washing/` — Home, Gallery, Contact → **app-pressurewashing.com**
- `sales-consignments-rentals/` — Home, Sales (with subtabs for each represented brand), Consignments, Rentals, Contact → **app-salesrentals.com**
- `customs/` — Home, Audio, Metal Fab, Upholstery & Refurbishment, Contact → **app-customs.com**
- `app-luxe/` — Home, Gallery, Contact → **app-luxe.com**. Marketing company (brand strategy, campaigns, content).

Each site is plain HTML/CSS/JS with no build step. In this repo they live as sibling folders, but each is meant to be deployed to the root of its own domain above — so cross-site links use the full domain (e.g. the footer "App Enterprises" link points at `https://app-enterprises.com`, not a relative path), while links *within* a site stay relative.

## Status

- `landing/` uses the real design and copy you provided, wired up to the real domains (now including App Luxe as a 4th bay), with the real App Enterprises logo (`landing/assets/logo.svg`) in place of the text wordmark.
- `pressure-washing/`, `sales-consignments-rentals/`, and `customs/` use color palettes matched to their real badge logos (black + icy blue, black + bronze, black + red, respectively), nav/hero copy updated to match each badge's category list, and the real logo (`<site>/assets/logo.svg`) in the nav bar of every page.
- `app-luxe/` is newly scaffolded with placeholder branding (dark + gold/champagne accent) since no logo/colors have been provided for it yet.
- All 4 business sites still use placeholder body copy, sample "brand" tabs on the Sales page (currently "Brand One/Two/Three"), and placeholder photo tiles (dashed boxes) instead of real photos.

**Note on the existing logo files:** the SVGs for pressure-washing/sales-rentals/customs/landing are large (300 KB – 1 MB each) because they were produced by auto-tracing a raster/photorealistic design into thousands of small vector paths, rather than being drawn as clean flat vector art — that's also why they can look "grainy" up close (lots of tiny path segments approximating shading, instead of smooth flat shapes). They render fine in the browser, but if page-load size ever matters, consider re-exporting a simplified flat version or serving a PNG. For App Luxe's logo (still needed), a transparent-background PNG is the recommended format.

**Still needed:**

1. Logo and color palette for `app-luxe/`.
2. Real business names/copy, contact info, and photos for each site.
3. Actual names of the brands represented on the Sales page.
