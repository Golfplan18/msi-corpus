---
headline: America Wired Its Drinking Water to the Internet and Funded No Locks
publish_date: '2026-08-05'
lede: American water utilities left drinking water open to remote takeover.
pen_name: stewart-letterkenski
primary_entities:
- Minnesota
- Michigan
- New Jersey
- Federal Bureau of Investigation
- Environmental Protection Agency
- Cybersecurity and Infrastructure Security Agency
- Rockwell Automation
primary_themes:
- cybersecurity
- critical infrastructure
- water systems
topic_tags:
- crime
storyline_nexus: []
geographic_location: United States
floor_values_engaged:
- value: accountability_of_power
  intensity: 0.9
- value: informed_citizenship
  intensity: 0.6
framework_version: 1.1.0
generation_timestamp: '2026-08-05T23:38:39-07:00'
source_cluster_id: cluster_upi_2026-08-05_es-2026-08-05-how-hackers-attack-municip
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_disclosure: This article was generated algorithmically by Main Street Independent from the public sources listed in its Sources section.
ai_generated: true
sources:
  count: 1
  outlets:
  - United Press International
  outlet_classes:
  - wire
  highest_reliability_tier: 2
  has_originating: true
  has_primary_document: false
figures_aggregate:
  count: 0
  series_ids: []
  sources: []
cross_article_links:
- slug: 2026-08-05-hackers-attempted-to-breach-at-least-30-minnesota-water-systems
  relation: extends
  strength: 0.1871
  confidence: high
draft: false
---

American water utilities left drinking water open to remote takeover.

No water was harmed, in the narrow sense that matters, and utility officials spent the week saying so. The water stayed safe to drink. The trouble is that operators kept it safe the only way the budget ever provided for: they shut down the control computers, sent personnel into the field, and operated the equipment manually.

That is the good news. The bad news is that manual operation was the emergency plan because the normal plan had been left connected to the public internet.

At least 30 municipal water systems in Minnesota were targeted on July 26–27, and Michigan, New Jersey, and several other states have since reported similar attacks. The word “at least” is doing honest work here. The number is whatever has been noticed so far, and the count is kept by the understaffed.

To be fair — and the phrase is doing its work this time — the attackers never went near the office computers where utility staff read email and prepare reports. They went after programmable logic controllers, or PLCs: small industrial computers sitting inside pumps, valves, alarms, and treatment equipment. A PLC is not mysterious. It is closer to a thermostat with a job that matters more. It reads conditions, applies instructions, and tells machinery what to do.

The July 30 FBI and Environmental Protection Agency advisory reported that attackers remotely accessed Rockwell Automation MicroLogix controllers connected directly to the internet, then changed their IP addresses and passwords. That is not an exotic attack against an unknowable machine. It is a remote takeover of an exposed control endpoint — the digital equivalent of someone finding your back door unlocked, changing the lock, and renumbering the house.

The precedent was already documented. In 2023, federal officials reported Iranian-linked hackers targeting internet-connected Unitronics PLCs at water utilities. CISA found that some operators were still using the manufacturer’s default password. CISA has documented default credentials on other internet-connected water systems as well. NIST has warned that an intruder may replace legitimate industrial-control instructions with malicious commands.

Sophisticated malware is optional when the door is already open.

The usual public image of “the water system” is a fortified command centre, a wall of screens, and somebody in a jacket marked SECURITY. The actual system is distributed across treatment plants, storage tanks, pumping stations, and miles of pipe. The small computer at the edge may be old, poorly configured, directly reachable, and maintained by a utility with two employees, a large service area, and no spare cybersecurity team.

The system is only as secure as the least-protected controller that can issue a command.

That is the engineering substance behind the [recent attacks on water systems in Michigan and Minnesota](/articles/2026-08-01-cyberattacks-hit-water-systems-in-michigan-and-minnesota/). It is also why the language of “critical infrastructure” is not enough. Calling something critical does not secure it. A label is not a firewall.

An attacker searches internet addresses for exposed controllers, operator dashboards, and remote-access services. The attacker tries a default or stolen password, exploits an unpatched flaw, or uses a badly configured service. Once inside, the attacker can change credentials, issue commands, or attempt to replace legitimate control instructions with malicious ones.

The sophistication was never the constraint. The constraint was supposed to be an operations budget, and nobody ever appropriated one.

The industry’s defence of remote access writes itself: one employee, a hundred square miles, a vendor who will not drive three hours. All true. None of it requires the architecture to be left open to anyone holding a password.

