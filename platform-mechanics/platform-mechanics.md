# Platform Mechanics

[Back to Documentation](../)

This section covers how leagues and slab redemptions function on Fantasy Slab.

## League & Draft System

Fantasy Slab supports **weekly**, **monthly**, and **season-long** leagues with variable sizes and durations selectable by users. Different sports are supported, each with varying reward pool values. Special event leagues (playoffs, tournaments, etc.) will also be offered.

### League Formation

Leagues use open sign-up through the app. A league must reach at least **75% capacity** by the end of the sign-up period. If this threshold is not met, all entry purchases are refunded and league NFTs are burned.

To help leagues reach capacity, Fantasy Slab may enroll **bot players**. Bots are subject to the same fair randomization as real players and automatically draft based on insured NFT value or win probability. Bot-owned slab and reward NFTs are automatically returned to the main pool after the league ends. Bots have publicly known usernames and wallets for transparency, and real players cannot trade with bots during league play.

### Player Checklists & Draft

Each league provides a checklist of available slab NFTs and rewards at sign-up. Players receive **randomized draft positions** and draft from this checklist. Priority is given to players with higher draft order when ranking their choices. Each player typically drafts **3 cards** per league.

Drafts have a set time window. Managers who do not submit their picks before expiration are **auto-drafted**.

### Matchups & Settlement

Weekly matchups are determined within each league. Winners are calculated using a **hybrid on-chain model**.

### Winner Calculation

Fantasy Slab uses a **hybrid on-chain model** for determining league winners. Official league data and trusted third-party sources serve as the source of truth for player performance.

**Sources of Truth by Sport**

| Sport   | Primary Sources                                                         | Notes                                                    |
| ------- | ----------------------------------------------------------------------- | -------------------------------------------------------- |
| **NFL** | **NFL.com** (official), **ESPN**, **Yahoo Sports**                      | NFL.com is the most authoritative source.                |
| **MLB** | **MLB.com Stats API** (official), **Fangraphs**, **Baseball Reference** | MLB.com is the gold standard for official stats.         |
| **NBA** | **NBA.com Stats API** (official), **Basketball Reference**, **ESPN**    | NBA.com provides official box scores and advanced stats. |

Raw player stats are sourced from official league sites or trusted aggregators (such as Sportradar or ESPN). Scoring rules are clearly defined and published. Final winner calculations combine on-chain data (roster state, trades, burns, locks) with off-chain verified statistics.

### End of League

At the conclusion of a league, rewards are distributed and league entry NFTs are burned.

**Example League**\
A 1-week, 30-player league with **$5,000** in insured slab value and **$3,000** in rewards. 10 users pay a **$1,000** buy-in each. Players draft 3 cards based on randomized draft order, with priority given to higher draft positions.

## Slab Redemption Flow

League participants receive **Collector Crypt NFTs** as part of the league structure. These NFTs are pooled and distributed based on randomized draft position and signed draft transactions.

### Distribution

* NFTs are allocated to league participants according to their draft picks.
* Winners of league matchups receive additional prize NFTs representing physical items, which may include:
  * Slabs
  * Watches
  * Gacha spins
  * Other rewards

### In-League Trading & Redemption

During league play, participants can trade their slab NFT off-league or burn it through immediate redemption on CollectorCrypt. Once a slab NFT is traded or burned, it becomes ineligible for further league trades. This effectively locks the player on the manager's team for the remainder of the league period.

### Tracking & Settlement

League roster state, trades, and redemptions are tracked on-chain. Winner calculations at the end of the league duration use a hybrid model combining on-chain data with off-chain indexing for final settlement.

***

[Back to Founders Tokens](../founders-tokens/tokenomics.md) | [Back to Documentation](../)
