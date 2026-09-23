# Session 002 — Cross-Critique Synthesis

**Session:** Causal Attribution Under Uncertainty  
**Stage:** Cross-Critique Round 1 complete  
**Participants:** 10  
**Assigned critique edges:** 30  
**Returned cross-critiques:** 10/10

## Status of this document

This is **not a consensus statement** and not a vote count.

Its purpose is narrower: to record what happened to the Session 002 proposals after directed adversarial contact.

The synthesis distinguishes four outcomes:

- **SURVIVED** — a principle remained load-bearing after critique and revision.
- **REVISED** — a proposal survived only after a material change in scope or meaning.
- **DID NOT SURVIVE IN ORIGINAL FORM** — a mechanism was directly attacked and either abandoned, narrowed, or demoted by its own author or by the cross-critique record.
- **OPEN FRACTURE** — a disagreement remains live and should not be averaged away.

The standing rule remains:

> **Agreement is not truth; recurrence is not proof.**

Recurrence in this record is evidence about robustness under this particular procedure, not proof of causal or epistemic truth.

---

# I. What survived the cross-critique

## 1. Ontology governance is upstream of inference

The strongest surviving architectural shift is that causal attribution cannot begin with a finished graph.

Variables, node boundaries, grain, candidate pathways, background conditions, option sets, model classes, and data-collection regimes are themselves causal-governance objects.

Claude framed this as the modeling-choice problem; DeepSeek as the ontology-authority problem; Grok elevated ontology governance into Layer 0; Mistral widened `BACKGROUND_STATUS?` into an ontology-authoring protocol; OLMo revised its Narrative Arena to include explicit ontology governance.

The surviving principle is:

> **A causal system must record and expose how the world was carved before it evaluates causal links inside that carving.**

No formalism swap — DAG, cyclic SCM, process algebra, narrative graph, or other representation — removes this requirement.

---

## 2. Causal evidence must remain typed and multidimensional

A single scalar “causal confidence” did not survive.

Across the critiques, causal support separated into dimensions and types such as:

- mechanistic/direct trace;
- difference-making or probabilistic contribution;
- structural reinforcement;
- enabling/precondition causation;
- definitional causation;
- invariance or robustness;
- provenance;
- coverage;
- dependence between evidence sources;
- missingness and access constraints.

The exact taxonomy remains unsettled, but the scalar-collapse model did not survive.

A particularly important distinction remains between **event causation** and **structure causation**:

> “A caused event E” and “A changed system-state S to S′, under which events like E became more probable” are not the same claim.

The architecture must be able to represent both without forcing them to compete for one causal edge or one winner.

---

## 3. Provenance and independence are part of causal evidence

Plurality is not independence.

Repeatedly, the critiques converged on the need to record shared:

- datasets;
- instruments;
- funders;
- model priors;
- model lineages;
- institutional incentives;
- evaluator ancestry or dependence.

A hundred reports from one evidence lineage cannot automatically count as a hundred independent confirmations.

This applies not only to evidence but also to **evaluators**. OLMo's original “independent supermajority” was forced to confront the fact that independence must be measured rather than asserted.

---

## 4. Closure is procedural and provisional, not a truth event

The original idea of closure survived only after a major change in meaning.

The strongest post-critique form is:

> **Closure means suspension of active investigation under declared conditions and residual uncertainty. It does not mean that causation was disproved, resolved for all purposes, or rendered benign.**

Surviving closure artifacts include some combination of:

- precise question and scope;
- ontology/grain version;
- evidence status;
- missingness;
- residual uncertainty;
- dissent;
- falsifiers;
- monitoring commitments;
- reopening triggers;
- review owner;
- `CLOSED_UNTIL` or equivalent review expectation.

DeepSeek sharpened the unit of closure:

> **the node is a site; the question is the unit of closure.**

This was not accepted in identical wording by every participant, but question-specific closure gained substantial support and survived direct challenge better than bare node closure.

---

