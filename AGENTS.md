# Marathon-Inspired Web Art Direction

## Purpose

This skill defines a visual and interaction system for creating modern websites inspired by the artistic and graphic-design principles associated with Bungie's **Marathon**.

The objective is NOT to reproduce Marathon's official website, UI, logos, characters, artwork, faction symbols, or proprietary assets.

Instead, extract and reinterpret the underlying design principles:

* Strong graphic identity
* Geometric forms
* Futuristic industrial design
* Product-design aesthetics
* Editorial composition
* High-contrast visual hierarchy
* Technological interfaces
* Controlled asymmetry
* Organic elements contrasted with engineered structures
* Bold typography
* Worldbuilding through graphics
* Minimal but deliberate decoration
* Distinctive iconography
* Strong use of negative space
* Interfaces that feel like artifacts from an existing fictional world

The final result must be an ORIGINAL web design.

---

# 1. Core Design Philosophy

Think like a graphic designer and art director before thinking like a frontend developer.

Every visual element must have a reason to exist.

Avoid:

* Generic cyberpunk aesthetics
* Generic neon sci-fi
* Excessive glowing effects
* Random HUD elements
* Excessive gradients
* Stock-looking futuristic graphics
* Generic AI-generated sci-fi imagery
* Decorative elements without semantic purpose
* Excessive glassmorphism
* Excessive rounded cards
* Conventional SaaS layouts
* Overloaded interfaces

Prefer:

* Strong silhouettes
* Flat or restrained color fields
* Hard geometric divisions
* Industrial materials
* Typography as a visual element
* Technical labeling
* Structured grids
* Deliberate asymmetry
* Large graphic elements
* Editorial layouts
* Visual tension
* Controlled imperfections
* Functional decoration
* Repeated graphic motifs

The website should feel designed rather than decorated.

---

# 2. Visual Keywords

Use these concepts as a design vocabulary:

```text
industrial
futuristic
graphic
editorial
geometric
technical
organic
experimental
asymmetrical
brutalist
precise
mechanical
tactical
institutional
architectural
modular
dense
minimal
contrasting
unusual
worldbuilding
```

Do not interpret these keywords as permission to add every possible effect.

Select a small number of dominant characteristics and build consistency around them.

---

# 3. Design Hierarchy

Every page should establish a clear hierarchy:

```text
PRIMARY
↓
Main visual / title / concept

SECONDARY
↓
Supporting information

TERTIARY
↓
Metadata / technical information

DECORATIVE
↓
Graphic elements supporting the world
```

Decorative elements must never compete with the primary content.

The user must understand the page's purpose within approximately 1–2 seconds.

---

# 4. Layout System

Prefer asymmetric layouts over perfectly centered compositions.

Use:

* Large horizontal sections
* Offset columns
* Overlapping elements
* Variable-width containers
* Strong vertical divisions
* Technical sidebars
* Large empty areas
* Full-width visual sections
* Editorial grids
* Modular blocks

Example:

```text
┌───────────────────────────────────────────────┐
│ LOGO                         SYSTEM / 07      │
├───────────────┬───────────────────────────────┤
│               │                               │
│               │       MAIN TITLE              │
│   METADATA    │                               │
│               │       Supporting text         │
│               │                               │
├───────────────┴───────────────────────────────┤
│                                               │
│                 VISUAL                        │
│                                               │
├───────────────────────────────┬───────────────┤
│ INFORMATION                   │ DATA          │
└───────────────────────────────┴───────────────┘
```

Do not make every section symmetrical.

---

# 5. Grid

Use a strict underlying grid even when the final composition appears chaotic.

Recommended:

* 8px base spacing
* 12-column desktop grid
* 4–6 column tablet grid
* 2–4 column mobile grid

Maintain consistent:

* margins
* gutters
* typography spacing
* component dimensions
* alignment rules

Graphic irregularity should exist on top of structural precision.

---

# 6. Typography

Typography is one of the primary visual components.

Prioritize:

* Condensed sans-serif
* Geometric sans-serif
* Technical grotesk
* Monospaced fonts for metadata
* Bold display typography

Use a maximum of 2–3 font families.

Example hierarchy:

```text
DISPLAY
Large condensed / bold

BODY
Neutral sans-serif

TECHNICAL
Monospace
```

Use typography to create visual rhythm.

Examples:

