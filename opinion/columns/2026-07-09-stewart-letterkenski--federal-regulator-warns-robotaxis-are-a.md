---
headline: Alphabet's Cars Don't Recognize a Fire Truck
publish_date: '2026-07-09'
lede: Alphabet ships four thousand cars onto American streets that cannot recognize a fire engine.
pen_name: stewart-letterkenski
primary_entities:
- National Highway Traffic Safety Administration
- Jonathan Morrison
- Waymo
- Zoox
- Tesla
- Goldman Sachs
primary_themes:
- autonomous vehicles
- public safety
- federal regulation
- emergency response
topic_tags:
- transport
- robotics
- government policy
- science and technology
- transportation accident and incident
storyline_nexus: []
geographic_location: United States
floor_values_engaged:
- value: human_life_and_dignity
  intensity: 0.9
- value: accountability_of_power
  intensity: 0.6
framework_version: 1.1.0
generation_timestamp: '2026-07-09T11:10:43-07:00'
source_cluster_id: cluster_wsj_2026-07-09_-federal-regulator-warns-robotaxis-are-a
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
- slug: 2026-07-09-nhtsa-orders-av-companies-to-address-robotaxi-interference-with-first-responders
  relation: extends
  strength: 0.2169
  confidence: high
draft: false
---

Alphabet ships four thousand cars onto American streets that cannot recognize a fire engine. The National Highway Traffic Safety Administration, in a letter dated July 8 and made public Wednesday, has at last put on the public record what first responders in Phoenix, Austin, San Francisco, and Los Angeles have been telling the agency for some time. Driverless cars are driving into active emergency scenes. They are blocking the paths of ambulances and fire engines. They are failing to recognize traffic cones, flashing lights, smoke, and fire. The agency's administrator, Jonathan Morrison, has stated the matter without euphemism: "An AV that cannot safely interact with first responders is a danger to the general public. Every second matters when law enforcement officers, firefighters, or paramedics are answering a call." He is not wrong. He is, however, describing a problem that was identified in the engineering literature years before the deployment, and is now being managed as if it were a discovery.

It is true that Morrison had to write the letter he wrote. In the narrow sense in which regulators usually operate, it was a necessary intervention. The trouble is that a regulator asking a company to explain why its cars drive through active fire scenes is not a regulatory success; it is a confession that an unverified system was allowed to operate on public roads in the first place. NHTSA's earlier posture — closing its four-year Tesla phantom-braking probe earlier this summer, covering 416,000 vehicles, without enforcement action — did not encourage confidence that the letter, on its own, will change the operational posture.

And here it is worth being precise about what the vehicle's perception system actually is, because the public discourse has the misleading habit of treating it as a singular intelligence rather than a continually-tuned set of weights serving a continually-revised objective function. The robotaxi industry has the further habit, in its public communications, of treating "self-driving" as a binary condition — either the car drives itself or it does not — rather than a continuum of capabilities, each of which is acquired separately, each of which fails separately, and each of which fails in ways the marketing copy does not enumerate. A Waymo that can handle a dry Arizona afternoon at forty miles an hour on a wide boulevard cannot, on the available documentary record, recognize an active fire scene with smoke, cones, and a flashing light bar on a parked engine. These are not the same capability. They are two capabilities, both labelled "autonomy," and only one of them is ready.

The sensor-fusion stack — the layer that combines camera, lidar, and radar inputs into a single spatial map — and the semantic-segmentation models that label those inputs were never trained on the visual signatures of an emergency scene. The visual signature of a flashing emergency light varies by manufacturer and by jurisdiction. The optical properties of a traffic cone in low-angle sunlight differ from those of a traffic cone in the headlights of an oncoming ambulance. These are long-tail perception problems. The model performs well on the long-tail categories for which it has been trained, and degrades on the long-tail categories for which it has not. Smoke is a genuinely hard case. You cannot patch a fundamental perception failure with an over-the-air update to the routing layer; the machine literally does not see the thing you are telling it to avoid.

This is the same architectural gap the NTSB documented when it questioned Blue Cruise after fatal crashes in Texas and Pennsylvania. The pattern is not a mystery. It is the documented reality of shipping hardware that the software cannot yet reliably perceive.