The trouble is that convenience has been allowed to become architecture. A connection intended to let a vendor inspect a machine becomes a path into the machine. A dashboard intended to help an operator becomes an exposed control surface. A password intended to be temporary survives for years because changing it might interrupt operations.

Cory Doctorow has spent a career describing how this kind of decay becomes structural rather than incidental. The forces that used to make a system behave — competition, regulation, self-help and interoperability, labour power — get removed one at a time. What looks like carelessness afterward is the predictable residue of what the removing was for.

A controller shipped with a default password is not merely a defect a careless employee introduced. It is the shipping configuration of an industry that put its equipment on the network, the regulatory posture that answered with advisories, and the appropriations process that answered with nothing, all agreeing without ever meeting that the operator in the field would be the last line of defence.

The operator did the professional thing. The computer was shut down. Someone went outside to the pumps and ran the equipment by hand.

That response is a credit to the people who knew how the plant worked. It is not a defence of the architecture that made their intervention necessary.

This is where Larry Lessig’s framework of the four modalities — law, norms, market, and architecture — remains useful, even in a water plant rather than a social-media platform. Security depends on architecture: vendor-shipped, internet-facing PLCs with weak defaults. It depends on law: no enforceable federal security baseline for small water utilities. It depends on administration: one-person operations stretched across dozens of remote sites. And it depends on norms: operators who lack the authority to refuse an unsafe remote setup because the vendor’s contract and the utility’s schedule say otherwise.

Remove any one of those constraints and the system does not become neutral. It becomes available to whoever is willing to use the opening.

A millwright’s question is useful here: what happens when the powered control fails?

If the answer is that somebody who understands the machinery can still operate it safely, the system has resilience. If the answer is that the machine is inaccessible until the vendor restores the account, the system has been designed around dependency.

Water utilities need straightforward changes. Controllers and human-machine interfaces should not be directly reachable from the public internet. Operational networks should be separated from office networks. Remote access should pass through properly configured gateways or virtual private networks, use multifactor authentication, and grant each user only the access required for the job. Default passwords should be changed. Unused remote-access services should be disabled. Controller programs should be backed up, remote activity logged, and manual operation practised rather than rediscovered during an incident.

Those measures are not a substitute for money. They are what money is supposed to purchase.

The agencies’ own guidance keeps moving toward measures that cost money, which is why the usual remedy — issue a thicker advisory — is inadequate. Small systems should be placed on shared, professionally operated security services, the way utilities already pay for chlorination and laboratory testing. Infrastructure grants should fund network separation and secure remote access. Manufacturers and integrators should be required to document supported security features, patch obligations, credential management, recovery procedures, and safe local operation for the full service life of industrial equipment. A default password should be a violation, not a best-practice suggestion.

The United States has about 152,000 public drinking-water systems. Many are small, rural, and operating with limited staff. Telling those utilities to behave like well-funded technology companies is a way of transferring responsibility without transferring capacity. A rural water operator cannot hire a full security team because a federal advisory used the phrase “properly configured firewall.”

The federal government should fund shared cybersecurity services for small utilities, provide technical assistance that does not depend on a vendor selling the equipment, and attach enforceable security requirements to infrastructure grants. Open standards for monitoring and control, portable configuration backups, independent auditing, and right-to-repair protections would make it easier for utilities to change vendors without losing the ability to understand or operate their own machinery.

The remedy is not to make every operator an expert in every layer of the stack. It is to stop treating each municipality as an isolated customer responsible for defending an industry-wide exposure. Water is a public necessity, and its security baseline should be a public function.

There is a wicked-problem element here. Old controllers remain in service because replacement costs money and interrupting operations carries risk. Remote access remains because staff are scarce and the territory is large. Vendors, utilities, regulators, and governments each control part of the system, while no single actor bears the entire cost of failure.

That complexity is real. It is not an alibi.

The public pays for the water, the pipes, the treatment plant, the emergency response, and the consequences when a system fails. It should not also have to pay for a private infrastructure model in which the password is “admin” and the repair manual is a subscription.

The water stayed safe this time. It stayed safe because somebody left the office, walked out to the pump, and turned the valve by hand.

That is the oldest security measure on the continent, and apparently the only one the richest country on it has ever actually paid for. “The operator will go outside” is not a security architecture.

It is a weather report.

The water stayed safe this time. The passwords did not.

## Sources

### src_001 — United Press International, wire, Tier 2, originating
**Publication date:** 2026-08-05
**Title:** How hackers attack city water systems -- and why they're vulnerable
**URL:** https://www.upi.com/Voices/2026/08/05/how-hackers-attack-municipal-water-systems/6031785951167/
