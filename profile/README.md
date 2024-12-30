
# Services

| Service  | Repository | Deployment | Observability 
| -------- | ---------- | ----------- | ----------- 
| Dev | [zaban-org/dev](https://github.com/zaban-org/dev) | N/A | N/A 
| [Web](https://zaban.ai) | [zaban-org/web](https://github.com/zaban-org/web) | [Vercel](https://vercel.com/zaban/web/deployments) | [Logs](https://vercel.com/zaban/web/logs?timeline=pastHour) 
| [Core](https://core.zaban.ai)     | [zaban-org/core](https://github.com/zaban-org/core) | [Render](https://dashboard.render.com/web/srv-ctfl5hl2ng1s738koivg/events) | [Logs](https://dashboard.render.com/web/srv-ctfl5hl2ng1s738koivg/logs?r=1h) 
| [Database](https://edge.zaban.ai) | [zaban-org/supabase](https://github.com/zaban-org/supabase) | [Supabase](https://supabase.com/dashboard/org/xfzzkbcscrfwttoidigy/usage) | [Logs](https://supabase.com/dashboard/project/ufebcvbnfoopvrssncfv/logs/explorer?q=select%0A++cast%28timestamp+as+datetime%29+as+timestamp%2C%0A++event_message%2C+metadata+%0Afrom+edge_logs+%0Alimit+100) 
| Billing | N/A | [Stripe](https://dashboard.stripe.com/test/dashboard) | [Logs](https://dashboard.stripe.com/test/payments) 
| Mail | N/A | [Resend](https://resend.com/emails) | [Logs](https://resend.com/logs) 
| DNS | N/A | [Cloudflare](https://dash.cloudflare.com/3fdc57d9c28cf7f48aac59bb47c02b0b/zaban.ai/dns/records) | [Logs](https://dash.cloudflare.com/3fdc57d9c28cf7f48aac59bb47c02b0b/zaban.ai/analytics/traffic) | 
