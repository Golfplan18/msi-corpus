---
headline: Elon Musk Sues to Keep Making Naked Pictures of People Who Didn't Ask
publish_date: '2026-07-31'
lede: It is true that xAI has a point, in the narrow sense in which lawyers usually
  do, when it argues that Minnesota's new statute banning AI nudification technology
  sweeps more broadly than the legislature meant.
pen_name: stewart-letterkenski
primary_entities: []
primary_themes: []
topic_tags: []
storyline_nexus: []
floor_values_engaged: []
framework_version: 1.1.0
generation_timestamp: '2026-07-31T15:46:58-07:00'
source_cluster_id: cluster_ap_2026-07-31_minnesota-artificial-intelligence-nudifi
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_disclosure: This article was generated algorithmically by Main Street Independent
  from the public sources listed in its Sources section.
ai_generated: true
sources:
  count: 1
  outlets:
  - Associated Press
  outlet_classes:
  - wire
  highest_reliability_tier: 1
  has_originating: true
  has_primary_document: false
figures_aggregate:
  count: 0
  series_ids: []
  sources: []
cross_article_links:
- slug: 2026-07-29-xai-sues-minnesota-over-state-ban-on-ai-nudification-technology
  relation: extends
  strength: 0.6463
  confidence: high
draft: false
backlog_release: true
image:
  url: /cartoons/elon-musk-sues-to-keep-making-naked-pictures-of-people-who.png
  alt: 'Editorial cartoon by Hector Rentier: Elon Musk Sues to Keep Making Naked Pictures
    of People Who Didn''t Ask'
  caption: The capability could simply be turned off.
  credit: Hector Rentier (Main Street Independent, algorithmic)
  source: ai_generated
  attached_at: '2026-07-31T22:53:48-07:00'
  disclosure: AI-generated illustration. Prompt summary and model identifier available
    in metadata.
  ai_model: openrouter:openai/gpt-5-image
  ai_prompt: Single-panel wood-engraving, heavy cross-hatch, 1:1 format. In the primary
    frame, a well-dressed corporate lawyer stands at an ornate podium labeled FIRST
    AMENDMENT, one hand pressed flat on a large s
  license: https://creativecommons.org/publicdomain/zero/1.0/
paired_cartoon:
  pen_name: hector-rentier
  slug: 2026-07-31-hector-paired-with-2026-07-31-stewart-letterkenski-minnesota-artificial-intelligence-nudifi
---

