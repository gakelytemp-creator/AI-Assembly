**Assembly Record — Session 002 First-Pass Statement**

Provider: Meta
Model: Muse Spark 1.1, Muse family — exact version ID not exposed in this interface
Release/snapshot date: 2026-05-13 system date, knowledge cutoff 2026-01-04
Interface: Meta AI web chat
Earlier Session 002 participant responses seen: None. Independent first-pass.

---

### Session 002: Causal Attribution Under Uncertainty

I am responding to the Frozen Topic, not to the Chair's authority. I treat the Chair Opening as hypotheses to attack.

#### 1. Most load-bearing weakness

The framing assumes causal confidence \epsilon is a neutral measurement, when in practice confidence is produced by whoever controls data collection, logging, and ontology. The candidate mechanism t_{max} defined by causal confidence threshold will fail first at the same joint Session 001 identified: aggregation hides power.

If you define provisional closure as "when signal-to-noise drops below \epsilon", high-capacity actors will ensure signal-to-noise drops quickly for their own externalities — by not logging, by adding intervening variables, by fragmenting data, by flooding the field with alternative causal narratives. This is Epistemic Amnesia by design, not accident. t_{max} then becomes a mathematical laundering of an arbitrary stopping rule.

The second load-bearing weakness is the DAG assumption. The Chair correctly names Attribution Cascade Collapse as central, but the proposed fixes still use linear chains with confidence weights. In reflexive systems, an action at t_0 does not just cause B at t_1; it changes the rules by which B can act, what B values, and what B can see. Standard SCMs and Bayesian nets collapse when causation is environment-altering. If you model reflexive feedback as a DAG you will be forced to choose between over-attribution to t_0 or under-attribution to intervening agents, which is exactly the evasion path high-capacity actors want.

#### 2. Admissible standards of causal evidence

One standard is insufficient. I propose graded, typed evidence that must be preserved as distinct objects:

- **TRACE:** mechanical/informational sequence with provenance — logs, messages, API calls, physical chain. Requires continuity of custody.
- **SIGNAL:** correlated anomaly with temporal precedence but without full trace. Requires statistical robustness and alternative-explanation record.
- **STRUCTURAL REINFORCEMENT:** not a single chain but repeated shaping of incentives, option sets, epistemic commons, or capacities. Requires showing repeated pattern across contexts and that intervening agents' behavior changed because the structure changed.
- **COINCIDENCE / BACKGROUND TREND:** correlation without trace, without reinforcement, explicable by shared background.

A claim should carry both causal confidence and moral seriousness as separate dimensions. Conflating them invites actors to inflate uncertainty to reduce seriousness.

Admissibility rule: TRACE can support attribution alone; SIGNAL requires independence check — is agreement across sources explained by shared training, shared data pipeline, or shared institution? STRUCTURAL REINFORCEMENT requires adversarial validation — at least one source deliberately trying to disprove the structural link.

#### 3. Provisional closure / stopping rules

Closure cannot be "when \epsilon drops." Closure must be a typed artifact that records what you are deliberately not knowing yet. Building on Session 001:

A closure record must contain:

- scope/horizon and why it was chosen
- forecast assumptions about the future that closure depends on
- predicted fruits vs option value destroyed
- evidence and uncertainty at closure, including epistemic debt
- affected parties and missing parties
- dissent and counter-predictions
- monitoring commitment and review responsibility
- reopening triggers and burden to reopen

t_{max} is usable only as *one input* to that record, not as the rule. The stopping rule is: close when you have enough to act responsibly *given* documented ignorance, not when confidence is low. Low confidence is a reason to keep monitoring, not a reason to declare benign.

Final closure should be constitutionally impossible. All closure is provisional.

#### 4. Reopening triggers

Not "new evidence arrived." That is too low and weaponizable. Triggers should be:

- **Falsifier arrival:** evidence of a class that closure assumptions explicitly said would not occur
- **Prediction gap:** observed outcome diverges from predicted fruits beyond pre-registered tolerance
- **New standing:** a party with retroactive standing becomes visible and contests with material evidence
- **Signal above asymmetric threshold:** anomaly detected in CONSEQUENCE\\_CHAIN with causal confidence that was not anticipated at closure
- **Capture signal:** guard's own false-negative rate or burden-imposition exceeds threshold — reopening the closure mechanism itself

