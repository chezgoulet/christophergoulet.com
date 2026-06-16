# Canada — canada.christophergoulet.com

## Role

The Canada page is a portal home for Franco-Americans exploring citizenship reconnection. It is the most emotionally driven of the four subdomains. Its job is to make someone who has felt disconnected from their roots realize that the path back is real, walkable, and that someone has already done it.

**The feeling after 5 minutes:** "I didn't know this was possible. I think this might be for me. I want to talk to this person."

## Core Content (from Christopher's interview)

- Great-grandfather Wilfrid Goulet came from Québec during the Grande Hémorragie
- Christopher's father described family gatherings at a cabin in the woods — songs, music, stories, all in French. Food and wine and dancing. Christopher yearned for this his whole life
- Watched the Harper government's citizenship changes from Vermont. The door seemed closed
- Bjorkquist decision (2023) — hope rose again. Applied under interim measures before Bill C-3
- One of the first ~5,000 "found Canadians" — *les Canadiens retrouvés*
- "Holding my certificate of Canadian citizenship was one of the proudest days of my life. I was right. I am Canadian, and I always was all along."
- "I want to contribute to a society that opened the door and welcomed me in with open arms."

## Information Architecture

```
[Nav — brand + "Book a call" CTA + bilingual toggle]
[Hero — story-first, single column]
[Stats bar — key numbers]
[The story — Wilfrid, the cabin, the journey]
[How it works — 3 steps]
[Who this is for — short identifiers]
[FAQ — "not a militia" style questions live here]
[Booking panel]
[Footer]
```

No archive section. No services section. This page is about a forward journey.

## Bilingual Toggle

Full toggle between English and French versions of the page. The toggle is prominent — top nav, right side, clearly labeled (EN | FR).

**Implementation:** Two complete versions of the content in the same HTML file, toggled by a JS switch. CSS controls visibility. The French version uses blue + white on dark (Québec flag colors). The English version uses red + white on dark (Canadian flag colors). Both must work on dark background.

**Language mixing policy for English view:** More French phrases and Québecois-isms than other pages, but not overboard. Key terms in French with English context: *les Canadiens retrouvés*, *Grande Hémorragie*, *bienvenue chez vous*. The tagline is bilingual by default: "Retrouver vos racines — finding your way home."

On the French view, full French. Same structure, same emotional weight.

## Design Direction

**Reference:** Emotional, warm, grounded. Not a consulting page. Not a tech page. A home page in the literal sense.

**Flag-responsive palette:**
- English mode: Canadian red (#e04545 or similar dark-compatible red) on true black OLED background. White text for body, red for accents and highlights.
- French mode: Québec blue (#2a5caa or similar) on true black OLED background. White text for body, blue for accents.
- Both modes: No heavy white backgrounds. Red and blue on dark. White is text, not canvas.

**What makes this page feel like itself:**
- No mesh canvas. No boot sequence. No stats panels (a small stats bar is fine, but not the big framed panel from the biz/tech templates)
- Story-first — the hero is not a value proposition, it's a narrative opening
- Bilingual toggle is a feature, not an afterthought. It should feel like switching between two homes, not like a translation widget
- The palette shift when toggling languages (red → blue) should feel like crossing the border, not like a theme switch
- Warm, personal, human-scale typography. The Fraunces serif carries the emotional weight. IBM Plex Sans for body.

### Key structural difference from current version

The current canada page has a story section, a "how it works" section, and a "who this is for" section. That structure is close to right. What needs to change:

1. **The hero must lead with Christopher's own words from the interview** — "I am Canadian, and I always was all along" — not a generic value prop
2. **Add the cabin story** — the childhood memory of his father describing French Canadian family gatherings. This is the emotional on-ramp
3. **The stats bar should be small and human-scale** — "# under 5,000 found Canadians" is the headline stat. Not "15+ yrs" or "3x"
4. **Add a FAQ** — the "not a militia" approach: things people worry about (cost, timeline, do I need a lawyer, do I need French) get answered so they don't get in the way of the emotional journey
5. **No services** — this page does not sell consulting. It offers a path. The CTA is "Book a free call" but the framing is "let's talk about your story," not "hire me"

## OLED

True black background (`#000000`). The Canada page has the most reason to use it — the red/white and blue/white palettes on black are the Canadian and Québec flags rendered in dark mode. Pure black makes the red and blue glow.

## Content Headcount

**Stories to capture from Christopher's interview (not yet on the page):**
1. The cabin in the woods — his father's childhood memory of French Canadian family gatherings. Songs, music, stories, food, wine, dancing. The thing he yearned for his whole life.
2. Watching from Vermont during the Harper years — the door seemed closed but he never gave up hope
3. The Bjorkquist decision (2023) — hope rising again, applying under interim measures before Bill C-3 even existed
4. Holding the citizenship certificate — "one of the proudest days of my life. I was right. I am Canadian, and I always was all along."
5. "I want to contribute to a society that opened the door and welcomed me in" — the motivation to do this work

**Framings to capture:**
6. Found Canadians as synthesis — "some synthesis of a people very old and a people very new"
7. The path is clear — "few other diasporas have such a clear path to their roots"
8. If someone has ever felt alone or disconnected like an alien in their own country — "there are so many of us. This is a shared experience."

## FAQ Topics (to be written)

- Do I need a lawyer?
- How long does it take?
- Do I need to speak French?
- What if I don't know my family tree?
- How much does it cost?
- What if I'm not sure my family qualifies?
- What's the difference between Bill C-3 and the Bjorkquist pathway?
- I'm a found Canadian too — can you help me with the paperwork, or just the emotional side?
