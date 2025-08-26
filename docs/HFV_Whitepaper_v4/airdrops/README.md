# Airdrops — HFV Protocol  

📅 Updated: 26 August 2025  

## Allocation
- **15% of supply** = 10,500,000 HFV  
- Reserved for early contributors, community members, and stakers.  

---

## Technical Implementation
- **AirdropConfig.sol** — Stores distribution config.  
- **MerkleDistributorVesting.sol** — Verifies claims + enforces vesting.  
- **generate-merkle.ts** — Builds Merkle root from CSV, outputs proofs JSON.  

---

## Rules
- All engaged community members and stakers are eligible.  
- DAO decides schedule and allocation per round.  
- Higher-tier stakers influence timing/amounts.  
- Anti-dump: governance rights lost if tokens are sold too fast.  

---

## Transparency
- Proof JSONs published before each distribution.  
- DAO sets Merkle root on-chain.  
- Claim + vesting events logged permanently.

