# My prompts:
For our HCI midterm project, based on the criteria mentioned by my professor in criteria.md, we currently have two distinct proposals.

The first proposal is the shared night street block, for which we already have some initial ideas in proposal.md. The second, newer idea is a plant companion: a plant and its pot would include sensors that allow the system to personalize the plant, support creative human-plant interaction, and enable plant-plant interaction through an agent. It could also support sharing among humans, friends, and plants, while possibly incorporating environmental awareness.

As a critic in the HCI field, a rigorous HCI researcher, and an innovator, please critique these two ideas. Analyze their potential, evaluate their strengths and weaknesses, and help us decide which proposal we should ultimately choose.

# Critique: Night City Block vs. Plant Companion

A rigorous HCI / HAX evaluation of two candidate semester-project directions, written against Prof. McGee's 8 Fundamental Questions and the criteria.md rubric (motivation, literature review, objectives/RQs).

---

## 0. Reviewer's stance

Both proposals share the team's core values from `planning.md`: artistic, physical-over-digital, calm-tech, gentle social. Both are *plausible* projects. The job of this critique is not to declare a winner on aesthetic grounds but to assess where each idea sits relative to (a) the existing HCI literature and (b) what is realistically defensible in a semester-scale project. I am intentionally harsh, because flattering critique is useless to you.

The headline finding: **the two proposals are not in the same maturity class.** Night City Block has a sharply identified literature gap and a clean RQ structure already on the page. The Plant Companion idea, as currently sketched, lands in one of the most over-cultivated subfields in HCI today, and its novelty contribution is unclear without serious scoping work that has not yet been done.

---

## 1. Proposal A — Night City Block (existing proposal.md)

### 1.1 What is strong

**Motivation is genuinely tight.** The ABT structure is doing real work: digital connectivity is documented as up (Roberts et al. 2025, Holt-Lunstad meta-analyses), the costs of notification-driven attention are documented (Kushlev & Dunn 2016), and the inferential leap to "ambient, expressive, low-demand systems are underexplored for *young-adult intimate friend groups*" is small and defensible. The pain point is real, and importantly, it is empirically grounded rather than a designer's intuition.

**The literature review identifies a specific, narrow gap.** The two stated gaps — (1) ambient awareness systems mostly convey *presence/availability* not *expressive identity*, and (2) privacy is almost always managed via settings rather than spatial metaphor — are both supportable from the cited literature (Dey & Guzman 2006; Markopoulos et al. 2004; Hassenzahl et al. 2012; CareNet). These are non-trivial gaps; they are also gaps that a 1-semester project can plausibly contribute to.

**The RQ-to-objective mapping is clean.** RQ1 (expressive vs. presence-only) maps to Objective 3. RQ2 (architectural privacy) maps to Objective 2. RQ3 (which design elements matter) is the salience question that makes the field study interpretable. Each RQ is testable: you can run a between-subjects or within-subjects deployment and measure with ABC-Q (Markopoulos et al. 2004) plus qualitative interviews.

**The 8-questions self-assessment is honest** — it does not claim the contribution is "vital" without qualification, and it locates the disciplinary fit precisely (calm tech / ubicomp / CSCW).

### 1.2 What is weak or under-defended

- **The originality claim rests on a *combination* argument** ("no existing system combines: night-city metaphor + diary-to-atmosphere + architectural privacy + physical artifact"). Combination novelty is acceptable in HCI but it is the weakest form of contribution. A reviewer at CHI would push back: which of the four ingredients is the actual claim? If it is *architectural/spatial privacy as an alternative to settings menus*, that is the strongest single contribution and it deserves to be promoted from one of three RQs to *the* RQ.
- **The "diary-driven generation" pipeline is hand-waved.** "A drawing becomes street art on their wall. A chosen color tints their window light." With current generative models this is technically straightforward, but it is also where most of the user-experience risk lives — the legibility of the mapping (does my friend recognize that the dim warm lamp = me having a quiet day?) is the actual research question hiding inside the system design. The proposal does not yet acknowledge this.
- **5 participants × 3–4 weeks is thin for two RQs simultaneously.** This is a real operational risk, but it is not a reason to reject the proposal — it is a reason to scope down to RQ1 and RQ2 and treat RQ3 as exploratory.
- **The physical artifact is listed as "optional."** Optionality is a tell. Either the artifact is core to the calm-tech thesis (in which case commit to it and accept the build cost) or it is decorative (in which case cut it from the proposal so the focus is sharper). Right now it is doing rhetorical work — invoking Tangible Bits — without doing study work.
- **No baseline / control condition specified.** RQ1 implicitly compares to "a baseline of no ambient display," but a methodologically stronger baseline is a *presence-only* version of the same system (just window-lights, no diary-driven expressive content). That comparison is what isolates the contribution.

