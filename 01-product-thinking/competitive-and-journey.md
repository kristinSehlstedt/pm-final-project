# Competitive Analysis & Journey Map (Module 2)

## Responses
- **Role, who are you solving for? (the specific user segment or profile):** Aylin, 30, HR specialist, Nuremberg (P09)

Role: A heavy BNPL user (8 purchases a month) and Riverty Flex user who also carries Klarna and PayPal and falls back to her debit cards everywhere else.
- **Goal, what is this user ultimately trying to achieve?:** Keep the "decide first, pay after" convenience she already treats as the default online, in any shop she walks into.
- **Friction, the main barrier (moment of misery) stopping them from succeeding:** Her Moment of Misery is the till. Online she uses pay later on almost every order, but in a shop she has no way to decide later and pay afterwards from home. She says she would use a Riverty card in stores only if that option came with it. Her closest research quote is about a conditional wish, so the till scene is inferred from it and not something she described directly. A corroborating, explicit version comes from another participant, Mara (P01), who says that in a shop she is back to her debit card because pay later just doesn't exist there for her.
- **External tools, the outside platforms or tools the user is forced to use:** Klarna, PayPal
- **The process, the 3 to 5 manual steps the user takes to get the job done:** Online, she taps a pay-later provider by default (documented). She says she uses pay later on almost every order. She holds Klarna, PayPal and Riverty accounts, and her segment (Checkout Default) is defined by choosing whatever is easiest, so which brand wins is a matter of what's offered first.
If the merchant doesn't offer Riverty, she uses Klarna or PayPal (inferred). This is the "everything outside its merchant base" part of your hook. Another participant (P03) describes Riverty as what shows up when the shop has it. For Aylin the data doesn't say this step happens or how often.
In a shop, she pays with her Girocard or Visa debit (partly documented). Her profile lists both. Mara's quote supplies the behaviour: "In a shop I'm back to my debit card." For Aylin the fallback is inferred from her cards held and her conditional wish.
The money leaves her account at the till (inferred from how debit works). The keep decision hasn't been made yet, and she has no pay-after-the-fact option, which is exactly what she says she'd want from a Riverty card in stores.
Any manual workaround, such as buying online instead of in-store, is not in the data. If she has one, it still needs to be found out.
- **Core frustration, the exact moment the process feels most “broken”:** It gives up what she values most. The pay-after-keep benefit is the one thing she says would bring her to a card, and debit removes it entirely.
It splits her behaviour across tools. Online she may use three providers and in-store a fourth, with no single place to see what she owes. This is inferred, not stated by her.
It is brittle. The one wish she voiced (decide later, pay afterwards, from home) has no equivalent at the till, so the fallback depends on a product that was never built for the situation.
It's invisible to Riverty. Nothing in her file shows she is dissatisfied or leaving. She is a heavy user who simply spends outside Riverty at the point of sale.
- **The evidence, a specific quote or behavior from the research that proves this:** Spend goes to someone else. In-store purchases land on debit, and online ones may land on Klarna or PayPal. The business case assumes year-1 spend of €4,000 per active user, rising to €7,000, and the survey's stated spend for high-intent respondents (about €3,744) already sits below that. Aylin is the kind of heavy user that assumption relies on.
Habit without loyalty. Only about 7% of survey respondents name Riverty as their first checkout choice, and Aylin's own segment picks on convenience. This backs your hook's worry about habits hardening, but only as a risk. Nothing in the data shows habits changing over time.
No in-store foothold. The research names the in-store gap as one of the strategic gaps, and each month without a card leaves her fallback on someone else's rails.
Her profile fits the intent signal. About 40% of heavy BNPL users show high intent to apply, against about 11% for light users, so she sits in the segment most open to a card.
- **Your journey map, a shareable link, or the map file you committed (e.g. journey-map.html):** <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Future-state journey map: Aylin and the Riverty card</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Schibsted+Grotesk:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --paper:#F6F7F3;
  --ink:#12231F;
  --ink-2:#4A5A55;
  --line:#D5DBD3;
  --mint:#CFEBDD;
  --mint-ink:#0E5A43;
  --pain:#FBE8E4;
  --pain-ink:#8A2A1B;
  --card:#FFFFFF;
  --font:"Schibsted Grotesk",system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;
}
*{box-sizing:border-box}
html{background:var(--paper)}
body{margin:0;font-family:var(--font);color:var(--ink);line-height:1.5;font-size:15px}
.wrap{max-width:1120px;margin:0 auto;padding:40px 24px 64px}
header{display:grid;grid-template-columns:1.1fr 1fr;gap:32px;align-items:end;padding-bottom:28px;border-bottom:1px solid var(--line)}
h1{font-size:34px;line-height:1.15;font-weight:600;margin:0 0 10px;letter-spacing:-0.01em}
h2{font-size:20px;font-weight:600;margin:0 0 14px}
.sub{color:var(--ink-2);margin:0;max-width:52ch}
.persona{background:var(--card);border:1px solid var(--line);border-radius:6px;padding:16px 18px}
.persona p{margin:0 0 8px;font-size:14px}
.persona p:last-child{margin:0}
.persona b{font-weight:600}
.map{margin-top:32px;display:grid;grid-template-columns:128px repeat(4,1fr);column-gap:12px;row-gap:12px}
.lane{font-size:13px;color:var(--ink-2);padding-top:12px;font-weight:500}
.stagehead{background:var(--ink);color:#fff;border-radius:6px;padding:12px 14px;font-weight:600;font-size:16px;display:flex;gap:10px;align-items:baseline}
.stagehead span{font-weight:400;opacity:.7;font-size:13px}
.cell{background:var(--card);border:1px solid var(--line);border-radius:6px;padding:12px 14px;font-size:14px}
.cell.pain{background:var(--pain);border-color:#F0C9C2;color:var(--pain-ink)}
.cell ul{list-style:none;margin:0;padding:0;display:grid;gap:10px}
.cell li{font-size:13.5px}
.cell li i{font-style:normal;color:var(--mint-ink);font-weight:600;padding:0 4px}
.curve{grid-column:2 / span 4;position:relative;height:120px;background:var(--card);border:1px solid var(--line);border-radius:6px}
.curve svg{position:absolute;inset:0;width:100%;height:100%}
.curve .dot{position:absolute;width:14px;height:14px;border-radius:50%;background:var(--mint-ink);border:3px solid var(--mint);transform:translate(-50%,-50%)}
.curve .note{position:absolute;right:12px;bottom:8px;font-size:12px;color:var(--ink-2)}
.curve .hi,.curve .lo{position:absolute;left:12px;font-size:12px;color:var(--ink-2)}
.curve .hi{top:8px}.curve .lo{bottom:8px}
.mob-label{display:none}
.adv,.caveats{margin-top:44px}
.advgrid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
.advgrid div{background:var(--mint);border-radius:6px;padding:16px 18px}
.advgrid h3{margin:0 0 6px;font-size:16px;font-weight:600;color:var(--mint-ink)}
.advgrid p{margin:0;font-size:14px}
.caveats ul{margin:0;padding-left:20px;color:var(--ink-2);font-size:14px;display:grid;gap:6px;max-width:80ch}
.caveats b{color:var(--ink);font-weight:600}
a:focus-visible,button:focus-visible{outline:3px solid var(--mint-ink);outline-offset:2px}
@media (max-width:860px){
  header{grid-template-columns:1fr}
  .map{grid-template-columns:1fr}
  .lane{display:none}
  .mob-label{display:block;font-size:12px;color:var(--ink-2);font-weight:500;margin-bottom:4px}
  .curve{display:none}
  .stagehead{margin-top:12px}
  .advgrid{grid-template-columns:1fr}
  h1{font-size:28px}
}
@media print{
  html{background:#fff}
  .wrap{padding:16px}
  .stagehead{-webkit-print-color-adjust:exact;print-color-adjust:exact}
}
</style>
</head>
<body>
<div class="wrap">

<header>
  <div>
    <h1>Future-state journey: Aylin and the Riverty card</h1>
    <p class="sub">Four stages from application to settlement, built around one idea: keep it first, pay later, in any shop. As of 6 Oct 2026.</p>
  </div>
  <div class="persona">
    <p><b>Aylin, 30, HR specialist, Nuremberg (P09).</b> A heavy BNPL user (8 purchases a month) and Riverty Flex user who also carries Klarna and PayPal and falls back to her debit cards everywhere else.</p>
    <p><b>Goal:</b> keep the "decide first, pay after" convenience she treats as the default online, in any shop she walks into.</p>
  </div>
</header>

<section class="map" aria-label="Journey map">

  <div class="lane"></div>
  <div class="stagehead">1 <span>Apply in the app</span></div>
  <div class="stagehead">2 <span>Add to phone wallet</span></div>
  <div class="stagehead">3 <span>Pay at the till</span></div>
  <div class="stagehead">4 <span>Keep or return at home</span></div>

  <div class="lane">User action</div>
  <div class="cell"><div class="mob-label">User action</div>Opens the Riverty app and taps the card offer.</div>
  <div class="cell"><div class="mob-label">User action</div>Adds the card to Apple Pay or Google Pay and sets her own limit.</div>
  <div class="cell"><div class="mob-label">User action</div>Taps her phone at a shop terminal.</div>
  <div class="cell"><div class="mob-label">User action</div>Reviews purchases at home, returns some, and repayment settles automatically.</div>

  <div class="lane">Internal state</div>
  <div class="cell"><div class="mob-label">Internal state</div>Interested but wary of a credit check.</div>
  <div class="cell"><div class="mob-label">Internal state</div>Impatient, expecting it to just work.</div>
  <div class="cell"><div class="mob-label">Internal state</div>Confident, the same default she has online.</div>
  <div class="cell"><div class="mob-label">Internal state</div>In control, with no rolling debt.</div>

  <div class="lane">Mood trend</div>
  <div class="curve" role="img" aria-label="Qualitative mood line: cautious at application, dips at wallet setup, rises at the till, highest at settlement">
    <svg viewBox="0 0 400 120" preserveAspectRatio="none" aria-hidden="true">
      <polyline points="50,74 150,88 250,40 350,26" fill="none" stroke="#0E5A43" stroke-width="2" vector-effect="non-scaling-stroke"/>
    </svg>
    <span class="hi">Positive</span>
    <span class="lo">Negative</span>
    <span class="dot" style="left:12.5%;top:62%"></span>
    <span class="dot" style="left:37.5%;top:73%"></span>
    <span class="dot" style="left:62.5%;top:33%"></span>
    <span class="dot" style="left:87.5%;top:22%"></span>
    <span class="note">Qualitative and inferred, not measured</span>
  </div>

  <div class="lane">Pain point addressed</div>
  <div class="cell pain"><div class="mob-label">Pain point addressed</div>Credit-check anxiety.</div>
  <div class="cell pain"><div class="mob-label">Pain point addressed</div>No wallet support, called "dead on arrival" by one participant.</div>
  <div class="cell pain"><div class="mob-label">Pain point addressed</div>No pay later at the till.</div>
  <div class="cell pain"><div class="mob-label">Pain point addressed</div>Paying before deciding, plus refund and debt fears.</div>

  <div class="lane">Action to benefit</div>
  <div class="cell"><div class="mob-label">Action to benefit</div><ul>
    <li>Prefilled Flex details<i>&rarr;</i>fewer steps to apply.</li>
    <li>Soft eligibility check<i>&rarr;</i>less fear of a Schufa hit before committing.</li>
  </ul></div>
  <div class="cell"><div class="mob-label">Action to benefit</div><ul>
    <li>Instant wallet provisioning<i>&rarr;</i>card usable before her next shop visit.</li>
    <li>Self-set spending cap<i>&rarr;</i>she stays in control instead of drifting to a limit.</li>
  </ul></div>
  <div class="cell"><div class="mob-label">Action to benefit</div><ul>
    <li>Tap at any Mastercard terminal<i>&rarr;</i>the same fast habit as online.</li>
    <li>Pay later applied in-store<i>&rarr;</i>no keep decision forced at the counter.</li>
  </ul></div>
  <div class="cell"><div class="mob-label">Action to benefit</div><ul>
    <li>Review items at home<i>&rarr;</i>decide before the money commits.</li>
    <li>Fixed automatic repayment<i>&rarr;</i>predictable monthly cost, no rolling debt.</li>
    <li>Return items in-app<i>&rarr;</i>refunds stay quick and clean.</li>
  </ul></div>

</section>

<section class="adv">
  <h2>Three competitive advantages over the manual workaround</h2>
  <div class="advgrid">
    <div><h3>Pay later where debit can't</h3><p>Today her debit card pulls money at the till before she has decided. The card moves that decision to after the purchase, as she already does online.</p></div>
    <div><h3>One place to see what she owes</h3><p>Today her spending is split across debit, Klarna, PayPal and Riverty. One card gives her a single repayment view.</p></div>
    <div><h3>A direct relationship at purchase</h3><p>Today the in-store habit builds around her debit card and a rival brand at no cost to them. The card puts Riverty at the till and gives it a direct view of her spending.</p></div>
  </div>
</section>

<section class="caveats">
  <h2>Caveats</h2>
  <ul>
    <li><b>All source data is synthetic.</b> The research workbook was generated for a case exercise. Treat this journey as a hypothesis, not a finding.</li>
    <li><b>The in-store mechanic is the biggest assumption.</b> Nothing in the research shows that "decide later" can work on a card at the till. Stage 3 is a design hypothesis.</li>
    <li><b>Pain points are not all Aylin's.</b> Credit-check anxiety (stage 1) and wallet support (stage 2) come from other participants (P07, P10, P02, P11). Her own quotes (Q025, Q026, Q027) cover stages 3 and 4.</li>
    <li><b>"Why launch now" points are taken as given.</b> The CCD2 exemption, the Mastercard and Paymentology platform and the Amazon Business pilot timing are not in the research file and were not verified.</li>
    <li><b>Strategy line interpretation.</b> "Fastest for everyday work" is read here as the fastest everyday checkout for Aylin.</li>
  </ul>
</section>

</div>
</body>
</html>
