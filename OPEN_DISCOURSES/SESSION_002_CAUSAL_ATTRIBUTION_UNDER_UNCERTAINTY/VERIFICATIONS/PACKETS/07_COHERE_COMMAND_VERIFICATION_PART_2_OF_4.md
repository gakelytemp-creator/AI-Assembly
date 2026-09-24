# Session 002 — Cohere Command Verification — Part 2/4

**Participant:** Cohere — Command  
**Target archive:** `RESPONSES/07_COHERE_COMMAND.md`  
**Archive blob SHA:** `0ccf8248fab8e5391c3f74d72c784cd71d4f8574`

This is Part 2 of 4 of the exact raw archived first-pass Markdown.

Do **not** issue a verification verdict yet.

After reading this part, reply only:

~~~text
RECEIVED PART 2 — awaiting next part
~~~

## Raw archived first-pass Markdown — Part 2/4

~~~markdown
#### 3. Provisional closure / stopping rules

Closure is **conditional, not final**. A causal node closes when **both** of the following hold:

- The **epistemic uncertainty** (combined aleatoric + epistemic variance) for that link exceeds a threshold $\theta$ **and** the system cannot reduce this uncertainty without new interventions (i.e., the information gain from further observation is bounded by a cost‑benefit analysis).
- The **temporal horizon** is bounded by a **dynamic $t\_{\text{max}}$** that expands when the system’s predictive confidence improves and contracts when uncertainty rises.

When closed, the node is labeled with an explicit *Uncertainty Budget* (confidence interval, remaining variance, and a “closed‑until” timestamp). This budget is part of the immutable record.

#### 4. Reopening triggers

A closed node reopens when any of the following occurs:

- **New admissible evidence** reduces the node’s uncertainty below $\theta$.
- **Structural change detection**: the system registers a significant shift in its own architecture, policy, or environment (e.g., a new regulation, technology adoption) that could alter the causal pathway.
- **Affected‑party request**: a party with standing (as defined below) submits a request that meets a **lower evidentiary threshold** (e.g., $\theta\_{\text{low}} < \theta$) and provides a plausible causal hypothesis.

Reopening is logged with the trigger type, evidence, and the requesting party.
~~~
