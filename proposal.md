# Project Proposal: ImmigrationOS Public Archive

**Author:** Hazuri Dhillon  
**GitHub:** [@hazuridhillon](https://github.com/hazuridhillon)  
**Live URL:** [hazuridhillon.github.io/immigrationos-archive](https://hazuridhillon.github.io/immigrationos-archive)  
**Date:** April 2026

---

## Problem Statement

In April 2025, ICE awarded Palantir Technologies a $30 million sole-source contract to build ImmigrationOS — an AI-powered platform designed to identify, prioritize, track, and deport individuals at scale. The contract was issued with no competitive bidding, justified on the grounds that Palantir's proprietary architecture made it the only possible vendor.

The system has since expanded: a $29.9 million operations and maintenance renewal followed within six months, a separate USCIS contract was signed in October 2025, and ELITE — the field-facing targeting tool — was deployed to ICE agents with access to Medicaid records, DMV files, and utility data to generate address "confidence scores" for deportation targets.

Despite the scale and implications of this infrastructure, the documentation underpinning it — government procurement justifications, civil liberties assessments, congressional letters, investigative reporting, and the Amnesty International–Palantir correspondence — is scattered across dozens of sources with no unified, publicly accessible reference point.

---

## Proposed Solution

A single-page public archive website that consolidates the complete documented record of ImmigrationOS into one navigable, sourced, and permanently hosted resource.

The archive is designed to serve journalists, researchers, advocates, students, and members of the public who need a reliable, well-organized starting point for understanding the system — its history, technical capabilities, legal implications, and the public debate surrounding it.

---

## Goals

1. **Accessibility** — Make the primary source record findable and readable without requiring access to government procurement databases or paywalled journalism
2. **Completeness** — Cover the full arc from 2011 to present, not just the 2025 contract
3. **Sourcing integrity** — Every factual claim linked to its origin document; no unsourced assertions
4. **Permanence** — Hosted on GitHub Pages, version-controlled, and open for public reference indefinitely
5. **Design quality** — Editorial, newspaper-grade presentation that treats the subject with the seriousness it deserves

---

## Scope

The archive covers six content areas:

| Section | Content |
|---------|---------|
| Overview | What ImmigrationOS is, key developments timeline sidebar |
| Timeline | Annotated 14-year history, 2011–2026, with contract amounts |
| The Three Pillars | Enforcement Prioritization, Self-Deportation Tracking, Lifecycle Operations |
| System Architecture | Data sources, ELITE tool, ICM backbone, deportation logistics |
| Civil Liberties Concerns | Fourth Amendment, healthcare data, vendor lock-in, algorithmic bias, conflict of interest, human rights due diligence |
| Sources | 27-entry reference table, fully hyperlinked, color-coded by source type |

---

## Research Methodology

Primary sources were drawn from:

- **Government procurement records** — SAM.gov (J&A-25-0092, J&A-25-0309), USASpending.gov (Task Order 70CTD022FR0000170), FPDS
- **FOIA litigation** — EPIC v. ICE (Electronic Privacy Information Center)
- **Investigative journalism** — The Washington Post, 404 Media, Axios, Fortune, The Hill, The New York Times, Biometric Update, The Guardian
- **Civil liberties organizations** — ACLU, American Immigration Council, Amnesty International, EFF, AFSC Investigate, Immigration Policy Tracking Project
- **Academic and policy analysis** — NYU Stern Center for Business & Human Rights, KFF (Kaiser Family Foundation)
- **Primary company documents** — Palantir S-1 filing (SEC), Palantir FAQ Blog, Palantir–Amnesty International correspondence (July–August 2025)
- **Congressional correspondence** — Rep. Menendez letter (Feb. 2026), Sen. Wyden / Rep. Ocasio-Cortez letter (June 2025)

All dollar figures are sourced from official federal procurement systems.

---

## Technical Implementation

- **Stack:** Plain HTML5 and CSS3 — no frameworks, no build tools, no dependencies beyond Google Fonts
- **Hosting:** GitHub Pages (free, permanent, version-controlled)
- **Typography:** Playfair Display (display headlines), IBM Plex Mono (data labels, metadata), Source Serif 4 (body text)
- **Design approach:** Editorial / investigative newspaper aesthetic — cream paper ground, double-rule borders, red accent citations, dark section for civil liberties concerns
- **Accessibility:** Semantic HTML, responsive layout, smooth scroll navigation, intersection observer for timeline animations
- **File size:** ~51KB — fast-loading, no external JS dependencies

---

## Why This Matters

ImmigrationOS represents a specific and underexamined phenomenon: the privatization of government enforcement infrastructure through proprietary vendor lock-in. Because Palantir built ICM on its own codebase starting in 2014, ICE lost the ability to competitively bid this work — permanently. The $30 million 2025 contract was not a choice; it was the inevitable consequence of a decade of architectural decisions.

The archive makes this argument visible through documentation rather than assertion. The procurement justifications, the Amnesty correspondence, the ELITE user guide, the congressional letters — together they constitute a primary source record of how AI becomes policy, how vendor relationships become infrastructure, and how that infrastructure becomes irreversible.

---

## Intended Audience

- Journalists covering immigration enforcement and surveillance technology
- Policy researchers and legal advocates working on algorithmic accountability
- Students studying AI ethics, government contracting, or civil liberties
- Members of the public seeking a reliable reference on ImmigrationOS

---

*This project was researched and built in April 2026 as a public interest resource. All sources are publicly available. The archive will remain live and version-controlled at the GitHub repository indefinitely.*