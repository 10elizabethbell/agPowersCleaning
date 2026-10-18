---
name: A&G Power's Cleaning Services
description: A window you clean yourself; New Jersey sunshine through freshly wiped glass, over deep teal.
colors:
  deep-teal: "#0f3b40"
  teal-slate: "#2c5a5e"
  fresh-ground: "#f4f8f6"
  mint-wash: "#dff1ea"
  squeegee-aqua: "#0b7770"
  sponge-yellow: "#ffc94d"
  rinse-line: "#c9ddd6"
  field-sage: "#789a93"
  on-dark: "#eaf6f2"
  on-dark-muted: "#b9d8d1"
  frame-white: "#fbfdfc"
  surface-white: "#ffffff"
  error-text: "#a3262a"
  error-stroke: "#c4474b"
typography:
  display:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(40px, 11.4vw, 88px)"
    fontWeight: 900
    lineHeight: 0.94
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(30px, 8vw, 52px)"
    fontWeight: 900
    lineHeight: 1.02
    letterSpacing: "-0.02em"
  title:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "clamp(20px, 5.6vw, 28px)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.01em"
  title-step:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "24px"
    fontWeight: 800
    lineHeight: 1.2
    letterSpacing: "0"
  body:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    lineHeight: 1.1
  note:
    fontFamily: "system-ui, -apple-system, \"Segoe UI\", Roboto, \"Helvetica Neue\", Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.55
rounded:
  hint: "8px"
  field: "12px"
  pane: "18px"
  pill: "999px"
  circle: "50%"
spacing:
  gutter-phone: "16px"
  gutter-wide: "32px"
  stack: "26px"
  heading-gap: "22px"
  field-gap: "18px"
  section-top-phone: "60px"
  section-bottom-phone: "80px"
  section-top-desk: "96px"
  section-bottom-desk: "110px"
  container: "1160px"
components:
  button-primary:
    backgroundColor: "{colors.deep-teal}"
    textColor: "{colors.surface-white}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "58px"
  button-primary-hover:
    backgroundColor: "{colors.squeegee-aqua}"
    textColor: "{colors.surface-white}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.deep-teal}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 24px"
    height: "58px"
  button-ghost-hover:
    textColor: "{colors.squeegee-aqua}"
  service-row:
    textColor: "{colors.deep-teal}"
    typography: "{typography.title}"
    padding: "12px 2px"
    height: "72px"
  row-arrow:
    backgroundColor: "{colors.mint-wash}"
    textColor: "{colors.deep-teal}"
    rounded: "{rounded.circle}"
    size: "46px"
  row-arrow-hover:
    backgroundColor: "{colors.squeegee-aqua}"
    textColor: "{colors.surface-white}"
  step-number:
    backgroundColor: "{colors.sponge-yellow}"
    textColor: "{colors.deep-teal}"
    rounded: "{rounded.circle}"
    size: "52px"
  chip:
    backgroundColor: "{colors.surface-white}"
    textColor: "{colors.deep-teal}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "46px"
  chip-selected:
    backgroundColor: "{colors.deep-teal}"
    textColor: "{colors.surface-white}"
  input:
    backgroundColor: "{colors.surface-white}"
    textColor: "{colors.deep-teal}"
    rounded: "{rounded.field}"
    padding: "13px 15px"
    height: "54px"
  instagram-card:
    backgroundColor: "{colors.deep-teal}"
    textColor: "{colors.surface-white}"
    rounded: "{rounded.pane}"
    padding: "18px 20px"
    height: "64px"
  header-phone:
    textColor: "{colors.deep-teal}"
    typography: "{typography.label}"
    padding: "0 4px"
    height: "44px"
---

# Design System: A&G Power's Cleaning Services

## Overview

**Creative North Star: "The Window Mid-Clean"**

The whole system is one moment: a dusty pane in a white-painted frame, a yellow kitchen sponge halfway across it, soap bubbles drifting off the wipe, and morning sky showing through where the glass is clean. Everything else on the page is the room around that window. Mint and a fresh off-white ground do the airing-out; deep teal is the solid, trustworthy floor; sponge yellow is the one warm thing, and it only shows up where something is being counted, tapped or pointed to.

The page is phone-first and dense in the useful way: one column, big tap targets (44px minimum, 58px for primary actions), heavy uppercase headings that read at a glance in a Facebook in-app browser, and plain sentence-case body copy at 17px. Section edges are not straight lines; each band opens with an animated wet wave, the edge a squeegee leaves. Motion belongs to the world (wiping, bubbles, wet seams) and never to the UI chrome: buttons and rows change colour, they do not fly in.

Typography uses the platform's own sans (the stack in `--font`), set very heavy and tight for display. Depth is almost entirely tonal: colour bands, not cards. The single lifted object is the window itself.

