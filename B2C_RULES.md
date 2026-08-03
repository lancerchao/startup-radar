# B2C App Filter — Lance's Rules

Eight gates a consumer idea must clear before it's worth pursuing over B2B. Context: two software engineers, weak at marketing/distribution, and the session-level finding is that B2B has better base-rate odds for this team (2-4x survival, lower churn, traction-override achievable via a single pilot rather than a viral spike).

**The actual objective this B2C project serves (stated 2026-08-03): not to be the big outcome itself.** Lance has free Meta ad spend already available. The goal is to build something *semi-successful* — enough real traction to (a) prove the marketing/distribution weakness is fixable, (b) build a track record and public reputation as a builder, and (c) become credible evidence for a *future* YC application, on an idea that may not even be this one. Rules 1-6 define the narrow slice of B2C economically worth pursuing over B2B; rules 7-8 filter further for the specific job this project has to do — generate a legible, tellable, reputation-positive proof point, not necessarily the best possible business.

Score every B2C candidate against all eight before adding it to the sheet above `watch` status. Fail one, it's a pass — not a maybe.

## Rule 1 — Meta-targetable, not just age/gender

The audience must be reachable via Meta's **interest, behavior, or life-event** targeting — not merely a demographic bucket like "women 25-40." Verify with Meta Ads Manager's audience-size estimator before committing; "decent size" means the estimator returns a real number, not a guess.

Qualifies: "recently divorced," "small business owner," "parents of a child under 2," "frequent international traveler." Doesn't qualify: anything too diffuse to target precisely, or reachable only by demographic overlap (which Meta increasingly restricts anyway — see the dating-ads and financial-products authorization gates hit earlier).

## Rule 2 — High LTV (6mo–1yr+) AND a renewing population

Two conditions, both required:
- **Retention**: real reason to keep paying past the first purchase — accumulated data/context (Ancestry-style), an ongoing service, or a recurring need. Not a one-and-done purchase.
- **Inflow, not just stock**: new people must be entering this demographic continuously — a new cohort of parents every year, a constant stream of people changing jobs, retiring, getting married — not a fixed population you eventually saturate and have nothing left to sell into. This is why the new-parent memory-keeper concept structurally beat a purely senior-population play on this axis, even though it died on Rule 4.

## Rule 3 — Existing competition doesn't disqualify, but the buyout thesis needs a real moat to work

Big tech or incumbents already serving this space does **not** kill the idea by default — the goal is to take share and be worth acquiring for it. **But this only works if the idea has something an acquirer can't just cheaply clone instead of paying for**: real network effects/liquidity, proprietary accumulated data, or a trust/brand position that took years to build. Established this session (Playabl.ai vs. Roblox): if the differentiator is a feature, the incumbent builds it themselves rather than acquiring you — Roblox already has AI-native game creation on its own roadmap. "Competitors exist" is fine. "Competitors exist and could trivially copy what makes me different" is not.

## Rule 4 — Not a thin AI wrapper

If the entire product is "call an LLM API and format the output," it's not defensible — AI-wrapper startups are running an estimated **~80% failure rate** (CB Insights/Gartner, by end of 2026). There must be a moat beyond the model call: proprietary data, workflow embedding, accumulated per-user context, or genuine engineering depth a frontier lab wouldn't bother shipping as a free feature (see: the DIY-repair-agent and real-estate-camera-agent kills — if OpenAI/Google would plausibly demo it on stage for free, it's dead as a standalone product).

## Rule 5 — Organic spread via referral/friend mechanics, explicitly NOT a new social network

Must have a real, built-in reason people bring in other people — but the mechanism has to be one of these three (established this session), not a platform/liquidity play:

1. **Aligned double-sided referral** (Dropbox model) — the reward is more of what the product already delivers, not a bolted-on currency.
2. **Forced-multiplayer retention** (Duolingo Friend Streaks) — both people have to act to keep the thing alive, so retention and invites become the same mechanic.
3. **Identity-flex shareable artifact** (Wordle/Spotify Wrapped) — the output itself is something people want to show off, no incentive needed.

**Explicitly excluded**: anything requiring two-sided marketplace liquidity to function (dating apps, UGC platforms, anonymous-community apps) — these have their own cold-start problem and were the exact shape of every "platform" idea killed this session (LinkedOut, TikTok-for-games, the professional-discovery network). A referral loop bolted onto a single-player product is fine; needing strangers to show up for each other to make the product work at all is not.

## Rule 6 — Niche audience, not broad

The target must be a defined niche, not a broad general-population category. Broad audiences mean: worse Meta targeting precision (conflicts with Rule 1), more entrenched/well-funded incumbents already serving the mass market, and no natural community-density to seed organic spread (Rule 5) or word-of-mouth (see: the YC traction research — every real organic win happened inside a *dense, specific* community, never a generic mass audience). Niche-but-real, sized and confirmed via Rule 1's Meta estimator, beats broad-and-shallow every time in this filter.

## Rule 7 — Reputationally clean; actively enhances the name attached to it

Given the objective is trust/brand-building toward a future YC shot, this isn't a nice-to-have — a "successful" product that damages Lance's name works *against* the actual goal, not neutrally. Kill anything where the honest one-line description reads badly to an investor, a future co-founder doing diligence, or a journalist: exploiting a vulnerable population (killed: OnlyFans-for-seniors), building on a fetishized racial/identity dynamic (killed: the "snowbunny" pairing app), enabling defamation exposure (killed: LinkedOut). The bar isn't "legal" — several killed ideas were legal. The bar is "would I want this as the headline case study when I pitch the next thing."

## Rule 8 — Produces a tellable story, not just a number

The eventual pitch needs to be a sentence, not a spreadsheet: a real, specific, ideally counterintuitive lesson about distribution — not "we spent money on ads and it worked at X% margin." Since the whole point is demonstrating the marketing/distribution gap got closed, prefer execution paths that let Lance discover and later *articulate* a genuine, non-obvious growth insight (an unusual channel, an organic mechanic that outperformed paid, a niche nobody else was serving) over a path that's just "we ran the standard playbook competently." Competent-and-boring proves less in an interview than surprising-and-true.

---

## Good to knows (execution guidance, not gates — don't score candidates against these)

**Fast, legible leading-indicator signal.** Full LTV realization (Rule 2) can take the whole 6-12 months, but try to know within *weeks* whether a launched candidate is working — early cohort retention, week-4 repeat usage, organic referral rate. Same discipline as the fake-door/landing-page tests already run this session. This is about how you *run* the project once picked, not a reason to reject an idea that otherwise clears rules 1-8.

**Keep the ad account and pixel separate from CareerPic's.** Run on its own domain, its own Meta pixel, its own ad account — never careerpicai.com's. Protects CareerPic's proven conversion-optimization history from a new, unproven experiment, and keeps the two brand identities cleanly separable if the new project's story (per Rule 7) ever needs to stand entirely on its own.

---

## Applying this

A candidate that clears all eight gates is rare by design — that's the point, given the base-rate case for B2B established this session. When one does clear all eight, it should be flagged in the daily digest as a genuine exception worth the radar agent's full research pass, same rigor as a B2B candidate gets — then run under the two "good to knows" above.
