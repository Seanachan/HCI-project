# Night City Block: An Ambient, Place-Based Social Awareness System for Intimate Friend Groups

**HCI / HAX Semester Project — Midterm Proposal**

---

## 1. Research Motivation

### 1.1 Where We Started

Our team works **interest-first, research-second**. We did not start from a research problem — we started from a feeling we wanted to design for.

Our reference point is what friendship expert Matt Ritter calls **"doorbell friends"** (Ritter, n.d.) — and what anyone who watched _Friends_ already recognizes: Joey wanders into Monica's apartment without calling. Chandler shows up because the light is on. Nobody schedules. Nobody messages first. Ritter defines a doorbell friend as someone who can show up at your house, ring the bell, and be welcomed not as a nuisance but as a pleasant surprise. He argues this register — built through low-stakes consistency rather than scheduled intensity — is what modern adult friendship has structurally lost.

We take Ritter's framing as the **gold standard** for the kind of friendship we want digital tools to support. But we also want to name the tension head-on: a doorbell friend, in the literal sense Ritter writes about, requires **physical proximity**. You cannot ring the bell of a friend who lives in another city, another country, another time zone. Yet that geographically dispersed configuration is exactly the situation our target users live in — young adults whose closest friends scattered after college, after grad school, after first jobs.

So our motivating question is not "how do we replicate Ritter's prescription digitally" — that prescription (say yes to low-stakes hangs, lower the bar, just stop by) **assumes co-location we don't have**. Our question is one step over: **can a digital ambient environment reproduce the _register_ of doorbell-friend relationships — no scheduling, no performance, no obligation to respond, casual presence built through consistency — when literal doorbells are off the table?**

The seed of our project, in those terms: friends should be able to leave _traces_ for each other to discover, the way you might notice a book left open on someone's desk, or a light still on across the courtyard at 2am. Not a post. Not a message. Not a notification. Not a doorbell ring either — because rings still demand a sender and a receiver. Just a quiet, ambient sign that someone is there, and something of who they are. The digital equivalent of seeing the kitchen light on across the courtyard — without ever needing to walk over.

Our first sketch was a **shared digital garden** — friends draw, and the drawings become flowers in each other's gardens. From that, we extracted three design variables we cared about:

- `<something>` — the shared artifact people gather around (garden → night city block)
- `<a_way>` — the expressive interaction (drawing, color, photo, voice fragment)
- `<feel_something>` — the emotional outcome (felt closeness without obligation)

### 1.2 Three Design Values We Are Committed To

1. **Creative & artistic, not utilitarian.** The interaction should feel expressive — closer to keeping a diary than filling a form.
2. **Physical over purely digital.** A tangible artifact (a small lit building model on the desk) sitting in peripheral vision matters more to us than another tab in the browser.
3. **Social but gentle.** No notifications, no read receipts, no obligation to reply. Friends discover each other by wandering, not by being pinged.

Night City Block is the current incarnation of this commitment: a shared dim city where each friend inhabits a block, a private daily diary becomes the atmosphere of that block, and connection happens by quietly noticing each other's lights.

### 1.3 Why Existing Apps Don't Fit

A wave of consumer apps targets the same gap we feel — IG / feeds are too public, DMs are too demanding — and aims at the same population (young adults, close friend groups). Looking at them sharpened what we actually want.

- **Locket Widget** — friends' photos appear on the home screen. Closer to ambient: no feed to scroll. But still **push-based** (someone takes a photo, others receive it) and the content is literal photographs.
- **BeReal** — synchronized daily prompt; everyone posts at the same random moment. Lowers performance pressure, but still feed-shaped, post-shaped, and demands a daily action.
- **"Doorbell"-style ping apps (Poke, yo, Wave)** — one tap = "thinking of you." Genuinely low-effort, but binary: pinged or not. No expressive content; still uses notifications.

