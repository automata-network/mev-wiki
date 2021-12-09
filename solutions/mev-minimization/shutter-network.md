# Shutter Network

## ![](../../.gitbook/assets/image%20%283%29.png)Shutter Network

Shutter Network is an open-source project that aims to prevent frontrunning and malicious MEV on Ethereum by using a threshold cryptography-based distributed key generation \(DKG\) protocol.

A Shutter transaction is a transaction protected from front running in the target smart contract system. It, therefore, passes through a sequence of stages before it is executed.

A Shutter transaction flow:

1. Created and encrypted in the user's wallet;
2. Sent to the batcher contract as a standard Ethereum transaction;
3. Picked up and decrypted by the keypers;
4. Sent to the executor contract, and
5. Forwarded to the target contract.

{% hint style="info" %}
**Links:**

* Website: [https://shutter.ghost.io/](https://shutter.ghost.io/)
* GitHub: [https://github.com/brainbot-com/shutter](https://github.com/brainbot-com/shutter)
{% endhint %}

