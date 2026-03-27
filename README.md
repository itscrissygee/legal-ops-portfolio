# Legal Ops Portfolio — Crystal Grossley

**Live demo:** https://itscrissygee.github.io/legal-ops-portfolio/

> A collection of legal operations and contract management tools built to demonstrate both domain expertise and front-end development skills.
 
---
 
## Projects
 
| Project | Description | Live Demo |
|---|---|---|
| Contract Request Intake | Multi-step intake form with workflow routing | [View](https://itscrissygee.github.io/legal-ops-portfolio/) |
| Contract Clause Library | Searchable clause reference with comparison tool | [View](https://itscrissygee.github.io/legal-ops-portfolio/clause-library.html) |
 
---
 
## Project 1 — Contract request intake form
 
A multi-step contract intake form with dynamic workflow routing, built in vanilla HTML/CSS/JS.
 
### What it does
 
- Guides requestors through a 4-step intake process: contract type → parties & scope → risk & value → submitter info
- Dynamically routes based on contract type — vendor agreements, MOUs, interagency agreements, grant subawards, NDAs, and custom contracts each produce a distinct approval pathway
- Auto-calculates risk level (low / medium / high) based on contract value and federal funding involvement
- Generates a tailored approval workflow on submission, including relevant compliance checkpoints (OMB Uniform Guidance, SAM.gov verification, tribal regulatory review)
- Produces a submission summary with a unique reference number
- Fully responsive and supports light/dark mode via CSS custom properties
 
### Why I built it
 
In my work reviewing contracts and MOUs across federal grant portfolios, I noticed that intake is where most delays originate — requestors don't know what information is needed, which approval path applies, or how risk level affects timeline. This tool addresses that gap by surfacing routing logic at the point of submission rather than after.
 
### Tech
 
- HTML5, CSS3 (custom properties, CSS Grid, responsive layout)
- Vanilla JavaScript — no frameworks or dependencies
- Zero external libraries — loads instantly, works offline
 
### Domain knowledge reflected
 
- Contract types mapped to real-world routing workflows (tribal governance, OMB Uniform Guidance, federal subaward compliance)
- Risk tiers based on dollar thresholds and federal funding status, consistent with standard procurement policy
- Approval pathways include compliance-specific checkpoints (subrecipient risk assessment, SAM.gov, board notification thresholds)
 
---
 
## Project 2 — Contract clause library
 
A searchable reference library of standard contract clauses with drafting notes, risk ratings, and side-by-side comparison — built in vanilla HTML/CSS/JS.
 
### What it does
 
- 12 clauses across three categories: confidentiality & data use, payment & compensation, and federal compliance
- Full-text search across clause titles, descriptions, contract language, and drafting notes simultaneously
- Filter by category (pill navigation) and risk level (dropdown) independently or combined
- Expand any clause to read the full contract language plus practical drafting notes
- Select multiple clauses and compare them side by side to evaluate language differences
- Fully responsive and supports light/dark mode
 
### Why I built it
 
Contracts professionals regularly reference standard clause language when drafting or reviewing agreements — but that language is usually scattered across files, templates, and institutional memory. A centralized, searchable library with risk context and drafting guidance is a core legal ops infrastructure problem. This tool is a working prototype of that solution.
 
### Tech
 
- HTML5, CSS3 (custom properties, CSS Grid, responsive layout)
- Vanilla JavaScript — no frameworks or dependencies
- Zero external libraries
 
### Domain knowledge reflected
 
- Federal compliance clauses cite specific regulatory provisions (2 CFR Part 200, §200.332, §200.337, Privacy Act of 1974, FISMA)
- Drafting notes reflect real operational considerations — SAM.gov UEI transition, single audit thresholds, retroactive approval risks, tribal data sovereignty
- Risk ratings based on standard compliance and procurement risk frameworks
 
---
 
## About
 
I'm a contracts and compliance professional with a background spanning federal grant administration, fintech, and public sector legal operations — and a self-taught front-end developer. These projects sit at that intersection intentionally: domain knowledge driving the logic, code making it usable.
 
**Connect:** [linkedin.com/in/hirecrystalgee](https://linkedin.com/in/hirecrystalgee) · hirecrystalgee@gmail.com
 
---
 
*More projects in progress — federal grant compliance tracker coming next.*
