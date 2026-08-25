---
headline: Wall Street Is Cashing Out the AI Stack Before the Music Stops
publish_date: '2026-08-25'
lede: Wall Street is cashing out the AI stack before the receipts come due.
pen_name: stewart-letterkenski
primary_entities:
- Oura
- Inspire Brands
- Anthropic
- Switch
- SB Energy
- Nscale
- SpaceX
- OpenAI
- Roark Capital Group
- Dealogic
primary_themes:
- capital markets
- initial public offerings
topic_tags:
- business information
- economy, business and finance
- financial and business service
- technology and engineering
storyline_nexus: []
floor_values_engaged:
- value: truthfulness
  intensity: 0.9
- value: equality_fairness
  intensity: 0.6
- value: accountability_of_power
  intensity: 0.3
framework_version: 1.1.0
generation_timestamp: '2026-08-24T19:32:05-07:00'
source_cluster_id: cluster_wsj_2026-08-24_finance-stocks-oura-and-dunkin-get-ready
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_disclosure: This article was generated algorithmically by Main Street Independent from the public sources listed in its Sources section.
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
- slug: 2026-08-25-oura-inspire-brands-among-companies-targeting-fall-ipos
  relation: extends
  strength: 0.4797
  confidence: high
draft: false
---

Wall Street is cashing out the AI stack before the receipts come due. Anthropic is preparing to raise as much as $100 billion in an initial public offering that could land in September or October. Oura, the fitness-tracking-ring company, is weighing its own September or October listing at a valuation well above the $11 billion it fetched in its last private round. Inspire Brands, the Roark Capital–backed parent of Dunkin' and Arby's, is looking at an offering as early as the end of this year. Switch, SB Energy, and Nscale are out meeting prospective investors right now. Five companies, three sectors, one window. The market remains dependent on conditions and there are no guarantees any of them will land as planned; the point is that the queue has formed, and the queue is the signal.

The companies lining up are not a random sample of the private market. They are a precise stack, and what each layer actually requires in compute, capital, and infrastructure is the part the press summaries consistently leave out. The 2026 IPO cohort is not the 2021 cohort. The AI stack has real engineering dependencies that the 2021 meme stocks and pre-revenue SPACs did not. Whether that distinction matters for the people who buy the paper depends on which way the unit economics break.

Start at the top, with Anthropic. The company's flagship product is a family of large language models — Claude Opus, Sonnet, and Haiku, as the marketing tier names them. What the marketing does not say is what each of those cost the company to train and to serve. A frontier-class training run now consumes on the order of ten thousand to thirty thousand high-end GPUs running for weeks to months; Meta's published number for the largest Llama 3 configuration was 16,384 H100s trained over roughly a month, and Anthropic's top-end runs are believed to be at or above that scale. The dollar cost of a single frontier training run, before any data-center overhead, is in the range of $50 million to $200 million depending on whose estimate you trust and which model you are talking about. Depreciation of the GPU fleet is on top of that, and the useful life of a frontier-training GPU before it is relegated to inference is on the order of eighteen months to three years. The depreciation schedule is real and short.

Then there is inference, which is the part of the business that actually generates revenue. Each token a customer gets back from Claude cost Anthropic real money to produce — electricity, GPU-hours, cooling, and the slice of training cost that accountants amortize across the model's useful life. The published price for Claude Sonnet is roughly $3 per million input tokens and $15 per million output tokens; the cost side of that, at scale, is the part the prospectus will eventually have to disclose. OpenAI reported 18 percent revenue growth between the first and second quarters of this year, with losses deepening at the same time, and OpenAI is dependent on Microsoft for a substantial share of its compute and for a substantial share of its commercial distribution. The same shape — top line moving, bottom line moving faster in the wrong direction — describes the AI-stack revenue picture across the frontier-model developers. Whether the gross margin on inference is positive, zero, or negative at frontier scale is the question whose answer determines whether the $100 billion valuation is a bet on a real industry or a bet on a bezzle.

