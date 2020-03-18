# Reading List

This is a list of resources the Quilt team has found useful and relevant to our work. Please open an issue to add something to this list.

## Phase 2 Proposals
* [Phase 2 Proposal 1](https://notes.ethereum.org/@vbuterin/HylpjAWsE)
* [Phase 2 Proposal 2](https://notes.ethereum.org/w1Pn2iMmSTqCmVUTGV4T5A)
* [Alternate phase 2 architecture proposal](https://notes.ethereum.org/YNnC-fakRxixbMCTEnNDXQ)
* [Eth2 shard chain simplification proposal](https://notes.ethereum.org/@vbuterin/HkiULaluS)
* [A Short History and a Way Forward for Phase 2](https://ethresear.ch/t/a-short-history-and-a-way-forward-for-phase-2/6982)

## Cross-Shard Communication
* [Phase 2 pre-spec: cross-shard mechanics](https://ethresear.ch/t/phase-2-pre-spec-cross-shard-mechanics/4970)
* [A protocol for cross-shard ETH transfers: even more simpler and transparent](https://ethresear.ch/t/a-protocol-for-cross-shard-eth-transfers-even-more-simpler-and-transparent/6996)
* [Fast cross-shard transfers via optimistic receipt roots](https://ethresear.ch/t/fast-cross-shard-transfers-via-optimistic-receipt-roots/5337)
* [Cross-shard DeFi composability](https://ethresear.ch/t/cross-shard-defi-composability/6268)
* [Simple synchronous cross-shard transaction protocol](https://ethresear.ch/t/simple-synchronous-cross-shard-transaction-protocol/3097)
* [Encumberments: instant cross-shard payments over slow cross-shard base-layer communication as a layer 2](https://ethresear.ch/t/encumberments-instant-cross-shard-payments-over-slow-cross-shard-base-layer-communication-as-a-layer-2/4369)
* [Synchronous cross-shard transactions with consolidated concurrency control and consensus (or how I rediscovered Chain Fibers)](https://ethresear.ch/t/synchronous-cross-shard-transactions-with-consolidated-concurrency-control-and-consensus-or-how-i-rediscovered-chain-fibers/2318)
* [Implementing cross-shard transactions](https://ethresear.ch/t/implementing-cross-shard-transactions/6382)
* [Cross-shard receipt and hibernation/waking anti-double-spending](https://ethresear.ch/t/cross-shard-receipt-and-hibernation-waking-anti-double-spending/4748)
* [Commit Capabilities - atomic cross shard communication](https://ethresear.ch/t/commit-capabilities-atomic-cross-shard-communication/6509)
* [x-shard/meta-ee discussion](https://hackmd.io/g-FvxXFoRDWYGPIEs82AAQ)
* [An even simpler meta-execution environment for ETH](https://ethresear.ch/t/an-even-simpler-meta-execution-environment-for-eth/6704/9)
* [Cross-chain Deals and Adversarial Commerce](https://arxiv.org/abs/1905.09743)

## State Provision
* [The Data Availability Problem under Stateless Ethereum](https://ethresear.ch/t/the-data-availability-problem-under-stateless-ethereum/6973)
* [State Provider Models in Ethereum 2.0](https://ethresear.ch/t/state-provider-models-in-ethereum-2-0/6750/8)
* [Automated Detection of Dynamic State Access in Solidity](https://ethresear.ch/t/automated-detection-of-dynamic-state-access-in-solidity/7003/4)

## Data Availability
* [Fraud and Data Availability Proofs: Maximising Light Client Security and Scaling Blockchains with Dishonest Majorities](https://arxiv.org/abs/1809.09044)
* [Coded Merkle Tree: Solving Data Availability Attacks in Blockchains](https://arxiv.org/abs/1910.01247)
* [A note on data availability and erasure coding](https://github.com/ethereum/research/wiki/A-note-on-data-availability-and-erasure-coding)
* [LazyLedger: A Distributed Data Availability Ledger With Client-Side Smart Contracts](https://arxiv.org/abs/1905.09274)

## Consensus
* [Reaching Agreement in the Presence of Faults](http://lamport.azurewebsites.net/pubs/reaching.pdf)
* [The Byzantine Generals Problem](https://people.eecs.berkeley.edu/~luca/cs174/byzantine.pdf)
* [Easy impossibility proofs for distributed consensus problems](https://groups.csail.mit.edu/tds/papers/Lynch/FischerLynchMerritt-dc.pdf)
* [Proofs of Work and Bread Pudding Protocols](http://www.hashcash.org/papers/bread-pudding.pdf)
* [Analysis of Nakamoto Consensus](https://eprint.iacr.org/2019/943.pdf)
* [BFT Protocols Under Fire](https://www.usenix.org/legacy/event/nsdi08/tech/full_papers/singh/singh.pdf)
* [HotStuff: BFT Consensus with Linearity and Responsiveness](https://www.cs.unc.edu/~reiter/papers/2019/PODC.pdf)
* [State Machine Replication in the Libra Blockchain](https://developers.libra.org/docs/assets/papers/libra-consensus-state-machine-replication-in-the-libra-blockchain/2019-11-08.pdf)
* [Streamlet: Textbook Streamlined Blockchains](https://eprint.iacr.org/2020/088.pdf)

## Plasma
* [Lower Bounds for Off-Chain Protocols: Exploring the Limits of Plasma](https://eprint.iacr.org/2020/175.pdf)

## Distributed Hash Tables

### Kademlia

#### Overview

* [Kademlia: A Peer-to-peer Information System Based on the XOR Metric](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf) - **The** paper that describes the Kademlia protocol.
* Implementing a DHT in Go - Easy to follow walkthrough of building a Kademlia DHT in Go. Covers most of the basics, and you end up with something functional.
  * [Part 1](http://blog.notdot.net/2009/11/Implementing-a-DHT-in-Go-part-1)
  * [Part 2](http://blog.notdot.net/2009/11/Implementing-a-DHT-in-Go-part-2)

#### Security
* [S/Kademlia: A Practicable Approach Towards Secure Key-Based Routing](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.68.4986&rep=rep1&type=pdf) - Discussion of attacks on the Kademlia protocol, and some mitigation strategies.

## Account Abstraction

### Background

* [Ethereum Account Abstraction Explained](https://ethgasstation.info/blog/ethereum-account-abstraction-explained/)
* [Ethereum Roadmap: Account Abstraction](https://docs.ethhub.io/ethereum-roadmap/ethereum-2.0/account-abstraction/)

### Potential Implementation Strategies & Criticisms

* [Implementing account abstraction as part of eth1.x](https://ethereum-magicians.org/t/implementing-account-abstraction-as-part-of-eth1-x/4020)
* [Tradeoffs in account abstraction proposals](https://ethresear.ch/t/tradeoffs-in-account-abstraction-proposals/263)
* [Abstraction of transaction origin and signature (EIP-86)](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-86.md)
