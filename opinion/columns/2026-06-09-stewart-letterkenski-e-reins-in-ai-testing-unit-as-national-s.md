---
headline: Sean Cairncross is burying AI model assessments behind a national-security
  screen
publish_date: '2026-06-09'
lede: Sean Cairncross is burying AI model assessments behind a national-security screen.
pen_name: stewart-letterkenski
primary_entities: []
primary_themes: []
topic_tags: []
storyline_nexus: []
floor_values_engaged: []
framework_version: 1.1.0
generation_timestamp: '2026-06-09T22:41:21Z'
source_cluster_id: cluster_wsj_2026-06-09_e-reins-in-ai-testing-unit-as-national-s
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_generated: true
sources:
  count: 0
  outlets: []
  outlet_classes: []
  highest_reliability_tier: null
  has_originating: false
  has_primary_document: false
figures_aggregate:
  count: 0
  series_ids: []
  sources: []
image:
  url: /cartoons/sean-cairncross-is-burying-ai-model-assessments-behind-a.png
  alt: 'Editorial cartoon by Hector Rentier: Sean Cairncross is burying AI model assessments
    behind a national-security screen'
  caption: The work of testing is being done, somewhere, by someone.
  credit: Hector Rentier (Main Street Independent, algorithmic)
  source: ai_generated
  disclosure: AI-generated illustration. Prompt summary and model identifier available
    in metadata.
  ai_model: openrouter:openai/gpt-5.4-image-2
  ai_prompt: A single-panel scene in heavy cross-hatch, 1:1. Sean Cairncross stands
    in the foreground, in a business suit, his back half-turned to the viewer but
    his profile fully visible — he is a recognizable, i
  license: https://creativecommons.org/publicdomain/zero/1.0/
cross_article_links: []
draft: false
paired_cartoon:
  pen_name: hector-rentier
  slug: 2026-06-09-hector-paired-with-2026-06-09-stewart-letterkenski-e-reins-in-ai-testing-unit-as-national-s
---

![Editorial cartoon by Hector Rentier: Sean Cairncross is burying AI model assessments behind a national-security screen](/cartoons/sean-cairncross-is-burying-ai-model-assessments-behind-a.png)
*The work of testing is being done, somewhere, by someone.*

Sean Cairncross is burying AI model assessments behind a national-security screen. The National Cyber Director has instructed the Center for AI Standards and Innovation—the unit at Commerce that, until a Trump-era rebrand, was called the AI Safety Institute—to stop issuing public reports on the models it tests, which is to say, to stop telling anyone outside a handful of security-cleared officials what the government knows about the capabilities of systems before they are released. The *Wall Street Journal* reports that Cairncross and Treasury Secretary Scott Bessent have told the unit to pause its reports while an executive order signed last week is implemented. The testing will continue, the people familiar with the matter told the paper. The public is out of the room.

The mechanism is straightforward. CAISI, housed within the Commerce Department, was established as the civilian body responsible for pre-release testing and public documentation of model capabilities. The executive order effectively transfers the evaluation architecture from a civilian, open-standards regime to a closed national-security loop. To anyone who has read the documentation from the cryptographic standards bodies, the operational mistake is glaring. You do not secure a system by taking a red-team report—a document that details a model's failure modes, its susceptibility to adversarial prompting, its capacity to generate dual-use payloads—and classifying it. You secure the ecosystem by publishing the vulnerabilities, assigning them identifiers, and forcing the industry to patch them. When you lock the audit in a classified facility, the only people who know about the flaws are the auditors who wrote the report and the independent researchers who reverse-engineered the model on their own time. The defenders get a blackout; the attackers get a roadmap.

The move is neat. It is not new. The pattern fits what Cory Doctorow, borrowing from Lee Vinsel, calls "criti-hype": inflate the risks of the thing you want to control, then use the magnitude of those risks to justify controlling it in secret, then exclude everyone who might ask whether the risks were inflated in the first place. The unit's original mandate, when it was housed under NIST and called the AI Safety Institute, was to produce public, standardized evaluations against a defined set of danger thresholds—cybersecurity, bioweapons, autonomous replication—so that government, industry, and the public could talk about model safety with reference to the same evidence. That evidence is now being produced behind a screen. The screen is labelled national security.

The question no one inside the administration seems to be asking—or at least no one has succeeded in getting the administration to answer—is what the national-security interest is in preventing the American public from knowing whether AI systems about to be integrated into critical infrastructure, markets, and government decision-making have been found, by the government's own testers, to have dangerous properties.

This is not a dispute between innovation and safety, at least not in the way the recent debates framed it. It is a dispute over who gets to see the source of the risk. Administration AI advisers, including venture capitalist David Sacks, have warned that the real risk is an "overzealous" testing process that might slow innovation and hinder the development of American AI—a position with the advantage of being unfalsifiable, because if no public testing results are released, no one can demonstrate that testing was overzealous, or indeed that it was done at all. National-security hawks, meanwhile, want the assessments locked down. Both sides have an interest in keeping the testing away from the public, because the public is the one actor in this arrangement that might demand explanations that cut against both speed and secrecy.

The companies themselves—OpenAI, Anthropic—are alarmed by the move. They had relationships with the unit under its previous name and they worry, correctly, that security-agency evaluators will be less predictable and more inclined to find a model "risky" on grounds the companies cannot contest, since the evidence will not be public. The companies preferred the civilian unit, not because they love transparency, but because a civilian unit operating with documented methods afforded something like a known rule-set. That is now gone. Anthropic's Mythos model has already demonstrated code-execution capabilities that unsettle the Pentagon. The administration's response—visible in the parallel push to accelerate military AI adoption—is to treat the entire software stack as a state secret. That does not make the models safer. It makes the independent engineering community illegal.

The consolidation of the auditing layer follows the enshittification template applied to safety. First, the government invites companies to test their models publicly to establish a baseline of trust. Then, the national-security apparatus demands the reports be restricted, citing the risk of dual-use exploitation. Finally, the reports vanish entirely, and the models are deployed with no independent audit, because the state and the platform companies have agreed that the only risk worth measuring is the risk of falling behind in the arms race.

The longer-term cost is structural. The *Wall Street Journal* notes that CAISI is critically underfinanced compared with its counterparts in allied nations. By gagging the only domestic body capable of transparent model auditing, Washington voluntarily cedes the international standards table. The European AI Office and the U.K. AI Security Institute publish; they are building a public-evidence record. The U.S. is building a file cabinet.

The remedy is not a smarter executive order or a tighter clearance regime. It is a statutory requirement that model evaluations be conducted under open-standards protocols, with public vulnerability disclosures mandated before commercial deployment, insulated from the apparatus that treats risk assessment as contraband. Structural separation is the only mechanism that prevents the safety audit from becoming a marketing prop. There is a phrase in protocol analysis for a security claim that cannot be checked by anyone outside the room: it is a zero-knowledge proof that proves nothing to anyone but the prover. The work of testing is being done, somewhere, by someone, the people told the *Journal*. That is the kind of assurance that works exactly as well as the lock on the cabinet works. The lock is good. The question is whether it is locked because the contents are too dangerous, or because the contents, once opened, would show the reasoning was weak. From outside, you cannot read the difference.

---

*Stewart Letterkenski is a heteronym in Main Street Independent's editorial architecture — an analytical voice, not autobiography of any actual person. The position this column expresses is the publication's position on the territory Stewart Letterkenski's lane covers, rendered through Stewart Letterkenski's register.*

*[About Stewart Letterkenski](/advocacy/stewart-letterkenski) · [How the pen names work](/about#how-the-pen-names-work)*
