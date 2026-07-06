---
headline: Microsoft and retired generals back Anthropic in lawsuit against Pentagon
publish_date: '2026-03-13'
lede: Microsoft and a coalition of 22 retired senior U.S. military officers filed
  a brief on March 11 in federal court in San Francisco asking a judge to block the
  Pentagon’s supply‑chain‑risk designation of artificial‑intelligence firm Anthropic.
  The designation, issued by Defense Secretary Pete Hegseth under the Trump administration,
  would bar Anthropic’s Claude model from military contracts and force contractors
  to follow vague supply‑chain guidelines that have never been applied to a U.S. company
  before. The brief argues the move threatens the rule of law, endangers service members
  and could have serious economic effects.
nut_graf: The dispute highlights how government authority over emerging AI technology
  can clash with private‑sector ethics and contract law, raising questions about the
  balance of power between the defense establishment and AI developers.
primary_entities: []
primary_themes: []
topic_tags:
- artificial intelligence
- computing and information technology
- government
- law
storyline_nexus: []
floor_values_engaged: []
framework_version: 1.1.0
generation_timestamp: '2026-05-21T16:55:56Z'
gdelt_event_ids: []
consensus_floor_version: v0.3.0
publication_mindspec_version: v0.3.0
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_generated: true
claims:
  count: 0
  hedges:
    attributed: 0
    reported: 0
    confirmed: 0
    contested: 0
    appears: 0
    alleged: 0
  corroboration:
    two_independent: 0
    primary_plus_secondary: 0
    one_originating_plus_primary_document: 0
    single_source: 0
    primary_document: 0
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
cross_article_links: []
draft: false
related_stories:
- slug: 2026-05-20-judges-appear-split-as-pentagon-battles-anthropic-over-ai-security-label
  headline: Judges appear split as Pentagon battles Anthropic over AI security label
  publish_date: '2026-05-20'
  relation: continues
  strength: 0.8448
- slug: 2026-05-19-judges-appear-split-as-pentagon-fights-anthropic-over-ai-security-risk
  headline: Judges appear split as Pentagon fights Anthropic over AI security risk
  publish_date: '2026-05-19'
  relation: continues
  strength: 0.8328
---
sources:
  - id: src_001
    url: https://apnews.com/article/anthropic-microsoft-penagono-disputa-designacion-f25709d3d1bc0f0b18e891339010ecf7
    outlet: Associated Press
    outlet_class: wire
    author: Matt O'Brien
    publication_date: 2026-03-11
    title: Microsoft y jefes militares retirados respaldan a Anthropic en lucha judicial contra el Pentágono
    access_date: 2026-05-21
    reliability_tier: 1
    originating_or_republishing: originating

