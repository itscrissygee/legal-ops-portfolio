# Legal Ops Portfolio — Crystal Grossley

**Live demo:** https://itscrissygee.github.io/legal-ops-portfolio/

> A collection of legal operations and contract management tools built to demonstrate both domain expertise and front-end development skills.

---

## Project 1 — Contract Request Intake Form

A multi-step contract intake form with dynamic workflow routing, built in vanilla HTML/CSS/JS.

### What it does

- Guides requestors through a 4-step intake process: contract type → parties & scope → risk & value → submitter info
- Dynamically routes based on contract type — vendor agreements, MOUs, interagency agreements, grant subawards, NDAs, and custom contracts each get a distinct approval pathway
- Auto-calculates risk level (low / medium / high) based on contract value and federal funding involvement
- Generates a tailored approval workflow on submission, including relevant compliance checkpoints (OMB Uniform Guidance, SAM.gov verification, tribal regulatory review)
- Produces a submission summary with a unique reference number
- Fully responsive — works on desktop and mobile
- Supports light and dark mode via CSS custom properties

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

## About

I'm a contracts and compliance professional with a background spanning federal grant administration, fintech, and public sector legal operations — and a self-taught front-end developer. These projects sit at that intersection intentionally: the domain knowledge driving the logic, the code making it usable.

**Connect:** [linkedin.com/in/hirecrystalgee](https://linkedin.com/in/hirecrystalgee) · hirecrystalgee@gmail.com

---

*More projects coming — contract clause library and federal grant compliance tracker in progress.*
