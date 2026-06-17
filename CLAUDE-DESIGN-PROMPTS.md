# Claude Design prompts — Michael Florian personal site

_Generated 2026-06-16. Goal: get 4 visually distinct, anti-slop directions to compare, then pick one._

## How to use this

Claude Design builds one design per prompt. So:

1. Open Claude Design, start a **new project**.
2. Paste **SHARED CORE** (below) **+** one **DIRECTION** block (A, B, C, or D).
3. Repeat for each direction in its own project.
4. Compare all four. Pick the one that feels like you. We then hand-edit tokens on the winner (never re-prompt from scratch, that re-rolls to the generic mean).

The SHARED CORE keeps the content, voice, and anti-slop rules identical across all four, so you are comparing **look**, not substance.

---

## ▓▓ SHARED CORE — paste this first, every time ▓▓

```
You are designing a personal website. The brand name is "Michaels Corner". The
person behind it is Michael Florian. "Michaels Corner" is the wordmark/title;
Michael Florian is the human you meet on the site. Read every constraint before
you design. This is a real person's site, not a SaaS product. Restraint over
reflex.

WHO IT IS FOR
Michael is a builder who uses AI to ship software fast. He is not a classic
engineer. His edge is the combination of: shipping a lot, very fast (20+ real
projects built solo with AI); learning new tools quickly; and explaining AI in
plain language for normal people. Audience: non-technical founders, solo
entrepreneurs, and the broad AI-curious public. Many are non-native English
speakers.

WHAT THE SITE IS
A generous, useful resource hub. Not a sales funnel. People arrive from his
social media. The site gives things away:
  - Prompt routines: the actual prompts and workflows he uses, packaged to copy
  - Videos: links out to his YouTube
  - Tools: small calculators and utilities he built (e.g. a credit calculator)
  - Notes: short "what I'm learning" entries (optional, keep light)
  - About + connect: who he is, links to his socials (handle @michaelflorian_ai)

THE PROMISE / MESSAGE
"AI hasn't taken my job. It made me faster. I turn that into routines and tools,
then give them away so you can get the same leverage."

COPY RULES (write the real copy, do not use lorem ipsum)
  - First person. Short declarative sentences. Headlines under 8 words.
  - B2 English: common words, no idioms, no slang.
  - Generous, teaching, a little confident, still warm. Never corporate.
  - NO em dashes anywhere. Use commas and periods.
  - BANNED words/phrases: leverage, synergy, streamline, supercharge, seamless,
    powerful, sleek, modern, cutting-edge, world-class, enterprise-grade,
    "in today's landscape", "build X in minutes", "stop wrestling with",
    "not just X but Y", "say goodbye to", "unlock", and any unsourced metric
    like "10x" or "99.9%".

INFORMATION ARCHITECTURE
One idea per screen. Do NOT use the generic landing-page assembly line. Sections,
in a sensible order you choose:
  - An opening that says who he is and what he gives away (one strong idea)
  - Prompt routines (a real, browsable list, copy-to-clipboard feel)
  - Tools (small utilities, shown as real things not feature cards)
  - Videos (links to YouTube, presented editorially, not a thumbnail wall)
  - About + connect (short bio, social links)
There is NO pricing, NO testimonials, NO "trusted by" logo strip, NO newsletter
hero, NO contact-sales CTA.

HARD ANTI-SLOP RULES (apply to ALL directions, non-negotiable)
  - NEVER use Inter or Geist. NEVER use Space Grotesk, Cal Sans, or Instrument
    Serif as a "tasteful" fallback.
  - Max 2 type families. Max 2 weights per family. Real cuts, no faux bold/italic.
  - ONE accent color only. No gradients on hero, buttons, or backgrounds. No
    purple/indigo/violet. No "text-gradient". No glassmorphism / frosted blur.
  - No animated mesh, aurora, starfield, blur-orb, or dotted-grid-with-radial-
    fade backgrounds.
  - No Lucide icons at default stroke. NEVER the Sparkles + Brain + Zap trio.
    Prefer 1-2 custom hand-drawn glyphs or no icons.
  - No bento grid. No identical 3-column feature cards. No icon-tile-above-
    heading repeated. No numbered "01 / 02 / 03" unless truly sequential. No
    colored 3-4px left card border. No stat banner row.
  - No Aceternity/Magic UI components (BorderBeam, BentoGrid, Spotlight,
    MovingBorder, AnimatedTooltip).
  - Motion budget: two easing curves total. One signature transition for the
    whole site. NO fade-up-on-scroll on every section. No animated counters, no
    mouse-following spotlight, no magnetic buttons, no marquee, no scroll-jacking.
  - Hairlines and 1px borders over drop shadows. High contrast text (WCAG AA+).
  - Performance: self-host fonts, two weights max, keep it light.

Do NOT output this structure: eyebrow pill -> huge centered headline with an
italic-serif word -> two CTAs -> trusted-by strip -> 3-column features -> bento
grid -> testimonial -> stats -> pricing -> FAQ -> footer. If you find yourself
heading there, stop and rethink the layout.

The specific look (palette, fonts, layout personality, named reference) comes
from the DIRECTION block below.
```

---

## ── DIRECTION A — Bold & confident (editorial statement) ──

