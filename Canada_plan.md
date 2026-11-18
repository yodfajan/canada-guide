
Yodfa Jantam
# Project Specification: Canada "Test-the-Waters" Work & Study to PR Interactive Guide (2027–2028)

## 1. Project Overview & Core Objective
Act as a Senior Full-Stack Developer, Apple HIG UI/UX Designer, and Canadian Education/Immigration Strategist.
Build an interactive Single-Page Web Application (SPA) designed specifically for a Thai professional who wants to:
1. **Phase 1 (Test the Waters):** Start with a **Work & Study (Co-op)** program in Canada (2027/2028) to experience Canadian life, test personal adaptability, work part-time/Co-op, and manage initial budget risk.
2. **Phase 2 (Academic & Career Pivot):** Transition into specialized fields (**Medical/Health Informatics, Data Analytics, Business Intelligence, Digital Transformation, AI, or Management**).
3. **Phase 3 (Long-Term Goal):** Secure a Post-Graduation Work Permit (PGWP) and Permanent Residency (PR).

---

## 2. Tech Stack & Design System (Apple Minimal Classic)
- **Delivery Format:** Single-file `index.html` using Tailwind CSS (CDN), Vanilla JavaScript, and Lucide Icons (or React + Vite if running in a full project workspace) so it runs immediately in the browser.
- **Visual Style (Apple HIG):**
- Clean, airy layout (`#F5F5F7` background, `#FFFFFF` cards, `20px` border radius, subtle borders `rgba(0,0,0,0.06)`, frosted glass sticky top navigation).
- Typography: SF Pro / Inter for English, Noto Sans Thai / Sukhumvit Set for Thai. High legibility, generous line-height (`1.65`).
- **Bilingual Switch (`TH` / `EN`):** Instant client-side language toggle in the navbar with complete, natural translations across all tabs, cards, and calculators.
- **Persistence:** Save checklist states and simulator inputs to `localStorage`.

---

## 3. Core Interactive Modules & Content Requirements

### Module 1: "Am I Ready?" Reality Check & Work-and-Study Comparison
Help the user evaluate if going for Work & Study first is the right move by comparing the **2 types of Work & Study (Co-op)** in Canada:

