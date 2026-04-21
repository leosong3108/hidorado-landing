# hidorado.com

Landing page for **Dorado** — one you, every Agent knows you.

A single-file static HTML landing, designed to be deployed to `hidorado.com` via any static host (Vercel, Netlify, Cloudflare Pages).

## Deploy

```bash
# Vercel (recommended)
npx vercel --prod

# or just drop index.html into any static host
```

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Palette (matches Dorado product)

- `#0A0D1A` paper / background
- `#4361EE` electric indigo · primary accent
- `#748FFC` periwinkle · secondary
- `#0891B2` stream cyan · data highlights
- `#E8EBFF` ink · foreground text

Fonts: Fraunces (display) · Inter (body) · JetBrains Mono (meta).

## Structure

- Galaxy canvas hero (900 spiral stars, 200 bulge stars, 6 labeled agent nodes, live mouse parallax)
- 4 feature sections — Memory · Anywhere · Delegate · Bridge
- Stats band + finale + footer
- Loader + bilingual 中/EN toggle