```
DIRECTION: Bold, confident, editorial. This site has a point of view and is not
afraid of it. Think the cover-confidence of Bloomberg Businessweek and the
type-led swagger of an editorial portfolio, NOT a startup landing page.

AESTHETIC FAMILY: editorial magazine confidence.
REFERENCE TASTE: borrow the oversized type hierarchy and asymmetric editorial
layout of early pitch.com, and the high-contrast restraint of vercel.com (but
warm, not black-and-amber).

TYPE:
  - Display/headlines: "Clash Display" (heavy weight, big). Self-host.
  - Body/UI: "General Sans" (regular + medium only).
LAYOUT:
  - Off-center hero, left-aligned, ragged right. Headline 72-110px. Break the
    grid: headline spans 8 columns, a short caption sits in a 4-column sidenote.
  - Negative space is a feature. Protect the whitespace.
  - Prompt routines as a confident editorial list/index, not cards.
PALETTE (one accent, high contrast):
  - Background: warm white #FAF7F2
  - Ink (text): near-black #15130F
  - Accent: muscle-car orange #F2541B  (provenance: Michael's Dodge Challenger.
    This is HIS color, not a generic accent. Use it sparingly and loud.)
MOTION: one signature only. A confident, quick text reveal on first load
(180ms ease-out), nothing on scroll.
RADIUS: max 4px. SHADOW: none, use 1px hairline rules.
PERSONALITY: declarative, a builder who shows receipts. The numbers (20+
projects) can be stated plainly and large, with no fake "10x" framing.
```

---

## ── DIRECTION B — Personal homepage (lived-in digital home) ──

```
DIRECTION: A real person's corner of the internet. Handmade, warm, lived-in. It
should feel like Michael arranged his desk and invited you in, not like a
product page. Personality over polish, on purpose.

AESTHETIC FAMILY: indie personal web / "small web" homepage.
REFERENCE TASTE: borrow the warm, content-first, no-decoration honesty of
robinmalfait.com and the playful-but-disciplined personal-site feel of paco.me.
Warmer and more hand-arranged than either.

TYPE:
  - Headings/body: "Satoshi" (medium + bold).
  - Captions/labels/meta: "IBM Plex Mono" (regular) for a handmade, notes feel.
LAYOUT:
  - Single flowing column or a relaxed two-column "desk" layout. Not centered-
    hero. Things laid out like a real homepage: a short hello, then lists of
    prompts, tools, videos, notes.
  - Hand-arranged, slightly irregular spacing is welcome. It should not look
    grid-perfect or templated.
PALETTE (one accent):
  - Background: warm cream #F4EFE6
  - Ink: #1E1B16
  - Accent: a hand-picked forest green #2F6B4F (calm, personal, not a SaaS color).
MOTION: almost none. One small, friendly hover lift on links. No scroll effects.
RADIUS: soft, up to 12px on small elements only.
PERSONALITY: warm, generous, a person not a brand. A single tasteful emoji in
the hello line is allowed here (and ONLY here). Short personal asides are good.
```

---

## ── DIRECTION C — Raw maker's lab (mono, shows the work) ──

```
DIRECTION: A builder's workshop. The work IS the aesthetic. Mono-led, plain-text
energy, terminal-but-warm. Anti-design as the design. Honest and dense, no
decoration.

AESTHETIC FAMILY: maker's lab / content-first mono.
REFERENCE TASTE: borrow the dense, no-nonsense, content-first discipline of
robinmalfait.com and the type-led minimalism of paco.me, rendered in monospace.

TYPE:
  - Primary: "JetBrains Mono" (regular + medium) for nearly everything.
  - Body long-form (optional, for readability): "General Sans" regular.
LAYOUT:
  - Looks like a well-kept index of a builder's work. Prompts and tools listed
    like directory entries. Generous line-height, locked measure 60-72ch.
  - No hero image. The opening is text: who he is, what he ships, what you can
    take.
PALETTE (near-monochrome, one restrained accent):
  - Background: paper #F5F3EE  (light, NOT muddy dark)
  - Ink: #161512
  - Accent: muted amber #B5731E (used only for links/active state). Absolutely
    no neon green.
MOTION: a single blinking cursor as the only signature motion. Nothing else.
RADIUS: 0 to 2px. SHADOW: none. Hairline dividers only.
PERSONALITY: confident maker, no fluff. Show counts and facts plainly. It should
feel like reading a sharp person's working notes.
```

---

## ── DIRECTION D — Warm analog / human (paper, real photos) ──

```
DIRECTION: Warm, human, print-like. Textured off-white paper, real photographs
of Michael, small handwritten or stamp-like touches. It should feel like a
person made it, closer to a zine than a SaaS site.

AESTHETIC FAMILY: warm editorial / print, human-first.
REFERENCE TASTE: borrow the warm-neutral palette, oversized editorial headlines,
and commissioned-photography feel of family.co. Use real photos of Michael (the
profile photo in assets/profile.jpg is a starting point) as art, never stock.

TYPE:
  - Display/headlines: "Fraunces" (a characterful serif, use its optical/soft
    settings, one bold weight).
  - Body/UI: "General Sans" (regular + medium).
LAYOUT:
  - Editorial. A real photo of Michael bleeding off the page edge as the opening.
  - Magazine devices: pull-quotes, sidenotes, mono captions under images.
  - Prompts and tools presented like articles/entries in a personal magazine.
PALETTE (one accent):
  - Background: paper #F2ECE1 (subtle paper texture allowed, very light)
  - Ink: #211C16
  - Accent: stamp red #B23A2E (provenance: a passport/journal stamp, ties to the
    "figuring it out in public" story). Used sparingly.
MOTION: gentle and restrained. One soft entrance on the hero photo. Nothing on
scroll.
RADIUS: small, photo corners can be square or 2px.
PERSONALITY: warm, honest, a real human guiding you. Handwritten-feel accents
sparingly (one or two, not everywhere).
```

---

## After you pick

Tell me which direction won (or which mix). Then:
- We lock the chosen palette/fonts into `brand/BRAND.md` under "Visual identity".
- We hand-edit tokens on the winning design instead of re-prompting.
- We decide build/host (likely Vite + Netlify under off-plate org, per the usual setup).
