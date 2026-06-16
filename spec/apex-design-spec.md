# Apex — christophergoulet.com

## Role

The apex is a router. Its only job is to help a first-time visitor self-identify in under 5 seconds and click through to the correct subdomain. It is not a landing page, not a portfolio, not a bio.

## Information Architecture (top to bottom)

```
[Nav bar — brand + "Book a call" CTA]
[Hero — one-line identity, short subtitle]
[Four doors — 2×2 grid]
[Booking panel — "The first call is free"]
[Footer — subdomain links + location + copyright]
```

That's it. No sections between the doors and the booking panel. No archive, no about, no stats, no services.

## Content Per Section

### Nav
- Brand: `C.GOULET` (mono font, 14px, linking to `#top`)
- Single link: `Book a call` styled as CTA button
- Mobile nav toggle (hamburger)

### Hero
- **Line 1** (serif, large): "Christopher Goulet"
- **Line 2** (serif, large, italic accent word): "I help people build things *they actually own.*"
- **Subtitle** (sans, muted): "Business infrastructure. Diaspora reconnection. Sovereign technology. Community resilience."
- No boot sequence, no stats panel, no mesh canvas, no animation
- No CTA buttons in the hero — the doors ARE the CTA

### Four Doors (2×2 grid)

Each door is a card with: SVG icon, subdomain label, one-sentence description, "Go →" link.

**Door 1 — biz**
- Icon: `#g-shop` (storefront)
- Label: "biz"
- Title: "Small business technology that works — and that you own."
- Hover: amber accent
- Link: `https://biz.christophergoulet.com`

**Door 2 — tech**
- Icon: `#g-arch` (stacked layers)
- Label: "tech"
- Title: "Resilient sovereign infrastructure for people who know what that means."
- Hover: cool blue accent
- Link: `https://tech.christophergoulet.com`

**Door 3 — canada**
- Icon: `#g-herit` (fleur-de-lis abstracted)
- Label: "canada"
- Title: "Retrouver vos racines — finding your way home."
- Hover: muted clay accent
- Link: `https://canada.christophergoulet.com`

**Door 4 — civic**
- Icon: `#g-comm` (radiating people)
- Label: "civic"
- Title: "Community resilience starts with people who show up."
- Hover: sage green accent
- Link: `https://civic.christophergoulet.com`

**Door behavior:** Each door's accent color is a preview of the subdomain's color scheme. No shared widget chrome — the doors themselves carry the visual identity of what's behind them.

**Responsive:** 2×2 on desktop, 1×4 on mobile (stacked)

### Booking Panel
- Same book-panel pattern (framed with bar and amber top border)
- Title: "The first call is free."
- Body: "Not sure which door is yours? A 20-minute conversation is all it takes to find out."
- CTA: "Book a free call" → `https://cal.com/christophergoulet`
- Secondary: `me@christophergoulet.com`

### Footer
- Row of subdomain links: biz, tech, canada, civic
- Meta: "Windsor, Vermont · EN · FR · © 2026"

## Design Direction

**Reference:** heydonworks.com — simplicity with attitude conveyed in few words.

**What makes this page feel like itself:**
- Minimal. No hero animation, no scroll reveal, no stats, no canvas
- The four doors ARE the page. Each one previews its subdomain's color
- The only motion is the door hover (translateY(-3px), accent bar scales in)
- Font scale: serif for the identity line (Fraunces), mono for labels, sans for body
- Selection color: amber (same as biz subdomain — default/apex color)

**What NOT to include:**
- No mesh canvas
- No boot sequence
- No stats panel
- No archive
- No about section
- No "who I am" text
- No pull quotes

## Bilingual

The apex does NOT need a bilingual toggle. The "EN · FR" in the footer signals multilingual capacity; the Canada subdomain is where the toggle lives.

## Tech Note

Single-file HTML. Inline CSS. Inline SVG defs for the four icons. No JS needed except the mobile nav toggle — no scroll reveal, no mesh canvas, no UTC clock, no boot animation.

The current `index.html` can be replaced entirely. This spec supersedes it.
