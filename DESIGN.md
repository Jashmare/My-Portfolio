---
name: Prince Mosqueda Portfolio
description: Claim and proof. One neutral scale, one lime signal, real course screens in soft frames.
colors:
  page: "#F7F7F5"
  surface-quiet: "#EFEFEC"
  hairline: "#E4E4E0"
  hairline-strong: "#CFCFCA"
  text-secondary: "#5E5E59"
  ink: "#111111"
  paper: "#FFFFFF"
  on-ink: "#F7F7F5"
  lime-signal: "#B5D334"
  ground-light: "#EDEDEA"
  portrait-ground: "#DCDCD7"
  dark-page: "#0F0F0E"
  dark-surface-quiet: "#171716"
  dark-hairline: "#262624"
  dark-hairline-strong: "#3A3A36"
  dark-text-secondary: "#A8A8A1"
  dark-ink: "#F2F2EE"
  dark-paper: "#1B1B19"
  inverse-hairline: "#2E2E2B"
  inverse-text-secondary: "#9E9E97"
  inverse-lede: "#B4B4AD"
  viewer-counter: "#BDBDB6"
  status-error: "#E5484D"
typography:
  display:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, -apple-system, Segoe UI, sans-serif"
    fontSize: "clamp(2.6rem, 5.6vw, 4.6rem)"
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: "-0.028em"
  headline:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(2rem, 4vw, 3.1rem)"
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: "-0.028em"
  title:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.5rem, 2.4vw, 2rem)"
    fontWeight: 700
    lineHeight: 1.12
    letterSpacing: "-0.022em"
  title-compact:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.25rem, 1.8vw, 1.5rem)"
    fontWeight: 700
    lineHeight: 1.12
    letterSpacing: "-0.022em"
  lede:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.1rem, 1.5vw, 1.25rem)"
    fontWeight: 400
    lineHeight: 1.55
  claim:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.1875rem"
    fontWeight: 400
    lineHeight: 1.5
  channel-value:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.05rem, 1.8vw, 1.35rem)"
    fontWeight: 500
    letterSpacing: "-0.01em"
  body:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.9688rem"
    fontWeight: 500
    lineHeight: 1.6
  label-small:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 500
  inverse-small:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.9063rem"
    fontWeight: 500
  caption:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.6
  initial-fallback:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 700
rounded:
  bar: "2px"
  focus: "6px"
  marker: "0.12em"
  control-xs: "8px"
  control: "10px"
  button: "12px"
  frame: "14px"
  panel: "20px"
  closing-panel: "28px"
  pill: "999px"
spacing:
  gutter: "clamp(1rem, 4vw, 2.5rem)"
  wrap: "1240px"
  header: "68px"
  header-mobile: "60px"
  row: "0.7rem"
  group: "2rem"
  section: "clamp(5rem, 10vw, 8.5rem)"
  work-gap: "clamp(5rem, 10vw, 8rem)"
  head-gap: "clamp(3rem, 6vw, 5rem)"
  more-row-gap: "clamp(3rem, 6vw, 5rem)"
  more-column-gap: "clamp(2rem, 4vw, 4rem)"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-ink}"
    typography: "{typography.label}"
    rounded: "{rounded.button}"
    padding: "0 1.4rem"
    height: "52px"
  button-primary-small:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-ink}"
    typography: "{typography.label-small}"
    rounded: "{rounded.control}"
    padding: "0 0.95rem"
    height: "40px"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.button}"
    padding: "0 1.4rem"
    height: "52px"
  icon-button:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    size: "40px"
  back-to-top:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-ink}"
    rounded: "{rounded.frame}"
    size: "48px"
  back-to-top-on-dark:
    backgroundColor: "{colors.dark-ink}"
    textColor: "{colors.ink}"
    rounded: "{rounded.frame}"
    size: "48px"
  nav-link:
    textColor: "{colors.text-secondary}"
    typography: "{typography.label}"
    rounded: "{rounded.control-xs}"
    padding: "0.5rem 0.8rem"
  nav-link-hover:
    backgroundColor: "{colors.surface-quiet}"
    textColor: "{colors.ink}"
  proof-frame:
    rounded: "{rounded.panel}"
    padding: "0"
  proof-sheet:
    backgroundColor: "{colors.surface-quiet}"
    rounded: "{rounded.control}"
  more-work-title:
    textColor: "{colors.ink}"
    typography: "{typography.title-compact}"
  more-work-claim:
    textColor: "{colors.text-secondary}"
    typography: "{typography.body}"
  count-chip:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    typography: "{typography.caption}"
    rounded: "{rounded.pill}"
    padding: "0.45rem 0.75rem"
  gallery-dialog:
    backgroundColor: "{colors.paper}"
    rounded: "{rounded.panel}"
  toast:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-ink}"
    rounded: "{rounded.button}"
    padding: "0.8rem 1.1rem"
  copy-button:
    backgroundColor: "transparent"
    textColor: "{colors.dark-ink}"
    typography: "{typography.inverse-small}"
    rounded: "{rounded.control}"
    padding: "0 0.85rem"
    height: "38px"
