# US Fintech & Deposit-Focused Companies Offering Credit Products

## A Detailed Guide to No-Personal-Guarantee Products, Soft-Pull Prequalification, and ITIN Accessibility

**Prepared:** June 4, 2026
**Scope:** US fintechs and deposit-focused neobanks offering **business/corporate cards** and **business loans / lines of credit**, with a focus on applicants who hold **only an ITIN** (no SSN).

---

## How to read this report

Three terms get used loosely in the market. Getting them straight is the key to the whole report:

| Term | What it actually means | Why it matters for an ITIN holder |
|---|---|---|
| **No Personal Guarantee (no-PG)** | The business — not you personally — is liable for the debt. You don't pledge personal assets. | Common on cash-balance corporate cards. Does **not** by itself mean "no SSN needed." |
| **No personal credit pull** | The issuer never touches your personal credit file — not even a soft inquiry. Underwriting rests on business cash balance, raised capital, or platform sales. | **The best outcome** for a thin-file or ITIN-only applicant — your personal credit (or lack of it) is irrelevant. |
| **Soft-pull prequalification** | The issuer does a *soft* personal-credit inquiry (no score impact) to generate a real, non-binding offer. A *hard* pull lands only when you accept or draw funds. | Your personal credit **is** checked — just gently, and only until you commit. Still needs a personal identifier (SSN **or ITIN**). |

A critical, repeated finding: **"no-PG" and "no SSN" are different things.** Almost every legitimate no-PG corporate card still verifies the *identity* of a beneficial owner (KYC / USA PATRIOT Act). That identity step — not the underwriting — is where ITIN-only applicants hit friction.

> **The single most important takeaway:** For an ITIN-only founder, the strongest products are those that do **no personal credit pull at all** and accept an **ITIN or passport** at the identity step — because then neither your credit file nor your lack of an SSN is a gate. The next best are platform/embedded lenders that underwrite on your sales history.

---

## PART 1 — The Big Picture: Is Having Only an ITIN an Issue?

**Bottom line: Having only an ITIN is *not* a hard blocker, but it narrows your options and — as of mid-2026 — is becoming a bigger friction point.**

There are three distinct pathways into US business credit, and an ITIN-only founder can use all three:

1. **Personal-credit-based business cards** (e.g., Chase Ink, Capital One Spark, Amex Business). These explicitly accept an **ITIN in place of an SSN**, pull your personal credit, and require a personal guarantee. This is the *most firmly documented* ITIN path — but it requires a personal credit history.

2. **Cash-flow / no-PG corporate cards** (Brex, Ramp, Rho, Mercury IO, Stripe). These underwrite on your **business bank balance or raised capital**, not personal credit — so no PG and often **no personal credit pull at all**. The catch: they still collect a personal identifier for KYC. Whether they accept an ITIN/passport at that step varies by issuer and is the make-or-break variable.

3. **EIN-only business credit** (net-30 vendors + business bureaus). Builds a *business* credit file keyed to your EIN/DUNS — essentially no personal-identity barrier beyond the EIN, which an ITIN holder can obtain.

### Why issuers ask for an SSN even on "business" products

The SSN request usually serves one of two *separable* functions:

- **Underwriting** — only relevant for products that pull your *personal* credit (path 1). Pulling credit requires a personal identifier, and bureaus *can* generate a report keyed to an ITIN.
- **Identity / KYC / AML** — required on virtually everything under the **USA PATRIOT Act (CIP rule)**, the **beneficial-ownership (CDD) rule**, and **OFAC** screening. For a *non-US person*, the CIP rule explicitly allows an **SSN, ITIN, EIN, or passport number** as a valid identifier. So banks *can* legally accept an ITIN — whether a given fintech *does* is a policy choice.

**Key insight:** On no-PG cash-balance cards, the SSN ask is almost always a KYC/identity requirement, not an underwriting one. That's the boundary where an ITIN-only founder's experience differs by issuer.

### ⚠️ New 2026 regulatory headwind

