---
headline: US officials urge encrypted messaging after Chinese telecom hack
publish_date: '2024-12-12'
lede: 'Federal cybersecurity officials urged Americans to use end-to-end encrypted messaging apps after a hacking campaign traced to China exposed the communications of an unknown number of people in the United States. The Cybersecurity and Infrastructure Security Agency released an extensive list of security recommendations for telecom companies — including Verizon and AT&T, which were targeted — including a directive to "ensure that traffic is end-to-end encrypted to the maximum extent possible."


  The guidance applies to ordinary consumers as well as carriers: several widely used messaging apps provide end-to-end encryption by default, while others do not, with significant consequences for who can access message content in transit.'
nut_graf: End-to-end encryption scrambles messages so that only the sender and recipient can read them, blocking telecommunications companies, technology platforms, and intercepting third parties from accessing the content — including in response to law enforcement requests.
primary_entities:
- CISA
- Signal
- WhatsApp
- Telegram
- Apple
- Google
- Meta Platforms
- Pavel Durov
- Verizon
- AT&T
- Samsung
primary_themes:
- cybersecurity
- encryption
- privacy
- telecommunications
- hacking
- China
topic_tags:
  - politics
  - "human interest"
  - "government policy"
  - "economy, business and finance"
  - "construction and property"
storyline_nexus: []
geographic_location: United States
floor_values_engaged:
- value: informed_citizenship
  intensity: 0.85
- value: accountability_of_power
  intensity: 0.55
- value: human_life_and_dignity
  intensity: 0.4
framework_version: 1.1.0
generation_timestamp: '2026-05-16T16:45:55Z'
source_cluster_id: cluster_ap_2026-01-02_privacy-encryption-signal-whatsapp-9faf3
gdelt_event_ids: []
consensus_floor_version: current
publication_mindspec_version: current
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_generated: true
claims:
  count: 18
  hedges:
    appears: 0
    alleged: 0
    attributed: 7
    reported: 5
    contested: 0
    confirmed: 6
  corroboration:
    primary_plus_secondary: 0
    one_originating_plus_primary_document: 0
    primary_document: 6
    single_source: 12
    two_independent: 0
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
image:
  url: /articles/2024-12-12-us-officials-urge-encrypted-messaging-after-chinese-telecom-hack.png
  alt: 'Illustration accompanying article: US officials urge encrypted messaging after Chinese telecom hack'
  source: ai_generated
cross_article_links: []
draft: false
---

Federal cybersecurity officials urged Americans to use end-to-end encrypted messaging apps after a hacking campaign traced to China exposed the communications of an unknown number of people in the United States. The Cybersecurity and Infrastructure Security Agency released an extensive list of security recommendations for telecom companies — including Verizon and AT&T, which were targeted — including a directive to "ensure that traffic is end-to-end encrypted to the maximum extent possible."

The guidance applies to ordinary consumers as well as carriers: several widely used messaging apps provide end-to-end encryption by default, while others do not, with significant consequences for who can access message content in transit.

End-to-end encryption scrambles messages so that only the sender and recipient can read them, blocking telecommunications companies, technology platforms, and intercepting third parties from accessing the content — including in response to law enforcement requests.

## What hackers obtained

Officials said the hackers targeted the metadata of a large number of customers, including information on the dates, times, and recipients of calls and texts. They also obtained the content of texts from a much smaller number of victims, according to the Associated Press.

## Texting: where encryption applies and where it does not

Messages sent between two iPhone users through iMessage are end-to-end encrypted, indicated by blue text bubbles. Android users exchanging messages through Google Messages receive the same protection; a lock icon appears next to each message's timestamp to indicate encryption is active.

The protection breaks down when iPhone and Android users text each other. Those messages travel over Rich Communication Services, an industry standard that replaced older SMS formats but does not provide full end-to-end encryption between platforms. Apple has noted that RCS messages "aren't end-to-end encrypted, which means they're not protected from a third party reading them while they're sent between devices." Samsung flagged the same gap in a press release, noting that "encryption only available for Android to Android communication."

## Encrypted messaging apps

Privacy advocates recommend Signal, a nonprofit-backed app that applies end-to-end encryption to all messages and voice calls. The organization behind Signal has made its source code publicly available for independent security audits and promises never to sell, rent, or lease customer data.

WhatsApp has integrated Signal's encryption protocol, giving its users the same level of security protection. End-to-end encryption is also the default mode for Facebook Messenger, which, like WhatsApp, is owned by Meta Platforms.

Telegram presents a different case. Contrary to widespread perception, the app does not enable end-to-end encryption by default. Users must manually activate the feature through an opt-in "secret chat" function, and that option does not extend to group chats. Cybersecurity experts have warned against using Telegram for private communications. Its founder and chief executive, Pavel Durov, was arrested in France.

## Encrypted calls

Signal and WhatsApp encrypt voice calls using the same technology applied to their messages. iPhone users can also place encrypted calls through FaceTime, while Android owners have the option of Google Fi. In each case, the person on the other end must also use the same service for the protection to apply.

Both Signal and WhatsApp allow users to hide their IP address during calls, which prevents their approximate location from being determined.

## Atomic claims

