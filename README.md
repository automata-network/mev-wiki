---
description: Introduction to MEV.
---

# Introduction

This is a public resource for learning about **Miner Extractable Value**.

We cover a range of topics including the key concepts, research on this the topic, different approaches to tackling this issue and also Automata Network's approach.

Tip

1. Find any errors? Click the icon on each page to contribute.
2. Want to share your feedback? Contact us [**here** ](https://us2.list-manage.com/survey?u=ffeae60ea2fcc1c9fe0f8ce40&id=8d7d318a72&attribution=false).

## What is Miner Extractable Value?

  
When one sends a transaction on the blockchain, there is a delay between the time when the transaction is broadcast to the network and when it is actually mined into a block. During this period, transactions sit in a pending transaction pool called the mempool where contents are visible to everyone. Arbitrageurs and miners can monitor the mempool and find opportunities to maximize their own profits e.g. by frontrunning transactions. If a front-runner is a miner, they can also reorder or even censor transactions.

Miner Extractable Value refers to the amount of profit that can be extracted from reordering and censoring transactions on the blockchain.

### Why does this matter? <a id="why-does-this-matter1"></a>

#### MEV can harm users <a id="mev-can-harm-users"></a>

MEV is an invisible tax that miners can collect from users.

#### MEV can destabilize Ethereum <a id="mev-can-destabilize-ethereum"></a>

If block rewards are small enough compared to MEV, it can be rational for miners to destabilize consensus by reordering or censoring transactions.

### Just how bad is the problem? <a id="just-how-bad-is-the-problem"></a>

The [Flashbots Dashboard ](https://explore.flashbots.net/) tracks Extracted MEV over time.

It is estimated that &gt;$500M has been extracted since 1st January 2020.

[Dune Analytics ](https://duneanalytics.com/phabc/backrunning-bots-gas-consumption) tracks Gas consumption by back-running bots.

