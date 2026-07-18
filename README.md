# Hobby Stock Price Alert

フィギュア・トレカ・ゲーム在庫/価格通知

## Repository

Recommended repository name: `hobby-stock-price-alert`

## Domain candidates

First candidate: `hobbystock.jp`

Other candidates:

- `hobbystock.jp`
- `figurealert.jp`
- `cardstock.jp`
- `gamezaiko.jp`

## Concept

在庫復活、価格下落、予約開始、再販を通知し、ECアフィリエイトと有料通知へつなげる。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- EC affiliate
- 有料通知
- 買取送客
- 広告枠
- スポンサー

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
