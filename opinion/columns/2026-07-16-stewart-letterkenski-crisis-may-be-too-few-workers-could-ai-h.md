---
headline: Your Future Raise Is AI's Newest Sales Pitch
publish_date: '2026-07-16'
lede: The AI industry is reframing your future bargaining power as its deployment crisis.
pen_name: stewart-letterkenski
primary_entities: []
primary_themes: []
topic_tags: []
storyline_nexus: []
floor_values_engaged: []
framework_version: 1.1.0
generation_timestamp: '2026-07-15T23:32:57-07:00'
source_cluster_id: cluster_wsj_2026-07-13_crisis-may-be-too-few-workers-could-ai-h
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
image:
  url: /figures/2026-07-13-u-s-labor-force-faces-historic-contraction-as-demographic-pressure-raises-the-st/fig-civpart-raw-hero.svg
  alt: 'Labor Force Participation Rate: falling from 62.90 to 61.50 (2015-01-01 to 2026-06-01).'
  source: ai_generated
cross_article_links:
- slug: 2026-07-13-u-s-labor-force-faces-historic-contraction-as-demographic-pressure-raises-the-st
  relation: extends
  strength: 0.8738
  confidence: high
draft: false
---

The AI industry is reframing your future bargaining power as its deployment crisis.

It is true that the United States faces a genuine demographic transition. Steven Ruggles, the University of Minnesota demographer and 2022 MacArthur Fellow, published a paper this May in *Proceedings of the National Academy of Sciences* showing the U.S. labour force will expand by only 9.1 million people in the decade ending in 2030 — the fewest since 1960 — and then contract by 2.1 million in the decade after that. The Congressional Budget Office reached broadly similar conclusions earlier this year when it [projected that declining fertility and shifting immigration policy would slow population growth to a crawl](/articles/2026-01-07-trump-immigration-policies-lower-fertility-to-slow-us-population-growth-cbo-says/). The fertility decline that began in the mid-2000s is baked into the actuarial tables. The two forces that masked the end of the baby boom — rising women's labour-force participation and increased immigration — have, by Ruggles's analysis, run their course.

What Ruggles is also documenting — though the Journal's headline would not lead you there — is that this scarcity could be the best structural news American workers have had in forty years.

Here is where the substance discrimination matters, because the documentary record is unusually clear. Daron Acemoglu, the MIT economist who won the 2024 Nobel Prize, posted a working paper this month to the National Bureau of Economic Research with David Autor, Keelan Beirne, and Andrew Scott. Their core finding, from cross-country and cross-regional analysis: slower population growth is associated with higher GDP per working-age adult and higher wages. "Labour markets in which workers are scarce work really well for workers and generate productivity gains as well," Acemoglu told the Journal. The mechanism is not mysterious: scarce workers command higher prices. Businesses then invest in labour-saving technology, and the resulting productivity gains have historically been sufficient to support overall GDP growth while wages rise.

This is the Easterlin hypothesis vindicated — Richard Easterlin's 1978 prediction to the Population Association of America that young men's real wages would rise once the baby boom passed through the labour market. The prediction was delayed forty years by rising female participation and immigration, but the demographic arithmetic now says it must come due. Ruggles himself thinks wages for young people will rise and that organised labour could get a boost.

The trouble is that the AI industry has read the same projections and arrived at a different conclusion: not that scarcity will raise wages, but that scarcity is a productivity crisis that AI must solve.

Notice the move. The Journal reports that "AI companies, facing criticism, have lately shifted their messaging" from replacing jobs to boosting productivity. That shift is not a concession to critics. It is a deployment strategy. When the pitch was "AI will take your job," the public resisted — resistance the industry now frames as a problem to be managed. When the pitch becomes "AI will fill the jobs no one else can," the same public is asked to be grateful. The underlying technology has not changed. The marketing adapted to the audience's antibodies.

And the engineering reality of the technology has not changed either. What the industry sells as "artificial intelligence" in these productivity pitches is, in almost every case, a large language model — a system trained on vast quantities of text to predict the most probable next sequence of tokens given a prompt. The technical term for what it does is next-token prediction. The practical consequence is that it produces outputs that are statistically plausible given its training distribution, not outputs that are correct, grounded, or novel in the way the work actually requires. A billing clerk does not need statistically plausible invoices. A radiologist does not need a plausible reading of a scan. They need the right one, and the difference between the two is the difference between a tool that supplements labour and one that introduces a new failure mode.

This is not a theoretical objection. Hallucination — the production of confident, fluent, fabricated output — is not a bug the industry is working around. It is an architectural consequence of how these systems work. A model trained to produce the most likely next word has no mechanism for distinguishing truth from plausibility, because plausibility is the only objective function it was given. Companies deploying these systems in hiring, legal discovery, customer service, and clinical documentation have discovered that every output requires a human verifier — which means the technology does not eliminate the worker, it reorganises the worker's role into something narrower and more repetitive: monitoring a system that might be wrong at any moment for ways in which it is wrong. Cory Doctorow has a precise term for this: the reverse centaur, where a human being is "pressed into service as a peripheral for a machine," running at machine pace and absorbing the blame when the system fails. The centaur — a worker augmented by a capable tool — was the promise. The reverse centaur is the deployment reality.

