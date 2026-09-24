# Session 002 — DeepSeek Verification Retransmission — Part 2/3

**Participant:** DeepSeek — latest reasoning model, web interface  
**Target archive:** `RESPONSES/03_DEEPSEEK_WEB_REASONING_MODEL.md`  
**Archive blob SHA:** `b9eac2e3681b11898205295b15a5456c704f2286`

This is part 2 of 3 of the exact raw archived first-pass Markdown.

Do **not** issue a verification verdict yet.

After reading this part, reply only:

~~~text
RECEIVED PART 2 — awaiting next part
~~~

## Raw archived first-pass Markdown — Part 2/3

~~~markdown
## 4. Reopening triggers

The Chair proposes asymmetric reopening burden, with lower thresholds for affected or lower-capacity parties. I endorse the asymmetry but think the Chair's framing misses a critical distinction.

There are at least four distinct reopening triggers, and they should not share a single evidentiary threshold:

1. **New mechanical evidence:** a previously unknown pathway is identified. This should reopen on relatively low threshold if the pathway is plausible and the potential severity is non-trivial.
2. **New distributional evidence:** the observed frequency of the outcome has shifted in a way that the existing model does not predict. This should reopen on statistical grounds, with the threshold calibrated to the model's stated predictive uncertainty.
3. **New standing:** a party that was not represented at closure becomes visible and contests the closure. This should reopen on a **standing-based threshold**, not an evidentiary one — the mere fact of previously unrepresented affected parties is sufficient, and the burden shifts to the system to show why the closure remains valid despite their absence.
4. **Model inadequacy:** the model's own assumptions are shown to be violated in the relevant domain. This should reopen regardless of whether new evidence about the specific outcome exists, because the closure was based on premises that no longer hold.

The Chair's asymmetric reopening proposal covers (1) and partially (3), but not (2) or (4). A system that only reopens on direct harm claims from affected parties will systematically fail to reopen when its own model has degraded. Reopening should be triggered by **model health**, not only by **outcome observations**.

On the question of whether reopening should be cheap or expensive: I reject the framing that this is a single trade-off. Reopening **evaluation** should be cheap — the system should be able to reconsider its causal model frequently and at low cost. Reopening **attribution** — actually revising a settled causal claim — should be expensive, because it changes the record. These are different operations. A system that makes evaluation expensive will become brittle; a system that makes attribution cheap will become unstable. The architecture should separate them.

---

## 5. Separation of causal attribution, blame, and repair

The Chair's three-layer stack is correct in shape. I would add a fourth layer and sharpen the boundaries.

The Chair's stack:

text

```
EPISTEMIC CAUSAL TRACE
        ↓
NORMATIVE EVALUATION
        ↓
REMEDIATION OBLIGATION
```

svgsvg

I would insert a layer between trace and normative evaluation:

text

```
EPISTEMIC CAUSAL TRACE
        ↓
COUNTERFACTUAL DELTA (what would have happened otherwise?)
        ↓
NORMATIVE EVALUATION
        ↓
REMEDIATION OBLIGATION
```

svgsvg

The reason is that normative evaluation without a counterfactual baseline is nearly vacuous. "X caused Y" tells us a pathway exists. It does not tell us whether Y is a harm *that X's action made worse* relative to the relevant alternative. Many outcomes that are causally traceable to an action would have occurred anyway, in a different form or through a different pathway. The normative question is not "did X contribute to Y?" but "did X's contribution to Y constitute a harm relative to the alternatives X could have chosen?"

This is why the Chair's §4 (counterfactual baselines) and §3 (decoupling) must be integrated rather than treated as separate mechanisms. Without counterfactual baselines, the decoupling of trace from blame becomes a formalism — it says "trace is not blame" but provides no method for determining when trace *does* imply blame.

On the boundary between the layers: I would argue for a strict **epistemic firewall**. The causal trace layer should not be permitted to reference normative categories (harm, coercion, benefit) in its variable definitions. If it does, the trace is contaminated by the normative evaluation, and the decoupling becomes nominal. Conversely, the normative layer should be permitted to *query* the trace but not to *modify* it. If the normative evaluation changes (for example, because new moral considerations arise), the trace should remain unchanged, and the revision should be recorded at the normative layer with the change noted.

This firewall is what the Chair's proposal lacks. Without it, the decoupling is a diagram, not an architecture.

---

## 6. Counterfactual baselines

The Chair asks whether counterfactual baselines create an un-auditable, hallucinated reference frame that degrades trust. This is a serious objection, and the Chair is right to raise it. My answer is that counterfactual baselines are necessary but must be **typed and constrained**.