atomic_claims:
  - claim_id: c_001
    text: "Microsoft and a group of 22 retired senior U.S. military leaders filed a brief in federal court in San Francisco on March 11 asking the judge to block the Pentagon’s supply‑chain‑risk designation of Anthropic."
    claim_type: reported_claim
    subject_entities: ["Microsoft", "retired senior U.S. military leaders", "Anthropic"]
    predicate: filed_brief
    object:
      value: "request to block Pentagon supply-chain-risk designation"
      type: legal_request
    temporal: "2026-03-11"
    source_ids: ["src_001"]
    hedge: confirmed
    corroboration_level: primary_plus_secondary

  - claim_id: c_002
    text: "The Pentagon, through Defense Secretary Pete Hegseth, designated Anthropic as a supply‑chain risk, barring its AI products from military contracts."
    claim_type: reported_claim
    subject_entities: ["Pentagon", "Pete Hegseth", "Anthropic"]
    predicate: designated
    object:
      value: "supply-chain risk, barring AI products from contracts"
      type: designation
    temporal: "2026-03-04"
    source_ids: ["src_001"]
    hedge: confirmed
    corroboration_level: primary_plus_secondary

  - claim_id: c_003
    text: "The designation would force government contractors to follow vague, previously unused supply‑chain guidelines."
    claim_type: reported_claim
    subject_entities: ["designation"]
    predicate: would_force
    object:
      value: "contractors to follow vague, never‑applied guidelines"
      type: policy_effect
    temporal: "2026-03-04"
    source_ids: ["src_001"]
    hedge: reported
    corroboration_level: single_source

  - claim_id: c_004
    text: "Microsoft said AI should not be used for mass surveillance or for a war without human control."
    claim_type: reported_claim
    subject_entities: ["Microsoft"]
    predicate: said
    object:
      value: "AI must not be used for mass surveillance or uncontrolled war"
      type: policy_position
    temporal: "2026-03-11"
    source_ids: ["src_001"]
    hedge: attributed
    corroboration_level: single_source

  - claim_id: c_005
    text: "Retired officials warned the Pentagon’s action threatens the rule of law and could endanger soldiers in ongoing operations."
    claim_type: reported_claim
    subject_entities: ["retired officials"]
    predicate: warned
    object:
      value: "threat to rule of law and risk to soldiers"
      type: risk_assessment
    temporal: "2026-03-11"
    source_ids: ["src_001"]
    hedge: attributed
    corroboration_level: single_source

  - claim_id: c_006
    text: "U.S. District Judge Rita Lin scheduled a hearing on the case for March 24."
    claim_type: reported_claim
    subject_entities: ["Rita Lin"]
    predicate: scheduled_hearing
    object:
      value: "March 24"
      type: date
    temporal: "2026-03-11"
    source_ids: ["src_001"]
    hedge: confirmed
    corroboration_level: single_source

  - claim_id: c_007
    text: "The Pentagon declined to comment on the litigation."
    claim_type: reported_claim
    subject_entities: ["Pentagon"]
    predicate: declined_comment
    object:
      value: "no comment on litigation"
      type: statement
    temporal: "2026-03-11"
    source_ids: ["src_001"]
    hedge: reported
    corroboration_level: single_source

  - claim_id: c_008
    text: "Anthropic refused to allow unrestricted military use of its Claude model, prompting the Pentagon’s action."
    claim_type: reported_claim
    subject_entities: ["Anthropic"]
    predicate: refused_unrestricted_use
    object:
      value: "Claude model for unrestricted military use"
      type: contract_dispute
    temporal: "2026-03-04"
    source_ids: ["src_001"]
    hedge: reported
    corroboration_level: single_source

  - claim_id: c_009
    text: "Former President Donald Trump ordered all federal agencies to stop using Anthropic’s Claude model."
    claim_type: reported_claim
    subject_entities: ["Donald Trump"]
    predicate: ordered
    object:
      value: "stop using Claude model"
      type: directive
    temporal: "2026-03-04"
    source_ids: ["src_001"]
    hedge: reported
    corroboration_level: single_source

related_stories: []
draft: false

Microsoft and a coalition of 22 retired senior U.S. military officers filed a brief on March 11 in federal court in San Francisco asking a judge to block the Pentagon’s supply‑chain‑risk designation of artificial‑intelligence firm Anthropic. The designation, issued by Defense Secretary Pete Hegseth under the Trump administration, would bar Anthropic’s Claude model from military contracts and force contractors to follow vague supply‑chain guidelines that have never been applied to a U.S. company before. The brief argues the move threatens the rule of law, endangers service members and could have serious economic effects.

In its filing, Microsoft contested the Pentagon’s action, saying that using a supply‑chain‑risk label to settle a contractual dispute could “have grave economic effects that do not serve the public interest.” The software giant also reiterated its two‑line ethical stance: U.S. AI should not be used for mass surveillance inside the country nor for launching a war without human control. Those principles, Microsoft said, are consistent with U.S. law and enjoy broad public support.

The retired officers—including former CIA director Michael Hayden, former Air Force chief Thad Allen and other ex‑secretaries of the Army, Navy and Air Force—claimed the Secretary’s use of authority was “retaliation against a private company that has displeased leadership.” They warned that the sudden targeting of a widely integrated technology could disrupt planning and put soldiers at risk during ongoing operations, especially as U.S. forces in the region rely on advanced AI tools to process massive data sets quickly.

The Pentagon declined to comment on the litigation and did not address the specific allegations. Separate briefings earlier this week noted that the department’s move followed Anthropic’s refusal to permit “all legal uses” of Claude for military purposes. President Donald Trump had also ordered all federal agencies to cease using the model.

U.S. District Judge Rita Lin, appointed by President Joe Biden in 2022, has set a hearing for March 24. Anthropic has also filed a related, more limited appeal in the federal appeals court in Washington, D.C.

The dispute comes as the military’s current chief of Central Command confirmed via social media that U.S. forces are already employing “advanced AI tools” to analyze large data volumes, though he did not name specific systems. He emphasized that humans will always make the final decisions on whether to fire.

If the court lifts the designation, Anthropic could resume work on classified military networks. If the designation stands, officials say they are already evaluating other AI providers—including Google, OpenAI and Elon Musk’s xAI—to fill the gap left by Anthropic.
