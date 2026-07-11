---
headline: Waymo Makes First Responders Pay to Debug Its Unverified Public-Road Software
publish_date: '2026-07-10'
lede: Alphabet's Waymo forces first responders to pay for debugging its unverified public-road software.
pen_name: stewart-letterkenski
primary_entities:
- Waymo
- Austin Police Department
- California
- Texas
primary_themes:
- autonomous vehicles
- law enforcement
- traffic regulation
topic_tags:
- law enforcement
- transport
- robotics
- artificial intelligence
- government policy
storyline_nexus: []
geographic_location: United States
floor_values_engaged:
- value: accountability_of_power
  intensity: 0.9
- value: human_life_and_dignity
  intensity: 0.9
framework_version: 1.1.0
generation_timestamp: '2026-07-10T11:57:17-07:00'
source_cluster_id: cluster_wsj_2026-07-10_dache-for-police-getting-driverless-cars
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
- slug: 2026-07-10-police-struggle-to-ticket-autonomous-taxis-as-robotaxi-fleets-grow
  relation: extends
  strength: 0.2838
  confidence: high
draft: false
---

Alphabet's Waymo forces first responders to pay for debugging its unverified public-road software.

It is true that, in the narrow sense in which the company usually means these things, Waymo's cars are better drivers than most of the people I share the road with in Peterborough, and probably better than me on my worst-tempered mornings. The trouble is that the standard being applied — "better than a person operating on three hours' sleep and a drive-through coffee" — is not the standard the rest of our transportation law is built to evaluate. Transportation law is built to find the person who did the thing, write them a piece of paper, and let the consequences of the paper do the rest of the work. Waymo has spent five years building a system in which the piece of paper has no address.

The architecture of the avoidance is worth looking at, because it is not accidental. In Texas, a police officer cannot write a moving-violation ticket to a car without a driver — the ticket requires a signature, and the signature has to come from a person sitting in the seat. So when an Austin officer sees a Waymo run a stop sign, the officer files a complaint in municipal court. A police lieutenant, William White, then confirms the identity of the vehicle's registered agent. In Waymo's case, the registered agent is the company's law firm. The court mails a summons to the law firm. The law firm decides whether to appear or pay a fine. White, who serves on the state bodies that are supposed to be figuring this out, called it "a very cumbersome process, and it isn't done a whole lot just because of the complexity of doing it versus writing it a ticket." The regulation isn't merely lagging. It has been routed, deliberately, into a system the company designed to be slow.

The mechanism is recognizable from any industry in which a company has discovered that, if the only penalty for a violation is the cost of a process the company itself administers, the violation is the business model. There is no other word for it. The company is the regulator's mailbox. The company is also the regulator's court of last resort. The company is, in any practical sense, the enforcement arm of the law that governs it, because the only person the law is built to punish is the person who happens to be sitting in the seat, and there is no person sitting in the seat, by design.

The engineering reality underneath the marketing — and Waymo's marketing is unusually polished, which is to its credit in the same way that a well-tailored suit is to the credit of someone who has just stolen your car — is that the cars do not, in fact, know how to do the things a person in the driver's seat has always been able to do. They do not reliably stop when a California Highway Patrol officer flips the lights and shouts "Stop, Waymo" through a speaker, as Elliot Slade and his fiancée discovered on U.S. 101 on May 18, when their vehicle drove into a construction zone and kept going. They do not reliably move for ambulances: in March, a Waymo blocked an ambulance from reaching a shooting in Austin, a delay the company says did not affect patient outcomes, and which a person who is not a doctor might note that the company is not, in fact, qualified to certify. They do not reliably interpret hand signals from officers, though Tesla's forthcoming Cybercab, by Tesla's own June document, will. They rip street signs out of concrete at University of Texas football games. They get lost at the end of dead-end roads at graduation ceremonies and have to be rescued by human employees in what the officer described, with admirable restraint, as a "corral" of traffic cones.

