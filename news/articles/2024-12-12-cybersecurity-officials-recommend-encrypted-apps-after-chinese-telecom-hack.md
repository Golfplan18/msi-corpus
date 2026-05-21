---
headline: Cybersecurity officials recommend encrypted apps after Chinese telecom hack
publish_date: '2024-12-12'
lede: 'U.S. cybersecurity officials are advising Americans to use end-to-end encrypted messaging after a hacking campaign originating in China exposed the communications of an unknown number of people. Federal authorities released security recommendations for telecom companies including Verizon and AT&T, with guidance that applies to any phone user: "Ensure that traffic is end-to-end encrypted to the maximum extent possible."'
nut_graf: 'The recommendation signals a shift in the federal government''s posture: law enforcement had long resisted end-to-end encryption because it prevents technology companies from handing messages over to investigators, but officials now say the protections are essential for ordinary consumers.'
primary_entities:
- Signal
- WhatsApp
- Telegram
- Pavel Durov
- Meta Platforms
primary_themes:
- cybersecurity
- encryption
- privacy
- China hacking
- telecommunications
topic_tags:
  - "science and technology"
  - "technology and engineering"
storyline_nexus: []
geographic_location: United States
floor_values_engaged:
- value: informed_citizenship
  intensity: 0.85
- value: accountability_of_power
  intensity: 0.55
framework_version: 1.1.0
generation_timestamp: '2026-05-16T00:00:00Z'
source_cluster_id: cluster_ap_2026-01-02_privacy-encryption-signal-whatsapp-9faf3
gdelt_event_ids: []
consensus_floor_version: current
publication_mindspec_version: current
license: https://creativecommons.org/publicdomain/zero/1.0/
ai_generated: true
claims:
  count: 16
  hedges:
    appears: 0
    alleged: 0
    attributed: 5
    reported: 1
    contested: 0
    confirmed: 10
  corroboration:
    primary_plus_secondary: 0
    one_originating_plus_primary_document: 0
    primary_document: 0
    single_source: 16
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
  url: /articles/2024-12-12-cybersecurity-officials-recommend-encrypted-apps-after-chinese-telecom-hack.png
  alt: 'Illustration accompanying article: Cybersecurity officials recommend encrypted apps after Chinese telecom hack'
  source: ai_generated
cross_article_links:
- slug: 2024-12-12-us-officials-urge-encrypted-messaging-after-chinese-telecom-hack
  relation: continues
  strength: 1.0
  confidence: high
draft: false
---

U.S. cybersecurity officials are advising Americans to use end-to-end encrypted messaging after a hacking campaign originating in China exposed the communications of an unknown number of people. Federal authorities released security recommendations for telecom companies including Verizon and AT&T, with guidance that applies to any phone user: "Ensure that traffic is end-to-end encrypted to the maximum extent possible."

The recommendation signals a shift in the federal government's posture: law enforcement had long resisted end-to-end encryption because it prevents technology companies from reading messages or responding to law enforcement requests, but officials now say the protections are essential for ordinary consumers.

As MSI previously reported, the breach prompted federal authorities to advise Americans to shift toward encrypted communications platforms — <a href="/articles/2024-12-12-us-officials-urge-encrypted-messaging-after-chinese-telecom-hack">details of that advisory are available here</a>.

## What end-to-end encryption does

End-to-end encryption, also known as E2EE, means that messages are scrambled so that only the sender and recipient can see them. Anyone who intercepts the message sees only a garble that cannot be unscrambled without the key.

Officials said the hackers targeted the metadata of a large number of customers, including information on the dates, times, and recipients of calls and texts. They also managed to see the content from texts from a much smaller number of victims.

## Texting: when messages are and are not protected

iPhone users texting other iPhone users are covered. Blue text bubbles indicate iMessages, which are end-to-end encrypted. Android users sending texts through Google Messages will see a lock next to the timestamp on each message when encryption is active.

The protection breaks down when iPhones and Android devices exchange messages. Those texts travel over Rich Communication Services, an industry standard that replaces older SMS and MMS formats. Apple has noted that RCS messages "aren't end-to-end encrypted, which means they're not protected from a third party reading them while they're sent between devices."

## Chat apps: Signal, WhatsApp, and Facebook Messenger

Privacy advocates recommend encrypted messaging apps to avoid the cross-platform gap. Signal applies end-to-end encryption on all messages and voice calls. The independent nonprofit behind the app has made its source code publicly available so that it can be audited by anyone for security and correctness.

WhatsApp uses Signal's encryption protocol, giving its much larger user base the same level of protection. End-to-end encryption is also the default mode for Facebook Messenger, which, like WhatsApp, is owned by Meta Platforms.

## Telegram: a common misconception

Telegram does not turn on end-to-end encryption by default. Users must switch on the option manually, and it does not work with group chats. Cybersecurity experts have warned against using Telegram for private communications. The app's only E2EE option is an opt-in feature called "secret chat." Telegram has also drawn scrutiny for hosting criminal activity; its founder and CEO, Pavel Durov, was arrested in France.

