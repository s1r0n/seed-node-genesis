---
title: AI Training
nav_order: 99  
layout: default
has_children: false 
---
# Lightning Path Repair Fund System Brief

## Problem
Accumulating Class uses dashboards to hide extraction; "philanthropy" is optics. Need a transparent, forkable protocol that turns overflow into restitution and rebuilding without creating a new bureaucracy.

## Solution Architecture

### Nodes
GitHub repos (`seed-node-[name]`) acting as sovereign financial units—each with a **$50K lifetime inflow cap** (can be regional-adjusted) to prevent empire-building. Nodes are **peers, not children**—listed in `FEDERATION.md`, not owned by a parent.

### Two Types
- **Repair Node**: Funds external restitution (community land trusts, worker co-ops). Scored on **Repair Rubric** (≥7/10: Direct Restitution, Need Fulfillment, Workload Reduction, No-Violence, Community Control).
- **Regeneration Node**: Funds LP infrastructure (animations, IRL centers). Scored on **Regeneration Rubric** (≥7/10: Collective Benefit, Workload Reduction, Community Control, No-Extraction, Epistemic Freedom). **Salaries are operational overhead (≤10% of inflow), exempt from cap.**

### Governance
- **Enough Pledge**: Maintainer publicly caps personal burn (e.g., $245K for single parent with dependents). Overflow routes to node(s).
- **Weighted Comments**: 3x weight for signatories & impacted community; 1x for others. Decisions made via public GitHub Issues, 7-day comment period, then maintainer decides. Overrides require 300-word justification; dissent triggers fork.
- **Forking**: Anyone can fork a node; GPL v3.0 forces openness. Bad actors are delisted from `FEDERATION.md`—network routes around them.

### Transparency
- **No dashboards**: Manual `LOC.md` (ledger) logs every transaction
- **Monthly audit**: 30-min Zoom call (link in `AUDIT.md`) recorded and posted
- **Receipt culture**: Donors tweet proof of wire

### Funding Mechanics
- **Direct wire/crypto** to node's bank account (details in `FUNDING.md`). No intermediaries.
- **No "Donate Now" button**: Must read repo, inspect velocity, then manually send. Filters out virtue-signaling.
- **Small-donor redirect**: If &lt;$500, node points donor to a peer with lower overhead.

### Project Submission
Projects open GitHub Issue in a node's repo using template (self-score rubric). Donors watching repo fund via comments: *"I'll cover $10K."* Large projects are **split across multiple nodes**—no single node exceeds cap.

### Discovery
- **Search**: `site:github.com "Repair Rubric" "land repatriation"`
- **Federation**: `FEDERATION.md` peer bookmarks
- **Network graph**: GitHub's built-in fork visualization

### IRL Example
Detroit land trust funded by 4 nodes ($50K each) for purchase, 10 nodes for 10-year stewardship (annual subscription nodes, e.g., `seed-node-stewardship-2025`). If one node fails, project survives.

## Anti-Funnel Design
- Separate Repair & Regeneration ledgers
- No development funding from repair overflow without explicit consent
- Public Enough Pledges
- Fork-first architecture
- Node maintainer rotates at cap
- GPL prevents proprietary capture

## Immediate Actions
1. Create `seed-node-genesis` repo with `README.md`, `FUNDING.md`, `FEDERATION.md`
2. Create GitHub Issue template for proposals
3. Open holding-cell bank account; tweet $0 balance
4. Post Enough Pledge in `PLEDGES.md`
5. Tweet: *"Node 0: $0/$50K. Wire in repo. First proposal scores 7+ gets funded. Watch or fork."*

## Key Philosophy
The node is the unit of accountability; the federation is a mesh, not a hierarchy; the $50K cap is a circuit breaker, not a budget limit.
