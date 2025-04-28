# Introduction: What We Are Studying

The first thing people usually think about when we talk about bitcoin is that it is a currency, or a form of money.
But this is an interpretation—or an abstraction—rather than the essence of what bitcoin is.
In conflating the map with the territory, we risk misunderstanding the system.
Bitcoin, at its most basic, is a computer system designed to implement a form of money.
It is not wrong to think of bitcoin as money;
indeed, it is a system purpose-built to enable monetary exchange.
But whether it succeeds in being used as money is ultimately a discovery of the market.
The tokens exist as digital entries, and their value arises from human interaction and recognition, not from any intrinsic property.

Bitcoin can also be understood as a communication protocol:
a set of rules, agreed upon by a distributed network of peers, that defines how to communicate valid transactions and blocks.
This is, in many ways, a more concrete view of bitcoin, focusing on its true operational essence.
Yet it is also a more conceptual view, because it frames bitcoin as a discipline—a set of conventions for exchanging messages—rather than a particular product.
This perspective aligns Bitcoin with other major technological systems such as the internet, itself composed of protocols stacked together to enable communication across space and time.

Furthermore, bitcoin can refer to the specific instance of a network of computers running software implementations of the bitcoin protocol—what we usually call "the Bitcoin network."
These computers validate messages, maintain a shared history of ownership, and reach consensus without centralized coordination.
It is this network that maintains the global record of bitcoin transactions in the form of a distributed blockchain.
It is within this network that the protocol "materializes" and becomes alive, evolving organically through the interactions of its participants.

The Bitcoin network, in this sense, resembles a complex system similar to a school of fish.
Each node in the network acts independently, basing its decisions only on local information:
the transactions and blocks it directly receives, the rules it is programmed to enforce, and its interactions with neighboring nodes.
There is no central authority dictating the network's behavior, just as there is no leader among the fish.
Instead, coordination emerges implicitly from the local rules that every participant follows.
In a school of fish, the simple imperatives to stay close to neighbors yet avoid collisions give rise to the appearance of a single, fluid entity.
In Bitcoin, the result is a decentralized consensus about ownership, secured not by verbal communication or centralized orders, but by cryptographic proofs and economic incentives.
This organized complexity—the emergence of a coherent system from decentralized and autonomous parts—is at the heart of what makes Bitcoin both resilient and revolutionary.

Understanding Bitcoin as a communication protocol will be the conceptual foundation we develop throughout this course.
We will treat bitcoin (the currency) as an emergent phenomenon:
it exists because the protocol enables ownership to be communicated, verified, and enforced in a decentralized way.
Similarly, we will observe the Bitcoin network as the current, real-world deployment of the protocol, but our focus will remain on understanding the rules that any such network must implement.

The essence of Bitcoin is that it acts as a communication protocol for ownership changes.
Its primary purpose is to allow participants to exchange signed messages that update who controls specific tokens within the system.
Each valid message represents a voluntary transfer of ownership, and the Bitcoin protocol ensures these transfers are recorded in a tamper-resistant ledger without requiring any central authority to oversee them.
This achievement rests on a careful combination of cryptography, economic incentives, and decentralized consensus mechanisms, rather than trust.
Throughout this course, we will revisit these foundational elements repeatedly, as they form the pillars supporting Bitcoin's operation and resilience.

Viewing Bitcoin as a communication protocol also reshapes how we study its internal structure.
Transactions become the fundamental messages.
Scripts define the conditions for spending tokens.
Blocks aggregate sets of messages into atomic units of history.
Mining secures the sequencing of those messages against manipulation.
Even Bitcoin’s scaling challenges and the emergence of second-layer solutions, such as the Lightning Network, can be understood naturally by analyzing the communication and verification constraints of the base protocol.
This lens will guide our exploration of Bitcoin from the first lecture to the last.

This course is structured to progressively develop a clear and technically grounded understanding of Bitcoin.
We will start with the motivation for its creation, delve into the cryptographic primitives that make it possible, explore transaction formats and scripting, study wallet construction, examine mining and settlement, and finally discuss how Bitcoin’s security guarantees enable further innovation on top of its foundation.

Because Bitcoin is not governed by a formal standard or RFC, our sources of truth are practical and distributed.
The Bitcoin Core source code (the major implementation of the bitcoin protocol), the whitepaper published by Satoshi Nakamoto in 2008, and key technical books such as *Mastering Bitcoin*, *Programming Bitcoin*, and *Grokking Bitcoin* provide overlapping but complementary perspectives.
Throughout this course, we will rely on these materials to guide our exploration, while also developing our own coherent mental model of the system.
Moreover, the course will include a strong hands-on component, with programming tasks that will direct students to implement parts of the protocol or pieces of software that interact with the Bitcoin network, reinforcing understanding through practice.

By the end, we aim not only to understand how Bitcoin works, but also why it works—and why it matters.
