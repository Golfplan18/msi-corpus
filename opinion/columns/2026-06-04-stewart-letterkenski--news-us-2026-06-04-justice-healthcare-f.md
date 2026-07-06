---
headline: 'The HealthSplash Racket: Extracting a Billion Without Examining a Patient'
publish_date: '2026-06-04'
lede: Brett Blackman's racket extracted one billion dollars from Medicare without
  examining a patient.
pen_name: stewart-letterkenski
primary_entities: []
primary_themes: []
topic_tags: []
storyline_nexus: []
floor_values_engaged: []
framework_version: 1.1.0
generation_timestamp: '2026-06-05T06:05:46Z'
source_cluster_id: cluster_upi_2026-06-04_-news-us-2026-06-04-justice-healthcare-f
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
image:
  url: /cartoons/the-healthsplash-racket-extracting-a-billion-without.png
  alt: 'Editorial cartoon by Hector Rentier: The HealthSplash Racket: Extracting a
    Billion Without Examining a Patient'
  caption: He billed for a million braces. He never examined a single patient.
  credit: Hector Rentier (Main Street Independent, algorithmic)
  source: ai_generated
  disclosure: AI-generated illustration. Prompt summary and model identifier available
    in metadata.
  ai_model: openrouter:openai/gpt-5.4-image-2
  ai_prompt: 'Single central allegorical figure: Brett Blackman, a middle-aged man
    in business attire, sits at a sleek digital console. His face is fully rendered,
    composed, eyes fixed on a screen displaying a dash'
  license: https://creativecommons.org/publicdomain/zero/1.0/
paired_cartoon:
  pen_name: hector-rentier
  slug: 2026-06-04-hector-paired-with-2026-06-04-stewart-letterkenski--news-us-2026-06-04-justice-healthcare-f
---

![Editorial cartoon by Hector Rentier: The HealthSplash Racket: Extracting a Billion Without Examining a Patient](/cartoons/the-healthsplash-racket-extracting-a-billion-without.png)
*He billed for a million braces. He never examined a single patient.*

Brett Blackman's racket extracted one billion dollars from Medicare without examining a patient.

The Department of Justice secured six convictions for billion-dollar healthcare fraud in three weeks, a result that looks like a victory for the taxpayer until you look at the mechanics. The designation of Vice President JD Vance as the country's fraud czar on April 3, followed by the Justice Department's April 7 announcement of the National Fraud Enforcement Division, is a bureaucratic wrapper designed to make extraction harder to track. The press release is at pains to describe these six convicted operators as isolated bad actors, which is to say the department is framing a systemic architecture flaw as a personnel problem. In the same month, the administration was already walking that logic backward, announcing a $1.3 billion Medicaid deferral to California over its own fraud suspicions, a move detailed in our prior reporting. A czar does not fix architecture; a czar adds a title to the same ledger.

The technical substrate is what matters, not the press conference in Fort Lauderdale. Brett Blackman, founder of HealthSplash, owned the DMERx platform, which routed Medicare beneficiaries to vendors prescribing braces to patients it had never physically examined. His billing platform circumvented physical oversight by allowing the auto-generation of patient profiles and provider referrals that never required a real-time, face-to-face examination, turning the shift to digital-first Medicare intake into a structural loophole for automated theft. The scheme generated more than $1 billion in false billings, of which Medicare paid out more than $450 million. Blackman was convicted of Medicare fraud conspiracy and kickback arrangements. His co-defendant Gary Cox, convicted at a prior trial, received fifteen years. The architecture here is simple: a digital routing layer that converts patient intake forms into claim numbers at machine speed, divorcing the billing code from any verifiable clinical encounter.

This aligns directly with the 2024 CMS Office of Inspector General audit data, which documents how standardized billing codes can be systematically divorced from verifiable service delivery without triggering an automated payment lock. When the payment model rewards quantity of submitted codes rather than quality of verified care, the fraud is not a bug; it is a feature designed by the incentives.

