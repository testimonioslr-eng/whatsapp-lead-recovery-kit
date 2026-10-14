# WhatsApp Lead Recovery Kit (LandingPixel)

A small, opinionated reference kit for small business owners who are losing
potential customers through WhatsApp every week. It includes:

- A diagnostic checklist (audit your own WhatsApp funnel in 10 minutes).
- Three free tracking templates (Google Sheets / CSV) for logging incoming
  leads, time-to-first-response, and lost reasons.
- An open calculation of "revenue-at-risk" based on observed response times
  and a configurable close rate.
- A short, vendor-neutral comparison of the most common recovery patterns
  (auto-reply, routing, attribution, follow-up) so you can decide what to
  implement before paying for any SaaS.
- A one-page **calculadora** (`calculator.html`) that runs entirely in your
  browser: no backend, no cookies, no analytics.

This project is the public side of [LandingPixel](https://www.landingpixel.com/tiktok/),
a tool that connects ad + landing page + WhatsApp + response tracking in a
single flow for Argentine and Latin American SMBs. The kit is intentionally
free, vendor-neutral, and useful even if you never use LandingPixel.

## What is in this repo

| File | Purpose |
|---|---|
| `docs/diagnostic-checklist.md` | 10-minute self-audit of your WhatsApp funnel |
| `docs/revenue-at-risk.md` | How to estimate how much money your slow response is costing you |
| `docs/patterns.md` | 4 common recovery patterns, with pros/cons and what to measure |
| `docs/calculadora.md` | Notes on the one-page calculator (`calculator.html`) |
| `calculator.html` | The browser-only calculator (single file, no dependencies) |
| `templates/leads-log.csv` | Empty template for logging incoming leads |
| `templates/response-time-log.csv` | Empty template for tracking time-to-first-response |
| `templates/lost-reasons.csv` | Empty template for tagging why a lead was lost |
| `assets/whatsapp-funnel.svg` | Diagram of a typical WhatsApp funnel (open, edit, redistribute) |
| `examples/sample-leads.csv` | 10 anonymized rows to show the schema in use |
| `examples/README.md` | Notes about the example data |

## Who this is for

- Sole proprietors and small teams (1-10 people) using a personal or
  Business WhatsApp account to receive customer inquiries.

- Service businesses (lawyers, dentists, trainers, repair shops, real
  estate agents, photographers, coaches) where a missed message is a
  permanently lost customer.

- Marketing agencies that want a simple framework to onboard a new SMB
  client and show the client the cost of their current "best effort"
  WhatsApp coverage.

## Who this is NOT for

- Large contact centers with dedicated CRM integrations.
- Businesses whose inbound is already < 95% answered in < 5 minutes.
- Anyone looking for a magic button: the kit is a starting point, not a
  finished product.

## License

MIT. See `LICENSE`.

## About LandingPixel

LandingPixel is a tool for SMBs that connects ad + landing page + WhatsApp
+ tracking in one flow. It is built for the Argentine and Latin American
market and supports the Spanish-language WhatsApp Business flow end-to-end.

- Product page (Spanish): https://www.landingpixel.com/tiktok/
- Owner repo (if you fork this and want to stay in sync): see Releases.

If you find this kit useful, the easiest way to say thanks is to send the
URL of your fork to a friend who runs a small business and complains about
missed WhatsApp leads. That is more valuable to us than a star.
