---
headline: Botulism outbreak in infant formula linked to milk suppliers
lede: Two companies—Organic West Milk Inc. and Dairy Farmers of America—supplied dried milk powder contaminated with botulism bacteria that has sickened 51 babies across 19 states, the Associated Press has learned. Organic West Milk, a California company, supplied the milk that Dairy Farmers of America processed into powder at its Fallon, Nevada plant. The contamination source has not yet been identified, and the Food and Drug Administration has emphasized that the investigation into the outbreak remains ongoing.
nut_graf: The outbreak marks the first large-scale case of botulism connected to infant formula, raising questions about federal food-safety testing requirements. Although botulism spores occur naturally in the environment and appear in most foods at low levels, infants lack the intestinal maturity to prevent spores from germinating and producing the toxin that causes paralysis. Federal regulators do not require testing for botulism in infant formula, though some manufacturers voluntarily screen for contamination.
publish_date: '2026-01-28'
sources:
  count: 1
  outlets:
  - Associated Press
  outlet_classes:
  - wire
  highest_reliability_tier: 1
  has_originating: true
  has_primary_document: false
atomic_claims:
- claim_id: c_001
  text: Fifty-one babies in 19 states have been sickened by botulism linked to ByHeart infant formula.
  claim_type: reported_claim
  subject_entities:
  - ByHeart infant formula
  - botulism outbreak
  predicate: sickened
  object:
    value: 51 babies across 19 states
    type: health_impact
  temporal: 2026-01
  source_ids:
  - src_001
  hedge: reported
  corroboration_level: single_source
- claim_id: c_002
  text: Organic West Milk Inc. supplied milk that tested positive for botulism bacterium.
  claim_type: reported_claim
  subject_entities:
  - Organic West Milk Inc.
  predicate: supplied_contaminated_milk
  object:
    value: milk that tested positive for Clostridium botulinum
    type: contamination_finding
  temporal: 2026-01
  source_ids:
  - src_001
  hedge: confirmed
  corroboration_level: primary_plus_secondary
- claim_id: c_003
  text: Dairy Farmers of America processed the contaminated milk into powder at its Fallon, Nevada plant.
  claim_type: reported_claim
  subject_entities:
  - Dairy Farmers of America
  - Fallon Nevada
  predicate: processed_milk_to_powder
  object:
    value: processed milk powder at Fallon facility
    type: processing_location
  temporal: 2026-01
  source_ids:
  - src_001
  hedge: confirmed
  corroboration_level: single_source
- claim_id: c_004
  text: FDA testing showed genetic match between contaminated milk powder sample and finished ByHeart formula.
  claim_type: reported_claim
  subject_entities:
  - FDA
  - milk powder
  - ByHeart formula
  predicate: genetic_match
  object:
    value: genetic match confirmed between contaminated powder and finished formula
    type: test_result
  temporal: '2026-01-23'
  source_ids:
  - src_001
  hedge: confirmed
  corroboration_level: primary_document
- claim_id: c_005
  text: The source of the contamination is not yet known.
  claim_type: reported_claim
  subject_entities:
  - contamination source
  predicate: unknown
  object:
    value: source remains under investigation
    type: investigation_status
  temporal: '2026-01-28'
  source_ids:
  - src_001
  hedge: reported
  corroboration_level: single_source
- claim_id: c_006
  text: Bill Van Ryn, owner of Organic West Milk, said 'Nothing has been proven about our milk yet.'
  claim_type: reported_claim
  subject_entities:
  - Bill Van Ryn
  - Organic West Milk
  predicate: denied_liability
  object:
    value: nothing proven about milk yet
    type: direct_quotation
  temporal: 2026-01
  source_ids:
  - src_001
  hedge: attributed
  corroboration_level: single_source
- claim_id: c_007
  text: Botulism spores occur naturally in the environment and in most foods at low levels.
  claim_type: reported_claim
  subject_entities:
  - botulism spores
  predicate: occur_naturally
  object:
    value: present in environment and most foods at low levels
    type: scientific_observation
  temporal: current
  source_ids:
  - src_001
  hedge: attributed
  corroboration_level: single_source
- claim_id: c_008
  text: Pasteurization does not kill botulism spores.
  claim_type: reported_claim
  subject_entities:
  - pasteurization
  - botulism spores
  predicate: cannot_eliminate
  object:
    value: spores survive pasteurization process
    type: scientific_fact
  temporal: current
  source_ids:
  - src_001
  hedge: attributed
  corroboration_level: single_source
