# Civic — civic.christophergoulet.com

## Role

The Civic page is for neighbors, organizers, fellow selectboard members, and anyone involved in the work of keeping a community together. It covers Christopher's municipal service, community organizing, and the 161st Catamounts scouting troop.

**The feeling after 5 minutes:** "This person has actually been in the room. They've done the hard, unglamorous work of keeping a town running through a crisis. And they made it better — the pride flag flies, cannabis is legal, taxes stayed low, and kids have new playgrounds."

## Aesthetic Direction

**Theatrical stage lighting on a dark house. Cirque du Soleil, not carnival midway.**

The coral and gold are not carnival colors — they're gel over spotlights. The content is not arranged in booths — it's performed in acts. The dark background is the auditorium; the sections are where the light falls.

**What this means in practice:**
- Opulent, theatrical, slightly mysterious. Deep jewel tones on black. Warm spotlights pick out specific elements; the rest stays in shadow.
- Nothing literal. No tent flaps, no midway banners, no striped awnings, no ticket booths. The coral and gold glow like stage lights, not carnival paint.
- String lights become **footlights** — a warm gold gradient washing up from the bottom edge of each section. Content feels lit from below, like a performer standing at the lip of the stage.
- The Fraunces serif works at larger, more dramatic sizes for section headers. Pull quotes feel like an actor stepping forward to address the audience directly — "I spoke truth to power and moved the needle."
- Sections are **acts**, not chapters. Generous spacing between them — breathing room, like the pause between acts. Scroll reveals have theatrical timing: a brief pause, then content appears as if the curtain just went up.
- The coral accent is not just a color — it's a gel over a spotlight. It has warmth and intensity that feels lit from within, not painted on. On dark background, it glows.

**Counter-examples of what this is NOT:**
- Not a literal carnival (no midway banners, no tent flaps, no ticket booth)
- Not a government website (no official seals, no beige, no Helvetica)
- Not tech-in-disguise (no mesh canvas, no terminal aesthetic)
- Not minimal/restrained (this page has *presence* — it fills the room)

**Color palette:**
- Background: `#0a0b0d` (existing dark — the auditorium)
- Primary accent: Warm carnival coral — `#e87a6a` or as chosen from palette exploration (the spotlight gel)
- Secondary accent: Soft gold — `#dfb85a` or as chosen (the footlight glow)
- Text: warm white `#e6e8ea`
- Muted: `#9aa1a9`
- The coral and gold must read as *illuminated*, not painted. On dark, they should feel like they're emitting light, not reflecting it.

**The one animated element:** A gentle footlight glow at the bottom of sections — a CSS gradient that pulses subtly, like someone adjusted a dimmer. That's it. No mesh canvas, no boot sequence, no marquee text.

## Content Architecture

```
[Nav — brand + "Book a call" CTA]
[Hero — story left, stats panel right]
[Section 01 — Selectboard: Governing through a crisis]
[Section 02 — 161st Catamounts: Adventure, skills, community]
[Section 03 — Community work: Whatdothlife, Windsor Live]
[Section 04 — What I offer to communities]
[Booking panel]
[Footer — standard layout, "web ring" pattern optional for this page]
```

### Hero

