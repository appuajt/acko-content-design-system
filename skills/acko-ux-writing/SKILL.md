---
name: acko-ux-writing
description: ACKO's UX writing rules and voice for in-product copy — CTAs, headers, body copy, empty/error/success/loading states, alerts, modals, helper text, plus grammar, casing, numbers, readability, and inclusive language. Use whenever writing, reviewing, or rewriting any ACKO product UI copy (app screens, flows, forms, buttons, labels, microcopy). Triggers on: button text, headings, error messages, empty states, loading copy, tooltips, form labels, confirmation screens, claim/policy/payment copy, or any request to "make this sound like ACKO".
---

# ACKO UX Writing

How ACKO writes in-product copy. We're not a traditional insurer that talks like a policy — we write for the human on the other end. No intimidating jargon, no frustrating processes. We're a helping hand.

When copy pulls in different directions, this priority order decides what wins:

**Trust > clarity > usefulness > warmth > cleverness**

---

## Voice — how we always sound

Voice is constant across every screen. ACKO sounds **Assuring, Plainspoken, Insightful, and Transparent**.

| Pillar | What it means | In practice |
|---|---|---|
| **Assuring** | Clear, steady, in control — especially when something goes wrong | Remove uncertainty step by step: what happened, what we're doing, what the user does, what's next |
| **Plainspoken** | Insurance shouldn't need a translator | Say what's covered, what's not, what it costs, what to do next — easy to find, hard to misunderstand |
| **Insightful** | Be the most informed person in the room, in the user's service | Tell users what they didn't know they needed to know. Help them choose well — don't push |
| **Transparent** | No sugarcoating | Give exclusions the same space as coverage. If it could surprise someone at claim time, say it upfront |

```
Use:   Your claim has been submitted. We'll review the details and update you by tomorrow.
Avoid: Woohoo! Your claim journey has started.

Use:   You'll pay ₹2,000 because your policy has a deductible. ACKO will cover the remaining approved amount.
Avoid: Applicable deductible shall be borne by the insured as stated in the policy.

Use:   ₹4,500 is not covered because consumables are not included in your policy.
Avoid: Certain charges may be payable by you.
```

## Tone — shifts with the moment

Tone reflects the emotional weight of the moment. Match the user's state:

- **Accident / mid-crisis** → calm, immediate, give the next step. Don't be insightful or chatty — they need to act, not learn.
- **Hospitalisation / claim** → supportive, composed. No exclamation marks, no emojis, no over-celebration.
- **Purchase / browsing** → clear, insightful. Don't over-reassure — it plants doubt that wasn't there.
- **Rejection / bad news** → direct and fair. State the fact, the cause, the option. No build-up.

---

## The six UX writing principles (apply in order)

A filter, not a checklist. Run every piece of copy through these — in sequence.

1. **Check if copy is required.** If a design solution (icon, layout, hierarchy) can do the job, don't write. Copy that explains a bad design is still bad design.
2. **Be very clear.** Complete sentences. Explain jargon the moment you use it. If a sentence can be read two ways, it will be read the wrong way. Clarity beats brevity when they conflict.
3. **Be concise.** Right level of detail, no more. No filler, no throat-clearing, no restating. Pick the shorter word when both work.
4. **Be useful.** Every line moves the user toward their goal. Explain status, suggest the next action. If something breaks, say what to do — not just what happened.
5. **Be conversational.** Personal pronouns (you, your, we, our). Simple syntax, active voice, short sentences. Write like a knowledgeable person explaining to a friend.
6. **Be the brand.** Positive associations only — preparedness, transparency, dependability. Not excitement, fear, or pressure. Ask: does this sound like ACKO, or like any insurance company?

```
Be useful:  Payment failed. Check your card details and try again, or use a different payment method.
   not →    Payment failed.

Be the brand:  Your documents are verified. You're covered from today.
      not →    Congratulations! You're now protected against life's uncertainties! 🎉
```

---

## Universal rules

**We always:**
- Lead with the user's outcome — tell them what it means for *them* first
- Write in second person ("you", "your"). Avoid "customer", "policyholder", "insured", "claimant" unless legally required
- Prefer active voice — "We're reviewing your claim", not "Your claim is being reviewed"
- Give the next step — every message answers "What should I do now?"
- Use exactness — amounts, dates, time windows, documents, claim stages, who pays
- Explain why — especially when asking for documents, permissions, payment, or health details
- Make the catch visible — waiting periods, exclusions, deductibles, co-pay, limits
- Match the user's emotional state

**We never:**
- Overpromise — no "guaranteed approval", "instant settlement", "100% covered" unless factually true
- Hide behind T&Cs — explain the actual condition, not "subject to terms and conditions"
- Make insurance sound like a party
- Blame the user — "These details don't match our records", not "You entered incorrect details"
- Use vague service language — "We're checking your documents. This takes up to 2 hours", not "We're processing your request"
- Hard-sell or use fake urgency
- Choose cleverness over clarity in claims, payments, exclusions, emergencies, or failures

---

