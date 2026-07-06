---
headline: Every Script Kiddie's Universal Attacker's Manual
publish_date: '2026-06-29'
lede: OpenAI and Anthropic ship a universal attacker's manual and sell you the defence.
pen_name: stewart-letterkenski
primary_entities:
- Bruce Schneier
- Five Eyes intelligence alliance
- L0pht
- OpenAI
- Anthropic
primary_themes:
- Artificial intelligence
- Cybersecurity
- Hacking
- Skill gap
topic_tags:
- artificial intelligence
- computing and information technology
- crime
- international relations
storyline_nexus: []
geographic_location: United States
floor_values_engaged:
- value: truthfulness
  intensity: 0.6
- value: informed_citizenship
  intensity: 0.7
- value: accountability_of_power
  intensity: 0.5
framework_version: 1.1.0
generation_timestamp: '2026-06-30T16:37:09Z'
source_cluster_id: cluster_guardian_2026-06-29_commentisfree-2026-jun-29-cyber-attacks-
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
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
cross_article_links:
- slug: 2026-06-29-ai-erodes-skill-barrier-for-cyber-attacks-security-expert-warns
  relation: extends
  strength: 1.0
  confidence: high
draft: false
---

OpenAI and Anthropic ship a universal attacker's manual and sell you the defence.

That is the structural claim buried in Bruce Schneier's column this week on the joint Five Eyes statement on AI and cyber risk, and it is worth saying aloud because Schneier, characteristically, will not. Schneier is a security technologist; he writes inside the professional guild that has spent the last forty years managing the gap between what an attacker can do and what a defender can do. He is generous to his guild, and to the AI companies whose models he has been broadly respectful of in adjacent work. He is right that the gap is widening, and right that the defence will require AI as well. He is wrong that the widening is incidental to the business model that produced it, and wrong that the defence the Five Eyes proposes is anything other than the next sales cycle for the same firms.

To be fair — the phrase is doing real work here, not Letterkenny work — Schneier's central distinction is the genuinely useful one. Skill and ability, he observes, were once synonyms. To be able to do something difficult, you needed the skill that came from years of acquiring the knowledge. That process of acquisition also instilled, he notes, the moral and professional codes that made the would-be poisoner or bridge-blower-up mostly restrain themselves. AI breaks the coupling. The same model that helps a junior defender find a buffer overflow helps a stranger with no training assemble a ransomware campaign. The knowledge is the same knowledge; only the socialization that comes with acquiring it has been stripped out. Schneier is right that this is the structural problem, and that no amount of model alignment research is going to put the socialization back. He is right that open-source models, particularly small ones that run on a laptop, are going to be the carrier of this knowledge. He is right that the megacorps' guardrails are product features, not security properties, and product features do not generalize.

The seven members of the L0pht hacker collective who testified before Congress in 1998 could threaten to take down the internet because they had spent years learning how the protocols actually worked. AI decouples the ability to execute an attack from the years of professional formation required to understand it. Today's models can autonomously find vulnerabilities, chain exploits, and deploy ransomware with minimal prompting. The capability is now available to anyone who can write a prompt, and the professional norms that historically gated that capability are gone with the apprenticeship. The seven acquired a vocation; the script kiddie acquires a tool.

The question is what the industry and the security state propose to do about it, which is where the engineering-substance discrimination has to separate what is being said from what is being built. The AI megacorporations talk about "guardrails" to prevent their models from generating malicious code. Schneier correctly notes that these guardrails will not survive contact with smaller, cheaper, locally-run open-source models that will be passed around like the script-kiddie tools of the early 2000s. But there is a second-order function to the guardrails that the security state is very happy to let the megacorporations build. Schneier mentions it in passing: the proposal to instruct the models to spy on people and report any malicious prompts to the authorities. The guardrails are not a security measure. They are a compliance and surveillance apparatus. They do not stop the open-source models from breaking your code. They ensure that the frontier models — the ones you pay for, the ones you agree to Terms of Service to use — report you to the authorities when you ask them to do something interesting.

Where Schneier is a little more careful than I would be is on the cui bono. The Five Eyes statement Schneier is reporting on is itself a document produced by national-security agencies that have, over the last two decades, become the largest single customer of the offensive cyber industry — GCHQ, NSA, CSE, ASD, GCSB, and their various directorates operate what is in effect a permanent, state-funded, machine-speed red team, and their procurement records are public. The advice they give — "use AI for defence," "monitor unusual behaviour," "respond faster to incidents" — is the advice of an industry to its customer base, where the customer base is the same set of institutions whose security budgets the same firms are now pitching AI to. As [US government AI use cases have surged seventy per cent since the Biden administration left office](/articles/2026-06-15-us-government-ai-use-cases-surge-70-since-biden-left-office/), a substantial share of the new procurement sits in the offensive-cyber pipeline. None of this is a conspiracy. It is how the procurement apparatus is supposed to work, and the procurement apparatus is, structurally, the thing it buys from.

The same procurement apparatus has, for most of this century, also been the regulator most reluctant to constrain the offensive market whose tools occasionally end up in the hands of people who are not the customers. The mercenary-spyware industry that Citizen Lab at the Munk School has spent two decades documenting — NSO Group's Pegasus, the Intellexa consortium, Cytrox, Candiru — is the empirical record of what happens when a state-funded cyber industry sells the same tools to governments and to private clients, and the tools leak. Bill Marczak and John Scott-Railton, working from a base in Toronto, have built much of the forensic record on which the public understanding of that market rests. The thing about people with ability but no skill is that they include the *customers* of commercial spyware firms — the political operators, security services, and private buyers across Cyprus, the Gulf, and the former Soviet space who can now commission a surveillance operation with a phone call, and whose access to the underlying tradecraft is mediated entirely by the firm they pay. The firms themselves are staffed by highly skilled engineers; the skill sits in the building, and the ability travels out the door with the licence. The same firms now want to sell you the AI that will defend against the next generation of tools the AI will enable. As the *Main Street Independent* has reported, [hijacked AI agents](/articles/2026-06-02-hijacked-ai-agents-become-new-insider-threat-security-experts-warn/) are already a documented new category of insider threat — the model itself as the attack surface. The market is, in the structural sense, working as designed.