A **May 2026 Executive Order, "Restoring Integrity to America's Financial System,"** directs federal regulators to treat customer immigration status as a financial-risk factor. It specifically states that **use of an ITIN to obtain credit products or open deposit accounts where the applicant lacks verified lawful immigration status may be flagged as a risk factor requiring enhanced due diligence.**

Critically:
- It does **NOT** ban ITIN accounts or ITIN credit applications, and does **not** require banks to close existing accounts or collect citizenship data from current customers (a mandatory-data-collection draft provision was dropped after industry pushback).
- Treasury was directed to issue a **red-flags advisory (~mid-July 2026)** and propose **BSA rule changes (~mid-August 2026)**.
- **Practical effect:** an ITIN-only applicant may face **more identity questions and enhanced due diligence**, especially without verified lawful status — but ITIN credit access remains legal.

*This is a fast-moving area. Reconfirm the current Treasury guidance before applying.*

---

## PART 2 — No-Personal-Guarantee Corporate & Business Cards

These underwrite on business cash/capital, not your personal credit. **No-PG ≠ no-SSN** — the ITIN column is what matters for you.

| Company | Product type | No PG? | Personal credit pull? | ITIN / no-SSN path | Key approval requirements |
|---|---|---|---|---|---|
| **Ramp** | Corporate charge card | ✅ Yes | ❌ None | ✅ **Strongest documented** — apply with foreign **passport + proof of address** instead of SSN | ~$25K in a US business bank account; incorporated/LLC/partnership (no sole props); mostly US operations |
| **Stripe Corporate Card** | Charge card (Stripe Issuing) | ✅ Yes | Soft only (no hard) | ✅ Underlying Stripe account **explicitly accepts ITIN** (and non-US tax IDs) | Must be an existing Stripe processing customer; limit from processing volume |
| **Brex** | Corporate charge card | ✅ Yes | ❌ None | ⚠️ EIN-forward, but **excludes non-US-registered companies**; ITIN at KYC *unverified* | ~$50K cash balance (funded startups); US-registered C/S-corp, LLC, LLP only; connect bank account |
| **Rho** | Corporate charge card | ✅ Yes | ❌ None | ⚠️ Non-residents effectively need a US address or a US SSN-holder on the account | US corp/LLC/LP; underwrites raised capital + cash on hand; works pre-revenue |
| **Mercury IO** | Charge card (cash-backed) | ✅ Yes | ❌ None | ⚠️ Business accounts open with passport+EIN; **Personal accounts reject ITIN**; IO-via-ITIN *unverified* | Hold a qualifying Mercury balance (~$25K for meaningful limits); US entity + EIN |
| **Revenued** | Prepaid Visa + revenue-based Flex Line | ✅ Yes | ❌ None (no credit check) | ⚠️ Plausibly accommodating (revenue-only), but *unverified* | ≥1 yr in business; ≥$20K/mo bank deposits; no sole props |
| **Emburse** | Commercial Mastercard (spend platform) | ✅ Yes | ❌ None indicated | ⚠️ FAQ allows "personal *or business* ID number"; ITIN-specific *unverified* | Enterprise-oriented; verify one control person's identity |
| **Navan** | Corporate charge card | ✅ Yes | ❌ None (company-level) | ⚠️ *Unverified*; aimed at larger firms | ~$4M+ revenue typical; assessed at company level |
| **BILL Divvy (Spend & Expense)** | Charge card / spend line | ⚠️ Conditional | Soft pull | ⚠️ *Unverified* | ~$20K bank balance or steady cash flow; ≥3 mo in business |
| **Capital on Tap** | Revolving business credit card | ❌ **No — PG required** | Soft on personal + hard on business | ⚠️ Uses EIN/SSN; ITIN *unverified* | EIN for LLC/Corp; ~670+ FICO improves odds; ~$25K balance |
| **Torpago** | Corporate charge card | ⚠️ Conditional (carve-out) | Marketed none | ⚠️ *Unverified* | **Reportedly no longer accepting direct applications** — verify availability |

### The standouts for an ITIN-only founder

