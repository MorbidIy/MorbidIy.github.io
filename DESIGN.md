# NestJS Landing Page — Design System Specification

---

## Layout

The page is a single 1280px container (32px side padding) on Soot Canvas, punctuated by full-bleed rounded frames inset 40px from the viewport edge. The hero is one such 32px-radius glowing frame holding a floating 80px nav bar, a centred two-line 112px headline, a 14px mono subline, a centred button pair and right-aligned mono stats. Below, a five-column logo wall leads to split statement blocks (48px heading left, mono note right), a fan of overlapping square cards, and a 3000px-tall scroll-revealed 128px statement over a starfield. Three stacked 1520px showcase frames (Observe, Devtools, Deploy) follow, then a hairline 3-column service grid, a split syntax section, a crimson stats band, testimonials, a tiered sponsor grid and a grain-textured footer slab. Section gaps run 80–160px, so density is spacious despite compact mono copy.

---

## Imagery

Imagery is product UI and light. The three showcase frames hold real dark-mode application screenshots (logs, a dependency graph, deployment metrics) set inside a pale bezel with 12px top-rounded corners, lit by white and crimson radial glows. Feature cards carry small chrome, wireframe-like 3D objects; course cards glow in jewel tones (crimson, magenta, teal, violet) on black. There is no lifestyle photography beyond small square avatar portraits in testimonials. Brand logos are rendered monochrome white, icons are thin white line glyphs, and atmosphere comes from canvas-drawn animated gradients, a twinkling starfield, film grain and a glowing red arc.

---

## Lean into

- Use Soot Canvas `#050303` as the page field everywhere; lift panels only to Carbon Panel `#0b0b0b` and Graphite Slab `#181818`.
- Set display type in Manrope 500 at 0px tracking: 48px/56px section headings, 112px/0.95 hero lines and 128px/1.1 statements.
- Set all running copy in Geist Mono 14px/300 at 24px line-height, including hero sublines and feature descriptions.
- Apply Nest Crimson `#ea2845` as light: radial and linear glows fading through Garnet `#780f20` to Soot Canvas inside 32px-radius frames.
- Reserve the Bone White `#ffffff` fill for the single primary button per section, at 20px radius and 20px padding.
- Keep section labels as uppercase 12px/300 Geist Mono eyebrows in braces with a trailing underscore: `{ SUPPORT }_`.
- Build grids from 1px seams at `rgba(255, 255, 255, 0.15)` or Ash Seam `#1e1c1c` instead of filled cards.

---

## Steer clear of

- Do not fill buttons, badges or text with flat Nest Crimson `#ea2845`; red lives in the logo and the glows.
- Do not set headlines bold; Manrope stays at 500 even at 128px and 160px.
- Do not add negative tracking to the display sizes; the site measures 0px at every Manrope size.
- Do not switch paragraphs to a sans; body copy is light 300-weight Geist Mono.
- Do not use soft drop shadows for separation; use tonal steps and 1px translucent-white outlines.
- Do not square off frames or buttons; keep 32px frames, 24px cards and inputs, and 20px buttons.
- Do not use a cool blue-black as the canvas; keep the warm red-tinged Soot Canvas `#050303`.

---

## Component Specifications

### Floating Glass Nav Bar — Top site navigation inside the hero frame

An 80px-high bar inset in the hero frame: 60%-black fill over the crimson glow, 32px radius, 20px padding. Crimson cat logo at left, centred 16px/500 Manrope Bone White links with a chevron on Tools, white social glyphs at right. No shadow.

### Crimson Glow Hero Frame — Opening hero panel

A full-width frame inset 40px from the viewport with a 32px radius, filled with a drifting Nest Crimson `#ea2845` to Garnet `#780f20` to Soot Canvas `#050303` glow. Centre a 112px/500 Manrope Bone White headline at 0.95 line-height, then 14px/300 Geist Mono copy and the button pair.

### Bone White Button — Primary call to action

Bone White `#ffffff` fill with a black 16px/700 Manrope label at 24px line-height, 20px radius and 20px padding for a 64px-high block. No border, no shadow; it is the only bright filled control on the page.

### Ghost Text Button — Secondary hero action

Transparent fill, Bone White `#ffffff` 16px/700 Manrope label, 20px padding and 20px radius so it aligns with the Bone White Button beside it; an optional leading play glyph for video links. No outline.

### Ash Seam Button — Secondary filled action on dark sections

Ash Seam `#1e1c1c` fill with a Bone White 16px/700 Manrope label, 20px radius and 20px padding, 64px high. Used for Official documentation beside the syntax panel. No border, no shadow.

### Bracketed Mono Eyebrow — Section label above headings

Uppercase Geist Mono at 12px/300 with 16px line-height and -0.3px tracking in Pewter Text `#9b9a9a`, wrapped in curly braces with a trailing blinking underscore: `{ WHAT IS NEST }_`. Sits 16px above a 48px/500 Manrope heading.

### Split Statement Block — Section intro with heading and side note

A 48px/500 Manrope Bone White heading at 56px line-height spanning the left half of the 1280px container, with a 14px/300 Geist Mono paragraph at 24px line-height in the right third, top-aligned. No card, straight on Soot Canvas `#050303`.

### Fanned Feature Card — Overlapping capability cards

Square 350px Graphite cards with a top-lit gradient, 24px radius, a 1px `rgba(255, 255, 255, 0.2)` Smoke Outline `#373535` edge and a `0 4px 10px rgba(0, 0, 0, 0.2)` shadow. Fan them with slight rotations; centre a chrome 3D icon over a 20px/600 Manrope label.

### Product Showcase Frame — Observe, Devtools and Deploy panels

