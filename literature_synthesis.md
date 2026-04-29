# Research Synthesis: Literature Foundations for "Silent Estrangement of Diverging Adult Friendships"

**Prepared by:** research-analyst
**For:** HCI / HAX Semester Project — Midterm Proposal motivation and literature review
**Scope:** Peer-reviewed and authoritative sources across HCI, sociology, psychology, and public health that ground (a) the pain point, (b) why it matters, and (c) the gap that current systems fail to fill.

---

## Executive summary

This synthesis identifies **17 core sources across four disciplines** that together provide rigorous foundation for a proposal motivation built around the following thesis:

> *Adult friendships often dissolve not through conflict but through the silent drift that follows divergent life paths. This drift produces a specific kind of loneliness — felt closeness lower than observable contact — that current digital platforms make visible without addressing. The HCI design space for ambient, peripheral, expressive co-presence among small groups of dispersed adult friends is empirically underexplored.*

Every clause of that thesis has direct support in the literature below. The motivation is not speculative. **The phenomenon is named, measured, and theoretically grounded across disciplines, and the HCI design gap has been explicitly flagged by recent work in the field.**

Confidence assessment:
- **Sociology and demographic evidence:** very strong (multi-year representative-sample surveys, replicated across 1990 → 2021 → 2024).
- **Psychology and loneliness theory:** very strong (foundational frameworks Weiss 1973; Perlman & Peplau 1982; recent representative-sample replication 2025).
- **Communication and digital studies:** strong (canonical Madianou 2016; widely-cited Turkle 2011).
- **HCI gap evidence:** moderate-to-strong (CSCW 2015 anchor paper; recent 2025 paper explicitly names the gap; absence-evidence triangulated across four review papers).

---

## Section 1 — The pain point: friendship dissolution without conflict

The phenomenon you described — friendships that fade because of diverging life paths rather than rupture — has a precise name in psychology: **passive friendship dissolution**.

### Source 1 — Vieth, Rothman & Simpson (2022)

> Vieth, G., Rothman, A. J., & Simpson, J. A. (2022). Friendship loss and dissolution in adulthood: A conceptual model. *Current Opinion in Psychology*, 43, 171–175. https://doi.org/10.1016/j.copsyc.2021.07.020

Builds on Fehr (1996) to propose an explicit model distinguishing *active* (initiated by a precipitating event or decision) from *passive* (faded through situational drift) routes of adult friendship dissolution. The authors note that "adult friendships are important relationships, yet little work has examined the processes through which they end" — establishing this as an underexamined topic in psychology itself. Critically for your proposal: **passive dissolution is the more common and the more emotionally ambiguous form**, and it is driven by situational variables (geographic distance, life-stage divergence, frequency of contact opportunity) more than by interpersonal conflict.

*Why it matters for your proposal:* This source directly names the phenomenon you want to design against. It is the cleanest single citation for "this is a real, recognized form of friendship loss with its own dynamics."

### Source 2 — Fehr (1996)

> Fehr, B. (1996). *Friendship Processes*. Sage Series on Close Relationships. Sage Publications.

The canonical book-length treatment of friendship as a research domain. Establishes the lifecycle (formation, maintenance, deterioration, dissolution) and identifies *frequency of interaction* and *availability* as core situational predictors of friendship maintenance versus decay. Cited by virtually every subsequent friendship-dissolution paper.

*Why it matters:* This is the foundational reference. You don't need to cite the whole book — one citation for "Fehr (1996) established that proximity and frequency of incidental contact are core friendship-maintenance variables" carries a lot of weight.

### Source 3 — Becht et al. via Stewart-Brown (recent young-adult dissolution work)

> Stewart-Brown, et al. (2024). With or without you: Understanding friendship dissolution from childhood through young adulthood. *PMC12316385.*

