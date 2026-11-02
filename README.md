# PricePilot

Product discovery, price comparison, watchlists and project procurement.

## Prototype v0.1.0
- Item, Category and Project modes
- Expandable comparison cards with lowest / average / highest summaries
- Interactive prototype price-alert rules
- PC component category explorer
- Project procurement checklist previews
- Responsive dark dashboard

**Important:** All displayed prices and marketplace listings are illustrative demo data. No marketplace APIs are connected and no real notifications are sent.

## Run locally
Requires Node.js 20+.

```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
npm run preview
```

## Roadmap
1. Persist watchlists, projects and alert rules.
2. Add marketplace connectors and normalized listings.
3. Integrate permitted sources (eBay APIs, retailer APIs and approved feeds).
4. Add price history, shipping-aware comparisons and scheduled refresh.
5. Add project planning and compatibility-aware recommendations.
6. Add email and push notifications.

All marketplace integrations must comply with provider terms. Facebook Marketplace has no unrestricted public search API; use approved integrations or user-supplied listing links rather than unauthorized scraping.