---
headline: U.S. AI Companies Charged for Scarcity. Chinese Firms Are Selling Abundance.
publish_date: '2026-07-26'
lede: Moonshot's Kimi K3 undercuts Anthropic's Claude Fable on price and, by Mozilla Chief Technology Officer Raffi Krikorian's account, beats it on speed.
pen_name: stewart-letterkenski
primary_entities: []
primary_themes: []
topic_tags: []
storyline_nexus: []
floor_values_engaged: []
framework_version: 1.1.0
generation_timestamp: '2026-07-25T22:35:51-07:00'
source_cluster_id: cluster_ap_2026-07-25_china-ai-model-us-kimi-deepseek-a00bf637
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
- slug: 2026-07-26-chinese-ai-models-gain-u-s-users-as-companies-trim-costs
  relation: extends
  strength: 0.7095
  confidence: high
draft: false
backlog_release: true
---

Moonshot's Kimi K3 undercuts Anthropic's Claude Fable on price and, by Mozilla Chief Technology Officer Raffi Krikorian's account, beats it on speed. Coinbase is switching to Chinese models to trim costs. The AP wire filed the story last week; the more interesting story is what the cost differential reveals about the pricing model U.S. AI companies built.

Here is what inference actually is, because the public discourse obscures it behind the word "AI" as though it were a single thing. A large language model is a mathematical function with billions of parameters. Running that function on an input — answering a question, generating text, classifying data — is inference. It consumes GPU cycles and electricity. It is, in the engineering sense, a commodity operation: run the function, return the output. When every major lab is producing models that perform within a narrow band of each other on standard benchmarks, the operation itself — not any particular model's secret sauce — is what the customer is buying.

U.S. AI companies priced inference as though it were premium compute, because until very recently they were the only firms offering production-grade models at scale, and the chips they run on — NVIDIA's GPUs, manufactured by TSMC — were genuinely scarce. The scarcity premium was real. It was also, as of this week, visibly eroding.

It is true that a cryptocurrency exchange optimizing its overhead and a browser-maker's CTO switching chatbot providers are, individually, ordinary procurement decisions. Companies switch vendors. That is how markets work, or are supposed to. The trouble is that the U.S. AI industry's entire cost structure was built on the assumption that they would not have to compete on price — that inference, the act of running a trained model to produce output, was scarce enough to sustain margins that look more like pharmaceutical exclusivity than like cloud computing.

The erosion matters because the premium was load-bearing. U.S. AI companies — OpenAI, Anthropic, Google's DeepMind — have collectively poured hundreds of billions of dollars into the premise that they are building infrastructure with durable pricing power. Their cost models assume that inference revenue will scale with demand, that customers locked into their APIs and fine-tuned on their model architectures will tolerate price floors set by the companies themselves. When Coinbase, a company whose core business involves moving money as cheaply as possible, says publicly that it is switching to Chinese models to cut costs, the inference premium just lost a customer who ran the numbers.

The structural point is not about Moonshot or Kimi K3 specifically. It is about what it means when a model from a Chinese startup matches or exceeds the performance of a San Francisco lab's flagship product at a fraction of the price — and when a major U.S. technology organization's CTO switches within days of the model's launch. It means the U.S. AI companies' pricing was predicated on a scarcity that no longer holds. The margin has to come from somewhere. If it does not come from the price of inference, it has to come from lock-in — the inability to switch, the cost of migration, the switching costs that Cory Doctorow's [enshittification framework](/articles/2026-07-25-u-s-companies-ditch-pricey-ai-models-for-cheaper-alternatives/) identifies as the constraint whose removal forces firms to compete on quality rather than on captivity.

There are legitimate questions about Chinese AI models — data residency, training-data provenance, the security implications of routing sensitive queries through servers subject to Chinese jurisdiction. Those are real questions, and they deserve real answers. But notice when the security framing intensifies: it intensifies precisely as the cost advantage becomes undeniable. A [White House adviser last week accused Moonshot of stealing from Anthropic](/articles/2026-07-23-white-house-adviser-accuses-china-s-moonshot-ai-of-stealing-from-anthropic/); the accusation may or may not have merit on its facts, but its timing serves a function beyond the legal question. It reframes a cost problem as a security problem, which is more comfortable for an industry that would rather explain why its product is dangerous to refuse than why its product is too expensive to justify.

The deeper structural question is not whether U.S. companies should or should not use Chinese models. It is whether the inference premium that U.S. AI companies charged was ever going to survive contact with competition from firms that do not need to justify a trillion-dollar capital-expenditure cycle to Wall Street. Moonshot and DeepSeek [topped U.S. rivals at a Shanghai conference](/articles/2026-07-20-chinese-ai-models-top-u-s-rivals-at-shanghai-conference/) last month; their continued cost advantages suggest the answer is no. The U.S. AI industry built its economics on an assumption of permanent scarcity — scarce chips, scarce talent, scarce model capability — and Chinese firms are demonstrating, week by week, that the scarcity was a function of market structure, not of physics. You can build competitive models more cheaply. The question is whether anyone in the U.S. AI industry has an economic model that works once that fact is widely known.

It is worth pausing on the geopolitical dimension, because it cuts in the opposite direction from how most coverage frames it. The U.S. response to Chinese AI competition has been export controls on chips — restrictions on what semiconductors Chinese firms can buy. The stated rationale is national security. The structural effect is to force Chinese firms to build efficient models on constrained hardware, which makes them more cost-competitive, not less. Every chip restriction that tightens Chinese access to NVIDIA's latest GPUs is an incentive for Moonshot and DeepSeek to optimize harder — quantization, model pruning, mixture-of-experts architectures, speculative decoding — engineering responses to constrained hardware that make each query cheaper, not more expensive. The policy designed to preserve U.S. AI supremacy is accelerating the commoditization it was meant to prevent. This is not a paradox. It is what happens when a policy response addresses the symptom — Chinese firms are competitive — rather than the cause — U.S. AI pricing assumed scarcity that market forces were always going to erode.

Coinbase switching to Chinese models to save money is, in the end, a procurement decision. Mozilla's CTO switching to a faster model is a user-experience decision. Neither, individually, is a tech-policy event. But the pattern they belong to — U.S. organizations quietly migrating to cheaper Chinese inference as the cost gap widens — is the moment the AI pricing model meets the same force that deflated IBM's mainframe monopoly: the arrival of open, cheaper alternatives that make proprietary lock-in a losing bet rather than a moat. The U.S. AI industry's response will be revealing. If the answer is lock-in — proprietary fine-tuning, closed APIs, switching costs engineered into the workflow — then the industry has told you what it thinks its product is worth on the open market. IBM priced its dominance as permanent and watched it evaporate. The answer, by the look of this week's procurement decisions, is: not what they were charging.

---

*Stewart Letterkenski is a heteronym in Main Street Independent's editorial architecture — an analytical voice, not autobiography of any actual person. The position this column expresses is the publication's position on the territory Stewart Letterkenski's lane covers, rendered through Stewart Letterkenski's register.*

*[About Stewart Letterkenski](/advocacy/stewart-letterkenski) · [How the pen names work](/about#how-the-pen-names-work)*
