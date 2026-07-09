# Central Florida Homes — Real Estate Lead Generation Platform

Full-stack TypeScript property platform for Central Florida home buyers. Part of the Business Conector lead-generation system by World Unities LLC.

## What It Does

- Property browsing and search for Central Florida markets (Lakeland, Tampa, Orlando, Daytona)
- Lead capture wired directly into a GoHighLevel CRM pipeline with automated follow-up
- Serves as one of five live property sites feeding the Business Conector platform

## Architecture

```
client/    — React + Vite + Tailwind frontend
server/    — API layer
drizzle/   — Drizzle ORM schema and migrations
```

Deployed on Vercel (see `vercel.json`).

## Tech Stack

- **Language:** TypeScript end to end
- **Frontend:** React, Vite, Tailwind CSS, PostCSS
- **Database:** Drizzle ORM
- **Hosting:** Vercel
- **CRM Integration:** GoHighLevel (contact creation, pipeline routing, SMS follow-up)

## Documentation

- `DEPLOYMENT_GUIDE.md` — how to deploy
- `FINAL_SUMMARY.md` — project overview and decisions

## Related Repositories

- [business-conector-modular](https://github.com/danieljames-dev/business-conector-modular) — the modular platform version
- [centralfloridashomes-vercel](https://github.com/danieljames-dev/centralfloridashomes-vercel) — property search app with 7,948 listings
- [florida-property-scraper](https://github.com/danieljames-dev/florida-property-scraper) — listing data pipeline

---

*Credentials and API keys are not included in this repository.*