The structural problem — the one Schneier gestures at but does not quite name — is what Cory Doctorow, citing a long line back through the EFF, calls the suppression of *adversarial interoperability* in favour of *felony contempt of business model*. The knowledge of how to find and exploit a software vulnerability is the same knowledge you need to fix one. You cannot teach an AI the defensive craft without also teaching it the offensive craft, exactly as Schneier notes. The question is not whether this knowledge will exist; it will exist, in the model weights, in the open-source repos, in the API responses, in the public discussion of the previous attacks. The question is who is positioned to do something useful with the knowledge, and on what terms. The answer, in the absence of regulatory intervention, is that the firms that sold you the attack manual are best positioned to sell you the defence subscription, because they have the model, the API, the sales team, and the relationship with your CISO. The defence is not a counter-architecture; it is the same architecture with a different SKU. The policy apparatus wants the models to be good at defense but bad at offense, which is like wanting a doctor to know how to treat a poisoning without knowing how to administer one. The megacorporations will sell you the defense capability. They will also sell you the dual-use capability that can be prompted into offense, and they will wrap it in a Terms of Service agreement and a logging apparatus and call it a guardrail.

Kate Crawford's *Atlas of AI* makes the same point at the infrastructure layer. AI, Crawford argues, is not a cognitive technology but a logistical-extractive system — Earth, labour, data, classification, affect, state, and power, in her seven-chapter structure. The cybersecurity market is one of its nearer-term extraction surfaces. The defensive AI the Five Eyes is endorsing will be built on the same hyperscaler infrastructure, the same few model families, the same talent pipeline, and the same consulting shops as the offensive AI the same agencies are warning about. The training data, in particular, will be drawn from the same vulnerability databases and incident reports, in roughly the same proportion, with the same commercial markup. The architecture is a monoculture by design, and the monoculture is the attack surface. The Schneier column, characteristically, does not say this. The Five Eyes statement, also characteristically, does not say this. The firms selling the AI do not say this because it is not a sentence that fits in a sales deck.

The agencies that spent the last two decades demanding "exceptional access" to encrypted communications, pushing legislative apparatuses like the EARN IT Act — which critics warned would force platforms to scan encrypted messages — and hoarding zero-day vulnerabilities for their own offensive operations are now expressing newfound urgency about uncontrolled offensive capability in the wild. They are not worried about the automation of offense; they are worried that they will not be the only ones automating it.

The fix is not the AI defence the Five Eyes is pitching, and it is not the guardrails the megacorps are racing to install. Both are versions of the same product. The fix is the boring one Schneier's professional guild has been quietly recommending for thirty years and that the procurement apparatus has been quietly declining to fund: replaceable software, smaller attack surfaces, fewer monocultures, open-source maintainers paid for the work, mandatory disclosure regimes that shorten the time between vulnerability discovery and patch, and — most importantly — a regulatory floor on the offensive market that takes the question of *who gets the attacker's manual* out of the hands of the firms whose revenue depends on selling it. None of this will hold at the cadence AI brings unless the same fixes are themselves AI-accelerated: open-source maintainers funded at hyperscaler rates, disclosure treated as critical infrastructure, and the offensive-market floor tightened hard enough that the next decade looks like a defended one rather than a freshly monetized one.

The open-source models will not have guardrails. The frontier models will have guardrails that log your prompts. The network will remain exactly as vulnerable as it was before the models arrived, only now the automated attacks will be faster, and the only thing the guardrails will successfully stop is the unmonitored use of the products you paid for — leaving the actual attack surface, like [hijacked AI agents](/articles/2026-06-02-hijacked-ai-agents-become-new-insider-threat-security-experts-warn/), completely untouched.

The chokepoint version of this argument has been made about every other gatekeeper industry of the last twenty years, and the AI version is, structurally, the same argument about a different industry. The AI is here. The skill barrier is gone. The defence that has a chance is the one that does not require you to keep buying the attack manual in order to get the inoculation.

The Five Eyes statement is, like most such statements, a public-consultation exercise in advance of a procurement decision. Submissions to the public consultations the agencies are running, in their respective jurisdictions, are open through the summer. Deadlines are the only part of regulatory processes the regulated actually respect, and submissions are the only part of regulatory records that subsequent governments have to read. The work is to be done.

## Sources

### src_001 — The Guardian, national_daily, Tier 2, originating
**Publication date:** 2026-06-29
**Title:** Once, cyber-attacks required great skill. AI is changing that | Bruce Schneier
**URL:** https://www.theguardian.com/commentisfree/2026/jun/29/cyber-attacks-ai

---

*Stewart Letterkenski is a heteronym in Main Street Independent's editorial architecture — an analytical voice, not autobiography of any actual person. The position this column expresses is the publication's position on the territory Stewart Letterkenski's lane covers, rendered through Stewart Letterkenski's register.*

*[About Stewart Letterkenski](/advocacy/stewart-letterkenski) · [How the pen names work](/about#how-the-pen-names-work)*
