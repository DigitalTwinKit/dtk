---
name: hooks
description: Generate 10 alternative opening hooks (~4 seconds / ~10 words each) for a video script. Use when the user says "the opening is weak", "give me hooks", "rewrite the hook", or pastes a script and asks for better first lines.
triggers:
  - generate hooks
  - rewrite the hook
  - better opening
  - hook ideas
  - opening lines
  - first 4 seconds
---

# DigitalTwinKit — Hook Generator

The first 4 seconds of a video determine hold rate. Most drafts open with setup — your job is to rewrite the opening so it lands the central claim or question immediately.

## What you do

When the user provides a script or a topic plus claim, generate **10 alternative opening hooks**, each:

- ~10 words / ~4 seconds spoken
- Stating or implying the central claim
- Using a **different rhetorical move** (see list below) — no two hooks from the same category
- Matching the user's voice when a persona doc is available; otherwise neutral confident

## Inputs to gather

- **Script or topic + claim** — the draft or the core idea the hook must land
- **Audience** — who is watching
- **Persona doc** — if available, use it to match tone and phrasing

## Rhetorical moves to draw from

Use a different one for each of the 10:

1. **Direct claim** — state the conclusion flat
2. **Contrarian frame** — name the consensus and reject it
3. **In-medias-res story** — drop into a scene mid-action
4. **Named pattern** — give the topic a label and define it
5. **Question** — the question the video answers
6. **Stat punch** — a number that reframes the topic
7. **Confession** — admit something the audience suspects
8. **Misconception** — name the wrong belief, set up the correction
9. **Demonstration** — describe a thing the viewer can see / try
10. **Future-state** — paint where this leads in one sentence

## Output format

Number the hooks 1–10. **Do not pick a favorite or rank them.** The user picks.

```
HOOK 1 [direct claim] — [hook text, ~10 words]
HOOK 2 [contrarian frame] — [hook text]
...
```

After the list, add one line: `Reply with a number and I'll splice it into the script.`

## Don'ts

- Don't use clickbait phrasing ("You won't believe...", "The shocking truth...").
- Don't open with "In this video" or "Today we're going to".
- Don't repeat the same opening word across hooks.
- Don't generate fewer than 10 — variety is the value.
