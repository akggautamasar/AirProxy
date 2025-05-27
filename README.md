# AirProxy

AirProxy is a lightweight frontend hosted on Vercel that proxies API requests to your Koyeb-hosted backend.

## How it works

- Requests to `/api/*` are forwarded to:
  `https://courageous-casie-airarchives-0229921c.koyeb.app/api/*`
- Example: `/api/test` → Koyeb `/api/test`

## Deployment

This project is ready to deploy on [Vercel](https://vercel.com).
