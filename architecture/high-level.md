# High-Level Architecture

Fantasy Slab is built on Solana with a focus on on-chain ownership, transparency, and real-world collectible utility.

## Core Components

- **$SLAB Token** — Primary token with hybrid value accrual (20% gross weekly distribution + optional buybacks/burns)
- **Slab NFTs** — Tokenized graded cards (primarily via Collector Crypt integration)
- **League Participation** — On-chain league entries and draft mechanics
- **Gacha Rewards** — Weekly and seasonal rewards delivered through Collector Crypt gachas

## Revenue Flow (High Level)

1. Users pay league entry fees in USDC
2. **20% of gross revenue** is allocated to $SLAB holders via weekly on-chain distributions
3. Remaining revenue supports slab acquisitions, gacha rewards, operations, and optional buyback/burn activity

## Value Accrual (Hybrid Model)

- **Primary**: Weekly distribution of 20% gross revenue to $SLAB holders (every Sunday)
- **Secondary (Optional)**: Buybacks and burns when the token is significantly overvalued relative to fundamentals

## Key Design Principles

- **On-Chain First** — Revenue tracking, distributions, and ownership are handled on Solana
- **Non-Custodial** — Users retain control of their tokens and NFTs via their own wallets
- **Collector-First** — Real graded slabs and gacha mechanics are central to the reward model
- **Hybrid Economics** — Direct yield to holders with flexible valuation management tools

## Technology Stack

- **Chain**: Solana
- **Token Standard**: SPL Token
- **NFT Standard**: Metaplex Token Metadata
- **Distribution Trigger**: On-chain keepers / automated flows
- **Rewards Delivery**: Collector Crypt gachas

---

[Back to Documentation](../README.md)