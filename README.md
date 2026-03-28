# Legal Ops Portfolio — Crystal Grossley

**Live site:** https://[yourusername].github.io/legal-ops-portfolio/

> A collection of legal operations and contract management tools built to demonstrate both domain expertise and front-end development skills.

---

## Projects

| Project | Description | Live Demo |
|---|---|---|
| Contract Request Intake | Multi-step intake form with workflow routing | [View](https://[yourusername].github.io/legal-ops-portfolio/) |
| Contract Clause Library | Searchable clause reference with comparison tool | [View](https://[yourusername].github.io/legal-ops-portfolio/clause-library.html) |
| Federal Grant Compliance Tracker | Timeline-based deadline and compliance tracker | [View](https://[yourusername].github.io/legal-ops-portfolio/grant-tracker.html) |

---

## Project 1 — Contract request intake form

A multi-step contract intake form with dynamic workflow routing, built in vanilla HTML/CSS/JS.

### What it does

- Guides requestors through a 4-step intake process: contract type → parties & scope → risk & value → submitter info
- Dynamically routes based on contract type — vendor agreements, MOUs, interagency agreements, grant subawards, NDAs, and custom contracts each produce a distinct approval pathway
- Auto-calculates risk level (low / medium / high) based on contract value and federal funding involvement
- Generates a tailored approval workflow on submission, including compliance checkpoints (OMB Uniform Guidance, SAM.gov verification, tribal regulatory review)
- Produces a submission summary with a unique reference number
- Fully responsive and supports light/dark mode

### Why I built it

In my work reviewing contracts and MOUs across federal grant portfolios, intake is where most delays originate — requestors don't know what information is needed, which approval path applies, or how risk level affects timeline. This tool addresses that gap by surfacing routing logic at the point of submission rather than after.

### Tech

- HTML5, CSS3 (custom properties, CSS Grid, responsive layout)
- Vanilla JavaScript — no frameworks or dependencies

### Domain knowledge reflected

- Contract types mapped to real-world routing workflows (tribal governance, OMB Uniform Guidance, federal subaward compliance)
- Risk tiers based on dollar thresholds and federal funding status
- Approval pathways include compliance-specific checkpoints (subrecipient risk assessment, SAM.gov, board notification thresholds)

---

## Project 2 — Contract clause library

A searchable reference library of standard contract clauses with drafting notes, risk ratings, and side-by-side comparison.

### What it does

- 12 clauses across three categories: confidentiality & data use, payment & compensation, and federal compliance
- Full-text search across clause titles, descriptions, contract language, and drafting notes
- Filter by category and risk level independently or combined
- Expand any clause to read full contract language plus practical drafting notes
- Select multiple clauses and compare them side by side

### Why I built it

Contract language is usually scattered across files, templates, and institutional memory. A centralized, searchable library with risk context and drafting guidance is a core legal ops infrastructure problem. This is a working prototype of that solution.

### Tech

- HTML5, CSS3 (custom properties, CSS Grid, responsive layout)
- Vanilla JavaScript — no frameworks or dependencies

### Domain knowledge reflected

- Federal clauses cite specific regulatory provisions (2 CFR Part 200, §200.332, §200.337, Privacy Act of 1974, FISMA)
- Drafting notes reflect real operational considerations — SAM.gov UEI transition, single audit thresholds, retroactive approval risks, tribal data sovereignty
- Risk ratings based on standard compliance and procurement risk frameworks

---

## Project 3 — Federal grant compliance tracker

A timeline-based dashboard for tracking reporting deadlines, budget periods, document status, and subrecipient compliance across multi-agency federal grant portfolios.

### What it does

- Dashboard summary showing overdue, due soon, upcoming, and submitted counts at a glance
- Timeline view grouped by month with a progress bar showing completion rate per period
- List view for a flat, deadline-sorted view of all items
- Filter by agency (CDC, EPA, HHS, IHS, SAMHSA) and type (reporting, budget, document, subrecipient)
- Click any item to expand full detail — grant number, award amount, budget period, responsible party, and compliance notes
- Fully responsive and supports light/dark mode

### Why I built it

This is the tool I actually needed at work. Managing reporting deadlines, subrecipient monitoring schedules, and budget period end dates across multiple federal agencies in a spreadsheet is how things get missed. A visual, filterable tracker with built-in compliance context is the gap this fills.

### Tech

- HTML5, CSS3 (custom properties, CSS Grid, responsive layout)
- Vanilla JavaScript — no frameworks or dependencies

### Domain knowledge reflected

- Grant data uses real agency names, portal references (PMS, GrantSolutions, CDC PHEP portal), and form numbers (SF-425)
- Compliance notes cite specific regulatory requirements (2 CFR §200.332, GPRA, 3-year retention rule)
- Subrecipient monitoring logic reflects actual pass-through entity obligations under Uniform Guidance

---

## About

I'm a contracts and compliance professional with a background spanning federal grant administration, fintech, and public sector legal operations — and a self-taught front-end developer. These projects sit at that intersection intentionally: domain knowledge driving the logic, code making it usable.

**Connect:** [linkedin.com/in/hirecrystalgee](https://linkedin.com/in/hirecrystalgee) · hirecrystalgee@gmail.com

---

*More projects in progress — contract review assistant (AI-powered) and audit readiness checklist coming next.*
