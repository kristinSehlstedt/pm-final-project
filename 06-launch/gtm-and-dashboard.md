# GTM Launch Plan, Riverty business-unit case

| Field | Value |
|---|---|
| Feature | Riverty card |
| Goal | Engagement |
| Launch tier | M, Targeted |

## Goal & Audience
- **Goal:** Engagement, The metric is repeat usage at the till. The bet is that “decide later” gives her a reason to tap instead of falling back to debit.
- **Target audience:** A heavy BNPL user (8 purchases a month) and Riverty Flex user who also carries Klarna and PayPal and falls back to her debit cards everywhere else.

## Launch Tier
- **M, Targeted**, evidence supports a controlled ramp but not a full rollout.

## Channels
1. **Owned: In-app + push + email to existing Flex customers matching the persona. Launch moment: "Tap at any till, decide later from home." Activates users who already hold the card, and walks them through adding it to Apple Pay / Google Pay and making their first in-store tap. Owned reaches her where she already pays later online, at no media cost.**
2. **Earned: Word of mouth from pilot users: in-app prompt after her first "decide later" purchase to share or rate the experience, plus a short pilot-results story for consumer-finance media once the A/B test passes. The angle is shareable because it fixes a till problem people recognise: "I can pay later in shops, not just online." Low expected volume, so it supports owned and is not a main driver.**
3. **Paid: Small paid retargeting to existing Flex customers only (CRM-matched audiences on Instagram and Google), short-form video showing the tap-then-decide flow. Aimed at the gap between card activation and first in-store tap. Capped budget, no prospecting spend, and switched on only after the pilot passes. [Needs Legal sign-off on using customer data for ad targeting.]**

## Enablement & Assets
Launch email and in-app launch sequence (activation, first tap, first decision). Push notification copy for the "decide" prompt. 20-30 second demo video of the tap-then-decide flow. Updated app store copy. One-page FAQ for Support (how it works, decision window, default outcome, what happens on a decline, refunds). Support and CS briefed before launch, with a manual refund-handling process agreed with Ops. Sales: one-pager for partner/merchant questions confirming that no terminal or merchant change is needed. Compliance-reviewed copy covering total cost, the decision deadline and the default outcome. All claims pending Legal and Compliance sign-off.

## Ownership, Budget & Timeline
- **Ownership & budget:** Kristin (PM) owns the plan, the go/no-go gates and post-launch metrics (5+ card uses in 30 days, approval rate, default-settled share).
[Name] (Architect) owns the feasibility spike and the technical go/no-go.
[Name] (BA) owns requirements, decision-window rules and the Support FAQ content.
[Name] (Dev lead) owns the build and Apple Pay / Google Pay provisioning with the partner.
[Name] (QA) owns test sign-off and guardrail instrumentation checks.
[Name] (Marketing) owns the launch email, in-app sequence, push copy and capped paid retargeting. Budget needed: owned assets (no media cost), small paid cap to be set, TBD.
[Name] (Design) owns the demo video and in-app launch screens. Asset gap: no video capacity confirmed.
[Name] (Risk) owns exposure caps per phase and the default-settled / arrears limits.
[Name] (Legal/Compliance) owns sign-off on cost disclosure, post-purchase credit treatment, ad copy and use of customer data for ad targeting.
[Name] (Ops/Support lead) owns the manual refund process and briefs Support before launch. No extra budget requested unless Phase 2 volume needs more staffing.
Open budget items: paid media cap, demo video production, partner fees for wallet provisioning (to be confirmed).
- **Timeline:** Phase 1, Pilot (S, 652 users):
- Sprint 1: feasibility spike (Architect + 2 devs, time-boxed). Partner workstream for Apple Pay / Google Pay starts in parallel. Legal/Compliance review starts.
- Gate: spike passes. If not, switch to the fallback (plan choice at the till) and rescore before continuing.
- Next 2-3 sprints: build the Must Haves, instrument the guardrails, brief Support, agree the manual refund process. Freeze unrelated releases and wallet changes.
- Then 30 days: run the A/B test. Gate: ship rule met (lift of 5 pp or more, approval rate within 1 pp, default-settled share and arrears within Risk limits).

Phase 2, Launch moment (M, about 700 to 5,000 users):
- Launch email, in-app sequence and push for the first ramp group. Paid retargeting stays off until Legal approves.
- Monitor weekly: approval rate, default-settled share, tap-to-notification time, Support tickets. Gate: no guardrail breach for 30 days.

Phase 3, Post-launch:
- Widen towards L only if the Phase 2 gate passes, keeping a 5% holdout to prove the lift continues.
- Review at 30 and 60 days, then decide: scale, iterate or stop. Cashback and 0% offers are the next candidate once the till works.

## Success Metrics
- **Metrics:** 1. Primary: share of persona users with 5 or more card uses in 30 days (in-store taps counted). Target: +5 pp versus control.
2. Leading indicator: share of activated users who make a first in-store tap within 14 days of activation. Target: set from the pilot baseline.
3. Guardrail: approval rate (approved taps / attempted taps), no more than 1 pp below control, and default-settled share within the limit agreed with Risk.
- **Bad signal to watch for:** High card activation but low in-store taps = the message landed but the till is still not trusted. Also: approval rate dropping, or a rising default-settled share = usage bought with surprise charges.
- **Likely post-launch decision:** Iterate. If the lift is real but below 5 pp, fix the funnel (notification, decision step, default window) and retest. Double down (widen from M to L) only if lift is 5 pp or more and the guardrails hold for 30 days. Stop if there is no lift after 30 days or any guardrail breach.
