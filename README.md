SWIFTCASH
=================================================
![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg) [![Build Status](https://travis-ci.org/swiftcashproject/swiftcash.svg?branch=master)](https://travis-ci.org/swiftcashproject/swiftcash) [![Discord](https://img.shields.io/discord/488436992032636929.svg)](https://discord.me/swiftcash)

### Introduction - Peer-To-Peer Cryptocurrency
SwiftCash is an open-source, self-funded system of decentralized governance and economy, born out of a desire to create a digital store of value and a peer-to-peer cryptocurrency for daily transactional use along with cheat-proof lotteries that can be played by anyone in the blockchain without any custodian or third-party service getting involved, as well as on-chain HODL/Term deposits. SwiftCash uses the Proof-of-Stake algorithm to reach consensus and allows up to 10% of maximum inflation to be spent on proposals that are embraced by enough stakeholders. Another 10% of maximum inflation goes directly to stakeholders who help secure the network aka Miners and Masternodes, and the rest of maximum inflation which is 80% can go to HODL/Term deposits; coins that are time locked in the blockchain between 1-12 months.

### Proof-of-Stake vs. Proof-of-Work
The revolutionary Proof-of-Stake algorithm offers a solution to the problem posed by the exponential increase in energy consumed by Bitcoin, and other Proof-of-Work cryptocurrencies. Proof-of-Work mining is environmentally unsustainable due to the electricity used by high-powered mining hardware and anyone can attack the network and double spend by acquiring 51% of the network’s hash power. SwiftCash utilizes the green protocol, an energy-efficient Proof-of-Stake algorithm, which can be mined on any computer, and will never require specialized mining equipment. The green protocol offers a simple solution to sustainability issues posed by Bitcoin and other Proof-of-Work cryptocurrencies, and provides a faster, and more scalable blockchain that is better suited for daily transactional use.

### Initial Distribution & Inflation - Fair Launch
1:1 airdrop on all addresses of the old chain aka SwiftCash v2.x. Addresses with less than 1 SWIFT were excluded from the forkdrop. Passed proposals for the last superblock were also paid upfront during the forkdrop phase, since the reset occurred just before the last superblock.

### Blockchain-Based & Cheat-Proof Lotteries
Lottery tickets can be bought with as little as 0.01 SWIFT. Winners are picked randomly based on a future blockhash. Draws take place every 5,000 blocks - appx once a month, and each time 3 tickets win; the winning tickets can all belong to the same person, bought in just one transaction, as burning more coins is the only thing that results in higher chances. 80% of the coins spent to buy tickets will become the jackpot and will be distributed between the winners. First winner will receive 60% of the jackpot, second winner will receive 30% of the jackpot and third winner will receive 10% of the jackpot. Buying tickets within 20 blocks before or after each draw will not enter any draw! The core wallet does not allow users to buy tickets within 40 blocks before or after each draw; twice the protocol limit. 15% of the coins spent on buying tickets will be given to SwiftCash Miners and SwiftNodes. And last but not least, 5% of the coins spent on buying tickets will burn in a deflationary fashion, just like transaction fees!

### HODL Deposits - Immitating Term Deposits in Traditional Banking Systems
HODL deposits are designed to imitate term deposits in traditional banking systems. The idea is that users can lock their coins in the blockchain for a set period of time and be rewarded for doing so. HODL rewards come from future inflation, are paid instantly to the locked deposit and they cannot be spent until the deposit matures. The best rate is paid to 12-month deposits which is calculated by 80% of the maximum block rewards during 12 months divided by 80% of the total supply at the time the HODL deposit is made. For deposits less than 12 months, the annual rate is 7% less than the best rate. For example, if the best annual rate is 50% for a 12-month deposit, it will be 46.5% for an 11-month deposit and 43% for a 10-month deposit, etc. There is no minimum requirement for creating a HODL deposit; however, HODL deposit transactions cost 0.1 SWIFT.

- Fast transactions featuring instant locks on zero confirmation transactions, we call it _SwiftTX_.
- Decentralized blockchain voting enabling consensus-based advancement of the current SwiftNode
  technology used to secure the network and provide the above features, each SwiftNode is secured
  with a collateral of 50,000 SWIFT.
- More information can be found at [swiftcash.cc](http://www.swiftcash.cc)
- For enquiries, please reach out to info@swiftcash.cc

### Coin Specs
|                                                      |                       |
|------------------------------------------------------|-----------------------|
| Block Time                                           | ~10 minutes           |
| Maximum Block Size                                   | ~10 MB                |
| Mining Algorithm                                     | Keccak256             |
| Difficulty Adjustment (Timespan)                     | 24 hours              |
| Difficulty Adjustment (Interval)                     | Every block           |
| v3.0 HF Reset (PoW Phase)                            | ~130,000,000 SWIFT    |
| v3.0 HF Reset (PoS Phase)                            | ~4,840,000,000 SWIFT  |
| Maximum Supply (Total)                               | 5,000,000,000 SWIFT   |
| Minimum Transaction Fee [100% Deflationary]          | 0.001 SWIFT           |
| Minimum Lottery Ticket [5% Deflationary]             | 0.01 SWIFT            |
| HODL Deposit Fee [100% Deflationary]                 | 0.1 SWIFT             |
| Proposal Fee [100% Deflationary]                     | 10 SWIFT              |
| Budget Fee [100% Deflationary]                       | 1 SWIFT               |

### Theoretical Block Rewards Distribution (after v3.0 HF/Reset)

| **Block Height** | **SwiftNodes**    | **PoS Miners**     |
|------------------|-------------------|--------------------|
| 201-2000         | 20% (~2 SWIFT)    | 80% (~8 SWIFT)     | 
| 1001-Infinite    | 20% (~31-1 SWIFT) | 80% (~125-4 SWIFT) |

### Minimum & Maximum Block Rewards

Community proposals will be allowed to use 10% of the maximum inflation for budgetting as calculated with the following formula. Another 10% goes to PoS Miners and SwiftNodes/Masternodes which is also known as the minimum inflation. The rest which is up to 80% can go to HODL deposits.

Maximum Block Rewards = (4 * 2000 * 52560) / (4 * 52560 + nHeight + 58300 - 2000)

Minimum Block Rewards = (4 * 200 * 52560) / (4 * 52560 + nHeight + 58300 - 2000)

### License
Copyright (C) 2018-2020 SwiftCash Developers <br />
Copyright (C) 2020-2021 SwiftCash Developers <br />
This software is provided as is and with no warranty under the MIT license.

### Donation Addresses
* SWIFT: `SXucSXaV5HURNyJUWnPrVFHTdRzoVff6gU`
* BTC: `1E9xPAPifPFHmVTX1pDdPLcsgub71zdpDY`
* LTC: `LYNueNhYk3VM2J9gBxCvfMgdu7xP9WdLVL`
* DOGE: `DJJ3vRLMxo9aJVe7kQDBw6nUa3KQL8zzfv`

### Support
For support, join http://discord.swiftcash.cc

### Whitepaper
To find out more about SwiftCash, consider reading our whitepaper!
https://swiftcash.cc/assets/whitepaper.pdf