A 1520px frame with a 32px radius: a 60px/500 Manrope title and 14px/300 Geist Mono subline over a bezel-framed app screenshot, then a Graphite Slab `#181818` strip of three 22px/500 tab titles whose inactive state fades to Pewter, each over a 4px-radius progress line.

### Syntax Code Window — Tabbed code sample

A Carbon Panel `#0b0b0b` window with 24px top radii and a 1px Smoke Outline `#373535` edge, a tab row of 16px/600 Manrope labels, and 16px/300 Geist Mono code at 40px line-height using Coral Keyword `#ff7b72`, Amber String `#ffa657` and Frost Identifier `#a5d6ff`.

### Hairline Service Grid — Enterprise support feature grid

A 3-column grid with a 20px outer radius on the corner cells and 1px `rgba(255, 255, 255, 0.15)` seams, 320px-high cells on Soot Canvas `#050303`, each with a white line icon above an 18px/500 Manrope Bone White label. No fills, no shadow.

### Crimson Stats Band — Download and star counts

A 32px-radius frame with the same crimson-garnet glow as the hero: a 72px/500 Manrope statement at left and a 160px/500 Manrope figure at right with 12px/300 Geist Mono captions, smaller 48px figures beneath. Bone White text only.

### Sponsor Logo Grid — Tiered sponsor wall

Square 160px cells joined by 1px Ash Seam `#1e1c1c` borders, monochrome white logos centred in each, with a 12px Geist Mono `{ 1 }_` eyebrow and a 24px/500 Manrope tier name at the left of each row.

### Pill Newsletter Field — Footer e-mail signup

A 66px-high input with `rgba(255, 255, 255, 0.122)` fill and matching 1px border, 24px radius, 24px 20px padding and an uppercase 12px/400 Geist Mono placeholder; an Iron Gray `#4e4e4e` 22px-radius Subscribe button with a 14px/600 Manrope label sits inside the right end.

### Grain Slab Footer — Site footer

A Graphite Slab `#181818` frame with 32px top radii and film grain: a 96px/400 Manrope npm command whose letters fade from Pewter to white, then a 1px-seamed split with the newsletter at left and four link columns of 14px/600 Manrope under 12px Geist Mono uppercase headers.

---

## Agent Prompt Guide

```
Quick Color Reference:
- Soot Canvas: #050303 — page background behind every section
- Bone White: #ffffff — headlines, body copy and the primary button fill
- Nest Crimson: #ea2845 — logo and the hot core of every glow
- Garnet Sweep: #780f20 — midpoint of the crimson-to-soot frame gradients
- Graphite Slab: #181818 — syntax section, editor body, footer slab
- Carbon Panel: #0b0b0b — bordered code window body
- Ash Seam: #1e1c1c — secondary button fill and grid seams
- Smoke Outline: #373535 — 1px translucent-white card outlines
- Pewter Text: #9b9a9a — muted mono labels and inactive tabs
- Iron Gray: #4e4e4e — newsletter Subscribe button
- Coral Keyword: #ff7b72 — code keywords
- Amber String: #ffa657 — code strings
- Frost Identifier: #a5d6ff — code function names

Create a hero frame inset 40px from the viewport with a 32px radius and a Nest Crimson #ea2845 to Garnet #780f20 to Soot Canvas #050303 glow, a centred 112px/500 Manrope Bone White headline at 0.95 line-height, a 14px/300 Geist Mono subline and a 20px-radius Bone White button with a 16px/700 label beside a ghost text button.
Create a floating nav bar 80px high with a 60%-black fill, 32px radius and 20px padding: logo left, centred 16px/500 Manrope white links, white social icons right.
Create a section intro on Soot Canvas #050303 with an uppercase 12px/300 Geist Mono { WHAT IS NEST }_ eyebrow in Pewter Text #9b9a9a, a 48px/500 Manrope heading at 56px line-height on the left and a 14px/300 Geist Mono note at 24px line-height on the right.
Create a 3-column enterprise grid of 320px cells joined by 1px rgba(255, 255, 255, 0.15) seams with a 20px outer radius, each cell holding a white line icon and an 18px/500 Manrope label, no fills or shadows.
Create a code window on Carbon Panel #0b0b0b with 24px top radii and a 1px Smoke Outline #373535 edge, 16px/600 Manrope tabs, and 16px/300 Geist Mono code at 40px line-height coloured Coral Keyword #ff7b72, Amber String #ffa657 and Frost Identifier #a5d6ff.
```

---

## Gradient System

```
Colour arrives as light. The hero frame and stats band use a canvas-animated blob glow measured as linear-gradient(to right in oklab, rgb(234, 40, 69) 0%, rgb(120, 15, 32) 50%, rgb(5, 3, 3) 100%) and its symmetric soot-garnet-soot variant, so Nest Crimson #ea2845 always burns in a corner and fades through Garnet #780f20 to Soot Canvas #050303. Showcase frames swap in white radial glows (radial-gradient(circle at 50% 60%, #ffffff, transparent 30%)) and 200deg crimson or grey washes. Course cards get their own jewel-tone radial tops. Never flatten these into solid red fills.
```

---

## Motion Philosophy

```
Durations cluster at 0.3s (40 occurrences) and 0.15s (29) on cubic-bezier(0.4, 0, 0.2, 1) (41) and ease-in-out (27), mostly animating opacity (29) and filter (27). The large moves are scroll-driven: the 128px statement lights up word by word from grey to white, the npm command in the footer brightens across its letters, the feature cards fan out, and the hero glow drifts on a 30s blob loop. Showcase tabs auto-advance with a thin progress line.
```