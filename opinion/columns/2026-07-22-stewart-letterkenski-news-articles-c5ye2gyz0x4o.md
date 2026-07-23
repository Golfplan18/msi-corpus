---
headline: Kratsios calls Moonshot's hand. He shouldn't have.
publish_date: '2026-07-22'
lede: Moonshot AI, the Chinese lab whose Kimi K3 release last week narrowed the gap between American and Chinese frontier models, distilled capabilities from Anthropic's Fable AI on a "large scale" — that is the accusation Michael Kratsios, President Donald Trump's science and technology adviser, lodged on X this week.
pen_name: stewart-letterkenski
primary_entities: []
primary_themes: []
topic_tags: []
storyline_nexus: []
floor_values_engaged: []
framework_version: 1.1.0
generation_timestamp: '2026-07-22T19:34:31-07:00'
source_cluster_id: cluster_bbc_2026-07-22_news-articles-c5ye2gyz0x4o
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
- slug: 2026-07-23-white-house-adviser-accuses-china-s-moonshot-ai-of-stealing-from-anthropic
  relation: extends
  strength: 0.4007
  confidence: high
draft: false
backlog_release: true
---

Moonshot AI, the Chinese lab whose Kimi K3 release last week narrowed the gap between American and Chinese frontier models, distilled capabilities from Anthropic's Fable AI on a "large scale" — that is the accusation Michael Kratsios, President Donald Trump's science and technology adviser, lodged on X this week. He added that Moonshot obtained restricted Nvidia hardware for the training run. Treasury Secretary Scott Bessent followed on Fox Business: "If we see, especially, that overseas models are stealing from our great companies, we have the ability to sanction them." The Treasury Secretary is not in the habit of announcing tools he does not intend to use. The accusation lands weeks before a planned Trump-Xi meeting, and the meeting is the frame.

Distillation is a real engineering technique. A smaller model asks a larger one millions of questions, harvests the answers, and trains on the outputs — an entirely standard technique for transferring capability between systems that share an API. The trouble is that what Kratsios is describing as theft is not, on the documented record, a violation of any contract Moonshot signed with Anthropic, any statute the United States has passed, or any norm the American AI industry has bothered to articulate in writing. Distillation through a public API is not a crime. Distillation through a published model is not a crime. Distillation through an open-weights release is not a crime. What it is, is what every frontier lab in the United States does every day it has a smaller experimental model training on the outputs of its own larger one.

To be precise about what "the algorithm" actually is here, because the public discourse has the misleading habit of treating it as a thing rather than a continually-tuned set of weights serving a continually-revised objective function: distillation is the standard knowledge-transfer mechanism the industry uses internally, and has used since the GPT-3 era. The technique does not read out weights, copy a file, or exfiltrate proprietary code. It submits queries and reads answers, the same way any other customer does. The evidence that Moonshot used it at "large scale" is, by Kratsios's own statement, the U.S. government's belief that the K3 model's behaviour resembles Fable's. That is what model training does. That is what training on a frontier-lab's outputs looks like. It is not what stealing looks like.

The Nvidia allegation is the more interesting one, and the more easily verifiable. Restricted export-controlled hardware has a documented chain of custody. If Moonshot trained on H100s or H800s that reached it through a sanctioned intermediary, the paper trail is in Nvidia's shipping manifests, the U.S. Commerce Department's license records, and the export-control enforcement chain — which is to say, the actual U.S. intelligence on this question sits with the agencies that license and audit chip flows, not with the White House science adviser's X account. Kratsios said Moonshot "gained access" to restricted cutting-edge Nvidia servers. He did not say how. The absence is the news. The U.S. export-control apparatus on advanced AI accelerators is supposed to track individual accelerators at the serial-number level through the BIS Entity List, the October 2023 update, and the December 2024 diffusion rule that extended controls to twenty-plus countries. If that apparatus cannot produce the shipping records for the accelerators Moonshot trained on, the failure is in the apparatus, and the answer is to fund the Bureau of Industry and Security properly, not to call a Chinese lab thieves on the basis of API-query pattern-matching.