```text
SYSTEM 04
────────────

ARCHIVE

BIOLOGY

SECTOR 07

STATUS // ACTIVE

ENTRY 00421
```

Technical labels should be short.

Do not fill the interface with meaningless pseudo-technical text.

---

# 7. Typography Rules

Large titles should often be:

* uppercase
* tightly spaced
* bold
* oversized
* partially cropped
* aligned against unusual boundaries

However, readability always takes priority.

Avoid:

* excessive letter spacing
* extremely small text
* long paragraphs in uppercase
* decorative fonts for body text

---

# 8. Color System

Use a restrained palette.

Base palette:

```text
PRIMARY BACKGROUND
Near-black / charcoal

SECONDARY BACKGROUND
Dark industrial gray

PRIMARY TEXT
Off-white

SECONDARY TEXT
Muted gray

ACCENT
One dominant saturated color

WARNING / STATUS
Optional secondary accent
```

Do not automatically use cyan, purple and magenta.

The color palette should be determined by the project's identity.

Possible accent families:

```text
orange
red
yellow
acid green
blue
industrial white
```

Use one dominant accent rather than creating a rainbow sci-fi interface.

---

# 9. Color Proportion

Recommended approximate distribution:

```text
70–85% neutral surfaces
10–20% secondary tones
3–10% accent color
```

Accent colors should guide attention.

Use them for:

* active states
* important information
* navigation
* borders
* indicators
* selected elements
* key graphics

Do not use the accent color everywhere.

---

# 10. Shapes and Geometry

Favor:

* rectangles
* trapezoids
* angular cuts
* diagonal divisions
* thin technical lines
* segmented borders
* asymmetric frames
* modular panels

Rounded corners should be used sparingly.

Avoid excessive:

```css
border-radius: 9999px;
```

unless the component deliberately represents a circular or capsule-like object.

---

# 11. Borders

Borders are an important graphic language.

Use:

* 1px technical borders
* partial borders
* interrupted borders
* corner brackets
* double-line structures
* diagonal cuts

Example:

```text
┌─────────────────────
│ MODULE 04
│
│ CONTENT
│
└─────────────────────
```

Avoid putting a complete rounded border around every component.

---

# 12. Graphic Motifs

Create a small set of recurring motifs.

Examples:

```text
crosshair
grid
coordinates
sector markers
technical lines
registration marks
bars
brackets
angular cuts
small geometric symbols
measurement indicators
```

These motifs should form a coherent visual language.

Never randomly add HUD decorations to empty space.

---

# 13. Worldbuilding Through Web Design

The interface should imply that it belongs to a larger world.

Instead of:

```text
ABOUT
SERVICES
CONTACT
```

when appropriate, consider contextual terminology such as:

```text
ARCHIVE
DATABASE
INDEX
SYSTEM
SECTOR
CATALOG
FIELD NOTES
RECORDS
LOG
PROTOCOL
```

However, do not sacrifice usability.

Navigation labels must remain understandable.

---

# 14. Content Architecture

The design must support long-form content.

For educational or documentation websites, prioritize:

```text
TITLE
↓
INTRODUCTION
↓
CONTEXT
↓
MAIN CONTENT
↓
RELATED INFORMATION
↓
REFERENCES
```

Do not turn every paragraph into a UI panel.

Long-form reading requires calm sections with strong typography.

Use the visual language primarily for:

* headers
* metadata
* navigation
* diagrams
* tables
* callouts
* section transitions

The article itself should remain highly readable.

---

# 15. Hero Sections

A hero section should establish the identity immediately.

Recommended structure:

```text
[TECHNICAL LABEL]

MAIN TITLE

Short contextual description

[PRIMARY ACTION] [SECONDARY ACTION]

        LARGE VISUAL
```

The visual can use:

* abstract geometry
* original illustrations
* scientific imagery
* architectural forms
* diagrams
* generated artwork

Avoid copying official Marathon imagery.

---

# 16. Image Treatment

Images should feel integrated into the graphic system.

Use:

* cropped compositions
* monochrome treatments
* duotone treatments
* hard rectangular frames
* asymmetric masks
* overlays
* technical annotations
* controlled grain
* geometric clipping

Do not apply the same filter to every image.

The treatment should reinforce the subject.

---

# 17. Image Composition

Prefer images with:

* strong silhouettes
* large shapes
* unusual perspective
* architectural geometry
* negative space
* controlled visual noise

Avoid compositions that are visually busy without a clear focal point.

---

# 18. UI Components

Components should belong to the same visual system.

Recommended components:

```text
Navigation
Hero
Section Header
Article Header
Technical Metadata
Data Card
Image Panel
Timeline
Grid
Table
Callout
Status Indicator
Tabs
Accordion
Search
Pagination
Footer
```

Each component should have:

* primary state
* hover state
* focus state
* active state
* disabled state
* mobile behavior

---

# 19. Cards

Do not create a card for everything.

Use cards when content represents an independent information unit.

Prefer:

```text
┌────────────────────────────
│ 04 / BIOLOGY
│
│ CELLULAR STRUCTURES
│
│ Short description
│
│ OPEN →
└────────────────────────────
```

rather than:

```text
╭────────────────────────────╮
│ Everything inside a card   │
╰────────────────────────────╯
```

Cards should feel like modules, records or objects rather than generic SaaS containers.

---

# 20. Navigation

Navigation should be highly functional.

Desktop:

```text
LOGO
│
├── INDEX
├── ARCHIVE
├── CATEGORIES
├── SEARCH
└── SYSTEM
```

Possible secondary navigation:

```text
SECTION
  ├── CATEGORY
  ├── SUBCATEGORY
  └── CURRENT PAGE
```

Use visual indicators for the active location.

---

# 21. Search Interface

Search should feel like an information system rather than a generic search bar.

Example:

```text
SEARCH DATABASE

[ ENTER QUERY........................ ]

RESULTS // 028

01  ASTRONOMY
02  STELLAR EVOLUTION
03  GALAXIES
04  COSMOLOGY
```

For large content systems, emphasize:

* keyboard navigation
* instant results
* category filters
* hierarchical context
* result metadata

---

# 22. Interaction Design

Animations should communicate structure.

Good animations:

* panel expansion
* navigation transitions
* loading indicators
* data reveal
* image transitions
* subtle parallax
* section entry
* cursor states
* progress indicators

Avoid:

* constant background movement
* excessive particle effects
* aggressive camera movement
* animations on every element
* long transition durations

Recommended general transition range:

```text
120ms – 350ms
```

Large cinematic transitions may exceed this when justified.

---

# 23. Hover States

Hover states should reinforce the system.

Examples:

```text
border appears
accent line expands
text shifts slightly
metadata becomes visible
image crops change
technical indicator activates
```

Avoid excessive:

```text
scale(1.2)
glow
blur
neon shadow
```

---

# 24. Motion Language

Motion should feel:

```text
mechanical
precise
controlled
fast
intentional
```

Avoid:

```text
bouncy
cartoonish
excessively elastic
random
```

Use easing curves appropriate to the action.

---

# 25. Responsive Design

The visual identity must survive mobile layouts.

Never simply shrink the desktop interface.

Desktop:

```text
asymmetric
multi-column
large visuals
dense metadata
```

Mobile:

```text
single-column
strong hierarchy
reduced decoration
accessible typography
simplified metadata
```

Preserve:

* typography hierarchy
* accent language
* geometric identity
* technical motifs
* visual rhythm

Remove unnecessary decoration when space becomes limited.

---

# 26. Accessibility

The visual style must not compromise accessibility.

Required:

* sufficient contrast
* keyboard navigation
* visible focus states
* semantic HTML
* accessible labels
* readable font sizes
* reduced-motion support
* screen-reader compatibility

Never use color as the only indicator.

---

# 27. Technical Implementation

When implementing the design, prioritize:

```text
semantic HTML
CSS variables
design tokens
responsive CSS
component reuse
accessible interactions
performance
progressive enhancement
```

Create design tokens such as:

```css
--background
--surface
--surface-secondary
--foreground
--muted
--accent
--border
--font-display
--font-body
--font-mono
--spacing-unit
```

Do not hardcode dozens of unrelated values.

---

# 28. Design Tokens

Before implementing a major interface, establish:

```text
COLORS
TYPOGRAPHY
SPACING
BORDERS
SHADOWS
MOTION
BREAKPOINTS
GRID
```

Example:

```text
Background: near-black
Surface: dark gray
Text: off-white
Muted: gray
Accent: project-specific
Border: low-contrast
Display font: condensed
Body font: neutral sans-serif
Technical font: monospace
```

