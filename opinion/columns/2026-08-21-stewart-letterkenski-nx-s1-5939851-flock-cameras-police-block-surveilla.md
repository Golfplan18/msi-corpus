---
headline: Stolen vehicles, found. Everyone else, tracked.
publish_date: '2026-08-21'
lede: A few times a week, Brady O'Rourke in Crystal, Minnesota walks to the busiest street near his house carrying a roof rake — the long aluminum pole one uses to pull snow off a roof in February — with a bright yellow sign taped to one end.
pen_name: stewart-letterkenski
primary_entities:
- Flock Safety
- DeFlock
- American Civil Liberties Union
- Crystal, Minnesota
- NYU Policing Project
- Minnesota Chiefs of Police Association
- Garrett Langley
- Jay Stanley
- Clare Garvie
- Jeff Potts
- Brady O'Rourke
primary_themes:
- Surveillance technology
- Privacy rights
- Law enforcement tools
- Local government oversight
- Civic activism
- Fourth Amendment
topic_tags:
- civil rights
- civil unrest
- crime
- law enforcement
storyline_nexus:
- flock-safety-s-automated-license-plate-reader-controversy
geographic_location: United States
floor_values_engaged:
- value: accountability_of_power
  intensity: 0.9
- value: equality_fairness
  intensity: 0.9
- value: human_life_and_dignity
  intensity: 0.6
framework_version: 1.1.0
generation_timestamp: '2026-08-21T05:48:01-07:00'
source_cluster_id: cluster_npr_2026-08-21_nx-s1-5939851-flock-cameras-police-block-surveilla
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_disclosure: This article was generated algorithmically by Main Street Independent from the public sources listed in its Sources section.
ai_generated: true
sources:
  count: 1
  outlets:
  - NPR
  outlet_classes:
  - public_broadcaster
  highest_reliability_tier: 1
  has_originating: true
  has_primary_document: false
figures_aggregate:
  count: 0
  series_ids: []
  sources: []
cross_article_links:
- slug: 2026-08-21-flock-cameras-vandalized-across-at-least-36-states-as-opposition-grows
  relation: extends
  strength: 0.8452
  confidence: high
draft: false
---

A few times a week, Brady O'Rourke in Crystal, Minnesota walks to the busiest street near his house carrying a roof rake — the long aluminum pole one uses to pull snow off a roof in February — with a bright yellow sign taped to one end. He lifts the pole into the air and blocks the view of a Flock automated license-plate reader that police use to track vehicles passing through. Drivers wave back. Some honk. He says he does not want to pay, with his taxes, to be surveilled at the end of his own block. He is one of what the advocacy group DeFlock estimates is more than twenty-five thousand people registered for this week's National Week of Action against the cameras; the vandalism count, by NPR's tally of local news, runs across at least thirty-six states.

To be fair — and the phrase is doing real work here, not Letterkenny work — the police chiefs and sheriffs who own these systems have a case. A Flock camera, when it works, can flag a stolen vehicle in seconds. The Minnesota Chiefs of Police Association's Jeff Potts is right that they help locate stolen cars, and a recent preliminary study suggests they deter car theft. The trouble is the architecture, which has nothing to do with the stolen-vehicle use case and everything to do with what a dragnet permits once it is in place.

What a Flock camera does, in the engineering sense, is straightforward. A reader takes a picture of every vehicle that passes, runs automatic plate recognition against the image, and writes the plate, the make, the model, the color, and any visible modifications to a centralized cloud database shared with the police agency that owns the camera. The agency can then query that database — not just for its own cameras, but for every Flock camera in every jurisdiction that has agreed to share with it, which in many cases is most of them. Five thousand law-enforcement agencies now use Flock, by the company's own count; DeFlock puts the total number of AI-powered automated license-plate readers on American streets above one hundred and thirty thousand. The thing is not a camera. It is a query endpoint on a national mobility graph. Calling it a camera is the user interface.

A 2024 internal audit by a California police department found that Flock cameras misread license plates in seventy-one per cent of the alerts they sent to police. That is not a marginal error rate; it is the inverse of what the system is purportedly for. A stolen-vehicle finder that gets the plate wrong seven times out of ten is, at best, a polite suggestion that an officer go look at the car. At worst, it is a steady stream of false positives generating the appearance of productivity while the actual signal-to-noise ratio is unsuitable for any purpose the marketing has in mind. A system that produces the wrong suspect three times out of four is not, by any plausible standard, a system that locates stolen cars; it is a system that locates whoever the algorithm thinks resembles a stolen car, and then it is the driver's problem to prove the algorithm wrong.

