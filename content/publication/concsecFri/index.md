---
title: "On the Concrete Security of Non-interactive FRI"
date: "2024-07-11T12:08:02"
publication_types: ["1"]
publication: "in SCN '24"
abstract: "FRI is a cryptographic protocol widely deployed today as a building
block of many efficient SNARKs that help secure transactions of hundreds of
millions of dollars per day. The Fiat-Shamir security of FRI—vital for understanding
the security of FRI-based SNARKs—has only recently been formalized and
established by Block et al. (ASIACRYPT ’23).

In this work, we complement the result of Block et al. by providing a thorough
concrete security analysis of non-interactive FRI under various parameter settings
from protocols deploying (or soon to be deploying) FRI today. We find that these
parameters nearly achieve their desired security targets (being at most 1-bit less
secure than their targets) for non-interactive FRI with respect to a certain security
conjecture about the FRI Protocol. However, in all but one set of parameters, we
find that the provable security of non-interactive FRI under these parameters is
severely lacking, being anywhere between 21- and 63-bits less secure than the
conjectured security. The conjectured security of FRI assumes that known attacks
are optimal, the security of these systems would be severely compromised should
a better attack be discovered. In light of this, we present parameter guidelines
for achieving 100-bits of provable security for non-interactive FRI along with a
methodology for tuning these parameters to suit the needs of protocol designers."
---