It is worth being precise about what the vehicle actually is when it fails to respond to a police officer's hand signals. It is not a distracted employee. It is a continually-tuned set of weights serving a continually-revised objective function, operating within a bounded operational design domain — ODD is the engineering term for the specific physical and environmental conditions the software was trained to handle. When the environment falls outside that domain, the system's behavior is not insubordination; it is a formal specification failure. In Phoenix, traffic division officers reportedly underwent in-person training from Waymo to learn how to conduct traffic stops with clear, concise hand movements, on the theory that consistency might eventually allow the vehicle to comprehend what is being asked. This is the equivalent of teaching a human driver a new language by shouting at them, except the human driver has a central nervous system capable of generalizing from one shouting incident to the next. The software does not. Shipping a vehicle that cannot comprehend a police officer's hand signal is not a hiccup of the rollout, as the industry's lobbying apparatus would have it. It is deploying an appliance that cannot recognize the physical layer's most basic override.

Waymo has trained thirty-five thousand first responders in person, which is a real number doing real work, and the company is right that in Phoenix — the city with the most mature deployment — officers have learned to work around the machine. Detective Kurtis Merena of the Phoenix traffic division made the observation the company likes to quote: "Issuing a citation is never off the books. The ultimate goal is to correct bad behavior." What Merena is describing is not a system. It is a workaround. Officers in Phoenix have been given a phone number, a training session, and a relationship in which they negotiate, case by case, with a fleet of cars that does not, in the legal sense, have a driver to ticket. The relationship holds because the people on both ends of the phone have decided to make it hold. It is not portable. It does not survive a personnel change, a contract renegotiation, or a bad week. It is the relationship of a department that has been given the resources to make the call, and a company that has been given the time to answer it. Every other jurisdiction that takes the cars does not get the call.

The documentary record from Austin tells us which role the police are actually playing. Since July 2023, the city has documented 298 incidents involving autonomous vehicles. 231 of them involved Waymos. Eight of those led to a complaint being filed. Eight out of 231 is not, by any reasonable reading, a rate of correction. It is a rate of impossibility.

The autonomous-vehicle industry's expansion is climbing what Cory Doctorow calls the privilege gradient — the pattern by which unverified technology is deployed first in environments where the cost of failure can be externalized, sanding the rough edges off the software against the bodies of people who cannot fight back, until it is smooth enough for the affluent. The structural reality is that the AV industry has successfully lobbied to shift the burden of proof and the cost of enforcement onto municipalities lacking the technical apparatus to audit a neural network's decision boundary. This is a classic case of the public sector absorbing the research and development risk while the private sector harvests the commercial value, only here the public is also absorbing the physical risk of the beta test. [NHTSA's chief, the day before Waymo's expansion announcement, asked AV developers to do better with first responders](/articles/2026-07-09-nhtsa-orders-av-companies-to-address-robotaxi-interference-with-first-responders/) — the federal posture reduced to a mandate that developers improve their interactions. The [FedEx Freight CEO made a similar point](/articles/2026-06-01-autonomous-truck-technology-is-ready-but-regulation-lags-fedex-freight-ceo-says/) a month ago about the trucking side: the technology is ready, but the regulation lags. Goldman Sachs, whose business it is to put numbers on things that don't yet exist, projects sixty-three thousand commercial robotaxis on American roads by 2030. While passenger robotaxis struggle with hand signals, the commercial sector presses forward, with companies like [PepsiCo running dozens of driverless trucks on public highways](/articles/2026-06-08-pepsico-runs-35-driverless-trucks-on-arizona-roads-in-first-large-scale-consumer/) and compounding the burden on municipal infrastructure. The thing about sixty-three thousand is that it is no longer a number a regulator can chase with a phone call. It is a number that has to be governed by a system, or by something other than a system.