- **Ramp** — the best-documented *no-SSN* path: their own onboarding lets an owner/officer apply with a foreign passport + proof of address. No PG, no personal credit pull.
- **Stripe Corporate Card** — the underlying Stripe account *explicitly* accepts an ITIN (and non-US tax IDs). No PG, no hard pull. Caveat: you must be a Stripe processing customer and limits derive from volume.
- **Revenued** — no PG and no credit check at all (revenue-only), so SSN/FICO are largely irrelevant — though explicit ITIN acceptance is unverified and it's technically revenue-based financing, not a true card.

**Watch-outs:** *Capital on Tap is NOT no-PG* (a personal guarantee is required despite a soft personal pull — proof that "soft pull" ≠ "no PG"). *Brex's* policies may shift following its **Capital One acquisition (closed ~April 2026)**. *Torpago* appears unavailable to new direct applicants.

---

## PART 3 — Business Loans & Lines of Credit (Soft-Pull Prequalification)

This is where soft-pull prequalification lives. The table separates *whether* there's a soft prequal from *when* the hard pull lands and *whether* a PG is required.

| Lender | Product | Soft-pull prequal? | Hard pull stage | PG required? | ITIN | Key requirements |
|---|---|---|---|---|---|---|
| **Bluevine** | Line of credit (≤$250K) | ✅ Yes | On acceptance | ✅ Yes | ✅ **Accepts SSN or ITIN** (+ passport route) | 12+ mo; $120K+ revenue; FICO 625+ |
| **Fundbox** | Line of credit | ✅ Yes | On **first draw** | ✅ Yes | ⚠️ Unverified | 600 FICO; 3–6 mo; bank-data underwriting |
| **OnDeck** | Term loan + LOC | ✅ Yes | On acceptance | ✅ Yes (+ lien on term) | ⚠️ Unverified | 625+ FICO; $100K+ revenue; 1+ yr |
| **Amex Business Blueprint** (ex-Kabbage) | Line of credit | ❌ **No — hard pull upfront** | At application | ✅ Yes | ⚠️ Unverified | 660 FICO; 1+ yr; ~$3K/mo revenue |
| **Credibly** | MCA / working capital / LOC | ✅ Yes | If you proceed | ✅ Yes | ⚠️ Unverified | 500 FICO (MCA); $15K/mo revenue; 6 mo |
| **Backd** | LOC + working capital | ⚠️ Claimed (unverified) | Unverified | ❌ **No PG on the LOC** | ⚠️ Unverified | ~650 FICO; 1–2 yr; high revenue floor |
| **National Funding** | Working capital / equipment | ✅ Yes | At final decision | ⚠️ Likely | ⚠️ Unverified | ~600 FICO; 6+ mo; ~$250K revenue |
| **Rapid Finance** | Term / LOC / MCA | ⚠️ "No-hard-check" prequal, but **hard pull on full app** | At application | ✅ Yes | ⚠️ Unverified | 2+ yr / ~$120K revenue best |
| **Giggle Finance** | Revenue-based (gig/1099) | ✅ Yes (no score-based UW) | — | ✅ (MCA, assumed) | ⚠️ Unverified (very accessible model) | 3+ mo; 1099 income; bank link |
| **Mercury** | Working capital / venture debt | Unverified | Unverified | ❌ **No PG (working capital)** | ⚠️ Unverified | Ecommerce/VC focus; **not available in CA** |
| **Lendio** | Marketplace (75+ lenders) | ✅ Yes | At matched lender | Varies | Depends on lender | Varies |
| **Fundera (NerdWallet)** | Marketplace | ✅ Yes | At matched lender | Varies | Depends on lender | Varies |
| **Funding Circle** | Term / LOC / SBA | ✅ Usually | Some structures / SBA | ✅ Yes (+ lien) | ❌ Not for SBA | 660 FICO; 2+ yr; $50K revenue |

### Embedded / platform lenders — underwrite on sales, not credit (best for ITIN)

These never pull personal credit; they fund off your platform sales history. The first three explicitly treat ITIN as identity-only.

