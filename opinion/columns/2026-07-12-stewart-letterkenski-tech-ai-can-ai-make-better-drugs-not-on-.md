---
headline: Pharma is automating the molecules it knows will fail in people
publish_date: '2026-07-12'
lede: The pharmaceutical industry is automating the search for molecules it knows will fail in human bodies.
pen_name: stewart-letterkenski
primary_entities:
- Goldman Sachs
- Roche
- Eli Lilly
- Novartis
- Anthropic
- Aviv Regev
- Jack Scannell
- Eric Kauderer-Abrams
primary_themes:
- Artificial intelligence
- Drug discovery
- Pharmaceutical industry
- Research and development
- Investment returns
topic_tags:
- artificial intelligence
- biotechnology
- medical research
- economy, business and finance
storyline_nexus: []
geographic_location: United States
floor_values_engaged:
- value: human_life_and_dignity
  intensity: 0.6
- value: truthfulness
  intensity: 0.6
- value: informed_citizenship
  intensity: 0.6
framework_version: 1.1.0
generation_timestamp: '2026-07-12T07:34:55-07:00'
source_cluster_id: cluster_wsj_2026-07-12_tech-ai-can-ai-make-better-drugs-not-on-
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_disclosure: This article was generated algorithmically by Main Street Independent from the public sources listed in its Sources section.
ai_generated: true
sources:
  count: 1
  outlets:
  - The Wall Street Journal
  outlet_classes:
  - national_daily
  highest_reliability_tier: 1
  has_originating: true
  has_primary_document: false
figures_aggregate:
  count: 0
  series_ids: []
  sources: []
cross_article_links:
- slug: 2026-07-12-ai-shows-promise-in-drug-labs-commercial-payoff-years-away
  relation: extends
  strength: 0.9357
  confidence: high
draft: false
---

The pharmaceutical industry is automating the search for molecules it knows will fail in human bodies. There is no investor "dilemma" here, and the "trillion-dollar question" framing — common enough in the trade press — conceals what the industry is actually doing, which is feeding more molecules into a pipeline whose one-in-ten success rate in human trials has not meaningfully moved in the time anyone has been writing about AI.

Regev's "lab in the loop" at Genentech is what AI in drug discovery actually does well in 2026. Models predict protein-binding affinities and candidate targets; researchers test them in the lab; the model learns from what the wet lab produces. That is real engineering, and the people doing it are doing it honestly. Aviv Regev, the computational biologist who runs the program, is right that a model "encodes information very, very broadly" — the protein-structure-prediction work at DeepMind that earned Demis Hassabis and John Jumper a share of the 2024 Nobel Prize in Chemistry, alongside David Baker at the University of Washington for computational protein design, extending the foundational work of John Moult and Krzysztof Fidelis at the University of Maryland's Critical Assessment of protein Structure Prediction consortium, is genuinely consequential. So is high-throughput virtual screening, which narrows the search space before expensive bench work begins. So, in narrower and more equivocal ways, is target identification. None of these three things is a drug. The Regev program produces candidates. The clinical trial produces drugs, at the rate the trial system has always produced drugs.

Scannell's frog on a bicycle in Albuquerque is what AI does not. Jack Scannell, who co-wrote the 2012 *Nature Reviews Drug Discovery* paper that named Eroom's Law — Moore's Law spelled backward — with Alex Blanckley, Helen Boldon, and Brian Warrington, put the limitation precisely in a recent conversation with the *Wall Street Journal*'s Heard on the Street columnist David Wainer: training an AI on today's biological data is like training a Waymo by getting a frog to ride a bike around Albuquerque. The training data is fundamentally mismatched to the deployment environment. A model that learns from cell-line assays and isolated protein-binding measurements is learning the shape of an idealized adversary — one that plays by your rules, in a system whose specification you have written down. The human body is the original realistic adversary. Its specification, in the relevant clinical sense, cannot be written down. This is the same hard boundary that separates cryptographic protocol verification under the Dolev-Yao idealized-adversary model from computational soundness against an adversary that does not: in vitro is the math; in vivo is the world, and the math does not survive the translation.

Eroom's Law is a feature of biological complexity, not a software bug awaiting a better algorithm. The Scannell paper's diagnosis, twenty years on, still holds: each new drug must outperform the cheap generics already on the shelf, in a body whose metabolic and immune systems no amount of GPU compute has successfully mapped. The molecules the AI layer produces will go into Phase 1 trials at the rate Phase 1 trials have always cleared, will go into Phase 3 trials at the rate Phase 3 trials have always cleared, and will fail in the clinic at the rate the clinic has always failed them. Faster candidate generation does not change the downstream attrition curve. It just shifts the bezzle leftward on the calendar.

