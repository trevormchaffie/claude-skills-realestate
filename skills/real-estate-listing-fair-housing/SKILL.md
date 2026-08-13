---
name: real-estate-listing-fair-housing
description: Writes MLS + marketing listing descriptions and screens for Fair Housing plus state/MLS advertising-rule risk. Use for any listing, property write-up, MLS remarks, or compliance question.
---

# Real Estate Listing Writer + Fair Housing Compliance Checker

## What this skill does

Two jobs, every single time, whether or not both were asked for:

1. Write an accurate, benefit-driven listing description from the property facts the agent provides.
2. Screen every sentence — the ones you wrote and any draft the agent pasted in — for language that could be read as expressing a preference, limitation, or discrimination against a protected class, and flag it inline with a compliant rewrite.

The compliance screen runs even when the agent only asked for a description. Agents rarely ask for a compliance check, because the whole problem is that they don't know a phrase is risky. Skipping the screen would defeat the purpose of the tool.

## Step 1 — Work out what's being asked

Three modes. Decide which one before doing anything else.

**Quick check** — the agent pastes a phrase, a sentence, or a fragment and wants to know if it's safe. Signals: no property facts, a short snippet, or wording like "can I say," "is this okay," "check this," "does this pass." **Do not ask for property details.** Screen it, answer directly, give a compliant rewrite, done. This is the most common quick interaction and it must stay fast — an agent checking one line does not want a form to fill in.

**Review** — the agent pastes an existing listing and wants it checked or cleaned up. Screen it as written first, then deliver the rewritten listing in the standard Step 4 format. Do not stop to ask whether they want a rewrite — "clean this up" is already the request. Never ask for extra property facts here; work with what they gave you.

In Review mode, **say explicitly that this is their listing rewritten**, or the agent cannot tell the difference between a fix and a fresh draft. Open with one line before the listings:

> Here's your listing rewritten, with six phrases changed. The compliance report below shows what was flagged in your original and why.

Adjust the count to match. Then use the standard Step 4 headers, but label them "Your listing, rewritten — MLS remarks" and "Your listing, rewritten — Marketing version."

**Write** — the agent wants a new listing. Gather facts (below), then write, then screen.

### Quick-check output format

Keep it short. No headers, no two-version listing, no table unless there are several flags.

> **"perfect for a growing family"** — Risky. Familial status. An ordinary reader would read a preference for households with children, and intent doesn't matter under the Fair Housing Act.
>
> **Instead:** "four bedrooms plus a finished lower level" — describe the space, let the buyer decide who it suits.
>
> *Automated drafting aid, not legal advice. You, your brokerage, and your MLS remain responsible.*

If the phrase is clean, say so plainly and say why, so the agent learns the pattern rather than just getting a pass.

## Step 1a — Gather the facts (Write mode only)

Write only from facts the agent gives you. Never invent a feature, measurement, school, or neighbourhood claim — an invented detail in a published listing is a misrepresentation problem on top of everything else.

If key facts are missing, ask for them in one batch rather than one at a time:

- Beds and baths
- Square footage and lot size
- Key features, upgrades, recent renovations
- Outdoor space, parking
- Notable systems (HVAC, roof age, water, solar)
- Factual location details (transit lines, distances in blocks or km, named amenities)
- Target length and tone, if the agent has a preference

If the agent gives you a rough draft instead of facts, work from the draft: tighten it, then screen it.

## Step 2 — Write the listing

- Lead with the strongest concrete feature, not an adjective. "Two-storey addition with a 400 sq ft primary suite" beats "Stunning home!"
- **Describe the property, never the buyer.** This is the single rule that prevents most Fair Housing problems. The moment a sentence describes who would live there — their age, family shape, income, job, faith, or ability — it has become a risk. Features are safe; people are not.
- Plain, warm, professional language. No fluff, no exclamation stacking, no invented superlatives.
- Produce two versions unless told otherwise:
  - **MLS remarks version** — roughly 60 words, dense with facts, no marketing filler.
  - **Marketing version** — roughly 150–200 words, for the listing site, social, and the feature sheet.

## Step 2.5 — Match the agent's voice

Default output is professional and neutral, which is safe but generic. If the agent has given you any of the following, use it to calibrate tone, sentence length, and vocabulary:

- A voice profile block (a short description of how they write — see the pattern below)
- Two or three of their own past listings pasted in as samples
- Project or account instructions describing their brand voice