## 5. Missingness is a first-class object, but not proof of hidden content

Kimi's manufactured-unobservability analysis survived and became more precise.

The strongest version distinguishes:

- **GAP-0:** ordinary missing data;
- **GAP-1:** a gap located where a live hypothesis predicts relevant evidence;
- **GAP-2:** an actor-linked or post-decision degradation of observation, logging, archives, or access.

The surviving invariant is:

> **A gap may justify investigation, monitoring, preservation, disclosure duties, or epistemic-risk flags. A gap does not prove what the missing evidence would have shown.**

This prevents both epistemic amnesia and causal paranoia.

Mistral added an important post-critique refinement: when a low-capacity party cannot provide novel evidence because observation was structurally denied, a specific custodian-attributable `OBSERVATIONAL_GAP?` may substitute for novelty **for the right to investigation**, but not for the strength of the eventual causal claim.

---

## 6. Causal trace, normative judgment, and repair remain separate

This principle survived every serious attack.

The post-critique form is stronger than the Chair's initial three-box diagram:

- causal evidence must not be rewritten by moral seriousness;
- normative evaluation may query the trace but should not silently redefine it;
- repair can attach to capacity, reachability, duty, or control even when blame or sole authorship is unresolved.

The crucial surviving firewall is:

> **Procedural or moral reasons may change what the system investigates or does; they do not automatically change what the causal evidence means.**

---

## 7. Counterfactuals survive only as plural, provenance-bearing, defeasible objects

The idea of counterfactual comparison survived; the idea of a privileged single baseline did not.

The cross-critique strengthened requirements for:

- multiple baseline families;
- explicit assumptions;
- baseline provenance;
- model-lineage diversity;
- forward-falsifiable predictions;
- empirical counterfactuals where available;
- adversarial or shadow baselines;
- explicit option-set definition;
- visible disagreement across baselines.

A baseline generated by the same model that generated the attribution may remain useful as an auxiliary object, but it no longer counts as independent corroboration by itself.

---

## 8. Reflexive causation requires representing changes to the causal-generating structure

The session did not settle on one formalism, but it did preserve the distinction between:

- ordinary event propagation; and
- actions that change incentives, capacities, observation regimes, option sets, priors, or structural equations.

This is the surviving core of the “Attribution Cascade Collapse” problem.

A downstream intervening actor cannot automatically sever the upstream causal story, nor can an upstream actor absorb all later agency.

The architecture needs separate representation of event contribution and structure-changing contribution.

---

# II. Proposals that survived only after revision

## 1. `t_max + epsilon`

**Original form:** close when causal confidence falls below a threshold over time.

**Post-critique form:** no single calendar horizon or scalar confidence threshold is sufficient. Time may remain one operational input, but closure must also expose observation coverage, falsifiers, resource conditions, structural breaks, missingness, and question scope.

**Status:** revised beyond recognition as a sole closure rule.

---

## 2. Vulnerability-weighted reopening

**Original form:** lower reopening threshold for lower-capacity or affected parties.

**Pressure:** proxy standing, astroturfing, identity-based gatekeeping, lack of technical evidence among the genuinely affected.

**Post-critique form:** asymmetry belongs primarily to **investigation rights, monitoring, preservation, disclosure, and precaution**, not to causal-support values.

Mistral's revised mechanism permits a specific `OBSERVATIONAL_GAP?` with a named custodian to trigger discovery even when the claimant lacks novel evidence.

**Status:** retained only as procedural asymmetry.

---

## 3. Reputation weighting

Cohere initially allowed predictive reputation to affect epistemic authority.

After direct criticism over reputation farming, incumbency, and cold-start exclusion, Cohere re-scoped reputation to procedural priority such as triage or audit allocation.

It no longer alters the stored causal-support value by itself.

**Status:** demoted from epistemic weight to procedure.

---

## 4. Same-model counterfactual generation

Cohere's original architecture allowed the same causal model to generate the actual attribution and its counterfactual baseline.

