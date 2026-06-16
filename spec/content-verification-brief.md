# Content Verification & Design Brief

**Source:** Interview responses from Christopher Goulet, June 16, 2026
**Purpose:** Capture verified claims, corrected inaccuracies, tone guidance, and design direction for the five-site architecture.
**Status:** Operator-verified. Ready for design spec phase.

---

## Verified Claims — Across All Sites

These are statements that appear on the current sites. Christopher's responses confirm them:

| Claim | Status | Detail |
|---|---|---|
| Covered Bridge: 3× revenue in 3 years after coop conversion | ✅ Verified | Revenue tripled after converting 30-year family bakery to 100% worker ownership |
| Covered Bridge: 100% worker-owned | ✅ Verified | Four worker-owners, living wage, good working conditions |
| Covered Bridge: 4 recipes, real ingredients | ✅ Verified | Four honest recipes, no unpronounceable ingredients |
| Coop conversion: Christopher led it | ✅ Verified | He led the conversion; it's his core proof case |
| Whatdothlife: founding member, 501(c)(3) | ✅ Verified | Founding member, navigated nonprofit formation |
| Windsor Selectboard: 2.5 years from COVID onset | ✅ Verified | Sworn in ~2 weeks before lockdowns started. Pride flag, retail cannabis, low taxes, infrastructure investment, playgrounds |
| 161st Catamounts: Founder, Chief Tiguidou, OSG charter | ✅ Verified | Community scouting troop, Outdoor Service Guides. Adventure + skills + values first |
| Bill C-3 / Bjorkquist: among first #5,000 found Canadians | ✅ Verified | Applied under interim measures before Bill C-3. Proudest day: holding citizenship certificate |
| Bilingual (French / English) | ✅ Verified | Bicultural. Québec heritage through great-grandfather Wilfrid Goulet |
| General Manager at Hanover Stringed Instruments | ✅ Verified | Full P&L, purchasing, repair, live sound, sales, strategy, lutherie |
| Performer: The Pilgrims, The Jobz | ✅ Verified | Toured New England |
| Uproot Technology LLC | ✅ Verified | Independent IT services since 2013 |

## Claims Needing Correction

These appeared on the current sites and need fixing:

| Stale Claim | Issue | Corrected |
|---|---|---|
| "15+ yrs helping" (biz hero panel stat) | Ambiguous — not clear what it maps to | Replace with a stat that has a clear referent. Options: 5 yrs GM, 2.5 yrs Selectboard, 10+ yrs tech |
| Quebec/Sherbrooke relocation references | Scrubbed per previous session | Already removed from my push. Verify no remnants on the versions Christopher modified |
| Scouting framed as "explicitly not a militia" as lead | Defensive framing; Christopher says community + adventure first | Move "not a militia" to FAQ or bottom. Lead with skills, adventures, values |
| Consulting geography: "New England + Quebec" | Too narrow per Christopher | Change to "based in New England, work with anyone anywhere" |

## Tone & Voice Guidance

**The framing: Cookie maker who builds systems.** Christopher's own words: "I make cookies for a living with some of my best friends. We own it together." That's the 10-second answer. The 2-minute answer builds from there: Systems Builder, Community Collaborator, Fixer.

**Key voice qualities from the interview:**
- "I speak human and computer fluently" — this is the core differentiator
- "I don't try to oversell bullshit. I just listen." — conversational, earned authority
- "If you want to go fast, go alone. If you want to go far, go together." — values-forward
- "I can be a little choosy with the projects I take on" — confident selectivity
- "It is an active engagement process you must choose to do every day, just like any relationship" — honest about the work
- "I'm an internationalist at heart" — expansive, not provincial

**Isomorphic systems framing:** The Covered Bridge story and the tech work are not two separate things — they're the same pattern expressed through different domains. Both take source code (recipes), put it through a pipeline (production line), package it, and deploy it. "I generate isomorphic systems for values-based endeavors."

**What the visitor should feel after 5 minutes:** "That Christopher's skills are excellent, his depth is hard to match, his perspective is nearly inaccessible to anyone else, and he's willing and able to take care of me if I want him to."

**Pricing posture:** $125/hr. Not on the site, but the site should build enough trust that the number feels reasonable by the time someone books a call.

---

## Design Direction