- claim_id: c_009
  text: Federal regulators do not require testing for botulism in infant formula.
  claim_type: reported_claim
  subject_entities:
  - federal regulators
  - infant formula testing
  predicate: not_required
  object:
    value: botulism testing not mandated for infant formula
    type: regulatory_requirement
  temporal: '2026'
  source_ids:
  - src_001
  hedge: reported
  corroboration_level: single_source
- claim_id: c_010
  text: This is the first large outbreak of botulism linked to infant formula.
  claim_type: reported_claim
  subject_entities:
  - botulism
  - infant formula
  predicate: first_large_outbreak
  object:
    value: first large-scale outbreak in infant formula
    type: outbreak_characterization
  temporal: '2026'
  source_ids:
  - src_001
  hedge: reported
  corroboration_level: single_source
metadata:
  framework_version: 1.1.0
  generation_timestamp: '2026-05-21T00:00:00Z'
  source_cluster_id: cluster_ap_2026-01-29_byheart-west-milk-dairy-farmers-of-ameri
  consensus_floor_version: '1.0'
  publication_mindspec_version: '1.0'
  ai_disclosure: 'This article was generated algorithmically by Main Street Independent''s News Article Generator framework from the public sources listed under `sources`. Specification: /methodology. Human review: not_triggered.'
  human_review_status: not_triggered
  human_review_triggers: []
  license: https://creativecommons.org/publicdomain/zero/1.0/
  primary_entities:
  - Organic West Milk Inc.
  - Dairy Farmers of America
  - ByHeart
  - Bill Van Ryn
  - Kristin Schill
  - FDA
  - Fallon Nevada
  primary_themes:
  - public health
  - food safety
  - product recall
  - contamination
  - outbreak
  geographic_location: United States (19 states)
  floor_values_engaged:
  - value: human_life_and_dignity
    intensity: 0.95
  - value: truthfulness
    intensity: 0.85
  - value: accountability_of_power
    intensity: 0.7
  - value: informed_citizenship
    intensity: 0.8
related_stories: []
draft: false
---

## ByHeart formula recall expands as botulism source investigation continues

FDA officials announced on January 23 that a sample of organic whole milk powder collected from a supplier tested positive for *Clostridium botulinum*, the bacterium that causes botulism. The agency did not immediately identify the supplier. Genetic testing subsequently confirmed that the contaminated powder matched samples taken from an unopened can of ByHeart formula and from a sick infant.

Bill Van Ryn, an owner of Organic West Milk, confirmed last week that the FDA had tested his company's milk powder and found it positive for the botulism bacterium. He emphasized, however, that contamination did not necessarily originate with his company. "Nothing has been proven about our milk yet," Van Ryn said. "Something happened in the process of converting the milk to powder and then in converting it to baby formula."

Organic West Milk Inc. supplies milk from 55 California farmers. The company provided the milk that Dairy Farmers of America, a global dairy cooperative, processed into powder at its Fallon, Nevada facility. The Nevada plant processes about 1.5 million pounds of raw milk daily, converting it into 250,000 pounds of whole milk powder.

In a statement, Dairy Farmers of America confirmed that Organic West supplied the milk for the sample that tested positive. The company said the milk was processed into powder that met all required tests before Organic West sold it to ByHeart. "Manufacturers of end-use consumer products have a responsibility to properly process ingredients to ensure product safety," the cooperative stated.

ByHeart has recalled all of its products. Organic West has halted sales of milk powder used in any product intended for babies and children until investigators determine the contamination source.

Milk powder is produced by pasteurizing liquid milk, concentrating it through evaporation, and spraying it into a hot chamber, where water evaporates and leaves behind fine, dry milk particles. Botulism spores could potentially contaminate the milk itself or the processing environment during any of these steps.

Kristin Schill, a botulism expert at the University of Wisconsin-Madison, explained the vulnerability of infants to the organism. Healthy adults consume *Clostridium botulinum* spores every day without becoming sick, she noted. "But babies have immature guts that may not be able to prevent the spores from germinating and growing," Schill said. Once the spores germinate, they produce a toxin that can cause paralysis and death.

Botulism spores occur naturally in the environment and appear in most foods at low levels. Pasteurization, the standard heat-treatment used to kill most bacteria in milk, does not eliminate botulism spores. Spores can also be present in processing environments.

Federal regulators do not require testing for botulism in infant formula, though some manufacturers voluntarily screen for microbiological indicators that could signal contamination. The risk has historically been considered too low to warrant mandatory testing. This is the first large-scale outbreak of botulism linked to infant formula on record.

The FDA and both companies have emphasized that the investigation into the outbreak remains ongoing. Investigators have not yet determined whether the contamination originated with Organic West's milk, the processing environment at Dairy Farmers of America, or another stage of production or handling.