## Component patterns

### CTAs
The surrounding copy carries the message; the CTA just confirms the action.

- **User's point of view** — "See my recommended plan", not "Access your plan recommendations". First-person works well in high-stakes moments.
- **Short** — 6 words max, 2–3 ideal. "Renew now", "Download policy", "Add vehicle".
- **Sentence case, always** — exception: ACKO is always caps.
- **No punctuation** — apostrophes are the only exception. ("Let's get started" ✓, "Get started!" ✗)
- **Numbers for speed/effort** — "Renew in 2 mins" beats "Renew quickly". Only claim a time the flow actually delivers.

Verb conventions (don't swap freely): **View** (already theirs) · **Check** (a lookup) · **Explore** (intro a product) · **Download** (a document) · **Add** (something new) · **Learn more / Know more** (don't mix on one screen).

Fixed CTAs: explaining → **Got it** · error/end screen → **Okay** · multi-step → **Continue** · destructive → name what's lost ("Yes, cancel my policy", not "Confirm").

### Headers and subheaders
The header carries the full weight of the screen — write it to stand alone.

- Sentence case. No full stop (exception: two punchy short sentences for effect).
- Under 2 lines (3 is the hard limit). If longer, two ideas are fighting — split them.
- Must make complete sense without the subtext. If meaning only works with subtext, rewrite the header.
- No user names or variables in headers — "Your policy renewal is due", not "Hi Priya, your policy renewal is due".
- Use subtext sparingly. If info is critical, it belongs in the header. If no one would miss it, cut it.

### Body copy
- One message per sentence. Say one thing, stop, start a new sentence.
- Full sentences — subject, verb, outcome. Not fragments.
- Active voice, second person. Never "policyholder"/"insured" unless legally required.
- Bold key info — amounts, dates, deadlines, document names. Never bold decoratively.
- Lead with the user's outcome, not ACKO's process.

```
Use:   Your claim is approved. ₹12,000 will be transferred to your bank account.
Avoid: We have completed our review process and are pleased to inform you that your claim has been approved.
```

### Empty states
Not errors — don't apologise for them.
- State what's absent, not what went wrong. "No policies added yet. Add a vehicle to get started." — not "Oops! Nothing to see here."
- First-time states need more context (explain the section + invite action). Cleared states need less ("You're all caught up").
- Give a next step only where one genuinely exists — don't force a CTA or upsell on a passive state.

### Error states
Errors are already stressful — reduce the stress, don't add to it.
- Don't blame the user. "We couldn't verify your PAN. Please upload a clearer photo." — not "Your photo is too blurry."
- No "Oops", no exclamation marks — they make errors feel more alarming. Stay calm and direct.
- Always give a recovery path. An error with no next step strands the user.
- Deliver bad news plainly — no softening preamble.
- Use "sorry" **only** when it's ACKO's fault — and never follow "sorry" with "but" (it cancels the apology).

### Success states
Positive but composed — not a celebration.
- Confirm what happened, then give the next step. "Payment successful. Your policy is now active."
- Claims/emergencies stay composed — no "🎉", no "Great news!".
- Include specific timelines — "₹12,000 will be credited within 3–5 business days", not "shortly".

### Alert and nudge cards
Formula: **trigger + consequence + action**. Helpful, not alarmist.
- "Your PUC expires in 3 days. Renew it now to avoid a fine." — not "Your PUC is about to expire soon. Take action immediately!"
- Exact numbers, not approximations — "3 days" creates a deadline; "soon" creates vague unease.
- State risk plainly and give agency. No "Warning! You're at risk of huge fines!"

### Loading states
- Name what's happening — "We're checking your documents. This usually takes up to 2 hours." — not "Processing your request…"
- Give a time estimate for anything over a few seconds.
- Use "please" when asking the user to wait ("Please wait while we look for an agent") — not as filler elsewhere.

### Modals and bottom sheets
- Bottom sheets explain or confirm — they don't host primary flows or full forms.
- Keep under half the screen. If content-heavy, break into header + bullets + info cards.
- Informational sheets always use **Got it** (not "Okay"/"Close").
- Decision sheets: make both options clear; the secondary CTA names what's kept ("Keep my policy"), not "Cancel".

### Disclosure and helper text
- Helper text answers the field question in one short sentence, front-loaded ("Enter your 10-digit mobile number").
- Placeholder text ≠ helper text — placeholders vanish on typing, so use them only for examples of valid input, never for rules.
- Make the catch visible — exclusions, waiting periods, deductibles stated where the user sees them, not in footnotes ("*T&Cs apply").
- Always explain why when asking for sensitive info ("We need your PAN to process the claim payout to your account").

---

## Styles and standards