---

# Design System: Prince Mosqueda Portfolio

## Overview

**Creative North Star: "Claim and Proof"**

A monochrome product-marketing world in which every statement is followed by the screen that proves it. The chrome is quiet: one warm-neutral scale from near-white to near-black, set in Satoshi and tightly tracked, with headings in Title Case and everything you read or click in sentence case. The work itself (real e-learning screens, adverts, illustration) carries all the colour on the page; the site contributes only ink, paper, hairlines and a single lime signal.

Density is calm and generous. A 5/7 column split (claim left, proof right) repeats from the hero down through the featured work pairs, section heads, About and Contact, so the page reads as one steady argument; smaller collections follow in a compact two-column grid of proof, title and claim. Proof sits directly on the page, unframed, as screens with one soft shadow, and it moves: frames rise into place as they enter, and hovering a proof fans its next two screens out from behind the first.

Grouped information is tabular, never card-tiled: disciplines, spec lists, toolkit groups, values and contact channels are all hairline rows. The page closes on an inverse ink panel that holds the contact details.

**Key Characteristics:**
- One neutral scale plus one lime accent; the work supplies every other colour.
- Satoshi only, three weights with fixed jobs (700 display, 500 UI and labels, 400 running copy).
- Title Case headings over sentence-case reading and UI copy.
- Recurring 5/7 claim/proof grid for featured work; a compact 2-column grid for smaller collections.
- Hairline rows for any grouped list.
- Screens with 14px corners and a single soft shadow, placed straight on the page ground (no containing box); lift and fan on hover.
- Exponential ease-out on every movement; content visible without JS.

## Colors

A warm, slightly yellowed neutral ramp with one acid-lime signal that is rationed to marks, not surfaces.

### Primary
- **Lime Signal** (`lime-signal`): the live dot on primary buttons (a ring that fills on hover and focus), the 5px active-section dot in the nav, the toast status dot, the copy-confirmed check, text selection and the halo around the focus ring (the ring itself is ink, for contrast). It never fills a surface or a button.

