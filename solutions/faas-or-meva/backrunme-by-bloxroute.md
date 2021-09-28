---
description: What is BackRunMe?
---

# BackRunMe by bloXroute

[bloXroute Labs](https://bloxroute.com/) has a wide range of offerings and their core competency is low global latency for DeFi \(8% of blocks mined within 1 sec\).

Note

For the other side of the coin, here is bloXroute Labs' take on why private mempools are not necessarily bad:

1. Front-runners don't need these services to outpace regular users, who are slower by seconds. They need it to outpace one another, where improving speed 0.8-&gt;0.15 sec matters.
2. When a transaction is privately sent to pools other frontrunners can't attempt to front-run it. This helps avoid fierce escalation of fees.

### BackRunMe by bloXroute <a id="backrunme-by-bloxroute"></a>

BackRunMe is a service that allows users to submit private transactions \(e.g. protection against frontrunning and sandwich attacks\) while allowing searchers to backrun the transaction via MEV IF it produces an arbitrage profit. If it doesn't generate an arbitrage profit it is processed as a regular private transaction. BackRunMe, gives a portion of this additional profit back to the user.

The profit sharing ratio is as follows: 50% to miners, 25% to users, 20% to searchers and 5% to bloXroute.

Users can use MetaMask directly on BackRunMe to trade on Uniswap or Sushiswap.

