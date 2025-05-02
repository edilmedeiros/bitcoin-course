# Lecture 2: Bitcoin as a Protocol for Ownership Transfer

In the previous lecture, we explored how money emerges to solve coordination problems in trade.
We saw that money is not a static thing, but a technological tool:
a set of functions that evolves to meet the demands of space, time, and scale in economic exchange.
We also explored how money has become increasingly abstract—eventually transforming into communication protocols managed by trusted intermediaries.
In this lecture, we begin our study of Bitcoin by taking a bird's-eye view of its architecture.
We will introduce its most important components without diving into full technical detail yet.

Our goal is to understand what Bitcoin is as a system, and what kinds of problems it is designed to solve.
We will continue using the stories of Alice and Bob to illustrate how Bitcoin reimagines the concept of digital money.

## Transactions as Messages of Ownership Change

[todo: describe bitcoin transactions as signed messages that transfer value; bring Alice and Bob back as an example; stress that ownership is defined through the ability to authorize spending]

## Programming Transfers: Bitcoin Script and the Semantics of Inputs and Outputs

[todo: explain outputs as encumbered coins; inputs as satisfying conditions to spend; introduce the term UTXO; maybe postpone implementation details to later lectures]

## The Double Spending Problem

[todo: introduce the timing problem and the possibility of broadcasting conflicting transactions; highlight that this problem only appears when money becomes digital and decentralized]

[todo: explain that the peer-to-peer network and blockchain structure solve this by introducing a notion of shared history that can be verified and extended]

## Anchoring Trust with Proof-of-Work

[todo: explain how proof-of-work connects the communication layer to physical constraints, making it costly to rewrite history; frame miners as economic agents incentivized to extend the chain honestly]

[todo: show how this mechanism removes the need for a central timestamping authority]

## Concluding Overview

[todo: recap the major components of Bitcoin introduced here and preview how the following lectures will explore each one in detail]

## References