| Lender | Product | Personal credit pull? | PG required? | ITIN | Requirements |
|---|---|---|---|---|---|
| **Shopify Capital** | MCA / term loan from Shopify sales | ❌ None | ❌ No | ✅ **Explicitly SSN *or* ITIN** | Active Shopify store w/ sales; invitation-based |
| **Stripe Capital** | Advance on Stripe volume | ❌ None | ❌ No | ✅ **Explicitly SSN *or* ITIN** | Stripe processing history; offer-based |
| **Square Loans** | Loan repaid via card sales | ❌ None | ❌ No (≤$250K); ✅ >$250K | ✅ **SSN or ITIN (identity only)** | Square processing history; ~$10K+/yr |
| **PayPal Working Capital** | Advance on PayPal sales | ❌ None | ❌ No | ⚠️ Likely (unpublished) | PayPal account 90+ days; $15K–$20K/yr sales |
| **PayPal Business Loan** (LoanBuilder) | Fixed-fee term loan | Soft → hard on accept | ✅ Yes | ⚠️ Unverified | 580+ FICO; 9+ mo; ~$33K revenue |

> ⚠️ **Avoid the SBA path if you're ITIN-only:** 2026 SBA rules (Policy Notice 5000-876441) require **100% US-citizen/national ownership**, disqualifying ITIN-only owners. This affects SBA loans routed through Lendio, Fundera, Funding Circle, Live Oak, etc.

### Synthesis

- **True soft-pull prequal (credit checked, but softly until you commit):** Bluevine, Fundbox, OnDeck, Credibly, National Funding, PayPal Business Loan, and the marketplaces (Lendio, Fundera). Marketplaces are the efficient way to comparison-shop on a single soft pull.
- **No personal credit pull at all:** Shopify Capital, Stripe Capital, Square Loans, PayPal Working Capital, Mercury Working Capital, and (per reviews) Backd's LOC.
- **Worst for rate-shopping:** Amex Business Blueprint (hard pull upfront, no soft option) and Rapid Finance (markets "no-hard-check" prequal but hard-pulls on the real application).

---

## PART 4 — Deposit-Focused Neobanks & Their Credit Products

**Key finding:** No mainstream business-banking fintech offers a *true underwritten revolving credit line* an ITIN-only newcomer can easily access. The ITIN-accessible credit at these companies is almost entirely **cash-balance charge cards** (Mercury IO, Rho, Meow) that do no personal credit pull — so an SSN isn't a *credit* gate, only KYB is.

