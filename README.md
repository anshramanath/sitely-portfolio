# Sitely. 🌐

A bento-grid portfolio showcasing websites built for local businesses — corner shops, cafés, family trades.

## 🗂️ Sites

| Business | Type | City | Status |
|---|---|---|---|
| [Meetcha](https://sitely2web.github.io/meetcha/) | Bubble Tea Café | Plano, TX | ✅ Live |
| [Miao](https://sitely2web.github.io/miao/) | AYCD Boba | Carrollton, TX | ✅ Live |
| [See U Morning](https://sitely2web.github.io/see-u-morning/) | Chinese Breakfast | Frisco, TX | ✅ Live |
| Hadley & Co. | Used Books | Providence, RI | 🚧 In progress |
| Ridge Cycle Co. | Bike Workshop | Asheville, NC | 🚧 In progress |
| Linden St. | Bakery | Oakland, CA | 🚧 In progress |
| Pasta Notte | Trattoria | Chicago, IL | 🚧 In progress |
| Brick Lane | Barber Shop | Brooklyn, NY | 🚧 In progress |

## 🛠️ Stack

- Plain HTML, CSS, vanilla JS — no frameworks, no build step
- [Fraunces](https://fonts.google.com/specimen/Fraunces) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) + [DM Mono](https://fonts.google.com/specimen/DM+Mono) via Google Fonts
- CSS Grid bento layout (12-col, 52px rows)
- Hosted on GitHub Pages

## 📁 Adding a New Site

1. Drop a hero image into `assets/images/`
2. Add an entry to the `sites` array in `index.html`:

```js
{ name: "Business Name",  type: "Type",  city: "City, ST",  url: "https://...",
  screenshot: "assets/images/filename.jpg",  paid: true,  cta: "visit",
  size: "medium",  area: "row-start / col-start / row-end / col-end" }
```

3. Adjust `area` to fit the bento grid — the grid is 12 columns wide, rows are 52px tall.

## 📸 Screenshot Tips

- Aim for **16:9 or wider** crops for `wide`/`large` cards
- Use `imgPosition: "center X%"` to control focal point
- Use `nameCorner` + `ctaCorner` to reposition labels when the image needs breathing room

---

Made by hand, in plain HTML · [Sitely](https://sitely2web.github.io) · est. 2026 🌱
