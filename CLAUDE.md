# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository nature

Research writing project, not a code project. HCI / HAX semester midterm proposal. No build/lint/test commands — deliverables are Markdown documents. Not a git repo.

## Document structure & reading order

Documents form a dependency chain. Read in this order when picking up context:

1. `criteria.md` — grading rubric + McGee's 8 Questions. Binds what the proposal must cover.
2. `planning.md` — team philosophy ("interest-first, research-second") + original generalized design-space variables (`<something>` × `<a_way>` × `<feel_something>`). Ends by pointing at `design_space.md`.
3. `design_space.md` — Night City Block design-space explosion. Tables of options across block form, diary→city mapping, street elements, weather-as-emotion, privacy-as-architecture, physical artifact. Ends with "core design tensions" (forks still open) and a recommended combination.
4. `proposal.md` — the final written artifact. Locks in choices from `design_space.md` and is organized to answer `criteria.md` directly (ABT motivation, lit review ≥5 papers, RQs, McGee table).

Edits to `proposal.md` should trace back to decisions in `design_space.md`. If a design tension there is still marked as open (Option A vs B tables), the proposal represents a resolution — don't silently re-open it.

## Core concept (load-bearing facts)

- System: **Night City Block** — shared digital night city; each user inhabits a "block" (apartment window / shopfront / rooftop). Group size ~5.
- Interaction: private daily diary (drawing / photo / color / word / voice) — diary entries are never directly shared; they **generate the atmosphere** of the user's block.
- Privacy model: **architectural, not settings-based.** Visibility is encoded spatially (interior room → window display → doorstep → street → back alley).
- Theoretical anchors: Weiser & Brown calm tech (periphery/center), Ishii & Ullmer tangible bits (graspable vs. ambient media), Dey & Guzman presence displays, Markopoulos ABC-Q connectedness, Hassenzahl relatedness strategies.
- Three RQs in `proposal.md` §4 — expressive-trace awareness (RQ1), architectural privacy (RQ2), salience of city design elements (RQ3). Changes to the concept must stay consistent with all three.

## `docs/` and `skills/`

- `docs/decisions/` and `docs/references/` exist but are empty. When writing decision records or reference captures, place them here.
- `skills/brainstorming.md` — enforces: explore context → ask clarifying questions one at a time → propose 2–3 approaches → present design in sections → write to `docs/plans/YYYY-MM-DD-<topic>-design.md`. Terminal step is invoking writing-plans, not implementation. Honor this flow before proposing new design sections.
- `skills/research-analyst.md` — role/methodology template for literature-review expansion work. Use it when adding citations or widening the lit review.

## Conventions when editing

- Citations in `proposal.md` §References are numbered and cross-referenced by author-year in prose. Keep both forms in sync when adding/removing a source.
- ABT framing (And / But / Therefore) is explicit in §1.1 — preserve the rhetorical structure when revising motivation.
- McGee's 8-Questions table in §7 is the self-assessment rubric cell — keep rows aligned 1:1 with `criteria.md`'s 8 questions.
- Minimum of 5 HCI/related papers in the lit review (from `criteria.md`). Current count is well above; don't drop below when trimming.
