---
headline: The location-data racket selling American troops by the credit card
publish_date: '2026-09-04'
lede: The advertising industry runs a location-data racket that sells American troops by the credit card.
pen_name: stewart-letterkenski
primary_entities:
- Ron Wyden
- Pat Harrigan
- US Air Force
- US Army
- US Special Operations Command
- US Navy
- Pentagon
- Zach Edwards
- Decryptads
primary_themes:
- Military security
- Location data privacy
- Mobile advertising identifiers
- Data brokers
- Pentagon oversight
topic_tags:
- armed conflict
- conflict, war and peace
- government policy
- law enforcement
storyline_nexus: []
geographic_location: United States
floor_values_engaged:
- value: accountability_of_power
  intensity: 0.9
- value: human_life_and_dignity
  intensity: 0.9
- value: truthfulness
  intensity: 0.6
framework_version: 1.1.0
generation_timestamp: '2026-09-04T07:06:03-07:00'
source_cluster_id: cluster_guardian_2026-09-04_us-news-2026-sep-04-military-disables-ph
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_disclosure: This article was generated algorithmically by Main Street Independent from the public sources listed in its Sources section.
ai_generated: true
sources:
  count: 1
  outlets:
  - The Guardian
  outlet_classes:
  - national_daily
  highest_reliability_tier: 2
  has_originating: true
  has_primary_document: false
figures_aggregate:
  count: 0
  series_ids: []
  sources: []
image:
  url: /articles/2026-09-04-us-military-branches-disable-ad-trackers-on-service-members-devices.png
  alt: 'Illustration accompanying article: US military branches disable ad trackers on service members'' devices'
  source: ai_generated
cross_article_links:
- slug: 2026-09-04-us-military-branches-disable-ad-trackers-on-service-members-devices
  relation: extends
  strength: 0.8972
  confidence: high
draft: false
---

The advertising industry runs a location-data racket that sells American troops by the credit card.

On Friday, Senator Ron Wyden and Representative Pat Harrigan released letters from the air force, the army, and US Special Operations Command confirming what they had been told in private for months — each branch had, on different dates and through different mechanisms, disabled the mobile advertising identifiers on military-issued computers and phones. The air force said two months ago. Special Operations Command said "recently." The army said its mobile devices had been blocked by default since at least February 2026, its Windows computers since before 2021. Give the armed forces this much: the identifiers finally came off. That is competent housekeeping, and it was overdue. It fixes less than the announcement suggests.

Harrigan, a North Carolina Republican, put the stakes plainly: an adversary "should not be able to pull out a credit card and buy information that helps them track American troops." He is not wrong about that. He is wrong about the rest of it, which is that the trade his warning names is the same trade the announcement does not touch. Wyden, who has pressed the Pentagon on this for months, says the efforts "have not been effective at neutralizing this threat." Zach Edwards, co-founder of the privacy ad-tech firm Decryptads, confirms why: the restrictions keep military devices out of bulk data sales, but personnel can still be tracked by triangulating device details with network and location data. The industry's standard answer to every privacy control — when the identifier goes dark, fingerprint the device instead — is what the air force did not announce closing.

A mobile advertising identifier — Apple calls it IDFA, Google calls it GAID, the trade groups have settled on MAID — is a per-device token the operating system broadcasts to every app that asks for it. Disabling it is a settings-flip; the setting lives in iOS Settings and in the Android equivalent. It is true, in the narrow engineering sense in which such things are usually true, that the OS no longer broadcasts the identifier once the flip has been made. The trouble is that the OS-level identifier is one identifier among many, and not, by 2026, the most useful one. Apps routinely fingerprint devices by their installed application list, their screen resolution, their locale and time zone, their battery state, the names of nearby Bluetooth peripherals, and the cell-tower and Wi-Fi-network identifiers their radios touch. The SDK-level identifier that an ad network embeds in the weather app your phone shipped with will produce a comparable trail even after the OS-level identifier has been switched off. The thing the setting does not do is anything about the cell-tower location feed the carriers sell. The thing the setting does not do is anything about the Bluetooth and Wi-Fi beacon networks retailers install in their stores. Turning off the MAID changes the key, not the lock. The Pentagon switched off a setting. The data broker who sold the data, and the foreign adversary who bought it, did not receive a memo.

