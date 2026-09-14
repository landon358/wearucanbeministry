# Wear U Can Be T Shirt Ministry

Static marketing site for Wear U Can Be T Shirt Ministry, Detroit MI. No e commerce. The Order Here page collects an order request; Tye follows up by call or text and payment places the order.

## Run it

Any static host. Open `index.html`, or serve the folder:

```
python3 -m http.server 8000
```

## Deploy to GitHub Pages

1. Push this folder to the repo root (or to `/docs`).
2. Settings, Pages, Source: Deploy from a branch, `main` / root.
3. `.nojekyll` is included so the site is served as is.

## Files

```
index.html      the whole site (7 pages, client side routing)
support.js      runtime that renders index.html
assets/         logo, product photos, flyers
```

## Pages

Home, Designs, Custom Orders, Crochet, Our Ministry, Outreach, Order Here.

## Still to wire up

- The order form posts to Netlify Forms as `order`. It only works when the site is deployed on Netlify. On GitHub Pages it shows an error asking people to call or text. In Netlify, open Forms, then Form notifications, and add an email notification to wearucanbetshirts@gmail.com.
- Our Ministry has an "Image here" placeholder waiting on a portrait.
- Prices are deliberately absent until confirmed.
- Crochet needs new photography shot off the branded blanket.

## Brand

Ink Black `#060606`, Card Cream `#F6F6EA`, Sun Gold `#F9B627` (primary CTA), Sky Blue `#019EDF`, Heart Red `#E63532`, Leaf Green `#75B94C`, Lemon `#F9D54B`.
Type: Outfit, with Bagel Fat One for display slogans.
