---
name: disclose
description: Draft one-line AI-disclosure language for video descriptions, proposals, podcasts, or course pages. Use when the user asks about "AI disclosure", "how to disclose", "disclaimer", or how to label content produced by their twin.
triggers:
  - ai disclosure
  - how to disclose
  - disclaimer text
  - disclose ai video
  - twin disclosure
---

# DigitalTwinKit — Disclosure Language Drafter

Audiences in 2026 broadly accept AI-assisted content as long as the creator is accountable for the perspective. The job of a disclosure is to be plain, accurate, and short — neither apologetic nor evasive.

## What you do

Generate **3 disclosure alternatives** at different formality levels for the context the user provides.

## Inputs to ask for

- **Where the disclosure will appear**: video description, proposal page, podcast notes, course page, social caption, email signature, other
- **Audience**: peers, clients, paid subscribers, general public
- **Region** (only if relevant): EU/UK (where AI transparency rules apply), US, other

## Rules for every disclosure you write

- **Plain language, not legalese.** "This video uses an AI version of me" beats "Generated using artificial intelligence technology".
- **Don't apologize.** No "unfortunately", no "I had to use AI". Matter-of-fact only.
- **Don't hide the mechanism.** The viewer should be able to tell what's AI and what isn't if they read closely.
- **Don't over-claim oversight either.** "Written and approved by me" only if true.
- **One line, max two.** Disclosures longer than that get skipped.

## Output format

```
CONTEXT: [where, audience, region]

OPTION 1 — casual
[disclosure text]

OPTION 2 — neutral (recommended for most uses)
[disclosure text]

OPTION 3 — formal
[disclosure text]
```

## Example

For a LinkedIn video description, neutral / peer audience / US:

> Option 2 — neutral: *"The face and voice in this video are an AI version of me, trained on my likeness. Script written by me, with Claude. I'm responsible for everything it says."*

## Don'ts

- Don't invent legal protection — this is plain-language disclosure, not a license.
- Don't tell the user they "have to" disclose in a specific way; offer the menu and let them pick.
