---
name: Canada Work & Study to PR Guide
description: A calm macOS-style planning window in Liquid Glass, Thai first, for people going from zero to Canada.
colors:
  accent-blue: "#0070E0"
  link-blue: "#0064D9"
  link-blue-dark: "#5AAEFF"
  blue-soft: "rgba(0,122,255,.12)"
  success-green: "#1D7A33"
  success-green-dark: "#32D74B"
  success-green-soft: "rgba(52,199,89,.18)"
  caution-amber: "#9A4D00"
  caution-amber-dark: "#FFA826"
  caution-amber-soft: "rgba(255,149,0,.16)"
  alert-red: "#C4281C"
  alert-red-dark: "#FF6F66"
  alert-red-soft: "rgba(255,59,48,.12)"
  window-mist: "#EEF1F6"
  window-night: "#0C0E13"
  card-veil: "rgba(255,255,255,.6)"
  card-veil-dark: "rgba(255,255,255,.075)"
  glass-clear: "rgba(255,255,255,.55)"
  glass-dense: "rgba(255,255,255,.86)"
  glass-clear-dark: "rgba(52,56,68,.5)"
  glass-dense-dark: "rgba(120,126,142,.5)"
  glass-edge: "rgba(255,255,255,.75)"
  glass-edge-dark: "rgba(255,255,255,.16)"
  inset-wash: "rgba(0,0,0,.045)"
  gray-wash: "rgba(120,120,128,.14)"
  ink: "rgba(0,0,0,.88)"
  ink-secondary: "rgba(0,0,0,.66)"
  ink-tertiary: "rgba(0,0,0,.6)"
  ink-dark: "rgba(255,255,255,.9)"
  hairline: "rgba(0,0,0,.09)"
  hairline-strong: "rgba(0,0,0,.15)"
  series-blue: "#2a78d6"
  series-orange: "#eb6834"
  series-green: "#1baf7a"
  series-amber: "#eda100"
  series-pink: "#e87ba4"
  series-deep-green: "#008300"
  thai-red: "#A51931"
  thai-navy: "#2D2A4A"
typography:
  hero:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Inter, Sukhumvit Set, Noto Sans Thai, sans-serif"
    fontSize: "44px"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Inter, Sukhumvit Set, Noto Sans Thai, sans-serif"
    fontSize: "38px"
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: "-0.012em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Inter, Sukhumvit Set, Noto Sans Thai, sans-serif"
    fontSize: "24px"
    fontWeight: 600
    lineHeight: 1.3
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Inter, Sukhumvit Set, Noto Sans Thai, sans-serif"
    fontSize: "17px"
    fontWeight: 600
    lineHeight: 1.3
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Inter, Sukhumvit Set, Noto Sans Thai, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, SF Pro Text, Inter, Sukhumvit Set, Noto Sans Thai, sans-serif"
    fontSize: "12.5px"
    fontWeight: 500
    lineHeight: 1.6
rounded:
  chip: "5px"
  field: "10px"
  inset: "12px"
  popover: "16px"
  card: "20px"
  sheet: "22px"
  dock: "30px"
  pill: "999px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  card: "20px"
  lg: "24px"
  page-desktop: "28px"
components:
  button-glass:
    backgroundColor: "{colors.glass-dense}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "4px 16px"
    height: "32px"
  button-primary:
    backgroundColor: "{colors.accent-blue}"
    textColor: "#FFFFFF"
    rounded: "{rounded.pill}"
    padding: "4px 16px"
    height: "32px"
  segmented-control:
    backgroundColor: "{colors.gray-wash}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "3px"
  segmented-control-selected:
    backgroundColor: "{colors.glass-dense}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "3px 14px"
    height: "28px"
  card:
    backgroundColor: "{colors.card-veil}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "20px"
  stat-tile:
    backgroundColor: "{colors.inset-wash}"
    textColor: "{colors.ink}"
    rounded: "{rounded.inset}"
    padding: "12px 14px"
  badge-blue:
    backgroundColor: "{colors.blue-soft}"
    textColor: "{colors.link-blue}"
    rounded: "{rounded.pill}"
    padding: "2px 10px"
  number-field:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "2px 8px"
    height: "30px"
  dock:
    backgroundColor: "{colors.glass-clear}"
    textColor: "{colors.ink-secondary}"
    rounded: "{rounded.dock}"
    padding: "5px"
  dock-item-active:
    backgroundColor: "{colors.glass-dense}"
    textColor: "{colors.link-blue}"
    rounded: "24px"