The productivity numbers reflect this gap. Despite three years of generative-AI product launches, U.S. total-factor productivity growth has remained within its post-2005 range. The firms deploying these systems report internal efficiency gains in specific, bounded tasks — summarising documents, drafting initial versions of boilerplate, triaging routine queries. They do not report the kind of economy-wide productivity acceleration that would be required to offset a 2.1-million-person labour-force contraction. The Acemoglu paper establishes that economies have historically invested in labour-saving technology when workers become scarce, and that the resulting efficiency gains have been sufficient. But the historical examples — mechanised agriculture, industrial automation, computing itself — involved technologies whose engineering characteristics were well understood before deployment. The technology this time is being deployed at scale before its capabilities and failure modes are characterised, in a market where the incentive is to sell the licence before the customer discovers the limits.

The limits are specific and structural. A large language model's knowledge is frozen at the moment its training data is assembled. It cannot learn from its interactions in real time without retraining — a process that costs tens of millions of dollars and takes weeks. It operates within a context window — a fixed span of tokens it can attend to at once — that, however expanded by engineering advances, remains a fraction of what a skilled human worker holds in working memory across a full day. It cannot maintain persistent state across sessions without external engineering that reintroduces the very integration costs the technology was supposed to eliminate. Every deployment at production scale requires what engineers call a retrieval-augmented generation pipeline — a surrounding architecture of databases, search indices, and verification layers that does the actual work of keeping the system grounded in facts. Strip away that architecture and you are left with a text generator that cannot tell you whether what it just said is true.

These are the constraints that the industry's productivity narrative elides. They are not edge cases. They are the architecture.

Cory Doctorow has a name for the dynamic beyond the reverse centaur. In *The Internet Con* and across the *Pluralistic* corpus, he describes a labour-discipline mechanism: the threat of replacement does the work, whether or not the technology can actually deliver. An executive who believes a chatbot can do your job no longer has to negotiate with you. Bosses are "thrilled by the prospect of swapping professionals for chatbots" partly because it lets them "escape ego-shattering conflicts with empowered workers who actually know how to do things" — Doctorow's gloss, from his essay on AI as a war on professional bargaining power. The labour-scarcity framing is the salesman's latest deployment of this same move: convert the one demographic shift that might finally raise your wages into an argument for installing the technology that could prevent it.

Doctorow's framework names four forces that historically constrained this kind of extraction: competition, regulation, self-help through interoperability, and labour itself. The labour scarcity Ruggles documents is, structurally, the return of the fourth force — workers who can say no because employers have no one else to hire. The entire purpose of the AI deployment narrative is to neutralise that force before it fully materialises. If the boss believes a machine can replace you, your scarcity leverage collapses — whether or not the machine actually can. And the engineering record suggests it largely cannot, at least not at the level of generality the marketing implies: a system that hallucinates case law in a legal brief, fabricates citations in a medical review, and loses coherence beyond its context window is not a system that replaces the professional. It is a system that creates a new category of risk for the firm deploying it — risk the firm will manage by keeping the professional on call at reduced wages, which is the actual labour-discipline outcome.

Acemoglu himself is more careful than the framing that surrounds him. He notes that massive AI productivity gains could mean "you're actually laying off workers rather than running after them" despite the shrinking labour pool — which is the engineering reality the marketing obscures: a technology powerful enough to offset a demographic contraction is powerful enough to hollow out the wage gains the contraction would produce. His paper establishes that economies have historically offset labour scarcity through efficiency investments. It does not establish that AI is the technology that will do it this time, or that the gains will flow to workers rather than to the shareholders of the firms deploying the systems. The economists [surveyed on this](/articles/2026-06-10-economists-mostly-agree-ai-will-boost-productivity-split-on-job-impact/) mostly agree AI will boost productivity. They split on whether it will create or destroy jobs. That split is the difference between a technology that supplements your bargaining power and one that eliminates it.

Gerdau of Porto Alegre acquired the Selkirk steel mill in 1995. The pitch was modernisation — new rolling technology, efficiency gains, a leaner operation. The efficiency was real. The workforce was cut. The workers who stayed worked harder for less security, and the productivity gains flowed to shareholders half a hemisphere away. The mechanism is older than any algorithm: leverage the efficiency argument against a workforce that has just begun to acquire bargaining power, capture the gains, move on.

The policy task is to ensure that demographic scarcity delivers the wage gains the arithmetic promises before the efficiency argument is deployed to capture them. Sectoral bargaining — setting wages industry-wide so no firm gains by substituting machines for people at the margin — is the structural instrument. [Tripling union membership would raise median worker pay 14.5%](/articles/2026-07-15-tripling-union-membership-would-raise-median-worker-pay-14-5-report-says/), according to a report published this week. A workforce that can bargain collectively is one that captures its own productivity gains. A workforce that cannot watches those gains flow to whatever platform replaced it. There is an ongoing policy discussion at the Federal Trade Commission about algorithmic wage discrimination — the practice of using AI to pay different workers different rates based on how desperate the system calculates each one to be. The comment portal is at regulations.gov. Submissions matter.

The demographic arithmetic says wages are about to rise. The AI industry has spent the last six months making sure you think of that as a problem. The engineering record says the tool it is selling you to solve that problem largely cannot do what it promises — but that does not matter, because the promise was never really for you.

---

*Stewart Letterkenski is a heteronym in Main Street Independent's editorial architecture — an analytical voice, not autobiography of any actual person. The position this column expresses is the publication's position on the territory Stewart Letterkenski's lane covers, rendered through Stewart Letterkenski's register.*

*[About Stewart Letterkenski](/advocacy/stewart-letterkenski) · [How the pen names work](/about#how-the-pen-names-work)*
