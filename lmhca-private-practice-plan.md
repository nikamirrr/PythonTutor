# LMHCA Private Practice — Business Plan

**Location:** Redmond, Washington · **Model:** Solo, telehealth-only · **Entity:** Washington PLLC
**Last revised:** 2026-08-23 · **Status:** Pre-launch

> **How to use this document.** Every requirement below carries a link to the authority that
> defines it. Dollar figures are current as of the revision date; anything marked **[verify]**
> should be re-checked at the moment of filing or purchase. Costs that are required but not yet
> quoted are shown as ranges with stated assumptions — never as "TBD" — so the total stays honest.

---

## 1. Fixed decisions


| #   | Decision                 | Choice                                                                                                                                                                                                                                                                                |
| --- | ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Legal entity             | Washington PLLC                                                                                                                                                                                                                                                                       |
| 2   | Principal office         | **Redmond apartment / home office.** Must be a physical street address — no PO Box or PMB. See §2.3.                                                                                                                                                                                  |
| 3   | Business mailing address | **Home address at launch** — allowed, free, and removes the business-associate question entirely (§2.4). Revisit a HIPAA-capable virtual mailbox (VirtualPostMail Business, with BAA) once volume justifies it (§2.5).                                                                |
| 4   | Mail handling            | Delivered to home. Written handling rules in §2.4. Paper containing client information goes to a **locked cabinet**; disposal by cross-cut shredding.                                                                                                                                 |
| 5   | Domain registrar         | Cloudflare Registrar                                                                                                                                                                                                                                                                  |
| 6   | Business email           | Microsoft 365 Business Basic (no Teams)                                                                                                                                                                                                                                               |
| 7   | Phone / SMS              | iPlum **Professional** (HIPAA, BAA) — browser on the work computer **and** the app on the iPhone 12, one number across both (§5.4).                                                                                                                                                   |
| 8   | EHR                      | SimplePractice                                                                                                                                                                                                                                                                        |
| 9   | Telehealth video         | **SimplePractice Starter** — verified included, with **no limit on session count or length**. Psychology Today Sessions retained as a free fallback. See §5.2.                                                                                                                        |
| 10  | Directory / marketing    | Psychology Today ($29.95/mo) **plus** the Professional Website and Therapy Finder listing included free with SimplePractice Starter (§5.2).                                                                                                                                           |
| 11  | AI                       | BastionGPT Professional (HIPAA, BAA) — **deferred past launch**. Cheaper than SimplePractice's own Note Taker add-on at $35/mo.                                                                                                                                                       |
| 12  | Bank                     | BECU Business Basic Checking + optional BECU Business Cash Back card                                                                                                                                                                                                                  |
| 13  | Bookkeeping              | Wave (free)                                                                                                                                                                                                                                                                           |
| 14  | Clients at home          | No. Telehealth only, WA-located clients only.                                                                                                                                                                                                                                         |
| 17  | Workspace                | No dedicated room. **Primary control: no household member in the room during sessions or paper handling.** Acoustic controls close the remaining sound gap. See §5.4.                                                                                                                 |
| 18  | Devices                  | **Two: computer and iPhone 12.** Mac has a separate work account, sole admin, FileVault on, no cloud sync. Phone runs **iPlum and SimplePractice** under the §5.4 configuration. Apple Family Sharing is fine (§5.4). Neither device stores records. Household members get no access. |
| 15  | Supervision & CE         | Required. Budgeted with stated assumptions, not deferred.                                                                                                                                                                                                                             |
| 16  | Registered agent         | **Self** (noncommercial registered agent) at the apartment. No commercial service. See §2.3.                                                                                                                                                                                          |


---



## 2. Entity, addresses, and identifiers



### 2.1 The PLLC

A PLLC is the correct vehicle: Washington authorizes professional LLCs for licensed professions,
and mental health counseling qualifies as a "professional service."


