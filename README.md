# Growth Audit — Mango Languages

**Live:** https://bterzic123.github.io/mango-flow-rebuild/ · prototype: https://bterzic123.github.io/mango-flow-rebuild/?view=proto

Every Mango install tells you which language they want on Pick a Language. The paywall, “Fluency favors the bold.”, never says it. This audit rebuilds the first launch in Mango's own design and prices so the picked language carries all the way to the paywall, shown on three phones: an install from the YouTube ad (Japanese), a Spanish learner and a French learner.

## The five ideas

| # | Idea | Screen | Expected impact |
| :-- | :-- | :-- | :-- |
| 1 | Name their language on the paywall | Paywall | CR +15–20% |
| 2 | Show the first chapter before the price | First chapter | CR +10–15% |
| 3 | Open on Yearly, with your own saving on it | Paywall | ARPU +10–15% |
| 4 | Ask about notifications after the paywall | Stay on track. | CR +10–15% |
| 5 | Let the loader say their language back | Loader | CR +10–15% |

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps, not measured lift for Mango Languages.

## Grounding

Screens, copy and icons come from the Mango iOS app as recorded on 13 November 2026 (EU storefront: 14,99 € / 129,99 € Individual, 22,99 € / 179,99 € Family, 14-day free trial). US prices, the 4.8 rating from 44K ratings and 70+ languages come from the US App Store listing. The ad, its dates and the channel split are from AppMagic via Atlas; the Japanese and French lines on the first-chapter screens are quoted from that ad. Nothing is invented: no discount, no timer, no statistic.

## Run locally

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080/.

Prepared by Adapty · [Book a demo](https://calendly.com/d/cty4-37z-zqj)