---

# Design System: Canada Work & Study to PR Guide

## Overview

**Creative North Star: "The Glass Planner"**

The app is a calm macOS window that a Thai first-timer keeps open for 12 to 18 months while planning the move to Canada. Its frame is Apple AppKit rendered in Liquid Glass: a soft, tinted wallpaper sits at the back, the toolbar items, segmented controls, popovers and the tab dock float above it as frosted glass, and the content (steps, money, charts, calendars) rests on quiet, lightly veiled panels so every number and next step reads clearly. The mood is calm, trustworthy and premium: official enough to trust with visa and money decisions, never loud, never salesy.

Density is moderate and task-driven. Pages are long, readable columns of cards with generous line height for Thai script, tabular figures for every amount, and colour reserved for meaning (action, status, data series). The earlier plain card-based look and a flat AppKit rendition were both rejected by the user; the glass material is the identity, but it belongs to the floating chrome, not to every surface.

**Key Characteristics:**
- Frosted glass for floating chrome only; content panels are lighter veils that rest on the wallpaper.
- One action colour (system blue); green, amber and red only carry status.
- Pill-shaped controls, 20px card corners, hairline dividers.
- Thai first: system font with Sukhumvit Set and Noto Sans Thai, looser Thai line height, no negative tracking on Thai headings.
- Every amount in tabular figures, usually CAD and THB together.
- Full light and dark themes driven by CSS custom properties.

## Colors

A cool, misty neutral world with a single system-blue accent, soft tinted wallpaper glows, and a fixed six-colour data series.

### Primary
- **System Blue Accent** (`{colors.accent-blue}`): the only fill colour for action. Primary buttons, checked checkboxes, the selected radio dot, slider tracks, progress bars, the "do this next" card border, the today marker in the calendar, and the selected map label.
- **Link Blue** (`{colors.link-blue}`, dark theme `{colors.link-blue-dark}`): text links, icons beside headings, citation markers, glossary term underlines, active dock item text, and blue badges. Paired with **Blue Wash** (`{colors.blue-soft}`) for badge backgrounds, hover on links and chips, highlighted table columns and flashed list items.

### Secondary
- **Success Green** (`{colors.success-green}`, dark `{colors.success-green-dark}`): positive money (+), completed steps, "official fee" badges, live-data dots, the goal dot on the roadmap. Its wash (`{colors.success-green-soft}`) backs done-step counters and green badges.
- **Caution Amber** (`{colors.caution-amber}`, dark `{colors.caution-amber-dark}`): warnings that need attention but are not failures, such as "should have started", risky roadmap steps, and notes on the money panel. Wash: `{colors.caution-amber-soft}`.
- **Alert Red** (`{colors.alert-red}`, dark `{colors.alert-red-dark}`): negative money (-), shortfalls, the "intake too close" warning, the critical verdict. Wash: `{colors.alert-red-soft}`.

### Tertiary
- **Data Series** (`{colors.series-blue}`, `{colors.series-orange}`, `{colors.series-green}`, `{colors.series-amber}`, `{colors.series-pink}`, `{colors.series-deep-green}`): the validated chart palette, always used in this order. Charts, the program timeline, spending split bars, and the plan calendar (checklist phases 1 to 5, then key dates). Dark-theme variants are slightly deeper (`#3987e5`, `#d95926`, `#199e70`, `#c98500`, `#d55181`, `#0ca30c`).
- **Thai Flag Red and Navy** (`{colors.thai-red}`, `{colors.thai-navy}`): only for the Thai embassy and consulate pins and flag on the map.

