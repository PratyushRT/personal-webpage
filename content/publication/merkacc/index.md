---
title: "Trading Accumulation Size for Witness Size: A Merkle Tree Based Universal Accumulator Via Subset Differences"
date: "2019-10-11T12:08:02+05:30"
publication_types: ["3"]
publication: in IACR eprint
abstract: "Merkle-type trees are widely used to design cryptographic accumulators. The primary advantage in using Merkle tree for accumulators is that they only assume existence of collision resistant hash functions. Merkle tree based accumulators produces constant size accumulation values. But, the size of the witness is always logarithmic in the number of values accumulated, opposed to the constant size witness as exhibited by some of the other popular accumulators that uses number theoretic techniques and problems. Surprisingly, there exists no Merkle tree based accumulator that provides a trade-off between accumulation size and witness size. Such a trade-off is warranted, as argued in this paper, in a situation where witnesses are stored in memory constrained devices and are being moved around continuously, as opposed to the accumulation values that remain stationary, often in devices with moderate storage capacity. In this paper we propose a Merkle-tree based accumulator scheme assuming only collision-resistant hash functions exist. Our scheme allows witness of size that is in general strictly less than logarithmic in the number of values accumulated, and in some cases reduces to constant size. The trade-off cost results in an increased accumulation size."
---