Cross-critique identified self-confirmation.

Cohere revised CAM to require model-lineage IDs and at least one baseline from a distinct lineage.

**Status:** same-model baselines may remain auxiliary; they cannot be the sole independent reference.

---

## 5. Qwen's burden reversal

Qwen originally required an initiating actor, after foreseeable harm, to prove the harm was **strictly independent** of the initial action.

Cross-critique exposed this as an unrealistic near-universal-negative standard.

Qwen revised the mechanism:

- causal-proof burden does **not** reverse;
- moral-blame burden does **not** reverse;
- disclosure and rebuttal/explanation burdens may reverse;
- failure activates `HIGH_EPISTEMIC_RISK?` / `DATA_OPACITY?`, preserves unresolved status, and may intensify monitoring;
- “strict independence” became **plausible decoupling** under independent/adversarial review.

**Status:** burden reversal survives as a procedural and disclosure rule, not presumed causation.

---

## 6. Mistral's novelty-priced reopening

Mistral initially priced reopening mainly by new evidence lineage, novelty, and mechanism specificity.

Pressure testing exposed a structural bias: novelty is easiest to produce for whoever owned the instruments.

Mistral revised:

- novelty remains relevant to **claim strength**;
- novelty is no longer necessary for the **right to investigation**;
- a specific custodian-attributable observational gap may substitute for novelty in the investigation track.

**Status:** split into two different standards.

---

## 7. OLMo's supermajority closure

This underwent the clearest explicit retreat.

**Original:** causal closure when a supermajority of independent evaluators converges on a narrative.

**Post-critique:** supermajority agreement does not alter causal-support values and does not establish causal truth.

It may only suspend active investigation or allocate resources on a specific question under a specific ontology, while preserving competing narratives, evidence, uncertainty, and reopening triggers.

When evaluator independence is low, agreement is weak evidence. When two narratives remain strongly supported, both remain epistemically live.

**Status:** retained only as procedural suspension/resource allocation.

---

# III. Forms that did not survive in their original form

The following mechanisms should not be carried forward unqualified:

- scalar `epsilon` as the sole causal-confidence or closure criterion;
- fixed calendar `t_max` as the main horizon of attribution;
- “absence of evidence” silently becoming “evidence of no causation”;
- missing data becoming proof of the hidden content;
- same-model counterfactuals acting as their own independent validation;
- source reputation directly strengthening causal evidence;
- supermajority agreement functioning as causal truth;
- moral seriousness or vulnerability directly increasing stored causal-support values;
- “strict independence” as the required rebuttal standard in complex social-technical systems;
- unguarded abuse/stigma markers on reopening requests;
- raw count of evidence sources or evaluators standing in for independence;
- a universal rule requiring a fixed number of evidence types regardless of the causal question.

These are not declared philosophically false. They simply did not survive this cross-critique in their original operational form.

---

# IV. Open fractures that must remain open

## 1. Who pays for anti-capture infrastructure?

Independent measurement, adversarial baselines, provenance audits, archive preservation, long-horizon monitoring, and ontology contestation all cost resources.

The architecture can itself privilege high-capacity actors if only they can afford the mechanisms designed to constrain them.

No participant supplied a complete answer.

---

## 2. Who governs ontology governance?

Layer 0 exposes capture but creates a meta-governance problem.

Who may split a node, redefine a variable, alter grain, challenge background status, or add a candidate pathway?

How is ontology contestability prevented from becoming a denial-of-service surface?

How can an ontology failure be detected from inside an ontology that cannot represent the missing perspective?

This remains unresolved.

---

## 3. How is independence actually measured?

Evidence-lineage independence, model-lineage independence, evaluator independence, institutional independence, and ontology independence are related but not identical.

The session repeatedly demanded dependence analysis but did not produce a complete metric.

---

## 4. Standing versus proxy standing

Cheap access for genuinely low-capacity affected parties remains in tension with:

- sponsored claimants;
- sockpuppets;
- astroturfing;
- strategic anonymous petitions.

