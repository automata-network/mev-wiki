---
description: What is a time bandit attack?
---

# Time bandit attack

Time-bandit attacks are attacks where miners rewrite blockchain history to steal funds allocated by smart contracts in the past. If block rewards are small enough compared to MEV, it can be rational for miners to destabilize consensus.

Imagine two miners, Sam and Dan, both get a $100 reward for each block they find. Sam has found three blocks, the first of which contained a $10,000 arbitrage opportunity.

Now Dan has a choice: he can either mine on top of Sam’s 3 blocks, or he can attempt to re-mine the first block in order to take the Uniswap arbitrage for himself. The $10,000 is much more lucrative than the $100 block reward, and Dan is more rational than honest, so he decides to re-mine the first block. While Dan’s at it, since the current longest chain is height 3, he will also re-mine the second and third block \(and captures any MEV that was in those, too\). After the re-organization, Dan owns the longest chain he and Sam can progress from the third block.