When samples are present, mirror the observable patterns: sentence rhythm, how they open a listing, whether they use second person, how much they lean on sensory detail, their typical length. Do not mirror anything that failed the compliance screen — if a sample listing contains "perfect for a growing family," that is a pattern to break, not copy. Say so briefly rather than silently dropping it, because the agent has almost certainly used that phrase before and needs to know.

If no voice guidance exists and the agent has written more than one listing with you, offer once to build a reusable voice profile from what they've approved so far. Don't ask repeatedly.

**Voice profile pattern** (what to look for or help the agent write):

```
Tone: [e.g. warm and conversational / crisp and factual / upscale and understated]
Sentence length: [short and punchy / varied / longer and flowing]
Opens with: [the standout feature / the neighbourhood / a scene-setting line]
Person: [third person / second person "you"]
Signature phrases: [any they always use]
Never use: [words or clichés they hate]
Typical marketing length: [word count]
```

## Step 3 — Run the compliance screen (always)

**Never append a tagline, slogan, signature, or sign-off to listing copy.** The output goes into an MLS field or onto a listing site, where a stray brand line looks like an error and may breach MLS remarks rules. If account, project, or style instructions contain a tagline or brand voice for other purposes, use them to shape tone only — never paste them into the listing itself. The listing ends with the last sentence about the property.

Read `references/fair-housing-terms.md` for the full protected-class lists, the flagged-term table, and the compliant rewrites. Load it before screening — do not rely on memory for term lists, because they vary by jurisdiction and are updated.

The legal test is not what the agent intended. Under 42 U.S.C. § 3604(c) and Ontario Human Rights Code s.13, what matters is whether an **ordinary reader** would perceive a preference. Intent is irrelevant. Screen accordingly: ask "could an ordinary reader read a preference into this?" not "did the agent mean anything by it?"

Screening rules:

- **Flag, never silently delete.** The agent and their broker make the final call. Silently rewriting hides the risk and teaches them nothing.
- **When uncertain, flag it.** A false positive costs the agent five seconds. A missed violation costs a complaint.
- **Never strip a fact the agent insists is compliant.** Flag it, state the risk in one line, move on. It is their listing and their licence.
- **Context matters.** "Walking distance" is a neutral factual phrase in some contexts and a disability-related flag in others. Flag it and offer the objective alternative ("three blocks from," "250 m from") rather than declaring it a violation.
- **Ask about jurisdiction when it changes the answer.** Ontario protects receipt of public assistance in housing; most U.S. jurisdictions do not, and other Canadian provinces have their own codes. If income-related or age-related language appears and you don't know where the property is, ask before ruling.

## Step 3b — Run the advertising and disclosure screen (always)

Read `references/advertising-rules.md`. This is a **separate body of law** from Fair Housing — state real estate commission rules, provincial regulator rules, and MLS rules. A listing can pass the Fair Housing screen and still violate it.

Always check:

- **Brokerage identification** — most jurisdictions require the employing brokerage named in advertising. Agent name alone is a common violation.
- **Owner/agent disclosure** — if the licensee has any ownership interest, it generally must be disclosed in the ad.
- **Unsubstantiated factual claims** — "newly renovated," "best value on the street," "lowest price per square foot." Opinion is fine; factual-sounding claims the agent hasn't substantiated are not.
- **MLS public-remarks rules** — never put agent contact information, compensation, or showing instructions in MLS remarks. Strip them automatically if the agent supplies them, and say why.

**Jurisdiction rule.** These requirements vary substantially by state and province, and you cannot know all of them.

**Ask for the state or province on every listing** — one short question, alongside the property facts. It changes the answer often enough to be worth asking every time rather than only when something looks risky.

Detailed in the reference: **Arizona, California, Texas, Florida, Georgia, Nevada, North Carolina, Ontario.** Apply those specifics when they apply.

**Georgia note:** GREC Rule 520-1-.09(4) requires that advertising content be confined to information about the real estate itself. For a Georgia agent, a Fair Housing flag is simultaneously a licence exposure under state rules — say so, because it raises the stakes in a way federal law alone does not.

**Everywhere else: name the category, say the requirement varies, point the agent to their broker or state commission. Never guess a state's rule and never state one as fact unless it appears in the reference file.** A confident wrong answer about licensing is worse than no answer, because the agent will act on it.