### c_001 — reported, single source
**Subject entities:** China
**Predicate:** exposed
**Object:** communications of Americans via US telecom networks (data_breach)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> A hacking campaign originating in China exposed the communications of an unknown number of Americans.

### c_002 — confirmed, primary document
**Subject entities:** CISA; Verizon; AT&T
**Predicate:** issued_guidance_to
**Object:** US telecom companies (organization_group)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Federal cybersecurity authorities released security recommendations for US telecom companies including Verizon and AT&T that were targeted by the hacking campaign.

### c_003 — confirmed, primary document
**Subject entities:** CISA
**Predicate:** recommended
**Object:** end-to-end encryption for carrier traffic (security_recommendation)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> The federal guidance recommended that carriers 'ensure that traffic is end-to-end encrypted to the maximum extent possible.'

### c_004 — reported, single source
**Subject entities:** China
**Predicate:** accessed
**Object:** customer metadata including call and text records (data)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Hackers targeted the metadata of a large number of customers, including information on the dates, times, and recipients of calls and texts.

### c_005 — reported, single source
**Subject entities:** China
**Predicate:** accessed
**Object:** text message content from a smaller number of victims (data)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Hackers also obtained the content of texts from a much smaller number of victims.

### c_006 — confirmed, primary document
**Subject entities:** Apple; iMessage
**Predicate:** provides
**Object:** end-to-end encryption for iPhone-to-iPhone messages (security_feature)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Messages between two iPhone users through iMessage are end-to-end encrypted, indicated by blue text bubbles.

### c_007 — confirmed, primary document
**Subject entities:** Google Messages; Android
**Predicate:** provides
**Object:** end-to-end encryption for Android-to-Android messages (security_feature)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Android users sending messages through Google Messages receive end-to-end encryption, indicated by a lock icon next to each message timestamp.

### c_008 — confirmed, primary document
**Subject entities:** Apple; RCS
**Predicate:** stated
**Object:** RCS messages lack end-to-end encryption (security_limitation)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Apple has stated that RCS messages 'aren't end-to-end encrypted, which means they're not protected from a third party reading them while they're sent between devices.'

### c_009 — confirmed, primary document
**Subject entities:** Samsung
**Predicate:** stated
**Object:** cross-platform RCS messages lack encryption (security_limitation)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Samsung noted in a press release that encryption for its Android phones is 'only available for Android to Android communication.'

### c_010 — attributed, single source
**Subject entities:** Signal
**Predicate:** provides
**Object:** end-to-end encryption and open-source auditable code (security_feature)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Signal applies end-to-end encryption to all messages and voice calls, and the nonprofit behind it has made its source code publicly available for independent auditing.

### c_011 — attributed, single source
**Subject entities:** WhatsApp; Signal
**Predicate:** uses
**Object:** Signal encryption protocol (security_technology)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> WhatsApp has integrated Signal's encryption protocol, providing its users the same level of security protection.

### c_012 — attributed, single source
**Subject entities:** Facebook Messenger; Meta Platforms
**Predicate:** has_as_default
**Object:** end-to-end encryption (security_feature)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> End-to-end encryption is the default mode for Facebook Messenger, which is owned by Meta Platforms.

### c_013 — reported, single source
**Subject entities:** Telegram
**Predicate:** lacks
**Object:** default end-to-end encryption (security_limitation)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Telegram does not enable end-to-end encryption by default; the feature is available only through an opt-in 'secret chat' function that does not work in group chats.

### c_014 — attributed, single source
**Subject entities:** Telegram
**Predicate:** warned_against
**Object:** using Telegram for private communications (security_recommendation)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Cybersecurity experts have warned against using Telegram for private communications.

### c_015 — reported, single source
**Subject entities:** Pavel Durov; Telegram
**Predicate:** was_arrested_in
**Object:** France (place)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Telegram founder and CEO Pavel Durov was arrested in France.

### c_016 — attributed, single source
**Subject entities:** Signal; WhatsApp
**Predicate:** encrypt
**Object:** voice calls (communication_type)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Signal and WhatsApp encrypt voice calls using the same technology applied to their messages.

### c_017 — attributed, single source
**Subject entities:** Apple; FaceTime; Google Fi
**Predicate:** provide
**Object:** end-to-end encrypted voice calls (security_feature)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> iPhone users can use FaceTime for encrypted calls; Android owners can use Google Fi, both of which are end-to-end encrypted.

### c_018 — attributed, single source
**Subject entities:** Signal; WhatsApp
**Predicate:** allow
**Object:** IP address hiding during calls (privacy_feature)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Signal and WhatsApp allow users to hide their IP address during calls to prevent their general location from being approximated.

## Sources

### src_001 — Associated Press, wire, Tier 1, originating
**Author:** Kelvin Chan
**Publication date:** 2024-12-12
**Access date:** 2024-12-12
**Title:** One Tech Tip: How to protect your communications through encryption
**URL:** https://apnews.com/article/privacy-encryption-signal-whatsapp-9faf31ed3411bc5b7cab0647b4ab224d

---

*This article was generated algorithmically by Main Street Independent's News Article Generator framework from the public sources listed above. [Methodology](/methodology). Published under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).*