Dr. Violetta Mailya operated on the same register. She collected more than $24 million from Medicare for Botox injections for migraines that she never delivered, including $19 million while her clinic was literally closed. Some claims were backdated to before the patient had even contacted her, a technical manipulation of the service-date field that allowed her to bill for capacity that never existed. Ruby Scott, a nurse operating Delta Home Health Care in Michigan, ran a $1.6 million kickback scheme billing for un-evaluated patient visits. Tony Brown-Arkah in Brooklyn ran an American Medical Centers program where a Florida nurse practitioner signed Suboxone prescriptions remotely, and a van would literally purchase the unused medication from patients who rejected it. Olga Popovych managed physical therapy clinics that paid cash kickbacks to transport drivers to route Medicare patients to her doors. The common denominator across these convictions is never the presence of medical ethics; it is the presence of software and logistics that can process a claim faster than a clinic can produce a therapy session.

Heather Marks, a nurse practitioner at a pain clinic in Carthage, Tennessee, presided over the most material harm of the cluster. She prescribed nearly a million opioid pills to almost a thousand Lifeforce patients, resulting in convictions on eight counts of illegally distributing controlled substances. The clinical injury is the ledger imbalance made physical.

What the DOJ press release carefully omits is that the current focus on "fraud" is a convenient administrative filter for dismantling the reimbursement systems themselves. Conviction data now feeds directly into centralized risk-scoring dashboards, allowing the administration to trigger automatic state-level payment holds without the inconvenience of new legislation. By focusing the public eye on a nurse prescribing a million opioid pills, they provide the aesthetic cover for mass deferrals of Medicaid funding in states that have done nothing but maintain the status quo. You are being asked to cheer as the administration justifies an increasingly expansive freeze on Medicare hospice enrollment and a national "fraud czar" infrastructure by pointing to these specific, high-dollar-amount prosecutions. They are not solving for healthcare efficiency; they are using the existence of the racket as a justification for closing the bank.

The engineer who has built billing systems knows that "fraud" is a management choice, not a crime of nature. You can close off the vectors — require physical examination for durable medical equipment, tighten controls on substance-referral networks, or mandate actual oversight of nurse practitioners — or you can use the existence of fraud as a pretext to starve the entire infrastructure. This administration has chosen the second path. The conviction of Olga Popovych for an $8 million phantom-transport scheme is justice served, in a narrow, prosecutorial sense. But if the goal were protecting the Medicare trust fund, the fraud division would be auditing the software-as-a-service platforms that allow these schemes to scale.

The department's framing of this as a "fraud" problem obscures the engineering reality of the fee-for-service architecture. The technical analysis demonstrates that the extraction mechanism is a rent-extraction layer sitting atop the medical billing system. When platforms — whether they are a telehealth app routing patients to brace vendors or a home-health nurse scheduling zero-evaluation visits — can generate claims that pay out automatically, the system is not failing; it is executing its incentive structure exactly as designed.

The structural remedy is embedded in the payment layer itself. Shifting from fee-for-service to bundled-value care requires open-standards for claims adjudication, meaning the CMS data architecture must function as an API-driven real-time validation layer rather than a legacy public ledger, where zero-clinical-encounter claims trigger automatic audits rather than passive payouts. This rent-extraction layer persists because legacy billing incumbents and hospital lobbying groups actively fortify the current fee-for-service protocol, ensuring the proposed compliance firewall is treated as a systemic disruption to their revenue streams. The interoperability mandate that lets Blackman route patients across platforms must be reversed with a compliance firewall that requires verifiable service dates to clear the payment gateway.

There is a public portal for the new division to receive tips, which opens on June 15. The deadline will pass, as deadlines always do, and the submission records will be processed by the same auditing contractors who have processed them for a decade.

The ledger always balances in these transactions. A bill that arrives for a brace never fitted, or a pill never swallowed, is a receipt for an extraction machine running at full capacity. The only fraud occurring at that velocity is the fiction that a new division title will alter the arithmetic.

---

*Stewart Letterkenski is a heteronym in Main Street Independent's editorial architecture — an analytical voice, not autobiography of any actual person. The position this column expresses is the publication's position on the territory Stewart Letterkenski's lane covers, rendered through Stewart Letterkenski's register.*

*[About Stewart Letterkenski](/advocacy/stewart-letterkenski) · [How the pen names work](/about#how-the-pen-names-work)*