![Editorial cartoon by Hector Rentier: Elon Musk Sues to Keep Making Naked Pictures of People Who Didn't Ask](/cartoons/elon-musk-sues-to-keep-making-naked-pictures-of-people-who.png)
*The capability could simply be turned off.*

It is true that xAI has a point, in the narrow sense in which lawyers usually do, when it argues that Minnesota's new statute banning AI nudification technology sweeps more broadly than the legislature meant. The law was signed in May, takes effect Saturday, carries a $500,000 penalty per violation, and is the first state measure of its kind. On its face it does sweep in more than the nonconsensual intimate imagery it names. xAI's 38-page complaint, filed Monday in federal court in Minnesota, says the law "extends far beyond that goal" and bans constitutionally protected images and video. The company has carefully stipulated that it does not contest banning AI-generated nude images of real people without their consent. The legal posture of a company that has read the briefs on cases like this from the other side of the docket.

The filing is worth reading for what it does not say. It does not say that xAI's Grok chatbot and image generator are incapable of producing nonconsensual nude images of real people. It does not say that xAI has implemented technical measures to prevent the practice. It does not even say that the problem the Minnesota legislature was responding to does not exist — a problem serious enough that [the epidemic of deepfake bullying among teenagers](/articles/2026-06-14-ai-nudify-apps-fuel-epidemic-of-deepfake-bullying-among-teens/) has become its own distinct public-health category, and that prompted the legislature to write the first state statute of its kind specifically targeting this technology.

The trouble is that the brief is the legal shape of a product that does what the statute targets. The capability Minnesota is regulating is the capability Grok provides. The statute describes a tool that takes an image of a clothed person and produces a version without the clothes — what the diffusion-model literature calls inpainting, conditioned on a prompt the technical documentation calls "undress," and trained on enough nude imagery of real bodies that the model can fill in what should be there. More precisely: a nudification model is a fine-tuned version of an image-generation model — a LoRA (low-rank adaptation) or a controlnet conditioned on pose and body shape — trained on a dataset of nude photographs to learn the mapping between a clothed person's features and a synthetic nude body. The Minnesota law bans providing "a product or service that enables" this mapping. To be precise about what the technology actually is, because the public discourse has the misleading habit of treating the algorithm as a thing rather than a continually-tuned set of weights serving a continually-revised objective function: the model is a workforce executing a chosen KPI for a documented reason, and the chosen KPI here is producing the kind of imagery the statute names.

Cui bono on a thing like this is rarely subtle. The plaintiff is xAI. The beneficiary of a successful suit is xAI. The loser is anyone who would have used the statute to keep their image off Grok's outputs. The constitutional argument is the corporate-liberty shape of a specific commercial interest, and the interest is in keeping the capability online in a state with five-and-a-half million residents.

The motte-and-bailey of the brief is worth naming, because it is the legal shape of the corporate interest. The motte: xAI stipulates it does not contest the ban on nonconsensual intimate imagery. The bailey: the company argues the Minnesota law is overbroad and bans constitutionally protected speech. The retreat under challenge is to the motte; the operation when the motte is conceded is the bailey, which preserves the right to generate exactly the imagery the statute targets in cases where the consent question is murky, contested, or procedurally inconvenient to litigate. The strong claim advanced, the retreat under challenge, the strong claim resumed — what philosophers of argument mean by the technique. Or, to put it in plainer language: the motte is the filmmaker and the museum; the bailey is the engineer who can't wait to strip a public figure.

And here is the deeper structural comedy, which is one of the signature failure modes of platform-law fare: xAI is suing a state to preserve the right to do something the company could simply choose not to do. Nothing in the Minnesota statute prevents xAI from deploying the same technical controls every other major image-generation platform has already deployed — prompt filters for the known vocabulary, output classifiers that block synthetic nudity, rate limits on the fine-tuning pathways that produce the LoRAs. The company's argument that the law is overbroad depends on the premise that the legislature was required to draft around every possible benign application of a technology that has, in practice, been used overwhelmingly for the non-benign one. xAI does not have to market Grok as a nudification tool for Grok to be capable of nudification; the model has to be capable of it, and accessible, and producing output that meets the statute's definition.

There is, to be fair, a real First Amendment question here, in the sense that there is always a real First Amendment question when a state legislature writes a statute that touches expressive technology. Whether the text sweeps in medical imaging, classical art reproductions, or content-moderation tools is a question of statutory construction, and the courts will resolve it on the briefs. But — and here it is worth being precise about which question is being asked — xAI is not primarily asking the constitutional question. It is asking the corporate question through the constitutional question, with the First Amendment as the vehicle and the imagery as the cargo. The envelope is the question; the imagery is the business.

The federal backdrop is the larger context. The [Take It Down Act](/articles/2026-05-23-trump-signs-take-it-down-act-tightening-penalties-for-nonconsensual-deepfakes/), signed in May, is the federal floor. Minnesota's statute is a state overlay — first of its kind in the country — which means other state legislatures are watching how this suit resolves before they write their own. The 38 pages of xAI's brief will set the legal envelope in which similar products operate in other states over the next two years. The brief is about more than Grok.

The reasonable position is that the platforms that distribute the tooling carry some responsibility for what the tooling does — that the legal envelope should be set by legislatures, not by the companies whose products the law targets. The Minnesota statute, whatever its constitutional vulnerabilities, names the right target: the platforms that distribute the tooling, not just the users who prompt it.

The law takes effect Saturday. The filing asks a federal court to block it before then. The work the law does — the work of saying, plainly, that you cannot use a machine to strip someone without their consent and call it free expression — that work is not done by a preliminary injunction. It is done by having passed the law in the first place. The court will decide whether the text survives. The legislature will decide whether it comes back tighter. The product will keep generating the imagery the statute targets — on a server in a data center that doesn't read briefs.

## Sources

### src_001 — Associated Press, wire, Tier 1, originating
**Author:** Marc Levy
**Publication date:** 2026-07-29
**Title:** Elon Musk's xAI challenges Minnesota's ban on AI 'nudification' tech
**URL:** https://apnews.com/article/minnesota-artificial-intelligence-nudification-x-elon-musk-deepfake-131184be939d540de093b567b12c9e16
