# Changelog

All notable changes to the Real Estate Listing Writer + Fair Housing Compliance Checker.

Compliance references were last verified **August 2026**. Regulations change — anything unverified for more than twelve months should be re-checked before distribution.

---

## [1.6.0] — 2026-08-13

**Added**
- Georgia (GREC) advertising rules — Rule 520-1-.09. Firm name and telephone number required on specific-property advertising; firm name at equal or greater size, prominence, and frequency than the agent's; firm name and phone on every viewable web page; written owner permission required before advertising.
- Georgia cross-reference: Rule 520-1-.09(4) requires advertising content be confined to information about the real estate itself, making a Fair Housing flag simultaneously a state licence exposure for Georgia agents.

## [1.5.0] — 2026-08-13

**Added**
- State-specific licensee advertising rules for Arizona (ADRE), California (DRE), Texas (TREC), Florida (FREC), Nevada (NRED), North Carolina (NCREC), and Ontario (RECO/TRESA).
- Per-jurisdiction comparison table of the most commonly missed requirement.
- Explicit coverage limits: uncovered jurisdictions are named, and the skill is instructed to flag the category without asserting a specific rule.

**Changed**
- Jurisdiction is now requested on every listing rather than only when a flag depends on it.

## [1.4.0] — 2026-08-13

**Added**
- Advertising and disclosure screen as a separate pass from Fair Housing, reported in its own output section.
- `references/advertising-rules.md` — licensee advertising rules, MLS public-remarks rules, truthfulness and material-fact standards.
- Automatic removal of agent contact information, compensation references, and showing instructions from MLS remarks.

**Changed**
- Disclaimer broadened from Fair Housing alone to Fair Housing, advertising, and disclosure compliance.

## [1.3.0] — 2026-08-09

**Added**
- Review mode now labels its output explicitly as the agent's listing rewritten, with a count of phrases changed.
- Rule preventing taglines, slogans, and sign-offs from being appended to listing copy.

## [1.2.0] — 2026-08-09

**Added**
- Quick-check mode: a bare phrase or "can I say X" question is screened directly without requesting property details.
- Review mode: an existing listing is screened as written, then rewritten in one pass.

## [1.1.0] — 2026-08-08

**Added**
- Voice calibration. Reads voice profiles and past-listing samples from project instructions or pasted samples.
- Non-compliant patterns in an agent's samples are surfaced rather than reproduced.

## [1.0.0] — 2026-08-01

Initial release.

- MLS remarks and marketing listing generation from property facts.
- Fair Housing screen on every output: U.S. federal protected classes, common state and MLS additions, Ontario Human Rights Code grounds.
- Proxy-language detection (school quality, neighbourhood safety, household composition).
- Flag-don't-delete behaviour with compliant rewrites.
- No-fabrication rule on property facts.
- Standard disclaimer on every output.
