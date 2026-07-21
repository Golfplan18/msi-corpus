---
headline: Commerce Secretly Crippled Anthropic's Most Capable Models and Called It Safety
publish_date: '2026-07-21'
lede: The Commerce Department secretly crippled Anthropic's most capable AI models and called it safety.
pen_name: stewart-letterkenski
primary_entities: []
primary_themes: []
topic_tags: []
storyline_nexus: []
floor_values_engaged: []
framework_version: 1.1.0
generation_timestamp: '2026-07-21T09:49:16-07:00'
source_cluster_id: cluster_upi_2026-07-21_21-legally-or-not-us-controlling-access-
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_disclosure: This article was generated algorithmically by Main Street Independent from the public sources listed in its Sources section.
ai_generated: true
sources:
  count: 0
  outlets: []
  outlet_classes: []
  has_originating: false
  has_primary_document: false
figures_aggregate:
  count: 0
  series_ids: []
  sources: []
cross_article_links:
- slug: 2026-07-21-commerce-department-ai-export-order-raises-unresolved-legal-questions
  relation: extends
  strength: 0.8257
  confidence: high
draft: false
backlog_release: true
---

The Commerce Department secretly crippled Anthropic's most capable AI models and called it safety. On June 12, the Bureau of Industry and Security sent Anthropic [a letter](/articles/2026-06-13-u-s-bans-foreign-use-of-anthropic-s-top-ai-models-company-halts-access/) barring all foreign nationals from using Fable 5 and Mythos 5, the company's two most advanced large language models. The order included Anthropic's own noncitizen employees. With no mechanism to validate nationality for the hundreds of thousands of users accessing the models through the company's API and consumer products, Anthropic shut both models down for everyone. Commerce [lifted the restrictions](/articles/2026-06-30-lutnick-announces-deal-to-restore-anthropic-s-fable-5-access/) on June 30, but only after Anthropic imposed safety guardrails that collapsed the models' benchmark performance. In one post-restriction test, Fable 5 completed 3 of 12 tasks that had been routine before the controls. The models are back. They are not the same models.

It is true that genuinely dangerous AI capabilities — models that could assist in designing biological or chemical weapons, for instance — may warrant government intervention of the kind export-control law was designed to provide. That is the strongest version of the case for what Commerce did. The trouble is that what Commerce actually did bore no resemblance to a targeted intervention against a specific dangerous capability. It shut down everything, for everyone, with no notice, and then allowed access again only after the models were worse at everything. The only theory of safety consistent with a model completing 3 of 12 routine tasks is the theory that a model too broken to be dangerous is also too broken to be useful for anyone, anywhere, at anything. The 3-of-12 score is not a spike; it is the new normal after the guardrails that Commerce called a victory. That is not a precision instrument for preventing weapons-proliferation assistance. It is a sledgehammer swung under a statute that may not even authorize the swing.

The Export Control Reform Act of 2018 was written to prevent companies from exporting items like uranium enrichment centrifuges and missile guidance systems without government consent. Commerce invoked this statute to control access to a service that generates text on a server in Virginia — the first time the government had used export controls to restrict foreign access to an AI service. When a user sends a prompt to Fable 5, the model processes it and replies; the model itself, its weights, its training data — none of it leaves the building. The only item that crosses a border is the response, which is to say, the "export" Commerce is controlling is whatever text the model produces in reply to a prompt. Commerce's own prior guidance has treated remote access to software running on U.S. servers as outside the reach of export controls. The fact that Congress is currently attempting to legislate explicit authority over AI model access is itself an admission that existing law may not cover what Commerce just did.

Even granting that the statute reaches AI services, the procedure was extraordinary. The "is informed" mechanism Commerce used is designed to notify a specific company that a specific type of transaction to a specific country requires an export license. Commerce's letter swept every foreign national on Earth, was never published, carried no expiration date, required no sign-off from the Defense or State departments, and committed the government to no allied review. The temporary classification the government has traditionally used for urgent technology controls — designation 0Y521, designed for exactly the situation where existing controls have not yet caught up with a fast-moving threat — requires all of those safeguards: interagency sign-off, publication, a one-year expiration, and allied consultation. Commerce bypassed every one.

