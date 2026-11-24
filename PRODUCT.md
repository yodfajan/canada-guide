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
- Simulator audit, 19 November 2026: money to show includes travel (IRCC requires tuition, living costs and travel); living costs include health insurance (CAD 80 a month); compulsory school fees slider; take-home rate falls with monthly pay (93% to 80%); after-graduation months earn only while a PGWP application is pending; IRCC amount projected from 2028; Co-op has no IRCC weekly hour limit (private default 35 h with a 20 h cautious case shown), plus an optional side job up to 24 h a week.
- Simulator round 3, 20 November 2026: results can be shown in THB, CAD or both; the cash list splits tuition and school fees, and every line (tuition, fees, IRCC amount, travel, setup reserve) can be typed over with the user's own quote; a "where do these monthly numbers come from" panel shows the pay formula (hours × wage × 4.33 weeks, then the share kept after CPP, EI and tax) and lets the user type rent, food, other costs and health insurance; the three-type comparison uses the user's own settings for the selected type (so it matches the results) and typical values for the other two, in the chosen currency.
- Glossary, 20 November 2026: one shared list of 124 terms and abbreviations (Thai and English, 9 groups, official links where one exists) opened from a book button in the toolbar on every page, with search. Known terms in page text are underlined automatically (once per card) and open a short explanation when tapped. The Start page and simulator glossaries draw from the same list.
- Simulator round 4: optional tips per hour for part-time service jobs (default 0, taxable per CRA line 10400); rent is labelled as including water, electricity and heat; the "where from" panel shows THB next to CAD and has number boxes for hours, wages, tips and extra job hours instead of jump buttons.
- Checked 20 November 2026 and added as step-by-step help on the All Costs rows: translation of Thai documents (IRCC guide IMM 5269: translation plus translator affidavit unless certified in Canada; applicant, family and representatives may not translate; Thai Department of Consular Affairs legalization 200 THB per stamp, optional; shop prices about 350 to 950 THB a page, no official price; Thailand joins the Apostille Convention on 28 Feb 2027); the Bangkok VAC run by VFS Global (biometrics include one transmission, courier 270 THB, SMS 70 THB, Premium Lounge 2,930 THB, prices from 1 Nov 2026; biometrics valid 10 years for temporary residence, new ones for every PR application); PR medical exam (after the Express Entry invitation, panel physician only, results valid 12 months, no IRCC fee, two clinic price lists about CAD 240 to 275, possible reuse of an exam from the last 5 years under a policy to 5 Oct 2029); Thai police certificate (Royal Thai Police Special Branch, 100 THB in person or 160 by post, 15 to 25 working days, from abroad with fingerprints; no Canadian certificate needed for PR). The checklist has a 16th step for translations. Glossary search accepts partial words, letters in order, one typo, and * or ? wildcards.
- Agents, changed 23 November 2026 at the user's request: the Checklist tab now names 11 agencies in Thailand that pass at least 2 of 3 verifiable checks (ICEF Agency Status; named for Thailand on a Canadian public school's agent list, only lists read directly; TIECA membership or ICEF Canada Course/ITAC staff), each with evidence links and a clear "not an endorsement or ranking" warning. No agency is ranked or recommended. Reworked the same day into "where to ask for advice": each agency shows a book or contact button, its study-in-Canada page, whether its site says consultation is free, phone, LINE and hours (all from the agency's own website), a branch-city filter, and its check results. Hands On Education Consultants (named by the user) is included with a neutral "not found on the 3 check sources" badge and advice on how to verify it. iae GLOBAL (no Thailand office shown on its site) and Born to Consult (no phone or booking) were dropped from this list.
- Fingerprints in Canada for the Thai police certificate (2 ink cards): about CAD 65 to 125, most often 80 to 110 with tax (Edmonton and Winnipeg police, RCMP-accredited companies); Vancouver police do digital only, Calgary, Toronto and Ottawa police refer to private companies; Thai missions in Canada do not take fingerprints.
- Calendar planner, 23 November 2026: on the Checklist tab the user picks an intake (January, May or September of 2027 or 2028); every step gets a recommended date from its phase window (overdue steps start from today, always in checklist order), editable per step and saved on the device. Each step and 4 key dates (arrival, classes start, program end, PGWP) have an "Add to Google Calendar" link that opens a pre-filled event in the user's own Google account, and the whole plan downloads as a .ics file to import into Google Calendar, Apple Calendar or Outlook. No Google API, OAuth or data upload: true two-way sync would need the user's own Google Cloud OAuth client. Once an item is added, its button becomes "Added to Google" with Remove; adding it again is blocked until it is removed, and Remove opens a Google Calendar search so the user can delete the event there too (the page cannot delete Google events or detect whether Save was pressed). Below the planner, a Calendar card has two views: "My Google Calendar" embeds the user's real Google Calendar (official embed iframe; the user pastes a Calendar ID, several IDs or the embed code once, stored only in that browser and never written into the file; month view on computers, list view on phones; Refresh, Open in Google Calendar and Change calendar; it reloads itself when the user returns from the Google tab). A private calendar shows only when the browser is signed in to Google and allows Google's cookies in the embed (Chrome on a computer usually works, Safari and some phones block it), and the page says so. "Added from this page" is the in-app month grid of added items (empty until something is added; Today selects today, Next item opens the next added item). Reminders were tried and removed at the user's request on 23 November 2026.
- Program links, 23 November 2026 (user request): the Am I Ready? card "Rules and example programs" now covers all three options with an A / B / C switch. A (private Co-op): 5 rules (no PGWP, DLI check, Co-op at most half the program and no weekly hour limit per IRCC's intern page, PAL, 24 h off-campus) plus Greystone and Sprott Shaw Co-op programs with DLI numbers; Eton College dropped (DLI not confirmed), CDI College dropped (no study-permit applicants). B (public college): 6 rules plus 10 programs (Langara, Douglas, BCIT, Seneca, Humber, Conestoga, Lambton, Centennial, Durham, Fanshawe) with tuition from official pages and CIP codes where shown. C (master's): 16 programs, now including SFU MBA, McMaster MBA Co-op, Laurier MAC, Manitoba MSCM and Calgary MEng Software. In every table the school name opens its international or graduate admissions page and the program name opens the program page. The Fields tab's "example schools" are now 108 links across 25 fields (certificates, diplomas and master's only: bachelor's programs were removed at the user's request), each opening that school's matching program page with a short note (credential, length, co-op, CIP or PGWP status as the school states it). Programs suspended or closed to international students were left out or replaced by the closest open program and labelled "closest". George Brown, Emily Carr and uOttawa block automated reads, so their links come from search results. Automotive diplomas at Centennial, SAIT and BCIT are marked not PGWP-eligible by the schools, which the Automotive card now says.
- Section jumps, 23 November 2026: buttons that open another tab land on the section they name, not the top: Start step 1 "Take the quiz" opens the quiz, step 3 the English test prices, step 7 the document phase of the checklist, and the live card's "See all recent draws" the Express Entry draws table. Tab switches jump instantly (the page's smooth scrolling no longer fights the jump), and the position is rechecked after late layout. Buttons whose target is the whole tab (simulator, Fields, roadmap, All Costs) still open at the top.
- All Costs and Budget, 23 November 2026 (revised the same day at the user's request): the All Costs "money to show" card keeps its original simple form (no inputs) and shows the same amount and label as the Budget line "Money to show in the bank (for IRCC)", both from simCalc(). A note explains that the big Budget headline is the cash to have ready before you go (this amount plus the setup reserve), which was the source of the earlier mismatch. The Budget list now also ends with that sum as its own labelled line. Items in sections 1 to 4 of All Costs can be typed over ("Enter my own amounts") in their own currency (THB for Thai costs, CAD for Canadian ones), saved on the device; typed lines show a "Your amount" badge and feed the section subtotals and the cash-before-class total; an empty box or "Use the estimate" goes back to the range, and "Clear my amounts" resets all. Section 5 (later: PGWP and PR) stays as estimates.
- Budget compare table explained, 24 November 2026: in "Compare the three program types", the money-to-show and cash-to-have-ready rows show their formula under the label (tuition + fees + IRCC living cost + travel; money to show + setup reserve) and a "See each line in the list above" link that scrolls to the Budget money list and highlights it. "Money at the end" now has a "where it comes from" block per type, folded under a "See how it is worked out" toggle on that row (closed by default, remembered on the device): reworded the same day after the user found it confusing, it now reads as one chain from the bank: money in your bank (the money to show) − year-1 tuition and fees − flights to and from Canada = money left for living when you arrive (equal to the IRCC amount), + pay from work over all months (after tax, first month half) − living costs over all months (months × monthly cost) − year-2 tuition and fees (always shown; "None (1-year program)" when it does not apply) = money at the end. A plain-language note says the setup reserve is separate money. The parts are summed from the same monthly plan the simulator uses, so they always add up to the number shown.
- Budget controls on one scale, 24 November 2026: every money control on the Budget page (tuition, fees, wage, tips and Co-op wage sliders, the IRCC amount box, the "where from" number boxes and the typed-amount list) now shows and takes the start-year amount, the same number the results use; before, the sliders showed today's prices while the list showed start-year amounts (20,000 vs 20,800 for 2027). The saved state still holds today's prices (simFac converts), so older saves keep working. Slider steps are finer: tuition CAD 50, fees CAD 10, wages and tips CAD 0.05 (so values such as 17.95 can be picked).
- Budget layout, 24 November 2026: on wide screens (1024 px and up) the controls card now runs the full height of the results column, and the controls inside follow the scroll both ways (scrolling down moves them up until the last control is in view above the dock, then they hold; scrolling up brings them back until the first control is in view). Before, the card was pinned to the top, so on most screens its lower controls stayed hidden until the end of the page. Phones keep the single-column layout.
- Live IRCC living-cost amount: read daily from the IRCC proof-of-funds page (the newest "on or after" table, 1 person, outside Quebec), which allows cross-site reads. The money to show and the Costs and Start pages follow it unless the user typed their own amount. The IRCC fee list (ircc.canada.ca) blocks cross-site reads, so fees stay as verified links. Live data refreshes once a day, when the app comes back into view, every 30 minutes if the day changed, and on "Check now".
- Checked 19 November 2026: ILAC and Tamwood closed (September 2026), CCTB takes no 2026 intakes, Cornerstone was suspended in 2026; private Co-ops are often about 20 hours a week near minimum wage. Take-home pay about 93% at part-time pay (CPP 5.95%, EI 1.63%, 2026 rates). Shared room in Toronto about CAD 1,150 (U of T 2026).
- Preparation Checklist: 17 ordered steps in 5 phases (a translation step was added on 20 November 2026, and on 23 November 2026 the English test step was split into "start preparing" and "book and take it"; old ticks carry over) with a "do this next" card, English test prices and booking links, IELTS guidance, and how to check an agent (no named agents are endorsed).
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
- The original specification is `Canada_plan.md` (its design section predates the Liquid Glass change). The current visual system is documented in `DESIGN.md`, with its machine-readable companion in `.impeccable/design.json`.
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