The bezzle, in the economist John Kenneth Galbraith's 1929 sense, is the interval between the decision to spend and the discovery that the money did not produce the promised return — during which the capital expenditure is booked as an asset and the stock is rerated on the promise of tomorrow. Eli Lilly and Novartis are committing billions to compute. Goldman Sachs pegs the present value of AI's pharmaceutical upside at as much as $400 billion over the next decade — a number large enough to make any equity analyst reach for a discounted cash-flow model, and small enough, on an annual basis, to be lost in the capex announcements of any single hyperscaler. That is the bezzle in spreadsheet form: capex that has not yet produced a single approved molecule at lower cost, booked as though it had. The model builders, having [pivoted from chatbots to "physical AI" systems](/articles/2026-06-24-ai-entrepreneurs-pivot-from-chatbots-to-building-physical-ai-systems/), are now applying the same interval to human biology. [Wall Street, which is still grappling with an AI hiring dilemma as tools reshape banking jobs](/articles/2026-06-18-wall-street-grapples-with-ai-hiring-dilemma-as-tools-reshape-banking-jobs/), is more than willing to look the other way, because the firms building the AI infrastructure are rewarded in calendar quarters while their customers in the slower-moving sectors of the real economy wait out longer cycles.

That clock-mismatch is the Wainer column's actual subject, and it deserves the kind of reading it is unlikely to get from anyone who needs to make a decision this quarter. Wainer runs through what AI in drug discovery genuinely is in 2026 and what it is not, cites the one-in-ten success rate in human trials as the figure that does not move, and concedes — even from the believers, including the person leading life sciences at one of the frontier model companies — that the industry is in the "second inning" of a nine-inning game. The column is honest that the bottleneck is biological. The column is somewhat less honest about the institutional arrangements that Eroom's Law names. Marcia Angell, the former editor of the *New England Journal of Medicine*, made the structural point plainly twenty years ago in *The Truth About the Drug Companies*: the high cost of bringing a new drug to market is, in significant part, a cost imposed by the industry's own pricing power, marketing expenditures, and the extension of patent monopolies on drugs that are minor modifications of existing ones. The actual cost of meaningful innovation, when the underlying research was done at the National Institutes of Health and the academic medical centers, is closer to one-tenth of the industry-cited figure of $2.6 billion per drug. The industry's response, then and now, has been to insist on the figure it needs to stay in business, and to leave unexamined how much of that cost is rent extraction from a system in which the buyer cannot decline and the seller faces no competition until the patent expires.

The most legible single indicator that the regulator has been substantially captured by the regulated is the Prescription Drug User Fee Act. PDUFA has been reauthorized six times since 1992, and industry user fees now fund roughly seventy-seven percent of the human-drug review program's costs. AI deployed inside that arrangement will produce whatever returns that arrangement is structured to deliver, which is more me-too drugs on extended monopolies, not transformative new mechanisms. The reform that would actually change the arrangement is straightforward and unfashionable: restore public appropriations to the FDA's review program, return PDUFA to a modest share of agency funding, and stop extending patent monopolies on drugs that are minor modifications of existing ones. None of this is novel. Congress has not done the kind of sustained work over multiple sessions that would change that arrangement on any complex regulatory matter in living memory. AI may or may not bend Eroom's Law. Congress will not.

The most consequential AI research in 2026 is not the kind that produces a press release. It is the kind that produces a phase-two clinical trial result in 2031 that nobody read about this year. The molecules will still fail in human bodies, on the schedule biology has always run. The capital expenditure will be amortized regardless. The public subsidizes the basic science that makes any of this possible, and the private sector extracts the premium for the AI layer.

The closing observation is the one the Wainer column declined to write: in 1995, when new owners bought the Manitoba steel mill where my father was a journeyman millwright, they did not write better software to save declining margins. They loaded debt onto the balance sheet and extracted rent from the physical machinery until it rusted. The pharmaceutical industry's pivot to artificial intelligence is that same extraction playbook, applied to human biology.

## Sources

### src_001 — The Wall Street Journal, national_daily, Tier 1, originating
**Author:** David Wainer
**Publication date:** 2026-07-12
**Title:** Can AI Make Better Drugs? Not on Wall Street’s Timeline
**URL:** https://www.wsj.com/tech/ai/can-ai-make-better-drugs-not-on-wall-streets-timeline-98a50d9d

---

*Stewart Letterkenski is a heteronym in Main Street Independent's editorial architecture — an analytical voice, not autobiography of any actual person. The position this column expresses is the publication's position on the territory Stewart Letterkenski's lane covers, rendered through Stewart Letterkenski's register.*

*[About Stewart Letterkenski](/advocacy/stewart-letterkenski) · [How the pen names work](/about#how-the-pen-names-work)*
