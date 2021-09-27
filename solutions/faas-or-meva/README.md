---
description: MEVA and FaaS solutions.
---

# Front-running as a Service \(FaaS\) or MEV Auctions \(MEVA\)

In a FaaS or MEVA system, MEV is extracted in a variety of ways such as miners auctioning off the right to front-run users.

Vitalik Buterin - 

_'Centralizing MEV extraction is good because it quarantines a revenue stream that could otherwise drive centralization in other sectors.'_

Phil Daian, co-author of Flash Boys 2.0 - 

_'In this article, I’m going to go deep into my personal arguments for why extracting MEV in cryptocurrencies isn’t like theft, why it is a critical metric for network security in any distributed system secured by economic incentives \(yes, including centralized ones\), and what we should do about MEV in the next 3-5 years as a community.'_

### Private Transactions <a id="private-transactions"></a>

Typically, transactions are broadcast to the mempool where they remain pending until miners pick them and add to the block. Private transactions however, are only visible to the pool and are not broadcast to other nodes \(pay more for faster transactions\).

Examples include [1inch Exchange's Stealth Transactions](https://help.1inch.io/en/articles/4695716-what-are-stealth-transactions-and-how-they-work), [Taichi Network](https://taichi.network/) and [BloXroute](https://bloxroute.com/products/).

[_Private Transactions offered by Taichi Network_](https://taichi.network/)

[bloXroute Labs](https://bloxroute.com/) has a wide range of offerings and their core competency is low global latency for DeFi \(8% of blocks mined within 1 sec\).

Note

For the other side of the coin, here is bloXroute Labs' take on why private mempools are not necessarily bad:

1. Front-runners don't need these services to outpace regular users, who are slower by seconds. They need it to outpace one another, where improving speed 0.8-&gt;0.15 sec matters.
2. When a transaction is privately sent to pools other frontrunners can't attempt to front-run it. This helps avoid fierce escalation of fees.

### BackRunMe by bloXroute <a id="backrunme-by-bloxroute"></a>

See the various solutions:

### Flashbots <a id="flashbots"></a>

* [BackRunMe](backrunme-by-bloxroute.md)
* [Flashbots](flashbots.md)
* [mistX](mistx-by-alchemist.md)
* [KeeperDAO](keeperdao.md)
* [ArcherSwap](archerswap.md)
* [Optimism](optimism.md)
* [MiningDAO](miningdao.md)
* [BackBone Cabal](backbone-cabal.md)



### mistX by alchemist <a id="mistx-by-alchemist"></a>

### KeeperDAO <a id="keeperdao"></a>

