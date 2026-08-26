---
headline: The Physics Behind the Data Center Backlash
publish_date: '2026-08-26'
lede: Hyperscale operators drain rural aquifers and run their server farms on rural power bills.
pen_name: stewart-letterkenski
primary_entities:
- Murdock
- Nebraska
- Sierra Club
- Texas
- Wyoming
- Pennsylvania
- New Mexico
primary_themes:
- Bipartisan data center opposition
- Unusual political coalitions
- Rural community concerns
topic_tags:
- politics
- environment
storyline_nexus: []
floor_values_engaged:
- value: equality_fairness
  intensity: 0.9
- value: accountability_of_power
  intensity: 0.9
- value: human_life_and_dignity
  intensity: 0.6
framework_version: 1.1.0
generation_timestamp: '2026-08-25T22:24:51-07:00'
source_cluster_id: cluster_ap_2026-08-25_data-centers-bipartisan-opposition-trump
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_disclosure: This article was generated algorithmically by Main Street Independent from the public sources listed in its Sources section.
ai_generated: true
sources:
  count: 1
  outlets:
  - Main Street Independent
  outlet_classes:
  - other
  highest_reliability_tier: 1
  has_originating: true
  has_primary_document: false
figures_aggregate:
  count: 0
  series_ids: []
  sources: []
cross_article_links:
- slug: 2026-08-26-data-center-opposition-spans-republican-democratic-and-swing-states
  relation: extends
  strength: 0.6474
  confidence: high
draft: false
---

Hyperscale operators drain rural aquifers and run their server farms on rural power bills.

That is what is happening on the ground in the counties where opposition has surfaced over the last several months — Republican-dominated counties in Nebraska, Texas, and Wyoming; the swing precincts of Pennsylvania; Democratic-leaning counties in New Mexico. The pattern looks partisan on a political map. It is hydrological and electrical on an engineering map, and the engineering map is the one that determines whether the local ratepayer and the local aquifer come out ahead.

This is a column about the engineering.

A hyperscale data center is, in its essentials, a building full of computers whose heat has to go somewhere. The IT load — the servers themselves — produces roughly equal heat for each watt it draws, by the first law of thermodynamics, which is not negotiable. The job of the rest of the facility is to move that heat from the chips to somewhere it can be dumped: the atmosphere, a river, a cooling tower, or, increasingly, back into a district-heating loop as recovered waste heat. Everything interesting about the politics of data centers follows from how that heat gets moved, and how much water and electricity the moving takes. Kate Crawford made the load-bearing observation half a decade ago: AI is infrastructure first and cognition a distant second, "made from vast amounts of natural resources, fuel, and human labor." The opposition surfacing in five states is not contesting that framing. It is contesting who absorbs the bill.

The two metrics that govern the rest are PUE (Power Usage Effectiveness) and WUE (Water Usage Effectiveness). PUE is total facility power divided by IT power; a PUE of 1.0 is theoretical perfection, where every watt goes into computing. The hyperscale operators publish PUE figures in the 1.1 to 1.3 range — Microsoft, Google, and Meta's most efficient facilities run around 1.12, which means roughly 12% of the electricity the facility draws is being spent not on computing but on cooling, networking, and lighting the building. That 12% is not nothing, but it is the smaller number.

WUE is the metric the politics is actually about. WUE is liters of water consumed per kilowatt-hour of IT load, and it varies by an order of magnitude depending on the cooling architecture. Evaporative cooling — the cheapest, most common design at hyperscale — sits in the 1.0 to 2.0 liters-per-kWh range, dominated by cooling-tower make-up water. Liquid-to-chip and immersion cooling, which the industry is increasingly marketing as the water-frugal option, can run a tenth of that, on the order of 0.1 L/kWh or less. Rear-door heat exchangers and adiabatic dry coolers fall in between. The hyperscalers' own sustainability reports will give you a different number for every site, and the dry-cooled sites are nearly always in the temperate Pacific Northwest or the Nordic countries, not in the High Plains.

Do the arithmetic on a 100-megawatt facility. At WUE 1.5 L/kWh — middle of the evaporative range, conservative — a 100 MW data center draws roughly 1.3 billion liters of water a year, or about 350 million US gallons. That is the annual water draw of a small city, in a county that frequently does not have a small city. Scale up to a 1-gigawatt campus — Microsoft is contracting for 835 MW from the restarted Three Mile Island unit; Meta has signed for the full 1.1 GW of Constellation's Clinton facility in Illinois; Amazon sits adjacent to Talen's Susquehanna nuclear — and you are at 13 billion liters a year for the largest sites, equivalent to the municipal supply of a mid-sized US city, drawn continuously from whatever watershed the operator has chosen.

Now look at the watershed the operator has chosen. The Republican-dominated counties resisting data center sit-downs include the Nebraska counties overlying the Ogallala aquifer, the Texas counties overlying the northern extension of the same formation, and Wyoming's Powder River Basin counties where the surface-water rights are already spoken for. The Ogallala — USGS monitoring since the 1970s — has been declining at rates from less than a foot per year in the Nebraska Sandhills to more than two feet per year in the Texas Panhandle, with overall storage loss in the High Plains on the order of 10% since measurement began and substantially more in the southern districts. The aquifer does recharge. Slowly. In some places not at all on a planning horizon. A 100 MW facility drawing 350 million gallons a year is, against that arithmetic, a measurable fraction of the water budget of a county that has been managing depletion for half a century.

