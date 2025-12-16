# Static ERP UI (HTML/CSS Only)

A multi-page, responsive ERP-style UI using only HTML and CSS (no JavaScript, no backend). Includes dashboard, products, customers, orders, reports, and settings.

## What’s inside

- `index.html`: Dashboard with KPI cards and recent orders
- `products.html`: Product list table and a non-functional create form
- `customers.html`: Customer directory table and a non-functional add form
- `orders.html`: Orders table with status badges
- `reports.html`: KPI-style summary cards and a simple list
- `settings.html`: Visual-only preference toggles
- `styles.css`: Modern reset, CSS variables, responsive layout, tables/forms/badges
- `favicon.svg`: Small gradient icon for tabs/shortcuts

## How to run

No build steps required. Just open `index.html` in your browser.

Optional: run a simple local server (helps with relative paths and caching):

```zsh
# Python 3 built-in server
python3 -m http.server --directory . 5173
# then open http://localhost:5173
```

## Customize

- Brand/title: In each page, update `<title>` and the `.logo` text
- Colors: In `styles.css`, change the `:root` color variables (e.g., `--primary`)
- Tables: Edit the sample rows inside `<tbody>` to reflect your data
- Forms: Forms are non-functional placeholders; set `action` to a URL if you later add a backend

## Notes

- The mobile menu uses a CSS-only checkbox toggle (no JS)
- Typography uses system fonts for speed and simplicity
- Light/dark colors adapt to your OS preference (`prefers-color-scheme`)
- This is a static prototype—no persistence or interactivity beyond navigation

## License

MIT — do anything, but no warranty. Replace content with your own as needed.