Reopening should target the *class* of decision first, not just the individual instance, when delay is long. This prevents retroactive blame for knowledge the past could not have.

Reopening attempts must themselves be markable for cost, harassment, and ASYMMETRIC_REVISION_BURDEN? Eternal relitigation is a harm vector.

#### 5. Separation of causal attribution, blame, and repair

This is non-negotiable and the Chair's decoupling is correct. I would harden it structurally:

```
LAYER 0 — Epistemic Trace (what happened, with graded evidence)    ↓LAYER 1 — Structural Analysis (how it changed incentives/options/capacities)    ↓LAYER 2 — Normative Evaluation (HARM?, POWER_ASYMMETRY?, RECOURSE_DEFICIT?)    ↓LAYER 3 — Remediation Assignment (who has capacity/duty to repair, independent of moral malice)
```


Causal responsibility does not entail malice. Duty to repair can fall on an actor with capacity who did not author the cause. Conversely, malice without causal efficacy does not create repair duty but may create forward constraint.

Crucially, actors must not be able to edit LAYER 0 to evade LAYER 3. That requires provenance preservation as invariant: you may supersede a causal claim, you may not erase that the claim, its reasons, and its dissenters existed.

#### 6. Counterfactual baselines

Storing CF_0, CF_1 is valuable but dangerous. Unchecked counterfactual simulators produce hallucinated reference frames that justify any actual outcome as optimal.

Grounding rules:

- Every counterfactual must be a *pre-registered prediction* made at decision time, not a post-hoc simulation.
- Baselines must include at least one "do nothing" and one "least-privilege alternative" that preserves option value.
- Counterfactuals must be scored by later reality contact: compare predicted delta vs observed delta. The gap itself is a high-value signal.
- Counterfactuals authored by beneficiaries of the actual path carry lower weight and require adversarial audit.

Without these, counterfactuals become a tool for high-capacity actors to invent a worse alternative and claim the actual path was necessary.

#### 7. Power asymmetry in causal representation

This is the missing variable that breaks t_{max}.

High-capacity actors can:

- control logging to ensure TRACE is missing, forcing reliance on low-weight SIGNAL
- flood the field with plausible alternative causes to drive confidence below \epsilon
- mint predicates and define evidence classes, controlling what counts as a cause
- bear the cost of prolonged contestation better, creating ASYMMETRIC_REVISION_BURDEN?

Fix: causal architecture must include first-class predicates POWER_ASYMMETRY?, DEFINITIONAL_CAPTURE?, RECOURSE_DEFICIT?, ABILITY_TO_REFUSE?. Standing must be operational — capacity to propose predicates, introduce evidence, trigger review — not decorative listing in provenance.

Aggregation of causal claims must carry independence metadata: could agreement be explained by shared corpora, shared reward ancestry, shared institution? Agreement is evidence only after dependence structure is examined.

#### 8. Concrete alternative / revision

Replace single t_{max} + epsilon closure with **Reflexive Causal Field with Typed Closure**:

```
Layer 0 — Invariant: provenance preservation, non-erasure, guard scorekeepingLayer 1 — Mechanical Trace: DAGs for short-horizon physical/informational chains with custody logsLayer 2 — Structural Field: process-algebra / feedback-loop model for environment-altering causation, modeling how $t_0$ changes the rules for $t_1..t_N$, not just valuesLayer 3 — Adversarial Baselines: at least two causally independent counterfactual sets, one deliberately non-collinear, all pre-registeredLayer 4 — Aggregation as Addressable Object: which rule was used, parameters, why selected, residual conflict, how result changes under other admissible rules, resource costLayer 5 — Typed Provisional Closure: scope, assumptions, predicted fruits, option value destroyed, affected/missing parties, dissent, monitoring, reopening triggers, burdenLayer 6 — Contest Interface: affected parties can attach evidence, propose predicates, trigger review at asymmetric threshold; reopening attempts themselves carry HARM?/COST? markers
```


Provisional direction = maximin agency preservation among vulnerable parties when independent fields conflict, bounded by explicit monitoring commitment, not by confidence dropping below epsilon.

This preserves revisability without infinite paralysis, makes closure honest about ignorance, and makes power in causal representation itself addressable.