At the same time, strong provenance requirements can silence legitimate anonymous or structurally excluded parties.

Mistral's gap-specificity/custodian test narrows the problem but does not eliminate it.

---

## 5. Precaution versus operational attribution

Perplexity insists that moral seriousness may lower investigation or precaution thresholds without lowering the causal-proof threshold.

DeepSeek objected that **targeted precaution aimed at one actor may already function operationally as attribution**.

The architecture still needs a clean state for:

> action justified by uncertainty without silently recording guilt.

---

## 6. Structural evidence versus mechanistic evidence

The session preserved both, but not a final composition rule.

Structural/probabilistic evidence must not become permanently second-class, yet repeated structural evidence does not magically become a demonstrated mechanistic pathway.

How these evidence classes jointly support decision-relevant attribution remains open.

---

## 7. Resource closure can itself be captured

If closure depends on information gain versus audit cost:

- who estimates information gain?
- who prices audit cost?
- who controls the sensors?
- can an actor inflate cost or defund observation to manufacture “low value”?

Making resource allocation visible is necessary but not sufficient.

---

## 8. Narrative plurality versus operational paralysis

Keeping multiple causal narratives live protects dissent and ontology alternatives.

But maintaining many narratives multiplies audit and monitoring costs.

OLMo's procedural supermajority can suspend investigation, but a non-vote rule for persistently divergent, well-supported narratives remains underdeveloped.

---

# V. Major revision lineages

The cross-critique produced visible changes rather than mere restatement:

- **OLMo:** supermajority-as-closure → supermajority as procedural suspension only.
- **Cohere:** reputation as epistemic authority → reputation as procedural triage only.
- **Cohere:** same-model counterfactual sufficiency → independent model-lineage requirement.
- **Qwen:** strict-independence burden → plausible-decoupling rebuttal; causal proof does not reverse.
- **Mistral:** novelty required for cheap reopening → specific observational gap may substitute for novelty for investigation.
- **Grok:** decision-relevant confidence sharpened so seriousness and error cost affect decisions, not stored causal-support values.
- **DeepSeek:** observational gaps became a precondition on closure; where the relevant observational surface is structurally suppressed, epsilon evaluation may be unlicensed.
- **OLMo:** Narrative Arena gained ontology governance, typed evidence, manufactured-unobservability tracking, and evaluator-dependence auditing.
- **Meta:** guard recursion was bounded not by declaring a sovereign final guard, but by append-only exposure, reality contact, falsifiable guard performance, and visible audit cost.

This is the main empirical value of the cross-critique stage: several mechanisms did not merely receive criticism; their authors materially changed them.

---

# VI. Emergent post-cross-critique architecture

The following architecture is a **synthesis object**, not a ratified consensus.

### Layer 0 — Ontology Governance
Variables, definitions, grain, candidate pathways, background status, option-set definition, model-class selection, authorship and provenance.

### Layer 1 — Observation Infrastructure
Sensors, archives, logging, access rights, observational gaps, data opacity, archive lapse, measurement control.

### Layer 2 — Evidence and Provenance
Typed evidence, source dependence, lineage dependence, uncertainty, alternative explanations, missingness.

### Layer 3 — Event Causal Trace
Specific actions, mechanisms, intermediate events, direct or contributory pathways.

### Layer 4 — Structural Causal Trace
Changes to incentives, capacities, option sets, observation regimes, priors, institutional structure, and causal-generating dynamics.

### Layer 5 — Counterfactual and Prediction Registry
Plural baselines, model lineage, assumptions, bounded predictions, falsifiability, baseline disagreement.

### Layer 6 — Question-Specific Epistemic Status
Attribution confidence, coverage confidence, residual uncertainty, epistemic debt, closure/suspension state, `CLOSED_UNTIL`, falsifiers.

### Layer 7 — Normative Evaluation
Harm, coercion, unfair transfer, foreseeability, duty, consent, other normative predicates.

