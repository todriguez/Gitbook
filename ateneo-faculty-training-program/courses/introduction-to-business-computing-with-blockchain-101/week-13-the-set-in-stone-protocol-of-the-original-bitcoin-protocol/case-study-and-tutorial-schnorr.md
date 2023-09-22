# Case Study & Tutorial - Schnorr

{% embed url="https://craigwright.net/blog/bitcoin-blockchain-tech/schnorr/" %}

The article discusses the implications of protocol variations on the legal standing of a blockchain, specifically Bitcoin. It emphasizes the difference between privacy and anonymity, arguing that Bitcoin was designed to be a private but not anonymous system. The author argues that anonymous systems are not legally enforceable and are prone to misuse, as seen in the Silk Road case. The article also discusses the introduction of Schnorr signatures, which some believe can provide plausible deniability and additional anonymity. However, the author argues that this is a misunderstanding and that such changes could lead to legal issues, including violations of the Bank Secrecy Act. The article concludes by stating that Bitcoin's protocol should remain immutable and that attempts to alter it for anonymity purposes will only lead to legal complications and potential failure.

*   "The nature of Bitcoin is such that once version 0.1 was released, the core design was set in stone for the rest of its lifetime. Because of that, I wanted to design it to support every possible transaction type I could think of. The problem was, each thing required special support code and data fields whether it was used or not, and only covered one special case at a time. It would have been an explosion of special cases. The solution was script, which generalizes the problem so transacting parties can describe their transaction as a predicate that the node network evaluates. The nodes only need to understand the transaction to the extent of evaluating whether the sender's conditions are met.

    The script is actually a predicate. It's just an equation that evaluates to true or false. Predicate is a long and unfamiliar word so I called it script.

    The receiver of a payment does a template match on the script. Currently, receivers only accept two templates: direct payment and bitcoin address. Future versions can add templates for more transaction types and nodes running that version or higher will be able to receive them. All versions of nodes in the network can verify and process any new transactions into blocks, even though they may not know how to read them.

    The design supports a tremendous variety of possible transaction types that I designed years ago. Escrow transactions, bonded contracts, third party arbitration, multi-party signature, etc. If Bitcoin catches on in a big way, these are things we'll want to explore in the future, but they all had to be designed at the beginning to make sure they would be possible later.

    I don't believe a second, compatible implementation of Bitcoin will ever be a good idea. So much of the design depends on all nodes getting exactly identical results in lockstep that a second implementation would be a menace to the network. The MIT license is compatible with all other licenses and commercial uses, so there is no need to rewrite it from a licensing standpoint." - Satoshi Nakamoto, [https://bitcointalk.org/index.php?topic=195.msg1617#msg1617](https://bitcointalk.org/index.php?topic=195.msg1617#msg1617)[\
    ](https://bitcointalk.org/index.php?topic=195.msg1617#msg1617)

Leading Questions:

1. What is the difference between privacy and anonymity in the context of blockchain technology, and why is this distinction important?
2. How can changes to Bitcoin's protocol, such as the introduction of Schnorr signatures, potentially lead to legal issues?
3. What is the Bank Secrecy Act, and how could protocol variations potentially violate this act?
4. Why is it important for Bitcoin's protocol to remain immutable, and what are the potential consequences of altering it?
5. How does the author view the attempts to alter Bitcoin's protocol for anonymity purposes, and why?
6. What are the implications of these protocol changes for businesses that rely on Bitcoin's blockchain?
7. How does the author's perspective align or contrast with the principles discussed in Week 10 - The 'Set-in-Stone' Protocol of the Original Bitcoin Protocol?
8. How can understanding the Original Bitcoin Protocol and its immutability help businesses navigate the legal landscape of blockchain technology?
