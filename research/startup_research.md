# Startup Research Criteria

Working filter for the next startup idea. Goal is YC-caliber / venture-scale outcome, not another capped consumer app like CareerPicAI.

## What "solid foundation" actually means (and doesn't)

- **Not** weeks/months of solo desk research before talking to anyone or building anything. That's a documented YC red flag, not diligence.
- Bounded research (days) on market size/growth + a fast loop of talking to real users + a cheap paid test is the actual best practice. The talk-to-users loop *is* the research — it's also literally what YC asks about in interviews.
- Big outcomes correlate with founder-market fit, market size/growth, and speed of iteration — not with idea polish or research volume.

## Founder-market fit

- Real founder-market fit = months of immersion in a domain (30-50+ conversations, ideally hands-on adjacent work) until you know the non-obvious pain points insiders complain about that outsiders can't see from reading.
- "I'll just learn the problem" is fine, but only if that learning *is* the immersion process, done iteratively alongside building — not a research sprint done upfront as prep.
- I don't currently have founder-market fit in a new vertical, but I do have real scar-tissue insight from CareerPicAI in **consumer growth/paid acquisition**: CAC/LTV math, Meta ad platform behavior, Stripe/payment-rail quirks, chargeback/dispute economics, in-app-browser payment breakage, refund policy tradeoffs. That's a real edge on the *acquisition* side even without vertical-specific fit.

## Acquisition / distribution filter

This is the criterion to filter ideas on *before* committing time — arguably more decisive than the idea itself.

**Paid ads as ignition (bootstrap) is fine.** Getting the first ~100-1,000 users via paid acquisition to learn fast and find PMF is completely normal.

**Paid ads as the permanent engine is the trap.** CareerPicAI's structural flaw: flat CAC to infinity, no mechanism making user #10,000 cheaper to acquire than user #10.

**The actual filter:** does the idea have a compounding/organic mechanism that kicks in *after* the paid bootstrap, so CAC trends down over time instead of staying flat? Patterns that provide this:

- **Network effects** — each user pulls in more (marketplaces, social, collaboration tools)
- **Virality/shareability** — output is inherently shown to other people (CareerPicAI actually had a latent version of this — generated photos shown to others — but it wasn't exploited)
- **SEO/content moat** — organic search traffic instead of bought traffic
- **Platform hook** — built on top of something with existing distribution (Chrome extension store, Slack/Shopify app store, API marketplace)
- **Bottom-up B2B wedge** — one person adopts free/cheap, spreads inside their org (Slack/Figma/Notion model)
- **Existing audience** — a newsletter, following, or community to launch into for free

**Working rule:** if the first 1,000 users can't come from anywhere other than paid ads, kill the idea. And separately: if there's no visible path for CAC to trend down as the user base grows, kill it too.

## Summary checklist for evaluating a new idea

1. Large or fast-growing market (checkable in hours via desk research)
2. Some founder-market fit — either domain immersion already done, or a credible plan to do the immersion as part of building, not before
3. Paid acquisition is acceptable to *start*, but there must be a plausible compounding/organic mechanism to graduate off it
4. Bias toward talking to real potential users and running a cheap real-money test over more desk research

## 2026-08-01 update: applying the acquisition filter retroactively

Everything researched through 2026-07-29 to -31 (senior apps, Senior Line, senior dating, Family Tree Keep-Alive, YC batch/traction analysis — see LEDGER.md) was scored on demand, competition, and regulation, but **not yet on this doc's own compounding-mechanism filter.** Doing that now:

- **AI-native senior dating** is the one candidate that passes cleanly. Dating has a genuine network effect (more users → better matches → more valuable, classic marketplace liquidity) — the exception among the senior ideas, not the rule.
- **Senior Line** compounds on *retention/trust*, not *acquisition* — LTV grows, but CAC stays flat per new customer with no organic mechanism identified yet. One real, unexploited candidate: adult-child-to-adult-child word of mouth ("my sister found this for our mom") — never scoped as a growth channel, worth a real look before writing this off as paid-only.
- **Family Tree Keep-Alive** has a latent multi-user hook (inviting family members to contribute to a shared tree) that was designed as a retention feature, not a growth one — same unexploited-virality shape this doc already flagged for CareerPicAI itself.
- **TikTok for UGC games** actually passes this filter well (real network effects, real shareability) — proof the acquisition filter and the competitive-crowding filter are different axes; an idea can pass one and still die on the other (Roblox already owns the space).
- Everything else killed today (DIY/real-estate camera agents, memory layer, professional-discovery platform, paid AI companionship, virtual pet/guilt mechanics, LinkedOut, interview-sharing, cheap AI interviewer, voice travel booking) failed on demand/competition/liability grounds before the acquisition filter was even relevant.

**Founder-market-fit honesty check:** the senior vertical now has real desk-research depth (multiple research passes, competitor teardowns, regulatory maps) — but per this doc's own bar, that is NOT founder-market fit. It's the bounded-research phase this doc says is fine to do fast; the 30-50+ real conversations step hasn't happened yet for any senior candidate.

**Live cross-reference:** the CareerPicAI share-button + Facebook-login + credits work started 2026-08-01 is a direct, in-progress attempt to fix the exact "latent virality, never exploited" gap this doc calls out above. Worth tracking whether it actually moves CAC, not just DAU.