### Neutral
- **Window Mist** (`{colors.window-mist}`, dark `{colors.window-night}`): the window background under the wallpaper glows.
- **Wallpaper glows**: four large radial tints fixed behind everything (blue `rgba(110,165,255,.42)`, pink `rgba(255,140,165,.28)`, teal `rgba(95,215,205,.32)`, violet `rgba(175,150,255,.24)`; deeper versions in dark). They exist so the glass has something to blur.
- **Card Veil** (`{colors.card-veil}`, dark `{colors.card-veil-dark}`): content panels.
- **Glass Clear and Glass Dense** (`{colors.glass-clear}` / `{colors.glass-dense}`, dark `{colors.glass-clear-dark}` / `{colors.glass-dense-dark}`): floating chrome at rest and selected or raised glass (buttons, selected segments, popovers). **Glass Edge** (`{colors.glass-edge}`, dark `{colors.glass-edge-dark}`) is the 1px rim on both.
- **Inset Wash** (`{colors.inset-wash}`) for stat tiles and calendar cells; **Gray Wash** (`{colors.gray-wash}`) for segmented control tracks, neutral chips and badges.
- **Ink** (`{colors.ink}`, dark `{colors.ink-dark}`), **Ink Secondary** (`{colors.ink-secondary}`) for supporting text, **Ink Tertiary** (`{colors.ink-tertiary}`) for eyebrows, axis labels and captions.
- **Hairline** (`{colors.hairline}`) between rows; **Hairline Strong** (`{colors.hairline-strong}`) for totals and the tab bar edge.

### Named Rules
**The One Accent Rule.** System blue is the only colour that means "act here". Green, amber and red are status, never decoration, and are never used for buttons.

**The Fixed Series Rule.** The six data colours always appear in the same order with a legend or label beside them; colour alone never carries meaning. On the amber series colour, text is near-black (`#0b0b0b`), not white.

## Typography

**Display Font:** the system UI font (`-apple-system`, `BlinkMacSystemFont`, SF Pro Text) with Inter as the web fallback
**Body Font:** the same stack; in Thai the order becomes Sukhumvit Set, then Noto Sans Thai, then Inter
**Label/Mono Font:** none; numbers use the same family with tabular figures

**Character:** native macOS type: neutral, legible, and quietly confident, so the content feels like an Apple app rather than a website. Inter and Noto Sans Thai (400 to 700) load from Google Fonts for systems without SF Pro or Sukhumvit Set.

