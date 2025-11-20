# The Enough is Enough Pledge

This repository hosts the [Lightning Path](https://spiritwiki.lightningpath.org/index.php/Lightning_Path) "Enough is Enough" pledge—a public commitment to move from endless accumulation to conscious healing and connection. By declaring a personal income cap and routing surplus to dedicated [Repair Funds](https://spiritwiki.lightningpath.org/index.php/Repair_Fund) and [Regeneration Funds](https://spiritwiki.lightningpath.org/index.php/Repair_Fund), participants actively dismantle the growth-at-all-costs paradigm. 

## The Philosophy

By creating a pledge here, you are making a conscious choice to:

*   **Reject the Infinite Growth Paradigm:** Acknowledge that personal and planetary well-being requires sufficiency, not endless accumulation.
*   **Embrace a Dual-Mandate:** Address both the wounds of the past (**Repair**) and the need to build resilient, connected futures (**Regeneration**).
*   **Operate with Radical Transparency:** Make your commitment and its execution visible and accountable through public ledgers.
*   **Build a New Pattern:** Create a replicable model for using capital as a tool for healing and connection, not enrichment and disconnection.

Through transparent ledgers and community accountability, we're building a practical framework for economic transformation that prioritizes human and planetary well-being over perpetual expansion.

## How to Join the Movement

### 1. Fork and Setup
Fork this repository to your own GitHub account. You will be working within your fork to create your pledge.

### 2. Create Your Pledge Directory
In the `pledges` directory, create a new folder named with your GitHub username (e.g., `pledges/octocat/`).

### 3. Populate Your Files
Copy the pledge template from the `templates` directory into your new folder and personalize it.

| File | Purpose |
| :--- | :--- |
| `pledge.md` | Your personal declaration and "Enough Number." |
| `repair-fund-charter.md` | This fund is for direct restitution and healing. It addresses the harm caused by the extractive economy. Think of it as "composting" the damage of the past. Its focus is on **justice and healing**.<br>*Examples:* Supporting indigenous land back initiatives, funding community reparations projects, providing direct aid to those impacted by ecological disaster, supporting worker advocacy groups. |
| `regeneration-fund-charter.md` | This fund is for building the new. It invests in the infrastructure, models, and mindsets of a connected, life-affirming future. Its focus is on **resilience and creation**.<br>*Examples:* Funding community land trusts, investing in open-source public interest technology, supporting regenerative agriculture projects, funding cooperative business start-ups. |
| `repair-fund-ledger.csv` | The transparent ledger for all Repair Fund transactions. |
| `regeneration-fund-ledger.csv` | The transparent ledger for all Regeneration Fund transactions. |

### 4. Commit and Propose
Commit your changes to your fork and submit a Pull Request to the main repository. Once merged, your pledge will be listed below on the [Pledges](./pledges.html) page.


### The Two Funds

To effectively channel surplus, we recommend separating your capital into two distinct funds, each with a clear purpose:

1.  **The Repair Fund:** This fund is for direct restitution and healing. It addresses the harm caused by the extractive economy. Think of it as "composting" the damage of the past. Its focus is on **justice and healing**.
    *   *Examples:* Supporting indigenous land back initiatives, funding community reparations projects, providing direct aid to those impacted by ecological disaster, supporting worker advocacy groups.

2.  **The Regeneration Fund:** This fund is for building the new. It invests in the infrastructure, models, and mindsets of a connected, life-affirming future. Its focus is on **resilience and creation**.
    *   *Examples:* Funding community land trusts, investing in open-source public interest technology, supporting regenerative agriculture projects, funding cooperative business start-ups.

| Feature          | **Repair Node**                                   | **Regeneration Node**                           |
| ---------------- | ------------------------------------------------- | ----------------------------------------------- |
| **Purpose**      | External restitution                              | Internal development                            |
| **Rubric**       | Repair Rubric (7/10 threshold)                    | Regeneration Rubric (8/10 threshold)            |
| **Source**       | Overflow from Enough Pledge                       | Explicit development pledges, optional overflow |
| **Governance**   | Weighted comments, 7-day issues                   | Same mechanism, separate repo                   |
| **Funding LP?**  | **No** (except as community-controlled IRL space) | **Yes** (animations, curriculum, tools)         |
| **Transparency** | Public ledger, monthly audit                      | Public ledger, monthly audit                    |
| **License**      | GPL v3.0                                          | GPL v3.0                                        |


### The Pledge Workflow

1.  **Declare:** Set your "Enough Number" in `pledge.md`.
2.  **Calculate:** Periodically (e.g., quarterly) calculate your surplus: `Income - Enough Number = Surplus`.
3.  **Allocate:** Decide how to split your surplus between the Repair Fund and Regeneration Fund (e.g., 50/50, 70/30).
4.  **Transfer:** Move the allocated funds to your real-world bank/brokerage accounts designated for each purpose.
5.  **Deploy & Log:** Donate or invest the funds according to your charters and log every transaction in the respective CSV ledger with date, amount, recipient, and purpose.

---

*This is a prototype for a new economic practice. Last updated: {{ site.time | date: "%Y-%m-%d" }}*


**License: GPL v3.0**  
This is not a product. It is a protocol. You cannot own it. You can only fork it, improve it, and keep it open.

## What This Repo Is
- **Code**: Allocation logic, GitHub Action scripts for auto-publishing transactions, issue templates for proposals.
- **Content**: The Repair Rubric, Enough Pledge template, audit transcripts. *All content is also GPL'd—no CC-BY dual license.* If you remix the theory, you must share alike.

## What You Cannot Do
- **Cannot** repackage this as a proprietary SaaS for "ethical giving."
- **Cannot** add a clause requiring attribution to "Lightning Path" in your fork (GPL allows removal of branding).
- **Cannot** sue us if the protocol fails. You inspect at your own risk.

## What You Must Do
- **Must** publish your fork's allocations, velocity, and burn if you distribute it.
- **Must** keep governance issues and audit calls public if you run a node.
- **Must** credit the source in your first commit message, then you're free to erase our name.

**This is a Gordian Knot. The license is the sword.**