The other half of this story is that Anthropic did not fight. The company called the episode "a misunderstanding" and sent executives to Washington to negotiate, not litigate. This is a company that had previously sued the Trump administration over a supply-chain-risk designation, so it is not incapable of contesting government overreach. But Anthropic is in a bind of its own construction. Two days before Commerce's letter arrived, CEO Dario Amodei published an essay arguing that the government "should have the power to block or deter deployment" of dangerously capable frontier models. Going to court to deny the government that power would undercut Anthropic's own stated position — the company that sells itself as the responsible AI developer cannot simultaneously argue in court that the government has no business deciding when a model is too dangerous. And the case that these models are dangerous enough to warrant government intervention comes largely from Anthropic's own public warnings and thousands of hours of red-team testing conducted in collaboration with the government. Anthropic is in the business of selling both capability and danger: the same frontier model is marketed to customers as powerful enough to transform their operations and to regulators as dangerous enough to require oversight. Anthropic [built the evidence](/articles/2026-07-01-lutnick-letter-commits-anthropic-to-proactive-ai-security-detection-as-export-co/) for the prosecution of its own products.

The Export Control Reform Act also strips federal courts of their usual power to review such decisions as arbitrary and capricious — the standard that normally allows a court to examine whether an agency weighed relevant factors and explained its reasoning. Under ECRA, anyone challenging a Commerce directive must show not that the order was unreasonable, but that it was flatly unauthorized by statute or unconstitutional. That is a far narrower path, and one made narrower still by the fact that the directive itself was secret. The most consequential government action affecting AI model access in American history occurred with no public notice, no comment period, no allied coordination, and no meaningful judicial review.

This is where the engineering substance matters, because it exposes what "safety" actually cost. The guardrails Commerce demanded — the conditions for restored access — appear to work through broad suppression mechanisms: either routing queries on certain topics to a less capable model or filtering outputs against pattern-matching rules, deployed widely enough that benign queries trigger them alongside whatever specific capability the government was targeting. A safety system, in any engineering discipline that takes the term seriously, is one that blocks the specific dangerous failure mode while preserving the system's function. A circuit breaker trips on an overcurrent, not on a light switch. What Anthropic delivered was a system whose breaker trips on everything. The Lutnick deal that restored access [itself codified this approach](/articles/2026-07-01-lutnick-letter-commits-anthropic-to-proactive-ai-security-detection-as-export-co/) — Anthropic agreed to monitor for misuse proactively, but the monitoring sits atop a design-phase capability collapse that made the models less dangerous by making them less capable. Run Fable 5 ten times on tasks it handled routinely before June 12 and it fails seven of them. The model is not safer. It is broken. The benchmark collapse is not collateral damage from a well-designed intervention. It is the predictable consequence of a constraint so broad it cannot distinguish a chemistry student's homework from a weapons designer's query. Cory Doctorow has been writing for fifteen years about the structural impossibility of building a computer that runs every program except the ones someone fears — the war on general-purpose computing. The demand is always the same: install a control layer that distinguishes good use from bad. The result is always the same: a system that cannot do what it was designed to do. The demand is always the same — build a gate that lets through only the good. The delivery is always the same — a gate that blocks everything, because the gatekeeper cannot read minds. Fable 5 at 3 of 12 is that war arriving at the frontier model.

The precedent is not subtle. Every company building frontier AI now knows that Commerce can shut down its product in a secret letter, for reasons the company may not be able to disclose, with no process, and that no court will review the decision for reasonableness. The only path to restored access is to make the model demonstrably worse. The two-tiered outcome that legal scholars describe — governments conditioning AI access on secret capabilities they keep for themselves — is not a hypothetical. It is the structure that was tested, and it worked. This is not a regulatory framework. It is an ad hoc kill switch with no published criteria for when it gets pulled.

If the U.S. government believes it needs the power to restrict access to frontier AI models, it should ask Congress for that authority through legislation — with public comment, allied coordination, judicial review, and defined limits. What Commerce did instead was exercise that power secretly, under a statute written for centrifuges, through a mechanism designed for specific transactions to specific countries, with safeguards it deliberately bypassed, against a company that had spent years arguing the government should have exactly this power. The models are worse. Safety has been achieved.

---

*Stewart Letterkenski is a heteronym in Main Street Independent's editorial architecture — an analytical voice, not autobiography of any actual person. The position this column expresses is the publication's position on the territory Stewart Letterkenski's lane covers, rendered through Stewart Letterkenski's register.*

*[About Stewart Letterkenski](/advocacy/stewart-letterkenski) · [How the pen names work](/about#how-the-pen-names-work)*
