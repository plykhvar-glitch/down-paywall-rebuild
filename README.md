# DOWN — the VIP paywall, personalized from the onboarding

**Live page: https://plykhvar-glitch.github.io/down-paywall-rebuild/**

DOWN's VIP paywall, rebuilt in its own design and fed by what the onboarding already knows: the first
name, GET DOWN or GET DATE, the highlight sticker, the city Nearby uses, and the button that opened VIP.
Change them under the phone and the paywall rewrites itself. Flip **Today** to see the version shown on
downapp.com. English and Spanish, plus a 30-second walkthrough.

## The five changes

| # | Change | Today | Now | Expected impact |
| :-- | :-- | :-- | :-- | :-- |
| 1 | Their answer in the headline | "See who liked you!" for everyone | "Maya, see who's DOWN for you in Austin!" (or "…wants a DATE…"), with GET DOWN, the highlight sticker and the city under it | CR +15–20% |
| 2 | The feature they tapped, first | Same four benefits in the same order, whatever opened VIP | Opened from Visitors, Flirt, the end of today's profiles or a new location: that line leads and the headline follows | CR +10–15% |
| 3 | Proof under the button | Nothing on the screen says who else is here | "★ 4.3 · 130K ratings · Every member photo-verified" under Continue | CR +10–15% |
| 4 | Prices that add up, per week | "12 MONTH, $7.99/mo" billed "$29.99/3mo"; 1 WEEK at $19.99 | 1 week $12.99 · 3 months $2.31/wk, Save 82%, picked · 1 month $4.61/wk | ARPU +8–15% |
| 5 | A smaller yes on close | Closing ends it | "Be the Top Profile in Austin this week": 1 Week Profile Boost, $6.99 | CR +3–6% from people who close |

*Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps —
not measured lift for DOWN.*

Prices, the Profile Boost, the 4.3 rating from 130K ratings, photo verification and 19M users come from
DOWN's US App Store listing; the paywall, benefits, highlight stickers and screens from downapp.com.
Per-week prices and savings are computed from DOWN's own prices. "Today" is rebuilt from the paywall
shown on downapp.com, so the live in-app screen may differ.

## Run locally

```bash
python3 -m http.server 8000
```