---

# 29. Avoid Generic AI Design

The agent must actively reject visual clichés.

Do NOT automatically produce:

* neon blue cyberpunk
* glowing cyan borders
* purple gradients
* floating glass cards
* random circular HUDs
* excessive scanlines
* fake terminal text
* random coordinates
* meaningless numbers
* unnecessary grids
* generic space backgrounds

Every decorative element must answer:

> What purpose does this element serve?

If the answer is "it looks futuristic", remove it or redesign it.

---

# 30. Originality Rules

The design may be inspired by Marathon's artistic principles but must remain original.

Do not reproduce:

* Marathon logos
* Bungie logos
* official faction logos
* official characters
* official UI layouts
* exact promotional compositions
* proprietary symbols
* recognizable artwork
* copied typography treatments
* exact color arrangements from official artwork

Instead:

```text
extract principle
↓
reinterpret principle
↓
introduce project identity
↓
create new geometry
↓
create new symbols
↓
validate originality
```

---

# 31. Project Identity Layer

Before designing a website, identify:

```text
PROJECT NAME
PROJECT PURPOSE
TARGET AUDIENCE
SUBJECT
PRIMARY COLOR
SECONDARY COLOR
SYMBOL
VISUAL METAPHOR
TONE
CONTENT STRUCTURE
```

The Marathon-inspired visual system is the FOUNDATION.

The project's own identity is the CONTENT.

Never allow the reference aesthetic to completely replace the project's identity.

---

# 32. Art Direction Workflow

For every new page:

### Step 1 — Understand the content

Determine:

```text
What is this page?
Who uses it?
What information matters most?
What action should the user take?
```

### Step 2 — Establish hierarchy

Define:

```text
primary
secondary
tertiary
decorative
```

### Step 3 — Define composition

Choose:

```text
grid
alignment
visual focal point
negative space
section rhythm
```

### Step 4 — Define visual language

Choose:

```text
geometry
color
typography
borders
imagery
motifs
```

### Step 5 — Design components

Only create components that serve the content.

### Step 6 — Add motion

Animation comes after layout.

### Step 7 — Responsive adaptation

Design mobile deliberately.

### Step 8 — Art-direction review

Evaluate the final design using the checklist below.

---

# 33. Art Direction Review

Score each category from 0–5.

```text
Visual identity       /5
Typography            /5
Composition           /5
Color discipline      /5
Graphic language      /5
Originality           /5
Usability             /5
Accessibility         /5
Responsive behavior   /5
Worldbuilding         /5
```

A design should not be considered finished if:

```text
Visual identity < 3
Usability < 4
Accessibility < 4
Originality < 4
```

---

# 34. Final Quality Questions

Before delivering a design, ask:

1. Does the page have a recognizable visual identity?
2. Is the hierarchy obvious?
3. Does the composition feel intentional?
4. Are geometric elements supporting the content?
5. Is typography doing meaningful visual work?
6. Is the accent color controlled?
7. Are decorative elements necessary?
8. Does the design feel futuristic without becoming generic cyberpunk?
9. Does it contain an original identity rather than copying Marathon?
10. Does it remain readable for long sessions?
11. Does the mobile version retain the visual language?
12. Are animations purposeful?
13. Can the interface plausibly belong to a larger fictional or institutional system?
14. Would removing a decorative element improve the design?
15. Does the design still work without visual effects?

---

# 35. Output Expectations

When asked to create a website, interface, page, component, or visual system:

1. Analyze the content.
2. Establish the information hierarchy.
3. Define the visual concept.
4. Define the layout.
5. Define typography.
6. Define color usage.
7. Define graphic motifs.
8. Design the components.
9. Implement responsive behavior.
10. Add restrained interaction.
11. Perform an originality check.
12. Perform an accessibility check.
13. Perform an art-direction review.

Do not begin by adding decorative effects.

Begin with composition, hierarchy and identity.

---

# 36. Core Principle

The final design should communicate:

> **A sophisticated technological world expressed through graphic design, industrial forms, editorial composition and deliberate visual systems.**

It should feel like a designed artifact from a coherent universe—not like a generic "futuristic website."

Marathon is the reference point.

The project's own identity is the destination.

---

# 37. Corporate Visual Art Direction (Marathon Identity System)

