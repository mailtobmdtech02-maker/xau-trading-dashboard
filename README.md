# XAU/USD Trading Analytics Dashboard

Production-ready React + Vite dashboard for real-time XAU/USD trading performance monitoring.

## API endpoints
Configured in `src/config.js`:

- `GET /webhook/trades`
- `GET /webhook/ea-trades`
- `GET /webhook/telegram-signals`
- `GET /webhook/indicators`

Default n8n server:

```txt
http://202.182.125.225:5678
```

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy to Vercel

```bash
npm install -g vercel
vercel login
vercel deploy --prod
```

## Demo mode
If the n8n endpoint is unavailable, the app automatically switches to demo data.
