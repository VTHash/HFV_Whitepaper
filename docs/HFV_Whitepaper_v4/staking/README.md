# Staking — HFV Protocol  

📅 Updated: 26 August 2025  

## Overview
HFV staking incentivizes long-term alignment.  
Users lock HFV tokens in **tiered staking contracts**, receiving rewards and governance rights.

---

## Tiers
- **Tier 1** → 21 days  
- **Tier 2** → 3 months  
- **Tier 3** → 6 months  
- **Tier 4** → 12 months  

---

## Rewards
- Rewards scale with **lock duration**.  
- Rewards are automatically distributed on claim.  
- Higher-tier stakers = stronger governance rights.  

---

## Claiming
- Tokens + rewards are claimable once lock expires.  
- DAO anti-dump rule applies (selling >25% = loss of rights).  

---

## Smart Contract Functions
- `stake(uint256 amount, uint256 duration)`  
- `claim(uint256 index)`  
- `getPendingReward(address, uint256)`  
- `getStakeCount(address)`  
- `getStakedAmount(address, uint256)`