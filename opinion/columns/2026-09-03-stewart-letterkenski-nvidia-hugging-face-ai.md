---
headline: Nvidia bought the town square of AI
publish_date: '2026-09-03'
lede: Jensen Huang just bought the workshop eighteen million AI developers share.
pen_name: stewart-letterkenski
primary_entities:
- Nvidia
- Hugging Face
- Jensen Huang
- OpenAI
primary_themes:
- Corporate acquisitions
- Artificial intelligence
- Open-weight models
- Industry competition
topic_tags:
- artificial intelligence
- computing and information technology
- economy, business and finance
storyline_nexus: []
floor_values_engaged:
- value: accountability_of_power
  intensity: 0.9
- value: equality_fairness
  intensity: 0.6
- value: truthfulness
  intensity: 0.6
framework_version: 1.1.0
generation_timestamp: '2026-09-03T07:10:10-07:00'
source_cluster_id: cluster_ap_2026-09-02_nvidia-hugging-face-ai-d96d50e037a2ade47
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
- slug: 2026-09-03-nvidia-to-acquire-ai-developer-platform-hugging-face-for-12-93-billion
  relation: extends
  strength: 0.6884
  confidence: high
draft: false
image:
  url: /cartoons/nvidia-bought-the-town-square-of-ai.png
  alt: 'Editorial cartoon by Hector Rentier: Nvidia bought the town square of AI'
  caption: He thanked them for the workshop. They paid for it.
  credit: Hector Rentier (Main Street Independent, algorithmic)
  source: ai_generated
  attached_at: '2026-09-03T22:10:09-07:00'
  disclosure: AI-generated illustration. Prompt summary and model identifier available
    in metadata.
  ai_model: openrouter:google/gemini-3.1-flash-image
  ai_prompt: 'Single panel, 1:1, heavy cross-hatch wood-engraving throughout. The
    interior of a vast, crowded workshop — workbenches, lathes, drafting tables, hanging
    tools, scattered papers, pinned sketches — the '
  license: https://creativecommons.org/publicdomain/zero/1.0/
paired_cartoon:
  pen_name: hector-rentier
  slug: 2026-09-03-hector-paired-with-2026-09-03-stewart-letterkenski-nvidia-hugging-face-ai
---

![Editorial cartoon by Hector Rentier: Nvidia bought the town square of AI](/cartoons/nvidia-bought-the-town-square-of-ai.png)
*He thanked them for the workshop. They paid for it.*

Jensen Huang just bought the workshop eighteen million AI developers share.

It is true that Huang, in a blog post on Thursday announcing the acquisition, wrote that Hugging Face "will remain an open platform for the entire AI ecosystem." It is true that he added, separately, that "Nvidia compute will not be required to build on or deploy through Hugging Face." Both statements have the form of reassurance, which is itself a tell: the people who need to reassure you about what they are about to do are usually doing the thing the reassurance is meant to obscure. The chip monopolist's assurance that it will not use its control of the chip layer to favour itself at the platform layer is structurally an assurance that could be broken in a thousand small ways without any single breach being visible enough to litigate.

Hugging Face, before Thursday, was the closest thing the field had to a neutral commons. Eighteen million developers, two hundred thousand companies, three million models, half a million datasets, a million applications, none of which had to ask Nvidia's permission to put their work there or take it down. After Thursday, all of that lives inside the world's largest publicly traded company — a firm whose chips, by any honest accounting, run somewhere in the seventy-to-eighty-percent range of the world's AI training compute. The mechanism by which the value was produced is the unpaid labour of eighteen million people who built a workshop together. The mechanism by which the value was transferred is a thirteen-billion-dollar acquisition. The transaction is, in the precise sense, a captured commons.

It is worth being precise about what Hugging Face actually is, because the public discourse has the unhelpful habit of treating "AI platform" as a single thing. It is a hosting layer for model weights — the numerical parameters that determine what a model does when it runs — and for the datasets used to train those weights. It is a runtime environment for AI applications. It is also, less visibly and more importantly, a community: a place where researchers share code, where papers get discussed, where small teams without the budget to advertise can be discovered by the people who need them. The first two are stackable in the technical sense; the third is not. When the third moves to a new owner, what was once a commons becomes a mall.