These three confirm the appetite for something gentler than IG and less demanding than DMs. But all of them keep three properties we deliberately want to remove:

1. **Push semantics** — someone sends, someone receives
2. **Literal content** — a photo, a tap (not an abstracted trace)
3. **Direct addressing** — posted _to_ a friend list

Night City Block replaces these with **ambient generation** (the city renders, no one sends), **expressive abstraction** (a diary becomes weather, not a photo), and **architectural disclosure** (visibility comes from spatial proximity, not a recipient list). Whether that swap still produces felt closeness — or whether removing push / literal / direct kills the very thing that makes those apps work — is exactly what we want to find out.

### 1.4 What We Want to Find Out

The reason this is a research project, and not just a design exercise, is that we don't yet know whether this register actually works. Concretely, we want to test:

- Whether expressive, indirect traces (a window color, a tinted weather, a smear of street art) can produce real felt closeness — or whether they read as decoration.
- Whether **architectural** privacy (closer space = more disclosure) feels intuitive, or whether users still want a settings menu.
- Which city elements (weather, street traces, simultaneous presence) actually carry the social signal, and which are just visual noise.

These map onto RQ1–RQ3 in §4. The literature in §2 grounds why each of these is worth asking — but the questions come from the design first.

### 1.5 The Interaction Scenario

We are designing **Night City Block**, a shared digital urban environment where a small group of close friends (~5 people) each inhabit a personal "block" — rendered as a lit apartment window, shopfront, or rooftop in a living night-city scene. The city is not a social feed or a messaging interface. It is a collective ambient display: your block reflects you through the traces of a private daily diary (a drawing, a photo, a chosen color, a single word), and you discover your friends by wandering through theirs. Nobody sends anything directly. Connection happens through the city noticing you both.

The system is explicitly designed around calm technology principles: information flows to the periphery, not the center. You are not asked to respond. You do not receive notifications. You simply coexist — and the city, over time, tells a layered story of who was here, when, and in what state of mind.

### 1.6 Target Audience

The primary target users are **young adults in intimate friend groups (3–8 people)** who are geographically dispersed — living in different apartments, cities, or time zones — and who want lightweight, emotionally resonant awareness of each other without the pressure of explicit communication. Secondary contexts include long-distance couples and creative communities who value expressive over informational sharing.

---

## 2. Literature Review

The design instincts in §1 line up with a substantial body of HCI and social-psychology work. Two broad findings frame why this register is worth designing for. First, the stakes of social disconnection are severe and well-documented: Holt-Lunstad et al.'s 2015 meta-analysis (3.4M participants, 70 studies) ties loneliness to a 26% increase in early-mortality risk and social isolation to 29% — comparable to obesity and smoking; their 2010 meta-analysis links being socially connected to a 50% increase in odds of survival. Second, more digital connectivity is not closing the gap: a nine-year longitudinal study of nearly 7,000 adults found that both passive _and_ active social-media use predicted increased loneliness over time, and the effect was most pronounced among users who turned to these platforms specifically to maintain close relationships (Roberts et al., 2025). Smartphone notifications alone — even when ignored — measurably worsen attention and well-being (Kushlev & Dunn, 2016). Awareness systems and calm technology have been studied in HCI since Weiser and Brown (1996), but most of that work targets workplace collaboration or elderly/family communication. Ambient social connection in an expressive, low-demand register, for young adults in geographically dispersed friend groups, remains underexplored.

### 2.1 Calm Technology and Peripheral Awareness

The foundational framework for this project is Weiser and Brown's (1996) theory of calm technology. They argue that well-designed technology should engage both the center and the periphery of attention, and — crucially — should move easily between the two. Their concept of _locatedness_ is particularly relevant: a calm technology places us in a familiar environment in which the periphery is working well, allowing us to be "tuned in to what is happening around us" without cognitive overload. The dangling string — a physical indicator of network traffic requiring no interpretation — exemplifies the design ideal we are pursuing. Night City Block is built on this principle: the city is a peripheral display that can become a center of attention when the user chooses to explore it, but demands nothing in its resting state.