The first rule of a mill floor is never to put a machine into production until you have proven it will not hurt the people working around it. That is the structural reality of the heavy industry my father worked in for forty years: you do not run unverified equipment in a space where human bodies move. The software industry operates on the opposite principle, shipping the beta to a paying public and treating the resulting collisions as a feedback loop. But a two-ton vehicle moving at forty miles an hour is not a beta test, and the paramedics standing in its path are not error logs.

The Goldman Sachs projection — a national commercial robotaxi fleet of sixty-two thousand eight hundred vehicles by 2030, in a market worth nearly nineteen billion dollars — is a fundraising document, not a transportation plan. Waymo, the Alphabet-owned early leader, runs a fleet of nearly four thousand vehicles across eleven American cities. This week it announced expansion to four more: Denver, Las Vegas, San Diego, Tampa. Amazon's Zoox and Tesla's robotaxi service are scrambling for the same pavement. The deployment curve is steep, the capital behind it is patient, and the engineering constraints are doing what engineering constraints always do under management pressure, which is to be negotiated with rather than respected. The constraint is being "solved," in the language of one industry technical disclosure, "in the field" — meaning, on the public, in real emergencies, at the cost of first-responder safety and emergency-response time.

There is an infrastructure-side answer, and it deserves the dispatch it is about to receive. V2X — vehicle-to-everything communication, with municipal transponders on emergency vehicles broadcasting a signal the cars cannot ignore — has been on the engineering table for a decade. It is also unfunded at the municipal scale that would matter, would require a public works program the deploying firms are not lobbying for, and does not solve the perception problem for emergency scenes that are not in the broadcast network, which is to say, for the great majority of them. It is the answer the industry prefers when asked why a federal standard is premature — look over there, at the technology that would solve this without regulation. It is also the answer that, on the available record, neither the industry nor the public sector is building. The regulatory lever remains the lever that exists.

That is the management decision behind the deployment. The technical failures NHTSA has now documented are the consequence of that decision, not an accident that befell it.

The liability architecture is doing the rest of the work. The industry has spent the last two years building the case, in state legislatures and in federal comment dockets, that the operator of a driverless vehicle should not be held to the standard of a reasonable human driver in an emergency encounter — that the perception failure is a known limitation of an emerging technology, and that tort exposure should be calibrated accordingly. The structure being assembled is one in which the engineering constraint is negotiated with, the perception stack ships anyway, and the legal architecture absorbs the consequences. Schedule, liability shield, repeat. The people inside the firms who set the engineering targets are not, on the documentary record, being asked to certify competence. They are being asked to ship.

I want to dwell on the regulatory architecture, because the architecture is the part of this story that nobody outside the Washington-and-Sacramento-and-Phoenix-and-Austin corridor has been asked to think about, and the architecture is doing the work.

There is no federal standard for autonomous-vehicle operation on public roads. NHTSA's traditional role, under the National Traffic and Motor Vehicle Safety Act of 1966, is to set Federal Motor Vehicle Safety Standards — the FMVSS, the rulebook that has governed American vehicle design for sixty years. For autonomous vehicles, the agency has not set such standards. It has, instead, allowed individual states to develop their own regulatory regimes. California and Arizona, the two states with the most deployed robotaxi miles, require companies to file law-enforcement interaction protocols before granting driverless permits. Other states have done less. Many have done nothing. The result is what an engineer would call a heterogeneous test environment and what a policy analyst would call a regulatory race to the bottom.

The Trump administration has actively sought to advance autonomous-vehicle deployment, including working to streamline federal regulation. The companies, predictably, want federal preemption of state safety regulations, which would also preempt the modest state-level protocols California and Arizona now require. They do not, on the available documentary record, want federal safety standards. Preemption without standards is the corporate objective: lock in the unregulated terrain while escaping the inconsistent patchwork of state rules. Cory Doctorow, in *The Internet Con* and across a decade of writing on platform companies, describes the move as "felony contempt of business model" — using the architecture of regulation to lock in the incumbents' preferred terrain while escaping accountability for the conduct the regulation would have policed. The structural decay pattern he names *enshittification* — good to users, then good to business customers, then value extracted from both for shareholders, then collapse — applies here with a substitution. The AV industry is running the same play on wheels.

