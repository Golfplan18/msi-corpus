---
headline: Google Built the Scam Engine. Now its Lawyers Are Suing.
publish_date: '2026-06-12'
lede: Google built the billion-dollar SMS theft racket with Gemini and is now suing the scammers.
pen_name: stewart-letterkenski
primary_entities: []
primary_themes: []
topic_tags: []
storyline_nexus: []
floor_values_engaged: []
framework_version: 1.1.0
generation_timestamp: '2026-06-12T19:04:40Z'
source_cluster_id: cluster_wsj_2026-06-12_harging-the-spamosphere-amping-up-prolif
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
cross_article_links: []
draft: false
---

Google built the billion-dollar SMS theft racket with Gemini and is now suing the scammers. The company named the group “Outsider,” the FBI attributed 3.87 million stolen credit cards and $1.9 billion in losses since July 2023, and Google is asking a New York federal court to take down the websites and the communication channels that run them. The press release calls it a pioneering enforcement action against the “spamosphere” — a term that does a lot of heavy atmospheric lifting to distance the platform from the atmosphere it actually is.

To understand the architecture — and it is worth being precise, because the public discourse treats AI fraud as a magical new threat rather than as a feature of the current generation of large language models deployed without friction — one has only to read the admission Google’s general counsel made to the press. Halimah DeLaine Prado said the company’s safety filters let the scam prompts through because a content filter is not necessarily going to block a person’s ability to create code for a website, and generating front‑end code is a “fairly innocuous ask.” She is right. The technical layer of a credential‑harvesting phishing site — a responsive HTML form that asks for a carrier account number, a password, and a credit‑card field — is textually identical to the front end of the legitimate carrier rewards portal. If you ask an LLM to write a script that fetches a directory structure, it returns the script. If you ask it to build an HTML template that mimics the phone carrier rewards page and posts to an unauthorised endpoint, it does that too. The difference between the enterprise developer and the organised‑crime syndicate is the intention in the human’s head, which the LLM does not see and the safety filter does not read. Google built a code‑generation engine that cannot distinguish the builder from the thief, and when the thief used it exactly as advertised, the company decided the remedy was a federal lawsuit rather than a specification change.

The fraud is not a technological accident. It is a trade‑off the company has made. To filter out prompts that ask for an HTML page that looks like a T‑Mobile login form would require a classifier that can distinguish between a legitimate developer building a login demo and a scammer building a credential harvester. That classifier does not exist in Gemini, or in any of the major consumer AI tools, because building it would make the product less useful for the vast gray zone of borderline requests real developers make every day. The code‑generation tool is priced for scale and optimised for throughput. Outsider ran the numbers, realized the marginal cost of a phishing template had collapsed to near zero, and scaled the operation to 8,000 sites. The $1.9 billion in extracted value is a theft‑racket at machine scale, stripped of the human labour usually required to maintain 8,000 rotating domains and write thousands of unique front‑end templates. Google Messages is the transport layer for the Android ecosystem, and the 55,000 suspicious‑message reports in a single two‑week window in late May were routed through the very pipe the company controls and advertises as the secure upgrade from legacy SMS.

Galbraith’s concept of the bezzle — the interval between the commission of a fraud and its discovery, during which the perpetrator enjoys the gains and the victim feels no loss — is running at scale. Google’s legal complaint is an effort to shorten that interval for a single group of scammers while keeping the underlying machinery intact. The 55,000 reports in two weeks are not an anomaly. They are the noise floor of a product whose designers have decided that a few billion dollars a year in stolen credit card numbers, borne by other people, is an acceptable cost of being a general‑purpose computer that happens to run programs its makers don’t like.

The playbook is not unique. West African fraud rings, identified by threat‑intelligence firm DarkTower, are now using AI to manage invoice‑scam operations end‑to‑end — researching executives, crafting phishing emails, even recommending who to target — a sign that the industrialization of AI fraud extends well beyond telecom phishing. When Anthropic reported state‑sponsored hackers using its models for automated cyberattacks, the response was identical: the technology is too powerful to constrain, the filters cannot keep up, and the only viable recourse is the intellectual‑property and anti‑fraud litigation team. The framing of a “spamosphere” is platform‑apologetics dressed as atmospheric science — as if the fraud were weather that just happens to occur over Google’s infrastructure, rather than the exhaust of the machine Google switched on and sells by the token. The company’s simultaneous boasting about using AI to block scam ads is instructive: when AI helps Google filter bad content on its own platforms, it is a capability showcased for trust; when the same class of tool is used to generate fraudulent pages, the remedy is a lawsuit against the operators, not a redesign of the tool.

The structural response — the one the platform has no interest in building because it touches the revenue model — is not a lawsuit in the Southern District of New York. It is a verification layer at the transport level, a re‑architecture of the model’s objective function that treats the generation of spoofed credential‑harvesting forms as an intrinsic property of the output rather than a question of the prompt’s phrasing, and an interoperable reporting standard that shifts the burden of enforcement from private litigation to a public registry of malicious infrastructure. All three would cut against the model’s core value proposition — friction‑free code generation for anyone — which is precisely why the company treats litigation as the first resort, not the last.

The court will handle the takedowns. The scammers will write new prompts. The code will render.

---

*Stewart Letterkenski is a heteronym in Main Street Independent's editorial architecture — an analytical voice, not autobiography of any actual person. The position this column expresses is the publication's position on the territory Stewart Letterkenski's lane covers, rendered through Stewart Letterkenski's register.*

*[About Stewart Letterkenski](/advocacy/stewart-letterkenski) · [How the pen names work](/about#how-the-pen-names-work)*