### 2.2 Tangible Bits and Physical–Digital Integration

Ishii and Ullmer's (1997) _Tangible Bits_ vision proposes bridging the gap between the physical world and digital information through ambient media — light, sound, airflow, water — that leverages the periphery of human perception. Their distinction between _graspable media_ (foreground bits manipulated actively) and _ambient media_ (background bits available peripherally) maps directly onto our system design. The private diary functions as graspable media; the city atmosphere is ambient media. The optional physical artifact extension — a small lit building model on a desk, whose windows glow according to friends' activity — instantiates the Tangible Bits vision in a domestic, intimate register.

### 2.3 Ambient Awareness and Social Closeness

Scissors et al. (2016) provide empirical evidence that ambient awareness — the peripheral accumulation of fragmentary social information — can develop a coherent sense of knowing others even in the absence of direct one-to-one communication. In their study of Twitter users, participants reported moderate-to-high ambient awareness of people in their network, noting that this awareness increased perceptions of approachability. This supports our design premise that indirect, trace-based social information can create meaningful closeness without requiring active exchange. Importantly, their data also show that this effect works best in small, familiar networks — the exact social scale Night City Block targets.

### 2.4 Presence Displays and Physical Connectedness

Dey and Guzman (2006) designed Presence Displays — physical, peripheral ambient displays of online presence for close friends and family — and found, in a five-week field study, that these displays produced significantly better awareness of and connectedness to loved ones than standard graphical presence indicators. Their work demonstrates that the _form factor_ matters: physically embodied ambient displays outperform screen-based equivalents for fostering felt connection. This motivates our attention to a possible physical artifact (a small illuminated building model) as a key design direction.

### 2.5 Awareness Systems and Affective Benefits

Markopoulos et al. (2004) introduce the concept of connectedness as an affective benefit of awareness systems, and develop the ABC-Q instrument to measure it. Their empirical work with the ASTRA system demonstrates that sharing experiences at the moment they happen, in a non-interrupting manner, can yield measurable affective benefits for intimate social networks. This is critical for our proposal: it suggests that the value we are designing for — felt closeness, emotional attunement — is not only conceptually plausible but empirically measurable.

### 2.6 Relatedness Technologies and Design Tensions

