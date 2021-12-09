# Vega protocol

## ![](../../.gitbook/assets/image%20%283%29.png)Vega Protocol

Traditionally, fairness in a blockchain has been defined in absolute terms, i.e. once a transaction is seen by a sufficient number of validators, it will be executed in some block, soon. Vega's proposal is to add a module to blockchains that support the concept of relative fairness so that competing transactions may be sequenced under a known and understood protocol, and not subject to a validator’s discretion.

"_If there is a time t such that all honest validators saw a before t and b after t, then a must be scheduled before b”._ This is a property that can be assured of at any time with a minimal impact on performance.

To get the best combination, their current approach is a hybrid of the two. In normal operation, the protocol will assure block fairness. If the network detects that this causes a bottleneck, it temporarily switches to the timed approach \(thus sacrificing a little fairness for performance\), before switching back once the bottleneck is resolved. However, Vega will ultimately make the level of fairness customisable by the market.

{% hint style="info" %}
**Links:**

* Website: [https://vega.xyz/](https://vega.xyz/)
* Blog: [https://blog.vega.xyz/new-paper-fairness-and-front-running-an-invitation-for-feedback-cbb39a1a3eb](https://blog.vega.xyz/new-paper-fairness-and-front-running-an-invitation-for-feedback-cbb39a1a3eb)
* Wendy, the Good Little Fairness Widget: [https://vega.xyz/papers/fairness.pdf](https://vega.xyz/papers/fairness.pdf)
* Video: [https://www.youtube.com/watch?v=KjfLj5fhkGQ&t=18s&ab\_channel=VegaProtocol](https://www.youtube.com/watch?v=KjfLj5fhkGQ&t=18s&ab_channel=VegaProtocol)
{% endhint %}