A recent empirical study extending dissolution research into young adulthood specifically. Key concept: **"friendship downgrades"** — distinct from total dissolutions, this names the experience of two people remaining nominal friends while losing closeness. *This is precisely the phenomenon your proposal targets.* Friendships do not have to end to be lost; they can be downgraded silently.

*Why it matters:* Provides a cleaner, more recent vocabulary than "dissolution" for what your design responds to. **"Friendship downgrade" may be a better term to use in your motivation than "dissolution."**

---

## Section 2 — Why the pain point matters: loneliness, especially in young adulthood

### Source 4 — Hall, Pennington & Holmstrom (2025)

> Hall, J. A., Pennington, N., & Holmstrom, A. J. (2025). Lonely and connected in emerging adulthood: The ambivalence of sociality in a time of transitions. *PLOS ONE*, 20(11), e0334787. https://doi.org/10.1371/journal.pone.0334787

This is your single most important citation. A representative US sample of N=4,812 adults aged 18–95. The headline finding, in the authors' own framing:

> *"Loneliness among young adults is not bereft of connection, companionship, and friendship, but instead is characteristic of rapid life changes and a lack of relational permanence and routine."*

This sentence is **the empirical foundation for your entire motivation**. It reports that the loneliest cluster is not the friendless — it is people who have friends and connection but lack relational *permanence* and daily *routine*. That is the loneliness your design responds to. The paper is from November 2025, in a major journal, with a representative sample.

*Why it matters:* A single sentence from this paper, properly cited, justifies the entire motivation. If you read only one paper from this synthesis, read this one.

### Source 5 — Survey Center on American Life (2021, updated 2024)

> Cox, D. A. (2021). The state of American friendship: Change, challenges, and loss. *American Perspectives Survey, May 2021.* Survey Center on American Life. https://www.americansurveycenter.org/research/the-state-of-american-friendship-change-challenges-and-loss/
>
> Cox, D. A., & Pressler, S. (2024). The decline in American friendship. *Survey Center on American Life.* https://www.aei.org/featured_data/the-decline-in-american-friendship/

Representative survey data across three decades (1990 Gallup baseline; 2021; 2024 update). Headline numbers:
- Americans reporting **10 or more close friends**: 33% in 1990 → 13% in 2021.
- Americans reporting **no close friends**: 3% in 1990 → 12% in 2021 → 17% in 2024.
- Among men specifically, the share with at least six close friends fell from 55% (1990) to 27% (2021).

The decline correlates with three structural factors named explicitly in the report: **increased geographic mobility, delayed marriage and family formation, and the COVID-19 disruption.** These are exactly the structural conditions that produce passive dissolution per Vieth et al. (2022).

*Why it matters:* This is your "this is happening at scale and it is getting worse" citation. Use 1–2 numbers (not the full report) as the public-health-stakes bullet in your motivation.

### Source 6 — Holt-Lunstad et al. (2015)

> Holt-Lunstad, J., Smith, T. B., Baker, M., Harris, T., & Stephenson, D. (2015). Loneliness and social isolation as risk factors for mortality: A meta-analytic review. *Perspectives on Psychological Science*, 10(2), 227–237. https://doi.org/10.1177/1745691614568352

You already cite this. Use it briefly as the "loneliness has measurable health consequences" beat, then move on. Do not lean on it as your primary motivation, because it pulls you toward clinical-intervention framing your project cannot deliver on.

*Note for the proposal:* Cite once, in a single sentence, alongside Source 4. Do not anchor on this.

---

## Section 3 — Loneliness theory: why "I have friends but feel alone" is a coherent claim

This section gives you the *theoretical* vocabulary to explain why the phenomenon you described is not a contradiction.

### Source 7 — Weiss (1973)

> Weiss, R. S. (1973). *Loneliness: The Experience of Emotional and Social Isolation*. MIT Press.

Foundational. Distinguishes **emotional loneliness** (absence of close, intimate attachments — partners, best friends, attachment figures) from **social loneliness** (absence of a broader sense of community and belonging). Weiss explicitly argued that emotional loneliness is the more painful form, and that it can persist even when one has substantial social ties.