### 1.3 Score against McGee's 8 questions

| Question | Verdict |
|---|---|
| Research problem clear? | Yes — sharp. |
| Significant? | Yes — loneliness/connection literature carries this. |
| Contribution to knowledge? | **Combinational; would be stronger if focused on architectural privacy alone.** |
| Vital? | Plausibly — it speaks to a class of systems, not one product. |
| Original? | **Combination-novel, not primitive-novel.** Acceptable but defensible only with care. |
| How readers know? | Lit review demonstrates the gap; OK. |
| Validity? | Mixed-methods is right; needs control condition. |
| Disciplinary fit? | Clean — calm tech / CSCW. |

---

## 2. Proposal B — Plant Companion (new idea)

### 2.1 What the idea actually is, restated

A potted plant with sensors in/around the pot becomes (a) a *personalized companion* for the human, (b) a node in a *plant-to-plant* network mediated by a software agent, (c) a *social channel* between human friends via their respective plants, with optional environment-awareness. The team's calm-tech / artistic / physical-over-digital values map onto this naturally.

### 2.2 The hard problem: this is one of the most saturated subfields in HCI right now

I want to be direct here, because the planning document explicitly flags the team as "interest-first, research-second" — which is fine, but it means the team needs to *know* when an interest has already been heavily worked over, and human-plant interaction is exactly that case.

A non-exhaustive map of what already exists:

- **Chang, Shen, Maheshwari, Danielescu & Yao (2022).** *Patterns and Opportunities for the Design of Human-Plant Interaction.* DIS 2022. This is a **full design-space taxonomy** of HPI — sensing techniques, embedding strategies, integration patterns. If you propose an HPI system, this paper is the one a reviewer will check your novelty against first.
- **Hauser et al. (2022).** *A Biocentric Perspective on HCI Design Research Involving Plants.* ACM TOCHI. A meta-review of 47 HPI papers (11 at CHI alone) re-framing the design ethics. This means HPI is not just a topic — it has its own methodological discourse.
- **Webber, Kelly, Wadley & Smith (2023).** *Engaging with Nature through Technology: A Scoping Review of HCI Research.* CHI 2023. Another full review.
- **Heitlinger, Houston & others (2024–2025).** The "more-than-human design" turn in HCI is now a named subfield with its own special issues (HCI Journal special issue 2024; ACM Interactions XXXII.2, March–April 2025). Plants are central to it.
- **PlantMate (CHI EA 2025)** — bidirectional touch-based system for human-plant empathy with EMG + EMS.
- **PlantWhisperer (CHI EA 2026)** — LLM-driven chatbot characters representing individual plants, evaluated for wellbeing. This is *strikingly close* to "personalized plant companion."
- **NugiTex (DIS 2023)** — wearable that conveys plant comfort via haptic cues.
- **I/O Plant** — toolkit specifically for designing augmented human-plant interactions.
- **PLEASED, Cyborg Botany** — embedded electrode work treating plants as sensors.
- **"Other Intelligences" (Castellanos & Valverde, 2024)** — *already does plant-to-plant communication via technology, in domestic spaces, with users interpreting plant relationships as friendships.* This is the most worrying reference for the team's idea, because it covers the plant-plant-via-agent angle directly.
- **Sonifying Aquatic Plant Photosynthesis (DIS 2025)** — music generation system for plant care in everyday context, *and explicitly criticizes prior HPI work for "overemphasis on visual representation and instrumentalization of plant organs."*
- **PlantTalk / Gemini-API plant talking apps (arXiv 2024)** — IoT plant + LLM "the plant talks back" pattern is now in the consumer/student-project zone, not the research-frontier zone.