**The core critique:** The current templates have shared widgets that don't fit every domain. The organization feels like "take a tech template and paint in the colors." Each domain needs its own information architecture centered on what brings someone there.

**Per-domain design direction:**

### Apex (christophergoulet.com)
Minimal router, as designed. True to heydonworks.com — simplicity with attitude conveyed in few words. Four doors, one CTA. No shared widgets, no stats panels, no mesh canvas.

### Biz (biz.christophergoulet.com)
Warm, approachable, solution-oriented. The pain questions work but need to feel less templated. Covered Bridge is the proof block — lead with the isomorphism (cookies = software). Christopher's process: listen first, understand the position, collaborate on the answer, make complex solutions simple.

### Tech (tech.christophergoulet.com)
Terminal aesthetic fits here. Should feel like wodniack.dev — immersive, with coherent messaging that shows depth without overwhelming. Should demonstrate competency for hire AND show off cool stuff (Phonon, The House). The isomorphism (baking pipeline = software pipeline) is the strongest framing. The tagline: "Systems that last are systems that can evolve."

### Canada (canada.christophergoulet.com)
Story-first, full bilingual toggle. This page needs the most emotional weight — Christopher's citizenship ceremony story (holding the certificate, "I am Canadian and I always was all along") is the strongest content on any of the five sites. Should feel like a portal home, not a consulting landing page. More French phrases and Québecois-isms on the English side. The Grande Hémorragie, Wilfrid Goulet, the found Canadian story, the reconnection pathway.

### Civic (civic.christophergoulet.com)
Human-scale, grounded. Lead with what the Selectboard experience taught Christopher about how power, markets, and people interact. The Catamounts lead with adventure and skills — "a community project based on getting together, getting really good at skills, and going on adventures." The "not a militia" framing is defensive and goes in an FAQ, not the hero.

---

## Architecture Decisions

| Decision | Answer |
|---|---|
| One repo per subdomain? | Yes, GH Pages. Under chezgoulet org. |
| Bilingual? | Yes, full toggle for every page. Canada page gets more French/Québecois content. |
| Each page same layout? | No — each domain has its own information architecture. Shared design tokens (fonts, spacing, scanline) but different layouts and widgets. |
| Stats panels / mesh canvas / boot sequences on every page? | No — only where the domain calls for it. Tech gets terminal aesthetic. Others get their own signature elements. |
| Geography boundary? | "Based in New England, work with anyone anywhere." |
| Pricing on site? | Not on the front page. $125/hr is the number. Funnel builds trust toward accepting that price. |
| Leave crumbs between subdomains? | Minimal. Something simple at the bottom of each page. No active redirect. |
| Scouting "not a militia" placement? | FAQ or bottom of page. Not in hero or lead. |

---

## Content Gaps to Fill

These are areas where Christopher's interview surfaced information that needs to be captured on the sites:

1. **The isomorphism framing** — Cookies and software are both source code → pipeline → package → deploy. This is the single best metaphor for the biz and tech sites. Not currently on any page.
2. **The feeling of holding the citizenship certificate** — "One of the proudest days of my life. I was right. I am Canadian, and I always was all along." This belongs on the Canada page in Christopher's own words.
3. **The Catamounts as adventure-first** — "Getting together, getting really good at skills, and going on adventures." The current civic page leads with "not a militia" and governance structure. Needs to lead with this.
4. **Selectboard decisions** — Pride flag, retail cannabis, low taxes during COVID, infrastructure investment, playgrounds. These specific, concrete wins belong on the civic page as proof of effectiveness.
5. **"I speak human and computer fluently"** — This belongs in the tech hero.
6. **"I can be a little choosy"** — This belongs in the consulting/services framing. It signals quality by selectivity.
7. **Reference sites for aesthetic:**
   - wodniack.dev — immersive experience with coherent messaging
   - heydonworks.com — simplicity with attitude conveyed in few words
   - ciechanow.ski — incredible functionality that lets people learn as they go

---

## Next Phase: Design Spec

Christopher confirmed: we'll spec out the design and build it, not iterate on the current templates. The design brief above defines the direction for each subdomain. The next step is a structured design spec per subdomain covering:

- Information architecture (content hierarchy per page)
- Signature UI elements per domain (what makes each page feel like itself)
- Layout wireframes (not visual design — structural layout)
- Bilingual toggle implementation
- Responsive behavior

Ready to proceed when you are.