| Requirement                                                                        | Where to check                                                                                              |
| ---------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| PLLC authority and formation                                                       | [RCW 25.15.046](https://app.leg.wa.gov/RCW/default.aspx?cite=25.15.046)                                     |
| Definition of "professional service"                                               | [RCW 18.100.030](https://app.leg.wa.gov/RCW/default.aspx?cite=18.100.030)                                   |
| Name availability search + online filing                                           | [WA SOS — CCFS](https://ccfs.sos.wa.gov/)                                                                   |
| Certificate of Formation fee — **$180 by mail / ~$200 online**                     | [WA SOS — LLCs](https://www.sos.wa.gov/corporations-charities/limited-liability-companies-llc) **[verify]** |
| **Annual Report — $70/yr**, due by the last day of the formation anniversary month | [WA SOS — Annual Reports](https://www.sos.wa.gov/corporations-charities/annual-reports)                     |
| Registered agent must have a physical WA street address                            | [RCW 23.95.410](https://app.leg.wa.gov/RCW/default.aspx?cite=23.95.410)                                     |


The entity name must include "PLLC" or "Professional Limited Liability Company," and must not imply
a scope of practice broader than an LMHCA holds.

**An LMHCA may own a PLLC and operate a private practice in Washington** — but may not practice
independently. All clinical work must occur under an approved supervisor for the entire associate
period. Confirm current DOH position: [WA DOH — Behavioral Health FAQs](https://doh.wa.gov/licenses-permits-and-certificates/professions-new-renew-or-update/behavioral-health-professions-facilities-and-agencies/frequently-asked-questions).

### 2.2 Operating Agreement

**Required in practice, even though Washington will not ask for it.** The Operating Agreement is
not filed with the Secretary of State and a single-member PLLC can feel like it does not need one.
It does. This is the document that establishes the PLLC as an entity genuinely separate from you
personally — and that separation is the entire basis of the liability shield. Without it, a
single-member PLLC with commingled paperwork looks like a sole proprietorship wearing a hat, which
is precisely the argument made by anyone trying to pierce it. BECU will also likely ask for it at
account opening.

**What it must cover:**


| Provision                      | Detail                                                                                                                                                                                                                                                                                          |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Ownership                      | Sole member, 100% membership interest                                                                                                                                                                                                                                                           |
| **Professional qualification** | State that the sole member is licensed to render the professional service — a PLLC may only be owned by someone licensed for that service ([RCW 25.15.046](https://app.leg.wa.gov/RCW/default.aspx?cite=25.15.046) · [RCW 18.100.030](https://app.leg.wa.gov/RCW/default.aspx?cite=18.100.030)) |
| Purpose                        | Limited to the practice of mental health counseling and activities incidental to it                                                                                                                                                                                                             |
| Management                     | Member-managed; the member's authority to act for the PLLC                                                                                                                                                                                                                                      |
| Capital contributions          | The initial owner contribution, and how later contributions are recorded (§7 Phase 3)                                                                                                                                                                                                           |
| Distributions                  | How and when the member takes distributions, kept distinct from the business account                                                                                                                                                                                                            |
| Records and accounting         | Fiscal year, where records are kept, that business and personal funds stay separate (§3.5)                                                                                                                                                                                                      |
| Transfer and dissolution       | What happens on death, incapacity, or wind-down — coordinate with the professional will and the records-custodian arrangement (§4.7)                                                                                                                                                            |


**Cost: $0–500.** A single-member template is adequate for a straightforward solo practice; an
attorney review is worth it if you want the professional-qualification and dissolution language
tied cleanly to the LMHCA credential and the records-custodian duty.

**Sign it, date it, and keep it in the Entity file.** An unsigned agreement in a drafts folder does
not help you. Revisit it if you ever add a clinician, take on a partner, or elect S-corp treatment.

### 2.3 Addresses on the filing

Two addresses appear on the Certificate of Formation and **both are public record**. Neither may be
a PO Box or PMB — which rules out any commercial mailbox for both fields.


| Field on the filing                    | What you enter                    | Rule                                                                         |
| -------------------------------------- | --------------------------------- | ---------------------------------------------------------------------------- |
| Principal Office — **street address**  | **Redmond apartment**             | Physical street address; no PO Box or PMB.                                   |
| Principal Office — **mailing address** | **Home address** (or leave blank) | Optional alternate. A PMB **is** allowed here if you later adopt one (§2.5). |
| Registered agent — **name**            | **You**                           | Mandatory field, but nothing to buy — see below.                             |
| Registered agent — **street address**  | **Redmond apartment**             | Physical street address that **must be in Washington**; no PO Box or PMB.    |


The Principal Office is legally defined as *where the entity's records are kept*.

Sources: [WA SOS — PLLC Certificate of Formation](https://www.sos.wa.gov/sites/default/files/2023-10/PLLC_COF.pdf) ·
[WA SOS — Contact info requirements](https://www.sos.wa.gov/corporations-charities/frequently-asked-questions-faqs/contact-info-requirements-updates) ·
[WA SOS — Registered Agents FAQ](https://www.sos.wa.gov/corporations-charities/frequently-asked-questions-faqs/faq-registered-agent)

#### Registered agent: you, at $0

Every Washington LLC **must designate a registered agent** — the field is mandatory and the filing
cannot be submitted without it. What is optional is *paying a company to be it*. Washington allows a
**noncommercial registered agent**, so you serve as your own and **there is nothing to purchase**.

What serving as your own agent commits you to
([RCW 23.95.410](https://app.leg.wa.gov/RCW/default.aspx?cite=23.95.410) ·
[RCW 23.95.430](https://app.leg.wa.gov/RCW/default.aspx?cite=23.95.430)):

- Washington resident, 18 or older, with a physical Washington street address — the apartment
- **Written consent to serve**, filed with the Certificate of Formation
- **Physically present at that address during normal business hours** to accept service of process

No commercial service is worth buying: the apartment is already public as the Principal Office, so
an agent service would shield nothing, and a home-based weekday telehealth practice already meets
the business-hours availability requirement that such services exist to solve.

**Reversible for $0.** Changing the agent later is a free Statement of Change filed online through
[CCFS](https://ccfs.sos.wa.gov/). Switch to a commercial agent if you begin receiving **subpoenas
for client records** — common for therapists in custody and divorce matters — and want a
professional buffer, if you travel enough that you are not reliably home on weekdays, or if you take
an office. The risk accepted meanwhile is that missed service of process can produce a default
judgment; small for a solo practitioner who is home on weekdays.

**The mailing address field.** At launch, leave it blank or repeat the home address — see §2.4.
The apartment is already published twice on this filing (Principal Office and registered agent), so
a separate mailing address buys no privacy at this stage.

### 2.4 Mailing address at launch: home

**Allowed, and the simplest correct choice.** Every address field this practice must fill can be
the home address:


| Where                           | Field                                                                               | Home address allowed?                                                    |
| ------------------------------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| Certificate of Formation        | Principal Office street address                                                     | **Required** to be the apartment anyway (§2.3)                           |
| Certificate of Formation        | Principal Office mailing address                                                    | Yes — optional field; leave blank or repeat the street address           |
| Certificate of Formation        | Registered agent address                                                            | **Required** to be a WA street address — the apartment (§2.3)            |
| WA Business License Application | Business location vs. mailing address are **separate fields**; both may be the home | Yes ([DOR BLS](https://dor.wa.gov/open-business/apply-business-license)) |
| Redmond endorsement             | Driven by business *location*, which is the apartment regardless                    | Yes                                                                      |
| Psychology Today                | Telehealth-only profiles can suppress the street address                            | Confirm at setup                                                         |


**It also removes a legal question rather than answering one.** With no third party receiving your
mail, the business-associate analysis in §2.5 never arises. That is worth more than the privacy a
mailbox would notionally provide — privacy the filing has already given away.

**Cost: $0.** This removes $24/month and the Form 1583 errand from the launch plan.

#### Mail handling rules

Most business mail carries no PHI. Some will: **subpoenas and court orders for client records**
(common for therapists in custody and divorce matters), records requests, client letters or checks,
and collections correspondence. A client's name plus the fact that they are your client is PHI.
The Privacy Rule requires reasonable administrative, physical, and technical safeguards for PHI
**in any form, including paper** — [45 CFR 164.530(c)](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-E/section-164.530).

1. **Collect mail promptly.** A shared building cluster box is a weak point; do not let mail sit.
2. **Open business mail in your closed-door session zone, or when you are alone** — never on a
  shared surface like the kitchen table. No dedicated room? See §5.4.
3. **Anything with client information goes straight to the locked cabinet**, or is scanned into
  SimplePractice and the paper destroyed the same day. Do not create a paper pile.
4. **Never leave mail with client information in camera frame.** A desk visible during a telehealth
  session is a disclosure. Clear the desk before every session.
5. **Dispose by micro-cut shredding (P-5, see below).** PHI must be rendered "essentially unreadable,
  indecipherable, and otherwise unable to be reconstructed" — a recycling bin is a reportable breach
   ([HHS disposal FAQs](https://www.hhs.gov/sites/default/files/disposalfaqs.pdf)).
6. **Log legally significant mail** — subpoenas, court orders, board correspondence — with the date
  received. The date starts response clocks.
7. **Household members are not workforce members.** They do not open, sort, or handle practice mail,
  even helpfully. See §5.4.



#### Locked cabinet — buy one before the first client

You need one regardless, for handwritten notes; it also solves mail storage. Required as a
*reasonable physical safeguard* under [45 CFR 164.530(c)](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-E/section-164.530)
and [45 CFR 164.310](https://www.law.cornell.edu/cfr/text/45/164.310), and by
[WAC 246-809-035](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-035), which requires records
be kept "safely with properly limited access."


| Spec                                                | Why                                                                                                                                 |
| --------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| **Locking**, and you hold the only key              | The threat model in a home practice is household members, guests, cleaners, and maintenance — not hackers. The lock is the control. |
| **Fire-resistant** if the budget allows             | You carry a 5-year retention duty (WAC 246-809-035). Losing records to a fire is a compliance failure, not bad luck.                |
| Small is fine — 2-drawer letter or a document chest | Most records live in SimplePractice. Minimal paper is the goal.                                                                     |
| Budget **$100–200** for the cabinet                 | One-time, deductible                                                                                                                |


**Shredder — buy DIN 66399 level P-5 (micro-cut, particles ≤2×15 mm), $50–120.** HIPAA sets no
particle size; it requires only that PHI be rendered unreadable and non-reconstructable. **P-4
cross-cut (≈4×40 mm) is the common baseline** for general PHI, but behavioral-health records are the
most sensitive category there is and P-5 costs very little more — take P-5. **Strip-cut (P-1/P-2) is
not acceptable**: strips can be reassembled. For calibration, NIST SP 800-88 specifies 1×5 mm or
smaller for federal data, which is stricter still.

**What goes in it:** any paper bearing client information · handwritten session and process notes ·
signed paper forms awaiting scanning · the Supervision file (it contains client-identifying case
material) · the Compliance, HIPAA, Entity, and Insurance files (§7).

> **Give the key to your records custodian — in the instructions, not the drawer.** The professional
> will (§4.7) obliges someone to retain or transfer records if you die or are incapacitated. A
> custodian who cannot open the cabinet cannot perform that duty. Record the key location or
> combination in the custodian instructions, stored separately from the cabinet itself.



### 2.5 If you later want a mailing address: the conduit question

**The conduit exception is narrower than it is usually described, and a commercial mailbox does not
sit cleanly inside it.**

The 2013 Omnibus Rule added **"maintains"** to the business-associate definition at
[45 CFR 160.103](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-160/subpart-A/section-160.103):
a business associate is anyone who *creates, receives, **maintains**, or transmits* PHI on a covered
entity's behalf. An entity that merely **stores** records — even without ever reading them — is a
business associate.

HHS limits the conduit exception to entities with **transient** possession for transmission: the
Postal Service, couriers, and their electronic equivalents. Storage qualifies only when it is
"temporary and incident to the transmission"
([HHS OCR guidance](https://www.hhs.gov/guidance/document/faq-2077-can-csp-be-considered-be-conduit-postal-service-and-therefore-not-business)).

**Where a mailbox provider like Pony Express falls is genuinely unsettled:**


| Argument it *is* a conduit                                                                     | Argument it is *not*                                                                                                            |
| ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| Mail is never opened, scanned, or read — they hold a sealed envelope and never access contents | They **receive and maintain** mail on your behalf under a Form 1583 agency authorization — the exact verbs in the BA definition |
| Functionally identical to a courier, which HHS names as a conduit                              | Mail sits in a box for days or weeks. That is persistent possession, not storage "incident to transmission"                     |
| This is the position mailbox providers themselves take                                         | Providers assert it in marketing and disclaim it as non-legal advice. It has not been tested                                    |


**Conclusion: the "no BAA needed" position is defensible but not certain.** Do not rely on it when a
free alternative exists.

**Three options, cleanest first:**

1. **Home address (selected, §2.4).** No third party touches the mail, so no analysis is needed.
2. **A provider that signs a BAA** — the correct answer when you do want an address. **VirtualPostMail
  (VPM)** signs a BAA at every location on its **Business plan or higher** and is SOC-2 certified
   ([VPM — healthcare](https://www.virtualpostmail.com/customers/healthcare-providers/) ·
   [VPM BAA terms](https://www.virtualpostmail.com/terms/hipaa-baa/)). Base plans start around
   $20/month with Plus at $35; **Business-tier pricing is not published — request a quote**. A signed
   BAA makes the question moot rather than arguable.
3. **A forward-only CMRA with no BAA.** Workable, but it rests on an argument rather than a rule.
  If chosen, document the reasoning and the written no-open / no-scan instruction in the Security
   Risk Analysis as a deliberate risk decision.

**Out-of-state mailing address — allowed.** The Principal Office *street* address need not be in
Washington, and a PMB is permitted as the alternate *mailing* address with no state restriction, so
a VPM address in another state works for the Certificate of Formation and for vendor mail. Two
constraints survive: the **registered agent address must still be a Washington street address**
(the apartment), and the **Redmond business location is still the apartment**, so the city
endorsement and zoning position do not change. Consider also that an out-of-state business address
on a WA-only telehealth profile invites "are they actually in Washington?" from prospective clients —
check whether VPM offers a Washington location before choosing one elsewhere.

**Reassess immediately** if any provider begins opening, scanning, storing, or otherwise processing
mail — that ends the conduit argument outright and a BAA becomes mandatory.

### 2.6 Identifiers — EIN, NPI Type 1, and NPI Type 2


| Identifier                                                | Cost | Where to obtain                                                                                                                                       |
| --------------------------------------------------------- | ---- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| EIN (for the PLLC)                                        | $0   | [IRS — Apply for an EIN online](https://www.irs.gov/businesses/small-businesses-self-employed/apply-for-an-employer-identification-number-ein-online) |
| NPI **Type 1** — the individual clinician, tied to SSN    | $0   | [NPPES](https://nppes.cms.hhs.gov/)                                                                                                                   |
| NPI **Type 2** — the PLLC as an organization, tied to EIN | $0   | [NPPES](https://nppes.cms.hhs.gov/)                                                                                                                   |




#### Why an NPI Type 2 is required

**The rule.** CMS treats a sole proprietor and their business as one person: a sole proprietor is
an Entity Type 1 and is eligible for exactly one NPI. But the moment the practice is
**incorporated** — a PLLC, PC, or LLC — two health care providers exist where there was one. The
individual still renders the care and keeps the Type 1. The entity is now an *organization health
care provider* in its own right and needs its own Type 2. An incorporated individual therefore
holds **both**. See [CMS NPI Fact Sheet](https://www.cms.gov/files/document/npi-fact-sheet.pdf)
and the NPI standard at [45 CFR 162.410](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-162/subpart-D/section-162.410).

This plan forms a PLLC. That single decision is what triggers the Type 2 requirement. A plan that
lists only "NPI Type 1" is inconsistent with the entity structure in §2.1.

**Why it matters in practice, even for a private-pay practice:**

1. **Superbills will be rejected or misrouted without it.** Out-of-network clients submit superbills
  to their insurer for reimbursement. The insurer matches the **billing entity's NPI against the
   TIN that received payment**. Payments go to the PLLC under its EIN; a Type 1 NPI is registered
   to an SSN. Supplying the individual NPI as the billing provider creates an NPI-to-TIN mismatch,
   which is a routine denial reason. The client's reimbursement is the casualty.
2. **The claim form has two separate fields, and they are not the same field.** On the CMS-1500,
  Box 33a is the **billing provider** NPI (the PLLC's Type 2) and Box 24J is the **rendering
   provider** NPI (the individual's Type 1). With only a Type 1, the form cannot be completed
   correctly for an incorporated practice. Confirm current form layout at
   [NUCC — CMS-1500 instructions](https://www.nucc.org/index.php/1500-claim-form-mainmenu-35).
3. **Any future insurance paneling requires a group NPI.** Credentialing applications and payer
  contracts ask for the organization NPI up front. Getting it later means amending contracts.
4. **It is free and takes about fifteen minutes.** Getting it at formation avoids reissuing
  superbills retroactively after a client's first denial.

**Sequence matters:** obtain the EIN first, then apply for the Type 2 using the EIN and the exact
legal PLLC name as filed. Keep the taxonomy code consistent across both NPIs.

---



## 3. Money



### 3.1 One-time startup costs


| Item                                                                                                        | Amount          | Reference                                                                                                                                                                 |
| ----------------------------------------------------------------------------------------------------------- | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| PLLC Certificate of Formation                                                                               | $180–200        | [WA SOS CCFS](https://ccfs.sos.wa.gov/) **[verify]**                                                                                                                      |
| WA Business License Application                                                                             | $90             | [DOR — Apply for a business license](https://dor.wa.gov/open-business/apply-business-license)                                                                             |
| Redmond city endorsement (year 1)                                                                           | $160/FTE        | [Redmond Business Licensing](https://www.redmond.gov/230/Business-Licensing) · [DOR — Redmond](https://dor.wa.gov/manage-business/city-endorsements/redmond) **[verify]** |
| EIN                                                                                                         | $0              | IRS                                                                                                                                                                       |
| NPI Type 1 + Type 2                                                                                         | $0              | NPPES                                                                                                                                                                     |
| Telemedicine training                                                                                       | $0              | WSHA (§4.4)                                                                                                                                                               |
| **Subtotal — paid from personal funds, before the account exists (§7)**                                     | **~$430–450**   | record as capital contribution                                                                                                                                            |
| **Operating Agreement** — template, or attorney review                                                      | $0–500          | §2.2                                                                                                                                                                      |
| **Locking file cabinet** (fire-resistant if budget allows)                                                  | $100–200        | §2.4 — required physical safeguard                                                                                                                                        |
| **Shredder, DIN 66399 P-5 micro-cut**                                                                       | $50–120         | §2.4 — P-4 is the floor, strip-cut is not acceptable                                                                                                                      |
| **Workspace controls** — white-noise machine, privacy screen filter, door seal, screen or curtain if needed | $60–370         | §5.4 — no dedicated room                                                                                                                                                  |
| Closed-back headphones                                                                                      | **$0**          | already owned (§5.4)                                                                                                                                                      |
| Consent / disclosure / policy templates, or attorney review                                                 | $0–1,500        | optional but recommended                                                                                                                                                  |
| **Realistic all-in**                                                                                        | **~$640–3,100** |                                                                                                                                                                           |


**Not counted as startup:** LMHCA application (already held) and initial NCC certification
(already completed). Only their renewals appear in §3.2.

### 3.2 Recurring monthly costs

**Core operations**


| Expense                                 | Monthly     | Reference                                                                                                                              |
| --------------------------------------- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| SimplePractice Starter                  | $49.00      | [Pricing](https://www.simplepractice.com/pricing/) — tier features **verified**, see §5.2                                              |
| Microsoft 365 Business Basic (no Teams) | ~$5.00      | [M365 Business plans](https://www.microsoft.com/en-us/microsoft-365/business/compare-all-microsoft-365-business-products) **[verify]** |
| iPlum Professional (annual billing)     | $14.99      | [iPlum pricing](https://iplum.com/pricing/) — Professional is **required** for the BAA; web calling included                           |
| Psychology Today directory              | $29.95      | [Join Psychology Today](https://join.psychologytoday.com/us/signup)                                                                    |
| Cloudflare domain (at cost)             | ~$1.00      | [Cloudflare Registrar](https://www.cloudflare.com/products/registrar/)                                                                 |
| HPSO professional liability (~$250/yr)  | $20.83      | [HPSO — Counselors](https://landing.hpso.com/counselors/) **[re-quote — see note]**                                                    |
| **Subtotal**                            | **$120.77** |                                                                                                                                        |


**Annual compliance, amortized**


| Expense                                | Annual   | Monthly    |
| -------------------------------------- | -------- | ---------- |
| WA SOS Annual Report                   | $70      | $5.83      |
| Redmond business license               | $160     | $13.33     |
| LMHCA renewal                          | $25      | $2.08      |
| Continuing education (18 hrs/yr, §4.3) | $250     | $20.83     |
| **Subtotal**                           | **$505** | **$42.07** |


**Fixed subtotal: $162.84/month**

**Supervision — required, the largest single line**

**50 hours** of immediate supervision across a minimum 36-month period, after the confirmed CACREP
credit (§4.2):


| Rate        | Hours  | Total       | Monthly over 36 mo |
| ----------- | ------ | ----------- | ------------------ |
| **$200/hr** | **50** | **$10,000** | **$278**           |


**Planning figure: $278/month.** Replace it with the actual figure once the supervision agreement is
signed.

> **⚠ On the $200/hr assumption — it is above market.** Observed Washington rates run roughly
> **$100–180/hour** for individual supervision, with group supervision reported as low as **$100 per
> participant**. $200 is above the top of that range, so this is a deliberately conservative figure.
> If the contracted rate lands at $150, supervision falls to **$7,500 total and $208/month**, and the
> launch target drops from **$441 to $371**. Budget the higher number and treat any saving as real,
> rather than planning around a rate you have not yet secured.
>
> **Two questions for every supervisor you interview**, because together they are the largest single
> lever on the biggest cost in this practice: do they offer a **group rate** (often near half of
> individual), and confirm with DOH **how much group supervision counts** toward the
> immediate-supervision requirement (§4.2).

**Deferred / optional**


| Expense                  | Monthly    | Note                                                                                                                                                                                         |
| ------------------------ | ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ACA membership ($189/yr) | $15.75     | Not required. [WMHCA](https://wmhca.org/) is cheaper and more locally useful. Keep ACA only if it is the channel for liability insurance.                                                    |
| NCC renewal ($85/yr)     | $7.08      | Not required for WA licensure. [NBCC](https://www.nbcc.org/certification/ncc). Keep only for planned reciprocity.                                                                            |
| BastionGPT Professional  | $20.00     | [BastionGPT](https://bastiongpt.com/). Defer past launch. **Cheaper than SimplePractice's Note Taker add-on ($35/mo per clinician)** — if AI is adopted later, this is the lower-cost route. |
| **Subtotal**             | **$42.83** |                                                                                                                                                                                              |




### 3.3 Totals


| Scenario                               | Monthly  |
| -------------------------------------- | -------- |
| Fixed only (no supervision)            | **$163** |
| **Launch target: fixed + supervision** | **$441** |
| With all optional items restored       | **$483** |


**Plus, both variable and both larger than the fixed total at a full caseload:**

- **Payment processing ≈ 3%+ of collections.** Model as a percentage of revenue, never as "TBD."
- **Federal income + self-employment tax:** reserve **25–30% of net**.

> **HPSO:** individual counselor professional liability at $1M/$3M typically runs $100–400/yr, so
> the $250 assumed above sits mid-range. Get an actual quote, and **ensure the PLLC is a named
> insured, not just the individual** — an entity-only claim against a policy naming only the person
> leaves a gap.



### 3.4 Taxes


| Obligation                   | Detail                                                                                                                                                                                                                                                               | Where to check                                                                                                                                                                                          |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Federal income tax           | Single-member PLLC is a disregarded entity by default → Schedule C                                                                                                                                                                                                   | [IRS — Single-member LLC](https://www.irs.gov/businesses/small-businesses-self-employed/single-member-limited-liability-companies)                                                                      |
| Self-employment tax          | 15.3% on net earnings                                                                                                                                                                                                                                                | [IRS — Self-employment tax](https://www.irs.gov/businesses/small-businesses-self-employed/self-employment-tax-social-security-and-medicare-taxes)                                                       |
| Quarterly estimated payments | Approx. Apr 15 / Jun 15 / Sep 15 / Jan 15                                                                                                                                                                                                                            | [IRS — Estimated taxes](https://www.irs.gov/businesses/small-businesses-self-employed/estimated-taxes)                                                                                                  |
| WA state income tax          | None                                                                                                                                                                                                                                                                 | —                                                                                                                                                                                                       |
| **WA B&O tax**               | Service classification. As of July 2026 the small-business credit is **$375/month** for service businesses and the annual filing threshold rose to **$250,000** — this practice will almost certainly owe **$0**, and may not need to file a return. Still register. | [DOR — B&O tax](https://dor.wa.gov/taxes-rates/business-occupation-tax) · [Small business B&O credit](https://dor.wa.gov/taxes-rates/business-occupation-tax/small-business-bo-tax-credit) **[verify]** |
| Redmond local B&O            | Redmond charges a per-FTE license fee; confirm whether any separate local B&O applies                                                                                                                                                                                | [Redmond Business Licensing](https://www.redmond.gov/230/Business-Licensing) — 425-556-2193                                                                                                             |
| Home office deduction        | Use a documented business-use allocation; do not deduct 100% of mixed-use costs                                                                                                                                                                                      | [IRS — Home office deduction](https://www.irs.gov/businesses/small-businesses-self-employed/home-office-deduction)                                                                                      |


**S-corp election:** premature. Revisit only at roughly $60–80k net profit, with a CPA.

### 3.5 Banking and expense categories

Open [BECU Business Basic Checking](https://www.becu.org/business) after the Certificate of
Formation, EIN letter, and UBI are in hand. Optional BECU Business Cash Back card, paid in full
monthly. Use the business account and card for all business expenses; never mix personal and
business purchases. Keep every receipt and invoice.


| Category                | Contents                                                                               |
| ----------------------- | -------------------------------------------------------------------------------------- |
| Professional            | Supervision · CE · licensing and renewals · HPSO · professional memberships            |
| Software / technology   | SimplePractice · iPlum · Microsoft 365 · domain · (BastionGPT, if adopted)             |
| Marketing               | Psychology Today                                                                       |
| Office / communications | Business phone · allocated home-office and internet share · cabinet, shredder, devices |
| Entity / compliance     | SOS annual report · state and city licenses                                            |
| Banking                 | Account and card fees, if any                                                          |
| Cost of revenue         | Payment processing                                                                     |


---



## 4. Clinical and regulatory compliance



### 4.1 Credential and the six-year clock


| Requirement             | Detail                                                                      | Where to check                                                                                                                                                                          |
| ----------------------- | --------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Active LMHCA credential | Renews **annually**; fee **$25**                                            | [WA DOH — MHC licensing information](https://doh.wa.gov/licenses-permits-and-certificates/professions-new-renew-or-update/mental-health-counselor/licensing-information) **[verify]**   |
| **Renewal cap**         | The LMHCA may be renewed **only six times** absent a DOH waiver             | [WA DOH — MHC licensing requirements](https://doh.wa.gov/licenses-permits-and-certificates/professions-new-renew-or-update/mental-health-counselor/licensing-requirements) **[verify]** |
| Governing rules         | [Chapter 246-809 WAC](https://app.leg.wa.gov/wac/default.aspx?cite=246-809) |                                                                                                                                                                                         |


> **This is a business constraint, not just a fee.** The associate period has a hard six-year
> ceiling and a three-year floor. Full LMHC licensure must be reached inside that window, which
> means caseload volume is a *licensure* variable as well as an income variable.



### 4.2 Supervision


| Requirement                            | Detail                                                                                                                                                                                                              | Where to check                                                                                                           |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Base postgraduate experience           | Minimum **36 months** full-time counseling **or 3,000 hours**                                                                                                                                                       | [WAC 246-809-230](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-230)                                              |
| Base immediate supervision             | **100 hours** within the 3,000                                                                                                                                                                                      | [WAC 246-809-230](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-230)                                              |
| **CACREP credit — confirmed eligible** | A CACREP-accredited degree credits **500 experience hours and 50 supervision hours**                                                                                                                                | [WAC 246-809-230](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-230)                                              |
| **→ Effective total experience**       | **2,500 hours**                                                                                                                                                                                                     | after CACREP credit                                                                                                      |
| **→ Effective immediate supervision**  | **50 hours**                                                                                                                                                                                                        | after CACREP credit                                                                                                      |
| Direct client contact                  | **1,200 hours** — confirm with DOH whether the CACREP credit reduces this figure or only the 3,000-hour total                                                                                                       | [WAC 246-809-230](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-230)                                              |
| Approved supervisor qualifications     | Licensed without restriction, in good standing 2 years, **15 clock hours of clinical supervision training**; may not be a relative, cohabitant, peer, or a past provider of psychological services to the candidate | [WAC 246-809-234](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-234)                                              |
| Supervisor declaration                 | Must be completed before supervision begins                                                                                                                                                                         | [Approved Supervisor Declaration (DOH 670130)](https://doh.wa.gov/sites/default/files/legacy/Documents/Pubs//670130.pdf) |


**Cost, when interviewing supervisors.** Washington rates run roughly **$100–180/hour** for
individual supervision; group supervision is reported as low as $100 per participant. The plan
budgets a conservative $200/hr (§3.2). Ask every candidate about group rates, and confirm with DOH
how much group supervision counts toward the 50 hours — that combination moves the largest cost in
the practice more than anything else on this page.

> **Note on ratios.** WAC 246-809-230 sets no per-hour supervision ratio. Budget against the
> **50-hour** effective total, not against any ratio quoted elsewhere. The 36-month minimum still
> applies independently of the hour count — confirm with DOH whether the CACREP credit shortens it.

**Supervision file to maintain** (a practical recordkeeping system — not every item is a separate
DOH form; use current DOH forms at verification time):

1. Signed approved-supervisor declaration
2. Supervision agreement — supervisor, supervisee, fee, frequency, format, responsibilities, confidentiality
3. Supervision log — date, duration, individual vs. group, topics
4. Running tally of total hours, direct client contact hours, and immediate supervision hours against the **2,500 / 1,200 / 50** targets
5. Supervisor evaluations and verification forms for the eventual LMHC application
6. Correspondence and payment records



### 4.3 Continuing education


| Requirement                     | Detail                                                                                                                                                                                                      | Where to check                                                                                                                                                                                                                        |
| ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **LMHCA annual CE**             | **18 hours per renewal**                                                                                                                                                                                    | [WAC 246-809-632](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-632) · [WA DOH — CE](https://doh.wa.gov/licenses-permits-and-certificates/professions-new-renew-or-update/mental-health-counselor/continuing-education)        |
| CE for full LMHC licensure      | 36 hours including **6 hours law and ethics**, completed after academic requirements and before licensure                                                                                                   | [WA DOH — CE](https://doh.wa.gov/licenses-permits-and-certificates/professions-new-renew-or-update/mental-health-counselor/continuing-education)                                                                                      |
| Distance learning               | No cap; asynchronous courses must include comprehension testing                                                                                                                                             | [WAC 246-809-610](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-610)                                                                                                                                                           |
| **Suicide prevention training** | **6 hours** from the DOH model list, during the first full CE reporting period after licensure, refreshed every 6 years; post-July-2021 second-cycle training must be advanced clinical (DBT, CAMS, CBT-SP) | [RCW 43.70.442](https://app.leg.wa.gov/RCW/default.aspx?cite=43.70.442) · [DOH model list](https://doh.wa.gov/public-health-provider-resources/healthcare-professions-and-facilities/suicide-prevention/training-programs/model-list) |


Budget: an unlimited-CE subscription (~$150–250/yr) covers the 18 annual hours more cheaply than
per-course purchases. The 6-hour suicide prevention course runs roughly $50–150 separately.

### 4.4 Telemedicine training

Required for any health care professional delivering clinical services by telemedicine.
**Sign and retain an attestation of completion** — it is not submitted to DOH unless requested.
The Washington State Telehealth Collaborative training is free and about 20 minutes.

- [RCW 43.70.495](https://app.leg.wa.gov/rcw/default.aspx?cite=43.70.495)
- [WA State Telehealth Collaborative (WSHA)](https://www.wsha.org/clinical-excellence/washington-state-telehealth-collaborative/)



### 4.5 Client-facing disclosures and documents


| Document                                       | Requirement                                                                                                                                                                                                                                                                                                  | Where to check                                                                                                                                                                                               |
| ---------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Counselor disclosure statement**             | A specific Washington requirement, distinct from informed consent. Must be provided to clients.                                                                                                                                                                                                              | [RCW 18.19.060](https://app.leg.wa.gov/RCW/default.aspx?cite=18.19.060)                                                                                                                                      |
| Associate status disclosure                    | Associate status and supervisor identity must be disclosed to clients and in advertising                                                                                                                                                                                                                     | [Chapter 246-809 WAC](https://app.leg.wa.gov/wac/default.aspx?cite=246-809)                                                                                                                                  |
| Informed consent                               | General clinical consent, including that cases are discussed in supervision                                                                                                                                                                                                                                  | practice document                                                                                                                                                                                            |
| **Telehealth-specific consent**                | Modality limits, technology failure protocol, client's physical location each session, local emergency contacts and crisis plan, and an **honest description of your working setting** (§5.4)                                                                                                                | practice document                                                                                                                                                                                            |
| Notice of Privacy Practices                    | Required under HIPAA; keep an acknowledgment of receipt                                                                                                                                                                                                                                                      | [HHS model notices](https://www.hhs.gov/hipaa/for-professionals/privacy/guidance/model-notices-privacy-practices/index.html)                                                                                 |
| **Good Faith Estimate**                        | **Federally required for every self-pay or uninsured client, in writing, before services.** Must itemize expected services with CPT and diagnosis codes, expected charges, and the notice that a bill exceeding the estimate by **$400 or more** may be disputed. Non-negotiable for a private-pay practice. | [45 CFR 149.610](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-B/part-149/subpart-G/section-149.610) · [CMS sample GFE](https://www.cms.gov/files/document/nsa-sample-good-faith-estimate.pdf) |
| Fee schedule and payment policy                | Set before first client                                                                                                                                                                                                                                                                                      | practice document                                                                                                                                                                                            |
| No-show and late-cancellation policy, with fee | Set before first client                                                                                                                                                                                                                                                                                      | practice document                                                                                                                                                                                            |
| Consent for electronic communication           | What may and may not be sent by email or iPlum text, and the risks                                                                                                                                                                                                                                           | practice document                                                                                                                                                                                            |
| Client information and emergency contact form  | Physical address per session, local emergency contacts, nearest emergency facility                                                                                                                                                                                                                           | practice document                                                                                                                                                                                            |
| Clinical intake questionnaire and history      | —                                                                                                                                                                                                                                                                                                            | practice document                                                                                                                                                                                            |
| Safety / crisis plan template                  | —                                                                                                                                                                                                                                                                                                            | practice document                                                                                                                                                                                            |
| Release of Information (ROI) form              | —                                                                                                                                                                                                                                                                                                            | practice document                                                                                                                                                                                            |
| Payment method authorization                   | Card on file for SimplePractice payments                                                                                                                                                                                                                                                                     | practice document                                                                                                                                                                                            |




### 4.6 Where clients — and you — may be located

**Clients:** practice is limited to clients **physically located in Washington** at the time of
service. Verify client location at the start of every session and address travel explicitly in the
consent form. The Counseling Compact does not help here — associates are not eligible for compact
privileges; check current status at [counselingcompact.org](https://counselingcompact.org/).

**You:** conduct sessions only while **physically in Washington**. Licensure follows the client's
location, but states also assert jurisdiction over practice occurring inside their own borders, and
you hold no credential outside Washington. Working a session from an out-of-state property — however
convenient — is a licensure exposure, not a travel detail.

### 4.7 Records retention and succession


| Requirement                      | Detail                                                                                                                                                                    | Where to check                                                                          |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| Clinical records retention       | **Five years following the last visit**, stored safely with properly limited access                                                                                       | [WAC 246-809-035](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-035)             |
| **Succession plan**              | The licensee **or the associate's supervisor** must make provisions for retaining or transferring records in the event of going out of business, death, or incapacitation | [WAC 246-809-035](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-035)             |
| Health care information handling |                                                                                                                                                                           | [RCW 70.02](https://app.leg.wa.gov/RCW/default.aspx?cite=70.02)                         |
| HIPAA documentation retention    | Policies, BAAs, risk analyses: **6 years**                                                                                                                                | [HHS — HIPAA for professionals](https://www.hhs.gov/hipaa/for-professionals/index.html) |


**Professional will.** Name a colleague as records custodian, in writing, with access instructions
and a coverage arrangement for illness or incapacity. In Washington this is not merely an ethical
nicety — WAC 246-809-035 makes the provision mandatory.

---



## 5. HIPAA, privacy, and the technology stack



### 5.1 Required HIPAA program

Solo practice does not reduce these obligations. Each is a document to produce, not a checkbox.


| Item                                                                                                                                                                                                 | Where to check                                                                                                                                                                                                                                |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Documented **Security Risk Analysis**                                                                                                                                                                | [HHS/ONC Security Risk Assessment Tool](https://www.healthit.gov/topic/privacy-security-and-hipaa/security-risk-assessment-tool)                                                                                                              |
| Written Privacy, Security, and Breach Notification policies                                                                                                                                          | [HHS — HIPAA for professionals](https://www.hhs.gov/hipaa/for-professionals/index.html)                                                                                                                                                       |
| Notice of Privacy Practices, provided to clients                                                                                                                                                     | [HHS model notices](https://www.hhs.gov/hipaa/for-professionals/privacy/guidance/model-notices-privacy-practices/index.html)                                                                                                                  |
| Breach notification procedure — **including the lost-device steps from §5.4**                                                                                                                        | [HHS — Breach notification](https://www.hhs.gov/hipaa/for-professionals/breach-notification/index.html) · [45 CFR 164.402](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-D/section-164.402)                  |
| Designate yourself Privacy Officer and Security Officer, in writing                                                                                                                                  | [HHS — Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/index.html)                                                                                                                                                        |
| **Signed BAA file**: SimplePractice, iPlum, Microsoft, BastionGPT (if adopted)                                                                                                                       | vendor portals                                                                                                                                                                                                                                |
| Device security: full-disk encryption, MFA everywhere, auto screen lock, unique passwords, secured home Wi-Fi                                                                                        | risk analysis output                                                                                                                                                                                                                          |
| Physical security: closed-door session zone, headphones, external white noise, sealed door gap, privacy filter. A dedicated room is **not** required — but the arrangement must be documented (§5.4) | [45 CFR 164.306(b)](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-C/section-164.306) · [45 CFR 164.310(b)](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-C/section-164.310) |
| **Paper PHI**: locked cabinet, clear desk before every session, P-5 micro-cut shredding on disposal (§2.4)                                                                                           | [45 CFR 164.530(c)](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-E/section-164.530) · [HHS disposal FAQs](https://www.hhs.gov/sites/default/files/disposalfaqs.pdf)                                         |
| **Devices and household separation** — the largest practical risk in a home practice (§5.4)                                                                                                          | [45 CFR 164.310](https://www.law.cornell.edu/cfr/text/45/164.310) · [45 CFR 164.312](https://www.law.cornell.edu/cfr/text/45/164.312)                                                                                                         |
| Backup and contingency plan                                                                                                                                                                          | risk analysis output                                                                                                                                                                                                                          |
| **WA My Health My Data Act** — keep trackers and pixels off any public web presence                                                                                                                  | [WA AG — My Health My Data](https://www.atg.wa.gov/my-health-my-data-act)                                                                                                                                                                     |




### 5.2 Telehealth video — resolved: SimplePractice Starter

**Verified against SimplePractice's official plan comparison:**

> "You can meet clients for HIPAA compliant online sessions using Telehealth by SimplePractice,
> **with no limits on session length or number of appointments.**" — Telehealth, **Starter: Included**.

**Decision: run all video in SimplePractice Starter at $49/month.** Nothing about telehealth
requires an upgrade. Psychology Today reverts to a directory listing only, with Sessions retained as
a free fallback. Disregard the *30-telehealth-sessions-per-month cap on Starter* reported by several
pricing blogs — SimplePractice's own documentation contradicts it.

#### The reminder limitation does not apply to this practice

Starter restricts appointment reminders to **telehealth appointments only**. In a general practice
that would be a serious gap. **This practice is telehealth-only, so every appointment is a
telehealth appointment and the restriction never binds.** Text, email, and voice reminders with
client confirm/cancel all work on Starter.

**Conclusion: stay on Starter.** Reminders are the usual reason a telehealth practice upgrades to
Essential ($79), and that reason does not apply here — $30/month saved, with no change to the §3
totals, which already assume $49.

#### What Starter includes that this plan depends on


| Feature                                                                                       | Starter              |
| --------------------------------------------------------------------------------------------- | -------------------- |
| Telehealth video — unlimited, with waiting room, screen share, whiteboard                     | Included             |
| Appointment reminders for telehealth appointments (text / email / voice, with confirm-cancel) | Included             |
| Online appointment requests                                                                   | Included             |
| **CMS-1500 claim forms** — the mechanism behind client superbills (§2.6)                      | Included             |
| Intake form customization                                                                     | Included             |
| **Professional Website + Therapy Finder directory listing**                                   | Included — see below |




#### What Starter gives up, ranked by impact here


| Missing on Starter                                            | Impact                                           | Mitigation                                                                                                                                 |
| ------------------------------------------------------------- | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ |
| **Secure Messaging**                                          | Real — no in-platform client messaging           | **iPlum** (already budgeted, HIPAA + BAA) is the messaging channel                                                                         |
| **Analytics dashboard and reports**                           | Moderate — no income or outstanding-balance view | Wave bookkeeping covers the financial picture                                                                                              |
| **"Other documents"** (create / sign / share for e-signature) | **Verify** — see §9                              | Confirm the WA disclosure statement, telehealth consent, and ROI can be delivered as *intake forms*, which **are** customizable on Starter |
| Customizable progress note templates                          | Low — default templates only                     | Acceptable at launch                                                                                                                       |
| Calendar sync to Outlook or Google                            | Low — annoyance                                  | Work from the SimplePractice calendar                                                                                                      |
| Client waitlist                                               | None yet                                         | Only matters once full                                                                                                                     |
| Administrative notes, Wiley planners, client announcements    | None                                             | Not needed for a solo private-pay practice                                                                                                 |


**Upgrade trigger to Essential ($79):** move up when you want secure messaging, analytics, the
waitlist, or custom progress note templates — realistically as the caseload fills, not at launch.
Treat the +$30/month as a year-two decision, not a launch one.

#### Three incidental findings worth acting on

1. **Starter includes a Professional Website and a Therapy Finder directory listing at no extra
  cost.** The decision to run no practice website (§1, item 10) was made on cost grounds that no
   longer apply. Point the Cloudflare domain at the included SimplePractice site, and take the free
   second directory listing — Therapy Finder will not match Psychology Today's traffic, but it is an
   additional referral channel for $0. Keep any site free of trackers and pixels for
   [My Health My Data](https://www.atg.wa.gov/my-health-my-data-act) reasons (§5.1).
2. **SimplePractice's Note Taker add-on is $35/month per clinician** — more than BastionGPT
  Professional at $20. If AI is adopted later, BastionGPT is the cheaper route.
3. **No eFax and no public API.** SimplePractice confirms it does not support eFaxing. If you end up
  coordinating care with prescribers or PCPs who fax, budget a third-party HIPAA-compliant eFax
   (~$10–20/month) or check whether the iPlum plan already covers fax.

> **⚠ Psychology Today's BAA covers Sessions only — not the directory profile or its contact form.**
> Do not let clinical detail arrive through the Psychology Today contact form. Route intake to the
> SimplePractice client portal and ongoing contact to iPlum.

Source: [Comparing SimplePractice features by plan](https://support.simplepractice.com/hc/en-us/articles/360034957931-Comparing-SimplePractice-features-by-plan)

### 5.3 System roles


| System                         | Use                                                                                                                                                                                                                                               | PHI?                                                                                                                                                                                                                                                                                              |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| SimplePractice                 | EHR, scheduling, notes, **unlimited telehealth video**, client portal and intake forms, telehealth appointment reminders, payments, CMS-1500 forms for superbills, included Professional Website. **No secure messaging and no eFax on Starter.** | **Yes — primary system of record**                                                                                                                                                                                                                                                                |
| iPlum Professional             | Business line — calls, SMS, voicemail. Browser on the computer **and** app on the iPhone, one number                                                                                                                                              | **Yes — under BAA** ([iPlum HIPAA](https://iplum.com/hipaa-compliance/))                                                                                                                                                                                                                          |
| SimplePractice mobile (iPhone) | Document capture — in-app camera straight into the client file; records access on the move                                                                                                                                                        | **Yes — under BAA.** Photos access Limited or None (§5.4)                                                                                                                                                                                                                                         |
| Microsoft 365 Business Basic   | Business email, administrative documents, non-clinical operations                                                                                                                                                                                 | **Policy: no PHI in email.** Microsoft signs a BAA via the Data Protection Addendum ([Microsoft HIPAA/HITECH](https://learn.microsoft.com/en-us/compliance/regulatory/offering-hipaa-hitech)), but Business Basic lacks message encryption. Route anything clinical to the SimplePractice portal. |
| Psychology Today               | Public profile and discovery only                                                                                                                                                                                                                 | **No**                                                                                                                                                                                                                                                                                            |
| BastionGPT (deferred)          | Administrative drafting; clinical only under BAA                                                                                                                                                                                                  | Only under the BAA-covered account                                                                                                                                                                                                                                                                |
| Wave                           | Bookkeeping — business financials only                                                                                                                                                                                                            | **No PHI**                                                                                                                                                                                                                                                                                        |




### 5.4 Devices, household, and workspace

> **A terminology point worth getting right.** A BAA is a *contract with a vendor* — you have them
> with SimplePractice, iPlum, and Microsoft. Devices are not "made BAA compliant." Your own hardware
> is governed by the Security Rule's technical safeguards
> ([45 CFR 164.312](https://www.law.cornell.edu/cfr/text/45/164.312)) and physical safeguards
> ([45 CFR 164.310](https://www.law.cornell.edu/cfr/text/45/164.310)). In a home practice this is
> the largest remaining risk after the vendor contracts are signed.



#### The computer — the only device

**Decision: a separate macOS work account, sole administrator, FileVault on, no cloud sync.** This
account is the entire practice: EHR terminal, business phone, and video platform. Configure it once,
properly.

**Unique user identification is a *required* implementation specification**
([45 CFR 164.312(a)(2)(i)](https://www.law.cornell.edu/cfr/text/45/164.312)) — a shared login fails
it outright. A separate account with sole admin rights satisfies it.


| Setting                                                                                   | Where                                            | Value                                                                                                                                                                                 |
| ----------------------------------------------------------------------------------------- | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Work account is the **only** administrator                                                | System Settings > Users & Groups                 | Demote every other account to **Standard**. Not "unused" — demoted.                                                                                                                   |
| Account password                                                                          | —                                                | Long, unique, in a password manager. Never reused from personal accounts.                                                                                                             |
| **FileVault**                                                                             | System Settings > Privacy & Security > FileVault | On                                                                                                                                                                                    |
| **FileVault recovery key**                                                                | During FileVault setup                           | **Choose "Create a recovery key", not "Allow my iCloud account to unlock my disk."** Print it and put it in the locked cabinet (§2.4). The default nudges toward iCloud — decline it. |
| Require password after sleep                                                              | Lock Screen settings                             | **Immediately**                                                                                                                                                                       |
| Display off / screen saver                                                                | Lock Screen settings                             | 5–10 minutes                                                                                                                                                                          |
| Firewall                                                                                  | Network > Firewall                               | On                                                                                                                                                                                    |
| Guest User                                                                                | Users & Groups                                   | Off                                                                                                                                                                                   |
| Sharing — Screen Sharing, Remote Login, File Sharing                                      | General > Sharing                                | All off                                                                                                                                                                               |
| Automatic updates                                                                         | General > Software Update                        | On, including security responses                                                                                                                                                      |
| **Dictation**                                                                             | Keyboard > Dictation                             | **Off, or on-device only.** Server-based dictation sends audio to Apple, who has no BAA with you. A therapist dictating notes is the exact risk.                                      |
| Siri                                                                                      | Apple Intelligence & Siri                        | Off on this account                                                                                                                                                                   |
| Analytics & crash reports                                                                 | Privacy & Security > Analytics                   | Off — reports can carry app data                                                                                                                                                      |
| iCloud Drive, **Desktop & Documents sync**                                                | Apple Account > iCloud                           | Off. Desktop & Documents sync is on by default for many setups — verify it specifically.                                                                                              |
| **Consumer** cloud sync — personal iCloud Drive, Google Drive, Dropbox, personal OneDrive | —                                                | Not installed on this account. **OneDrive for Business is different** — it is BAA-covered and used for the archive (§5.5), but via browser, not the sync client                       |
| Browser                                                                                   | —                                                | A dedicated browser or profile for practice use only. No password saving. No personal browsing on this account.                                                                       |


**Find My Mac is a separate toggle from iCloud sync.** You can enable Find My — and therefore remote
lock and wipe — without turning on iCloud Drive, Photos, or Desktop sync. Worth having if the machine
is a laptop that leaves the residence; optional for a desktop that never moves.

#### Authentication — MFA everywhere it exists, and biometrics where they help

> **Be precise about what macOS can do.** The local Mac account login has **no native MFA** — Apple
> does not offer it for local sign-in. What protects the machine is a strong unique password plus
> **FileVault**, which means the disk is unreadable without that password. MFA belongs to the
> *services*, and that is where it must be switched on without exception.


| Account                 | MFA              | Method                            |
| ----------------------- | ---------------- | --------------------------------- |
| **Microsoft 365**       | Required         | Authenticator app                 |
| **SimplePractice**      | Required         | Authenticator app                 |
| **iPlum**               | Required         | Authenticator app                 |
| **Apple Account**       | Required         | Apple's built-in two-factor       |
| **Password manager**    | Required         | Authenticator app or hardware key |
| **BECU**                | Required         | Strongest option the bank offers  |
| Cloudflare, Wave        | Required         | Authenticator app                 |
| IRS, WA SOS, DOR, NPPES | Wherever offered | —                                 |


**Use an authenticator app, not SMS.** SMS codes are defeated by SIM-swap, which is a realistic
attack against someone whose phone number is published on a directory profile. A TOTP app — or a
hardware key — removes that path. **Print every recovery code and put it in the locked cabinet**
(§2.4), alongside the FileVault recovery key.

**Biometrics: on for the iPhone, optional on the Mac.** These are not the same decision.

**iPhone — keep Face ID ON.** Three reasons, and the second is decisive:

- **It is not a choice between Face ID and a passcode.** Face ID cannot exist without a passcode —
enabling it *requires* one, and the passcode remains the fallback and is demanded after every
restart and periodically thereafter. You always have both.
- **Turning Face ID off disables [Stolen Device Protection](https://support.apple.com/en-us/120340).**
That feature works by requiring Face ID **with no passcode fallback** for the dangerous actions —
changing the Apple Account password, turning off Find My, erasing the device, reading iCloud
Keychain passwords — plus a one-hour security delay away from familiar locations. With no
biometric enrolled there is nothing for it to enforce, so the protection cannot be enabled.
- **It guards the realistic attack.** A thief shoulder-surfs your passcode in a café, takes the
phone, then uses that passcode to change your Apple Account password and switch off Find My —
defeating step 1 of the lost-device procedure (§5.4) before you can reach it. Stolen Device
Protection is built precisely for that sequence.

> **The reframe worth holding on to: Face ID does not replace the passcode, it protects it.** Every
> unlock done by face is a passcode you did not type where someone could watch. Passcode observation
> is the entry point to the whole takeover chain — so biometrics *reduce* exposure of the thing that
> actually matters. It also lets you run a long alphanumeric passcode without friction, which is a
> security gain in itself.

**Set Stolen Device Protection to "Always"**, not just "Away from Familiar Locations" — your home is
a familiar location, and it is where the phone spends most of its life.

**If compelled unlock is ever a concern**, you do not need to give up Face ID for it: press and hold
the side button with either volume button for a moment (or press the side button five times) and the
phone immediately requires the passcode and refuses biometrics until it is entered. You get the
protection on demand.

**Mac — Touch ID is genuinely optional; leaving it off is fine.** No equivalent protection depends on
it, and FileVault demands the account password at boot regardless. If you leave Touch ID off, set the
Mac's screen lock to **5–10 minutes** rather than something aggressive — without biometrics, an
over-tight lock is the setting people quietly disable, and a lock you keep beats a lock you turn off.

#### Find My — exact setup, without turning on iCloud sync

Enabling Find My requires an Apple Account on each device but **does not require iCloud Drive,
Photos, or Desktop & Documents sync.** Those stay off (§5.4 table). Find My also switches on
Activation Lock, so a thief cannot wipe and reuse the device.

**On the Mac**

1. System Settings > **Privacy & Security > Location Services** → on.
2. In the app list, turn on **Find My**. If it is not listed, open **System Services > Details** and
  enable **Find My Mac**.
3. System Settings > **[your name] > iCloud > Find My Mac** → **Turn On**, then **Allow**.

**On the iPhone**

1. Settings > **[your name] > Find My > Find My iPhone** → on.
2. Turn on **Find My network** — locatable even when offline or powered down.
3. Turn on **Send Last Location** — reports position before the battery dies.

**Test both once from [icloud.com/find](https://www.icloud.com/find).** A remote-lock capability you
have never exercised is not a capability; it is an assumption. This is also step 1 of the
lost-device procedure (§5.4).

#### Backups and continuity — two devices, no local repository

**Dropping the external drive is defensible, on one condition.** The HIPAA Data Backup Plan is a
*required* implementation specification
([45 CFR 164.308(a)(7)(ii)(A)](https://www.law.cornell.edu/cfr/text/45/164.308)) — but it applies to
ePHI **you maintain**. Maintain none locally and there is nothing local to back up:

- Client records live in **SimplePractice**; calls, texts, and voicemail live in **iPlum**. Both are
cloud services under BAA, and both back up their own systems as part of the service.
- **The condition: never let PHI exist only on a device.** Do not download client documents to the
desktop — work inside SimplePractice. Empty Downloads regularly. The moment a file exists only in
a Downloads folder, no vendor backup covers it and this arrangement has a hole in it.

**Continuity: the two devices genuinely cover each other.** This is why no third device or external
drive is needed. The computer fails → the phone carries both the business line and client records,
and the day continues. The phone fails → web calling and the full EHR on the computer. Neither device
holds anything the other needs, precisely because neither holds the records.

> **What two devices do *not* cover: credentials.** Lose the password manager, the Apple Account, or
> the SimplePractice login and both devices are equally useless — the redundancy evaporates, because
> the failure is upstream of both. Keep credentials in a password manager, and put **printed recovery
> codes and the FileVault recovery key in the locked cabinet** (§2.4). That is now your only physical
> backup, and it is the one that actually matters.

**Wording for the Security Risk Analysis:** "No local ePHI repository. PHI maintained exclusively in
SimplePractice and iPlum, both BAA-covered with vendor-side backup. Continuity provided by two
independently configured devices with access to both services. Credential recovery material stored
in the locked cabinet."

#### The phone — iPlum calls and document capture

**Role: business calls through iPlum, and document capture into SimplePractice.** Both apps live
here alongside the computer, which keeps its browser-based iPlum for desk work.

> **Installing iPlum brings texts as well as calls.** The app is one app — you can choose not to
> *send* texts from the phone, but client texts will still arrive and will still raise notifications.
> Configure for both. The Show Previews setting below is what makes this safe.

**Supported through the associate period.** The iPhone 12 runs iOS 26, is expected to take iOS 27 in
September 2026, and receives security patches into roughly 2029 — past your expected full licensure.

**Encryption is already on, but the passcode is the key.** iOS Data Protection derives its keys from
your passcode in the Secure Enclave. **No passcode means no meaningful encryption**, and **Face ID
encrypts nothing** — it is a fast way to present the key, not the key.


| Setting                                  | Path                                          | Value                                                                                                                                                                |
| ---------------------------------------- | --------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Passcode                                 | Face ID & Passcode > Passcode Options         | **Custom Alphanumeric**, or 6-digit minimum. Not 4-digit                                                                                                             |
| Require Passcode                         | Face ID & Passcode                            | **Immediately**                                                                                                                                                      |
| Confirm encryption is live               | Face ID & Passcode — bottom of screen         | "Data protection is enabled"                                                                                                                                         |
| Auto-Lock                                | Display & Brightness > Auto-Lock              | 30 seconds or 1 minute                                                                                                                                               |
| **Face ID**                              | Face ID & Passcode                            | **On** — required for Stolen Device Protection (§5.4)                                                                                                                |
| **Stolen Device Protection**             | Face ID & Passcode > Stolen Device Protection | **On, set to "Always"**                                                                                                                                              |
| **Show Previews**                        | Notifications > Show Previews                 | **When Unlocked** or Never — the single most important setting once client texts arrive here                                                                         |
| Allow Access When Locked                 | Face ID & Passcode                            | Control Centre, Reply with Message, Siri — off                                                                                                                       |
| **iCloud call-history sync**             | [name] > iCloud                               | **Off** — see below                                                                                                                                                  |
| iCloud Backup — iPlum and SimplePractice | [name] > iCloud > Manage Storage > Backups    | Exclude both, pending iPlum's answer on local storage                                                                                                                |
| **iCloud Keychain**                      | [name] > iCloud > Passwords and Keychain      | **On** — required for Microsoft Authenticator backup (§5.6). End-to-end encrypted and holds no PHI, so it is a different question from iCloud Drive, which stays off |
| **SimplePractice → Photos**              | Settings > SimplePractice > Photos            | **Limited or None.** Never Full Access                                                                                                                               |
| iPlum app PIN                            | in iPlum                                      | On, if offered — a second lock behind Face ID                                                                                                                        |
| Erase Data after 10 failed attempts      | Face ID & Passcode > Erase Data               | On, if no child can reach the phone; otherwise off **and documented**                                                                                                |
| Find My iPhone                           | [name] > Find My                              | On, with Find My network and Send Last Location                                                                                                                      |
| Automatic Updates                        | General > Software Update                     | On, including security responses                                                                                                                                     |
| Third-party scanner apps                 | —                                             | **None installed**                                                                                                                                                   |


**The call log is outside the app's control.** iPlum uses the system call interface, so its calls
appear in the iPhone's own Phone → Recents list alongside cellular calls. That log **syncs to iCloud
if iCloud is on** — a vendor with no BAA. Turn iCloud call-history sync off, or accept that client
numbers reach it, and record which you chose in the risk analysis.

**Notification previews are the setting that actually bites in a shared home.** By default iOS shows
message content on the lock screen. An iPlum text preview showing a client's name, on a phone lying
on the kitchen counter, is a disclosure to everyone who walks past. Set Show Previews to "When
Unlocked" — with Face ID this is barely a nuisance, since previews appear the moment you look at it.

**Scanning rules.** Use **SimplePractice's in-app camera capture only** (iOS 17.3+; the iPhone 12
qualifies) so the image goes straight into the client's file under BAA. **Never** use Apple Notes
scan, the Files app scanner, Adobe Scan, or Genius Scan — every one writes locally and syncs to a
cloud with no BAA.

**Still ask iPlum where its data lives** — server-side under their BAA, or in local app storage? If
local, the iCloud Backup exclusion above is mandatory rather than precautionary. On the open-items
list (§9).

#### Apple Family Sharing — fine, with three things to verify

**Family Sharing is not a shared Apple Account.** The two get confused constantly and they are not
the same thing:

- A **shared Apple Account** — everyone signing into one ID — would be disqualifying. Everything
syncs between people, and it fails unique user identification.
- **Family Sharing** groups **separate** Apple Accounts. Each person keeps their own. Sharing an
iCloud+ plan shares the storage **quota, not the data**: photos, documents, and backups stay
private to each account, and **no family member can access another member's backup**.

**So yes — you can scan into SimplePractice with Family Sharing enabled.** No configuration change
is required to make it acceptable. Verify three things once and record the result in the risk analysis:


| Verify                                                                                             | Where                   | Why it matters                                                                                                                |
| -------------------------------------------------------------------------------------------------- | ----------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **iCloud Shared Photo Library** off — or "Sharing Automatically" and "Share When at Home" both off | Photos > Shared Library | Opt-in and off by default, but if ever enabled, camera captures can auto-flow to family                                       |
| **Shared Albums** — none set to receive camera content                                             | Photos > Albums         | Opt-in and per-photo, but confirm                                                                                             |
| **Screen Time** — nobody else manages this device                                                  | Settings > Screen Time  | A family organiser with management rights over your device is a supervision path you do not want on hardware that touches PHI |


Optionally turn off **Purchase Sharing** if you would rather family not see that you installed
clinical apps. That reveals your profession, not PHI — a preference, not a requirement.

> **The real control is still the passcode.** If a household member knows it, none of the above
> matters. It is not shared, and it is not written anywhere they can reach.



#### Protecting the phone — in use, and when it goes missing

**In-use discipline**


| Rule                                                 | Why                                                                                                                                       |
| ---------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| Take client calls only where you cannot be overheard | The confidentiality duty follows the conversation, not the device. A call taken in a supermarket is a disclosure regardless of encryption |
| Never leave the phone unattended and unlocked        | Auto-lock is a backstop, not a substitute for habit                                                                                       |
| **Do not screenshot client information**             | Screenshots land in Photos, and Photos may sync to iCloud — a vendor with no BAA                                                          |
| Keep iPlum and SimplePractice updated, not just iOS  | App updates carry security fixes as much as the OS does                                                                                   |
| Keep the phone out of camera frame during sessions   | The §5.4 workspace rules apply to the phone as much as the desk                                                                           |
| Public Wi-Fi is acceptable for iPlum calls           | Traffic is encrypted in transit. The risk in public is being **overheard**, not intercepted                                               |


**If the phone is lost or stolen — do this the same day, in order**

1. **Remote lock.** Find My > Mark As Lost. Locks the device and suspends Apple Pay.
2. **Lock the iPlum account.** iPlum lets an administrator lock an account so its information cannot
  be reached from a lost or stolen device — independent of Apple. **Learn these steps before you
   need them** and write them into the breach procedure.
3. **Change passwords** — Apple Account, iPlum, SimplePractice, password manager. Assume the device
  is gone.
4. **Remote wipe** once you accept it is not coming back: Find My > Erase This Device.
5. **Document it** — date, time, what was on the device, what you did and when. The Security Rule
  expects the incident recorded even when no notification is required.
6. **Assess before assuming a breach** — see below.

**The encryption safe harbour is the payoff for the settings table above.** Under
[45 CFR 164.402](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-D/section-164.402)
a breach excludes PHI that was **secured**, and HHS guidance points to encryption meeting
**NIST SP 800-111** for data at rest. **If the phone was encrypted and the passcode was not
compromised, losing it is generally not a reportable breach.** Two conditions carry it:

- **Data Protection genuinely active** — which exists only because you set a passcode (§5.4 table).
A device that is merely "password-protected" without encryption does **not** qualify, and a full
breach risk assessment follows instead.
- **The key was not compromised** — the passcode is not written down near the phone, not shared with
household members, and not guessable.

Configured properly, a lost phone is an inconvenience and a documented incident. Configured
carelessly, it is a notifiable breach touching every client whose name ever reached the device. That
difference is made entirely by two settings you can change in ninety seconds.

> Put the lost-device steps in the **breach notification procedure** (§5.1), not only here. On the
> day it happens you will not be reading the business plan.

**Retirement — around 2029.** When the iPhone 12 leaves service, wipe it before sale, trade-in, or
disposal: sign out of the Apple Account, then Settings > General > Transfer or Reset > **Erase All
Content and Settings**. On an encrypted device this destroys the keys and renders the data
unrecoverable. Record the date and method — device disposal falls under the same media-controls duty
as shredding paper (§2.4).

#### The business line: iPlum on the computer and the phone

**Confirmed: iPlum Professional includes web calling at no extra cost.** You make and receive calls,
take voicemail, and send texts from a browser panel with a keypad, recents, contacts, and voicemail
inbox — **no phone or extra hardware required**
([iPlum web calling FAQ](https://www.iplum.com/faq/how-to-make-or-receive-calls-using-iplum-web-portal)).
Use the over-ear headphones from §5.4 as the headset.

**The plan tier matters and is not optional.** HIPAA compliance and the BAA are locked to
**Professional ($14.99/mo)**; the Standard plan at $8.99 has **no BAA**. Confirm you are on
Professional before the first client. **Each iPlum number carries its own BAA** — retain the
countersigned copy in the HIPAA file.

**Both surfaces, one number.** The browser panel is the desk tool; the phone app covers calls away
from the desk. **Family Sharing does not affect this** (§5.4 above) — it never would have. The two
exposures that adding the phone does create are lock-screen notification previews and the system
call log, and both are handled by the phone settings table above. Neither is a reason to avoid the
app; both are reasons to configure it before the first client.

**The trade-off, and how to handle it.** Calls only ring while you are logged in with the browser
open. Everything else goes to voicemail. For a therapy practice that is acceptable — you do not
take calls during sessions anyway — but it must be set up honestly:

- State response times in the voicemail greeting and in the consent forms: "calls returned within
one business day," and that the line is **not** for emergencies, with the crisis instruction given
explicitly.
- Enable browser and native notifications, which iPlum requires for call and text alerts.
- **Test inbound call, outbound call, voicemail, and text on both surfaces before the first client.**
- Decide which surface rings by default so the same call does not alert twice, then keep it consistent.



#### Household members

**They are not workforce members.** They have no role in the practice, so any access they have to
PHI is an impermissible disclosure — not a softer category of problem. Leak paths, ordered by how
often they actually bite:

1. **Shared logins and admin rights** — above.
2. **Shared Apple ID, Family Sharing, or a shared Google account.** These sync Messages, photos,
  iCloud Drive, and backups between people. A shared Apple ID *is* a shared account.
3. **Smart speakers and voice assistants in the therapy room.** An Alexa or Google Home is a live
  microphone in a confidential space, streaming to a vendor with no BAA. **Remove them from the
   room.** Easy to fix, easy to forget.
4. **Shared printer.** Print jobs left in the tray, and retained printer memory. Print client
  material rarely; collect it immediately.
5. **Shared NAS or a family backup drive.** Never store practice data there.
6. **Overheard sessions.** Closed door, headphones, and a white-noise machine outside the door if
  the walls are thin. Schedule around the household's busy hours where you can.
7. **Camera framing.** Whatever sits behind and beside you is visible to the client — a whiteboard,
  sticky notes, opened mail, or another person crossing the room.
8. **Shared Wi-Fi is generally acceptable** — traffic is TLS-encrypted end to end. Change the
  router's default admin password and put IoT devices on a guest network.

**Write the household rule down, and say it once, plainly:** nobody else uses the practice device,
answers the business line, opens practice mail, or enters the session zone during session hours.
This belongs in the Security Risk Analysis as an administrative safeguard.

#### Working without a dedicated room

**A dedicated room is not required.** The Security Rule is explicitly flexible and scalable to your
size and environment ([45 CFR 164.306(b)](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-C/section-164.306)),
and the Workstation Use standard ([45 CFR 164.310(b)](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-C/section-164.310))
requires a documented *policy* covering "the physical attributes of the surroundings" of your
workstation — not a particular floor plan. There is no small-practice exemption, but there is no
room requirement either. What matters is choosing reasonable controls for the space you actually
have, and writing down why.

**Exclusive *time* substitutes for exclusive *space* — and you have it.** No household member is in
the room while you see clients or handle client paper. That is the practice's **primary
administrative safeguard**, and it closes two of the three risk categories outright:


| Risk                                                           | Room exclusivity                                         | Remaining gap                                               |
| -------------------------------------------------------------- | -------------------------------------------------------- | ----------------------------------------------------------- |
| **Visual** — screen, papers, or mail seen by others            | **Closed**                                               | —                                                           |
| **Physical access** — someone handling documents or the device | **Closed**                                               | —                                                           |
| **Sound** — being overheard                                    | **Not closed.** Someone in the next room still hears you | Headphones · white noise outside the door · sealed door gap |


So the acoustic stack below is not redundancy — it is the only remaining gap. Treat the session
window as a fixed constraint when setting availability in SimplePractice, not something to flex for
a client's convenience.

**The strongest version:** where the household schedule allows, put sessions in windows when the
residence is *empty* rather than merely the room. That closes the sound gap too, and is worth
aiming for even if it cannot cover every slot.

**Define a zone, not a room.** A bedroom with the door closed during sessions, a corner behind a
folding screen or ceiling-track curtain, or a closet conversion. Whatever it is, it needs a door or
barrier you can close, and your chair should face away from the rest of the apartment.

**Sound — where the actual risk lives.**


| Control                                              | Note                                                                                                                                                  |
| ---------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Closed-back over-ear headphones — non-negotiable** | Removes the client's voice from the room entirely. Solves half the problem by itself. You already own a pair, so **$0**. See the wireless note below. |
| **White-noise machine *outside* the door**           | The common mistake is putting it inside. It has to mask *your* voice for someone in the hallway or next room.                                         |
| Door gap sealed — draft stopper or weatherstrip      | Door undercuts are the main leak path in an apartment; $15–30 fixes it                                                                                |
| Soft material on the shared wall                     | Bookshelf, heavy curtain, rug — absorb rather than only block                                                                                         |
| Normal conversational volume                         | A raised voice defeats everything above                                                                                                               |


**Wireless headphones and AirPods — both acceptable.** No rule prohibits them. HHS expects the risk
to be identified and addressed in the risk analysis rather than the technology banned, and modern
Bluetooth audio is encrypted. **The axis that actually matters is closed-back versus open**, not
wired versus wireless: open-back headphones leak the client's voice into the room, which is a far
more realistic exposure than Bluetooth interception.

If you use AirPods, four conditions:

1. **Never use Share Audio.** It routes session audio to a second set of AirPods.
2. **Confirm they are paired only to your devices.** AirPods auto-switch between devices on the same
  Apple Account; Family Sharing keeps accounts separate (§5.4), but check they are not also paired
   to a household member's device.
3. **Keep a wired pair as backup, and keep them charged.** The genuine risk is not interception — it
  is the battery dying mid-session and audio falling back to the laptop speaker, broadcasting the
   client's voice into the room. Plan for that failure, not for eavesdroppers.
4. Standard AirPods do not seal and leak at higher volume. **AirPods Pro with tips, or closed-back
  over-ear, are better.**

Keep both devices non-discoverable over Bluetooth except while pairing, and record the headphone
choice in the risk analysis.

**Sight — two separate risks.**

1. **What the client sees.** A neutral wall behind you. Prefer a physical backdrop or blank wall over
  a virtual background, which glitches and reveals the room. Nothing identifiable in frame: no
   whiteboard, no sticky notes, no opened mail, no doorway with traffic through it.
2. **What household members see** — the one that gets missed. Your monitor displays the client's face
  and name. Sit with your back to a wall, angle the screen away from any walking path, and add a
   **privacy screen filter ($20–40)** so the display is unreadable off-axis.

**Records, with no lockable room.** The locked cabinet does this job — that is why it is in the plan
(§2.4). Lock it whenever you leave the space, not only at night. Clear the desk at the end of every
*session*, not the end of the day. Lock the laptop screen whenever you stand up.

**Opening mail without a private office.** The rule is not "a separate room" — it is "not where
others can see it or reach it":

- Open it when you are alone in the residence, or in the session zone with the door closed
- Open it standing at the cabinet, with the shredder beside you
- **One-touch rule: open → scan into SimplePractice or file → shred.** Nothing gets set down, nothing accumulates
- Never on the kitchen table, the couch, or any shared surface
- If something must wait, it waits **inside the locked cabinet**, not in a tray on the desk

**Tell clients the truth about the setting.** The telehealth consent (§4.5) should describe your
space honestly — that you work from a private home setting, use headphones, and take specific steps
against being overheard. Do not describe a soundproofed dedicated office you do not have. And ask
the client about *their* privacy at the start of each session: in telehealth, the client's end is
more often the leak than yours.

**Document the arrangement in the Security Risk Analysis.** "No dedicated room. Primary control:
no household member present in the room during sessions or paper handling, enforced by schedule.
Compensating acoustic and physical controls: closed-door zone, over-ear headphones, external white
noise, sealed door gap, privacy filter, locked cabinet." The *undocumented* arrangement is the
problem — not the arrangement.

### 5.5 Email, exports, and the retention archive



#### Email — no PHI, by policy

**Microsoft 365 Business Basic stays.** Exchange Online and OneDrive for Business are both in-scope
under Microsoft's HIPAA BAA, which is incorporated automatically through the Data Protection
Addendum — there is nothing to sign. But Business Basic has **no message encryption**, so email
falls back on opportunistic TLS: if the recipient's server does not support it, the message can
cross in clear.

**Therefore: no PHI in email.** Clinical communication goes through the SimplePractice client portal
and iPlum. Two things make the policy stick:

- Say it in the **consent for electronic communication** (§4.5), before the first session.
- Put a standing line in the email signature: *"Please do not send clinical or personal health
information by email — use the client portal."*



#### When a client emails PHI anyway — because they will

> **First, the distinction that matters: a client sending you their own PHI is not a breach by you.**
> A breach is *you* disclosing PHI improperly. An inbound client email is a channel problem, not a
> reportable incident. Do not treat it as one.

1. **Do not reply with PHI.** Answer through the SimplePractice portal. If you reply by email at
  all, keep it content-free: *"I received your message and have replied in the client portal."*
2. **Move it into the record.** If it is clinically relevant it belongs in the client's file in
  SimplePractice, and the retention clock applies to it there.
3. **Delete it from the mailbox afterwards**, including Deleted Items, so email does not quietly
  become a second PHI store. **Exception:** keep it if there is any complaint, subpoena, or
   litigation hold in play.
4. **Redirect the client once, kindly.** Remind them of the portal and why. Do not shame someone for
  trying to reach their therapist.
5. **Log the pattern, not every instance.** Repeated occurrences mean the intake instructions need
  rewriting, not that the client needs correcting again.

**If *you* send PHI to the wrong recipient, that is a different matter entirely** — a potential
breach. Go to the breach notification procedure (§5.1), run the risk assessment, and notify if
required.

#### The retention archive — three copies, only one of which counts

**SimplePractice deletes your data when you leave.** Cancelled accounts cannot be recovered, and
retention after cancellation or expiry is **no more than 64 days**. Their documentation is explicit
that you are responsible for retaining anything you export. Microsoft's lifecycle is more forgiving
— roughly 30 days expired, then ~90 days read-only, then deleted — but it is the same shape of
failure.

Your obligation is **five years after last visit** ([WAC 246-809-035](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-035)),
and it is yours, not a vendor's.


| Copy                  | Where                                                                          | Survives                                             |
| --------------------- | ------------------------------------------------------------------------------ | ---------------------------------------------------- |
| Live records          | SimplePractice                                                                 | while subscribed                                     |
| Working archive       | **OneDrive for Business**, encrypted                                           | while subscribed (~120-day grace)                    |
| **Retention archive** | **Encrypted external drive** — bought and written **at shutdown only** (§10.1) | the end of the practice, and the five years after it |


In normal operation only the first two exist. **The drive is a shutdown artefact** (§10.1) — it is
bought and written when the practice closes, not maintained alongside.

> **The consequence to accept knowingly:** while the practice is running, nothing survives an unpaid
> card. If the Microsoft subscription lapses the archive follows it, on roughly a 120-day clock. That
> is tolerable while you are alive and paying attention; it is the death-and-incapacity case that
> needs covering, so the custodian's instructions carry a **deadline**, not just a location (§10.9).
> If you would rather close that gap, see the note on an encrypted USB stick in §5.6 — it fits the
> thin folder.

**Using OneDrive for Business for exports — permitted on Basic, with conditions:**

1. It must be **OneDrive for Business** on the work tenant. Personal OneDrive carries the same brand
  and is **not** BAA-covered.
2. **Encrypt each archive before upload** — an encrypted container with a strong passphrase. Basic
  has no DLP or sensitivity labels to enforce anything, so encryption is what compensates. It also
   means the encryption safe harbour applies if there is ever an incident (§5.4).
3. **Browser access only — do not install the sync client.** The work Mac stays a terminal.
4. Disable anonymous "anyone with the link" sharing; restrict external sharing.
5. Passphrase into the password manager **and** printed in the locked cabinet.

**Which encryption counts.** HHS's safe harbour points to **NIST SP 800-111** for data at rest,
which in practice means AES. Two methods, both native to macOS and both sufficient:

- **Archive files → encrypted disk image (**`.dmg`**) at 256-bit AES**, built in Disk Utility.
- **External drive → APFS (Encrypted)** at format time — whole volume, nothing to manage per file (§10.1).

**How to make the encrypted archive — Disk Utility, AES-256**

1. Put the quarter's exports in one folder, e.g. `SP-Export-2026-Q3`.
2. Open **Disk Utility**.
3. Menu **File > New Image > Image from Folder…**, select the folder, click **Choose**.
4. In the save sheet:
  - **Save As**: `SP-Export-2026-Q3.dmg`
  - **Encryption**: **256-bit AES encryption**
  - Enter and verify the passphrase
  - **Uncheck "Remember password in my Keychain."** Leave it ticked and the Mac unlocks the image
  automatically — the encryption then protects nothing on the machine that matters most.
  - **Image Format**: *read-only* (or *compressed* to save space)
5. Click **Save**.
6. **Verify**: double-click the `.dmg`, confirm it asks for the passphrase, mounts, and the files
  open. Then eject it.
7. Upload the `.dmg` to OneDrive. That is the archive during normal operation (§10.1 covers shutdown).

**At shutdown**, when you do write to an external drive, encrypt the whole volume once instead:
Disk Utility > select the drive > **Erase** > Format **APFS (Encrypted)** > set the passphrase (§10.1).

**Key management is half the requirement.** HHS is explicit that decryption keys must be kept
separately from the data they protect. Passphrase goes in the password manager **and** printed in the
locked cabinet — never in the same OneDrive folder, and never in the archive's filename.

> **Would Business Premium make this easier? No — and it would not remove the step.** OneDrive
> already encrypts everything at rest on **every** plan including Basic: BitLocker plus per-file
> AES-256 keys, FIPS 140-2 validated. What your own container adds is protection against *access*
> compromise — a link shared too widely, or stolen credentials — which service-side encryption cannot
> help with, because the service decrypts for any authorised session. Premium's sensitivity labels
> could cover that more elegantly, but **labelling with encryption depends on Azure Information
> Protection P1 licensing**, and automatic labelling needs a higher tier again, so the benefit is
> conditional and would need confirming with Microsoft. A two-minute encrypted `.dmg` each quarter
> costs nothing and qualifies without argument.

**Export routine: quarterly, or annually at minimum.** Note that the SimplePractice export covers
**client information only** — reports and payment data export separately, so a complete archive is
several files, not one.

> **This is the gap that closes the professional will (§4.7).** If you die or are incapacitated, the
> card stops clearing, the subscription lapses, and **within 64 days the records are gone** — leaving
> your custodian with a legal duty to retain records that no longer exist. The custodian needs the
> **encrypted drive and where its passphrase is kept**, not a SimplePractice login. Add to the
> custodian instructions: how to export, funds or means to keep the subscription alive long enough
> to do it, and where the archive lives.



### 5.6 Keys and recovery material — what has no reset button

Most passwords have a "forgot password" link. A few here do not, and losing one of those is not an
inconvenience — it is permanent data loss, and in two cases it means **failing a legal retention
duty**. Treat this list differently from ordinary credentials.

**Tier 1 — irrecoverable. No reset exists.**


| Secret                                                                     | What it unlocks                                           | If lost                                                                            |
| -------------------------------------------------------------------------- | --------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| **FileVault recovery key**                                                 | The Mac's disk, if the account password is ever forgotten | Disk unrecoverable. Apple cannot help — you chose the local key, not iCloud (§5.4) |
| **Archive passphrase** (`.dmg`)                                            | Every SimplePractice export                               | Archive gone. **Five-year retention duty failed** (§10.1)                          |
| **External drive passphrase** — *exists only from shutdown onward* (§10.1) | The retention archive itself                              | Same                                                                               |
| **Password manager master password**                                       | Everything else                                           | Everything else. No reset, by design                                               |
| **Password manager secret key / recovery kit**                             | Enrolling a new device                                    | Cannot add a device even with the master password                                  |


**Tier 2 — recovery codes. The way back in when the usual method is gone.**


| Secret                                                                          | Why it matters                                                                    |
| ------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **Authenticator app backup / TOTP seeds**                                       | If the phone dies with no backup, **every MFA account locks at once** — see below |
| **Apple Account recovery key or recovery contact**                              | Replaces Apple's normal account recovery once enabled                             |
| MFA backup codes — Microsoft 365, SimplePractice, iPlum, BECU, Cloudflare, Wave | Single-use; some rotate once used                                                 |




#### Authenticator backup — what Microsoft Authenticator does and does not restore

**It does back up third-party TOTP seeds.** Microsoft's own documentation is explicit: account names
**and third-party TOTP credentials** are backed up, and for third-party accounts the rotating codes
work again once restored. So SimplePractice, iPlum, BECU, Cloudflare and Wave come back intact.

**But work and school accounts do not.** For those, **only the account name is backed up** — you have
to sign in and re-enrol. **Your Microsoft 365 account is a work account**, so it is the one that will
*not* simply reappear. Keep its backup codes on the recovery sheet, or you can be locked out of the
very tenant you would use to fix things.

**On iOS the backup now goes through iCloud and iCloud Keychain** (since September 2025; iOS 16+),
with no personal Microsoft account required. That is why **iCloud Keychain stays on** in the §5.4
table even though iCloud Drive, Photos and Desktop & Documents stay off. It is a different question:
Keychain is end-to-end encrypted, Apple cannot read it, and **TOTP seeds are not PHI** — so no BAA is
needed for it.

**The universal fallback: capture the secret at enrolment.** Vendor backups are convenient; this is
what actually guarantees recovery, and it works with any app forever.

1. When a service shows its QR code, click **"Can't scan the code?"** (or "enter this code manually").
2. It reveals the plain **secret string** — that string *is* the account's TOTP seed.
3. Write it on the recovery sheet before you finish enrolling. Thirty seconds per account.
4. Any authenticator app, on any future phone, can be re-seeded from it — no vendor involved.

> The sheet then holds live TOTP seeds, so it stays sealed in the locked cabinet (§2.4). Note what it
> does **not** hold: passwords. A seed on its own does not log anyone in.

**If you would rather not run a separate app**, a password manager with built-in TOTP (1Password,
Bitwarden) makes backup automatic — the vault already syncs and is already recoverable via the master
password and secret key. The trade-off is real and worth naming: password and second factor then live
in the same vault, so whoever opens the vault has both. That is acceptable here because the vault
itself is behind a master password, a secret key, and its own MFA — but decide it deliberately rather
than by drift.

**The trap: recovery material stored inside the thing it recovers.** Every one of these is a real
circular dependency people walk into:

- Master password kept *in* the password manager — it opens nothing.
- MFA backup codes only in the password manager, whose own MFA lives on the phone you just lost.
- Archive passphrase saved on the drive, or in the same OneDrive folder as the archive.
- All TOTP seeds only on the iPhone — which you would need TOTP to recover.

**Where each thing lives**


| Location                                          | Contents                                                                                | Purpose                                    |
| ------------------------------------------------- | --------------------------------------------------------------------------------------- | ------------------------------------------ |
| **Password manager**                              | Day-to-day passwords, TOTP seeds                                                        | Daily use                                  |
| **Printed, sealed, in the locked cabinet** (§2.4) | Everything in Tier 1 and Tier 2                                                         | At-hand recovery                           |
| **Family safe deposit box**                       | A **thin folder**: a few key papers and a sealed copy of the recovery sheet — see below | Survives fire, flood, burglary at the flat |
| **Sealed envelope with the records custodian**    | Archive passphrase, drive locations, and what to do                                     | Someone can act when you cannot            |


The custodian needs to know **that the envelope exists and where** (§4.7, §10.9) — not what is inside it.

#### Using the family safe deposit box

You already have one, and only you and your spouse hold access. It closes the gap the locked cabinet
cannot: **if the flat burns, the cabinet and the drive burn together.** One rule governs how it is used.

It holds **a thin folder only** — a few sheets of paper. No drive. That constraint actually makes the
design simpler, because there is no encrypted media in there for a key to sit next to.

**What belongs in the folder**


| Item                                                                          | Why                                                                                            |
| ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| **Sealed copy of the recovery sheet** (§5.6)                                  | The fireproof offsite copy of Tier 1 and Tier 2 — passphrases, FileVault key, MFA backup codes |
| **EIN confirmation letter (CP 575)**                                          | The IRS will not reissue it — they send a 147C letter instead, which takes weeks               |
| **Stamped Certificate of Formation**, signed **Operating Agreement** original | Slow and awkward to replace (§2.1, §2.2)                                                       |
| Box inventory — one page listing what is in the folder                        | So you and the custodian know the contents without opening it                                  |


**Your spouse has access, and is not a workforce member.** That is manageable rather than
disqualifying, and worth being deliberate about:

- **Seal the recovery sheet in a marked envelope** — "practice records, do not open" — and agree once
that it is not opened. A household agreement is a legitimate administrative safeguard; write it
into the Security Risk Analysis (§5.1) rather than leaving it as an understanding.
- **The sheet contains no passwords.** MFA backup codes and passphrases without the corresponding
logins do not get anyone into SimplePractice or OneDrive.
- The FileVault key is the one item that would matter with physical access to the Mac — and it
matters little, because that machine is deliberately **a terminal, not a repository** (§5.5). There
is no PHI store on the disk to reach.

**Tell your spouse what to do, once:** if something happens to you, the sealed envelope goes to the
records custodian, whose name and number they should have. **The custodian has no access to the box**,
so this handoff is the only route that makes §10.9 work.

> **Optional, and it fits the thin folder: an encrypted USB stick.** A few gigabytes covers years of
> exports, and a stick is a couple of millimetres thick. Format it APFS (Encrypted) the same way, drop
> it in the folder, refresh it annually. That restores the copy that survives an unpaid subscription
> without needing a drive — the only caveat being the §5.6 rule: **if the stick goes in, the recovery
> sheet comes out**, into the cabinet and the custodian's envelope. Never the media and its key together.

**Check the folder annually** against its inventory (§8).

**Check it once a year.** Confirm the printed sheet is legible and current, that unused codes still
work, and that the archive passphrase actually opens the most recent `.dmg`. Recovery material you
have never tested is a guess, not a backup.

---



## 6. Revenue model

Fixed overhead is not the risk in this business — client acquisition is. Set these numbers before
launch and revisit them quarterly.

### 6.1 Assumptions


| Variable                 | Assumption                                                                                                                                                     |
| ------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Private-pay session rate | $110 (WA associate range $80–130)                                                                                                                              |
| Payment model            | **Private pay + superbills.** Most commercial payers will not credential an associate — treat any paneling as a separate go/no-go decision, not an assumption. |
| Target caseload          | 15 billable sessions/week                                                                                                                                      |
| Working weeks            | 46/year                                                                                                                                                        |
| Ramp                     | 6–12 months to fill; plan year 1 at roughly one-third of target                                                                                                |
| Processing               | 3.2% of collections                                                                                                                                            |




### 6.2 Full-caseload year


| Line                                        | Amount       |
| ------------------------------------------- | ------------ |
| 690 sessions × $110                         | $75,900      |
| Less payment processing (3.2%)              | −$2,429      |
| Less fixed overhead ($162.84 × 12)          | −$1,954      |
| Less supervision ($10,000 over 3 years)     | −$3,333      |
| **Net before tax**                          | **~$68,184** |
| Less federal income + SE tax reserve (~27%) | −$18,410     |
| **Approximate take-home**                   | **~$49,800** |




### 6.3 Break-even

- Fixed overhead only ($163/mo): **~2 sessions/month**
- Fixed + supervision ($441/mo): **~4 sessions/month**

Break-even is trivially low. Plan attention and spending accordingly: the constraint is referral
flow and the six-year licensure clock, not overhead.

### 6.4 Licensure pacing check

At 15 sessions/week, 1,200 direct-contact hours takes roughly 80 weeks. The binding constraints are
the 3,000 total hours and the 36-month minimum — comfortably inside the six-renewal ceiling, but
only if caseload actually ramps. Track hours monthly against §4.2.

---



## 7. Launch checklist

Each phase lists its tasks, then the documents that phase produces or obtains. **(P)** = you write or
sign it; **(O)** = a third party issues it to you. Keep everything in five files:


| File            | Contents                                                                |
| --------------- | ----------------------------------------------------------------------- |
| **Entity**      | Formation, tax IDs, licenses, banking                                   |
| **Supervision** | Declaration, agreement, logs, hour tracker (§4.2)                       |
| **Compliance**  | Credential, training certificates, CE records, retention and succession |
| **HIPAA**       | Risk analysis, policies, BAAs, officer designation (retain 6 years)     |
| **Insurance**   | Policy, declarations page, renewals                                     |


Client documents live per-client in SimplePractice, not in these files.

**Spending sequence.** The phases are ordered so that as little money as possible leaves a personal
account. Every expense that can wait does wait, until the business checking account and card exist
in **Phase 3** — that keeps the bookkeeping clean, the deductions easy to substantiate, and the
personal/business separation that §2.2 depends on intact from the first transaction.

Only three things unavoidably come first, because the bank needs them to open the account at all:


| Unavoidable pre-account spend                                        | Amount        |
| -------------------------------------------------------------------- | ------------- |
| PLLC Certificate of Formation                                        | $180–200      |
| WA Business License Application (produces the UBI the bank asks for) | $90           |
| Redmond city endorsement                                             | $160          |
| **Total paid from personal funds**                                   | **~$430–450** |


Pay these personally, keep the receipts, and record the total as the **initial capital contribution**
in Phase 3 — which is exactly the contribution the Operating Agreement (§2.2) provides for. Do not
treat it as a personal gift to the business or leave it undocumented.

If account opening drags and something genuinely cannot wait, pay personally and file a dated
expense reimbursement from the business account once it opens. Reimbursement is fine; *undocumented*
reimbursement is what causes problems.

### Phase 1 — Decide and verify (before any filing)

- [ ] **Find supervisor** — start here. Supervision gates every clinical hour, sets the largest recurring cost, and approved supervisors have limited capacity. Verify the candidate meets [WAC 246-809-234](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-234) and agree a rate before committing to the rest of the plan (§4.2)
- [ ] Accept that the apartment street address is public as the Principal Office (§2.3) — a legal requirement, not a choice
- [ ] Confirm PLLC name availability — [CCFS](https://ccfs.sos.wa.gov/)
- [ ] Confirm current SOS formation fee and annual report fee
- [ ] Confirm Redmond licensing: does a solo home-based owner count as 1 FTE? Any small-business threshold? — 425-556-2193, [RMC Ch. 5.04](https://www.redmond.gov/230/Business-Licensing)
- [ ] Confirm Redmond home-occupation / zoning rules for a no-client-visit telehealth practice
- [ ] **Confirm the apartment lease permits home business use**
- [ ] Serve as your own registered agent (§2.3) — apartment street address, and sign the written consent to serve
- [ ] Confirm the WA disclosure statement, telehealth consent, and ROI can be delivered as Starter *intake forms* (§5.2)
- [ ] Re-quote HPSO; confirm the PLLC can be a named insured
- [ ] Confirm the home address will be used for every mailing field (§2.4) — no mailbox provider at launch
- [ ] **Confirm you can hold sole admin on the existing machine** (§5.4). If anyone else holds admin and will not give it up, the separate-account design does not work and a dedicated machine becomes necessary

**Documents**


| Document                                                                                               |     | File        |
| ------------------------------------------------------------------------------------------------------ | --- | ----------- |
| Supervisor's proof of licensure, good standing, and 15 hours of supervision training                   | O   | Supervision |
| Supervisor's written rate quote                                                                        | O   | Supervision |
| PLLC name availability search result                                                                   | P   | Entity      |
| Redmond licensing determination — FTE treatment and thresholds, with the date and name of who answered | P   | Entity      |
| Redmond home-occupation / zoning confirmation                                                          | O   | Entity      |
| **Landlord or lease written confirmation that home business use is permitted**                         | O   | Entity      |
| Consent to Serve as Registered Agent, signed                                                           | P   | Entity      |
| HPSO quote naming the PLLC as insured                                                                  | O   | Insurance   |




### Phase 2 — Form the entity

- [ ] File Certificate of Formation — Principal Office street address = apartment (required); mailing address = home, or left blank (§2.4)
- [ ] Complete Initial Report
- [ ] Obtain EIN — [IRS](https://www.irs.gov/businesses/small-businesses-self-employed/apply-for-an-employer-identification-number-ein-online)
- [ ] File WA Business License Application; obtain UBI — [DOR](https://dor.wa.gov/open-business/apply-business-license)
- [ ] Add Redmond city endorsement
- [ ] Obtain **NPI Type 1** and **NPI Type 2** — [NPPES](https://nppes.cms.hhs.gov/) (§2.6)
- [ ] **Write and sign the Operating Agreement** — see note below
- [ ] Calendar the annual report due date (formation anniversary month)

> **Operating Agreement.** Washington does not require you to file one, and a single-member PLLC can
> feel like it does not need one — but it is the document that shows the PLLC is a real entity
> separate from you. That separation is what the liability shield rests on, and it is the first
> thing challenged if anyone ever tries to pierce it. BECU will also likely ask for it at account
> opening. Cover: ownership, that the sole member is a licensed LMHCA, management, capital
> contributions, distributions, and dissolution.

**Documents**


| Document                                                                 |     | File   |
| ------------------------------------------------------------------------ | --- | ------ |
| Certificate of Formation, filed and stamped                              | O   | Entity |
| Initial Report confirmation                                              | O   | Entity |
| **Operating Agreement**, signed                                          | P   | Entity |
| EIN confirmation letter (CP 575)                                         | O   | Entity |
| WA business license / UBI certificate — post it at the place of business | O   | Entity |
| Redmond business license                                                 | O   | Entity |
| NPI Type 1 confirmation                                                  | O   | Entity |
| **NPI Type 2** confirmation (the PLLC, §2.6)                             | O   | Entity |




### Phase 3 — Banking (open the account before you spend)

- [ ] Open [BECU Business Basic Checking](https://www.becu.org/business) (bring Certificate of Formation, EIN letter, UBI, ID)
- [ ] Apply for the BECU Business Cash Back card if desired
- [ ] Make the initial owner contribution and document it
- [ ] Move all recurring practice subscriptions onto the business card
- [ ] Set up a separate tax-reserve savings account; automate 25–30% of net into it
- [ ] Set up the Wave chart of accounts to match the §3.5 expense categories
- [ ] Calendar the four quarterly estimated-tax dates

**Documents**


| Document                                                                                              |     | File   |
| ----------------------------------------------------------------------------------------------------- | --- | ------ |
| BECU account agreement and signature card                                                             | O   | Entity |
| **Capital contribution memo** — amount, date, and transfer receipt for the initial owner contribution | P   | Entity |
| Business card agreement                                                                               | O   | Entity |
| Chart of accounts matching §3.5                                                                       | P   | Entity |
| Estimated-tax payment calendar                                                                        | P   | Entity |




### Phase 4 — Clinical compliance

- [ ] Confirm active LMHCA credential and note the renewal-count position against the six-renewal cap
- [ ] Obtain the signed [supervisor declaration](https://doh.wa.gov/sites/default/files/legacy/Documents/Pubs//670130.pdf) from the Phase 1 supervisor **before supervision begins**
- [ ] Sign supervision agreement; record the actual monthly cost and replace the §3.2 planning figure
- [ ] Establish supervision log and the **2,500 / 1,200 / 50** hour tracker (post-CACREP credit, §4.2)
- [ ] Ask DOH whether the CACREP credit also reduces the 1,200 direct-contact hours and the 36-month minimum (§4.2)
- [ ] Complete telemedicine training; **sign and file the attestation** ([RCW 43.70.495](https://app.leg.wa.gov/rcw/default.aspx?cite=43.70.495))
- [ ] Plan the 6-hour suicide prevention course from the [DOH model list](https://doh.wa.gov/public-health-provider-resources/healthcare-professions-and-facilities/suicide-prevention/training-programs/model-list)
- [ ] Select a CE subscription covering 18 hours/year
- [ ] Write the records retention policy (5 years post-last-visit) and the professional will / records custodian arrangement ([WAC 246-809-035](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-035))

**Documents**


| Document                                                                                       |     | File        |
| ---------------------------------------------------------------------------------------------- | --- | ----------- |
| LMHCA credential printout — expiration date and renewals used against the six-renewal cap      | O   | Compliance  |
| **Approved Supervisor Declaration** (DOH 670130), signed by the supervisor                     | O   | Supervision |
| **Supervision agreement** — parties, fee, frequency, format, responsibilities, confidentiality | P   | Supervision |
| Supervision log, started                                                                       | P   | Supervision |
| Hour tracker against 2,500 / 1,200 / 50                                                        | P   | Supervision |
| DOH's written answer on CACREP credit vs. direct-contact hours and the 36-month minimum        | O   | Supervision |
| **Telemedicine training attestation**, signed — retain, do not submit unless asked             | P   | Compliance  |
| Telemedicine training completion record                                                        | O   | Compliance  |
| Suicide prevention training certificate, 6 hours, once completed                               | O   | Compliance  |
| CE tracking log — 18 hours per renewal year                                                    | P   | Compliance  |
| **Records retention policy** — 5 years post-last-visit                                         | P   | Compliance  |
| **Professional will / records custodian agreement**, signed by the custodian                   | P   | Compliance  |




### Phase 5 — Technology and equipment (everything on the business card)

- [ ] Register domain — [Cloudflare Registrar](https://www.cloudflare.com/products/registrar/)
- [ ] Set up Microsoft 365 Business Basic (no Teams); accept the Data Protection Addendum / BAA
- [ ] Set up iPlum **Professional** with a WA number; execute and file the BAA; enable **web calling** and browser notifications (§5.4)
- [ ] Set up SimplePractice; execute and file the BAA; configure telehealth video, client portal, intake forms, and payments
- [ ] Create the Psychology Today profile; suppress the street address; point all inquiries at the SimplePractice portal
- [ ] Set up Wave bookkeeping
- [ ] Device hardening per §5.4: full-disk encryption, MFA everywhere, 5–10 min screen lock, password manager, separate browser profile
- [ ] **Confirm you are the sole administrator** on the practice computer; demote any other accounts to standard users
- [ ] Configure the macOS work account per the §5.4 table: sole admin, FileVault with a **local** recovery key (not iCloud), immediate password on wake, firewall on, guest off, sharing off, dictation off or on-device, Siri off
- [ ] Verify iCloud Drive and **Desktop & Documents sync are off**; no *consumer* cloud sync installed (OneDrive **for Business** via browser is fine — §5.5)
- [ ] Store the FileVault recovery key in the locked cabinet (§2.4)
- [ ] Configure the iPhone 12 per the §5.4 table: passcode, Show Previews **When Unlocked**, auto-lock, iCloud call-history sync **off**, iPlum app PIN, Find My, SimplePractice Photos access **Limited or None**, no third-party scanner apps
- [ ] **Ask iPlum whether messages and voicemail are stored server-side under their BAA or in local app storage** — if local, the iCloud Backup exclusion is mandatory (§5.4)
- [ ] Learn and write down the **iPlum account-lock steps** for a lost device (§5.4)
- [ ] **Family Sharing checks** (§5.4): Shared Photo Library auto-sharing off, no Shared Album receiving camera content, nobody managing this device via Screen Time
- [ ] **Face ID on, and Stolen Device Protection set to "Always"** (§5.4). Touch ID on the Mac is optional — if left off, set the Mac screen lock to 5–10 min
- [ ] **MFA on every account** via authenticator app, not SMS — Microsoft 365, SimplePractice, iPlum, Apple, BECU, Cloudflare, Wave, password manager (§5.4)
- [ ] **Set up Find My** on Mac and iPhone per §5.4, without enabling iCloud Drive; **test both from icloud.com/find**
- [ ] Capture each service's **TOTP secret string** at enrolment ("Can't scan the code?") for the recovery sheet (§5.6)
- [ ] Turn **iCloud Keychain on** for Microsoft Authenticator backup; iCloud Drive stays off (§5.4)
- [ ] Assemble the **recovery sheet** per §5.6 — FileVault key, archive and drive passphrases, master password, secret key, all MFA backup codes. Print, seal, place in the locked cabinet; second sealed copy to the records custodian
- [ ] Create the encrypted **OneDrive for Business** archive folder; disable anonymous link sharing (§5.5)
- [ ] Add the "no PHI by email" line to the email signature (§5.5)
- [ ] **Buy the locking file cabinet and the shredder** (§2.4) — before any paper exists
- [ ] **Set up the session zone** (§5.4): over-ear headphones, white-noise machine *outside* the door, door gap sealed, privacy screen filter, neutral backdrop
- [ ] **Bind HPSO coverage** with the PLLC as named insured
- [ ] Confirm every recurring charge is on the business card, not a personal one

**Documents**


| Document                                                                                                  |     | File  |
| --------------------------------------------------------------------------------------------------------- | --- | ----- |
| **BAA — SimplePractice**                                                                                  | O   | HIPAA |
| **BAA — iPlum**                                                                                           | O   | HIPAA |
| **BAA — Microsoft** (Data Protection Addendum acceptance record)                                          | O   | HIPAA |
| **BAA — Psychology Today Sessions**, if used as the video fallback                                        | O   | HIPAA |
| **BAA — BastionGPT**, only if adopted                                                                     | O   | HIPAA |
| System and vendor inventory — every place PHI can land; the input to the risk analysis                    | P   | HIPAA |
| Device and account inventory — encryption status, MFA status, who holds admin                             | P   | HIPAA |
| **Household rule**, written — no access to device, phone, mail, or room during sessions (§5.4)            | P   | HIPAA |
| FileVault recovery key, printed — stored in the locked cabinet, not iCloud                                | P   | HIPAA |
| Contingency plan — two-device continuity, and the credential-recovery material that both depend on (§5.4) | P   | HIPAA |
| Family Sharing verification result — Shared Library, Shared Albums, Screen Time (§5.4)                    | P   | HIPAA |
| **Lost-device procedure** — Find My, iPlum account lock, password changes, documentation (§5.4)           | P   | HIPAA |
| iPlum's written answer on local vs. server-side PHI storage                                               | O   | HIPAA |
| Data backup and contingency plan                                                                          | P   | HIPAA |




### Phase 6 — Before the first client

- [ ] HPSO coverage active, PLLC named
- [ ] Supervision active, declaration and agreement filed
- [ ] Telemedicine training attestation filed
- [ ] Security Risk Analysis completed and documented
- [ ] Privacy, Security, and Breach Notification policies written; Privacy/Security Officer designated
- [ ] All BAAs signed and filed in one place
- [ ] Crisis and emergency protocol written, including per-session location verification
- [ ] Professional will executed and the custodian notified
- [ ] Business phone tested end to end
- [ ] Test telehealth session run start to finish, including payment
- [ ] Locking cabinet installed; key control confirmed; custodian key instructions written (§2.4)
- [ ] Cross-cut shredder in place
- [ ] Smart speakers and voice assistants removed from the therapy room (§5.4)
- [ ] Camera framing checked — nothing identifiable behind or beside you
- [ ] Screen not visible from any walking path; privacy filter fitted (§5.4)
- [ ] Session hours set to windows when the residence is unoccupied, where possible (§5.4)
- [ ] Sound test done — someone stands outside the closed door while you speak at normal volume
- [ ] **iPlum web calling tested end to end** — inbound call, outbound call, voicemail, and text, with the headset (§5.4)
- [ ] Voicemail greeting states response time and that the line is not for emergencies
- [ ] Phone tested: iPlum inbound and outbound call, and a SimplePractice in-app scan that lands in a client file without appearing in the camera roll
- [ ] **Find My remote lock tested** on the phone, and the lost-device procedure written into the breach procedure (§5.4)
- [ ] Confirmed no third-party scanner app is installed (§5.4)
- [ ] Headphones confirmed **closed-back**; if wireless, Share Audio off, paired only to your devices, wired backup to hand (§5.4)
- [ ] **First SimplePractice export completed** — client data, reports and payment data — encrypted and uploaded to OneDrive (§5.5)
- [ ] Quarterly export reminder calendared; custodian instructions updated with the drive location and passphrase location (§4.7, §5.5)
- [ ] Household rule communicated

**Documents — practice**


| Document                                                                                                                                        |     | File       |
| ----------------------------------------------------------------------------------------------------------------------------------------------- | --- | ---------- |
| HPSO policy and declarations page **naming the PLLC**                                                                                           | O   | Insurance  |
| **Security Risk Analysis** report ([HHS/ONC SRA Tool](https://www.healthit.gov/topic/privacy-security-and-hipaa/security-risk-assessment-tool)) | P   | HIPAA      |
| **Privacy policy**                                                                                                                              | P   | HIPAA      |
| **Security policy**                                                                                                                             | P   | HIPAA      |
| **Breach Notification policy and procedure**                                                                                                    | P   | HIPAA      |
| Privacy Officer and Security Officer designation, in writing — both are you                                                                     | P   | HIPAA      |
| BAA register — an index of every signed BAA and its date                                                                                        | P   | HIPAA      |
| **Crisis and emergency protocol** — per-session location verification, local emergency contacts, escalation steps                               | P   | Compliance |
| Go-live test record — full session run start to finish including payment                                                                        | P   | Compliance |




#### Intake packet

Assemble every document below, load it into SimplePractice as an intake form, and test the full
packet on yourself as a dummy client before the first real one. Details and authorities in §4.5.

- [ ] **WA counselor disclosure statement** — must name your associate status and your supervisor ([RCW 18.19.060](https://app.leg.wa.gov/RCW/default.aspx?cite=18.19.060))
- [ ] **Informed consent for treatment** — including that cases are discussed in supervision
- [ ] **Telehealth informed consent** — modality limits, technology-failure protocol, per-session location verification, local emergency contacts, crisis plan
- [ ] **Notice of Privacy Practices** + acknowledgment of receipt ([HHS model notices](https://www.hhs.gov/hipaa/for-professionals/privacy/guidance/model-notices-privacy-practices/index.html))
- [ ] **Good Faith Estimate** — federally required for every self-pay client, in writing, before services ([45 CFR 149.610](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-B/part-149/subpart-G/section-149.610) · [CMS sample](https://www.cms.gov/files/document/nsa-sample-good-faith-estimate.pdf))
- [ ] **Fee schedule and payment policy**
- [ ] **No-show and late-cancellation policy**, with the fee stated
- [ ] **Payment method authorization** — card on file for SimplePractice payments
- [ ] **Consent for electronic communication** — what may and may not be sent by email or iPlum text
- [ ] **Client information and emergency contact form** — physical address per session, local emergency contacts, nearest emergency facility
- [ ] **Clinical intake questionnaire and history**
- [ ] **Safety / crisis plan template**
- [ ] **Release of Information (ROI) form**
- [ ] Records request procedure and retention notice — 5 years post-last-visit ([WAC 246-809-035](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-035))

---



## 8. Operating rhythm — the recurring checklist

§7 gets you open. This keeps you compliant afterwards. Almost every failure mode in this plan is a
failure to *repeat* something, not a failure to set it up.

### Every session

- [ ] Desk cleared — nothing with client information in camera frame (§2.4, §5.4)
- [ ] Client confirmed physically in Washington (§4.6)
- [ ] Headphones on and charged; wired backup within reach (§5.4)
- [ ] Screen locked and cabinet locked whenever you leave the space



### Daily

- [ ] Mail collected and handled one-touch: open → scan into SimplePractice or file → shred (§2.4)
- [ ] Anything bearing client information shredded **same day**, P-5 micro-cut (§2.4)
- [ ] Downloads folder emptied of anything client-related (§5.4)
- [ ] Any PHI that arrived by email moved into the record, then deleted from the mailbox (§5.5)



### Weekly

- [ ] Supervision log updated — date, duration, individual or group, topics (§4.2)
- [ ] Hour tracker updated against **2,500 / 1,200 / 50** (§4.2)
- [ ] Receipts and expenses entered in Wave



### Monthly

- [ ] BECU reconciled against Wave
- [ ] Every recurring charge confirmed on the **business** card, not a personal one (§7, Phase 3)
- [ ] 25–30% of net moved into the tax reserve account (§3.4)
- [ ] Caseload checked against licensure pacing — on track for 1,200 direct hours? (§6.4)



### Quarterly

- [ ] **SimplePractice export — three separate exports**: client data, reports, payment data (§5.5)
- [ ] Encrypted to `.dmg` at 256-bit AES, **opened to verify**, uploaded to OneDrive (§5.5)
- [ ] Archive date-labelled, so its purge date is calculable (see cleanup below)
- [ ] Estimated tax paid — approx. Apr 15 / Jun 15 / Sep 15 / Jan 15 (§3.4)
- [ ] OS and app updates applied on both devices (§5.4)
- [ ] Open items reviewed (§9)



### Annually


| Renewal                                              | When                        | Cost     |
| ---------------------------------------------------- | --------------------------- | -------- |
| WA SOS Annual Report                                 | Formation anniversary month | $70      |
| LMHCA renewal + **18 CE hours**                      | Credential anniversary      | $25 + CE |
| Redmond business license                             | City cycle                  | $160     |
| HPSO — **confirm the PLLC is still a named insured** | Policy anniversary          | ~$250    |
| Cloudflare domain                                    | Registration anniversary    | ~$12     |


- [ ] **Recovery sheet checked (§5.6)** — legible, current, unused codes still work, passphrase opens the latest `.dmg`
- [ ] **Find My remote lock tested** on both devices (§5.4)
- [ ] **Security Risk Analysis** reviewed and updated (§5.1)
- [ ] Every **BAA** confirmed still in force; BAA register updated (§5.1)
- [ ] **Professional will**: custodian still willing, details current, envelope location unchanged (§4.7)
- [ ] **Family Sharing** settings re-verified — Shared Photo Library, Shared Albums, Screen Time (§5.4)
- [ ] Fee schedule and no-show policy reviewed (§4.5)
- [ ] Cabinet contents match what you believe is in it
- [ ] **Annual client retention review** — delete clients last seen over six years ago, after the pre-flight checks (§8, cleanup)
- [ ] **Safe deposit box folder checked** against its inventory; recovery sheet copy still current (§5.6)



### Every few years


| Item                                                   | Frequency                                      |
| ------------------------------------------------------ | ---------------------------------------------- |
| Suicide prevention training refresh                    | Every 6 years (§4.3)                           |
| LMHCA renewal cap — track how many of the six are used | Ongoing (§4.1)                                 |
| iPhone 12 replacement                                  | ~2029, when security patches end (§5.4)        |
| Full LMHC application                                  | At 2,500 / 1,200 / 50 **and** 36 months (§4.2) |




### Data cleanup and erasure

**Ongoing**

- Paper with client information — **shredded same day**, P-5 micro-cut (§2.4)
- Client PHI arriving by email — into the record, then deleted from the mailbox **including Deleted Items** (§5.5)
- Downloads folder emptied regularly (§5.4)
- Screenshots of client information — never taken (§5.4)

**Scheduled purge — measured per client, never per archive**

Retention runs **five years from each client's last visit**
([WAC 246-809-035](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-035)) — not from the age of a
file. A client you are still seeing has a record with nothing expired in it, because **the clock has
not started**. A client of six years has zero expired content.

So **archives cannot be purged by age.** A 2026 export opened in 2032 still contains active clients,
clients who terminated last month, and clients long gone — all mixed together. The unit of retention
is the client record; the archive is only a snapshot.

**Archives: keep current and previous, overwrite the rest.** Each quarterly export supersedes the
last, because SimplePractice's live data already holds every client, active and terminated. Two
generations covers a corrupt file. There is no chain of dated snapshots to manage, and therefore no
archive purge to schedule at all.

**Clients: review annually, delete at six years.**

- [ ] Once a year — tie it to the SOS annual report month, so there is one date to remember — list every client whose **last visit was more than six years ago**. Six rather than five buys a year of buffer against date errors, and matches the six-year HIPAA documentation retention you already keep.
- [ ] Run the pre-flight below on each one **before deleting anything**.
- [ ] Delete, then **log it**: client identifier, last-visit date, destruction date, method. That log is what demonstrates you both retained and destroyed correctly.
- [ ] Refresh the archive afterwards so the deletion propagates.

**Pre-flight — all four, before a single record goes**


| Check                                                     | Why                                                                                                                                           |
| --------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| **Was the client a minor at the last visit?**             | Their clock is longer and **not yet confirmed** (§9). Until DOH answers, **delete no record of anyone seen as a minor**                       |
| Any open complaint, subpoena, board matter or litigation? | Preservation overrides retention. Destroying it is spoliation                                                                                 |
| **Financial records extracted first?**                    | Tax records run **seven years** (§10.8) — longer than the clinical five. Deleting a client in SimplePractice may take billing history with it |
| Is the deletion reversible?                               | Assume it is not. Verify the list before you act                                                                                              |


> **If the practice is adults-only, state that explicitly** in the intake policy. The minors clock
> then never applies, the §9 open item closes, and this annual review becomes a ten-minute job.

**Equipment retirement**

- [ ] iPhone or Mac: sign out of the Apple Account, then **Erase All Content and Settings** (§5.4)
- [ ] External drive: it is APFS (Encrypted), so erasing destroys the keys — cryptographic erase suffices
- [ ] Log the date and method. Device disposal is the same media-controls duty as shredding paper (§2.4)

---



## 9. Open items


| Item                                                                 | Action                                                                                                                                                                                                           |
| -------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Supervisor identity and hourly rate                                  | Contract a supervisor; replace the $278/mo planning figure ($200/hr assumed) with the real one                                                                                                                   |
| Direct client contact hours under CACREP credit                      | Confirm with DOH whether the 1,200 figure is reduced, and whether the 36-month minimum shortens (§4.2)                                                                                                           |
| Starter "other documents" limitation                                 | Confirm the disclosure statement, telehealth consent, and ROI work as Starter intake forms (§5.2)                                                                                                                |
| iPlum local vs. server-side PHI storage                              | Ask iPlum; if local, the iCloud Backup exclusion becomes mandatory (§5.4)                                                                                                                                        |
| Records retention on closure                                         | **Resolved** — see §5.5 and §10.1; SimplePractice deletes within 64 days of cancellation                                                                                                                         |
| **Minors retention period**                                          | **Blocking for the annual purge (§8).** Confirm with DOH how long records for clients seen as minors must be kept. Until answered, delete none of them — or declare the practice adults-only and close this item |
| HIPAA eFax, if coordinating with prescribers                         | SimplePractice has none; ~$10–20/mo third party, or check iPlum (§5.2)                                                                                                                                           |
| HPSO quote                                                           | Get a quote with the PLLC as named insured; $250/yr assumed                                                                                                                                                      |
| Redmond FTE treatment and any small-business threshold               | Call 425-556-2193                                                                                                                                                                                                |
| VirtualPostMail Business quote, if a mailing address is wanted later | Business-tier pricing is unpublished; also ask whether a Washington location exists (§2.5)                                                                                                                       |
| Paneling vs. strictly private pay                                    | Decide before setting the fee schedule (§6.1)                                                                                                                                                                    |
| CPA engagement                                                       | Engage before the first tax year closes                                                                                                                                                                          |


**Budgeting rule.** Carry every required-but-unquoted cost as a range with a stated assumption, and
pair it with the action that resolves it. Nothing required is left out of the total.

---



## 10. Closing the practice

Most of this is not optional, and the clinical obligations bind before the paperwork does. Read it
once now rather than for the first time on the way out — and note that **this plan may have to be
executed by someone other than you** (§10.9), which is why it lives in the document rather than in
your head.

### 10.1 The retention archive — the artifact that must already exist

**Encrypted external drive, $50–100 — bought at shutdown.** During operation the archive lives in
OneDrive for Business (§5.5); the drive exists to hold the five-year retention copy **after** the
Microsoft subscription is closed. Buy it as the first step of winding down, not before.

> If closure happens without you, your custodian buys it — which is why their instructions carry the
> **deadline** for exporting before the subscription lapses (§10.9).


| Spec       | Detail                                                                                   |
| ---------- | ---------------------------------------------------------------------------------------- |
| Encryption | **APFS (Encrypted)**, set at format time. Strong passphrase                              |
| Passphrase | Password manager **and** printed in the locked cabinet, separate from the drive          |
| Contents   | Every SimplePractice export: client data, reports, payment data — they export separately |
| Refresh    | Quarterly, or annually at absolute minimum (§5.5)                                        |
| Verify     | Open the archive after each refresh. An unreadable backup is not a backup                |




### 10.2 Order of operations — never cancel before you export

**SimplePractice deletes cancelled account data within 64 days, unrecoverably.** The order is not
negotiable:

1. **Export everything** — client data, reports, and payment data are three separate exports.
2. **Encrypt, copy to both** the drive and OneDrive for Business (§5.5).
3. **Open and verify** the archive reads correctly.
4. **Only then cancel.**



### 10.3 Clients first — 30 to 60 days' notice

Abrupt closure is client abandonment: an ethics violation and a licensing complaint waiting to
happen. It is also the part with the least room to improvise.

- **Written notice to every active client**, 30–60 days ahead.
- **Per client**: plan a proper termination, or refer and transfer. Offer **two or three** concrete
referrals, not a directory link.
- **Tell them how to request records**, and for how long records will be available (§10.5).
- **Maintain crisis coverage** through the wind-down — you are still their clinician until you are not.
- **Document the final session** and the termination or transfer for each client.



### 10.4 Supervision — get the hours signed off before anything else

If you close mid-associate-period, your supervisor's **verification of supervised hours** is what the
eventual LMHC application depends on. Get it signed, dated and filed **before the supervision
relationship ends**. A supervisor who later moves, retires, or becomes unreachable turns a formality
into a lost licensure pathway. This is the single most irreversible item on the page.

### 10.5 Records — retention and, crucially, reachability

- **Five years after last visit** ([WAC 246-809-035](https://app.leg.wa.gov/wac/default.aspx?cite=246-809-035)).
Longer for minors — confirm with DOH (§9).
- **Keep one contact route alive for those five years.** This is the step people miss: close the
mailbox, the phone line and the email, and clients have a legal right to records they cannot
exercise. Decide which channel survives, and **state it in the closure notice**.
- **Update the custodian instructions** (§4.7) with the drive location, the passphrase location, and
the surviving contact route.
- **Business and tax records: keep seven years** — the IRS and DOR can audit a closed entity.



### 10.6 Insurance — the expensive thing to get wrong

**Find out now whether your HPSO policy is occurrence or claims-made.** HPSO offers both, and the
difference decides whether closing costs you nothing or several hundred dollars:


| Policy type     | On closure                                                                                                                                                                                      |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Occurrence**  | Incidents during the policy period stay covered no matter when the claim arrives. **No tail needed.**                                                                                           |
| **Claims-made** | Only claims filed while the policy is active are covered. You must buy **tail coverage** (extended reporting period), typically **150–300% of the annual premium** — $375–750 on a $250 policy. |


**Ask at purchase, not at closure** — it is now a Phase 1 question (§7). Claims in this field can
arrive years after the work. Never let coverage lapse before tail is in place, if tail is needed.

### 10.7 Vendors — order matters, and BAAs have a termination duty

Terminating a BAA obliges the business associate to **return or destroy PHI**
([45 CFR 164.504(e)(2)(ii)(J)](https://www.ecfr.gov/current/title-45/subtitle-A/subchapter-C/part-164/subpart-E/section-164.504)).
Get your export first, then let them delete.

- Cancel **Psychology Today**, then **iPlum**, then **SimplePractice last** — it holds the records.
- **Keep Microsoft 365 running** while OneDrive still holds the archive, or move the archive to the
drive first and then close it.
- Request written confirmation of deletion where a vendor offers it; file it with the BAAs.



### 10.8 Entity, tax and licensing


| Step                                   | Detail                                                                                                                                                                                                               |
| -------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Certificate of Dissolution**         | **No filing fee.** 1–2 weeks to process; revocable within 120 days ([WA SOS form](https://www.sos.wa.gov/sites/default/files/2023-10/LLC_&_PLLC_Dissolution.pdf))                                                    |
| **Close the DOR account — separately** | **Dissolving with the Secretary of State does not notify DOR.** File a Business Change Form to close the B&O account, then a **final excise return by the 25th of the following month** ([DOR](https://dor.wa.gov/)) |
| Redmond endorsement                    | Close it with the city                                                                                                                                                                                               |
| Federal tax                            | Final return / Schedule C; **cancel the EIN in writing to the IRS** ([IRS — closing a business](https://www.irs.gov/businesses/small-businesses-self-employed/closing-a-business))                                   |
| Banking                                | Close accounts **after** every final expense has cleared                                                                                                                                                             |
| Registered agent                       | Ends with the entity — nothing to cancel, since it is you (§2.3)                                                                                                                                                     |




### 10.9 If this happens without you

Death or incapacity executes this plan on your behalf, so your records custodian (§4.7) needs enough
to run §10.1 through §10.5 without you. Their packet must contain:

- **Where the encrypted drive is, and where its passphrase is** — separately stored
- Credentials, or the location of the password manager and its recovery material
- **A deadline, not just a location.** Both clocks start when the card stops clearing, not when
someone notices: **SimplePractice deletes at 64 days**, and **Microsoft 365 — which holds the
archive — at roughly 120**. The custodian needs funds or a means to keep both paid, and the
instruction to **buy the drive and write the archive to it within 60 days**
- A client notification template and the referral list
- The surviving contact route for records requests, and who answers it