It is worth pausing on the data-center layer underneath, because this is the part of the stack where engineering reality and capital-markets narrative most violently diverge. Switch, SB Energy, Nscale, and Vantage Data Centers are all data-center developers and operators. Their customers are the AI companies. The product they sell is not racks of servers; it is megawatts delivered to a building that is hot enough to need its own weather system. A single hyperscale AI training campus consumes on the order of 100 to 300 megawatts of continuous power. A multi-building campus runs into the gigawatt range. The U.S. grid was not built for this. Interconnection queues at the major regional grids — PJM, which covers Ohio; ERCOT in Texas; MISO in the Midwest — are now measured in years, not months. A new substation build can take five to seven years from application to commissioning. Hyperscalers have been signing twenty-year power purchase agreements with nuclear plants specifically because the grid cannot move fast enough: Microsoft's restart deal at Three Mile Island, Meta's twenty-year contract for the entire 1.1-gigawatt output of Constellation's Clinton plant, Amazon's adjacency to Talen's Susquehanna nuclear site. The data-center operators going public in 2026 are selling into a market where the bottleneck is no longer how fast you can buy GPUs; it is how fast you can get the electricity authority to build the substation.

The Ohio agreement SB Energy signed with OpenAI this month is the most legible single indicator of what this actually means. Ohio is in PJM Interconnection territory, which means a new hyperscale campus there requires not just a building and a power purchase but also a queue position at PJM for the substation that feeds it. The negotiations between SB Energy and OpenAI that ran for weeks before the deal was announced were, by industry accounts, less about price than about siting: which county has the transmission capacity, which substation upgrade can be expedited, which water source can cool several hundred megawatts of GPU waste heat. The deal getting signed is good news for SB Energy's IPO story. The deal getting signed is also the single fact that should make a public-market investor ask how many more of these campuses the existing grid can absorb, and on what timeline.

What this implies for the broader IPO queue is the part the Dealogic totals do not capture. The data-center build-out is a precondition for the AI business at frontier scale, and the data-center build-out is constrained by a U.S. electrical grid that has not added a major transmission line in twenty years. The constraint is physical. It cannot be relaxed by a price reduction or a marketing campaign. It can only be relaxed by substations, transmission lines, and — at the upper end — nuclear restarts that take years to commission. The 2026 IPO class is selling a future in which the bottleneck is overcome. The price of admission to that future is denominated in electrons the grid has not yet learned to deliver.

Oura is the easier story, and it is worth understanding because it is the one the prospectus will not try to hide. Oura makes a ring. Inside the ring are several infrared LEDs, a red LED, a photodiode, an NTC temperature sensor, and a three-axis accelerometer. The infrared photoplethysmography — flashing LEDs into the skin and reading what bounces back — measures heart rate and, with a little statistical inference, heart-rate variability, which is a real physiological signal correlated with recovery and stress. The temperature sensor measures skin temperature, which drifts with circadian rhythm and, in women, with menstrual cycle. The accelerometer measures motion, from which the firmware infers sleep stages — wake, light, deep, REM — at accuracies that, in published validation studies, hover around 65 percent agreement with a polysomnography sleep lab. That is better than a coin flip by a useful margin, and worse than a clinical instrument by enough that no clinician should make a diagnosis on the basis of the ring.

What the ring sells to the customer is the ring plus a subscription. The hardware runs from about $300 for the base model to $400-plus for premium finishes. The subscription — Oura Ring Membership, roughly six dollars a month — unlocks the long-term trend lines and the readiness, sleep, and resilience scores that the company publishes daily. The business model is the funnel-and-LTV pattern that any subscription software company recognizes: sell the device cheap, make the recurring fee do the work. The data generated by the ring is technically the company's most valuable asset, though Oura has been notably careful about how it monetizes that data, having faced a class-action and regulatory complaints over health-data sharing several years ago. The current prospectus story, to the extent one can be inferred from the company's investor materials, is hardware plus subscription, with an option value on data that the company has chosen not to exercise aggressively.

