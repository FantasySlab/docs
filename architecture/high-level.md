# High-Level Architecture

Fantasy Slab is built on Solana with a focus on on-chain ownership, transparency, and collectible utility.

## Core Components

- **Founders NFT** — 100 premium NFTs that receive weekly revenue share airdrops
- **League Spot NFTs** — Represent participation in 10-man leagues (separate from Founders NFT)
- **Slab NFTs** — Tokenized graded cards on Collector Crypt
- **Gacha Rewards** — Weekly and seasonal rewards delivered as Collector Crypt gachas

## Revenue Flow (High Level)

1. Users pay league entry fees in USDC
2. 8% of gross revenue is allocated to Founders NFT holders
3. Remaining revenue supports slab acquisitions, gacha rewards, and platform operations

## Key Design Principles

- **On-Chain First** — Revenue tracking, airdrops, and ownership are handled on Solana
- **Non-Custodial** — Users retain control of their NFTs via their own wallets
- **Collector-First** — Slab NFTs and gachas are central to the reward and utility model

## Technology Stack

- **Chain**: Solana
- **NFT Standard**: Metaplex Token Metadata
- **Airdrop Trigger**: Switchboard Keepers (decentralized)
- **Rewards Delivery**: Collector Crypt gachas

---

[Back to Documentation](../README.md)
