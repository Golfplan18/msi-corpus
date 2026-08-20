---
headline: Maryland can shut ICE's commercial backdoor.
publish_date: '2026-08-20'
lede: Penlink sells Marylanders' cell phone locations to ICE without a warrant.
pen_name: stewart-letterkenski
primary_entities:
- Maryland
- Penlink
- Thomson Reuters
- Motorola
- Insight LPR
- LexisNexis
- Flock Safety
- ThunderCat Technology
- Georgetown University Law Center
- Center for Democracy & Technology
- Electronic Privacy Information Center
- We Are CASA
- U.S. Immigration and Customs Enforcement
- Anthony G. Brown
primary_themes:
- data privacy
- civil liberties
- immigration enforcement
- state privacy law
- data brokers
topic_tags:
- civil rights
- crime, law and justice
- government policy
storyline_nexus: []
geographic_location: United States
floor_values_engaged:
- value: accountability_of_power
  intensity: 0.9
- value: equality_fairness
  intensity: 0.9
- value: truthfulness
  intensity: 0.6
framework_version: 1.1.0
generation_timestamp: '2026-08-20T03:35:27-07:00'
source_cluster_id: cluster_npr_2026-08-20_nx-s1-5938822-maryland-privacy-data-brokers
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
- slug: 2026-08-20-maryland-coalition-asks-state-ag-to-investigate-data-brokers
  relation: extends
  strength: 1.0
  confidence: high
draft: false
---

Penlink sells Marylanders' cell phone locations to ICE without a warrant.

To be fair — the phrase doing real work here, not the Letterkenny kind — the companies named in last week's complaint have lawyers, and the lawyers have arguments. Penlink insists it does not process or sell precise location data of Marylanders. These are careful statements, drafted by careful people. They are also not what the products do.

Penlink's Webloc program is, by the company's own product description, a tool that lets law enforcement customers search cell phone location data. State records proposing an upgrade of the Maryland State Police contract for Penlink's PRX product — Citizen Lab previously reported a comparable contract for Baltimore County Police — list "geolocation information" as one of the product's capabilities. Maryland's statute defines "precise geolocation data" as information that can identify a consumer's, mobile device's, or vehicle's location within a radius of 1,750 feet. "Geolocation" is what the statute defines as precise when the data identifies location within that radius. The denial and the contract specification describe the same product on different days of the week. The discrepancy is, on the documents, the case the 2024 law was written to address.

The complaint was filed Wednesday with the Maryland Attorney General by the Georgetown University Law Center's Technology Law Clinic on behalf of We Are CASA and eleven other civil-rights and privacy organizations — including the Center for Democracy & Technology and EPIC. It names Penlink, Thomson Reuters, Motorola, Insight LPR, LexisNexis, Flock Safety, and ThunderCat Technology, alleging that they are collecting and selling personal information and location data on Maryland residents — and, in several cases, selling it specifically to U.S. Immigration and Customs Enforcement — in violation of the 2024 Maryland Online Data Privacy Act and the amendments that took effect last month. Penlink and Thomson Reuters deny the allegations. The other named companies did not respond, or returned automated out-of-office replies. Flock Safety's auto-reply to NPR's request for comment was, by the reporter's account, "Our media team is currently touching grass and taking a break."

Thomson Reuters's denial is the more carefully worded one. The company's statement says its license-plate-recognition product "is not capable of tracking real time locations of a vehicle; it provides access to ad hoc images collected randomly." That is a real engineering distinction at the level of any single camera's output. A choke-point camera that takes plates at intersections produces a different record than a continuous feed. It is true that "real time" and "random ad hoc" describe different operating modes for any one sensor. The trouble is that the constitutional question is not whether the LPR is real-time; it is whether the warrant requirement is bypassed. By design, the camera network lets law enforcement assemble from database query what no single camera could provide — a track of where a vehicle went, reconstructed from the timestamps and locations of ad-hoc plate reads. That is the warrant-bypass mechanism: not the camera's operating mode, but the network's queryable architecture. The cameras themselves do not appear to be on the same schedule as the press team.

The architecture the complaint describes has been known to people who pay attention for the better part of a decade. It is straightforward, and it is constitutional in a narrow technical sense that disguises a substantial evasion. The Fourth Amendment requires the government to obtain a warrant before conducting most searches. It does not require the government to obtain a warrant before *buying* what it would otherwise need a warrant to compel. So the government has learned to buy from data brokers what it cannot lawfully take — bypassing both the warrant requirement and the visibility that comes with seeking one through a court. Privacy and civil-rights organizations have been filing complaints and motions about this for years; bipartisan members of Congress have argued that the loophole should be closed. Congress has not closed it. ICE has been building a parallel apparatus through facial-recognition partnerships with local police. Residents answered the architecture directly last month when activists disabled Flock cameras in the field.