The fitness-tracking ring is not a status symbol, although it functions as one in the financial-executive class that the original press coverage singled out. It is a consumer-electronics device with a subscription business model layered on top, competing with the Apple Watch, Whoop, Garmin, and Samsung Galaxy Ring in a category where the differentiation has converged on the same handful of physiological signals and proprietary scoring algorithms. Oura's ring is a real product with real engineering, real customers, and a real subscription business. It is also the company in the 2026 IPO queue whose economics most closely resemble a normal hardware business. Whether it deserves a valuation well above the $11 billion private-round mark is a question the public market will be asked to defend.

Traditional U.S. IPOs have already raised $137 billion in 2026, per Dealogic, putting the year on pace to top the prior record of roughly $156 billion set in 2021. Companies that went public in 2026 are trading up 21 percent on average from their IPO prices, also per Dealogic. That is the figure the sponsors selling the second-half pipeline are leaning on. It is also a figure measured in weeks. The 2021 cohort finished its first year underwater, with two-thirds of that year's issues trading below their IPO prices, and the survivors have spent five years clawing back. The discipline this time, the sponsors insist, is different. SpaceX priced in June at $86 billion and has since drifted below its IPO price; Jersey Mike's, which Blackstone took public in late July, has had a choppy debut, and the volatility is already tempering the valuations Inspire's backers will accept.

The 2026 cohort and the 2021 cohort are not the same cohort. The 2021 class was dominated by pre-revenue SPACs, EV companies without products, and speculative biotechs whose value rested on FDA decisions that had not been made. The 2026 class has physical assets in the data-center plays, real revenue in Anthropic's case, and a recurring-subscription business at Oura. The engineering dependencies — gigawatts of power, GPU fleets with real depreciation schedules, inference margins that have not been disclosed — are real in a way the 2021 cohort's were not. None of that prevents the 2026 cohort from ending like the 2021 cohort. It only requires that the revenue growth decelerate faster than the cost base, that the inference margins be negative enough to convert gross profit into gross loss, that the data-center build-out run into grid constraints faster than the AI companies can work around them, and that the public-market investors buying the 2026 paper reach a point at which they stop believing that the next training run will produce the capability jump that justifies the multiple.

Whether the engineering reality refutes the bezzle frame or merely specifies its contents depends on what the prospectus discloses. The public-markets regime already in place — the SEC's investor-protection machinery, the materiality standards, the climate-disclosure rule that survived legal challenge — is the venue where inference margins, customer concentration, training-capex schedules, and grid-constraint timelines would either appear or be conspicuous in their absence. A requirement that frontier-model developers disclose gross margin on inference separately from training capex, and that hyperscale data-center operators disclose contracted backlog and grid-interconnection queue position, would resolve most of what the second-half pipeline is currently selling around. The lever exists. Whether the political coalition that would use it is being organized is the question that has not yet been asked in the loud voice the receipts will eventually require.

Earlier coverage at this paper has tracked the build-up: [Anthropic's pitch to prospective investors](/articles/2026-08-11-anthropic-pitches-prospective-investors-ahead-of-planned-ipo/) ahead of its planned offering, and the broader [AI-company rush toward blockbuster listings](/articles/2026-06-04-leading-ai-companies-push-toward-blockbuster-ipos-amid-cash-race/) that has put 2026 on pace to be the year the prior record falls.

There is a phrase for the interval between a deal priced and a deal proved. John Kenneth Galbraith called it the bezzle — the magic interval when a confidence trickster knows he has appropriated the money but the victim does not yet understand he has lost it. The 2026 cohort is in the bezzle.

Cory Doctorow, in his 2024 novel of the same title, took the term as a general theory of tech grift: the gravity-defying interval when Wile E. Coyote runs on air. The engineering substance — the GPU depreciation schedules, the inference margins, the substation build-out queues, the data-center cooling — does not refute the frame. It specifies what would have to be true for the 2026 cohort to prove out, and what would have to be true for the bezzle to collapse. The question is not whether the music stops. The question is whether the receipts, when they arrive, fit the story the second-half pipeline is being sold against.

## Sources

### src_001 — Main Street Independent, other, Tier 1, originating
**Title:** ## Oura, Inspire Brands Among Companies Targeting Fall IPOs
**URL:** https://mainstreetindependent.com/articles/2026-08-25-oura-inspire-brands-among-companies-targeting-fall-ipos/
