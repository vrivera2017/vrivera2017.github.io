---
title: "Other Projects"
menu:
  main:
    weight: 5
---

## Efficient Storage for Verifiable Computation

{{< imgright "/images/rsa-acc-circuit.jpg" "300px" >}}
The circuit for updating an RSA accumulator.
We show how to implement it within a SNARK.
{{< /imgright >}}

Cryptographers have shown that you can certify the correct execution
of a program using proofs that
(a) are verifiable in constant time and
(b) keep the inputs to the program hidden.
These systems are called _zk-SNARKs_ (Zero Knowledge Succinct Non-Interactive
Arguments of Knowledge) and they power crypto-currencies like
[Zcash](https://z.cash/).

A pervasive but tough problem for these systems is how to manipulate
persistent memory.
Traditionally these systems have summarized that memory with a [hash
tree](https://en.wikipedia.org/wiki/Merkle_tree)

---