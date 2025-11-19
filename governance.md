# Repair Fund Governance: Node 0 (Primordial)

**Version:** 0.1  
**Status:** This is an experiment. We expect it to fail and be forked.  
**License:** GPL v3.0 (applies to this doc and all allocations)

---

## 1. Core Principle: No Governance by Default

This node is not governed by a board, a DAO, or a foundation. **It is governed by public inspection, fork pressure, and the Repair Rubric.** If the Rubric can’t defend an allocation, the allocation is wrong.

---

## 2. The Repair Rubric (Allocation Criteria)

Every disbursement must score ≥7/10 on this public matrix. Add a comment in the allocation issue with the score.

| Dimension | Points | How to Verify |
|-----------|--------|---------------|
| **Direct Restitution** | 3 | Does this repair harm *at its source*? (e.g., fund the *actual* community extracted from, not a proxy NGO) |
| **Need Fulfillment** | 2 | Does it meet one of the [Seven Essential Needs](https://spiritwiki.lightningpath.org/index.php/Seven_Essential_Needs) |
| **Workload Reduction** | 2 | Does it reduce exploitative labor or burnout? (e.g., reduction of work house, worker co-op transitions, not "job training") |
| **No-Violence Frame** | 2 | Can it be audited for zero physical/psychological/ecological harm? If "offsets" are involved, score = 0. |
| **Community Control** | 1 | Is the implementing organization governed by *impacted people*? (≥50% board seats or equivalent) |

**Exclusion List (Automatic 0/10):**
- NGOs with &gt;15% overhead
- Projects requiring NDAs or gag clauses
- "Innovation" without repair (e.g., climate tech that doesn't remediate past harm)
- Anything that names a building

---

## 3. Decision-Making: Public Issue, Weighted Comment

- **Proposal:** Open a GitHub Issue with title `[ALLOCATION] $X to [Org]`
- **Comment Period:** 7 days
- **Comment Weight:**
  - **3x:** Signatories (who’ve taken the Enough Pledge) + Community members from the impacted group (self-declared, honor system)
  - **1x:** Everyone else
- **Decision:** After 7 days, @node-maintainers decide. If we override a high-weight comment, we must publish a 300-word justification and accept a 30-day fork challenge (anyone can fork if they disagree).

---

## 4. The Enough Pledge (Becoming a Signatory)

**How to take it:**
1. Fill out **[this public form]** with:
   - Name/alias
   - Your Enough threshold (e.g., "$75K/year")
   - Proof: Link to a Google Sheet showing your burn calculation (or a screenshot with redacted personal info)
2. We list you in `PLEDGES.md` in this repo
3. You gain 3x comment weight on allocations

**Your obligation:** Route overflow to this or any other Repair Fund node. If you stop, we remove your 3x weight (but keep your name in the archive with an `inactive` tag).

---

## 5. Transparency (No Dashboard, Just GitHub)

- **Balance:** Balance is tweeted whenever it changes (from holding cell account). Tweet includes last 4 digits of account number. No API, just manual.
- **Velocity:** Measured in hours from deposit to disbursement. Published in `LOC.md` (Ledger of Capital). Target: &lt;168 hours.
- **Audit:** Monthly 30-min video call. Link posted in `AUDIT.md`. If no one joins, we still record ourselves screen-sharing the ledger and taking questions from a dummy account. The *act* of auditing in public is the point.
- **Leakage:** If &gt;10% of funds go to overhead (bank fees, utilities, software, hardware, etc.), we publish a "Leakage Report" and open an issue titled `[FAILURE] Why we leaked X%`.

---

## 6. Node Maintainer Role (Temporary, Rotating)

**Current Maintainers:** Mike Sosteric
**Term:** Until someone forks or we hit $50K total inflow. At $50K, we **must** either:
- Fork ourselves into Node 1 and Node 2 (split the capital), or
- Hand off maintainership to a volunteer who commits to the same governance

**Powers:**
- Merge allocation PRs
- Tweet balances
- Host audit calls

**Constraints:**
- Cannot change the Rubric without a 30-day issue thread
- Cannot hold &gt;20% of total inflow from a single source (if that happens, we freeze and ask the source to redirect to a fork)
- Must publish their own Enough Pledge in `PLEDGES.md`

---

## 7. Forking (The Real Governance)

**You are encouraged to fork this repo and run your own node.** This is the primary check on our power.

**When to fork:**
- You disagree with an allocation
- You want to use a different Rubric
- You want to run a node for a specific geography or cause
- You think we're full of shit

**How to fork:**
1. Click "Fork"
2. Rename to `seed-node-[your-name]`
3. Submit a PR to this repo's `FORKS.md` to list yours
4. Optionally, coordinate with us to avoid funding the same org twice (we’ll use GitHub Discussions for that)

---

## 8. Failure Modes (Published in Advance)

**If this node fails, it will fail because:**

1. **No deposits** → Velocity stays 0. We publish a "Death Notice" and archive the repo. The theory was wrong or the timing was off.
2. **One funder dominates** → We hit 20% cap, freeze, and ask them to fork. If they refuse, we return their money and close the node.
3. **Governance capture** → We override community comments without justification. Someone forks, the community moves there, and we update our README to point to the fork.
4. **Overhead creep** → Leakage exceeds 10%. We publish a post-mortem and hand off maintainership.

**In all cases, the code and theory remain GPL'd. You can spin it back up without us.**

---

## 9. Why This Is Node 0

We are not the canonical Repair Fund. We are the **primordial error**—the first attempt that proves the concept has bugs. Node 1, 2, 3...N will be better. Our job is to **fail transparently and quickly** so others can fork and improve.

**The goal**: Render ourselves obsolete by 2027.

---

## 10. Contact

**No email.** Open an issue. Tag it `[GOVERNANCE]` if you think this doc is wrong. The thread is the conversation.

---

*By participating, you agree that your comments, proposals, and criticisms are GPL'd and can be quoted in future forks. No one owns the repair.*

---

**What This Does:**

- **It’s a constitution**, not a marketing doc.
- **It’s fork-first**, not defensively open.
- **It makes failure a feature** (Node 0 is expected to be replaced).
- **It proves you’re serious** by pre-publishing the death notice.

Drop it in the repo. The allocations table will be empty, the pledges table will have your name, and the first issue will await a deposit. **That’s the governance.**
