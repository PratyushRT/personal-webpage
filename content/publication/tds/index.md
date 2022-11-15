---
title: "Time-Deniable Signatures"
date: "2022-09-11T12:08:02+05:30"
publication_types: ["3"]
publication: in IACR eprint
abstract: "In this work we propose time-deniable signatures (TDS), a new primitive that facilitates deniable authentication in protocols such as DKIM-signed email. As with traditional signatures, TDS provide strong authenticity for message content, at least for a sender-chosen period of time. Once this time period has elapsed, however, time-deniable signatures can be forged by any party who obtains a signature. This forgery property ensures that signatures serve a useful authentication purpose for a bounded time period, while also allowing signers to plausibly disavow the creation of older signed content. Most critically, and unlike many past proposals for deniable authentication, TDS do not require interaction with the receiver or the deployment of any persistent cryptographic infrastructure or services beyond the signing process (e.g., APIs to publish secrets or author timestamp certificates.) We first investigate the security definitions for time-deniability, demonstrating that past definitional attempts are insufficient (and indeed, allow for broken signature schemes.) We then propose an efficient construction of TDS based on well-studied assumptions."
---