1. **Option A: Private Career College Co-op (6+6 or 12+12 Months)**
- *Purpose:* Purely to test living in Canada with a lower initial tuition budget (~$8,000–$14,000 CAD) and flexible admission/English requirements.
- *Popular Programs:* Digital Marketing, Business Administration, Hospitality, IT/Web Dev basics (e.g., Tamwood, ILAC, Cornerstone, Greystone, CCTB).
- *Pros:* Low tuition, quick entry, 20–24 hrs/week part-time work during study + full-time paid Co-op term.
- *Cons / Reality Check:* **No PGWP (Post-Graduation Work Permit) eligibility.** Co-op jobs are mostly service/entry-level rather than corporate Data/BI roles. Requires a "Bridge Strategy" (transferring to a Public College/University after completion) if the user decides to stay for PR.
2. **Option B: Public College Post-Graduate Diploma with Co-op (1 or 2 Years)**
- *Purpose:* Test living in Canada while studying a specialized tech/data track that **directly qualifies for up to a 3-year PGWP** and counts toward PR.
- *Popular Programs:* Health Informatics, Data Analytics, Business Intelligence, AI (e.g., BCIT, Langara, Douglas, George Brown, Seneca, Humber).
- *Pros:* Corporate/technical Co-op placements (hospitals, tech firms, banks), eligible for PGWP (if the program matches IRCC's eligible CIP codes in STEM/Healthcare), direct pathway to PR.
- *Cons:* Higher tuition (~$18,000–$24,000 CAD/year), requires IELTS Academic 6.5.

*Interactive Element:* Build an **"Adaptability & Fit Self-Assessment Quiz"** (Lifestyle, Weather/Winter, Part-time Service Work vs. Back-office Technical Work, Budget Risk) that recommends whether the user should start with Option A or Option B.

---

### Module 2: Target Study Fields & PR Eligibility Matrix
Provide an interactive card grid and filter for the user's 5 target fields, showing **Co-op job reality**, **IRCC PGWP Eligibility (2026+ rules)**, and **PR Draw Category**:

1. **Medical / Health Informatics (Top Strategic Pick)**
- *Why it works:* Combines Data/BI skills with Healthcare. Eligible for both **PGWP** and **Express Entry Healthcare / STEM Category Draws** (lower CRS cut-offs).
- *Sample Schools:* George Brown (Health Informatics PG), BCIT, McMaster (MSc eHealth Co-op), UVic.
2. **Data Analytics & Business Intelligence (BI)**
- *Why it works:* Direct match for SQL, Power BI, Python, and Excel skills. High Co-op demand in operations, supply chain, and finance. Eligible under **STEM CIP codes**.
- *Sample Schools:* Langara College (Data Analytics Post-Degree Co-op), Douglas College, Conestoga, SFU, Northeastern Vancouver.
3. **Artificial Intelligence (AI) & Machine Learning**
- *Why it works:* Strong alignment with **BC PNP Tech** and **OINP Tech Draws**.
- *Sample Schools:* Humber, Centennial, SFU, Waterloo.
4. **Digital Transformation & IT Systems**
- *Why it works:* Focuses on business process automation, ERP, and cloud systems. Good fit for Business Systems Analyst (NOC `21221`).
5. **Management / Business (Warning Flag)**
- *Critical Warning:* Display a clear red/amber badge explaining that **General Management/Business diplomas at colleges are largely excluded from PGWP** under updated IRCC field-of-study rules unless taken as a University Master's degree or paired with an eligible STEM/Healthcare CIP code.

---

### Module 3: The Step-by-Step Bridge Roadmap (From "Testing the Waters" to PR)
Create an interactive visual timeline showing how a user moves from Year 0 to PR under two selectable scenarios:
- **Scenario 1: The "Safe Test" Route (1-Yr Private Co-op -> Public PG/Master's -> PGWP -> PR)**
- Shows how to use Year 1 to adapt, save money from part-time/Co-op work, improve English on-shore, and apply for a Public College/University in STEM/Healthcare to unlock PGWP and PR.
- **Scenario 2: The "One-Shot" Route (Public Co-op PG Diploma / Master's -> 3-Yr PGWP -> CEC/PNP PR)**
- Shows how going straight into a Public Co-op program in Data/Health Informatics saves 1 year of tuition and accelerates PR via Canadian Experience Class (CEC) + Foreign Work Experience points.

---

### Module 4: Preparation Checklist & Budget Simulator
1. **Interactive Preparation Checklist (with Progress Bar):**
- **Document & Skill Prep:** IELTS preparation, Academic Transcripts, Resume tailored to Canadian format (1-2 pages, impact-focused), Sponsor Financial Proof (IRCC minimum ~$20,635 CAD living cost + 1st year tuition, 4–6 months bank statement seasoning).
- **Visa & Logistics:** PAL (Provincial Attestation Letter), Study Permit + Co-op Work Permit application, Upfront Medical (IOM Bangkok), Biometrics.
2. **Interactive Cost vs. Income Simulator:**
- Sliders for Tuition Type (`Private Co-op` vs `Public Co-op` vs `Master's`), Living Style (`Shared Room` vs `Studio`), and Work Hours (`20 hrs/wk Study Term` + `40 hrs/wk Co-op Term` at `$17.50–$22/hr`).
- Calculates **Initial Show Money Required (THB/CAD)** vs. **Estimated Monthly Cashflow while in Canada** (showing whether part-time + Co-op income covers living expenses).

---

## 4. Execution Instructions
- Build the entire application with rich, accurate bilingual content (`TH` and `EN`).
- Do not use placeholder text. Make every tab, filter, quiz, and calculator fully functional.
- Provide instructions to open or serve the app locally once generated.