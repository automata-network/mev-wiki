---
description: What is Salmonella?
---

# Salmonella

Salmonella intentionally exploits the generalised nature of front-running setups. The goal of sandwich trading is to exploit the slippage of unintended victims, so this strategy turns the tables on the exploiters. It’s a regular ERC20 token, which behaves exactly like any other ERC20 token in normal use-cases. However, it has some special logic to detect when anyone other than the specified owner is transacting it, and in these situations it only returns 10% of the specified amount - despite emitting event logs which match a trade of the full amount.

{% hint style="info" %}
Link: [https://github.com/Defi-Cartel/salmonella](https://github.com/Defi-Cartel/salmonella)
{% endhint %}