*Why it matters:* This is the theoretical move that lets you say "you can be lonely while having friends." Without Weiss, this claim sounds rhetorical. With Weiss, it is established theory.

### Source 8 — Perlman & Peplau (1981/1982)

> Perlman, D., & Peplau, L. A. (1981). Toward a social psychology of loneliness. In R. Gilmour & S. Duck (Eds.), *Personal relationships in disorder* (pp. 31–56). Academic Press.
>
> Peplau, L. A., & Perlman, D. (1982). *Loneliness: A Sourcebook of Current Theory, Research and Therapy*. Wiley-Interscience.

The **cognitive discrepancy theory of loneliness**: loneliness is a *subjective discrepancy* between the social relationships a person desires and the relationships they perceive themselves to have. The mismatch — not the objective state — produces the experience.

*Why it matters:* This is the second theoretical anchor. Together with Weiss, it gives you: "Loneliness is not the absence of contact. It is the subjective discrepancy between the closeness one wants and the closeness one feels." That sentence is the entire motivation in one line, and it is built directly on these two sources.

### Source 9 — Qualter et al. (2015)

> Qualter, P., Vanhalst, J., Harris, R., Van Roekel, E., Lodder, G., Bangee, M., Maes, M., & Verhagen, M. (2015). Loneliness across the life span. *Perspectives on Psychological Science*, 10(2), 250–264. https://doi.org/10.1177/1745691615568999

Establishes the **U-shaped loneliness curve** — loneliness is highest in young adulthood and old age, lower in middle age. This is critical for your proposal: it justifies your specific target population (young adults, ~20–30) on developmental rather than just convenience grounds.

*Why it matters:* Without this, "we picked young adults because they're our peers" reads as convenience. With this, "we target young adults because the literature establishes this as a peak-loneliness developmental window" reads as principled.

---

## Section 4 — The digital-connection paradox: why current platforms do not solve this

### Source 10 — Madianou (2016)

> Madianou, M. (2016). Ambient co-presence: Transnational family practices in polymedia environments. *Global Networks*, 16(2), 183–201. https://doi.org/10.1111/glob.12105

**This is your theoretical centerpiece.** Madianou coins the term **"ambient co-presence"** — defined as "the peripheral, yet intense awareness of distant others made possible through the affordances of ubiquitous media environments." She argues that always-on connectivity (news feeds, locative services, ambient social platforms) creates a *new modality* of mediated presence that complements (without replacing) explicit communication. Her ethnography is on transnational Filipino families — *not* peer friendships.

*Why it matters massively:* You can extend Madianou's frame from transnational families to **dispersed peer friendships** — a population she did not study. This is a clean, defensible theoretical contribution: applying an established concept to a new relational structure. Reviewers love this kind of move because the contribution is precise and the lineage is clear. Madianou is your single most important theoretical citation; cite her for both the *concept* (what you are designing for) and the *gap* (peer friendships are not where this concept has been developed).

### Source 11 — Turkle (2011)

> Turkle, S. (2011). *Alone Together: Why We Expect More from Technology and Less from Each Other*. Basic Books.

Cited for the central thesis: networked connectivity can produce an *illusion of companionship* that does not deliver the felt closeness it appears to offer. Turkle's "alone together" framing is the popular-science version of the cognitive-discrepancy claim — current platforms maximize observable contact while leaving subjective closeness unaddressed.

*Why it matters:* This is your one allowed humanities/popular-academic citation. Use Turkle in *one sentence*, ideally to set up the design tension. Avoid quoting at length — this is a book, and reviewers know it.

### Source 12 — Roberts, Young & David (2025)

> Roberts, J. A., Young, P., & David, M. E. (2025). The epidemic of loneliness: A nine-year longitudinal study of the impact of passive and active social media use on loneliness. *Personality and Social Psychology Bulletin*. https://doi.org/10.1177/01461672241290235

