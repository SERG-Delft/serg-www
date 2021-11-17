---
title: Software Reliability for Concurrent and Distributed Systems
name: SR4CDS
subtitle: Develop methods and tools for increasing reliability of concurrent and distributed systems.


menu:
  main:
    parent: Research Lines

responsible_authors:
  - Burcu Kulahcioglu Ozkan

additional_authors: []

collaborators: []

funding: []
---

Today’s software is evolving in the direction of more concurrency (to exploit multiple cores) and decentralization (to exploit networked systems). With the increasing use of mobile devices and cloud services, the applications we use today are deployed to geo-replicated distributed systems, easily accessible from everywhere.

However, it is difficult to implement distributed systems correctly since their behavior is more complicated than classical sequential programs. The nondeterminism in the delivery order of concurrent messages, network failures, or node crashes may result in subtle executions that lead to buggy behavior. It is difficult for the programmers to consider all possible executions during the system design and implementation. The reliability of distributed systems requires different techniques than the techniques designed for sequential software.

The goal of this research line is to build program analysis, testing, and debugging methods for increasing the reliability of concurrent programs and distributed systems. Our research interests span different kinds of concurrent programs, e.g., multi-threaded programs, asynchronous, event-driven, and distributed systems.

We currently focus on testing distributed systems, asking the following questions: 

**How can we design efficient tests to detect and diagnose bugs** that occur due to unexpected event orderings or faults in:

* **Fault-tolerant consensus systems** \- that implement consensus protocols such as Paxos and Raft
* **Weakly consistent systems** \- that provide weak levels of consistency such as causal or eventual consistency in favor of higher availability
* **Blockchains** – that is basically a distributed, decentralized database that stores information in a chain of blocks 

**Available MSc projects**.

* [Probabilistic Testing for Weak Memory Concurrency](https://pl.ewi.tudelft.nl/master-projects/master/2021/06/07/Probabilistic-Testing-Weak-Memory-Concurrency/) (co-supervised with [Soham Chakraborty](https://www.st.ewi.tudelft.nl/sschakraborty/))
* [Building a Conflict-Free Replicated Datatype (CRDT) Library for Distributed Systems](https://projectforum.tudelft.nl/admin/thesis_projects/157)
* [Controlled Crash-recovery Testing of Distributed Systems](https://projectforum.tudelft.nl/admin/thesis_projects/161)

[Contact](mailto:b.ozkan@tudelft.nl) if you are interested in working on software testing, concurrent programming, distributed systems, and blockchains.
