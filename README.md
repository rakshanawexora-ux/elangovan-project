# Elangovan Doorstep Services

A responsive four-page website for Chennai-based document assistance. Built with Vite and plain JavaScript/CSS. Includes generated photography, page-specific titles, business structured data, service filtering, FAQs, accessible mobile navigation, and reduced-motion support.

## Development

Requires Node.js 22 or newer.

```sh
npm ci --cache /tmp/elangovan-npm-cache
npm run dev -- --port 3000
```

## Production

```sh
npm run build
npm run preview -- --port 3000
```

Deploy `dist/` to a static host. Configure fallback routing to `index.html` for `/about`, `/services`, and `/contact`. Once a production domain is chosen, add canonical URLs and a domain-specific sitemap. Contact links use +91 7396039571. Visits are by arrangement; no invented street address or opening hours are included.

The generated hero photograph is illustrative, not a portrait of T.R. Elangovan.