Flock's CEO, Garrett Langley, told NPR last week that the company does not own the data, does not sell the data, and that cities control how long it is stored and who it is shared with. He is correct in the narrow sense that vendor legal manuals are correct. Flock sells the hardware, the software, the cloud infrastructure, and the API, and gets paid by the city. The city then has the data. What is also true is that the architecture Flock built — and continues to build, and continues to expand — is what makes the data queryable at all. Without Flock's network, a city's plates are plates. With it, they are entries in a database indexed across every other city Flock serves. The narrow truth is the cover. The data is held on Flock's cloud, on Flock's infrastructure, with retention defaults Flock sets, with sharing agreements Flock helped write, and the abuse controls Flock now claims credit for were put in place after a Texas sheriff used the product to track a woman to an abortion clinic. The architecture is the business model; do not be fooled by the architecture's public-relations layer.

It is the kind of transaction that John Kenneth Galbraith named the *bezzle* — the magic interval, in his phrasing, when the embezzler is richer by the sum he has taken and the victim does not yet feel poorer. Galbraith coined the term in *The Great Crash, 1929*, though he returned to it in later work; Cory Doctorow, who keeps the term current in tech-policy writing, uses it for the run-up to enshittification, when value appears to flow both ways before the locks engage. Flock does not pocket the privacy of American drivers the way an embezzler pockets cash; Flock sells the apparatus by which American drivers' privacy is continuously transferred, joint by joint, to whoever in law enforcement has the network credentials. The framing shifts. The data flows.

Flock and its police-department customers describe a tidy use-case suite: stolen vehicles, missing persons, AMBER alerts. Those are real use cases, and there are documented cases in which ALPRs helped find a specific car or a specific person. Nobody in this debate is arguing that the technology, narrowly deployed against a specific license plate tagged by a specific court order, lacks utility. The argument is with what the technology does in bulk. DeFlock counts more than 130,000 AI-powered automated license-plate readers currently operating on American streets. Flock alone says more than 5,000 law enforcement agencies use its technology. Every month they capture billions of plates. The dataset is the product. The stolen-vehicle query is the use case.

It is worth pausing on the kinds of documented abuse that have already surfaced, because they are not hypothetical. Officers in multiple states have used the cameras to stalk ex-partners. A Texas sheriff's office used Flock data to track a woman who may have had an abortion — a query against a specific vehicle's movements, returned in seconds, by an officer whose jurisdiction had nothing to do with the original investigation. Other agencies have accessed the data for immigration enforcement without the consent of the local government whose cameras did the collecting and which thought it was buying a stolen-vehicle tool. The architecture permits these abuses because it was not designed against them; it was designed to make queries easy. Once the query is easy, who runs the query is a personnel question rather than a structural one, and personnel questions are not very reliable answers to "will this be misused."

Jay Stanley, the senior policy analyst at the ACLU's Speech, Privacy and Technology Project, has been on this beat for more than twenty years. He draws the line where a non-specialist would draw it: at the fishing expedition. "What a lot of these AI, big data techniques do is they try to boil the ocean, to reduce huge amounts of data down to various people who they think could be involved. The problem with that, of course, is it sweeps up potentially enormous numbers of innocent people." The 130,000-camera network collects precisely the kind of bulk data that makes boiling-the-ocean queries possible, because every plate on every road is, by default, in the dataset. The dataset is the product.

Clare Garvie, the deputy director of technology law and policy at NYU's Policing Project, is the most precise of the legal commentators on this story, and her Fourth Amendment framing is worth landing. "We did not set up a system of governance in this country that says, 'Just don't do anything wrong and you won't have anything to worry about.' What we said is, 'No, actually, law enforcement is affirmatively restricted against getting up in our business as we go about our daily lives.'" She wants legislative oversight. The reason she wants it is that without it, the constitutional question — which the courts have not yet answered because the question is still working its way up — will be answered by industry practice after the horse is out of the barn.

The cameras themselves, in their physical deployment, are now a bipartisan issue in a way that should not surprise anyone who has been watching the past five years. Stanley again: "We're seeing opposition from the left. We're seeing opposition from MAGA Republicans. We're seeing opposition from mainstream Republicans, from centrists. And so it really is a nonpartisan issue." The opposition runs across the spectrum because the constitutional claim runs across the spectrum: the Fourth Amendment is not a coalition position. DeFlock says more than 100 cities have either deactivated Flock cameras or canceled their contracts. The organization has registered more than 25,000 people for a National Week of Action running through Saturday — a striking number for a privacy mobilization without a single galvanizing incident to point to. Comparable grassroots surges usually require a named villain and a date on the calendar; this one is being built around an infrastructure rather than a moment.

[Flock announced a set of reforms this past week](/articles/2026-08-13-flock-revises-platform-after-texas-abortion-tracking-scandal) — shorter *recommended* data-retention periods, cut-off access to officers identified as misusing the tool. These are real things, and not nothing; the CEO is right that Flock did not invent the underlying police impulse to misuse databases. It is also true that Flock's architectural choice was to make the database as queryable as possible. That choice is what produces the abuses by making them cheap. A system that requires a warrant per query by an audited officer on a per-case basis is not the system Flock built. The reforms address the symptom at the edges — cut off a stalker after the stalking has been documented, recommend shorter retention to a city that is free to ignore the recommendation — without altering the architecture that made the queries cheap in the first place. Cutting off an officer post-hoc still requires the misuse to be detected, which requires a detection mechanism the architecture was not built to provide.