To be fair — the phrase is doing real work here, not irony — there is a legitimate engineering argument that federal safety standards written today would freeze a moving technical frontier and entrench the incumbents who have the compliance apparatus to meet them. That argument has weight. It also has a counter-argument, which is that the alternative to a frozen standard is a four-thousand-car deployment that cannot recognize a fire engine, and that the weight of the frozen-standard argument is somewhat reduced when the moving frontier has produced a fleet that fails the perception test of a five-year-old with a bicycle.

The cui bono of the deployment architecture is concentrated and well-documented. Alphabet's quarterly disclosures treat Waymo as a long-term option on the robotaxi market, with the deployment curve and the regulatory landscape as the two variables that drive the option's value. The risk capital underwriting the deployment wants the deployment to continue. The first responders whose safety is being negotiated with do not have a comparable seat at the table. This is what a chokepoint looks like when the chokepoint is the perception stack of a vehicle that has been approved to operate without the perception stack being competent at the cases that matter.

This is not a counsel of despair. It is the opposite. Four constraints have historically limited platform abuse — competition, regulation, self-help interoperability, labor — and they apply here too, with the substitution that the relevant labor is the engineering labor inside the AV firms whose professional judgment is being overridden by the deployment schedule. Competition is constrained by first-mover capital. Regulation is being preempted. Self-help interoperability is not yet a question. Labor is being asked to ship before the long-tail cases are solved. Every one of these constraints can be reinstalled. Federal safety standards written now, with structured deployment sequences that require competence on emergency scenes before scale-up, are the obvious policy lever.

To be specific. A federal robotaxi safety standard, written now, should require: demonstrated competence on documented emergency-scene perception benchmarks before any vehicle is approved for unrestricted driverless operation; a structured deployment sequence that gates geographic expansion on demonstrated safety performance in already-deployed territories; a federal incident-reporting regime that supersedes the current state-by-state patchwork and feeds a public database; a right of action for first-responder organizations to challenge the deployment of vehicles that have failed documented perception benchmarks; a federal tort standard that holds operators to the duty of care of a reasonable human driver in emergency encounters, rejecting the industry's preferred limitation-of-liability framework; and explicit preemption of state law only where state law is less protective than the federal standard, not the other way around. None of this is exotic. All of it is the standard toolset of vehicle safety regulation, applied to a new vehicle category.

Canada, to take the comparison, has handled this with somewhat more caution. Transport Canada's approach to autonomous-vehicle testing has required pilot programs with safety protocols and provincial coordination, and has not pursued the federal preemption of provincial safety rules the U.S. industry is lobbying for. The result, in the available record, is a slower deployment, with fewer test miles, and no widely-reported cases of an AV driving into an active emergency scene in a Canadian city. Slower deployment is not, in itself, a virtue. But slower deployment that has not yet produced four thousand cars that cannot recognize a fire engine is, in the available evidence, preferable to faster deployment that has.

NHTSA has scheduled a round of company-by-company meetings by the end of the month to hear their solutions. Deadlines are the only part of regulatory processes that the regulated actually respect. The first responders who arrived at the active emergency scenes in Phoenix and Austin and San Francisco and Los Angeles — and found a driverless car blocking their path — did not show up to be test cases for a perception stack. They showed up to do their jobs. The cars that arrived before them arrived to do a different job, which was to demonstrate that the deployment was on schedule, that the option was building value, that the liability shield was holding, and that the engineering organization could be asked to ship one more time. The boards that approved the schedule and the executives who carried it out will not read Morrison's letter. They will, however, read the deadline. The perception stack the cars carry should be required, by federal standard, to be competent at the cases that matter, before the deployment curve carries them into another forty thousand cities.

## Sources

### src_001 — The Wall Street Journal, national_daily, Tier 1, originating
**Author:** Ellie Davis
**Publication date:** 2026-07-09
**Title:** Federal Regulator Warns Robotaxis Are a ‘Danger’ to the Public
**URL:** https://www.wsj.com/business/autos/federal-regulator-warns-robotaxis-are-a-danger-to-the-public-02ed28af

---

*Stewart Letterkenski is a heteronym in Main Street Independent's editorial architecture — an analytical voice, not autobiography of any actual person. The position this column expresses is the publication's position on the territory Stewart Letterkenski's lane covers, rendered through Stewart Letterkenski's register.*

*[About Stewart Letterkenski](/advocacy/stewart-letterkenski) · [How the pen names work](/about#how-the-pen-names-work)*