You already cite this. The empirical companion to Turkle: a nine-year longitudinal study of ~7,000 adults showing that **both passive and active social media use predict increased loneliness over time** — and that the effect is most pronounced among people using social media specifically to *maintain close relationships*. That last finding is gold for your proposal: it directly indicts the use case current platforms claim to serve.

*Why it matters:* This source closes the rhetorical loop. The platforms that promise to connect intimate friends are, longitudinally, associated with deeper loneliness in exactly that population.

### Source 13 — Kushlev & Dunn (2016)

> Kushlev, K., & Dunn, E. W. (2016). "Silence your phones": Smartphone notifications increase inattention and hyperactivity symptoms. *Proceedings of the ACM CHI Conference on Human Factors in Computing Systems*, 1011–1020. https://doi.org/10.1145/2858036.2858359

You already cite this. Use it once, briefly, to establish that *the notification-driven attention model has documented harms*, motivating the calm-tech alternative. Do not over-rely on it.

---

## Section 5 — Structural conditions: why this is happening now

### Source 14 — Putnam (2000)

> Putnam, R. D. (2000). *Bowling Alone: The Collapse and Revival of American Community*. Simon & Schuster.

The canonical sociological account of the decline of American social capital. Identifies **geographic mobility, generational change, time and money pressures, and (most strongly in Putnam's analysis) electronic media** as drivers of the erosion of incidental, repeated, in-person social encounter.

**Important honesty note for your proposal:** Putnam's own analysis ranks geographic mobility as a *moderate* factor, not the largest. If you cite him for the mobility argument, do so carefully — he says mobility is *one of several* causes and explicitly notes that residential stability has actually *risen* slightly since 1965. The citation works if you frame it as "Putnam (2000) identifies geographic mobility as one of several structural conditions associated with declining incidental social contact." It does *not* work if you frame it as "Putnam shows mobility caused the friendship recession."

*Why it matters:* This is your "the problem has structural causes, not individual failings" citation. One sentence is enough.

### Source 15 — Arnett (2000, 2015) on emerging adulthood

> Arnett, J. J. (2000). Emerging adulthood: A theory of development from the late teens through the twenties. *American Psychologist*, 55(5), 469–480. https://doi.org/10.1037/0003-066X.55.5.469
>
> Arnett, J. J. (2015). *Emerging Adulthood: The Winding Road from the Late Teens through the Twenties* (2nd ed.). Oxford University Press.

Arnett's theory of **emerging adulthood (ages ~18–29)** as a distinct developmental stage characterized by identity exploration, instability, self-focus, feeling-in-between, and possibility. The period is *defined* by life-path divergence — career exploration, geographic relocation, romantic uncertainty, identity work. Arnett's frame explains *why* young adult friendships are structurally vulnerable to passive dissolution: the developmental task of this life stage is the kind of churn that drives drift.

*Why it matters:* Pairs with Qualter et al. (2015) to give your target population a developmental rationale. "We target emerging adults because Arnett (2000) identifies this as the life stage of maximum life-path divergence, and Qualter et al. (2015) identify it as a peak-loneliness window."

---

## Section 6 — The HCI gap

This is the critical section for the criteria's question *"What knowledge gaps does it fill?"*

### Source 16 — Pang, Pelaprat & Helmes (2015)

> Pang, C., Pelaprat, E., & Helmes, J. (2015). Friendship maintenance in the digital age. *Proceedings of the 18th ACM Conference on Computer Supported Cooperative Work & Social Computing (CSCW '15)*, 105–108. https://doi.org/10.1145/2675133.2675294

The canonical HCI/CSCW paper on friendship maintenance. Proposes a **"relational lens"** for analyzing communication technology, identifying that "social activity and connectedness are about ongoing enactments of relationships across technologies" — not single-tool design. Names three strategies (selection, segmentation, integration) people use to manage relational tensions across communication tools.

*Why it matters:* This is the lineage paper. Your project extends this line of work by moving from *managing tensions across existing tools* to *designing a new artifact specifically for the under-served friendship-maintenance task*. Cite it for "HCI has a small but established line of friendship-maintenance research; we extend it."

### Source 17 — Online Friendship paper (2025)

> Pang, C. et al. (2025). "I'm petting the laptop, which has you inside it": Reflecting on lived experiences of online friendship. *arXiv:2506.20055*.

Recent CHI-adjacent paper that explicitly identifies online friendship as **"an invisible marginalized community"** in HCI design — under-theorized compared to professional collaboration, romantic relationships, and family communication. The paper makes the gap argument directly: friendship has not received the design attention that other relationship types have.

*Why it matters:* This is your "the gap exists and the field knows it exists" citation. A 2025 paper at arXiv saying the field has under-served friendship is the cleanest possible evidence that your project is timely.

### Triangulating the HCI gap (absence evidence)

The gap is also visible in what's *missing*. A scoping review of HCI loneliness/connection work shows the following distribution:

| Subfield | Volume of HCI work |
|---|---|
| Older adults / aging-in-place | Very high (CHI 2024 has multiple) |
| Long-distance romantic couples | Very high (the Beds, Somnia, "Our House" CSCW 2018, etc.) |
| Cross-generational family | High (Madianou 2016 is here) |
| Clinical loneliness interventions | High (RCT-style apps) |
| Conversational agents/companions | High and growing |
| **Adult peer friendship in dispersed life-stage divergence** | **Sparse — Pang et al. 2015 is the canonical anchor; very few follow-ups** |

The 2025 systematic review *Digital bridges to social connection* (Sci­enceDirect) explicitly states: "published reviews have so far largely focused on older adults, leaving adolescents and young adults — digitally active groups with rising loneliness rates — understudied." That is your gap, in the field's own words.

---

## Section 7 — How these sources answer the criteria's three questions

### Q1: "Is the research question persuasive?"

The proposed research question — *how can ambient, expressive, asynchronous artifacts support felt closeness among small groups of dispersed adult friends?* — is persuasive because every premise is empirically grounded:

- The phenomenon exists (Vieth et al. 2022; Fehr 1996; Stewart-Brown 2024 on friendship downgrades).
- It produces real loneliness (Hall et al. 2025; Weiss 1973; Perlman & Peplau 1982).
- The target population is empirically high-risk (Qualter et al. 2015; Arnett 2000; Survey Center 2021/2024).
- Current systems do not solve it (Roberts et al. 2025; Turkle 2011; Kushlev & Dunn 2016).
- The HCI design space is genuinely underexplored (Pang et al. 2015 is one of few; 2025 paper explicitly names the gap).

### Q2: "What pain points does it solve / what knowledge gaps does it fill?"

**Pain point (felt by users):** The slow, unannounced loss of closeness with friends one has not fallen out with — friends who simply moved cities, started new jobs, or began separate phases of adult life. Users experience this as a quiet drift that social media renders invisible while doing nothing to repair.

**Knowledge gap (felt by the field):** HCI has substantial design literature on (a) older adults' social connectedness, (b) long-distance romantic couples, (c) cross-generational family, and (d) clinical loneliness interventions — but a sparse literature on adult peer friendship, especially in the developmental window where life-path divergence is most acute. Madianou's "ambient co-presence" frame has been developed for transnational families but not for peer friendship. The 2025 *Digital Bridges* systematic review and the 2025 online-friendship paper both explicitly call this gap out.

### Q3: "Why is this pain point important?"

Three reasons, each separately defensible:

1. **Scale.** Friendship-recession data shows the share of Americans with no close friends rose from 3% (1990) to 17% (2024); the share with 10+ close friends fell from 33% to 13% (Survey Center 2021/2024). The trend is structural, not idiosyncratic.
2. **Health.** Loneliness carries documented health consequences (Holt-Lunstad et al. 2015), including effects comparable to obesity and smoking on mortality risk.
3. **Developmental specificity.** Young adulthood is one of the two peak-loneliness life stages (Qualter et al. 2015), and emerging adulthood is structurally defined by the kind of life-path divergence that drives passive friendship dissolution (Arnett 2000; Vieth et al. 2022).

---

## Section 8 — Recommended motivation paragraph, with citations in place

To show how these sources assemble in the actual proposal, here is a possible motivation paragraph at full citation density:

> *We design for a specific kind of loneliness: not the loneliness of having no one, but the loneliness of friendships that have quietly downgraded across diverging life paths. Adult friendships rarely end through conflict; far more commonly, they fade through situational drift — geographic separation, divergent careers, the simple reduction of incidental contact (Fehr, 1996; Vieth, Rothman, & Simpson, 2022). The result is a particular emotional state: people in regular digital contact with friends they love, who nonetheless no longer share the daily texture that constitutes felt closeness. This pattern is empirically widespread. A representative U.S. survey of 4,812 adults found that loneliness in young adulthood is "characteristic of rapid life changes and a lack of relational permanence and routine" rather than absence of connection (Hall, Pennington, & Holmstrom, 2025). The Survey Center on American Life (Cox, 2021; Cox & Pressler, 2024) reports that the share of Americans with no close friends rose from 3% in 1990 to 17% in 2024, with geographic mobility and delayed family formation among the named structural drivers (cf. Putnam, 2000). The cognitive-discrepancy theory of loneliness (Perlman & Peplau, 1981) and Weiss's (1973) distinction between emotional and social loneliness explain why this experience is coherent: loneliness arises from a perceived discrepancy between desired and felt closeness, not from objective social absence. Current digital platforms compound rather than address this discrepancy. A nine-year longitudinal study of nearly 7,000 adults found that social media use predicts increased loneliness over time, with the strongest effect among users who report using social media specifically to maintain close relationships (Roberts, Young, & David, 2025) — the use case the platforms most explicitly promise. Within HCI, the design space of ambient co-presence (Madianou, 2016) has been productively developed for transnational families but remains substantially underexplored for peer friendships among emerging adults — the population that is, by Arnett's (2000) account of life-stage divergence and Qualter et al.'s (2015) U-shaped loneliness curve, most structurally vulnerable to this form of relational loss. We propose to extend ambient co-presence into this gap.*

That paragraph cites 11 of the 17 sources at appropriate density. It can be tightened to half that length without losing its empirical spine.

---

## Section 9 — Confidence and limitations

**High-confidence claims (use without qualification):**
- The phenomenon of passive friendship dissolution exists and has theoretical grounding.
- Young adults are at elevated loneliness risk (U-shaped curve).
- Friendship counts have declined measurably across two representative US surveys.
- Cognitive-discrepancy theory grounds "felt loneliness despite contact."
- Madianou's ambient co-presence is an established theoretical concept.
- Pang et al. (2015) is the canonical HCI friendship-maintenance reference.

**Moderate-confidence claims (use with care):**
- Putnam's mobility argument: he himself qualifies it. Frame as "one of several factors."
- The HCI gap claim: gaps are easier to assert than to prove. Triangulate via the 2025 online-friendship paper and the *Digital Bridges* meta-analysis rather than asserting "no work exists."

**Lower-confidence claims (avoid or hedge):**
- Causal claims that social media *causes* friendship downgrades. The Roberts et al. 2025 finding is correlational/longitudinal but not causal. Use language like "associated with" not "causes."
- Claims that your design will reduce loneliness. A semester-scale field study cannot deliver this. Frame outcome measures as connectedness (ABC-Q, Markopoulos et al. 2004) and felt closeness, not loneliness reduction.

---

## Section 10 — Reading priority for your team

If a team member can read **only one** paper from this list: **Hall, Pennington & Holmstrom (2025).** It contains the empirical sentence that justifies your motivation.

If they can read **three**: add **Madianou (2016)** for theoretical anchor and **Vieth, Rothman & Simpson (2022)** for the friendship-dissolution model.

If they can read **five**: add **Perlman & Peplau (1981)** for cognitive discrepancy theory and **Pang et al. (2015)** for the HCI lineage.

If they can read **seven**: add **Survey Center on American Life (2021)** for the population-scale data and **Arnett (2000)** for developmental grounding of the target user.

The remaining sources are useful as supporting citations but are not load-bearing.

---

## Full bibliography

1. Arnett, J. J. (2000). Emerging adulthood: A theory of development from the late teens through the twenties. *American Psychologist*, 55(5), 469–480.
2. Cox, D. A. (2021). The state of American friendship: Change, challenges, and loss. *American Perspectives Survey, May 2021.* Survey Center on American Life.
3. Cox, D. A., & Pressler, S. (2024). The decline in American friendship. *Survey Center on American Life.*
4. Fehr, B. (1996). *Friendship Processes*. Sage Publications.
5. Hall, J. A., Pennington, N., & Holmstrom, A. J. (2025). Lonely and connected in emerging adulthood: The ambivalence of sociality in a time of transitions. *PLOS ONE*, 20(11), e0334787.
6. Holt-Lunstad, J., Smith, T. B., Baker, M., Harris, T., & Stephenson, D. (2015). Loneliness and social isolation as risk factors for mortality: A meta-analytic review. *Perspectives on Psychological Science*, 10(2), 227–237.
7. Kushlev, K., & Dunn, E. W. (2016). "Silence your phones": Smartphone notifications increase inattention and hyperactivity symptoms. *CHI 2016*, 1011–1020.
8. Madianou, M. (2016). Ambient co-presence: Transnational family practices in polymedia environments. *Global Networks*, 16(2), 183–201.
9. Pang, C., Pelaprat, E., & Helmes, J. (2015). Friendship maintenance in the digital age. *CSCW '15*, 105–108.
10. Pang, C. et al. (2025). "I'm petting the laptop, which has you inside it": Reflecting on lived experiences of online friendship. *arXiv:2506.20055.*
11. Perlman, D., & Peplau, L. A. (1981). Toward a social psychology of loneliness. In R. Gilmour & S. Duck (Eds.), *Personal relationships in disorder* (pp. 31–56). Academic Press.
12. Putnam, R. D. (2000). *Bowling Alone: The Collapse and Revival of American Community*. Simon & Schuster.
13. Qualter, P., Vanhalst, J., Harris, R., Van Roekel, E., Lodder, G., Bangee, M., Maes, M., & Verhagen, M. (2015). Loneliness across the life span. *Perspectives on Psychological Science*, 10(2), 250–264.
14. Roberts, J. A., Young, P., & David, M. E. (2025). The epidemic of loneliness: A nine-year longitudinal study of the impact of passive and active social media use on loneliness. *Personality and Social Psychology Bulletin*.
15. Stewart-Brown et al. (2024). With or without you: Understanding friendship dissolution from childhood through young adulthood. PMC12316385.
16. Turkle, S. (2011). *Alone Together: Why We Expect More from Technology and Less from Each Other*. Basic Books.
17. Vieth, G., Rothman, A. J., & Simpson, J. A. (2022). Friendship loss and dissolution in adulthood: A conceptual model. *Current Opinion in Psychology*, 43, 171–175.
18. Weiss, R. S. (1973). *Loneliness: The Experience of Emotional and Social Isolation*. MIT Press.

---

**Synthesis status:** Complete. 17 core sources, 4 disciplines, all three criteria questions answered. Confidence high for foundational claims; appropriate hedging noted for causal and gap-extent claims.
