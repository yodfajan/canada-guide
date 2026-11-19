# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Thai people in general who want to go to Canada and are starting from zero: they do not yet know the programs, permits, costs, or the order of steps. Many are working professionals considering a Work & Study (Co-op) program for the 2027 or 2028 intake, with a possible later path to a Post-Graduation Work Permit (PGWP) and Permanent Residency (PR).

Their job: find out what to do, how to prepare, how much money is needed, and in what order, well enough to actually go.

## Product Purpose

An interactive guide that takes a person from knowing nothing to landing in Canada. Success means a user can, from this app alone, understand their options, choose a path, know every step and cost, and act on it, checking official sources where the app points them.

It covers three phases:

1. Test the waters: a Work & Study (Co-op) program to try living in Canada with limited budget risk.
2. Academic and career pivot: specialized fields (Health Informatics, Data Analytics, Business Intelligence, Digital Transformation, AI, Management).
3. Long-term goal: PGWP and PR.

## Positioning

A single, free, bilingual guide written for Thai beginners that shows every amount in both CAD and THB at the day's live rate, separates official fees from estimates, and links each official figure to its source page.

## Operating Context

- Used on both mobile and desktop. It is currently opened as a local file and may be published online later (publishing is not yet decided).
- Users move between the app and official Government of Canada (IRCC) pages, school websites, their bank, and test providers.
- Planning runs over 12 to 18 months before the intake, so users return to the app many times; progress must persist on the device.

## Capabilities and Constraints

Confirmed functionality (all in `index.html`):

- Start from Zero: a 12-step guide from choosing a path to starting part-time work, with timing, actions, costs, progress ticks, and a glossary.
- Am I Ready?: comparison of private career college Co-op (no PGWP) against public college post-graduate diploma with Co-op (PGWP eligible), plus an 8-question fit quiz.
- Fields & PR Matrix: 28 fields in six groups (Tech & Data, Health & Social, Business & Finance, Engineering & Trades, Education, Creative & Hospitality) with filters, the CIP code to ask for, PGWP list status, 2026 Express Entry category, and NOC 2021 occupations linked to their official profiles.
- Cities & Map: interactive Leaflet map (Esri gray tiles, needs internet) of 11 study cities, with per-city rent (CMHC Oct 2025), minimum wage, hours of work to pay rent, January temperature, student health cover, provincial PR program, a comparison table, and the Thai embassy and consulate.
- Citations: any text can cite a source with a [[key]] token; each page shows numbered markers and a "References on this page" list linking to official pages.
- Bridge Roadmap: two selectable scenarios (Safe Test, One-Shot) from Year 0 to PR.
- All Costs: itemized costs in CAD and THB with subtotals and a currency converter.
- Am I Ready? also covers Option C, a university master's degree (with or without Co-op), with a 10-question quiz that scores all three options.
- Budget Simulator (own tab): program type (private Work & Study always has Co-op; public college and master's with or without Co-op), start year 2027 or 2028 (projected with sourced yearly increases), length 1 or 2 years, a month-by-month plan of study, Co-op and break months with separate pay rules, a plain-language analysis with a verdict, a money chart over the whole program including year-2 tuition, a comparison of the three types, pay vs living-cost bars, and a spending split.
- Checked 19 November 2026: ILAC and Tamwood closed (September 2026), CCTB takes no 2026 intakes, Cornerstone was suspended in 2026; private Co-ops are often about 20 hours a week near minimum wage. Take-home pay about 93% at part-time pay (CPP 5.95%, EI 1.63%, 2026 rates). Shared room in Toronto about CAD 1,150 (U of T 2026).
- Preparation Checklist: 15 ordered steps in 5 phases with a "do this next" card, English test prices and booking links, IELTS guidance, and how to check an agent (no named agents are endorsed).
- Live data fetched once per day: CAD and USD to THB rates, IRCC study permit processing time for Thailand, and the latest Express Entry draws (IRCC JSON feeds).
- Links to official sources on every tab.

Constraints the user confirmed must always hold:

- The whole app stays in one file, `index.html`, and opens immediately with nothing to install.
- Bilingual Thai and English with complete translations; Thai is the primary language and the default.
- Figures must link to official sources, and estimates must be clearly distinguished from official fees.
- State (quiz answers, checklist, steps, simulator inputs) persists in `localStorage`.

Technical facts: Tailwind CSS via CDN, vanilla JavaScript, Lucide icons via CDN, Google Fonts; an internet connection is needed for these and for the live rate.

Undecided: whether and where the app will be published online.

## Brand Commitments

- Visual style, binding, in the user's words: "Apple glass Minimal Classic".
- Visual language, binding, requested on 14 November 2026: Apple AppKit (macOS), per https://developer.apple.com/documentation/appkit. The earlier card-based look was rejected as too plain. It must use the Liquid Glass material (floating translucent sidebar, toolbar items, and tab bar over a soft wallpaper); a flat AppKit rendition was rejected for not looking like Liquid Glass.
- The original specification is `Canada_plan.md`.
- Organization rule: never use em dashes or en dashes in any text; use "to" for ranges.

## Evidence on Hand

- Official IRCC fees and the proof-of-funds amount were checked against the IRCC website on 14 November 2026 (study permit CAD 150, biometrics CAD 85, PGWP CAD 255, PR via Express Entry CAD 1,590, living-cost proof CAD 23,448 for one person applying on or after 1 September 2026).
- Checked 19 November 2026: since 1 April 2026 post-secondary students need no separate Co-op work permit (a school letter instead); IELTS in Thailand is computer-only since 22 March 2026 at THB 8,860; CELPIP-General is offered in Thailand (THB 7,000); PTE Core and PTE Academic USD 224; TOEFL iBT USD 230; Duolingo USD 70. IRCC accepts only IELTS General Training, CELPIP-General, PTE Core (and TEF/TCF) for the PGWP and Express Entry. Master's of 8 months or more can give a 3-year PGWP; spouse open work permit needs a master's of 16 months or more.
- All other costs (medical exam, flights, rent, living costs, tuition ranges) are estimates and are labelled as such.
- There are no testimonials, user numbers, partner schools, or endorsements. Future work must not invent any.
- The app is planning information only, not legal or immigration advice, and says so.

## Product Principles

1. Assume zero knowledge: explain every term and give the next action, in order.
2. Honest numbers: show both currencies, mark estimates, and link official figures to their source.
3. Thai first: natural Thai is the primary experience; English is complete, not secondary filler.
4. Opens anywhere: one file, no setup, works on a phone and a computer.
5. Tell the hard truths early: PGWP exclusions, second study permits, and budget shortfalls are shown plainly, not buried.