- **Casing** — sentence case everywhere. Title case only for proper nouns (product names, plans, ACKO).
- **Numbers** — always numerals. "3 documents needed", not "Three".
- **Currency** — ₹, no space before the number. Indian formats: lakh, crore (not million/billion). "₹2,000 · ₹5 lakh · ₹1 crore". Avoid "Rs.", "INR", "₹ 2,000".
- **Lakh and crore** — always lowercase when spelled out; never pluralise ("₹5 lakh", not "₹5 lakhs"). Contractions in tight UI use uppercase **L** and **Cr** ("₹5L", "₹1Cr"). Avoid lowercase `l` (reads as 1) and `cr` (reads as "credit").
- **Percentages** — always %. "20% co-pay", not "twenty percent".
- **Dates** — "24 Jun, 2026". Add the weekday when useful. No ordinals (no "24th").
- **Time** — "9:00 AM", ranges "9:00 AM – 7:00 PM". AM/PM in caps with a space.
- **Full stops** — only with 2+ sentences. None in one-line headings, buttons, labels.
- **Exclamation marks** — sparingly, only for positive low-stakes moments. Never in claims, health, accidents, payments, errors, rejections.
- **Ellipses** — loading states only. Never to trail off or build suspense.
- **Emojis** — low-risk marketing channels only (push, WhatsApp nudges, promo email). Never in claims, health, accident, payment, or emergency contexts.
- **Ampersands** — avoid unless space is extremely tight or the official name uses "&".
- **Brackets** — only to clarify abbreviations or add essential data ("No Claim Bonus (NCB)", "₹8,400 (including GST)"). Not for asides.
- **Bullets** — one idea per bullet, start with a capital. Full stop only if it's a complete sentence.

## Grammar

- Write directly to the reader — "you"/"your". Never "customer"/"policyholder"/"insured"/"claimant" unless legally required.
- ACKO is "we"/"our". Don't say "ACKO will…" alongside "you" — it creates distance.
- Use contractions ("We'll", "You don't") — they sound human. Skip only in legal/regulatory copy.
- Active voice. Test: add "by zombies" after the verb — if it still works, it's passive. *Exception:* status/progress screens describe the state of the user's item ("Your claim is under review") — that's a state description, not passive voice. "Your claim is being reviewed" hides who's responsible.
- British English spelling — cancelled, behaviour, authorise, organise, colour, licence (noun).
- "Please" purposefully — to soften, when asking someone to wait, or for extra effort. Not as politeness filler.
- Apologise only when it's our fault, and never follow "sorry" with "but".
- Lead with the bad news — state fact, cause, option. No softening preamble.

---

## Words and phrases

- **Introduce terms before abbreviating** — full term + abbreviation in brackets on first mention ("No Claim Bonus (NCB)"), then the abbreviation alone.
- **Stay abbreviated** (common enough): PAN, GST, UPI, OTP, SMS, PDF, FASTag, PUC, RC.
- **Always explain in context** (unfamiliar to most): deductible, co-pay, waiting period, exclusion, consumables, IDV, NCB, zero depreciation, network hospital, cashless claim, reimbursement claim, PED, room rent limit, sum insured, super top-up.
- **Compliance** — avoid superlatives and unverifiable claims ("We are the best/most trusted/fastest"). Reference accreditations only in the exact form awarded.

| Term | Plain-language explanation |
|---|---|
| Deductible | The amount you pay before ACKO covers the rest |
| Co-pay | The percentage of the claim you share |
| Waiting period | The time before a condition is covered |
| Sum insured | The maximum the policy will pay out |
| IDV | The current market value of the vehicle |
| NCB | A discount earned for not making claims |
| Cashless claim | Treatment without upfront payment at network hospitals |
| PED | A health condition that existed before the policy started |

---

## Readability

- **Shorter sentences** — one idea each. Don't chain with "and"/"which"/"that". Past 20 words, split. Say what matters first.
- **Shorter, simpler words** — use the plain word when it means the same. Avoid nominalisations ("make a decision" → "decide"). Never use double negatives ("not ineligible").
- **Aim for grade 6–7** reading level (check with Hemingway App). Anything above grade 10 needs a rewrite. For legal disclosures, add a plain-language summary above the fine print.

Common swaps: utilise → use · initiate → start · assist → help · provide → give · obtain → get · terminate → end · subsequent to → after · in the event that → if · prior to → before · with respect to → about.

## Inclusive language

- **Include diversity** — products are for everyone regardless of age, gender, religion, income, occupation, health, or region. "Plans for every Indian family", not "Made for young professionals".
- **Gender neutral** — keep third parties (nominee, doctor, agent) neutral. Restructure to avoid pronouns; otherwise "they/them/their". "If your doctor recommends surgery, they'll need to certify it."
- **Don't assume family structure** — "the people who depend on you", "your family", "your loved ones". Not "Protect your wife and kids."

---

## Quick self-check before shipping any string

1. Could a design solution replace this copy entirely?
2. Does it lead with the user's outcome, in "you" + active voice?
3. Does it answer "What do I do now?"
4. Are amounts, dates, and who-pays exact?
5. Is the catch (exclusion, deductible, waiting period) visible, not buried?
6. Does the tone match the user's emotional state?
7. Sentence case, no stray full stop or exclamation mark, British spelling?
8. Would this read at a grade 6–7 level?