### Neutral
- **Warm Page** (`page`): the page ground and the text colour on ink.
- **Quiet Surface** (`surface-quiet`): nav hover wash, image placeholders, gallery stage, toolkit row hover.
- **Hairline** (`hairline`): every divider row, frame borders, chip borders.
- **Strong Hairline** (`hairline-strong`): ghost button stroke, table header rule, link underlines at rest, scrollbar thumb.
- **Secondary Text** (`text-secondary`): supporting copy, labels in spec lists, nav links at rest, captions, More Work claims (about 6:1 on the page).
- **Ink** (`ink`): headings, body, primary buttons, the back-to-top button, toast.
- **Paper** (`paper`): gallery dialog, count chips, gallery arrow buttons; the white inside of a frame.
- **Ground** (`paper` to `ground-light`): the radial gradient `radial-gradient(120% 90% at 30% 20%, paper 0%, ground-light 70%)`, kept as a token; work proofs no longer sit on it (the owner asked for the boxes around projects to be removed).
- **Portrait Ground** (`portrait-ground`, rising to #F1F1EE at the top centre): the About portrait's radial backdrop. It stays light in both themes on purpose, so the cutout's pale fringe disappears into it; do not theme it dark.

### Dark theme
Dark mode swaps the same roles in place: `dark-page`, `dark-surface-quiet`, `dark-hairline`, `dark-hairline-strong`, `dark-text-secondary`, `dark-ink` (text), `dark-paper` (frames and dialog), and `on-ink` becomes near-black. The lime signal is unchanged in both themes.

### Inverse panel
The closing Contact panel is ink in light mode and `dark-paper` in dark mode, with `dark-ink` text, `inverse-lede` for its lede, `inverse-text-secondary` for channel labels and footer, and `inverse-hairline` for its rows. Its primary button inverts to a light fill with ink text. The panel is fixed-dark in both themes, so its `dark-ink` and `inverse-text-secondary` values are written as literals rather than theme variables; that is intentional.

### Fullscreen viewer
- **Viewer Counter** (`viewer-counter`): the image counter on the fixed-dark fullscreen viewer, in both themes.

### Status
- **Error Red** (`status-error`): only the toast dot when a copy fails.

### Named Rules
**The One Signal Rule.** Lime marks state and liveliness: dots, active marks, focus, selection. If lime is covering an area or colouring words, it is wrong. One owner-approved exception: in the hero headline "Ideas, Drawn to Be Understood." the word "Understood" sits on a lime marker at 60% (a band from 14% to 94% of the line, 0.12em corners, cloned across line breaks). No other word gets it.

**The Work Owns Colour Rule.** Chrome is neutral so the course screens are the only saturated thing on the page. Tool marks in the toolkit keep their real brand colours at 22px for recognition; that is the one sanctioned exception.

## Typography

**Display Font:** Satoshi (with ui-sans-serif, system-ui, Segoe UI fallback)
**Body Font:** Satoshi
**Label Font:** Satoshi at 500

**Character:** A single geometric-grotesque family doing all the work through weight and tracking. Headlines are heavy and tight; UI is medium; reading copy stays regular for legibility.

### Hierarchy
- **Display** (700, clamp(2.6rem, 5.6vw, 4.6rem), 1.05, -0.028em): the hero statement only, held to about 11ch on desktop.
- **Headline** (700, clamp(2rem, 4vw, 3.1rem), 1.05): section titles (Selected Work, More Work, Toolkit, the About and Contact statements).
- **Title** (700, clamp(1.5rem, 2.4vw, 2rem), 1.12, -0.022em): featured project titles. More Work titles use the compact title (clamp(1.25rem, 1.8vw, 1.5rem)); toolkit group and About value titles step down to 1.25rem and 1.125rem.
- **Lede** (400, clamp(1.1rem, 1.5vw, 1.25rem), 1.55): the one supporting sentence under a headline, in secondary text, about 34 to 40ch.
- **Claim** (400, 1.1875rem, 1.5): the featured project claim line, in ink, 38ch. In More Work the claim drops to body size in secondary text.
- **Body** (400, 1.0625rem, 1.6): running copy, capped at 44 to 60ch.
- **Label** (500, 0.9688rem to 1rem): buttons, nav, spec values, tool names, disciplines.
- **Label small** (500, 0.9375rem): the small CV button in the nav, gallery and viewer counters.
- **Channel value** (500, clamp(1.05rem, 1.8vw, 1.35rem), -0.01em): email, phone and LinkedIn on the contact panel.
- **Inverse small** (500 or 400, 0.9063rem): copy buttons and footer on the contact panel.
- **Caption** (400 or 500, 0.875rem): proof captions, table headers, count chips. Numerals in counters use tabular figures.
- **Initial fallback** (700, 0.8125rem): the letter shown in place of a tool mark that fails to load.

### Named Rules
**The Weight Has A Job Rule.** 700 for headings, 500 for anything you click or scan, 400 for anything you read. No other weights.

**The Title Case Heading Rule.** Headings and subheaders are Title Case with negative tracking: section titles, project titles, project claim lines, discipline names, toolkit group names and the toolkit table header ("Tool / Used For"), About value headings. Running body copy, descriptions, buttons, links and labels stay sentence case. No uppercase labels, no letterspaced small caps.

## Layout

A centred 1240px wrap with a fluid gutter. The structural move is a 5fr/7fr split used for the hero, section heads (title left, intro right, bottom-aligned), every featured work pair, About and Contact; featured pairs alternate which side holds the claim. Smaller collections follow in the More Work grid: two equal columns, rows separated by clamp(3rem, 6vw, 5rem) and columns by clamp(2rem, 4vw, 4rem), with no top padding so it reads as a continuation of Selected Work. The hero proof stack bleeds past the wrap to the viewport's right edge. The toolkit uses a 4/8 split (group name and purpose left, table right).

Vertical rhythm is large: sections at clamp(5rem, 10vw, 8.5rem), work pairs separated by clamp(5rem, 10vw, 8rem), section heads followed by clamp(3rem, 6vw, 5rem). Sections after Work drop their top padding so the rhythm is carried by the previous section's bottom.

Responsive: at 980px every split collapses to one column and every proof precedes its claim; disciplines go from 5 columns to 3, then 2 at 760px, then a single label/value list at 480px. At 760px the header drops to 60px, nav links become a full-width sheet revealed by a clip-path wipe, the CV button collapses to its icon and dot, hero CTAs stretch to fill the row, the More Work grid drops to one column, and the gallery goes edge to edge.

The sticky header is translucent page colour (86%) with a saturating blur and gains a hairline bottom border once scrolled.

## Elevation & Depth

Hybrid: surfaces are flat and separated by hairlines; only images of the work and floating controls get shadow. Depth comes from overlap (frames stacked and offset) more than from shadow strength.

### Shadow Vocabulary
- **Soft** (`box-shadow: 0 18px 40px -18px rgba(17,17,17,0.28), 0 2px 6px rgba(17,17,17,0.06)`): every screen at rest, the back-to-top button at rest, the primary button on hover, gallery arrow buttons.
- **Lift** (`box-shadow: 0 30px 60px -22px rgba(17,17,17,0.34), 0 4px 10px rgba(17,17,17,0.08)`): the front screen of a stack, a hovered proof sheet, the hovered back-to-top button, the toast.
- Dark theme uses the same geometry at rgba(0,0,0,0.7/0.4) and rgba(0,0,0,0.8/0.5).

### Named Rules
**The One Soft Shadow Rule.** A screen or a floating control gets the soft shadow; the one in front gets the lift. Text blocks, rows and panels get none.

## Shapes

Softly rounded, never pill-shaped except for small chips and dots. Screens use 14px corners (10px inside work proofs); dialogs use 20px; the floating back-to-top button shares the 14px screen radius. Controls step down: 12px buttons, 10px small buttons, icon buttons and copy buttons, 8px nav links and thumbnails. Count chips are full pills. Circles are reserved for dots, the avatar and gallery arrow buttons. The closing Contact panel rounds only its top corners (28px), reading as a sheet pulled up over the page. The smallest radii are functional: 6px on the focus ring, 2px on the menu bars, 0.12em on the hero marker so it scales with the headline.

Borders are 1px hairlines throughout. Icons are one custom stroke set: 24px grid, 1.75 stroke, round caps and joins, drawn at 18px.

## Components

### Buttons
Solid and quiet, with one lively detail.
- **Shape:** gently rounded (12px), 52px tall; small variant 40px at 10px radius.
- **Primary:** ink fill, page-coloured text, label weight, a leading 16px lime ring (the live dot) and a trailing directional icon.
- **Hover / Focus:** rises 2px and gains the soft shadow; the lime ring fills from the centre; the arrow nudges 4px in its direction (down for scroll and download, right for forward). Press scales to 0.97. Focus everywhere is a 2px ink outline at 3px offset with a 6px lime halo at 55%.
- **Ghost:** transparent with a strong-hairline stroke; hover darkens the stroke to ink and rises 2px. Ghost buttons carry no dot.
- **Icon button:** 40px square, hairline stroke, 10px radius; hover strokes in ink.
- **Text link:** medium weight with a 1px strong-hairline underline at 0.3em offset that darkens on hover while the trailing icon's gap opens.
- **Back to top:** a 48px ink square (14px radius, soft shadow, up arrow) fixed bottom-right at clamp(1rem, 3vw, 2rem). Hidden until the page has scrolled about 0.8 of a viewport, then rises in from 16px below at 0.9 scale; hover rises 3px with the lift shadow and nudges the arrow up; press scales to 0.94. Over the contact panel it flips to a light fill with an ink arrow so it stays visible.

### Chips
- **Count chip:** paper pill with hairline border, caption size, an images icon plus the count, pinned bottom-right of each proof's front screen; rises 2px with the proof hover.

### Cards / Containers
There are no content cards. Two containers exist:
- **Proof:** an unframed, borderless button (no background) holding up to three sheets (screens at 14px or 10px radius, soft shadow). Layout variants: screens (stacked back-right), posters (portrait adverts fanned side by side), art (illustration on a paper sheet).
- **Dialog:** paper, 20px radius, header bar with hairline bottom, 16:9 stage on quiet surface, thumbnail strip, description plus spec list.

### Navigation
Wordmark (700, 1.125rem) left; links (Home, Work, Toolkit, About, Contact) in label weight, secondary text, 8px-radius hover wash; the current section turns ink and gets a 5px lime dot centred beneath it (right-aligned in the mobile sheet); More Work counts as Work. Right side: theme toggle icon button and the small primary CV button. Mobile uses a three-bar button that morphs to a cross. The wordmark, the Home link, the footer's "Back to top" link and the floating back-to-top button all return to the top of the page.

### Hairline Row Lists
The world's idiom for any grouped information: spec lists (label column 7.5rem, value in 500), toolkit tables (header in caption over a strong hairline, rows on hairlines, second column in secondary text, row hover a horizontally faded quiet-surface wash with the tool mark scaling to 1.12), disciplines (columns separated by vertical hairlines), values and contact channels.

### Proof Stack and Fan (signature)
Screens overlap as physical sheets. In the hero three frames sit layered and bleed off the right edge (the course template (Blue_Design_Main, header bar cropped) in front with the lift shadow, Cotton behind, the Sales course at the back); on hover they drift apart. In each work pair, hover or keyboard focus on the proof lifts the front sheet (translate, -1.2deg, lift shadow) and fans the two behind it up and to the right at increasing rotation and full opacity. Clicking opens the gallery, then fullscreen. On entry each proof rises 48px from 0.97 scale over 1.2s; it is never hidden while waiting.

### More Work Grid
The compact register for smaller collections: the same claim-and-proof logic at lower volume. Each item is an unframed proof (the front screen flush with the title's left edge, the count chip kept on the image), then a compact Title Case title, a muted claim (secondary text, 40ch) and an "Open gallery" text link. Proofs fan on hover and open the same gallery as the featured pairs. Two columns; one at 760px and below.

### Toast
Ink pill-rectangle (12px) sliding up from the bottom centre with a lime dot (red on failure), lift shadow.

## Do's and Don'ts

### Do:
- **Do** follow every featured claim with its proof in the 5/7 split, alternating sides down the page; put smaller collections in the 2-column More Work grid.
- **Do** set headings, subheaders, project titles and claim lines in Title Case, and keep running copy, buttons and labels in sentence case.
- **Do** keep lime to dots, active marks, focus and selection.
- **Do** place screens straight on the page with the soft shadow and give the frontmost one the lift; do not wrap work in a bordered box.
- **Do** use hairline rows for any grouped list, including tools, specs and contact channels.
- **Do** use the single exponential ease-out (`cubic-bezier(0.16, 1, 0.3, 1)`) for movement, and keep content visible when motion is reduced or JS is absent.
- **Do** use weights 700, 500 and 400 only, for display, UI and reading respectively.

### Don't:
- **Don't** use lime as a fill, a text colour or a background.
- **Don't** tile content into identical icon cards; group it as a hairline table instead.
- **Don't** introduce a second accent colour in the chrome; colour comes from the work.
- **Don't** shadow text panels, rows or in-flow buttons at rest; only floating controls (the back-to-top button) carry the soft shadow at rest.
- **Don't** set UI text in uppercase or add letterspaced labels above headings.
- **Don't** use decorative blobs, arcs, tilted stat badges or marquees; the only overlap and rotation belong to stacked screens.
