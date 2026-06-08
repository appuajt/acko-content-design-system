# ACKO Content Design System — Project Instructions

## Project
This is the ACKO Content Design System (CDS) microsite. A single-file HTML reference site (`index.html`) and a standalone quiz (`quiz.html`) for product designers. Served locally on port 4321.

## ACKO Design System
When building any UI, always follow ACKO's design system. The skill and rules are loaded automatically — reference them for tokens, components, and patterns.

@.claude/rules/acko-setup.md

## Key design tokens in use
- Brand purple: `#6841E6`
- Font: Euclid Circular B (files in `Font/`, CDN at `pub-c050457d48794d5bb9ffc2b4649de2c1.r2.dev`)
- Grey scale: `#0A0A0A`, `#141414`, `#474649`, `#7A7B7D`, `#E0E0E1`, `#F5F5F5`
- Radii: 4px (sm) → 6px (md) → 8px (lg) → 10px (xl) → 20px (4xl)

## Content conventions
- ACKO voice pillars: Assuring, Plainspoken, Insightful, Transparent
- ACKO is always "we" and "our" in customer-facing copy
- No passive voice, no jargon, no overpromising
- Sentence case everywhere (CTAs, headings, labels)

## Files
- `index.html` — main CDS microsite (single file, all CSS + JS inline)
- `quiz.html` — standalone UX writing quiz (20 questions, phone mockups)
- `Font/` — Euclid Circular B font files (Regular, Medium, SemiBold, Bold)
- `.claude/rules/acko-setup.md` — ACKO component setup rule
- `.claude/skills/acko-design-system/` — full design system skill (SKILL.md + 14 reference files)
