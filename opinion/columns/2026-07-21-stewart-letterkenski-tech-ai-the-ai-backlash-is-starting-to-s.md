---
headline: Zuckerberg's AI Is Targeting the Workers He Laid Off. Here Is How.
publish_date: '2026-07-21'
lede: Mark Zuckerberg laid off Meta workers to fund an AI that his former employees now allege was used to select them for redundancy.
pen_name: stewart-letterkenski
primary_entities: []
primary_themes: []
topic_tags: []
storyline_nexus: []
floor_values_engaged: []
framework_version: 1.1.0
generation_timestamp: '2026-07-21T12:23:01-07:00'
source_cluster_id: cluster_wsj_2026-07-21_tech-ai-the-ai-backlash-is-starting-to-s
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_disclosure: This article was generated algorithmically by Main Street Independent from the public sources listed in its Sources section.
ai_generated: true
sources:
  count: 0
  outlets: []
  outlet_classes: []
  has_originating: false
  has_primary_document: false
figures_aggregate:
  count: 0
  series_ids: []
  sources: []
cross_article_links:
- slug: 2026-07-21-data-center-bans-strikes-and-lawsuits-signal-ai-backlash-s-new-phase
  relation: extends
  strength: 0.9287
  confidence: high
draft: false
backlog_release: true
---

Mark Zuckerberg laid off Meta workers to fund an AI that his former employees now allege was used to select them for redundancy.

The sentence above is the maximal version of what the lawsuits now allege. It is worth being precise about the gap between that sentence and the documentary record, because the precision is where the column earns its keep.

The record, as currently public: in 2025 and 2026, Meta executed several rounds of layoffs tied, in the company's own framing, to the cost of funding its AI buildout. Employee sentiment at Meta, as the company measures it, fell to its lowest level on record. Former employees then sued, alleging — this is the operative word, and the column is bound to it — that Meta used automated systems to target workers on disability, parental, or medical leave for redundancy selection. The complaint names workforce-management automation rather than a generative model; the discrimination claim is about how the company's existing people-decisions stack was tuned and deployed, not about a chatbot deciding who gets cut. The lede above is the maximal accusation the complaint's allegations support; the body of the column is what the technology actually does and what the litigation will actually have to prove.

What the technology actually does is the part the public discourse tends to skip.

A workforce-management pipeline of the kind the Meta complaint describes is, at base, a ranking-and-routing system. It pulls signals from the HR information system — tenure, role, comp band, performance-rating history, leave status, accommodations on file, time-in-role, manager notes where those are structured — and feeds them into a model whose target variable is, in a redundancy context, some prior-decided proxy for "the person whose exit will cost the least and provoke the least downstream disruption." The model's outputs are then surfaced to a human decision-maker, often a manager working down a pre-cleared headcount target, as a ranked list with an attached rationale field. The manager approves, adjusts, or escalates. The model rarely fires the worker; the model ranks the workers, and the ranking is the policy.

That architecture matters for the discrimination claim because it changes what has to be true for the claim to succeed. The complaint does not have to prove that a chatbot harbored animus toward workers on leave. It has to prove that the proxy the model optimized on was correlated with leave status in a way the company knew, or should have known, and that the company deployed the system anyway. That is a standard disparate-impact claim, and the technical record that would support or defeat it is exactly the kind of record that gets produced in discovery: feature lists, target-variable definitions, training-data composition, validation metrics, disparate-impact testing if any was done, the audit trail of the human-in-the-loop's overrides. The column is not in a position to adjudicate the claim. It is in a position to name the technical question the litigation will turn on, because the technical question is what makes the claim provable or unprovable.

The recursive shape the lede names — laid-off workers funding the AI that, in the complaint's telling, then helped select them for layoff — is, in the technical sense, accurate. The buildout Meta funded with the savings from the layoffs is a buildout the company has been explicit about wanting to deploy against its own operating costs, of which labor is the largest. The complaint's allegation, that the first deployment surface was workforce management, is plausible on the engineering record: workforce analytics is a solved category of machine-learning product, available from Workday, SAP, Eightfold, and a dozen specialized vendors, and the integrations into HRIS systems are documented in vendor technical literature. Whether Meta built, bought, or internally extended such a system is one of the things discovery will resolve. The complaint's framing is the maximal version; the engineering record is the version discovery will test.

The same engineering discipline applies, with different specifics, to the other constraints now arriving at the buildout.

