# FeedGuard Synthetic Demonstration Kit (Northwind Goods)

This folder contains 100% synthetic demonstration product feeds, product landing pages (with schema.org JSON-LD structured data), and SVG product images created solely for testing FeedGuard's live public URL scanner.

## Included Files
- `feedguard-demo.xml` — 10-product Google Shopping RSS 2.0 XML feed
- `feedguard-demo.csv` — 10-product Google Shopping CSV feed
- `products/*.html` — 9 live product pages (`discontinued-lantern-404.html` is intentionally omitted to produce HTTP 404; `waxed-tote.html` intentionally shows `92.00 USD` and `OutOfStock` vs `75.00 USD` and `in_stock` in the feed)
- `images/*.svg` — 7 synthetic SVG product images (`missing-flask-404.svg` is intentionally omitted to produce HTTP 404)
- `index.html` — Demo store directory and 1-click XML/CSV URL customizer for your GitHub Pages URL