| Company | Deposit ITIN-friendly? | Credit product | No PG? | Credit pull | Notes |
|---|---|---|---|---|---|
| **Mercury** | ✅ Business: passport + EIN, no SSN | IO charge card | ✅ Yes | ❌ None | Strongest combined deposit+credit story for non-resident *business* founders. Personal accounts are SSN-only. Tightened address KYB in 2025. |
| **Wise (Business)** | ✅ **Most flexible** (SSN, ITIN, or ID+selfie) | ❌ None | — | None | Great for ITIN deposits; **no credit product at all**. |
| **Bluevine** | ✅ SSN or ITIN for identity | Real revolving LOC | ❌ No (PG req'd) | Soft → hard | Has *real* credit, but LOC needs FICO 625+, 12 mo, $120K revenue + PG — hard for a new ITIN-only founder. |
| **Baselane** | ✅ **Explicitly SSN or ITIN** | Partner loans only | n/a | n/a | Real-estate niche; no native credit card. |
| **Novo** | ✅ Listed SSN or ITIN | Invite-only card + MCA "Funding" | n/a | Soft (Funding) | Card is invite-only; Funding is an MCA (~$500/mo revenue). |
| **Relay** | ⚠️ SSN expected for owners | Cashback card | Unverified | None for opening | Good for foreign-*owned* US LLCs, but owner-level SSN expected; ITIN substitution unconfirmed. |
| **NorthOne** | ⚠️ SSN expected | Marketplace LOC/loans | Per lender | Per lender | Credit is a referral, not native. |
| **Lili** | ✅ Non-resident: passport + EIN | ❌ None | — | — | No credit product. Conflicting SSN guidance (resident vs non-resident flows). |
| **Rho** | ⚠️ Unverified | Corporate charge card | ✅ Yes | ❌ None | No published ITIN support; US-incorporation oriented. |
| **Meow** | ⚠️ Unverified | Corporate card | ✅ (inferred) | ❌ None (inferred) | Treasury/startup focus; not immigrant-targeted. |
| **Grasshopper / Live Oak** | ❌ SSN-based (chartered banks) | Cards / SBA loans | ❌ No (PG req'd) | Hard | Traditional underwriting; least ITIN-relevant. |

### Immigrant / ITIN-focused providers

| Company | Type | ITIN | Credit product |
|---|---|---|---|
| **Comun** | Consumer neobank (Latino immigrants) | ✅ Opens with ITIN/passport, no SSN | Deposit + nascent/secured credit-builder |
| **Majority** | Consumer neobank (immigrants) | ✅ ITIN accepted (may not even be required) | **No credit product** |
| **Welcome Tech / SABEResPODER** | Immigrant services + banking (Green Dot) | ✅ ITIN-friendly | Partner-mediated credit (thin detail) |
| **Camino Financial** | Immigrant *business* lender | ✅ **Secured/micro loans accept ITIN-only** (no min FICO) | **Unsecured loans require SSN** |
| **Tomo** | Consumer credit card | ✅ Accepts ITIN | Credit card (cash-flow underwriting) |
| **Petal** | Consumer credit card | ✅ Accepts ITIN/passport/visa | Credit card *(verify still issuing in 2026)* |
| **Self** | Consumer credit-builder | ✅ SSN or ITIN | Credit-builder account + secured Visa, no hard pull |
| **Sequin** | Consumer debit + credit-building | ❌ **SSN required** | Debit (not a credit line) |
| **Stilt** | Was immigrant lender | — | **Effectively defunct** (platform sold to J.G. Wentworth, 2022) |
| **Nova Credit / Highnote** | Infrastructure (not openable accounts) | n/a | *Power* ITIN-friendly products at other issuers (e.g., Amex newcomer underwriting) |

---

## PART 5 — The EIN-Only Pathway: Build Business Credit Without an SSN

This is the most reliable, lowest-friction route for an ITIN-only founder because it leans on the *business* identity, not yours.

1. **Form a US LLC or corporation** and obtain an **EIN** from the IRS — an ITIN holder qualifies to request one.
2. **Get a free D-U-N-S number** from Dun & Bradstreet (tied to the EIN, not your SSN).
3. **Open net-30 vendor accounts** that report to business bureaus with EIN only (no personal credit check):
   - **Uline** — reports to all 3 business bureaus; needs business name + EIN; orders ~$50+ to be reported.
   - **Quill** — easy approval; EIN + ~30 days in business; reports to D&B.
   - **Grainger** — EIN + ~3 months in business; DUNS ideal.
   - **Crown Office Supplies** — no personal credit check; 90 days in business; active EIN.
4. **Add Nav Prime** to report 1–2 monthly tradelines to D&B, Experian Business, and Equifax Business.
5. The three **business bureaus** (D&B PAYDEX, Experian Business, Equifax Business) typically surface payment history after ~60–120 days.

This builds a **business** credit profile independent of your personal SSN/ITIN.

> **Note:** Avoid older guides citing **Nearside** (shut down 2022/23) or the **Tillful card** (acquired by Nav in 2023; card discontinued — use **Nav Prime** instead).

---

## PART 6 — Recommended Action Plan for an ITIN-Only Founder

**Foundation (do first):**
1. Register a US LLC/corporation; get an **EIN** using your ITIN.
2. Secure a **US business address** and open a **US business bank account**. If traditional banks balk, use **Mercury (Business)**, **Wise**, **Comun**, or **Majority** — all open with ITIN/passport.
3. Register a free **D-U-N-S** number.

**(a) For a no-PG corporate card:**
4. Fund the business account with a real balance (~$25K helps for Ramp; ~$50K for Brex).
5. Apply to **Ramp** (best no-SSN path) or **Stripe Corporate Card** (explicit ITIN). Have your **ITIN, passport, and EIN** ready, and **ask the issuer directly whether ITIN/passport satisfies the beneficial-owner identity check** — this is the make-or-break step and is not uniformly documented.
6. In parallel, build EIN-only net-30 tradelines + Nav Prime.

**(b) For business financing:**
7. If you sell on a platform, pursue **Shopify Capital / Stripe Capital / Square Loans** — no credit pull, no PG, explicit ITIN acceptance (identity only).
8. For a credit-underwritten line, **Bluevine** openly accepts ITIN (but requires FICO 625+, $120K revenue, and a PG).
9. For a term loan, use **Camino Financial's secured/micro business loan** (accepts ITIN-only, no min FICO).
10. **Avoid the SBA path** — 2026 rules require 100% US-citizen ownership.

**(c) If you need to build personal credit first:**
11. **Self** (credit-builder + secured Visa, ITIN OK, no hard pull) and consumer cards like **Tomo** / **Petal** (ITIN accepted) can establish a personal file that later unlocks personal-credit business cards (Chase Ink, Capital One Spark, Amex Business — all accept ITIN).

---

## Quick-Reference: Best Bets for an ITIN-Only Applicant

| Need | Best options | Why |
|---|---|---|
| **No-PG corporate card** | **Ramp**, **Stripe Corporate Card** | No PG, no personal credit pull, documented no-SSN/ITIN path |
| **Business financing, no credit pull** | **Shopify / Stripe / Square Capital** | Sales-based, no PG, explicit ITIN (identity only) |
| **Real revolving credit line** | **Bluevine** | Openly accepts ITIN (but PG + FICO 625+ required) |
| **Business term loan, ITIN-only** | **Camino Financial** (secured/micro) | Rare business loan accepting ITIN-only, no min FICO |
| **ITIN-friendly business deposits** | **Mercury (Business)**, **Wise**, **Baselane** | Open with passport/ITIN + EIN, no SSN |
| **Build personal credit (ITIN)** | **Self**, **Tomo**, **Petal** | Accept ITIN; no/soft pull |
| **Build business credit (EIN-only)** | **Uline, Quill, Grainger, Crown + Nav Prime** | No personal credit check at all |

---

## Important Caveats & Methodology

- **Point-in-time data.** This reflects publicly available information as of June 2026. Fintech approval criteria, ITIN policies, and product availability change frequently. **Confirm every figure directly with the provider before applying.**
- **ITIN acceptance is firmly verified only where stated.** It is *explicitly documented* for Stripe, Shopify Capital, Square Loans, Bluevine (identity), Self, Tomo, Petal, Camino (secured), Comun, Majority, and Wise. For Ramp the verified path is "foreign passport instead of SSN." For Brex, Mercury IO, Rho, Meow, and most loan products, ITIN acceptance is **unverified** — treat as "ask first."
- **"No-PG" never means anonymous.** Beneficial-owner KYC identity is always required.
- **Moving targets:** Brex's policies may change post–Capital One acquisition (closed ~April 2026). Torpago appears unavailable to new direct applicants. Stilt is defunct. Petal's 2026 issuing status should be verified. The May 2026 Executive Order on ITIN/immigration banking is still being implemented (Treasury guidance due summer 2026).
- **Not legal or financial advice.** Consult a qualified advisor for your specific situation.

---

*Report compiled from research across no-PG corporate cards, fintech business lending, deposit-focused neobanks, ITIN-access analysis, and the soft-pull prequalification landscape. Sources include company help centers and product pages (Brex, Ramp, Rho, Mercury, Stripe, Bluevine, Shopify, Square, PayPal, Comun, Majority, Camino, Self, Wise, and others), independent reviews (NerdWallet, Nav, Bankrate, Merchant Maverick, Finder), and regulatory/legal sources (FinCEN CIP guidance, Federal Register CDD rule, White House Executive Order, Mayer Brown, Time).*