A growing literature, summarized in Hassenzahl et al. (2012) and more recently in Wenhart et al. (2025), identifies the core strategies through which HCI systems can foster experiences of relatedness: awareness, expressivity, physicalness, gift-giving, joint action, and shared memory. Night City Block consciously deploys awareness, expressivity, physicalness (via the artifact layer), and shared memory (accumulated city history). However, Hassenzahl et al. also identify a critical design tension between relatedness (feeling connected to others) and autonomy (feeling in control of one's own attention and self-expression). Current social platforms tend to optimize for relatedness at the cost of autonomy — constant pings, social obligation to respond, performance anxiety. Night City Block's architectural privacy model (where visibility is determined by spatial proximity in the city, not by a settings menu) is a direct response to this tension: the system is designed so that the user always retains control over how much of themselves is visible.

### 2.7 Knowledge Gaps This Project Addresses

The existing literature on ambient awareness systems has two significant gaps that this project addresses:

1. **The aesthetic and expressive dimension of ambient social systems is understudied.** Most existing awareness systems — Presence Displays, ASTRA, CareNet — focus on conveying presence and availability, not on expressive or artistic self-representation. They tell you _that_ someone is home; they do not tell you anything about _who_ that person is. Night City Block proposes diary-driven, artistically-generated ambient output as the primary signal, creating a richer and more emotionally resonant form of ambient presence.

2. **The spatial and architectural metaphor has not been systematically explored as a privacy and intimacy interface.** Privacy in existing systems is managed through settings and permission layers. We propose using _spatial architecture_ — inside a room, a window, a doorstep, the street — as a naturalistic and intuitive privacy model, and study whether this lowers the cognitive and social cost of managing self-disclosure.

---

## 3. Research Objectives

1. To design and prototype an ambient social awareness system — Night City Block — that supports felt closeness among intimate friend groups without requiring explicit communication acts.
2. To investigate whether architecturally-encoded privacy (spatial proximity as a metaphor for disclosure level) is a viable and comfortable alternative to settings-based privacy management in ambient social systems.
3. To explore whether diary-driven, expressive ambient output generates richer and more emotionally meaningful awareness than presence/availability-based signals.

---

## 4. Research Questions

**RQ1:** How does ambient, expressive trace-based social information (diary-generated city elements) affect felt closeness and awareness among members of an intimate friend group, compared to a baseline of no ambient display?

**RQ2:** Does the architectural metaphor of spatial proximity (distance in the city corresponds to disclosure level) adequately and comfortably represent users' desired privacy boundaries, without requiring explicit privacy settings?

**RQ3:** What design elements within the Night City Block environment (e.g., weather as collective mood, street traces as social history, simultaneous presence indicators) are most salient to users in forming a sense of ambient social connection?

---

## 5. Proposed System Design

### 5.1 Core Concept

Each user owns a **block** in a shared digital night city. Their block reflects their inner state through a private daily diary: a drawing, photograph, mood color, single sentence, or voice fragment. These diary entries are never directly shared — instead, they _generate the atmosphere_ of the user's block. A drawing becomes street art on their wall. A chosen color tints their window light. Silence dims their curtains to a single warm lamp.

The city exists between the blocks. Weather, street textures, and ambient elements emerge from the collective state of the group. Friends discover each other by wandering — nobody sends; nobody receives. The city notices, and the city shows.

### 5.2 Privacy as Architecture

| Space          | Visibility               |
| -------------- | ------------------------ |
| Interior room  | Only the user            |
| Window display | Close friends            |
| Front doorstep | All friends              |
| The street     | Everyone in the city     |
| A back alley   | One specific person only |

Privacy is not configured in a settings menu. It is encoded spatially, in the physical logic of the city.

### 5.3 Optional Physical Artifact

A small illuminated building model sits on the user's desk. Its windows glow with the ambient colors of friends' moods. It requires no screen time; it lives in the peripheral vision of the workspace.

---

## 6. Methodology (Planned)

This midterm proposal focuses on motivation, literature, and research objectives. The full methodology will be developed in subsequent milestones. At present, we anticipate:

- **Formative study:** Semi-structured interviews with young adults (aged 20–30) about their existing practices around ambient social awareness and closeness — what do they notice, what do they miss, what feels exhausting?
- **Prototype development:** A functional prototype of the Night City Block environment, with a small cohort of 4–6 participants.
- **Field deployment study (3–4 weeks):** Participants use the system with their actual friend group; we collect diary entries, usage logs, and periodic experience sampling.
- **Post-study interviews:** Qualitative inquiry into felt closeness, privacy comfort, and the salience of specific design elements.

---

## 7. Prof. McGee's 8 Questions — Self-Assessment

| Question                           | Our Response                                                                                                                                                                                |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Research problem/question**      | How can ambient, expressive, trace-based social systems support felt closeness in intimate friend groups without explicit communication demands?                                            |
| **Is it significant?**             | Yes — the tension between digital connectivity and felt loneliness is a documented social phenomenon; ambient awareness systems for intimate, expressive social contexts are underexplored. |
| **Contribution to knowledge**      | A design prototype and empirical findings on (a) expressive ambient awareness vs. presence-only awareness, and (b) architectural vs. settings-based privacy as interaction design.          |
| **Is the contribution vital?**     | We believe so — the study outcomes could inform design of a whole class of calm, intimate social systems.                                                                                   |
| **Originality**                    | No existing system combines: night-city spatial metaphor + diary-to-atmosphere generation + architectural privacy model + physical artifact layer.                                          |
| **How readers know it's original** | Literature review demonstrates the gaps; no known system combines all four design elements.                                                                                                 |
| **Validity**                       | Mixed-methods field study with measurable affective outcomes (connectedness, using instruments from prior work such as ABC-Q) and qualitative depth.                                        |
| **Disciplinary fit**               | Core HCI / ubicomp / calm technology — with contributions relevant to CSCW and design research.                                                                                             |

---

## References

1. Weiser, M., & Brown, J. S. (1996). _The Coming Age of Calm Technology._ Xerox PARC. Retrieved from https://calmtech.com/papers/coming-age-calm-technology

2. Ishii, H., & Ullmer, B. (1997). Tangible bits: towards seamless interfaces between people, bits and atoms. _Proceedings of the ACM SIGCHI Conference on Human Factors in Computing Systems_, 234–241. https://doi.org/10.1145/258549.258715

3. Scissors, L., Burke, M., & Wengrovitz, S. (2016). What's in a Like? Attitudes and behaviors around receiving Likes on Facebook. In _Proceedings of CSCW 2016._ _(See also: Scissors et al., 2016, on ambient awareness — PMC4853799.)_

4. Dey, A. K., & Guzman, E. S. (2006). From awareness to connectedness: The design and deployment of presence displays. _Proceedings of the ACM CHI Conference on Human Factors in Computing Systems._ https://doi.org/10.1145/1124772.1124828

5. Markopoulos, P., van Baren, J., IJsselsteijn, W., de Ruyter, B., & Farshchian, B. (2004). Connecting the family with awareness systems. _Personal and Ubiquitous Computing_, 8(6), 405–414. https://doi.org/10.1007/s00779-004-0293-2

6. Hassenzahl, M., Heidecker, S., Eckoldt, K., Diefenbach, S., & Hillmann, U. (2012). All you need is love: Current strategies of mediating intimate relationships through technology. _ACM Transactions on Computer-Human Interaction (TOCHI)_, 19(4), 1–19.

7. Consolvo, S., Roessler, P., & Shelton, B. E. (2004). The CareNet display: Lessons learned from an in-home evaluation of an ambient display. _UbiComp 2004_, LNCS 3205, 1–17.

8. Bhowmick, P., & Stolterman, E. (2023). Exploring tangible user interface design for social connection among older adults: A preliminary review. _Extended Abstracts of CHI 2023._ https://doi.org/10.1145/3544549.3585722

9. Holt-Lunstad, J., Smith, T. B., & Layton, J. B. (2010). Social relationships and mortality risk: A meta-analytic review. _PLOS Medicine_, 7(7), e1000316. https://doi.org/10.1371/journal.pmed.1000316

10. Holt-Lunstad, J., Smith, T. B., Baker, M., Harris, T., & Stephenson, D. (2015). Loneliness and social isolation as risk factors for mortality: A meta-analytic review. _Perspectives on Psychological Science_, 10(2), 227–237. https://doi.org/10.1177/1745691614568352

11. Roberts, J. A., Young, P., & David, M. E. (2025). The epidemic of loneliness: A nine-year longitudinal study of the impact of passive and active social media use on loneliness. _Personality and Social Psychology Bulletin._ https://doi.org/10.1177/01461672241290235

12. Kushlev, K., & Dunn, E. W. (2016). "Silence your phones": Smartphone notifications increase inattention and hyperactivity symptoms. _Proceedings of the ACM CHI Conference on Human Factors in Computing Systems_, 1011–1020. https://doi.org/10.1145/2858036.2858359

13. Ritter, M. (n.d.). _The Friendship Habit_ [Newsletter]. The Friendship Guy. Concept of "doorbell friends" — friends welcomed without scheduling, built through low-stakes consistency rather than planned intensity. https://www.thefriendshipguy.com/newsletter

