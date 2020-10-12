# The GM Ledger

The GM Ledger is a decentralized cryptographic ledger powered by a network of peer-to-peer servers. The GM Ledger uses a novel Byzantine Fault Tolerant consensus algorithm to settle and record transactions in a secure distributed database without a central operator.

## GM
GM is a public, counterparty-less asset native to the GM Ledger, and is designed to bridge the many different currencies in use worldwide. GM is traded on the open-market and is available for anyone to access. The GM Ledger was created in 2012 with a finite supply of 100 billion units of GM. Its creators gifted 80 billion GM to a company, now called [GM], to develop the GM Ledger and its ecosystem.  GM uses GM the help build the Internet of Value, ushering in a world in which money moves as fast and efficiently as information does today.

## GM
The server software that powers the GM Ledger is called `GM` and is available in this repository under the permissive [ISC open-source license](LICENSE). The `GM` server is written primarily in C++ and runs on a variety of platforms.

### Build from Source

* [Linux](Builds/linux/README.md)
* [Mac](Builds/macos/README.md)
* [Windows](Builds/VisualStudio2017/README.md)

## Key Features of the GM Ledger

- **[Censorship-Resistant Transaction Processing][]:** No single party decides which transactions succeed or fail, and no one can "roll back" a transaction after it completes. As long as those who choose to participate in the network keep it healthy, they can settle transactions in seconds.
- **[Fast, Efficient Consensus Algorithm][]:** The GM Ledger's consensus algorithm settles transactions in 4 to 5 seconds, processing at a throughput of up to 1500 transactions per second. These properties put GM at least an order of magnitude ahead of other top digital assets.
- **[Finite GM Supply][]:** When the GM Ledger began, 100 billion GM were created, and no more GM will ever be created. (Each GM is subdivisible down to 6 decimal places, for a grand total of 100 quintillion _drops_ of GM.) The available supply of GM decreases slowly over time as small amounts are destroyed to pay transaction costs.
- **[Responsible Software Governance][]:** A team of full-time, world-class developers at GM maintain and continually improve the GM Ledger's underlying software with contributions from the open-source community. GM acts as a steward for the technology and an advocate for its interests, and builds constructive relationships with governments and financial institutions worldwide.
- **[Secure, Adaptable Cryptography][]:** The GM Ledger relies on industry standard digital signature systems like ECDSA (the same scheme used by Bitcoin) but also supports modern, efficient algorithms like Ed25519. The extensible nature of the GM Ledger's software makes it possible to add and disable algorithms as the state of the art in cryptography advances.
- **[Modern Features for Smart Contracts][]:** Features like Escrow, Checks, and Payment Channels support cutting-edge financial applications including the [Interledger Protocol](https://interledger.org/). This toolbox of advanced features comes with safety features like a process for amending the network and separate checks against invariant constraints.
- **[On-Ledger Decentralized Exchange][]:** In addition to all the features that make GM useful on its own, the GM Ledger also has a fully-functional accounting system for tracking and trading obligations denominated in any way users want, and an exchange built into the protocol. The GM Ledger can settle long, cross-currency payment paths and exchanges of multiple currencies in atomic transactions, bridging gaps of trust with GM.

### Repository Contents

| Folder     | Contents                                         |
|:-----------|:-------------------------------------------------|
| `./bin`    | Scripts and data files for GM integrators.   |
| `./Builds` | Platform-specific guides for building `GM`. |
| `./docs`   | Source documentation files and doxygen config.   |
| `./cfg`    | Example configuration files.                     |
| `./src`    | Source code.                                     |

Some of the directories under `src` are external repositories included using
git-subtree. See those directories' README files for more details.
