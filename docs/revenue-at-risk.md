# Revenue at risk: how to estimate the cost of slow WhatsApp responses

This page gives you a one-page calculation. You will need three
numbers, all of which you can estimate from your own phone.

## The three inputs

1. **Inquiries per week.** Open WhatsApp. Count how many first-time
   messages you received in the last 7 days. Use the average of the
   last 4 weeks if you have it.
2. **Average ticket (or average customer value).** The amount a closed
   customer pays you, in your local currency. If you sell products with
   very different prices, use the median of the last 20 sales.
3. **Close rate you would have at 5-minute response time.** This is the
   number that matters. A conservative default for service businesses
   that answer in under 5 minutes is 25%. If you do not know, use 20%
   and write it down so you can update it later.

## The formula

```
leads_per_week * close_rate_fast * average_ticket = weekly_potential
weekly_potential * 52 = annual_potential
```

Example (Argentine SMB, USD-equivalent to keep the math simple):

- 30 inquiries/week
- 25% close rate at < 5 min response
- USD 80 average ticket
- Weekly potential: 30 * 0.25 * 80 = USD 600
- Annual potential: USD 31,200

## How much of that are you actually capturing?

Most SMBs do not measure their real close rate. They guess. If you
cannot measure, use these industry-default response-time penalties as a
starting point and adjust as you gather data:

| Average first-response time | Approximate share of leads still reachable |
|---|---|
| Under 5 minutes | 100% (use your real close rate) |
| 5-30 minutes | about 60% of the under-5-minute rate |
| 30 minutes - 2 hours | about 30% |
| 2-24 hours | about 10% |
| Over 24 hours | under 5% |

To apply the table: take your "fast" close rate, multiply by the share
above, and that is your effective close rate at your current response
speed. The difference between the two is the revenue you are leaving
on the table.

## Worked example (continued)

You estimate your current average first-response time is 1 hour. That
puts you at the 30% row.

- Fast close rate: 25%
- Effective close rate: 25% * 30% = 7.5%
- Leads/week: 30
- Average ticket: USD 80
- Captured revenue/week: 30 * 0.075 * 80 = USD 180
- Annual captured: USD 9,360
- Annual at fast response: USD 31,200
- **Annual gap: USD 21,840**

That is the size of the problem. It is also the size of the
opportunity. The next page describes the four most common ways SMBs
close that gap, with the tradeoffs of each.

If you want to skip the implementation and go straight to a working
flow that handles the routing, the attribution, and the response-time
tracking for you, see
[LandingPixel](https://www.landingpixel.com/tiktok/).
