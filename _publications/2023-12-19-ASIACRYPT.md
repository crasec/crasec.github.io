---
title: "Polynomial IOPs for Memory Consistency Checks in Zero-Knowledge Virtual Machines"
collection: publications
category: conferences
permalink: /publication/2023-12-19-ASIACRYPT
excerpt: ' '
date: 2023-12-19
venue: 'ASIACRYPT 2023'
paperurl: 'https://link.springer.com/chapter/10.1007/978-981-99-8724-5_4'
citation: 'Yuncong Zhang, Shifeng Sun, Ren Zhang, Dawu Gu: Polynomial IOPs for Memory Consistency Checks in Zero-Knowledge Virtual Machines. ASIACRYPT (2) 2023: 111-141'
---
Zero-Knowledge Virtual Machines (ZKVMs) have gained traction in recent years due to their potential applications in a variety of areas, particularly blockchain ecosystems. Despite tremendous progress on ZKVMs in the industry, no formal definitions or security proofs have been established in the literature. Due to this lack of formalization, existing protocols exhibit significant discrepancies in terms of problem definitions and performance metrics, making it difficult to analyze and compare these advancements, or to trust the security of the increasingly complex ZKVM implementations.

In this work, we focus on random-access memory, an influential and expensive component of ZKVMs. Specifically, we investigate the state-of-the-art protocols for validating the correct functioning of memory, which we refer to as the memory consistency checks. Isolating these checks from the rest of the system allows us to formalize their definition and security notion. Furthermore, we summarize the state-of-the-art constructions using the Polynomial IOP model and formally prove their security. Observing that the bottleneck of existing designs lies in sorting the entire memory trace, we break away from this paradigm and propose a novel memory consistency check, dubbed Permem.  Permem bypasses this bottleneck by introducing a technique called the address cycle method, which requires fewer building blocks and—after instantiating the building blocks with state-of-the-art constructions—fewer online polynomial oracles and evaluation queries. In addition, we propose , a new construction for the lookup argument—a key building block of the memory consistency check, which costs fewer online polynomial oracles than the state-of-the-art construction cq.
