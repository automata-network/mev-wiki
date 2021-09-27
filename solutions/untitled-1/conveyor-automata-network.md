---
description: What is Conveyor?
---

# Conveyor \(Automata Network\)

## ![](../../.gitbook/assets/image%20%283%29.png)Conveyor - The Automata Network approach to tackling MEV

At Automata, we have created **Conveyor**, a service that ingests and outputs transactions in a determined order. This creates a front-running-free zone that removes the chaos of transaction reordering.

When transactions are fed into Conveyor, it determines the order of the incoming transactions and makes it impossible for block producers to perform the following:

1. Inject new transactions into the Conveyor output: The inserted transactions bypassing Conveyor is detectable by anyone because of signature mismatch.
2. Delete ordered transactions: Transactions accepted by Conveyor are broadcasted everywhere so transactions cannot be deleted unless ALL block producers are colluding and censoring the transactions at the same time.

From the DEX’s perspective, they can choose to accept either

1. Ordered transactions from Automata’s Conveyor which is free from transaction reordering and other front-running transactions
2. Other unordered transactions \(which include front-running etc\) that may negatively impact their users

#### Why should users trust Conveyor? <a id="why-should-users-trust-conveyor"></a>

Automata’s Conveyor runs on a decentralized compute plane backed by many Geode instances. Each Geode instance can be attested so anyone can publicly verify that the Geode is running on a system with genuine hardware \(i.e., CPU\) and that the Geode application code matches the version that is open-sourced and audited. This provides a strong guarantee that:

* The Geode code is untampered with
* The Geode data is inaccessible to even Geode providers \(In which case they cannot act on said data to front-run transactions\)

Importantly, Automata’s Conveyor is a chain-agnostic solution to the MEV issue, and works seamlessly on various platforms — zero modifications needed. Here’s a [demo](https://ata.network/demo-fp) on how trading pairs on Uniswap can be protected.

#### An industry-first: Oblivious RAM <a id="an-industry-first-oblivious-ram"></a>

In fully public computation, access pattern leakage is not negligible as everything is exposed. But in privacy-preserving computation, any tiny bit of information leakage becomes a significant issue. Studies have shown that access pattern leakage leads to exposure of sensitive information such as private keys from searchable encryption and trusted computing.

This is where the Oblivious RAM algorithm comes into play. Automata’s implementation is the first-of-its-kind in the blockchain industry, providing an exceedingly high degree of privacy in dApps.

This greatly reduces the probability of user privacy being leaked even as access patterns are being monitored and analyzed by malicious actors. The Automata team has authored multiple research papers on state-of-the-art ORAM and hardware technologies to enhance the privacy and performance of existing networks.

* Robust P2P Primitives Using SGX Enclaves [RAID 2020](https://www.usenix.org/system/files/raid20-jia.pdf)
* PRO-ORAM: Practical Read-Only Oblivious RAM [RAID 2019](https://www.usenix.org/system/files/raid2019-tople.pdf)
* OblivP2P: An Oblivious Peer-to-Peer Content Sharing System [USENIX Security 2016](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_jia.pdf)
* Preventing Page Faults from Telling Your Secrets [Asia CCS 2016](https://n.ethz.ch/~sshivaji/publications/pfdefense_asiaccs16.pdf)