### Hierarchy
- **Hero** (700, 44px, 34px on phones, line height 1.1, tracking -0.02em): the one big money figure, such as "cash to have ready".
- **Display** (700, 30px on phones to 38px from 640px, line height 1.3): page titles, one per tab. The Start page title runs larger, 28px to 42px.
- **Headline** (600, 20 to 24px, line height 1.3): section headings inside a page (agents, tests, master's examples).
- **Title** (600, 17 to 18px): card headings and checklist phase headings.
- **Body** (400, 15px, 16px for list rows on phones, line height 1.6): paragraphs, list items, table cells. Keep lead paragraphs near 62 to 75 characters wide.
- **Label** (500, 12.5px, Ink Tertiary): eyebrows above values, column headers (12px, 600), small captions (13 to 13.5px).
- **Values** (700, 20px in stat tiles): headline numbers inside tiles.

### Named Rules
**The Tabular Money Rule.** Every amount, count, date and chart label uses tabular figures so columns of money line up.

**The Thai Breathing Rule.** Thai headings drop negative letter spacing to 0 and use line height 1.45; never tighten Thai.

## Layout

A single centred column (max width 1040px) inside the window, with 16px side padding on phones and 28px from 1024px. Pages are stacks of cards with 16px gaps (`gap-4`) and 24px between major groups. Two-column and three-column grids appear from 768px (`md`) and 1024px (`lg`), for example the budget simulator's controls (2 of 5 columns) beside its results (3 of 5): the controls card runs the full height of the results, and the controls inside follow the scroll both ways (sticky with a top that moves within range), so every control stays reachable even when the panel is taller than the window.

The toolbar is a 56px sticky strip whose background blurs and fades out with a mask as content scrolls under it. Navigation is a floating tab dock: a full-width rounded bar 10px from the bottom on phones and tablets, and a centred dock (max width 1010px, 16px from the bottom) on computers, where icons and labels sit side by side. The body keeps 88px of bottom padding so the dock never covers content.

Breakpoints: 400px (smaller dock labels), 640px (tables gain column headers, calendar shows chips instead of dots), 768px (multi-column grids), 1024px (centred dock, scroll-following simulator controls, mini summary bar hidden). Under 1024px or on coarse pointers, every control grows to a 44px touch target and text inputs use 16px text to avoid zoom on focus.

## Elevation & Depth

A hybrid system. Depth comes from material first and shadow second: the wallpaper sits at the back, content cards rest on it as lightly veiled panels with a soft ambient shadow and a specular top edge, and only the floating chrome (toolbar items, segmented controls in the toolbar, the dock, the money mini bar, popovers, tooltips) is true glass that blurs and saturates what is behind it.

### Shadow Vocabulary
- **Glass shadow** (`box-shadow: 0 10px 30px rgba(30,40,70,.12), 0 1px 3px rgba(30,40,70,.08)`; dark `0 12px 34px rgba(0,0,0,.45), 0 1px 3px rgba(0,0,0,.3)`): floating chrome, popovers, the glossary sheet.
- **Specular rim** (`box-shadow: inset 0 1px 0 rgba(255,255,255,.95), inset 0 -1px 0 rgba(255,255,255,.25)`): added to every glass or raised surface so it catches light at the top edge.
- **Resting card** (`box-shadow: 0 6px 22px rgba(30,40,70,.07)` plus the specular rim): content cards.
- **Raised control** (`box-shadow: 0 3px 10px rgba(30,40,70,.12)` plus the specular rim): glass buttons; selected segments use `0 2px 6px rgba(30,40,70,.16)`.
- **Accent lift** (`box-shadow: 0 5px 14px rgba(0,90,200,.32), inset 0 1px 0 rgba(255,255,255,.5)`): primary buttons only.
- **Glass blur**: `backdrop-filter: blur(26px) saturate(190%)` for chrome, `blur(24px) saturate(1.6)` for popovers, `blur(14px)` with a fade mask for the toolbar edge. Where `backdrop-filter` is unsupported, glass falls back to the dense glass colour.

### Named Rules
**The Glass Floats Rule.** Glass is for things that float over content. Content cards stay as quiet veils; do not turn them into heavy frosted glass.

## Shapes

Soft, continuous macOS geometry. Controls are pills (999px): buttons, segmented controls and their segments, badges, category chips, the glossary filter chips. Containers step up in radius with their size: event chips in the calendar (5px), number fields and calendar cells (10px, 14px on touch), stat tiles and inset panels (12px), popovers and the map (16px), content cards (20px), the glossary sheet (22px), the floating dock (30px, with 24px items). Small square marks (legend swatches, the app icon) keep 3px to 7px corners. Dividers are 1px hairlines, never boxes inside boxes; tinted left bars (3px to 4px) mark status or series on verdicts, event chips and agenda rows.

## Components

### Buttons
Tactile glass pills that press in slightly.
- **Shape:** full pill (999px), 32px tall (44px on touch).
- **Glass (default):** Glass Dense background, Glass Edge 1px rim, Ink text, raised-control shadow; 14px medium text, 4px 16px padding, 6px gap to an optional 14px icon.
- **Primary:** System Blue fill with a top-to-middle white sheen gradient, white text, accent lift shadow. One primary per card at most.
- **Press:** scales to 0.97 and dims slightly (180ms, `cubic-bezier(.2,.8,.2,1)`).
- **Focus:** 3px outline in the focus ring blue (`rgba(0,122,255,.5)`), 1px offset.
- **Link button:** unstyled text in Link Blue, medium weight, underline on hover, for inline actions such as "Use default".

### Segmented controls
The main choice control (language, currency, program type, intake, filters).
- **Track:** Gray Wash pill with a hairline inset ring, 3px padding.
- **Segments:** transparent pills, 13.5px medium text; the selected segment becomes Glass Dense with a raised shadow. In the toolbar the whole control is glass.

### Chips and badges
- **Badges:** 12px semibold pills, 2px 10px padding, a soft wash with matching text (blue, green, amber, red, gray). Used for status ("official fee", "estimate", "should have started"), counts and evidence links.
- **Filter chips:** 34px pills in Gray Wash; selected becomes Blue Wash with Link Blue semibold text.
- **NOC chips:** 10px rounded gray tiles with the code in Link Blue and the title in Ink.

### Cards / Containers
- **Corner Style:** 20px.
- **Background:** Card Veil with a Glass Edge rim.
- **Shadow Strategy:** resting card (see Elevation & Depth).
- **Internal Padding:** 20px; tables use 0 padding with 10px 14px rows.
- **Variants:** the "do this next" card adds a 1.5px System Blue border; verdict cards carry a 4px left bar in green, amber or red; stat tiles sit inside cards on Inset Wash (12px radius).

### Inputs / Fields
- **Number field:** borderless, 10px radius, right-aligned 14px text, white (dark: 7% white) with a 1px inset control border; grows to 44px and 16px text on touch.
- **Slider:** 4px track filled with System Blue up to the value, 20px white knob (28px on touch) with a hairline shadow.
- **Checkbox and radio:** macOS style: 16px white control with an inset border, filling System Blue with a white tick or dot when on (22px and 20px on touch).
- **Search field:** 42px tall, 12px radius, strong hairline border, 16px text.
- **Focus:** the shared 3px focus ring.

### Navigation
- **Toolbar:** app icon tile (blue gradient, 7px corners), page title, the live exchange-rate chip, round 34px glass buttons (glossary, theme), and the TH / EN segmented control.
- **Tab dock:** eight tabs with 22px icons and 11px labels on phones; on computers a centred dock with 18px icons beside 13.5px labels. The active tab becomes a Glass Dense pill with Link Blue semibold text; others are Ink Secondary.

### Plan calendar (signature component)
The Calendar card switches between two views with a segmented control. "My Google Calendar" shows the user's real Google Calendar as an embedded frame (12px radius, white, hairline inset ring, 640px tall, 540px on phones) under a row of glass buttons (Refresh, Open in Google Calendar) and a Change calendar link; before a Calendar ID is saved it shows an inset setup panel (Inset Wash, 12px radius) with a search-style field, a primary Show calendar button and a how-to disclosure. "Added from this page" is a month grid: 7 columns, 10px cells on Inset Wash, day numbers in 24px circles (today filled System Blue), events as 5px chips with a 3px left bar and a 16% wash of their series colour, done items struck through. Under 640px the chips turn into 7px coloured dots and tapping a day lists its items below. When nothing is added yet, the grid stays clear under a Blue Wash hint; once items exist, a legend names the six colours.

### Add to Google control
An item not yet added shows a glass "Add to Google Calendar" button; once added it becomes a green "Added to Google" badge with a Remove link (an amber badge appears if the planned date changed since).

### Charts
Line, bar and stacked bar charts drawn as inline SVG: 1px grid lines in a faint ink, 12px tabular axis labels in Ink Tertiary, a 2px series line with a 10% area fill, glass tooltips (10px radius, blur 20px), legends with 10px rounded swatches, and every chart offering a "show as a table" fallback.

### Glossary term and popover
Known terms in body text get a 1.5px dotted Link Blue underline; tapping opens a 16px-radius glass popover (max 360px wide) with the term, full name, plain explanation, an official link and a link to the full glossary sheet (22px radius, full screen on phones).

## Do's and Don'ts

### Do:
- **Do** keep glass (`blur(26px) saturate(190%)`, Glass Edge rim, specular rim) for floating chrome: toolbar items, the dock, popovers, the mini summary bar and toolbar segmented controls.
- **Do** define every colour as a CSS custom property on `:root` with a matching override under `:root[data-theme="dark"]`.
- **Do** use System Blue for the single primary action on a card, and pills for every button and segment.
- **Do** show amounts in tabular figures, and pair the six data colours with a legend or label.
- **Do** keep 44px touch targets and 16px input text below 1024px or on coarse pointers.
- **Do** respect reduced motion: no fades, pulses or smooth scrolling when the user asks for less motion.

### Don't:
- **Don't** use em dashes or en dashes in any text; write "to" for ranges (organization rule).
- **Don't** make content cards heavy frosted glass; they stay as Card Veil panels resting on the wallpaper.
- **Don't** fall back to the plain card look or a flat AppKit rendition; both were rejected for not feeling like Liquid Glass.
- **Don't** use green, amber or red for buttons or decoration; they only carry status.
- **Don't** put white text on the amber series colour; use near-black.
- **Don't** reorder or recolour the data series, or let colour carry meaning without a label.