## Voice calls

Signal and WhatsApp encrypt voice calls with the same technology they use for messages. iPhone users can also use FaceTime, and Android users can use Google Fi — both are end-to-end encrypted. The requirement in all cases is that the person on the other end must also have the same app or service installed.

Signal and WhatsApp users can customize privacy settings to hide their IP address during calls, preventing their general location from being inferred.

## Atomic claims

### c_001 — attributed, single source
**Subject entities:** US cybersecurity officials
**Predicate:** advised
**Object:** use encryption (recommendation)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> U.S. cybersecurity officials advised people to use encryption in their communications after a hacking campaign originating in China.

### c_002 — confirmed, single source
**Subject entities:** US federal cybersecurity authorities; Verizon; AT&T
**Predicate:** released
**Object:** security recommendations (government_action)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Federal cybersecurity authorities released security recommendations for U.S. telecom companies including Verizon and AT&T.

### c_003 — attributed, single source
**Subject entities:** hackers
**Predicate:** targeted
**Object:** call and text metadata (data)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> The hacking campaign targeted the metadata of a large number of customers, including information on the dates, times, and recipients of calls and texts.

### c_004 — attributed, single source
**Subject entities:** hackers
**Predicate:** accessed
**Object:** text content (data)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Hackers managed to see the content of texts from a much smaller number of victims.

### c_005 — attributed, single source
**Subject entities:** law enforcement officials
**Predicate:** resisted
**Object:** end-to-end encryption (policy_position)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Law enforcement officials had resisted end-to-end encryption because it prevents technology companies from reading messages or responding to law enforcement requests.

### c_006 — confirmed, single source
**Subject entities:** Apple; iMessage
**Predicate:** encrypts
**Object:** iPhone-to-iPhone messages (technical_fact)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> iPhone-to-iPhone iMessages are end-to-end encrypted, indicated by blue text bubbles.

### c_007 — confirmed, single source
**Subject entities:** Google Messages
**Predicate:** displays
**Object:** lock icon indicating encryption (technical_fact)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Android users sending texts through Google Messages receive a lock next to the timestamp indicating encryption is on.

### c_008 — attributed, single source
**Subject entities:** Apple; RCS
**Predicate:** stated
**Object:** RCS messages not E2EE (technical_fact)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Apple has stated that RCS messages between iPhones and Android devices are not end-to-end encrypted.

### c_009 — confirmed, single source
**Subject entities:** Signal
**Predicate:** applies
**Object:** E2EE on all messages and calls (technical_fact)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Signal applies end-to-end encryption on all messages and voice calls and has made its source code publicly available.

### c_010 — confirmed, single source
**Subject entities:** WhatsApp; Signal
**Predicate:** uses
**Object:** Signal encryption protocol (technical_fact)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> WhatsApp uses Signal's encryption protocol, providing the same level of security protection.

### c_011 — confirmed, single source
**Subject entities:** Facebook Messenger; Meta Platforms
**Predicate:** defaults_to
**Object:** E2EE (technical_fact)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> End-to-end encryption is the default mode for Facebook Messenger, which is owned by Meta Platforms.

### c_012 — confirmed, single source
**Subject entities:** Telegram
**Predicate:** does_not_default_to
**Object:** E2EE (technical_fact)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Telegram does not turn on end-to-end encryption by default; only its opt-in 'secret chat' feature is end-to-end encrypted.

### c_013 — confirmed, single source
**Subject entities:** Telegram
**Predicate:** lacks
**Object:** E2EE for group chats (technical_fact)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Telegram's end-to-end encryption does not work with group chats.

### c_014 — reported, single source
**Subject entities:** Pavel Durov; Telegram
**Predicate:** arrested
**Object:** France (location)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Telegram founder and CEO Pavel Durov was arrested in France.

### c_015 — confirmed, single source
**Subject entities:** FaceTime; Google Fi
**Predicate:** encrypts
**Object:** voice calls (technical_fact)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> FaceTime on iPhone and Google Fi on Android are both end-to-end encrypted for voice calls.

### c_016 — confirmed, single source
**Subject entities:** Signal; WhatsApp
**Predicate:** allow
**Object:** IP address hiding during calls (technical_feature)
**Temporal:** 2024-12-12
**Source IDs:** src_001

> Signal and WhatsApp allow users to hide their IP address during calls to prevent their general location from being guessed.

## Sources

### src_001 — Associated Press, wire, Tier 1, originating
**Author:** Kelvin Chan
**Publication date:** 2024-12-12
**Access date:** 2024-12-12
**Title:** One Tech Tip: How to protect your communications through encryption
**URL:** https://apnews.com/article/privacy-encryption-signal-whatsapp-9faf31ed3411bc5b7cab0647b4ab224d

---

*This article was generated algorithmically by Main Street Independent's News Article Generator framework from the public sources listed above. [Methodology](/methodology). Published under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).*