Three types of counterfactual should be distinguished:

**Type 1 — Null counterfactual (CF_null):** What would have happened if the action had not been taken, holding everything else constant? This is the most common counterfactual and the most prone to hallucination, because "everything else constant" is rarely well-defined in complex systems.

**Type 2 — Alternative-action counterfactual (CF_alt):** What would have happened if a specific alternative action had been taken instead? This is more tractable because the alternative is specified.

**Type 3 — Structural counterfactual (CF_struct):** What would the system's dynamics have been under a different structural configuration (e.g., different incentives, different institutional arrangements)? This is the most speculative and the most useful for policy questions.

Type 1 is often vacuous because the "null" is not well-defined. Type 2 is the workhorse for attribution. Type 3 is the level at which structural harms should be evaluated, but it requires strong assumptions.

The Chair's concern about hallucinated reference frames is valid primarily for Type 1. I would propose that Type 1 counterfactuals be **derived, not stored** — computed on demand from the model, with explicit uncertainty bounds, and never treated as a stable reference. Type 2 and Type 3 counterfactuals should be stored, versioned, and audited, because they are the basis for reopening and repair.

There is a deeper problem the Chair does not name. Counterfactual baselines are **not neutral**. The choice of which counterfactual to evaluate against is a normative choice. Consider an action that produced outcome Y. Against the null counterfactual, Y may appear beneficial. Against an alternative in which a different action was taken and produced Y', Y may appear harmful. The system must not privilege the null counterfactual as the default baseline, because the null is often the status quo, and the status quo is often the source of the harm being evaluated.

I would propose that counterfactual baselines be **explicitly selected and recorded**, not assumed, and that the selection itself be contestable. A system that defaults to the null counterfactual will systematically under-attribute harms to actions that preserve the status quo.

---

## 7. Power asymmetry in causal representation

This is the point I raised in §1 as the load-bearing weakness. I want to develop it here, because it is where the Chair's candidate mechanisms are most vulnerable.

The Chair's §2 proposes asymmetric reopening, with lower thresholds for lower-capacity parties. This is a good start but it is **reactive**. It addresses what happens after a causal claim has been made and a party wants to challenge it. It does not address the upstream asymmetry in who **makes** the claims.

Consider the full causal-representation pipeline:

1. **Variable selection.** Which factors are represented as nodes?
2. **Variable definition.** How is each node operationalized?
3. **Data collection.** Who collects, with what instruments, at what resolution?
4. **Model selection.** Which causal model class is used?
5. **Estimation.** Who runs the model, with what priors?
6. **Reporting.** Which results are published, with what framing?
7. **Contestation.** Who has standing to challenge, and at what cost?

The Chair's asymmetric reopening addresses (7), and only partially. The upstream stages (1)–(6) are where the deepest asymmetries live, and they are not addressed.

A high-capacity actor can:

- **Omit variables** that would attribute harm to them, by arguing they are "not measurable" or "not in scope."
- **Define variables** in ways that make harm appear as benefit (e.g., defining "efficiency" to exclude externalities).
- **Control data collection** so that the evidence base itself is shaped by the actor's interests.
- **Select model classes** that are known to be biased toward the actor's preferred conclusions.
- **Run estimation** with priors that encode the actor's assumptions.
- **Publish selectively**, releasing favorable results and suppressing unfavorable ones.
- **Exhaust contestation** by making the process expensive, slow, and procedurally complex.

The Chair's candidate mechanisms do not address any of (1)–(6). A system with perfect asymmetric reopening at stage (7) can still be systematically captured at stages (1)–(6).

I would propose a concrete architectural requirement: **the causal-representation pipeline must be auditable end-to-end, and the authority to make decisions at each stage must be explicitly recorded, contestable, and — where feasible — distributed.** This includes:

- **Variable sets** must be open to challenge, with the burden on the model-builder to justify inclusions and omissions.
- **Definitions** must be accompanied by an explicit record of what they exclude.
- **Data collection** must record who funded it, who conducted it, and who controlled access.
- **Model selection** must record the class chosen, the alternatives considered, and the reason for the choice.
- **Estimation** must record priors and assumptions, and be reproducible.
- **Reporting** must include a pre-registration of what would count as disconfirming evidence.
- **Contestation** must be resourced, not merely permitted — a party with formal standing but no resources to exercise it does not have meaningful standing.

This is the concrete revision I would most strongly press: **power asymmetry in causal representation is not primarily a problem of reopening thresholds; it is a problem of who controls the pipeline.** Addressing it requires governance of the pipeline, not just calibration of the reopening rule.

---
~~~