The Democratic-leaning and swing-state opposition is not, despite the political map, about a different physical problem. New Mexico's Doña Ana and Sandoval counties are overlying the Mesilla and Rio Grande aquifer systems, which the New Mexico Office of the State Engineer has been allocating under declared groundwater rights since the 1930s, and which have been in net decline for most of that period. Pennsylvania's Luzerne and Susquehanna counties sit on the Susquehanna River basin, which feeds the Chesapeake and which has, in dry summers, become a contested resource between New York City (which holds pre-emptive water-supply rights), the Susquehanna's basin communities, and a fleet of gas-and-now-electricity interests that have already been through one round of "we are the future, trust us" promises.

The electricity side of the accounting is where the ratepayer question comes from, and the politics there is no less a function of the physics. A 100 MW data center is, by the order of magnitude above, a single point load larger than almost any single industrial customer a US utility has historically wired for. Wiring it requires new transmission lines, new substations, often new generation; the capital cost of transmission build-out for a hyperscale interconnection is, in PJM and ERCOT filings over the last several years, in the low hundreds of millions of dollars per site, with the cost allocated by state policy through one of three mechanisms — direct assignment to the hyperscaler (rare), socialization into the rate base (common), or a hybrid with a chunk assigned and the rest socialized. The socialization option is the one that has produced the ratepayer complaints surfacing in Nebraska, Texas, and Pennsylvania.

The industry calls this an "economic development" rate, which is the same name utilities have been putting on industrial recruitment deals since the 1950s. The arithmetic is the same arithmetic it has always been: the new load arrives; the utility builds the wires; the wires are paid off over thirty years; the residential and small-commercial ratepayers carry the fixed costs in the period before the new load ramps; the new load then discounts itself off the rate base, on the theory that the new revenue is incremental. The theory is contestable when the new load is interruptible — a factory that closes during a downturn sheds its share of the fixed costs — and it is much more contestable when the new load is prime power. Hyperscale operators do not interrupt. They cannot; the chips inside their facilities are rated for thermal cycling that does not include the cycling a steel mill would accept. The fixed-cost socialization is therefore a permanent transfer, not a temporary one, and the ratepayer is paying for thirty-year wire that serves a single customer with one operating mode.

This is the part the operators do not put in their sustainability reports. PUE and WUE are voluntary disclosure. The grid-cost-allocation mechanics are state-by-state regulatory decisions, and the docket numbers are public. In Texas, ERCOT's interconnection queue has data center projects accounting for a substantial fraction of the pending load. In Pennsylvania, PJM's 2025/2026 capacity auction cleared at prices that produced headlines, and the data-center load growth is the named driver in PJM's own filings. These are not contested facts. They are dockets.

The reason the opposition is bipartisan is that the engineering does not sort along party lines. An evaporative cooling tower draws the same water regardless of which party's sign is on the courthouse. A prime-power contract socializes the same transmission cost whether the utility is investor-owned, cooperative, or municipal. A 100 MW facility is a 100 MW facility, and the ratepayers are in every direction.

What binds the local opposition is that the operators' offer — jobs, taxes, a seat at the AI table — runs into the same arithmetic everywhere. The water draw does not negotiate with the county commissioner's party registration. The thirty-year wire does not negotiate with the ratepayer's. The Sierra Club chapter and the cattle rancher in Murdock do not have to agree on climate policy to agree that the offer is bad; the physics is doing the coalition work for them.

The lever, such as it is, sits in the state regulatory dockets the hyperscalers do not want to discuss. PUCs can — and a few have begun to — require direct assignment of transmission costs to the hyperscaler rather than socialization. PUCs can require site-specific WUE disclosure and binding limits on cooling architecture, with the consequence that the operator cannot choose evaporative cooling in a closed basin without paying a real price for the water. PUCs can refuse to extend prime-power contract terms on the theory that the operator should bear interruptibility, or at least pay for non-interruptibility in the rate it pays. None of these are radical interventions; they are the normal tools of utility regulation. They have not been deployed because the industry has lobbied, with some success, to keep them off the table.

The administration's posture — promote the buildout nationally while its own [Senate apparatus warns of voter fury](/articles/2026-08-20-trump-promotes-data-centers-as-senate-gop-arm-warns-of-voter-anger/) — is itself an artifact of the same physics. The buildout is real-economy infrastructure now, with real-economy resource costs, and the people absorbing those costs vote in primaries. The follow-up [coverage of opposition mounting as tech giants court communities](/articles/2026-08-23-data-center-opposition-mounts-as-tech-giants-court-communities/) was about the courtship phase. This is what comes after — the moment the courtship stops working.

The Murdock meeting is not a coalition story. It is a hydrology story that organized itself into a coalition because hydrology is patient and bipartisan. The water will still be gone in thirty years whether the data center goes there or not. The wire will still be on someone's rate bill. The industry's offer — jobs, taxes, a seat at the AI table — is, against that arithmetic, the same offer the same industries have been making to the same rural counties since the 1950s, and the answer, increasingly, is the answer it has always eventually been.

## Sources

### src_001 — Main Street Independent, other, Tier 1, originating
**Title:** ## Data center opposition spans Republican, Democratic, and swing states
**URL:** https://mainstreetindependent.com/articles/2026-08-26-data-center-opposition-spans-republican-democratic-and-swing-states/
