# CRAV — The Burger (Demo Storefront)

A loud, red-and-cream smash-burger brand site inspired by a TikTok design showcase (the "CRAV — The Burger" laptop reel) — rebuilt full-frame with huge typography, scroll tickers, and a fully working order flow.

## What's inside
- **Hero** — giant "THE BURGER YOU CRAV" display type, sticker badge, price tag, and tilted black marquee band
- **Menu grid** — 8 items with real food photography, prices, descriptions and tags; every "Add to Order" works
- **Burger Builder** — pick a bun, patties, cheese, fresh toppings and sauce; the stack visualises layer by layer with live pricing (base $4.00), then adds your custom build to the order as its own line item
- **Sides & Shakes strip** — full-bleed photo cards (fries, onion rings, freakshake) with one-tap add
- **Locations strip** — three stores with addresses, hours and "Open now" badges
- **Order drawer** — quantities, remove, live total, name/address fields, and a checkout success state with order number and pickup/delivery message
- **Extras** — scrolling tickers, toast notifications, scroll-reveal animations, fully responsive

## Run it
Open `index.html` in any browser. No build step, no dependencies beyond Google Fonts.

## Make it yours (buyer guide)
- **Menu:** edit the `MENU` and `SIDES` arrays in the script — name, price, description, tags, image
- **Builder:** edit `LAYERS` (groups, items, per-layer prices) and the `BASE` price constant
- **Photos:** replace files in `images/` (Unsplash placeholders — use your own food photography before launch)
- **Brand:** swap the CRAV name, colours via the `:root` variables (red/yellow/cream/ink), and the ticker phrases in the script
- **Ordering:** checkout is a front-end success state; wire the `checkoutBtn` handler to your POS/ordering provider for live orders

## Files
- `index.html` — the entire site (embedded CSS + JS)
- `images/` — 10 food photos
- `README.md` — this file