Reuters reported in July that mobile videos deployed personnel had been posting to the internet were already helping Iran target American bases in the Middle East — the same data path the Pentagon is announcing it has now partially closed. The threat is not hypothetical. The size of the surface the announcement does not close is what is hypothetical, and the answer should disturb anyone who has looked at it.

The larger exposure was never just the hardware the armed forces issue. The crowd around a base — the contractor with a personal phone, the cafeteria staff, the family visit on leave, the rideshare driver who drove the captain from the airport — generates the location data an adversary actually needs. The contractor's own MAID still rides into the same broker feed the army just opted out of; the cafeteria worker's commute is still for sale at a credit-card swipe; the spouse's app pulls a location update at every weather check. You do not need a soldier's identifier; you need the congregation's. The same broker market already slips past the rules that were supposed to protect sensitive sites: this spring, [lawmakers warned](/articles/2026-05-21-democrats-warn-data-broker-rules-miss-key-washington-sites-including-cia/) that the data-broker rules miss key Washington locations, including the CIA. Disabling its own identifiers is one institution finally opting out of a market the institution had inadvertently been trading in; the trade keeps selling everyone around the institution.

The architecture is the one Cory Doctorow has spent years documenting under the name chokepoint capitalism: a middleman positioned between two groups of users — the device-owners and the buyers of device behaviour — extracting rent from both sides because there is no realistic way for either side to reach the other without going through him. The national-security version of this story is the most photogenic, because the consequences arrive on the evening news and the names of the dead get attached to committee hearings. The ordinary American version is the daily one: a data broker sells a person's location history to a bail bondsman, a process server, or a matrimonial investigator, and no one writes a press release. Both stories use the same wire. The patchiness of the Pentagon's own rollout confirms the analysis: different dates, different mechanisms, different services. That is what a posture looks like when the posture is the substance.

All four of the constraints Doctorow names in his accounting of how platforms die — competition, regulation, self-help, and labor — are switched off here. The competition argument fails because there are two mobile operating systems in the world and neither has an interest in mandatory MAID suppression: their entire advertising business depends on the identifier being on by default. The regulation argument fails because the Federal Trade Commission has spent fifteen years writing letters about this and has produced no rule of the kind that would force disclosure at the broker level. The self-help argument fails because Section 1201 of the Digital Millennium Copyright Act makes the act of bypassing an access control a federal civil violation — and a criminal felony when done for commercial advantage or private financial gain — which is to say the same statute that prohibits the user from auditing the SDKs in their own phones also prohibits a researcher from publishing what they find. The labor argument fails because ad-tech workers, by 2026, do not generally work at firms with organized bargaining and have no mechanism by which to refuse to ship the SDK. The Pentagon has switched off a fifth thing — a device setting on a million government phones — and called it a fix. The fix that fixes the wire looks different.

It looks like a federal privacy statute with a private right of action, which would let individuals (and not only the captured regulator) sue the brokers. It looks like an FCC rule under Section 222 of the Communications Act requiring operating-system-level MAID suppression on every device sold in the United States, which would extend the Pentagon's settings-flip from a million government phones to the more than two hundred and fifty million civilian phones whose owners share the same coffee shops and the same cell towers as the troops do. It looks like a Federal Trade Commission rule, under the rulemaking authority the agency has been flexing since 2024, that puts the disclosure burden on the brokers themselves, who would have to publish, on a public register, every entity to whom they had sold location data in the previous quarter. The substantive offence is straightforward: precise location is not a commodity to be resold; the trade in it should be a statutory offence, not a request the industry occasionally honors. None of this requires a sixty-vote Senate majority. It requires a regulatory apparatus that has decided to do its job. And when the public comment docket opens at the Federal Trade Commission on the broker-disclosure rule, the deadline, as always, is the part of regulatory process the regulated actually respect.

My father's rule on the bar mill was that a machine you cannot shut down is a machine nobody actually owns. The Pentagon's IT office just found the switch. The rest of us are still told the machine cannot be switched off, because the tracking pays for the web. It pays for the ad networks' margins. It never paid for you.

## Sources

### src_001 — The Guardian, national_daily, Tier 2, originating
**Publication date:** 2026-09-04
**Title:** US military disables ad trackers on troops’ phones amid security fears
**URL:** https://www.theguardian.com/us-news/2026/sep/04/military-disables-phone-ad-trackers