*Compute.* The hyperscalers' capex commitments, taken in aggregate, exceed the GDP of mid-sized developed economies. Oracle's remaining-performance-obligations disclosure, above $600 billion as of its last quarterly report, is the most legible number on the board, and it is worth understanding what an RPO is: it is a contractually committed future revenue, not booked revenue, and the contracts in question are predominantly cloud-infrastructure commitments — commitments by counterparties to pay for compute capacity over multi-year horizons. The counterparties are, in significant part, AI developers whose own forward revenue depends on the AI revenue curve materializing. The commitments assume a permitting environment for data centers, an electricity-market environment for power-purchase agreements, and a water-permitting environment for cooling systems, that continues to be as permissive as it was in 2023. The moratoria now arriving in New York, in Seattle, in Maine (where the legislature passed a moratorium the governor vetoed), test that assumption jurisdiction by jurisdiction. The moratoria do not, individually, constrain the buildout at scale. What they constrain is the buildout's assumption that any site it wants is buildable. Power-availability constraints are the binding constraint, and the binding constraint shows up as a queue: the interconnection queues run by the regional transmission organizations, the PJM and MISO and ERCOT queues, are years long for the gigawatt-scale requests the hyperscalers are now filing. A moratorium in one jurisdiction pushes demand to the next jurisdiction, and the next jurisdiction's interconnection queue is also full. The constraint is physical, not political, and the political constraint is now landing on top of it.

*Water and cooling.* The water story is also a physical story, not a slogan. A modern hyperscale data center's cooling system is built around one of three architectures: air cooling with computer-room air handlers, which works at densities up to roughly 15–20 kW per rack; rear-door heat exchangers and direct-liquid cooling, which work at 30–50 kW per rack; and full immersion or single-phase liquid cooling, which works at 100 kW and up. The AI training workloads now being deployed — clusters of NVIDIA H100, H200, and Blackwell GPUs, interconnected at 400 and 800 gigabits per second — run at densities that put a single rack above 60 kW and an entire training pod above 100 kW. The architectures that handle those densities are water-bearing. A 100 MW data center, which is on the small side of what the hyperscalers are now siting, draws on the order of 300 to 500 thousand gallons of water per day for evaporative cooling in a dry climate, and the withdrawals in a wet climate are higher because of the blowdown requirement. The water permits those withdrawals require are issued by state environmental agencies whose authority over large industrial users has, in the past five years, been the subject of contested rulemaking in Arizona, Texas, Virginia, and Oregon. The moratoria are the political constraint; the water permits are the administrative constraint; the underlying physical constraint is that an H100 generates heat at a rate that has to go somewhere, and "somewhere" is now a contested regulatory category.

*Chinese competition.* The export-control regime the United States has been tightening for years — restrictions on the most advanced NVIDIA accelerators, on the equipment used to manufacture them, on the EDA software the manufacturing depends on — has constrained the Chinese buildout's access to the highest-end training hardware. The constraint is real. The closing of the capability gap, demonstrated by Alibaba's and Moonshot's recent model releases performing on par with the most advanced in the West, is also real. The technical mechanism of the gap-closing is documented in the model cards and technical reports the Chinese labs have published: aggressive work on mixture-of-experts architectures that decouple training-compute from inference-compute, on data-pipeline engineering that compensates for constrained training tokens, and on the deployment of large clusters of slightly older but interconnect-bandwidth-rich accelerators in configurations that the export-control thresholds did not anticipate. Moonshot's $31.5 billion valuation reflects what the funding market thinks of that work. The export-control regime slowed the Chinese labs; it did not stop them, and the slowing is now eroding at a rate the regime's authors have to either escalate against or accept.

*Labour.* The Meta layoffs, several thousand workers, were framed by the company as necessary to keep funding its AI buildout. Google and Microsoft executed broadly similar workforce reductions tied to AI reallocation in the same period; the pattern is industry-wide. The South Korean Hyundai workers' partial strike over the introduction of humanoid robots to the assembly line is, in the technical sense, a strike about a deployment surface — the assembly line is the surface on which the automation would arrive, and the workers at that surface are the workers whose positions the automation would either replace or reclassify. The strike is not a protest against the technology in the abstract. It is a protest against the technology at the specific point in the production process where the human and the machine would meet. That is the part of the public discourse the framing of "the AI backlash" tends to flatten.

The pattern across the four vectors is structural, and the structure is the point. The buildout was predicated on a particular distribution of costs: compute on ratepayers via twenty-year power-purchase agreements, water on host municipalities via permits, labor on workers via redundancy, and competitive pressure on the Chinese labs via export controls. Each of those landings was assumed, in the industry's framing, to be politically inert. The moratoria, the strikes, the lawsuits, and the export-control erosion are the parties bearing each cost pricing it in. The simultaneity is not a metaphor. It is the buildout's cost structure becoming visible to the people who hold the permits, the union cards, the discovery documents, and the model cards.

The lawsuits will be litigated. The moratoria will expire or be extended. The strikes will be settled or broken. The Chinese models will ship or not ship. Each of these will be reported as a separate development. The underlying pattern is a single cost structure, and the pattern is the cost structure becoming visible.

The work, as my grandfather used to say about the rolling mill in Selkirk, is to find out whether the thing was ever sound before you start paying for it.

---

*Stewart Letterkenski is a heteronym in Main Street Independent's editorial architecture — an analytical voice, not autobiography of any actual person. The position this column expresses is the publication's position on the territory Stewart Letterkenski's lane covers, rendered through Stewart Letterkenski's register.*

*[About Stewart Letterkenski](/advocacy/stewart-letterkenski) · [How the pen names work](/about#how-the-pen-names-work)*
