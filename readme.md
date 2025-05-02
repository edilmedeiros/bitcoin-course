# Bitcoin: Technical Aspects and Protocol Implementation

These are the lecture notes for the course **"Bitcoin: Technical Aspects and Protocol Implementation"**.
This project is based on a full redesign of the course originally taught by [Prof. Edil Medeiros](https://edil.com.br) at the University of Brasília in 2024.
The redesign emphasizes pedagogical cohesion, gradual concept introduction, and clear organization.
Also, the material is being developed in English in the hope it can serve as a high quality reference for other universities who want to offer similar courses.

The final product will be a **series of lecture notes**, written in a **conversational style**, targeting technically inclined computer science and engineering students aiming to deeply understand the Bitcoin protocol.


## Motivation

Bitcoin is a revolutionary protocol that addresses fundamental problems in money, decentralization, and trust.
To fully appreciate Bitcoin's design, it is essential to deeply understand its cryptographic foundations, transaction mechanics, economic incentives, and scaling strategies.

There are several excellent technical books about Bitcoin, each contributing valuable insights to the ecosystem:

1. *Mastering Bitcoin* by Andreas Antonopoulos: an authoritative and comprehensive reference on the Bitcoin protocol. 
While it was not primarily designed as a textbook for undergraduate students, it remains an essential resource for in-depth understanding.
2. *Programming Bitcoin* by Jimmy Song: an outstanding workbook that guides readers through Bitcoin's mechanics by building everything from scratch.
Although it is slightly dated and focused more on programming than on conceptual discussions, it is a highly practical companion.
3. *Grokking Bitcoin* by Kalle Rosenbaum: a remarkably approachable and intuitive explanation of the Bitcoin protocol.
Its accessibility makes it ideal for first-time learners, and it deserves wider recognition.

This project aims to produce a pedagogically sound, technically deep, and accessible set of lecture notes that can be refined and expanded over time with community collaboration.


## Structure

The lecture notes are organized into six Parts, each representing a major conceptual block:

| Part | Theme | Lectures |
|:---|:---|:---|
| 1 | Money, Bitcoin, and the Need for Decentralization | 1–3 |
| 2 | Cryptographic Foundations for Bitcoin | 4–7 |
| 3 | Understanding Bitcoin Transactions | 8–13 |
| 4 | Wallets — From Keys to Usability | 14–17 |
| 5 | Mining, Proof of Work, and Settlement | 18–20 |
| 6 | Second Layers and the Future of Bitcoin | 21–23 |

Each lecture will follow a consistent format:
- Overview of the main concept
- Detailed explanations
- Examples and figures when appropriate
- Exercises (optional)
- References for further reading


### Detailed Lecture Plan

**Part 1: Money, Bitcoin, and the Need for Decentralization**

1. What is Money? Why It Breaks
2. Decentralization and Its Challenges
3. Bitcoin’s High-Level Architecture

**Part 2: Cryptographic Foundations for Bitcoin**

4. Finite Fields and Modular Arithmetic
5. Elliptic Curves and secp256k1
6. Digital Signatures: ECDSA and Schnorr
7. Cryptographic Hashes

**Part 3: Understanding Bitcoin Transactions**

8. Transaction Serialization Basics (Legacy)
9. Bitcoin Script Language: Stack Semantics and p2pk
10. Bitcoin Script Contracts: p2pkh and p2sh
11. Transaction Malleability: The Problem and Motivation for SegWit
12. SegWit Transactions: p2wpkh and p2wsh
13. Advanced Script Features (Optional/Buffer)

**Part 4: Wallets — From Keys to Usability**

14. Private Keys, Public Keys, and Addresses
15. Mnemonics and BIP39
16. Hierarchical Deterministic Wallets (BIP32)
17. Wallet Architecture and Security Models

**Part 5: Mining, Proof of Work, and Settlement**

18. Proof of Work and Mining
19. Merkle Trees and Blockchain Structure
20. Chain Splits, Reorgs, and Settlement Assurance

**Part 6: Second Layers and the Future of Bitcoin**

21. Bitcoin's Security Guarantees
22. Conceptual Introduction to Lightning Network
23. Other Scaling Visions and Open Problems


## References

Main references for the material include:
- A. Antonopoulos, D. Harding, *[Mastering Bitcoin: Programming the Open Blockchain](https://github.com/bitcoinbook/bitcoinbook)*, 3rd ed., O'Reilly Media, 2023.
- J. Song, *[Programming Bitcoin: Learn How to Program Bitcoin from Scratch](https://programmingbitcoin.com/programming-bitcoin-book/)*, O'Reilly Media, 2019.
- K. Rosenbaum, *[Grokking Bitcoin](https://github.com/kallerosenbaum/grokkingbitcoin)*, Manning Publications, 2019.
- [Bitcoin Improvement Proposals](https://github.com/bitcoin/bips) (BIPs).
- Original Bitcoin whitepaper: *[Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf)*, by Satoshi Nakamoto.
- [Bitcoin Core documentation and source code](https://github.com/bitcoin/bitcoin).
- Lecture recordings by Prof. Edil Medeiros ([YouTube Playlist](https://youtube.com/playlist?list=PLfdR3_dt2rbexb-ohbaLLzAuNAp7Ypt8u))
- Personal notes and materials prepared during the original course offering.


## Contributions

This is a work in progress!
This repository is open for contributions and peer review.

We welcome:
- Corrections
- Suggestions for improving clarity and pedagogy
- Additional examples and exercises
- Diagrams and visualizations
- Alternative explanations where helpful

Feel free to fork, open issues, and submit pull requests!