**Key Characteristics:**
- One signature object: the wipeable window pane, with a canvas sky, grime layer, clean mask, sponge and bubbles.
- Tonal section bands (ground, mint, deep teal) joined by animated wavy seams.
- Heavy uppercase system-sans display over 17px sentence-case body.
- Pills for actions and choices, circles for markers, 18px rounded rectangles for objects.
- Every conversion path ends in a pre-written text message to one phone number.

## Colors

A cool, rinsed palette: deep teal and mint carry the page, aqua marks interaction, and a single sponge yellow supplies warmth.

### Primary
- **Deep Teal** (deep-teal): body text on light grounds, the dark "How it works" band and footer, primary button fill, selected chips, the Instagram card, and the brand mark square. Also the `theme-color`.
- **Squeegee Aqua** (squeegee-aqua): the interaction colour. Hover on buttons, rows, inputs, chips and the header phone link; the focus ring; the input caret; the phone icon; the one emphasised word in the hero headline.

### Secondary
- **Sponge Yellow** (sponge-yellow): warmth, used sparingly and almost always against deep teal. Step numerals, footer link icons and hover, the Instagram card arrow on hover, the "A&G" monogram letters, and text selection (yellow behind deep-teal text). The canvas sponge body is drawn in the same family (#ffd866 to #efb534).

### Neutral
- **Fresh Ground** (fresh-ground): the page ground and the services and estimate bands. Fresh, deliberately not pure white.
- **Mint Wash** (mint-wash): the hero gradient's lower stop, the "Our promise" band, resting row-arrow circles, and the form's "message ready" panel.
- **Teal Slate** (teal-slate): secondary text on light grounds (the promise line, notes, ledes, definitions, "optional" tags, wordmark subtitle).
- **Rinse Line** (rinse-line): hairline dividers between service rows.
- **Field Sage** (field-sage): resting borders of inputs and chips; chosen for 3:1 against white.
- **On Dark / On Dark Muted** (on-dark, on-dark-muted): primary and secondary text inside deep-teal bands. Headings inside dark bands go to pure white.
- **Frame White** (frame-white): the painted window frame and mullions, and the window trim in the canvas house.
- **Surface White** (surface-white): input and chip fills, text on deep-teal buttons and cards.
- **Error** (error-text, error-stroke): validation message text and the invalid field border. Only in the form.

### Named Rules
**The Sun On Teal Rule.** Sponge yellow is a fill or an icon colour on deep teal, or a highlight behind deep-teal text. It is never used as text on the light grounds, where it fails contrast.

**The Aqua Means Touch Rule.** Squeegee aqua is the answer to a pointer or focus. Outside the single emphasised hero word, an element is aqua only because someone is hovering, focusing or typing into it.

## Typography

**Display Font:** system-ui (with -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif)
**Body Font:** same stack
**Label/Mono Font:** same stack; phone numbers use tabular numerals

The system stack is a rule, not a fallback: Ellie's pitch-site house style (fast on cellular, no font downloads) overrides Impeccable's craft-floor refusal of system display faces. Keep it on future pages for this client unless Ellie changes it.

**Character:** One family carrying two registers. Display is weight 900, uppercase and pulled tight (negative tracking, sub-1 leading) so headlines feel like a bold shopfront sign; body is a relaxed 17px/1.55 in sentence case.

### Hierarchy
- **Display** (900, clamp 40-88px, 0.94, -0.035em, uppercase): the hero slogan only. One word may take squeegee aqua with no italic.
- **Headline** (900, clamp 30-52px, 1.02, -0.02em, uppercase, 22px below): section headings. The footer business name uses the same treatment at clamp 26-40px.
- **Title** (800, clamp 20-28px, uppercase, -0.01em to -0.02em): service rows and promise terms.
- **Step Title** (800, 24px, 1.2, sentence case, no tracking): the three "How it works" steps.
- **Body** (400, 17px, 1.55): all running copy; measures held to 34-46ch.
- **Label** (800, 17px): buttons, form labels, the header phone number; chips use 700.
- **Note** (15px): fine print, error messages, the window hint, footer service area, the Instagram handle. Nothing in the page body goes smaller.

### Named Rules
**The Seventeen Rule.** Body copy, form controls, labels and button text are 17px on every viewport, so iOS never zooms an input and the page reads at arm's length. 15px is the floor for secondary notes.

**The Shout And Talk Rule.** Headings shout (uppercase, 800-900, tight); everything a person reads as a sentence talks (sentence case, 400-500). Step titles are the deliberate bridge: heavy but sentence case.

## Layout

Phone-first single column inside a 1160px container with a 16px gutter (32px from 720px). Sections are full-bleed colour bands with generous vertical padding (56-60px top, 76-80px bottom on phones; 96px / 110px at 1024px+). The 26px stack gap recurs across the hero grid, steps and promise list; form fields sit 18px apart.

Responsive steps:
- **Base (phone):** everything stacks; hero actions are full-width stacked buttons; the window sits under the headline at clamp(260px, 72vw, 340px) tall.
- **max-width 380px (small phones):** the header tightens (34px mark, 14px/11px wordmark lines held on one line, 15px phone number) so wordmark and number never wrap or collide.
- **720px:** gutters grow to 32px; hero actions cap at 380px wide; service rows flow into two columns (56px column gap); steps and promise terms go to three columns.
- **1024px:** the header grows to 84px; the hero splits 1.05fr / 1fr with the window beside the headline at min(540px, 62vh); the estimate section splits 0.8fr / 1.2fr with its heading column sticky.

The script mirrors the 720px line (`innerWidth < 720`) to pick phone brush size, bubble count and canvas resolution, and uses `(hover: hover) and (pointer: fine)` to decide whether a service row texts or jumps to the form.

## Elevation & Depth

Depth is tonal: bands of fresh ground, mint and deep teal, with the hero ground fading into mint. Cards, rows, steps and form panels are flat. The window pane is the single lifted object, because it is a physical thing in the world: a soft teal-tinted drop shadow under the pane, an inset shadow inside its painted frame so the glass sits recessed, and a small shadow under each mullion. The canvas sponge casts its own soft shadow onto the glass.

### Shadow Vocabulary
- **Pane lift** (`box-shadow: 0 18px 40px -18px rgba(15,59,64,.45), 0 2px 6px rgba(15,59,64,.12)`): the window only.
- **Frame recess** (`box-shadow: inset 0 0 0 1px rgba(15,59,64,.08), inset 0 6px 14px rgba(15,59,64,.18)`): inside the painted frame.
- **Mullion** (`box-shadow: 0 3px 8px rgba(15,59,64,.18)`): the cross bars.
- **Field focus** (`box-shadow: 0 0 0 3px rgba(11,119,112,.22)`): a soft aqua halo on focused inputs, paired with an aqua border.

### Named Rules
**The One Window Rule.** Only the window (and objects drawn on its glass) casts shadows. All shadows are tinted deep teal, never neutral black. New surfaces are flat colour bands or flat rounded panels.

## Shapes

Three shape families, each with a job. Pills (999px) for anything you press or pick: buttons and chips. Circles for markers: row arrows (46px), step numerals (52px). Softly rounded rectangles for objects: the window and the Instagram card at 18px (`--radius`), inputs at 12px, the window hint at 8px; the message-ready panel uses 14px. Focus outlines carry a 6px radius so the ring follows the element.

Section boundaries are the one non-geometric form: a 40px-tall SVG wave (viewBox 1200x40, stretched) overlapping 38px into the section above, filled with the colour of the section it opens. Borders are 2px for controls and buttons, 1px hairlines for row dividers, 12px painted white for the window frame.

## Components

### Buttons
Confident, chunky pills that read as thumbs-sized.
- **Shape:** full pill (999px), 2px deep-teal border, 58px minimum height, 24px side padding, 10px gap to a 20px stroke icon.
- **Primary:** deep teal fill, white 800-weight 17px text. Used for "Text us for a free estimate" and "Text this to A&G".
- **Ghost:** transparent with deep-teal border and text; the secondary choice beside a primary, and the copy/open actions after the form.
- **Hover / Focus:** colour transitions at 0.2s; primary goes aqua fill and border, ghost turns its border and text aqua. Press scales to 0.98 (disabled under reduced motion). Focus is a 3px aqua outline at 3px offset. Inside the form, the submit keeps its teal fill on hover and shows the aqua ring instead.

### Header Phone Link
The number is always visible top-right on every viewport: 800-weight 17px, tabular numerals, no wrap, an 18px aqua phone icon, 44px tap height. Hover turns it aqua. Paired with the wordmark (40px deep-teal monogram square with yellow "A&G", two-line uppercase name) on a 68px header (84px at 1024px+).

### Service Rows
A list, not a grid of cards.
- **Style:** full-width rows, 72px minimum, title type, separated by 1px rinse-line hairlines; two columns from 720px.
- **Arrow-only hover:** the row itself never changes (no background, no shadow, no outline); only the 46px mint arrow circle fills aqua with a white arrow. Keyboard focus puts the 3px aqua ring on the arrow, not the row.
- **Behaviour:** on touch devices each row is an `sms:` link with a service-specific pre-written message; on fine-pointer devices it ticks that service in the form and scrolls there.

### Steps
Three numbered steps in the dark band. CSS-counter numerals in 52px sponge-yellow circles (900, 22px, deep teal), white step titles, muted on-dark body. Numeral beside text on phones; numeral above text in three columns from 720px.

### Promise List
A definition list on mint: uppercase title-weight terms, teal-slate definitions held to 44ch, 26px apart; three columns from 720px.

### Instagram Card
A flat deep-teal 18px panel (64px min height, 18px/20px padding) with 19px 800-weight white text, a muted 15px handle beneath, and a translucent white arrow circle that turns sponge yellow with a deep-teal arrow on hover. It is the only deep-teal panel on a light band.

### Chips
- **Style:** pill radio buttons, 46px tall, 16px padding, white fill, 2px field-sage border, 700-weight 17px text; native input visually hidden.
- **State:** hover turns the border aqua; selected fills deep teal with white text (an aqua border on hover while selected); focus is the 3px aqua ring at 2px offset; invalid turns the border error-stroke.

### Inputs / Fields
- **Style:** white fill, 2px field-sage border, 12px radius, 54px minimum (textarea 104px, vertical resize), 500-weight 17px text, aqua caret. Labels sit above at 800 weight; "(optional)" is 500 in teal slate.
- **Focus:** aqua border plus the soft aqua halo; no outline.
- **Error:** border goes error-stroke and a 700-weight 15px error-text message appears below in plain words.

### Estimate Handoff
The form never submits to a server. Validation runs on name, service and town; on success the page composes a plain multi-line message, opens the texting app with it, and reveals a mint panel showing the message in the body face with ghost "Copy message" and "Open texting app" buttons as a fallback. A 15px note under the button states nothing is sent until the visitor presses send.

### Footer
Deep-teal band opened by its own wave seam. Business name in headline treatment, the slogan in muted on-dark, then 44px links (call or text, Instagram) with 20px sponge-yellow icons that turn the link text yellow on hover, and a 15px service-area line.

### The Wipeable Window (signature)
A recessed pane in a 12px painted frame with cross mullions, built from stacked canvases: **sky** (morning gradient #2f93d6 to #bfe4f1, sun glow, radial-puff clouds, a neighbour's house in frame white and deep teal, a two-tone green treeline), **grime** (an off-screen dirt canvas of dusty film, smudges, bottom-heavy grime, water spots, specks and drip streaks, punched through by a half-resolution clean **mask** with `destination-out`), and **fx** above the frame (a pre-rendered yellow sponge with green scrub side that tilts and squashes with velocity, and soap bubbles spawned by fast wipes that drift up, wobble and scatter from the finger). The cursor is hidden over the pane; the sponge is the cursor.

Behaviour lives in the tunables at the top of `windowPane()`: film regrowth per frame (0.0008), specks landing back per frame (3), brush radius as a share of the short side (0.15 phone / 0.11 desktop), idle time before the sponge wipes on its own (3500ms), auto-wipe speed (0.55), bubble cap (46, halved on phones), mask scale (0.5). Device pixel ratio is capped at 2 on phones and 1.5 on desktop. A "Drag to wipe the window" hint (15px white on translucent deep teal, 8px radius) fades out on first touch. Resizes that do not change the pane's size are ignored so a phone's moving address bar never resets the wipe.

### Wet Seams (signature)
Each section and the footer open with an SVG wave whose path is rewritten every frame from three summed sines (speed 1.1, amplitude 9, 40 points), offset per seam so no two move alike.

### Motion
All animation runs through one shared `requestAnimationFrame` loop that stops itself when no job is active. The window and each seam register as jobs and switch on only while an IntersectionObserver reports them on screen. Under `prefers-reduced-motion`, the window draws once with a single pre-cleaned figure-eight swath and no regrowth or auto-wipe, the seams render one static wave, smooth scroll and press-scale are disabled, and the hint stops fading; a visitor can still wipe by hand.

## Do's and Don'ts

### Do:
- **Do** keep every new conversion path ending in a pre-written text to the one phone number, with a copyable fallback.
- **Do** open each new full-bleed section with a wave seam filled in that section's own background colour.
- **Do** keep tap targets at 44px minimum and primary actions at 58px; keep body, controls and labels at 17px.
- **Do** use squeegee aqua for hover, focus (3px outline, 3px offset) and caret, and sponge yellow only on or against deep teal.
- **Do** route any new animation through the shared loop, pause it off screen with an IntersectionObserver, and give it a reduced-motion still frame.
- **Do** keep new lists as hairline-divided rows with a circular arrow that carries the hover, rather than boxed cards.

### Don't:
- **Don't** add shadows to panels, rows or buttons; the window is the only lifted object and its shadows are teal-tinted.
- **Don't** set sponge yellow as text on fresh ground or mint.
- **Don't** change a service row's background, border or outline on hover; the arrow alone responds.
- **Don't** add entrance animations, parallax or scroll-triggered reveals to UI chrome; motion belongs to the window, the bubbles and the seams.
- **Don't** set body copy or form controls below 17px, or any page-body text below 15px.
- **Don't** use pure white as the page ground; the ground is fresh-ground, with white reserved for fields, chips and text on teal.