California, to its credit, has done the minimum. A new state law effective July 1 allows officers to issue notices of noncompliance directly to an AV manufacturer for moving violations, which solves the signature problem and shortens the path between incident and consequence. The law does not, so far as the reporting makes clear, scale a fine large enough to make four thousand cars, expanding to sixty-three thousand by 2030, take the consequence seriously. It is a step. It is not a system.

What a system would look like is not mysterious, and it is not unprecedented. It would mean a federal floor — not the NHTSA nonbinding guidance we have now, but a preemption rule that says the same enforcement mechanism applies in every state where a robotaxi operates. It would mean fines scaled to the fleet, so that a moving violation on a single vehicle is a citation, but a pattern of moving violations across a fleet is a finding against the manufacturer's licence to operate in that jurisdiction, the way a pattern of moving violations against a human driver eventually costs them the licence. It would mean a public incident database — the equivalent of the FAA's aviation reporting system, or of the NTSB's accident investigations — into which the 298 incidents in Austin and the comparable figures in every other operating city actually flow, in a form that is searchable and citable. It would mean a right-to-audit-the-machine framework, the kind that any safety-critical system the public is asked to trust ought to come with as a matter of course, instead of the marketing slogan of "we tried it on some inputs and it didn't crash" that has passed, for far too long, as a specification.

On a bar-mill floor, a millwright's job was to read a machine's behavior, diagnose the mechanical fault, and tag it out before the line went down. If a machine had ripped a street sign out of the concrete and then parked itself in a dead-end cul-de-sac, it would have been shut down and refused to management until the fault was isolated. The modern software deployment model does the reverse: it ships the machine onto the public right-of-way, tags the public with the cost of the fault, and calls the subsequent municipal congestion an edge case to be solved in the next over-the-air update. The structural remedy is not a suggestion box at NHTSA; it is a bright-line regulatory mandate requiring AV manufacturers to prove their software's operational design domain encompasses every physical override a first responder might issue, and banning the deployment of vehicles that fail that proof on public streets.

Waymo's spokesman, asked about all of this, said the company's goal is to be "a trusted public safety partner, not an additional burden, for first responders." The phrasing is, in the technical sense in which I was trained to use the word, beautiful. The grammar places the burden on the responder, not on the responder's new interlocutor. The vocabulary, "partner," implies a relationship of equals, in which one side is not a four-thousand-vehicle fleet and the other is a single officer at an intersection in Austin. The marketing is correct. The cars, in the places where they are, are an additional burden for first responders. The company is asking to be trusted, in the same way the Federal Aviation Administration was once asked to trust the manufacturers of the 737 MAX. The 737 MAX did not have a registered agent. It had a fleet, and it had two crashes, and it had, in the end, a grounding. The cars on U.S. 101 do not have a fleet, in the language of the law. They have a registered agent. The difference is the size of the letter the agent eventually has to answer.

The four thousand cars are not the problem. The four thousand cars are the load. The problem is the distance between the load and the consequence, and the load is, in the available indicators, growing faster than the consequence.

There is a public consultation open at NHTSA on automated-vehicle safety standards. The deadline matters because deadlines are the only part of regulatory processes that the regulated actually respect, and submissions are the only part of regulatory records that subsequent governments have to read. You can pay extra for the privilege of being the beta-tester for a company that charges you for the ride.

## Sources

### src_001 — The Wall Street Journal, national_daily, Tier 1, originating
**Author:** Ellie Davis
**Publication date:** 2026-07-10
**Title:** A Big Headache for Police: Getting Driverless Cars to Obey Traffic Laws
**URL:** https://www.wsj.com/business/autos/a-big-headache-for-police-getting-driverless-cars-to-obey-traffic-laws-d4a5efd2

---

*Stewart Letterkenski is a heteronym in Main Street Independent's editorial architecture — an analytical voice, not autobiography of any actual person. The position this column expresses is the publication's position on the territory Stewart Letterkenski's lane covers, rendered through Stewart Letterkenski's register.*

*[About Stewart Letterkenski](/advocacy/stewart-letterkenski) · [How the pen names work](/about#how-the-pen-names-work)*