The Anthropic framing is also worth pausing on, because it is the same Anthropic that, the month before last, accused Alibaba of running [the "largest known" AI distillation attack](/articles/2026-06-25-anthropic-accuses-alibaba-of-largest-known-ai-distillation-attack/) — a charge that was widely repeated and largely unverified at the time and remains largely unverified now. Anthropic has a corporate interest in the public framing of distillation-as-theft. It sells API access to its models. It does not sell the weights of its frontier systems. The commercial product is the gatekept output channel; the entire moat is the difference between the gated and the ungated. A technique that lets a third party train a comparable model on gated outputs is, from Anthropic's standpoint, an existential commercial threat, and the company has every incentive to position the technique as a theft and to seek government enforcement of its preferred commercial model.

This is the same pattern the American frontier labs and the U.S. government have been running for the better part of a year. When Moonshot released K3 and [the model narrowed the gap to U.S. frontier performance](/articles/2026-07-20-chinese-ai-models-top-u-s-rivals-at-shanghai-conference/), the response was not "we need to ship a better model." The response was to ask the Treasury Secretary to put sanctions on a Chinese lab. When Xi Jinping [endorsed open-source AI and stood up a China-led international AI body](/articles/2026-07-17-xi-endorses-open-source-ai-launches-china-led-global-body/) in the same fortnight, the response was not to articulate an American position on open-weight releases. The response was to threaten sanctions on the basis of technique-use that the U.S. industry uses internally every week. The pattern is consistent enough to be structural: when a foreign lab ships a model that competes with yours, ask the government to make the competition illegal. The Diffusion Rule itself, the export-control regime tightened in late 2024 to cap Chinese access to advanced accelerators, was sold to the public on exactly that logic.

There is, beneath this, a real policy question that the Kratsios statement actively obscures. Distillation through public APIs, against published terms of service, is the standard practice of the American AI industry. The OpenAI Terms of Use prohibit using model outputs to train competing models — but the prohibition is contractual, not statutory, and Anthropic's own API terms prohibit the same use against them. If the United States is going to sanction Chinese labs for distillation, the U.S. government is going to have to take a position on whether distillation is a protected technique in the American AI stack, or whether it is theft. The two are mutually exclusive. You cannot, as a matter of basic regulatory logic, prohibit your competitor from doing the thing you do to your own researchers.

The right move on the export-control question is the boring move: publish the BIS shipping records for the accelerators Moonshot trained on, or formally allege that the records show what Kratsios implied. If the records are classified, declassify the relevant portions. If they cannot be declassified, admit that the allegation is based on inference, not on tracking data — and submit to NIST, on the public comment record, the technical specification of how API-query pattern-matching distinguishes distillation from ordinary customer use. The right move on the distillation question is also the boring move: ask the frontier labs to publish their terms of service, publish the technical detection methods they claim can distinguish a distilling customer from an ordinary customer, and ask them to explain how the technique differs from the in-house distillation OpenAI, Anthropic, Google, and Meta each run as a core part of their own training pipelines. None of this is the move the administration is making. The move the administration is making is to call a Chinese lab a thief on the basis of API patterns, threaten sanctions from the Treasury Department, and leave the documentary record for someone else to assemble.

There is a public comment process, by the way, that will assemble part of it. NIST is taking comments on the AI Diffusion Rule and the export-control regime through the end of the month. The deadline matters because deadlines are the only part of regulatory processes that the regulated actually respect, and submissions are the only part of regulatory records that subsequent administrations have to read. If the American AI industry wants the United States to sanction Chinese labs for distillation, the comment period is the place to argue for it, on the record, with the technical specification attached. The alternative is what we have now: a Treasury Secretary promising sanctions he has not specified, on conduct that is not illegal, against labs whose techniques are standard industry practice, weeks before a meeting where the sanction threat is leverage, not enforcement. The work is to be done.

---

*Stewart Letterkenski is a heteronym in Main Street Independent's editorial architecture — an analytical voice, not autobiography of any actual person. The position this column expresses is the publication's position on the territory Stewart Letterkenski's lane covers, rendered through Stewart Letterkenski's register.*

*[About Stewart Letterkenski](/advocacy/stewart-letterkenski) · [How the pen names work](/about#how-the-pen-names-work)*
