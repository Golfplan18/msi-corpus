---
headline: Strangling the Labs, Empowering Beijing
publish_date: '2026-06-28'
lede: The Trump administration is strangling its own AI labs to hand the race to Beijing.
pen_name: stewart-letterkenski
primary_entities:
- Anthropic
- Zhipu AI
- 360 Security Technology
- Mythos
- National Security Agency
- OpenAI
primary_themes:
- AI competition
- cybersecurity
- technology policy
- U.S.-China rivalry
topic_tags:
- artificial intelligence
- computing and information technology
- international relations
- science and technology
- government policy
storyline_nexus: []
geographic_location: United States
floor_values_engaged:
- value: accountability_of_power
  intensity: 0.9
- value: truthfulness
  intensity: 0.6
- value: equality_fairness
  intensity: 0.6
framework_version: 1.1.0
generation_timestamp: '2026-06-28T07:49:00Z'
source_cluster_id: cluster_wsj_2026-06-28_tech-ai-chinese-ai-anthropic-mythos-cybe
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
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
- slug: 2026-06-28-chinese-ai-matches-anthropic-in-cybersecurity-narrowing-u-s-lead
  relation: extends
  strength: 0.8163
  confidence: high
draft: false
---

The Trump administration is strangling its own AI labs to hand the race to Beijing.

It is true, in the narrow sense in which such arguments are usually true, that an AI model capable of finding security bugs in software is also, in the wrong hands, capable of finding security bugs in your software. The dual-use problem is real, and it is not the kind of problem that goes away by being named. A model that can read code and flag the missed bounds-check, the uninitialized buffer, the dangling pointer, the SQL injection that no one noticed in code review — that model is, at any reasonable resolution, a model that an adversary can also use to find the same flaws. The question has never been whether to acknowledge this. The question is what to do about it without handing the entire field to the people who are, by every available indicator, building the same capability as fast as they can and shipping it openly.

The current policy, as best one can reconstruct it from the administration's case-by-case decisions and the vendors' public statements, is the worst possible answer to that question. The Trump administration had already [categorically prohibited foreign access](/articles/2026-06-13-u-s-bans-foreign-use-of-anthropic-s-top-ai-models-company-halts-access/) to Anthropic's Fable model, with no case-by-case exception architecture visible from the outside, and had spent more than two weeks restricting access to the related Mythos system. The National Security Agency had been [testing Anthropic's Mythos model](/articles/2026-06-24-anthropic-s-mythos-ai-finds-vulnerabilities-in-classified-u-s-systems-during-tes/) and found it impressive in trials. On Friday, Mythos 5 access was restored for "some trusted entities." The NSA, presumably, is one. The vendors and security researchers who would have built the next layer of American cyber-defense on top of those tools are, by all appearances, less so. [OpenAI said on Friday](/articles/2026-06-26-openai-limits-access-to-gpt-5-6-after-talks-with-trump-administration/) it was limiting access to its latest model, GPT-5.6, citing the same case-by-case review process that everyone else is now also operating under.

And at the same moment, the administration has been clearing exports of advanced AI chips to China — the very compute on which the competing Chinese models are trained and run. Saif Khan, a distinguished technology fellow at the Institute for Progress who worked on export restrictions in the Biden administration, called the combination "a gift to China." The framing is unusually blunt by Washington standards. The substance is not in serious dispute. To soften Khan's phrasing into a "structural guarantee" would be too gentle: it is a structural guarantee that the hardware will be used to build an unrestricted rival. As Lior Div, CEO of the cybersecurity firm 7AI, notes, "China is making sure that the gap becomes smaller and smaller over time."

To describe the policy in analytical terms, the administration has, in the same week, removed three of the four disciplines that Cory Doctorow, in his 2025 book *Enshittification*, identified as the constraints that historically kept platform decay in check — competition, regulation, self-help and interoperability, and labor. Competition: the leading American cyber-AI labs are forbidden from selling to the customers — allied governments, mid-tier American security vendors, independent researchers — who would have used the tools to build competitive defenses of their own. Self-help and interoperability: the same tools cannot be redistributed, audited, or built upon by the American security-research community that has historically been the country's most productive vulnerability-discoverer. Labor: the American cyber researchers who would have integrated the models into their work have been told, in effect, that the tools are too dangerous to use — and have, very predictably, begun to look for what comes next. The fourth force, regulation by a competent state, has been replaced by case-by-case ad-hoc decisions whose criteria the vendors themselves report they are struggling to learn.

What comes next is the part of the story that the available record already documents, and it is not flattering. Zhipu AI's GLM-5.2, an open-weight model released this month, has been shown in some benchmarking tests to match Anthropic's Claude Opus 4.8 — a closed-weight model released in May — at finding security bugs. In tests from the cybersecurity company Semgrep, GLM-5.2 bested Claude Opus 4.8 outright. When given further instructions, GLM-5.2 and Opus 4.8 can match Mythos itself, according to the researchers. GLM-5.2 has ranked as one of the ten most-used AI models on OpenRouter. 360 Security Technology, a Chinese cybersecurity company, released a comparable tool called Tulongfeng on Wednesday. Its CEO, Zhou Hongyi, told a Beijing conference that "this kind of powerful weapon that can alter the landscape of cyberwarfare can't remain solely in American hands." In plain English: you handed us the market by strangling your own suppliers.