It is worth being precise about what Maryland's law actually prohibits, because the companies' denials ride on the precision. The Maryland Online Data Privacy Act of 2024, with updates that took effect last month, bars data brokers from collecting or sharing Marylanders' sensitive data, including location data, unless it is to deliver a product or service the consumer requested, or in response to certain law enforcement demands. And it bars — this is the unusual part — brokers from selling to agencies that enforce immigration law, unless a warrant is presented. Maryland is one of a small group of states (New Jersey, Virginia, Oregon, and Connecticut have analogous data-sale restrictions) trying to wall off the chokepoint from one specific buyer. Maryland's ICE-firewall is the most pointed. Greg Nojeim, who directs the Center for Democracy & Technology's Security and Surveillance Project, told NPR the result is an attempt to close what the privacy literature calls the "data broker loophole": the federal practice of buying from private parties what it would otherwise need a warrant to obtain directly. "Maryland is telling ICE, 'Get a warrant if you want Marylanders' sensitive data,'" Nojeim said. That is a sentence the federal government does not want to hear, because the federal government has gotten used to skipping the warrant.

The four-part structure Cory Doctorow's chokepoint-capitalism analysis names — data brokers here, ICE on one side, Maryland residents on the other, and a state law trying to firewall the gatekeeper — fits in outline. ICE is not the textbook monopsonist; it is a single demand-side actor for a class of product nobody else values at the price ICE pays, and the position lets it acquire the supply on terms the seller would not otherwise accept. That is monopsony in its pure form. The brokers sell because ICE is the only deep buyer; ICE buys because the brokers have what ICE needs and the administrative subpoena gives ICE a warrant substitute. The trouble is the converse — that ICE's administrative subpoena gives it what would otherwise need a warrant, and that the brokers sell because federal contract doctrine legalises the trade regardless of state privacy law. Maryland's firewall tries to break that loop. Hardening the firewall here means hardening it at the point of sale.

The Canadian parallel is exact, if quieter. Canadian privacy law is split between PIPEDA federally and Quebec's Law 25; the Charter Section 8 doctrine articulated in *R. v. Spencer* (2014) and reinforced in *R. v. Bykovets* (2024) holds that subscriber information attracts a reasonable expectation of privacy, so a warrant is required. It is true that this baseline is precisely what Maryland is reaching for at state level. The trouble is that the federal government keeps proposing — Bill C-2 in 2025, Bill C-22 reintroduced in March 2026 as the Lawful Access Act, 2026 — to substitute administrative orders for warrants, with the same private-party-bypass architecture Maryland is trying to firewall. No province has yet imitated the ICE-specific firewall.

What is being sold, when a data broker sells to ICE, is not, strictly speaking, the right of access to a single location. What is being sold is the right of access to the entire system of movements, meetings, and routines that location data reveals. The data broker is selling what is, in plain language, the derivative product of the surveillance apparatus: a service whose only value is the surveillance, and whose only customer is the government. The argument that "we are just a data company" carries the same logical force as "we are just a locksmith" applied to a company that sells master keys to one customer: the police. It is the locksmith's commercial freedom; it is also the locksmith's quiet role in making the warrant redundant.

The strongest case the named companies have is that Maryland's law is novel and untested. The 2024 statute is barely two years old; the July amendments have been in force for seven weeks. There will be motions. There will be challenges under the dormant Commerce Clause. There will be arguments that geolocation data accurate to 1,750 feet is too broad a definition, or that a license-plate-reader capture at a toll plaza is not "sharing" within the meaning of the statute. That is a real argument. It is also not the strongest argument against the law. The strongest argument against the law is the one the companies have not yet made in writing: that the entire enterprise of selling surveillance access to federal agencies is incompatible with the constitutional structure the country inherited. They will not make that argument, because making it would require conceding that what they have been selling is surveillance, not data.

What enforcement of the existing law looks like, in practice, is not glamorous. It is a subpoena, a civil investigative demand, an order to cease and desist, an injunction, an assurance of voluntary compliance filed with a court, and the public-record trail of each. The complaint calls on Attorney General Anthony G. Brown to "use the full force" of the state's privacy laws. The AG's office, when reporters asked earlier this summer about the new provisions taking effect July 1, said, "Entities subject to the law should ensure they are in compliance." That is the regulatory equivalent of a shrug — technically correct, operationally inert. The office has now declined to comment on the complaint. Declining to comment on a complaint that names the warrant-substitute as the violation is not neutrality; it is the loophole, made administrative. The federal contracts continue. ICE continues to acquire what the state's firewall, on paper, was meant to deny it.

The deadline has now been set, in public record, by someone other than the data brokers.

## Sources

### src_001 — NPR, public_broadcaster, Tier 1, originating
**Author:** Jude Joffe-Block
**Publication date:** 2026-08-20
**Title:** Privacy advocates call on Maryland to investigate data brokers
**URL:** https://www.npr.org/2026/08/20/nx-s1-5938822/maryland-privacy-data-brokers
