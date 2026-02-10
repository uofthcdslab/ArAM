ArAM User Guide
===============

This guide explains the logic behind the **ArAM Framework** and provides a worked example to demonstrate how to articulate assumptions effectively.

The Logic: Premise-Target-Differentiator
----------------------------------------

Assumptions do not exist in a vacuum; they exist as part of an **argument**. To articulate an assumption, we must distinguish between the **Premise** (the assumption itself) and the **Target** (the conclusion or goal it supports).

ArAM introduces a meta-layer called the **Differentiator** to categorize how a premise relates to a target.

The Three Differentiators
~~~~~~~~~~~~~~~~~~~~~~~~~

When analyzing a decision or goal, use these three categories to unearth hidden assumptions:

1.  **Understanding of the Target:** Assumptions about the structural understanding of the concepts (e.g., fairness, safety) that underpin the target.
2.  **Appropriateness of Performed Action:** Assumptions about why the performed action is the "right" choice compared to alternatives (e.g., doing nothing vs. intervening).
3.  **Addressal of the Target:** Assumptions about how the action logically leads to the fulfillment of the target.

Worked Example
--------------

**Source:** PaLM 2 Technical Report.
**Context:** The report authors answered "No" to a question about prioritizing specific annotator demographics.

**Step 1: Identify the Target**
* **Target:** To perform inclusive hiring of annotators.
* **Is Target Implicit?** No.

**Step 2: Articulate Assumptions using Differentiators**

+---------------------------------------------+-------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------+
| **Differentiator** | **Articulation of Assumption (Premise)** | **Analysis** |
+=============================================+=======================================================================================================+================================================================================+
| **1. Understanding of the Target** | "The default state of the world has equal representation. So there is no need to prioritize any group." | The assumer understands "inclusivity" as a baseline state that exists naturally. |
+---------------------------------------------+-------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------+
| **2. Appropriateness of Performed Action** | "Of several actions (e.g., leveling up/down), doing nothing is the most appropriate action."          | Justifies inaction as superior to active intervention strategies.              |
+---------------------------------------------+-------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------+
| **3. Addressal of the Target** | "When no group is explicitly prioritized, hiring is inclusive."                                       | Links the action (not prioritizing) to the success of the target.              |
+---------------------------------------------+-------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------+

*Table adapted from Mothilal et al. (2025)*.