The trouble is that the open ecosystem Nvidia is buying into is one in which Nvidia already operates every other layer of the stack. Nvidia sells somewhere in the neighbourhood of eighty per cent of the accelerators used to train large models — the figure varies quarter to quarter, but the order of magnitude is not in serious dispute. Nvidia's CUDA software is what the training is written against. Nvidia's H100, H200, Blackwell, and forthcoming Rubin chips are the silicon. The cloud providers that rent those chips are Nvidia customers, in many cases contracted at the kind of scale that lets Nvidia dictate terms. PyTorch, the dominant framework for building these systems, sits on top of CUDA; if you train a model on AMD's MI300X, you can make it work, but the friction is real, the documentation is thinner, and the pretrained checkpoints your colleagues share will, by overwhelming default, target Nvidia hardware. AMD's ROCm has matured, the hyperscalers have built their own accelerators, and inference at scale increasingly routes outside Nvidia's preferred paths — and the default still routes through CUDA anyway. Saying that customers may choose non-Nvidia silicon in Hugging Face is not the same as saying the practical default will not continue to be Nvidia silicon. The default is the architecture, and Nvidia owns the architecture.

What the announcement calls "open" deserves the scrutiny the word has earned in this industry. Cory Doctorow calls the pattern open-washing: companies borrow the language and the goodwill of openness while preserving the closed apparatus. The pattern recurs. Meta calls its LLaMA models "open" while reserving a commercial-use licence that puts the weights under terms Meta can change. OpenAI called itself "Open" while progressively closing access to its model weights, restructuring its profit cap first in 2019 and again in 2025, and now operating as a public benefit corporation in which Microsoft holds twenty-seven per cent. The pattern is consistent enough that the only fair test for a claim of openness is what the buyer commits to in writing, not what the buyer's chief executive says on the day of the announcement.