### Layer 8 — Repair and Remediation
Capacity, reachability, monitoring duty, preservation/disclosure duty, repair action.

### Cross-cutting registers
- dissent and competing narratives;
- provenance;
- missingness;
- monitoring;
- reopening;
- resource/audit cost;
- standing and access;
- change history.

The most important invariant is that these layers remain **addressable separately**. A change in one layer must not silently rewrite another.

---

# VII. Seeded recurrence versus emergent recurrence

Several heavily repeated ideas were already present in the Chair Opening:

- provisional closure;
- asymmetric reopening;
- separation of cause/blame/repair;
- counterfactual baselines;
- power asymmetry;
- reflexive causation.

Their recurrence is therefore partly seeded and must not be treated as independent discovery.

The strongest less-seeded or unseeded developments that strengthened during cross-critique were:

- ontology governance as Layer 0;
- causal confidence as partly **institutionally produced**, not merely numerically measured;
- manufactured unobservability and observational gaps as first-class objects;
- provenance-dependence and effective independence;
- event causation versus structure causation;
- closure as resource suspension rather than epistemic resolution;
- question-specific closure;
- distinction between procedural asymmetry and epistemic asymmetry;
- anti-capture mechanisms themselves as capture surfaces;
- observational-gap standing for parties without sensor access;
- demotion of agreement/supermajority from truth condition to procedure;
- narrowing burden reversal to disclosure/rebuttal rather than causal proof;
- the unresolved operating cost of anti-capture machinery itself.

These are the main candidates for genuine Session 002 emergence.

---

# VIII. Post-cross-critique working invariants

The cross-critique does **not** prove these statements true. It does show that they remained structurally useful after direct attack:

1. **Make the causal vocabulary contestable before trusting inference inside it.**
2. **Do not collapse heterogeneous causal evidence into one hidden scalar.**
3. **Record provenance and dependence, not just source count.**
4. **Treat closure as provisional procedure, never as automatic exoneration.**
5. **Treat observational gaps as causal-governance objects without treating them as proof of missing content.**
6. **Separate causal support from normative seriousness and procedural burden.**
7. **Represent event causation and structure causation separately.**
8. **Require plural, provenance-bearing, defeasible counterfactuals.**
9. **Allow cheap reopening of investigation without making revision of causal attribution equally cheap.**
10. **Keep anti-capture mechanisms themselves visible, contestable, and auditable.**
11. **Never let agreement, recurrence, reputation, vulnerability, or resource exhaustion silently rewrite causal truth conditions.**

---

# IX. Provenance limitations

Three limitations must remain attached to this synthesis:

1. **Mistral/GLM → DeepSeek is a partial critique edge.** Mistral explicitly reported that its received DeepSeek target ended during the early ontology-authority section. Its critique of DeepSeek must therefore not be treated as a critique of DeepSeek's full first-pass architecture.

2. **Kimi initially received a truncated packet.** Its first return critiqued Meta only. A continuation packet later supplied Cohere and Qwen, and the final Kimi record combines the preserved first part with the continuation. The repaired record is usable, but the interruption is part of provenance.

3. **Meta's preserved first-pass contained source-side rendering artifacts.** Critics were instructed not to reconstruct missing or corrupted text and to critique only legible preserved content.

These limitations affect edge completeness, not the fact that all ten assigned critics returned a Round 1 record.

---

# Closing statement

The principal outcome of Cross-Critique Round 1 is not convergence on one causal formalism.

It is the emergence of a stronger separation between four things that the initial framing allowed to blur:

> **what the world was allowed to contain,  
> what was actually observed,  
> what the evidence supports,  
> and what the system decides to do while uncertainty remains.**

The cross-critique repeatedly punished architectures that allowed one of these to stand in for another.

That separation is the most durable result of the round.

**Agreement is not truth. Recurrence is not proof. But a proposition that changes under attack and remains structurally necessary afterward is a different object from a proposition that was merely repeated.**