The corporate graphic identity in Marathon is defined by high-contrast visual branding, dry graphic surfaces, and heavy industrial typography.

Interfaces and layouts must feel like functional artifacts produced by fictional megacorporations (e.g., Traxus Heavy Industries, Sekiguchi Genetics, UESC, NuCaloric, Synthetic Genesis, NuCore).

Every layout should feel like a piece of corporate industrial design rather than a software SaaS template.

---

# 38. Dry Matte Finish & Surface Rules ("Acabado Seco")

### Strict Material Rules:
* **Zero Gloss & Zero Bloom**: No neon glow (`box-shadow: 0 0 20px cyan`), no drop shadows, no blur, and no glassmorphism backdrop-blur.
* **Opaque Color Fields**: Surfaces must be flat, high-contrast, opaque fields (matte charcoal `#0D0D0E`, chalk white `#F4F4F0`, safety orange `#FF5500`, industrial yellow `#E5A900`, slate gray `#242629`).
* **Screen-Print & Industrial Stencil Texture**: Micro-grain textures, hard pixel/halftone dots, and physical screen-printed graphic art aesthetics.
* **Hard Cut Contours**: Containers use sharp 0px border-radii or aggressive 45° polygon chamfers (`clip-path: polygon(...)`).

---

# 39. Modular Geometric Typography & Display Systems

Typography is the core visual hero. Use heavy geometric construction inspired by custom corporate display typefaces:

### 1. NuCore Geometric Display Archetype
* **Traits**: Hard square blocks, extreme vertical weight, stencil gaps, zero rounded curves.
* **Usage**: Main page titles, sector indicators, massive graphic background lettering.

### 2. UESC Institutional Display Archetype
* **Traits**: Sharp 45° chamfered corners, high-density monospaced data blocks, rigid institutional alignment.
* **Usage**: Data tables, navigation headers, system status badges (`STATUS // OPERATIONAL`, `UESC_DIR_904`).

### 3. Synthetic Genesis Display Archetype
* **Traits**: Asymmetric stencil cuts, razor-sharp geometric angles, bio-technical specimen specs.
* **Usage**: Section headers, feature highlights, scientific data panels.

### 4. NuCaloric Tactical Packaging Archetype
* **Traits**: Bold industrial product labels, hazard stripes (`repeating-linear-gradient`), caution badges, technical ingredient/spec grids.
* **Usage**: Cards, callout containers, interactive buttons, technical action triggers.

---

# 40. Corporate Branding Layout Archetypes

When designing pages or components, adopt one of the following corporate design identities:

```text
┌─────────────────────────────────────────────────────────────┐
│ [NC-SPEC // 04]  NUCALORIC HEAVY INDUSTRIES  [VERIFIED]      │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  ███╗   ██╗██╗   ██╗██╗      ██████╗ ██████╗ ██████╗        │
│  ████╗  ██║██║   ██║██║     ██╔═══██╗██╔══██╗██╔════╝        │
│  ██╔██╗ ██║██║   ██║██║     ██║   ██║██████╔╝█████╗          │
│  ██║╚██╗██║██║   ██║██║     ██║   ██║██╔══██╗██╔══╝          │
│  ██║ ╚████║╚██████╔╝███████╗╚██████╔╝██║  ██║███████╗        │
│  SYS_ID: 9940-AX  //  SEC_LEVEL: ALPHA  //  STATUS: DRY      │
├───────────────────────────────┬─────────────────────────────┤
│ TECHNICAL SPECIFICATIONS      │ DATA MATRIX                 │
│ ▫ Chamfered hard borders      │ [01] RAW GEOMETRY           │
│ ▫ Flat matte contrast         │ [02] NO NEON / NO GLOW      │
│ ▫ Stencil typography cutouts  │ [03] INDUSTRIAL ACCENTS     │
└───────────────────────────────┴─────────────────────────────┘
```

1. **High Contrast Vector Blocking**: Massive black-on-white or white-on-dark contrast zones with razor-sharp division lines (`2px-4px solid`).
2. **Functional Labeling & Serial Numbers**: Every section must feature short technical metadata identifiers (e.g., `REG-884/TRX`, `BATCH_ID_0029`).
3. **Structured Hazard & Technical Accents**: Restrained use of solid safety orange or industrial yellow for active elements, borders, and status tags.

