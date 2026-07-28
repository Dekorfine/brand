# Vakkerlight Luxury Redesign

High-fidelity, responsive concept for the Vakkerlight storefront. The prototype establishes a complete visual system for:

- Global announcement, header, mega menu, search, cart drawer and footer
- Homepage editorial storytelling and product discovery
- Collection / product listing template
- Product detail template with option states, cart interaction and accordions
- Journal and brand story pages
- Mobile and desktop responsive behavior
- Scroll reveals, image motion, marquee, drawers and route transitions

## Preview

Open `index.html` with any static web server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/vakkerlight-redesign/`.

## Navigation

The prototype uses hash routes:

- `#home`
- `#collection`
- `#product`
- `#journal`
- `#about`

## Shopify implementation map

The concept is intentionally structured so it can be translated into Shopify OS 2.0:

- Header/menu/search/cart → `sections/header-group.json`, snippets and cart drawer
- Homepage blocks → reusable schema-driven sections
- Collection → `templates/collection.json`
- Product → `templates/product.json` and product information blocks
- Journal → `templates/blog.json` / `article.json`
- Footer/newsletter → `sections/footer-group.json`

No production Shopify theme was modified by this concept branch.