This is not a literature with a few scattered papers. It is a literature with **review papers, taxonomies, a named methodological turn, and consumer-grade implementations of the headline concepts.**

### 2.3 The novelty problem in concrete terms

Apply McGee's "originality" question to each component of the proposed system as currently described:

| Component of plant-companion idea | Has been done? | Where |
|---|---|---|
| Sensorized pot, plant biosignals → human feedback | Yes, extensively | Chang et al. 2022 taxonomy; PLEASED; Guttation Monitor; I/O Plant |
| Plant as personalized companion / character | Yes | PlantWhisperer (CHI EA 2026); PlantMate; Tamagotchi lineage |
| Plant-plant communication mediated by agent | Yes | "Other Intelligences" (Castellanos & Valverde 2024) |
| Plant-mediated social connection between human friends | **Less explored** — this is the *only* corner with real space | (gap in current literature) |
| Environment-awareness layer | Yes | Wen & Wu, *Slowing Plants, Slowing Home*; smart-city HPI work |

So there is exactly **one** place where the idea has clear room to breathe: **plants as a medium of gentle social connection between geographically separated friends**, building on the team's calm-tech / "social but gentle" values from `planning.md`.

But — and this is the critical observation — that exact framing is **structurally identical to Night City Block**, just with a different aesthetic skin (a plant instead of a city block). The underlying HCI contribution would be: *expressive ambient social awareness via a shared living artifact, with calm-tech principles, for intimate friend groups.* That is the Night City Block thesis.

### 2.4 What is genuinely strong about the plant idea

Setting aside the novelty problem, the plant idea has real merits:

- **Liveness.** A real plant is not a screen. It already grows, wilts, smells, casts shadows. The artifact does design work for free that the night-city must simulate. This is a serious calm-tech advantage.
- **Asymmetric care relationship.** A plant *needs* you in a way a city block does not. That asymmetry is interesting and underexplored as a social-bonding mechanism (you and your friend are co-tending something fragile). The PlantWhisperer paper gestures at this for individuals; the *shared-care across friends* angle is less developed.
- **Built-in temporal slowness** that fits calm-tech principles natively (Wen & Wu's "slowing plants, slowing home" argument).
- **Stronger physicality story** than the night-city's optional artifact.

### 2.5 What is weak or under-defended

- **No paper-level literature has been done yet.** The proposal is a paragraph; the night-city proposal is a 12-source literature review. This is not a fair comparison and is itself a signal of project readiness.
- **The pain point is unclear.** Why does a person need a plant companion? "Loneliness" is the implicit answer, but loneliness motivates Night City Block too, and at the moment Night City Block has the loneliness literature lined up cleanly. The plant proposal would need to either (a) anchor on a *different* pain point (plant-care wellbeing? eco-attunement? environmental-awareness?) or (b) re-derive the loneliness pain point in terms specific to plants.
- **"Personalize the plant" needs operational definition.** Personalize how? Each plant has a different LLM persona? A different sensor calibration? A different visual aura? The phrase is doing too much rhetorical work for a research proposal.
- **Plant-plant interaction "via the agent" is the most ethically loaded piece.** The more-than-human / biocentric HCI literature (Hauser et al. 2022; Hansen & Rolighed DIS 2024 on subverting "instrumentalization") will read "plant-plant communication via a software agent" as *instrumentalizing the plants for human entertainment*, which is precisely what that subfield has spent five years critiquing. This is not fatal but it is a *minefield* the team would need to navigate, and one Night City Block entirely sidesteps.
- **Hardware risk.** Real biosignal sensing (EMG on philodendrons, conductance, electrochemical) is finicky, noisy, and time-consuming to debug. This is well-documented across the I/O Plant and PLEASED line of work. A team that wants a working field-deployable prototype in one semester is taking on a significant engineering risk by going this route — risk that the night-city, which is essentially a software prototype with optional hardware, does not carry.
- **The interaction-modality question has no candidate yet.** The team's design space variables `<a_way>` are listed as drawing, rhythm, breathing, movement. Which of these is the input to the plant system? If the answer is "we'll figure that out" then the project does not yet have a research question, only a topic.

### 2.6 Score against McGee's 8 questions

| Question | Verdict |
|---|---|
| Research problem clear? | **No — currently a topic, not a question.** |
| Significant? | Plausibly, but the significance argument has not been made. |
| Contribution to knowledge? | **Risk of being non-novel** unless scoped to plant-mediated friend-to-friend connection specifically. |
| Vital? | Cannot judge until scoped. |
| Original? | **Major risk.** Multiple existing systems cover the headline concepts. |
| How readers know? | No literature review has been done yet. |
| Validity? | TBD. |
| Disciplinary fit? | Yes — multispecies / more-than-human HCI is a real subfield. |

---

## 3. Head-to-head comparison

| Dimension | Night City Block | Plant Companion |
|---|---|---|
| Motivation already supported by literature | **Strong** | Weak (not yet done) |
| Literature gap clearly identified | **Yes (2 specific gaps)** | No — and the available gap may be the same gap as A |
| Research questions testable | **Yes** | Not yet stated |
| Risk of overlap with existing work | Low–medium (combination novelty) | **High** (subfield has reviews and taxonomies) |
| Engineering risk in 1 semester | Medium | **High** (biosensing, hardware) |
| Fits team's values (artistic/physical/calm/gentle) | Yes | Yes (arguably better on physicality) |
| Connects to a recognised HCI subfield | Calm tech, CSCW, ambient awareness | More-than-human / multispecies HCI |
| Empirical evaluation feasible | Yes (ABC-Q + interviews + logs) | Yes in principle, but design-dependent |
| Defensible against McGee's 8 questions today | **Mostly yes** | Partially — major work remaining |

---

## 4. Recommendation

**Proceed with Night City Block as the primary proposal.** It is closer to submission-ready, the literature gap is articulated, the RQs are testable, and the engineering risk is bounded.

But proceed with three **specific revisions** that absorb the best of the plant idea:

1. **Sharpen the contribution claim** away from "novel combination of four elements" toward **architectural/spatial privacy as an alternative to settings-based privacy in expressive ambient awareness systems.** That is a primitive-novel contribution, not a combinational one. RQ2 becomes the headline.
2. **Add a presence-only baseline condition** to the field study so that RQ1 has a real comparison, not a null. Without this, RQ1 is unfalsifiable.
3. **Either commit to or cut the physical artifact.** "Optional" is the wrong word in a research proposal. If the calm-tech / Tangible Bits framing is doing work in your literature review (and it is), the artifact has to ship. If you cannot build it in time, drop the Tangible Bits framing and rewrite the lit review around screen-based ambient displays only — both are defensible, "optional" is not.

**Why not the plant idea?** Not because it is bad — it has real strengths, especially the liveness and asymmetric-care angles — but because **the version of it that is genuinely novel reduces to "Night City Block, but with a plant instead of a building," and Night City Block already has the work done.** The plant version would require the team to (a) do a fresh literature review against a saturated subfield, (b) navigate the more-than-human ethics discourse carefully, and (c) absorb significant biosensing hardware risk, all in the same semester. That is not a winning trade.

**If the team wants to keep a piece of the plant idea**, the most defensible move is to fold *one* element into Night City Block: **a small living plant somewhere in the physical-artifact layer, whose state (watered today / wilting / new leaf) becomes one of the ambient signals reflected in the user's block.** This preserves the plant's liveness affordance, sidesteps the saturated HPI subfield (because the plant is a peripheral signal source, not the research object), and reinforces the calm-tech argument. It does not require new research questions.

---

## 5. The hard question, asked plainly

If at the end of the semester your final report had to answer Prof. McGee's question *"How do readers know it's original?"* — which proposal can you answer for **today**, with the references already in your bibliography?

For Night City Block, the answer is on the page (`§2.7 Knowledge Gaps This Project Addresses`).

For Plant Companion, the honest answer is: *we don't know yet, and the literature suggests we may not like the answer when we find it.*

That is the decision.
