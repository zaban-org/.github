# Services

| Service  | Repository | Deployment | Observability
| -------- | ---------- | ----------- | -----------
| [core.codify.sh](https://core.codify.sh)     | [codify-sh/core](https://github.com/codify-sh/core) | [![CI](https://github.com/codify-sh/core/actions/workflows/ci.yml/badge.svg)](https://github.com/codify-sh/core/actions/workflows/ci.yml) [Render](https://dashboard.render.com/web/srv-ctfl5hl2ng1s738koivg/events) | [Logs](https://dashboard.render.com/web/srv-ctfl5hl2ng1s738koivg/logs?r=1h)
| [codify.sh](https://codify.sh) | [codify-sh/web](https://github.com/codify-sh/web) | [Vercel](https://vercel.com/codify-sh/web/deployments) | [Logs](https://vercel.com/codify-sh/web/logs?selectedLogId=zrwbs-1734301700144-ae2f22fe8dd1&timeline=pastHour)
| [edge.codify.sh](https://edge.codify.sh) | N/A | [Supabase](https://supabase.com/dashboard/project/ufebcvbnfoopvrssncfv) | [Logs](https://supabase.com/dashboard/project/ufebcvbnfoopvrssncfv/logs/explorer?q=select%0A++cast%28timestamp+as+datetime%29+as+timestamp%2C%0A++event_message%2C+metadata+%0Afrom+edge_logs+%0Alimit+100)
| Billing | N/A | [Stripe](https://dashboard.stripe.com/test/dashboard) | [Logs](https://dashboard.stripe.com/test/payments)
| Mail | N/A | [Resend](https://resend.com/emails) | [Logs](https://resend.com/logs)
| DNS | N/A | [Cloudflare](https://dash.cloudflare.com/3fdc57d9c28cf7f48aac59bb47c02b0b/codify.sh/dns/records) | [Logs](https://dash.cloudflare.com/3fdc57d9c28cf7f48aac59bb47c02b0b/codify.sh/dns/analytics)
| Dev | [codify-sh/dev](https://github.com/codify-sh/dev) | N/A | N/A |
