# dimer
PHCY 502 + 503 + 512 Integration Project

# DiMER Faculty Resource Site

This repository hosts a static site for DiMER-related faculty resources, available at:

> https://scottsin.github.io/dimer/

The site collects HTML resources that explain and operationalize the DiMER framework (Disease → Mechanism → Exposure → Response) across PHCY 502, PHCY 503, and PHCY 512.

The content is designed for **faculty use**, not for students directly.

---

## What’s Here

The site is a set of standalone HTML pages with a shared visual style (Avenir Next / Source Sans 3, neutral cards, course-color accents). There is no backend; everything is static.

Key pages include:

- **index.html**  
  DiMER – Faculty Resource Hub landing page that links to all other DiMER resources for faculty.

- **DiMER – Student Cognitive Transformations**  
  Narrative overview of the key cognitive shifts we want students to undergo for DiMER-based reasoning.

- **DiMER – Table of Student Transformations**  
  Literature-grounded table mapping each transformation to cognitive constructs and key references.

- **DiMER – MTP Brief**  
  How Medication Therapy Problems (MTPs) function as pharmacists’ “diagnoses,” and how DiMER, Bayesian reasoning, and MDP framing support MTP scripts.

- **DiMER – Script Types Cheat Sheet**  
  Illness, medication, and MTP scripts, and how all three sit on the Disease → Mechanism → Exposure → Response backbone.

- **DiMER – Terms to Scripts** and **DiMER Terms to Scripts Table Collapsible**  
  How core DiMER terms map onto script types and MTP reasoning, including a table/interactive-style view.

- **DiMER Weekly Operational Overview**  
  How DiMER is operationalized across the teaching week, including typical contributions from PHCY 502, 503, and 512.

- **DiMER – Basic-Faculty**  
  Audience-specific one-pager for CBMC/DPMP colleagues (PHCY 503 + 512).

- **DiMER – Clinical-Faculty**  
  Audience-specific one-pager for DPET/PACE clinical colleagues (PHCY 502).

- **DiMER – “What’s In It for Me?”**  
  Cross-cutting brief that summarizes DiMER’s benefits for foundational and clinical faculty.

- **DiMER – Four Wins Brief**  
  Overview of the four “wins” of DiMER operationalization across the three courses.

- **DiMER – Cognitive Load Rationale**  
  Rationale for the cognitive load and sequencing decisions built into DiMER.

- **DiMER – Deep Structure Memo**  
  Memo on the deeper reasoning architecture DiMER is intended to cultivate (scripts, MTP reasoning, Bayes/MDP framing).

---

## How to Use the Site

**For faculty:**

- Start at the **Faculty Resource Hub** (home page).  
- Use the audience-specific pages:
  - *DiMER – Basic-Faculty* for CBMC/DPMP (PHCY 503 + 512),
  - *DiMER – Clinical-Faculty* for DPET/PACE (PHCY 502),
  - *DiMER – What’s In It for Me?* for a quick “why this matters” overview.
- Use the transformation and script resources when:
  - Designing or revising sessions and cases, or
  - Explaining to colleagues what kind of reasoning we expect from students.

**For local/offline use:**

If needed, you can download the repository as a ZIP and open the HTML files directly in a browser. The landing page (`DiMER - Faculty Resource Hub.html`) will still work as an offline hub as long as all files stay in the same folder.

---

## Editing and Contributions

This is a static HTML site; there is no build step.

- Minor wording or typo fixes can be made by editing the relevant `.html` file and committing the change.
- To keep the look-and-feel consistent:
  - Reuse the shared CSS variables and card layout already present in existing pages.
  - Keep Avenir Next for headings and Source Sans 3 for body text, as described in the course HTML style guide.

If you add a new resource:

1. Create a new `.html` file following the existing style.
2. Add a link to it from the **Faculty Resource Hub** page.
3. Commit and push; GitHub Pages will rebuild automatically.

---

## GitHub Pages Configuration

- **Branch:** `main` (or the branch configured in GitHub Pages settings).
- **Site URL:** https://scottsin.github.io/dimer/
- **Structure:** Static HTML only; no frameworks or bundlers.

If the site does not update after a change, verify the GitHub Pages settings for the repository and trigger a new commit (GitHub Pages deployments are tied to pushes).

---

If you are a faculty colleague exploring DiMER for the first time, the recommended starting sequence is:

1. **DiMER – What’s In It for Me?**  
2. **DiMER – Student Cognitive Transformations**  
3. **DiMER – Script Types Cheat Sheet**  
4. Your role-specific page (*Basic-Faculty* or *Clinical-Faculty*).
