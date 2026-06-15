# Bridging the Gap: Extended Game Development Projects for Student Employability and Experiential Learning

[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Status](https://img.shields.io/badge/Status-In%20Revision-orange.svg)](#revision-todo-csedu-2026-192-reviewer-feedback)

## Authors

- **Drew A. Clinkenbeard** - California State University, Monterey Bay
  ORCID: [0000-0002-5694-1198](https://orcid.org/0000-0002-5694-1198)
  Email: dclinkenbeard@csumb.edu

## Abstract

This work-in-progress paper examines a 14-week intensive summer research project designed to bridge the gap between academic preparation and industry requirements in game development. The project engaged four undergraduate computer science students at California State University, Monterey Bay in authentic roguelite game development, combining experiential learning theory with professional software development practices. Students developed a Unity-based game featuring core combat mechanics, procedurally generated content, and custom art assets while learning collaborative workflows through Git/GitHub, code review practices, and agile methodologies.

Preliminary results demonstrate substantial student learning across technical, professional, and metacognitive domains. Analysis reveals four distinct developmental phases enabled by the extended timeline: foundation building, core feature development, iteration and refinement, and architectural maturity. Student self-assessments document significant confidence growth, technical skill acquisition, and transformation from task-completion to creative ownership. The project validates Kolb's Experiential Learning Theory in action and provides empirical evidence that extended timelines produce qualitatively different outcomes than typical semester projects.

Findings suggest implications for curriculum design, summer research program models, and employability interventions at teaching-focused institutions serving workforce-bound students.

## Revision TODO (CSEDU 2026 #192 reviewer feedback)

Source: `../paper_reviews_CSEDU_2026/Reviews_CSEDU_2026_192.pdf`
Scores: R1=4, R2=2, R3=2, R4=2. Three reviewers wanted major revisions; topic relevance/significance scored well, so the contribution holds — the evidence and presentation are what need work. Goal: address these before targeting the next venue.

### Quick wins (unblock major-revision concerns first)
- [ ] **Add an ethics statement** — IRB approval + informed consent for the four students. *(R3, blocker)*
- [ ] **Rewrite abstract** to include concrete results, not just claims. *(R4)*
- [ ] **Restructure introduction**: fold short subsections into paragraphs; add a roadmap paragraph at the end describing paper organization. *(R4)*

### Methodology rewrite (heaviest lift — blocks R2 and R3)
- [ ] **Name and describe the qualitative analysis framework** (e.g., reflexive thematic analysis): coding procedure, who coded, how themes were derived from reflections and faculty observations. *(R3)*
- [ ] **Triangulate self-reported data** with at least one objective measure beyond raw commit counts: independent expert code review, rubric-scored artifact eval, or formal assessment of the PCG algorithms. *(R3)*
- [ ] **Add replicability context**: student class year, that it was a paid research position (currently buried until §5.3.3), curriculum design, project assessment rubric, data-collection protocol. *(R2)*
- [ ] **Own the n=4 limitation** explicitly in the discussion. *(R2, R3)*

### Results & evidence
- [ ] **Document the PCG / Wave Function Collapse work** — abstract promises it, body defers to future work. Reviewers flagged this gap. *(R2)*
- [ ] **Add more student reflection excerpts** organized by theme; currently only one programmer quote and one artist quote. *(R2)*
- [ ] **Make the metrics → employability link explicit** — define which metrics predict employability and how. *(R4)*
- [ ] **Contextualize the 2,225 LOC figure** — R2 read this as thin output. Frame what counts (engine work, asset pipeline, system design) or drop the raw count.
- [ ] **Tie Results/Discussion to the RQs**, and revisit the RQs in the Conclusion. *(R4)*

### Figures
- [ ] **Add figures** — paper currently has none. *(R2, R4)* Suggested:
  - [ ] Project artifact screenshot (gameplay, generated dungeon)
  - [ ] Architecture / pipeline diagram (WFC system or Unity project structure)
  - [ ] 14-week timeline showing the four developmental phases
  - [ ] RQ → metric → evidence mapping diagram

### Literature review
- [ ] **Broaden geographically and chronologically** — more recent international (esp. Western) experiential-learning and gamification studies in CS ed. *(R3)*
- [ ] **Consider adding** Papadakis & Karakose (2025) on gamification & achievement; Zourmpakis, Kalogiannakis, & Papadakis (2023) on adaptive gamification frameworks. *(R3 suggestion)*

### Conclusions / Future Work
- [ ] **Strengthen Future Work section** — R2 specifically endorsed the longitudinal tracking idea (6 mo / 1 yr / 2 yr); make the plan concrete (instruments, recruitment, IRB path).
- [ ] **Make Conclusion answer the RQs** rather than restate findings. *(R4)*

### Presentation polish
- [ ] **Reference formatting** — citation markers should map cleanly to the bib list. *(R4)*
- [ ] **Verify every reference exists** (DOI/venue) — R3 hinted at possible AI-fabricated citations. *(R3)*
- [ ] **Re-edit intro transitions** in your own voice — R3 flagged "formulaic" structural transitions as a soft AI-writing concern.
- [ ] **Proofread pass** for stylistic inconsistencies and non-standard phrasing. *(R3)*

### Venue-specific: WorldTLE 2026 (Milan, Italy, 16–18 October 2026)

Target venue is the **4th World Conference on Teaching, Learning, and Education (WorldTLE)**, https://www.worldtle.org/. Templates are in `../WORLDTLE/` (`Abstarct-Format.doc`, `fullpaper_format-WORLDTLE.doc`).

**Abstract deadline: 25 September 2026.** Early registration: 6 July 2026. Process: submit abstract first → 7–14 day review → full paper on acceptance.

#### Format requirements (from WorldTLE templates — confirmed)
- [ ] **Convert from LaTeX/ACM to Word** — submission is `.doc/.docx` or PDF, Times New Roman, specific point sizes per template. The current ACM `sigconf` LaTeX source does not apply.
- [ ] **Switch citations to APA 7th edition** — in-text `(Author, year)`; re-render `references.bib` in APA. (Fold the "verify every reference exists" check into this conversion.)
- [ ] **Use IMRaD structure** (Introduction, Methods, Results, Discussion) — template explicitly recommends it.
- [ ] **Abstract: 200–250 words, single paragraph, no indentation**; max 5 keywords (English, alphabetical, semicolon-separated, not repeating title words).
- [ ] **Filename convention**: `Clinkenbeard_PAPER`.
- [ ] Copyright is CC BY 4.0 with the conference as original publisher.

#### Reframe for an education (not CS-education) audience
- [ ] **Reposition the abstract** around pedagogy + experiential learning theory; demote Unity/WFC/game-dev technicals to supporting detail.
- [ ] **Foreground Kolb's ELT** as the theoretical contribution.
- [ ] **Translate CS-specific jargon** (WFC, roguelite, agile sprints) into pedagogy terms (authentic task complexity, iterative design cycles, scaffolded mentorship).
- [ ] **Strengthen the "extended timeline" claim** — this is the cross-disciplinary insight that travels beyond CS.

#### Abstract-round priorities (due 25 September 2026)
- [ ] Rewrite abstract with concrete results, formatted to the WorldTLE template *(R4 + WorldTLE fit)*
- [ ] Add ethics statement to manuscript *(R3 — blocker)*
- [ ] Confirm authorship/affiliation block matches WorldTLE template (full names, full affiliation incl. country, corresponding author marked)

#### Full-paper round (after abstract acceptance)
- [ ] Apply the rest of the CSEDU revisions (methodology, figures, LR expansion, RQ alignment)
- [ ] Complete the Word/APA 7th/TNR conversion above

## Publication Details

- **Status:** Unpublished manuscript — in revision. **Not currently submitted, under review, or published at any venue.**
- **Review history:** Submitted to CSEDU 2026 (paper #192); reviews received, **not accepted**. That process is closed — the manuscript is not under review anywhere at this time.
- **Intended next venue:** 4th World Conference on Teaching, Learning, and Education (WorldTLE 2026), Milan, Italy, 16–18 October 2026 — *intended, not yet submitted.* https://www.worldtle.org/
  - Abstract deadline: **25 September 2026**
  - Early registration: 6 July 2026
  - Submission model: abstract first → 7–14 day review → full paper after acceptance of abstract
- **Type:** Work-in-Progress Paper
- **Format:** Currently ACM `sigconf` LaTeX (from the CSEDU submission). WorldTLE requires **Word (.doc/.docx) or PDF, Times New Roman, APA 7th edition citations, IMRaD structure** — a conversion is required (see Revision TODO). Templates: `../WORLDTLE/`

## Keywords

- Experiential learning
- Game-based learning
- Procedural content generation
- Project-based learning
- Computer science education
- Student employability
- Wave function collapse

## CCS Concepts

- **Social and professional topics → Computing education**
- **Computing methodologies → Procedural animation**

## Repository Contents

This repository contains the final PDF of the paper:

- `bridging-gap-game-dev-employability.pdf` - The compiled paper in PDF format

## How to Cite

This manuscript has not been accepted or published. If referencing it informally, please cite as an unpublished manuscript:

```bibtex
@unpublished{clinkenbeard_bridging,
  author = {Clinkenbeard, Drew A.},
  title  = {Bridging the Gap: Extended Game Development Projects for Student Employability and Experiential Learning},
  year   = {2026},
  note   = {Unpublished manuscript, in revision}
}
```

A formal citation will be added once the paper is accepted at a venue.

## Research Context

This research was conducted as part of the RSCA 2254 project at California State University, Monterey Bay. The study examines how extended, authentic game development projects can bridge the gap between academic preparation and industry requirements, with specific focus on:

1. **Experiential Learning Theory Application:** Validating Kolb's four-stage cycle in a game development context
2. **Extended Timeline Impact:** Comparing 14-week summer projects to typical 5-week semester projects
3. **Professional Practices Integration:** Teaching collaborative workflows, code review, and agile methodologies
4. **Student Development Phases:** Identifying four distinct phases of growth enabled by extended engagement
5. **Employability Enhancement:** Documenting confidence growth and skill acquisition for workforce readiness

## Project Highlights

The research project featured:

- **Unity-based roguelite game development** with procedurally generated content
- **Wave Function Collapse (WFC) algorithm** implementation for dungeon generation
- **Professional software development practices** including Git/GitHub workflows
- **Agile methodologies** with weekly sprints and retrospectives
- **Custom art asset creation** and integration
- **Core combat mechanics** and game systems development

## Related Resources

- GitHub Repository (Game Project): *[To be added if public]*
- CSUMB School of Computing and Design: [https://csumb.edu/scd/](https://csumb.edu/scd/)

## License

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

You are free to share and adapt this material for non-commercial purposes, provided you give appropriate credit and distribute any derivative works under the same license.

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

© 2026 Drew A. Clinkenbeard

## Contact

For questions about this research, please contact:

- Drew A. Clinkenbeard: dclinkenbeard@csumb.edu
- California State University, Monterey Bay
- School of Computing and Design
- Seaside, CA, USA

## Acknowledgments

This research was supported by California State University, Monterey Bay. We thank the four undergraduate students who participated in this summer research project for their dedication, creativity, and valuable feedback that made this study possible.

---

**Status:** Unpublished manuscript — in revision following CSEDU 2026 reviews. Not submitted, under review, or published anywhere; intended next venue is WorldTLE 2026 (Milan).
**Submission Type:** Work-in-Progress Paper

*Last Updated: June 2026*
