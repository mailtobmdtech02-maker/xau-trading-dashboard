# MONMON100 Trading Analytics Dashboard

Simple one-file HTML dashboard for XAU/USD closed trade analytics.

## Files
- `index.html` — dashboard only
- `README.md` — instructions

## Deploy to Vercel
1. Upload `index.html` and `README.md` to GitHub repository.
2. Import the repository into Vercel.
3. Framework preset: Other.
4. Build command: leave empty.
5. Output directory: leave empty or `.`.
6. Deploy.

## n8n endpoint
Default endpoint inside `index.html`:

```js
API_URL: 'http://202.182.125.225:5678/webhook/trades'
```

Dashboard counts only closed trades:
- WIN
- TP1_HIT
- TP_MID_HIT
- LOSS

Start date:
```js
START_DATE: '2026-06-16'
```