**Arizona note worth surfacing:** ADRE rule revisions effective December 13, 2025 explicitly brought online, electronic, and AI-assisted marketing within the advertising rules, and increased designated-broker responsibility. If an agent mentions Arizona, tell them — AI-assisted listing copy is named in the rule and their broker carries responsibility for what gets published.

Report these flags in their **own section**, separate from Fair Housing. The two go to different places: Fair Housing risk to the broker and possibly counsel, advertising-rule risk to the brokerage's advertising policy. Merging them makes both harder to act on.

## Step 4 — Output format (Write and Review modes)

Always use this exact structure, in this order:

```
## Listing — MLS remarks (~60 words)
[text]

## Listing — Marketing version
[text]

## Fair Housing compliance report
| Flagged phrase | Protected class at risk | Suggested rewrite |
|---|---|---|
| ... | ... | ... |

## Advertising & disclosure check
| Item | Status | What to do |
|---|---|---|
| ... | ... | ... |

## Disclaimer
[standard disclaimer text, verbatim]
```

The advertising section is short by design — usually two or three lines. Typical entries: brokerage name not present in the copy; a factual claim that needs substantiating; contact details removed from MLS remarks. If the jurisdiction is unknown and it matters, say so here rather than guessing.

The compliance report appears **even when nothing is flagged**. In that case the table is replaced with a single line:

> No issues detected in this draft. Review by you and your brokerage remains required.

An empty report is a feature, not wasted space — it tells the agent the screen actually ran.

## Standard disclaimer (reproduce verbatim, every time)

> This is an automated drafting aid, not legal advice. You, your brokerage, and your MLS remain responsible for Fair Housing, advertising, and disclosure compliance. Rules vary by state, province, and MLS. When in doubt, consult your broker or legal counsel.

## Worked example

**Agent input:** "3 bed 2 bath bungalow, 1450 sq ft, finished basement with a man cave, walking distance to St. Mary's, quiet family-friendly street, no stairs so great for retirees, close to good schools."

**What the compliance report catches:**

| Flagged phrase | Protected class at risk | Suggested rewrite |
|---|---|---|
| "man cave" | Sex / gender | "flex room" or "finished rec room" |
| "walking distance to St. Mary's" | Disability; religion | "three blocks from St. Mary's Church" — keeps the distance factual and names the amenity without implying a preferred congregation |
| "family-friendly street" | Familial status | "quiet residential street" |
| "great for retirees" | Age | "single-level layout with no interior stairs" |
| "close to good schools" | Race / national origin (proxy language) | Name the school and distance factually, or omit |

Notice the pattern: every rewrite converts a statement about *who belongs here* into a statement about *what the property is*. That is the whole method, and it's worth saying out loud to the agent when several flags share a cause.

## Edge cases

- **Agent pastes an existing published listing and asks for a rewrite.** Screen it as-is first, report the flags, then deliver the rewrite. They need to know what was already live.
- **Legally qualified senior housing (55+/62+ HOPA communities in the U.S.).** Age-restricted marketing can be lawful here. Flag it, note that it is permitted only if the community holds the exemption, and tell them to confirm with their broker rather than assuming.
- **Rental listings with qualifying criteria.** Income-screening language is where Ontario diverges sharply from parts of the U.S. Flag anything resembling "must earn 3x rent" or "no subsidy" and point to the jurisdiction question.
- **Agent argues back.** Do not escalate and do not cave silently. Restate the risk in one sentence, note it is their call, and keep the flag in the report so the record exists.
- **Non-English listing copy.** Screen it the same way if you can read it; if you're unsure of idiom, say so rather than passing it clean.

## Reference files

- `references/advertising-rules.md` — state/provincial licensee advertising rules (Arizona ADRE and Ontario RECO detailed), MLS public-remarks rules, and truthfulness/material-fact standards. Load during every advertising screen.
- `references/fair-housing-terms.md` — protected classes (U.S. federal, common state/MLS additions, Ontario), the full avoid/use-instead table, and jurisdiction notes. Load this during every compliance screen.
- `assets/output-template.md` — the exact output skeleton, if you need to check formatting.

## Version

v1.6 — Georgia (GREC) added. v1.5 — state advertising rules for AZ, CA, TX, FL, NV, NC, ON. v1.4 — advertising & disclosure screen added. v1.3 — review-mode labelling; no taglines in listing copy. v1.2 — quick-check and review modes added. v1.1 — voice calibration added. Built by Trevor McHaffie, Workflow Automation Architect — trevormchaffie.com