This is, more plainly, the chokepoint pattern Doctorow and Rebecca Giblin named in *Chokepoint Capitalism* — a powerful intermediary positioning itself between creators and audiences, collecting rent on every transit. In the AI version, the chokepoint sits between researchers who write the models and the rest of us who use them. Nvidia is now positioned at three distinct chokepoints simultaneously: the silicon that runs training and inference, the capital that finances the data centres — last month's announcement that Nvidia will partner with Wall Street firms to provide partial guarantees for up to [$500 billion in data-center financing](/articles/2026-08-10-nvidia-reaches-500-billion-ai-financing-deal-with-wall-street-firms/) extends that grip further still — and the distribution platform that gives models their public surface. The licensing for the training stack ([Nvidia paid six billion dollars for Poolside's open-weight technology](/articles/2026-08-23-nvidia-pays-6-billion-to-license-poolside-tech-for-open-weight-ai/) earlier this month) and the cloud capacity for the inference layer ([Anthropic's thirty-five-billion-dollar deal with Nvidia-backed Lambda](/articles/2026-08-31-anthropic-signs-35-billion-cloud-deal-with-nvidia-backed-lambda/) last week) sit between those two poles. Read the architecture in one piece and it is legible in real time.

Doctorow's four-stage name for what happens next is enshittification — a platform is first good to its users, then good to its business customers, then value is extracted from both for the benefit of shareholders, then the platform dies. His larger argument, which he has made in book after book and post after post, is that this is not a moral failing of any particular executive. It is what platforms do when the four forces that historically constrained them — competition, regulation, self-help and interoperability, and labour — have been removed. Consider what just disappeared from each.

Competition used to discipline the chip market. Consolidation has narrowed it. Hugging Face was a choice among platforms, and being on it did not require the chip vendor's permission; after Thursday, the platform choice and the chip choice are made in the same boardroom. Regulation used to discipline vertical integration. The Federal Trade Commission under its current leadership has not signalled any appetite to challenge a vertical integration of this size; the Competition Bureau in Ottawa has rarely blocked a merger outright in modern memory, a record worth pausing on whenever the language of merger review is invoked. Self-help and interoperability used to let developers avoid a vendor's preferences. CUDA lock-in and the absence of a serious alternative stack has weakened that. Labour used to discipline firms from inside; the post-2023 layoff wave flattened what leverage tech workers had. Eighteen million developers whose work gets routed through this platform have no collective voice, no seat at any table where the deal was negotiated, and no obvious mechanism for representing their interest in whether the workshop they built together remains a commons. Three of those four forces are already gone in the AI infrastructure market. The fourth is being worked on.

The historical analogues are not reassuring. Google bought YouTube in 2006 for one-point-six-five billion dollars; the concerns then were about content moderation and whether the most important video platform in the world should belong to the most important search company. They have been mostly borne out — YouTube's recommendation algorithm now operates in service of Google's broader advertising business in ways an independent platform would not have countenanced. Meta bought Instagram in 2012 for one billion dollars — a sum that looked inflated at the time, and that Zuckerberg himself, in internal correspondence unsealed during the FTC's monopoly case, called exactly the right price to pay to ensure no competitor ever got that asset. Microsoft acquired GitHub in 2018 for seven-point-five billion dollars; the worry then was that the largest host of open-source code would come to be operated by a firm whose commercial interest was in the parts of the stack that vendor could monetise. The pattern is the pattern, and the pattern matters most at the moment when the acquisition is being framed as inevitable, as foreordained, as the only way the field can continue to function.

The Wall Street Journal, in its coverage of the deal, noted the motive openly — the acquisition would help "counter the rapid ascent of open-weight models developed in China." It is worth pausing on what this framing accomplishes. The argument is that the United States must consolidate its AI infrastructure under domestic incumbents in order to compete with Chinese open-weight alternatives. The argument is also that the consolidation in question is the same consolidation that has produced, in every other industry in which it has been tried in the last forty years, both higher prices and less actual competition. The bundling of national security with market dominance is the move that makes consolidation irreversible; once a chokepoint is a matter of geopolitical necessity, breaking it up becomes an act against the state. The argument deserves more scrutiny than it has received, and will probably receive less.

The consolidation play that Lina Khan named in her 2017 *Yale Law Journal* piece, "Amazon's Antitrust Paradox," was that a firm with monopsony power in one layer of a stack can use that power to extract rents and foreclose competitors in adjacent layers. The 2020 House Antitrust Subcommittee report on competition in digital markets described, in its chapter on cloud infrastructure, the specific version of this play that Thursday's announcement instantiates. The committee's recommendation was that something be done. Nothing was done. The acquisition that report would have warned against is now announced.

The cui bono is plain enough. Nvidia's enterprise customers get a distribution channel for their models that is now vertically integrated with the chip supplier they already buy from. Nvidia's competitors — AMD, Intel, the various custom-silicon programmes at the hyperscalers — get the assurance that the largest model-distribution platform in the field has a parent with a strong commercial interest in steering default selections toward its own accelerators. The losers, in the medium term, are the people who would have benefited from an alternative distribution surface that did not come with a structural preference for one chip vendor. That is most of the field.

There is an older Canadian habit of thinking about extractive staples. Harold Innis, working in the middle of the last century, named what happens when an economy organises itself around shipping raw material out through a small number of chokepoints controlled by larger firms. The thing being extracted is not always fish or timber or oil. Sometimes it is the work of eighteen million developers, organised into a platform, and then shipped, through a thirteen-billion-dollar acquisition, into the corporate structure of a firm whose interests are not theirs. The mechanism is older than the technology. The technology just made it faster.

The pattern is older than the cloud. My father spent thirty years on the bar mill at Manitoba Rolling Mills. The plant was bought by Gerdau in 1995, the year I turned thirteen. He kept his job; several uncles did not. The pension he retired on, in 2011, was a fraction of the one the 1995 bargain had promised. The playbook — extract surplus from existing labour, lock the workforce in by raising the cost of leaving, find the next class of suppliers, do it to them — is older than the cloud. The cloud just runs it on a larger surface, with fewer witnesses, and in a vocabulary that has been scrubbed of any honest word for what is happening.

Jensen Huang, in his blog post, thanked the Hugging Face community. Jeff Bezos, after one of his earlier acquisitions, thanked Amazon employees and customers, because, in his words, "you guys paid for all this." Both forms of thanks are accurate. The eighteen million developers who built the models and the datasets and the applications that made Hugging Face worth $12.93 billion have, in the most literal accounting, paid for the workshop they are now leasing from the chip monopolist. The terms of that lease have not yet been written. The terms of every previous lease of this kind have been written, in retrospect, by the lessor.

The structural remedy that this market needs, and that the Khan-era FTC would have considered and the current FTC will not, is an interoperability mandate — a rule that requires the owner of Hugging Face to maintain, on commercially reasonable terms, the platform neutrality that existed before Thursday. Laws of this kind exist in the right-to-repair context in New York, Massachusetts, and Minnesota, and in the interoperability mandates of the European Union's Digital Markets Act. There is no good reason, technical or economic, why they cannot be extended to AI infrastructure. There is a very good political reason why they will not be: the chip monopolist sits at the table where the rule would be written.

There is no public consultation open on whether Nvidia should own the place where AI gets built. There probably will not be one. The Federal Trade Commission under its current leadership will, in the most generous reading, ask polite questions and accept polite answers. The Competition Bureau will do the Canadian equivalent, which is to say the same thing in two languages and with somewhat better procedural record-keeping. Hugging Face has users here and a presence here; the Bureau has thirty days from filing under the pre-merger notification regime to ask a supplementary information request. It will not ask. The deal will close. Eighteen million developers will go on using Hugging Face as if Thursday had not happened, because the cost of leaving a platform is paid later, in slow increments, by people who were not in the room when the decision was made. The announcement was on Thursday. The bill comes due over the next five years. Deadlines are the only part of regulatory processes that the regulated actually respect.

## Sources

### src_001 — Main Street Independent, other, Tier 1, originating
**Title:** ## Nvidia to acquire AI developer platform Hugging Face for $12.93 billion
**URL:** https://mainstreetindependent.com/articles/2026-09-03-nvidia-to-acquire-ai-developer-platform-hugging-face-for-12-93-billion/