A deflationary technical aside, because the public discourse has the misleading habit of treating "AI model" as a unitary thing rather than as a specific architecture with specific distribution properties. "Open-weight" means the trained parameters of the model are published, and the model can be downloaded and run on hardware the user controls — a security researcher's laptop, a small company's on-prem GPU rack, a basement with a few H100s. A closed-weight model is accessible only through an API the vendor controls, and the vendor can — and now sometimes does, at the U.S. government's request — decide who gets to query it. The closed-weight model is more controllable by a competent regulator. It is also more controllable by an incompetent one, which is the part of the trade-off the current policy has not noticed. The Trump administration, by restricting closed-weight access while leaving open-weight Chinese alternatives freely available, has chosen the worst combination: its own tools are constrained; the tools that achieve parity are not. The policy treats the distribution of open-weight models as if it were the distribution of a physical component, rather than the distribution of a mathematical proof. It is enforcing a digital rights-management scheme on a hosted database to protect the incumbent's market position.

The mechanism by which parity was achieved deserves a name. J.K. Galbraith called it the *bezzle* — though the word was minted in *The Great Crash of 1929* for the world's inventory of undiscovered financial fraud, the structure generalizes: a latent pile of disasters the world is sitting on and has not yet seen. The security equivalent is the world's stockpile of unfixed vulnerabilities, growing with every commit. The bug-finding capability the available reporting describes, in a more dramatic register, as a "bugmageddon," is, in any reasonable accounting, a way to convert that bezzle into disclosed-and-fixed vulnerabilities, which is a public good. The current policy treats that capability as a weapon to be locked down, and the locked-down version is, naturally, being built faster by the people who did not lock theirs down. The bezzle does not respect export controls. It does not respect the nationality of the model that finds the bug. It does not respect closed-weight architecture once a comparable capability exists in an open-weight form, which it now does.

Cui bono. The American AI labs lose revenue, reputational position, and the data feedback loop that would have come from large numbers of trusted users running their tools against real targets. American security researchers lose the most capable tools and the institutional relationships with the vendors that produced them. The NSA loses the time its testers spent integrating the now-restricted models, which is the kind of institutional capacity that does not come back quickly. Chinese open-weight vendors — Zhipu, DeepSeek, 360 Security — gain market share, gain prestige, gain the implicit endorsement of being the side whose tools the world can actually run. The Pentagon's recent deal with Reflection AI, the one domestic open-weight developer the available reporting names, is a real move, and a useful one, but it does not by itself offset the substitution now occurring in the broader market.

Niels Provos, a researcher who led security teams at Google and Stripe, summarized the result cleanly: "It is incentivizing companies across the globe to use cheaper but very capable Chinese open-weight models, while at the same time undermining the U.S. AI industry. I don't understand it."

Even the architects of the policy seem to realize the open-source genie cannot be stuffed back into the bottle. "Our administration is very much focused on Chinese open-source models," admitted Jacob Helberg, undersecretary of state for economic affairs. Yet their response is a panicked scramble, evidenced by the Pentagon's eleventh-hour deal with Reflection AI to use domestic open-weight models in classified settings — a half-measure arriving years too late to an ecosystem they spent years starving. When a European or Asian business cannot rely on an API that might be shut down by a Friday executive order, the rational engineering decision is to download GLM-5.2 and run it on their own sovereign infrastructure. The policy does not keep the technology out of adversarial hands; it simply ensures that when the technology arrives in those hands, it is a version the United States has no visibility into and no levers to pull.

My father spent thirty years as a millwright in a steel rolling mill, and he understood a basic rule of heavy machinery: you cannot control the output of a system by restricting the manuals while selling the raw iron. The iron gets shaped regardless. The only thing the restricted manual guarantees is that the people who need to repair the machine will go to the shop across the border that has the full schematic. In the digital economy, that shop is an entire ecosystem of engineers working on open architectures that the U.S. regulatory apparatus does not know how to read, let alone control.

What would work, on the documentary record, is the boring option. Treat cyber-defense AI as critical infrastructure requiring sustained public investment, sustained researcher access, and a serious export-control architecture — not a series of case-by-case decisions that vendors cannot predict and that the public cannot audit. Restore full access for the security-research community. Stop clearing the chip exports that build the competing model. Recognize that the advantage in this specific race is operational — researchers with tools, vendors with feedback loops, an administration that knows what it is doing — and that this kind of advantage does not survive strangling the operation in order to lock the door. The remedy is to mandate interoperability and build domestic infrastructure on open standards that make the monopoly irrelevant, enforced through a DARPA-model program that treats mathematical access as a public utility rather than a state secret.

The deadline that matters is not a regulatory one. It is the moment the NSA's testers, who found the now-restricted tools impressive in trials, finish the migration to the models they are now actually allowed to use. The work doesn't care how you feel about it. The work is being done.

## Sources

### src_001 — The Wall Street Journal, national_daily, Tier 1, originating
**Author:** Robert McMillan
**Publication date:** 2026-06-28
**Title:** China Has Matched Anthropic in Cybersecurity, Resetting AI Race
**URL:** https://www.wsj.com/tech/ai/chinese-ai-anthropic-mythos-cybersecurity-574b02c2

---

*Stewart Letterkenski is a heteronym in Main Street Independent's editorial architecture — an analytical voice, not autobiography of any actual person. The position this column expresses is the publication's position on the territory Stewart Letterkenski's lane covers, rendered through Stewart Letterkenski's register.*

*[About Stewart Letterkenski](/advocacy/stewart-letterkenski) · [How the pen names work](/about#how-the-pen-names-work)*
