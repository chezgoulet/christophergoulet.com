# Biz — biz.christophergoulet.com

## Role

The Biz page is for small business owners, family businesses, and nonprofits across New England who need technology that works without owning them. It's the most straightforward of the four subdomains — amber warmth, Main Street values, no theatrical framing, no retro gimmicks.

**The feeling after 5 minutes:** "This person has actually run a business. He's not selling me something he read about in a newsletter. He converted his family's bakery to worker ownership and tripled revenue. He can probably help me too."

## Aesthetic Direction

**Warm, approachable, Main Street. Amber stays.**

The biz page doesn't need a signature gimmick — it needs authority, clarity, and warmth. The amber palette from the existing site is correct. The aesthetic is: a well-lit Main Street storefront at golden hour. Approachable. Trustworthy. No theatrical lighting, no retro web motifs, no canvas animations.

**What this means in practice:**
- Amber (#e8b14f) primary accent. Same as the existing palette exploration — no change needed.
- Dark background (#0a0b0d), warm amber highlights, clean sans-serif body text.
- The existing service card pattern (.serve with amber underline on hover) works perfectly here.
- The existing proof block (amber-dim border, amber stats) works perfectly here.
- The pain questions format (2-column grid, italic questions, concise answers) works well — it's the right format for this audience.

**What NOT to include:**
- No mesh canvas (biz doesn't need a tech aesthetic)
- No boot sequence (biz doesn't need terminal framing)
- No page counter or web ring (tech's thing)
- No bilingual toggle
- No theatrical lighting
- No Geocities elements
- No "acts" framing

**Counter-examples:**
- Not a tech startup site (no grid backgrounds, no floating nodes, no "we're disrupting" energy)
- Not a cookie-cutter small biz IT site (no stock photos of people shaking hands, no "24/7 support" jargon)
- Not corporate (no "enterprise-grade solutions" language)
- Not trendy minimalist (this page needs enough warmth to feel like a person, not a Squarespace template)

## Content Architecture

```
[Nav — brand + "Book a call" CTA]
[Hero — identity + subtitle + stats panel + actions]
[Section 01 — Pain questions: "It shouldn't be this hard"]
[Section 02 — Proof: Covered Bridge story]
[Section 03 — Services: "What I deliver"]
[Section 04 — "If you want to go far, go together"]
[Booking panel]
[Footer]
```

### Hero

**Left column (identity + lede):**
- No boot sequence. A simple, warm greeting.
- Title: "Small business technology that works — **and that you own.**"
- Subtitle / lede: "I help small businesses, family businesses, and nonprofits across New England get technology that stays out of the way — and keep ownership where it belongs: with you. I've done this for my own family's business and I can do it for yours."
- If there's room for a short pull quote: "I don't try to oversell bullshit. I just listen."
- Actions: "Book a free call" (amber btn-primary) + "See how I help" (btn-ghost, linking to #how)

**Right column (stats panel):**
A simple stats card — no mesh canvas, no terminal chrome. Four stats in a 2×2 grid with amber numbers:
- 3× — grew our bakery
- 100% — worker-owned
- 30 yrs — family legacy kept
- EN·FR — fully bilingual

The stats panel should feel like a small side card, not a featured element. Amber numbers, muted labels, clean.

### Pain Questions

**Section header:** "It shouldn't be this hard to run your business."

**4 pain cards in 2-column grid (same pattern as current biz page):**

1. **"My systems keep breaking and no one can fix them."**
   I build simple, documented, stable setups that one person on your team can actually run — without needing me on retainer forever.

2. **"I'm drowning in monthly subscriptions."**
   Software rent adds up fast. Not every tool needs a subscription. Where it makes sense, I move you onto tools you own outright — so costs stay predictable and your data stays yours.

3. **"I want to pass this on — not sell to a stranger."**
   There's another option besides closing up or selling out: hand the business to the people who run it. I help families and owners explore worker ownership and cooperative models. I've done it.

4. **"The big software treats me like a corporation."**
   You're not an enterprise and you shouldn't pay like one. I right-size technology for real small businesses, in plain language, at a price that fits.

### Proof Block — Covered Bridge

**Section header:** "I've done this myself."

**The isomorphism framing (from Christopher's interview):**
"There's actually a lot of shared DNA and overlap between developing software and baking and shipping cookies. Both take source code, put it through a pipeline, package it, and deploy it."

**The story:**
"I led the conversion of my family's 30-year-old cookie bakery into a 100% worker-owned cooperative — and tripled revenue in three years. Four worker-owners, four honest recipes, no unpronounceable ingredients. Covered Bridge Cooperative proves that a Main Street business can belong to the people who run it — and do better for it."

**The "it's hard" honesty (from Christopher's interview):**
"It's hard. Collaborating with people as equals in a workplace based on values that you all care about is hard. It is worth it. But it's not a switch you can flip. It is an active engagement process that you must choose to do every day, just like any relationship."

**Proof stats row:** 100% worker-owned · 3× revenue in 3 yrs · 30 yrs family legacy

**Format:** Amber-dim border panel (same as current biz page). The isomorphism framing goes at the top as a pull quote or tagline. The honesty paragraph goes at the bottom as a grounded note — "this is real work, it's worth doing, and I've done it."

### Services

**Section header:** "What I deliver."

**4 service cards in 3-column grid (amber underline on hover):**

1. **Infrastructure & DevOps** — Design, deployment, and hardening. Docker Compose to TrueNAS, Traefik to Authentik. Stacks one person can operate.

2. **Private AI Infrastructure** — On-premise LLM inference, model distribution, and cluster management. Keep your data on your hardware — no cloud dependency, no leakage.

3. **Security & Resilience** — Architecture-level security review, threat modeling, and hardening. I find what automated scanners miss — logic errors, design assumptions, dead code paths.

4. **Cooperative Technology** — Platform co-op design and implementation. I help organizations move from extractive technology models to member-owned, democratically governed systems.

### "If you want to go far, go together"

A short section, maybe one panel or a pull quote. Warm tone.

**Content (from Christopher's interview):**
"If you want to go fast, go alone. If you want to go far, go together. Covered Bridge proves it."

This is the closure before the booking CTA. It's the values statement that ties the services back to the person. Keep it short — one sentence, maybe a short paragraph. No more.

### Booking

Same book-panel pattern as other subdomains. Amber accents.

"The first call is free." / "Tell me what you're trying to build, keep, or pass on. If I can help, I'll tell you how. If I can't, I'll tell you that too."

### Footer

Standard layout. Links to all four subdomains + main site. "Windsor, Vermont · EN · FR · © 2026"

## What's Different from the Current Version

The biz page already exists from Claude's draft and my build. It needs:

1. **Hero stats panel** — simplify. Remove the mesh canvas. A clean 2×2 amber numbers card.
2. **Pain questions** — keep the format, update the language to match Christopher's voice (more "I listen and understand the position" — the tone from question 6 of the interview).
3. **Proof block** — add the isomorphism framing (cookies and software are pipelines). Add the honesty paragraph about how hard cooperative work is. This is what separates the proof block from a generic case study.
4. **The proverb** — "If you want to go fast, go alone. If you want to go far, go together." — add as a standalone value statement before the booking panel.
5. **Remove** any remaining Sherbrooke/relocation references (should already be gone, verify)
6. **Remove** the "drowning in monthly subscriptions" language if it feels too generic — Christopher's interview clarified that it's a real pain point but the framing is about taking a step back to ask "what do I actually need my systems to do for me?" rather than "subscriptions bad"

## From Christopher's Interview — Voice Anchors for This Page

These are direct quotes that should inform the tone:

- "I often get compliments about how I don't try to oversell bullshit. I just listen."
- "My depth of experience allows me to help bridge gaps of understanding, context, and capacity that almost no one else can."
- "Somehow complex solutions are made simple through this process, and that's something I uniquely offer."
- "It's worth taking a step back and genuinely asking: what do I need my systems to do for me?"
- "We don't take a biased view to anything out of the gate. We learn the problem domain and address the issues holistically."
- "If you want to go fast, go alone. If you want to go far, go together."
