---
description: What is arbitrum?
---

# Arbitrum \(Offchain Labs\)

Arbitrum is against MEVA and FaaS.

3 Modes of Arbitrum:

1. **Single Sequencer: L2 MEV-Potential \(**_**Mainnet Beta**_**\)**

   For Arbitrum’s initial, flagship Mainnet beta release, the Sequencer will be controlled by a single entity. This entity has transaction ordering rights within the narrow / 15 minute window; users are trusting the Sequencer not to frontrun them.

2. **Distributed Sequencer With Fair Ordering: L2-MEV-minimized \(**_**Mainnet Final Form**_**\)**

   The Arbitrum flagship chain will eventually have a distributed set of independent parties controlling the Sequencer. They will collectively propose state updates via [the first BFT algorithm that enforces fair ordering within consensus \(Aequitas\)](https://eprint.iacr.org/2020/269.pdf). Here, L2 MEV is only possible if &gt;1/3 of the sequencing-parties maliciously collude, hence “MEV-minimized.”

3. **No Sequencer: No L2 MEV**

   A chain can be created in which no permissioned entities have Sequencing rights. Ordering is determined entirely by the Inbox contract; lose the ability to get lower latency than L1, but gain is that no party involved in L2, including Arbitrum validators, has any say in transaction ordering, and thus no L2 MEV enters the picture.