**Left column (story):**
- Title: "Community resilience starts with people who show up."
- Subtitle/lede: "Two and a half years on the Windsor Selectboard from the beginning of COVID through the worst of it. Founding a community scouting troop. Building mutual aid networks. Running a venue. This work taught me what communities actually need — and it's not enterprise software."
- Actions: "Book a free call" (coral btn-primary) + "See my work" (btn-ghost, linking to #selectboard)

**Right column (stats panel):**
A human-scale stats panel, not the framed terminal panel from tech/biz. Something simpler — maybe a card with four stat lines, no mesh canvas, no boot sequence.
- 2.5 years on Windsor Selectboard (COVID onset through the worst)
- Founder, 161st Catamounts (Outdoor Service Guides)
- Co-founder, Whatdothlife (501(c)(3) arts collective)
- Co-founder, Windsor Live (community venue since 2017)

### Section 01 — Selectboard

**Section header:** "Municipal service" / "Governing through a crisis"

**Content (drawn from interview):**
- Sworn in about two weeks before the lockdowns started
- Very hard choices at almost every meeting during that time
- Proud of: facilitating information sharing, bringing concerns of overlooked people back into the system, pulling every available lever for those who were traditionally unheard
- Permanent wins: pride flag raised over town hall during pride month, retail cannabis passed in town limits, taxes kept low during the worst economic upheaval in memory, historic investments in infrastructure, funds found for more playgrounds
- "I spoke truth to power and moved the needle."
- "I learned quite a bit about how a municipality works — the layers and dynamics of power, market, and people and how they all interact."

**Tone:** Direct, proud but not boastful. The pride flag and playgrounds should carry as much weight as the infrastructure investments. This section should make a fellow selectboard member nod and say "yes, that's what it's like."

### Section 02 — 161st Catamounts

**Section header:** "Community scouting" / "The 161st Catamounts"

**Lead with the adventure and the skills, not the defensive framing:**
- "A community project based on getting together, getting really good at skills, and going on adventures."
- Founder and Scoutmaster (Chief Tiguidou), chartered under Outdoor Service Guides
- All-adult, community defense-oriented, democratic governance
- Core training: de-escalation and crisis communication, Wilderness First Responder, emergency preparedness, HAM radio, backcountry navigation, community safety
- Motto: "Find your path, change the world!"
- "Framing is important, intent matters. We are passionately driven by principles and values that lead us to community defense and resilience as a practice — that is downstream of principles and values."

**"Not a militia" placement:** Bottom of the section, as an explicit note. Not the lead. Not the hero. Something like: "A note on framing: the 161st Catamounts are explicitly not a militia. We operate with democratic governance, mandatory background checks, JEDI principles, community accountability, and a de-escalation-first philosophy. The distinction matters and the distinguishing factors are obvious to anyone who engages with us."

### Section 03 — Community work

**Section header:** "More ways I serve" / "Community building across Windsor"

**Two items:**
1. **Whatdothlife** — Founding member of this Vermont music and arts collective, navigated it through 501(c)(3) status. Governance, compliance, community programming built from scratch.
2. **Windsor Live** — Community venue, event space, and cultural hub in downtown Windsor since 2017. Live music, art shows, community gatherings.

### Section 04 — What I offer

**Section header:** "What I offer to communities"

Three service cards (coral underline on hover):
1. **Municipal & Civic Technology** — Technology strategy for local government. I've been in the room — I know what small governments actually need, and it's not enterprise software.
2. **Cooperative Technology** — Helping community organizations move to member-owned, democratic systems. Platform co-op design and implementation for the people who do the work.
3. **Security & Resilience** — For community organizations and nonprofits at prices that make sense. Threat modeling, hardening, and continuity planning grounded in real experience.

## FAQ

A small FAQ section after the service cards (or in place of them if they feel too commercial). Topics:
- "The Catamounts sound like a militia." — The honest answer above
- "How long does it take to get something done in local government?" — Christopher's answer from experience
- "I'm part of a small nonprofit with no budget for tech. Can you still help?" — Yes, scaled scopes exist

## What NOT to include

- No tech jargon (this page is for neighbors, not engineers)
- No mesh canvas
- No boot sequence
- No terminal aesthetic
- No page counter (that's tech's thing)
- No bilingual toggle (civic doesn't need it)
- No Covered Bridge story (that's biz)
- No diaspora content (that's canada)

## OLED

Near-black (`#0a0b0d`) is fine. The carnival warmth comes from the coral/gold accents, not from pure black. True black isn't critical here.

## Special Elements

- Optional: a small, tasteful animated element that evokes the carnival feel. Not a GIF of a ferris wheel. Maybe a subtle string-light glow animation (a few dots of gold that pulse gently) in the hero or footer.
- Section dividers could use a small star or pennant character (✦ or ⚜ or similar) instead of a flat horizontal rule.

## Open Questions

1. **Coral color** — `#e87a6a` is a starting guess. Needs to feel festive and grounded on dark, not washed out. Should we test this on the palette explorer?
2. **Gold secondary** — `#d4a84b` for the string-light warmth. Does this work with the coral, or does it pull too warm/yellow?
3. **The carnival feel in execution** — how much of this is color vs. layout vs. typography vs. micro-animations? My instinct is mostly color + the section divider elements + a slightly looser typography treatment. Layout stays clean and readable.
