---
description: Welcome to the MEV Wiki.
---

# Introduction

## ![](.gitbook/assets/image%20%281%29.png) Introduction <a id="introduction"></a>

This is a public resource for learning about **Miner Extractable Value**.

We cover a range of topics including the key concepts, research on this the topic, different approaches to tackling this issue and also Automata Network's approach.

{% hint style="success" %}
Find any errors or wants to share your opinions?  
See how you can contribute [here](contributions.md).
{% endhint %}

### ![](.gitbook/assets/image.png)What is Miner Extractable Value?

When one sends a transaction on the blockchain, there is a delay between the time when the transaction is broadcast to the network and when it is actually mined into a block. During this period, transactions sit in a pending transaction pool called the mempool where contents are visible to everyone. Arbitrageurs and miners can monitor the mempool and find opportunities to maximize their own profits e.g. by frontrunning transactions. If a front-runner is a miner, they can also reorder or even censor transactions.

Miner Extractable Value refers to the amount of profit that can be extracted from reordering and censoring transactions on the blockchain.

### ![](.gitbook/assets/image.png)Why does this matter[¹](https://research.paradigm.xyz/MEV)?

#### MEV can harm users

MEV is an invisible tax that miners can collect from users.

#### MEV can destabilize Ethereum

If block rewards are small enough compared to MEV, it can be rational for miners to destabilize consensus by reordering or censoring transactions.

### ![](.gitbook/assets/image.png)Just how bad is the problem? <a id="just-how-bad-is-the-problem"></a>

The [Flashbots Dashboard ](https://explore.flashbots.net/) tracks Extracted MEV over time.

It is estimated that &gt;$500M has been extracted since 1st January 2020.

[Dune Analytics ](https://duneanalytics.com/phabc/backrunning-bots-gas-consumption) tracks Gas consumption by back-running bots.

{% hint style="info" %}
**Link:**  
According to [https://research.paradigm.xyz/MEV](https://research.paradigm.xyz/MEV) ↩¹
{% endhint %}