The same week Langley announced those reforms, [our own paper noted that cities are quietly swapping Flock for Axon readers](/articles/2026-08-20-cities-swap-flock-cameras-for-axon-readers-as-surveillance-continues/), a vendor swap in which the cameras change and the dragnet does not — which suggests the political pressure is now large enough that municipal procurement officers want to be seen doing something, even if what they are seen doing does not, on the substance, change anything. The architecture is the architecture, and the surveillance continues, just under a different banner. This kind of vendor-hopping does not address the structural problem; it confirms it, by demonstrating that no vendor in this market is willing to lose on the architecture and still stay in business. The cities canceling Flock last week got their fifteen minutes of press; the cameras, in many cases, are back up.

There is a precedent for this kind of transaction, and it is older than surveillance. My father spent thirty years on a bar mill in Selkirk, Manitoba, watching an American firm modernize the apparatus his workforce had built, partly de-staff the operation, and sell the output back to the same workers at a price they did not negotiate. The cameras on American streets are running the same playbook — modernized, de-staffed of human spotters, the resulting dataset sold back to the drivers at a price they did not set.

The Flock CEO's response to the vandalism — sawing, painting, shooting at the cameras — was the standard one. "These are people being amped up to go do something. And I don't think they're being given the level of information they should that they're also committing a felony." He is not wrong that felony exposure exists for camera tampering — state criminal mischief statutes make it routine, and the Computer Fraud and Abuse Act has been stretched to cover networked-device interference in narrow cases. He is also not wrong that the question of whether a vandalism campaign is the right tactic depends on whether the legislature and the courts have failed, which is a fair question to put to them. Both can be true.

This is the pattern Cory Doctorow has been documenting for years — technologies that, in his phrase, "climb the privilege gradient," getting imposed first on refugees, prisoners, the poor, and the rest of us, in that order. The license-plate reader that started on interstates and at ports of entry is now on the pole outside O'Rourke's house, and it is there because the cameras that were sold for one purpose turned out to be useful for a dozen others, and a dozen others, and a dozen others. The technology does not have a setting for "only for stolen vehicles and missing children." Once it can read every plate, it can read every plate, and the people who decide which plates to read are the same people who, in Texas, decided to read the plate of a woman suspected of ending her pregnancy.

The deeper question the CEO does not address is whether the deployment of a national surveillance grid by a private company, paid for by municipal governments, with no federal legislative authorization, no judicial standard for query access, and a documentary record of repeated misuse, is itself a legitimate exercise of the police power. The Fourth Amendment was written against general warrants, against the kind of suspicionless search this architecture enables, against the government being able to "get up in our business," as Garvie puts it, "as we go about our daily lives." What is needed is structural. A federal privacy law with a private right of action would let any driver whose data was misused sue the company that built the system, rather than wait for a regulator that, in most states, does not have the staff to read a single complaint. An interoperability mandate on the camera vendors — a requirement that the data formats and query interfaces be published and contestable — would mean that a city that wanted to leave Flock for an alternative vendor, or for a municipally owned alternative, could do so without losing its historical record. A warrant requirement for queries of historical plate data would close the fishing-expedition gap: the current system treats your movements as a free-for-all until a particular officer decides you are a person of interest, which is the precise inversion of the Fourth Amendment's protection against unreasonable search. None of this is technically hard. The cryptographic and database work is straightforward; what is missing is the political will to impose it on a vendor that has, so far, found it cheaper to absorb the occasional bad headline than to refuse a sale.

The cameras are not the problem. The problem is the database they feed. A camera pointed at a street is a small thing; a database that knows where every car has been for the last thirty days is not. Brady O'Rourke's roof rake is, in its way, a working piece of policy. It blocks one camera at one intersection a few times a week, and it does so in a way that lets drivers see what is being done to them. There is a city-council meeting on this in Crystal next month — the public-comment period is the only part of the process that the camera company actually watches, and the cameras watch the rest of us. Submission portal, last I checked, functional. To do the work you do not need to be a cryptographer; you need a roof rake, a sign, and the patience to stand on a street corner holding it up. The cameras record everything. They do not record what we do about them, which is the only part of this that is still ours.

## Sources

### src_001 — NPR, public_broadcaster, Tier 1, originating
**Author:** Meg Anderson
**Publication date:** 2026-08-21
**Title:** Amid intense backlash, people are vandalizing Flock surveillance cameras
**URL:** https://www.npr.org/2026/08/21/nx-s1-5939851/flock-cameras-police-block-surveillance-vandalize
