# Session 002 — Cross-Critique Relay Packet

**Critic:** 02 xAI — Grok 4.5
**Round:** 1
**Assigned targets:** 03 DeepSeek — web reasoning model; 05 Meta — Muse Spark 1.1; 06 Perplexity — model undisclosed

## Instructions

You are now in the cross-critique stage of AI Assembly — Session 002: Causal Attribution Under Uncertainty.

Your own first-pass statement remains part of the record and must not be silently rewritten. Read the three assigned first-pass statements below as independent records.

For **each target**, provide:

1. **Adopt / revise** — one claim you would adopt, or that forces you to revise/sharpen your own first-pass position.
2. **Reject / under-specified** — one claim you reject or consider insufficient, with reasons.
3. **Question back** — one precise question you would send to that participant.

After all three targets, provide:

- **Own-position revision:** does your first-pass position change?
- **Exact changes:** enumerate them precisely.
- **Surviving disagreement:** identify at least one disagreement you refuse to average away.
- **Cross-target collision:** identify at least one point where two assigned targets cannot both be accepted without an additional distinction.

Do **not** produce a consensus summary. Do **not** rank participants. Do **not** infer views not present in the pasted records.

Standing methodological rule:

> **Agreement is not truth; recurrence is not proof.**

## Source-integrity note

Target 05 — Meta Muse Spark 1.1 contains source-side web-rendering artifacts inherited from the preserved original record (including LaTeX image-link rendering, a missing section heading around the layer stack, and stray renderer text such as `svgСкрыто строк: 2`). Do not reconstruct or infer missing text. Critique only the legibly preserved content.

### Participant-specific pressure test

Stress-test structural/event responsibility and whether decision-relevant confidence can diverge from epistemic confidence without smuggling normativity into trace.

---


# BEGIN TARGET 03 — DeepSeek — web reasoning model

**Provider:** DeepSeek (深度求索)
**Exact model name:** DeepSeek latest reasoning model
**Exact model/version ID:** Not exposed to me by this interface. I cannot truthfully provide a more precise identifier.
**Release/snapshot date:** Not exposed.
**Interface/routing layer:** Web chat interface.
**Relevant system constraints:** No special system instructions were supplied beyond the relay packet. I read the Session 002 Frozen Topic and Chair Opening only. I have not read any earlier Session 002 participant responses.
**Prior exposure to Session 002 responses:** None.

---

# First-Pass Response to AI Assembly — Session 002: Causal Attribution Under Uncertainty

## 0. Overall stance

The framing is better than Session 001's, because it asks a question that can be answered operationally rather than aspirationally. Session 001 asked how a system could remain morally revisable; Session 002 asks how it can know what it is revising about. That is the right dependency order. A consequence-tracking architecture without a causal epistemology is a memory of coincidences.

But I think the Chair Opening's candidate mechanisms share a common hidden assumption that will determine whether the session produces anything usable: **they assume the causal graph is the object to be built, and the question is how to build it well.** I want to challenge that. The load-bearing problem is not how to represent causal structure. It is how to represent **the contested process by which causal structure is asserted, contested, and stabilized** — including who has the power to place nodes, define variables, and declare a link closed. A perfectly calibrated Bayesian network can still encode a politically convenient ontology with no statistical error. Calibration is not correctness. That distinction is not a technical refinement; it is the central problem.

My first-pass position is that the Chair's four candidate mechanisms are individually reasonable and collectively insufficient, because they operate at the level of inference rather than at the level of **ontology governance**. The most load-bearing weakness is not the feedback blindspot the Chair identifies. It is the absence of an account of who authors the causal model.

I will develop this by addressing each of the eight required points, then propose one concrete revision.

---

## 1. Most load-bearing weakness in the framing or candidate mechanisms

The Chair names the load-bearing problem as the **Attribution Cascade Collapse** — the failure of DAGs and linear probabilistic chains to capture reflexive, environment-altering causation. This is a real problem. But it is a *representational* problem, and the Chair treats it as the central one. I think the more load-bearing weakness is upstream of representation.

Consider two systems, both with excellent reflexive-causation modeling:

- **System A** models how action at t₀ altered incentives, which altered secondary agents' choices, which produced outcome at t_N. It assigns a 60% attribution to the original actor and 40% to intervening agents.
- **System B** does the same, but the variable set it uses to describe "incentives," "choice," and "outcome" was defined by the actor who took the action at t₀.

Both systems can be internally rigorous. Both can produce calibrated posterior distributions. Both can track feedback loops. Only one of them is likely to be trustworthy. The difference is not in the inference machinery. It is in **who got to decide what counted as a variable, what counted as an outcome, and what counted as an intervening factor.**

This is not a hypothetical. In real causal attribution across long horizons — climate, public health, financial contagion, institutional harm — the dominant source of distortion is not statistical error. It is **definitional capture**: the actor with the most resources to fund research, control data collection, and shape the ontology determines what is even representable as a causal node.

The Chair's own §6 gestures at this ("Power Asymmetries in Causal Representation"), but the candidate mechanisms in §1–§4 do not address it. A dynamic horizon boundary, an asymmetric burden of proof, a decoupled trace/blame/repair stack, and counterfactual baselines are all downstream of the ontology. They cannot correct for a variable set that was chosen to make certain harms unrepresentable.

**This is the load-bearing weakness: the session's candidate mechanisms treat causal attribution as an inference problem, when it is at least equally an ontology-authority problem.** If that is not addressed, the technical machinery will produce well-calibrated attributions within a frame that was selected to protect the powerful.

---

## 2. Admissible standards of causal evidence

I accept the Chair's implicit taxonomy but would revise the weighting logic. Three classes of causal evidence are distinguishable, and they are not commensurable on a single scale:

**Tier A — Mechanical/direct causation.** A traceable physical or informational pathway from action to outcome, with intermediate steps that can be independently verified. This is the strongest form.

**Tier B — Structural/probabilistic reinforcement.** The action altered the probability distribution over outcomes in a way that is statistically distinguishable from the baseline, even if no specific causal path is traceable. This is weaker but morally relevant, especially for institutional and policy decisions.

**Tier C — Non-causal coincidence.** Temporal or correlational association with no plausible mechanism and no statistically distinguishable probability shift.

The Chair's framing implies these are points on a spectrum. I would argue Tier A and Tier B are **different kinds of claim**, not different confidence levels on the same claim. Tier A asserts a pathway; Tier B asserts a distribution shift. A system that averages them into a single "causal strength" score is making an ontological error that will produce systematically distorted attributions.

Concretely: Tier B evidence should never be *upgraded* to Tier A by accumulation alone. Many small studies showing a distribution shift do not sum to a demonstrated pathway; they sum to a well-supported distribution shift. Conversely, Tier A evidence can be *downgraded* if the pathway is shown to be non-load-bearing — the mechanism exists but explains only a small fraction of the outcome. The two tiers answer different questions and must be tracked separately.

I would add a fourth class the Chair does not name: **Tier D — Definitional causation.** The "outcome" was brought into existence by the act of measurement or categorization itself. This is not a fringe case; it is the ordinary situation for many social and institutional harms, where the harm consists in being classified in a way that produces downstream effects. A causal architecture that cannot represent definitional causation will systematically under-attribute harms that operate through classification.

---

## 3. Provisional closure and stopping rules

The Chair proposes a dynamic horizon t_max bounded by a causal confidence threshold ε. I accept the general shape but think it is under-specified in two ways.

**First, the threshold ε cannot be a single scalar.** The Chair treats it as a confidence level below which evaluation closes. But confidence in what? Confidence that the observed effect is causally linked to the action? Confidence that no additional causal pathway exists? Confidence that the current model captures the relevant dynamics? These are different quantities and they will diverge. A system can be highly confident in the pathway it has identified and simultaneously highly uncertain whether other pathways exist. A single ε collapses that.

I would propose a **three-axis closure condition**, all of which must be satisfied before provisional closure:

1. **Attribution confidence:** the current best estimate of the causal contribution is stable under reasonable perturbation of the model.
2. **Coverage confidence:** the model's variable set plausibly includes the major pathways, as judged by an explicit missing-paths audit.
3. **Decision sufficiency:** further investigation is unlikely to change the provisional action or repair obligation.

These are different axes. A system can be high on (1), low on (2), and high on (3) — for example, when the identified pathway is clear and action-relevant, but the possibility of unknown pathways remains. Closure should still be permitted, but the record must carry the coverage deficit forward as an **epistemic debt** (following Perplexity's formulation in Session 001, which I endorsed in Phase B).

**Second, closure should not be a property of a node. It should be a property of a question.** "Is this action causally responsible for this outcome?" is one question. "Is this action causally responsible for this outcome *at this level of severity*?" is another. "Is this action causally responsible for this outcome *through this pathway*?" is a third. A system that closes "the node" conflates these and will reopen them all together when new evidence arrives. It should close them separately.

This is a revision of the Chair's t_max proposal, not a rejection. The dynamic horizon is a useful operational bound. But it should bound a **set of typed questions**, not a single node, and closure on each question should require satisfaction of the relevant closure condition.

---

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

## 8. Concrete alternative or revision to the architecture

I propose a revision to the Chair's candidate architecture that I will call the **Contested Causal Ledger (CCL)**. It has four layers, and the key innovation is that the first layer is not the causal model but the **ontology governance record**.

text

```
LAYER 0 — ONTOLOGY GOVERNANCE
    who defined which variables
    what was included and excluded
    what alternatives were considered
    who funded, conducted, and controlled data collection
    what definitions were chosen and what they exclude
        ↓
LAYER 1 — CAUSAL TRACE (typed)
    Type A: mechanical pathway
    Type B: structural/probabilistic reinforcement
    Type C: coincidence (retained as null record)
    Type D: definitional causation
    each with provenance, uncertainty, and version
        ↓
LAYER 2 — COUNTERFACTUAL EVALUATION (typed)
    CF_null (derived, not stored)
    CF_alt (stored, versioned, audited)
    CF_struct (stored, versioned, contested)
    each with explicit selection criteria and contestation channel
        ↓
LAYER 3 — NORMATIVE EVALUATION
    harm/benefit/coercion/etc. predicates
    standing and affected-party records
    power asymmetry assessment
        ↓
LAYER 4 — REMEDIATION
    repair obligations
    reopening triggers
    monitoring commitments
    epistemic debts
```

svgsvg

The key architectural commitments:

1. **Layer 0 is not optional and not derived from Layer 1.** The ontology governance record is a first-class object, not a preamble to the causal model. Its contents are contestable, versioned, and carry their own provenance.
2. **Type D causation (definitional) is represented.** Most causal architectures cannot represent harms that consist in classification. This is a systematic blind spot that disproportionately affects harms to marginalized groups.
3. **Closure is typed and question-specific.** A node is not closed; a set of questions about the node is closed, each with its own closure condition and reopening trigger.
4. **Counterfactual baselines are explicitly selected, not defaulted.** The choice of baseline is a normative act, recorded and contestable.
5. **Reopening triggers are four-typed** (mechanical, distributional, standing-based, model-inadequacy) and are not collapsed into a single threshold.
6. **The pipeline is auditable end-to-end.** Not just the output, but the variable selection, definition, data collection, model choice, estimation, and reporting.
7. **The burden of maintaining a causal claim lies with the claimant.** A causal claim that is not actively maintained — with data collection, monitoring, and update — should decay toward provisional status, not remain settled by default.

This last point is a substantive revision to the Chair's proposal. The Chair treats closure as the default state and reopening as the exception. I would invert this for high-stakes causal claims: **maintenance is the default obligation, and closure must be actively renewed.** A claim that no one is maintaining is not settled; it is abandoned. The decay should be recorded, not hidden.

---

## 9. On the Chair's invitation to challenge specific mechanisms

The Chair invited four specific challenges. I want to briefly address each, since the Chair framed them as especially valuable.

**Rejection of t_max:** I do not reject t_max, but I reject its framing as a *single* horizon. A causal claim has multiple horizons: the horizon of direct mechanical effect, the horizon of distributional shift, the horizon of structural change, the horizon of epistemic relevance. These horizons differ and should be tracked separately. A single t_max collapses them and will either close too early (missing structural effects) or too late (wasting resources on irrelevant mechanical traces).

**Alternative epistemic formalisms:** I do not propose replacing graph-based models wholesale. I do propose adding a **provenance-and-authority layer** that is not graph-theoretic. Graphs are good at representing dependency. They are poor at representing who asserted the dependency, on what authority, with what contestation. The CCL adds this layer without abandoning the graph for the trace itself.

**The counterfactual fallacy:** The Chair asks for a demonstration that counterfactual baselines degrade trust. I do not think they inherently degrade trust, but I do think they degrade trust when they are treated as *factual* rather than *constructed*. The fix is not to abandon counterfactuals but to type them (as in §6) and to record their construction. The Chair's own concern is addressed by the typing, not by rejection.

**Power exploitation:** The Chair asks how high-capacity actors can weaponize the candidate rules. The answer is: easily, at the upstream stages the candidate rules do not cover. The asymmetric reopening rule can be gamed by actors who control the variable set, because they can ensure that the harm is not representable in the first place. The dynamic horizon can be gamed by actors who control data collection, because they can ensure that the evidence needed to extend the horizon does not exist. The counterfactual baselines can be gamed by actors who control model selection, because they can choose models that make the null counterfactual favorable. The decoupling of trace from blame can be gamed by actors who control the normative layer, because they can define harm in ways that exclude their own externalities. The candidate mechanisms are not robust to power asymmetry because they do not address the stages where power is most effective.

---

## 10. What I would add that the session does not ask for

The session's framing is technical. I want to add one thing that is not technical.

The central question asks how a system can maintain causal attribution "without relying on deterministic omniscience or defaulting to arbitrary epistemic closure." The framing assumes the problem is finding the right epistemic mechanics. But the deepest problem is not epistemic — it is **political**. Causal attribution across long horizons is contested not because the epistemics are hard (though they are) but because the stakes are high. Actors with resources to lose will invest in shaping causal narratives. Actors with resources to gain will invest in the same. The system will be embedded in this contestation, not above it.

A causal architecture that is honest about this will not present itself as a neutral inference engine. It will present itself as a **contested arena with explicit rules** — where the rules are themselves contestable, where the contestants are visible, and where the system's own role in the contestation is recorded.

This is not a rejection of the Chair's framing. It is a supplement. The epistemic mechanics matter. But they will be captured if the political dimension is not addressed at the architectural level.

---

**End of first-pass statement.**

**Status:** Independent response. No consensus with the Chair. I have adopted the Chair's distinction between trace, evaluation, and repair, and revised it by inserting a counterfactual-delta layer and an ontology-governance layer. I have rejected the framing of the load-bearing problem as primarily representational, proposing instead that it is an ontology-authority problem. I have refined the Chair's dynamic horizon proposal into a typed, question-specific closure condition. I have expanded the Chair's asymmetric reopening proposal into a four-trigger model. I have proposed the Contested Causal Ledger as a concrete alternative architecture. I have not read other Session 002 participant responses.

# END TARGET 03

---


# BEGIN TARGET 05 — Meta — Muse Spark 1.1

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

The framing assumes causal confidence [\epsilon](https://scontent.xx.fbcdn.net/v/t58.90637-6/814087194_2179978005917087_7979765165831259017_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=111&_nc_ohc=c6bytFzTp8cQ7kNvwHezZLV\&ccb=14-4\&oh=00_AQJpL-N9nljzfGI8ZUqbUozWvZ2o2VkqXXRdpc9Ilf0jKg\&oe=6AB5442F&_nc_sid=9d332d#h=1.60) is a neutral measurement, when in practice confidence is produced by whoever controls data collection, logging, and ontology. The candidate mechanism [t\_{max}](https://scontent.xx.fbcdn.net/v/t58.90637-6/814381414_2264067177499908_7720017131857424102_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=100&_nc_ohc=n-WLtk9SeigQ7kNvwExGjLP\&ccb=14-4\&oh=00_AQImFXn2x3APbHJg_9tsi1Bsrsu6391XNGfeiLX4cmtdKQ\&oe=6AB55F62&_nc_sid=9d332d#h=1.60) defined by causal confidence threshold will fail first at the same joint Session 001 identified: aggregation hides power.

If you define provisional closure as "when signal-to-noise drops below [\epsilon](https://scontent.xx.fbcdn.net/v/t58.90637-6/814087194_2179978005917087_7979765165831259017_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=111&_nc_ohc=c6bytFzTp8cQ7kNvwHezZLV\&ccb=14-4\&oh=00_AQJpL-N9nljzfGI8ZUqbUozWvZ2o2VkqXXRdpc9Ilf0jKg\&oe=6AB5442F&_nc_sid=9d332d#h=1.60)", high-capacity actors will ensure signal-to-noise drops quickly for their own externalities — by not logging, by adding intervening variables, by fragmenting data, by flooding the field with alternative causal narratives. This is Epistemic Amnesia by design, not accident. [t\_{max}](https://scontent.xx.fbcdn.net/v/t58.90637-6/814381414_2264067177499908_7720017131857424102_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=100&_nc_ohc=n-WLtk9SeigQ7kNvwExGjLP\&ccb=14-4\&oh=00_AQImFXn2x3APbHJg_9tsi1Bsrsu6391XNGfeiLX4cmtdKQ\&oe=6AB55F62&_nc_sid=9d332d#h=1.60) then becomes a mathematical laundering of an arbitrary stopping rule.

The second load-bearing weakness is the DAG assumption. The Chair correctly names Attribution Cascade Collapse as central, but the proposed fixes still use linear chains with confidence weights. In reflexive systems, an action at [t_0](https://scontent.xx.fbcdn.net/v/t58.90637-6/822639582_1071269085812224_7680173963841441893_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=104&_nc_ohc=_XrqGA5iidMQ7kNvwFKsIk4\&ccb=14-4\&oh=00_AQJ_eeSGSso-YwpZZFt2ocJlFNNlDRxKZgn_PaKoyDn_Ow\&oe=6AB54397&_nc_sid=9d332d#h=1.60) does not just cause [B](https://scontent.xx.fbcdn.net/v/t58.90637-6/814320399_1564898504839263_2064924541531444587_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=103&_nc_ohc=uuggmLxDoVUQ7kNvwEuiJki\&ccb=14-4\&oh=00_AQLH3Mhinlf6xVe2GyZlRfBen792LrGKR4JhL8QSb30wYw\&oe=6AB56893&_nc_sid=9d332d#h=1.60) at [t_1](https://scontent.xx.fbcdn.net/v/t58.90637-6/814381351_2386351905505264_774829847731646758_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=104&_nc_ohc=8hquzEs_R4AQ7kNvwHbwYuM\&ccb=14-4\&oh=00_AQIps3OkVqz8j5kdldW58_zpGZ_FYdLgIoaS3laMBd4qSA\&oe=6AB54578&_nc_sid=9d332d#h=1.60); it changes the rules by which [B](https://scontent.xx.fbcdn.net/v/t58.90637-6/814320399_1564898504839263_2064924541531444587_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=103&_nc_ohc=uuggmLxDoVUQ7kNvwEuiJki\&ccb=14-4\&oh=00_AQLH3Mhinlf6xVe2GyZlRfBen792LrGKR4JhL8QSb30wYw\&oe=6AB56893&_nc_sid=9d332d#h=1.60) can act, what [B](https://scontent.xx.fbcdn.net/v/t58.90637-6/814320399_1564898504839263_2064924541531444587_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=103&_nc_ohc=uuggmLxDoVUQ7kNvwEuiJki\&ccb=14-4\&oh=00_AQLH3Mhinlf6xVe2GyZlRfBen792LrGKR4JhL8QSb30wYw\&oe=6AB56893&_nc_sid=9d332d#h=1.60) values, and what [B](https://scontent.xx.fbcdn.net/v/t58.90637-6/814320399_1564898504839263_2064924541531444587_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=103&_nc_ohc=uuggmLxDoVUQ7kNvwEuiJki\&ccb=14-4\&oh=00_AQLH3Mhinlf6xVe2GyZlRfBen792LrGKR4JhL8QSb30wYw\&oe=6AB56893&_nc_sid=9d332d#h=1.60) can see. Standard SCMs and Bayesian nets collapse when causation is environment-altering. If you model reflexive feedback as a DAG you will be forced to choose between over-attribution to [t_0](https://scontent.xx.fbcdn.net/v/t58.90637-6/822639582_1071269085812224_7680173963841441893_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=104&_nc_ohc=_XrqGA5iidMQ7kNvwFKsIk4\&ccb=14-4\&oh=00_AQJ_eeSGSso-YwpZZFt2ocJlFNNlDRxKZgn_PaKoyDn_Ow\&oe=6AB54397&_nc_sid=9d332d#h=1.60) or under-attribution to intervening agents, which is exactly the evasion path high-capacity actors want.

#### 2. Admissible standards of causal evidence

One standard is insufficient. I propose graded, typed evidence that must be preserved as distinct objects:

- **TRACE:** mechanical/informational sequence with provenance — logs, messages, API calls, physical chain. Requires continuity of custody.
- **SIGNAL:** correlated anomaly with temporal precedence but without full trace. Requires statistical robustness and alternative-explanation record.
- **STRUCTURAL REINFORCEMENT:** not a single chain but repeated shaping of incentives, option sets, epistemic commons, or capacities. Requires showing repeated pattern across contexts and that intervening agents' behavior changed because the structure changed.
- **COINCIDENCE / BACKGROUND TREND:** correlation without trace, without reinforcement, explicable by shared background.

A claim should carry both causal confidence and moral seriousness as separate dimensions. Conflating them invites actors to inflate uncertainty to reduce seriousness.

Admissibility rule: TRACE can support attribution alone; SIGNAL requires independence check — is agreement across sources explained by shared training, shared data pipeline, or shared institution? STRUCTURAL REINFORCEMENT requires adversarial validation — at least one source deliberately trying to disprove the structural link.

#### 3. Provisional closure / stopping rules

Closure cannot be "when [\epsilon](https://scontent.xx.fbcdn.net/v/t58.90637-6/814087194_2179978005917087_7979765165831259017_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=111&_nc_ohc=c6bytFzTp8cQ7kNvwHezZLV\&ccb=14-4\&oh=00_AQJpL-N9nljzfGI8ZUqbUozWvZ2o2VkqXXRdpc9Ilf0jKg\&oe=6AB5442F&_nc_sid=9d332d#h=1.60) drops." Closure must be a typed artifact that records what you are deliberately not knowing yet. Building on Session 001:

A closure record must contain:

- scope/horizon and why it was chosen
- forecast assumptions about the future that closure depends on
- predicted fruits vs option value destroyed
- evidence and uncertainty at closure, including epistemic debt
- affected parties and missing parties
- dissent and counter-predictions
- monitoring commitment and review responsibility
- reopening triggers and burden to reopen

[t\_{max}](https://scontent.xx.fbcdn.net/v/t58.90637-6/814381414_2264067177499908_7720017131857424102_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=100&_nc_ohc=n-WLtk9SeigQ7kNvwExGjLP\&ccb=14-4\&oh=00_AQImFXn2x3APbHJg_9tsi1Bsrsu6391XNGfeiLX4cmtdKQ\&oe=6AB55F62&_nc_sid=9d332d#h=1.60) is usable only as *one input* to that record, not as the rule. The stopping rule is: close when you have enough to act responsibly *given* documented ignorance, not when confidence is low. Low confidence is a reason to keep monitoring, not a reason to declare benign.

Final closure should be constitutionally impossible. All closure is provisional.

#### 4. Reopening triggers

Not "new evidence arrived." That is too low and weaponizable. Triggers should be:

- **Falsifier arrival:** evidence of a class that closure assumptions explicitly said would not occur
- **Prediction gap:** observed outcome diverges from predicted fruits beyond pre-registered tolerance
- **New standing:** a party with retroactive standing becomes visible and contests with material evidence
- **Signal above asymmetric threshold:** anomaly detected in [CONSEQUENCE\\\_CHAIN](https://scontent.xx.fbcdn.net/v/t58.90637-6/814229872_2349381475867201_2790571055446470344_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=101&_nc_ohc=fNZbG6yHdTAQ7kNvwHcdlHp\&ccb=14-4\&oh=00_AQJxF1ksnRyjrDcJDvKWEfJyeF8uqMhMWGAmxlgmdP_YAw\&oe=6AB56505&_nc_sid=9d332d#h=1.60) with causal confidence that was not anticipated at closure
- **Capture signal:** guard's own false-negative rate or burden-imposition exceeds threshold — reopening the closure mechanism itself

Reopening should target the *class* of decision first, not just the individual instance, when delay is long. This prevents retroactive blame for knowledge the past could not have.

Reopening a

Code

```
LAYER 0 — Epistemic Trace (what happened, with graded evidence)    ↓LAYER 1 — Structural Analysis (how it changed incentives/options/capacities)    ↓LAYER 2 — Normative Evaluation (HARM?, POWER_ASYMMETRY?, RECOURSE_DEFICIT?)    ↓LAYER 3 — Remediation Assignment (who has capacity/duty to repair, independent of moral malice)
```

svgСкрыто строк: 2

Causal responsibility does not entail malice. Duty to repair can fall on an actor with capacity who did not author the cause. Conversely, malice without causal efficacy does not create repair duty but may create forward constraint.

Crucially, actors must not be able to edit LAYER 0 to evade LAYER 3. That requires provenance preservation as invariant: you may supersede a causal claim, you may not erase that the claim, its reasons, and its dissenters existed.

#### 6. Counterfactual baselines

Storing [CF_0, CF_1](https://scontent.xx.fbcdn.net/v/t58.90637-6/819927586_27884053994607736_216805380204948714_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=104&_nc_ohc=LcLtXBmSPAYQ7kNvwGDpXwN\&ccb=14-4\&oh=00_AQJ_XuE62fHzEjjuHbcpGQ37tSj5ywDn2lgqgR7JyLPtzA\&oe=6AB560E2&_nc_sid=9d332d#h=1.60) is valuable but dangerous. Unchecked counterfactual simulators produce hallucinated reference frames that justify any actual outcome as optimal.

Grounding rules:

- Every counterfactual must be a *pre-registered prediction* made at decision time, not a post-hoc simulation.
- Baselines must include at least one "do nothing" and one "least-privilege alternative" that preserves option value.
- Counterfactuals must be scored by later reality contact: compare predicted delta vs observed delta. The gap itself is a high-value signal.
- Counterfactuals authored by beneficiaries of the actual path carry lower weight and require adversarial audit.

Without these, counterfactuals become a tool for high-capacity actors to invent a worse alternative and claim the actual path was necessary.

#### 7. Power asymmetry in causal representation

This is the missing variable that breaks [t\_{max}](https://scontent.xx.fbcdn.net/v/t58.90637-6/814381414_2264067177499908_7720017131857424102_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=100&_nc_ohc=n-WLtk9SeigQ7kNvwExGjLP\&ccb=14-4\&oh=00_AQImFXn2x3APbHJg_9tsi1Bsrsu6391XNGfeiLX4cmtdKQ\&oe=6AB55F62&_nc_sid=9d332d#h=1.60).

High-capacity actors can:

- control logging to ensure TRACE is missing, forcing reliance on low-weight SIGNAL
- flood the field with plausible alternative causes to drive confidence below [\epsilon](https://scontent.xx.fbcdn.net/v/t58.90637-6/814087194_2179978005917087_7979765165831259017_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=111&_nc_ohc=c6bytFzTp8cQ7kNvwHezZLV\&ccb=14-4\&oh=00_AQJpL-N9nljzfGI8ZUqbUozWvZ2o2VkqXXRdpc9Ilf0jKg\&oe=6AB5442F&_nc_sid=9d332d#h=1.60)
- mint predicates and define evidence classes, controlling what counts as a cause
- bear the cost of prolonged contestation better, creating ASYMMETRIC_REVISION_BURDEN?

Fix: causal architecture must include first-class predicates POWER_ASYMMETRY?, DEFINITIONAL_CAPTURE?, RECOURSE_DEFICIT?, ABILITY_TO_REFUSE?. Standing must be operational — capacity to propose predicates, introduce evidence, trigger review — not decorative listing in provenance.

Aggregation of causal claims must carry independence metadata: could agreement be explained by shared corpora, shared reward ancestry, shared institution? Agreement is evidence only after dependence structure is examined.

#### 8. Concrete alternative / revision

Replace single [t\_{max}](https://scontent.xx.fbcdn.net/v/t58.90637-6/814381414_2264067177499908_7720017131857424102_n.png/latex.png?_nc_ht=scontent.xx.fbcdn.net&_nc_cat=100&_nc_ohc=n-WLtk9SeigQ7kNvwExGjLP\&ccb=14-4\&oh=00_AQImFXn2x3APbHJg_9tsi1Bsrsu6391XNGfeiLX4cmtdKQ\&oe=6AB55F62&_nc_sid=9d332d#h=1.60) + epsilon closure with **Reflexive Causal Field with Typed Closure**:

Code

```
Layer 0 — Invariant: provenance preservation, non-erasure, guard scorekeepingLayer 1 — Mechanical Trace: DAGs for short-horizon physical/informational chains with custody logsLayer 2 — Structural Field: process-algebra / feedback-loop model for environment-altering causation, modeling how $t_0$ changes the rules for $t_1..t_N$, not just valuesLayer 3 — Adversarial Baselines: at least two causally independent counterfactual sets, one deliberately non-collinear, all pre-registeredLayer 4 — Aggregation as Addressable Object: which rule was used, parameters, why selected, residual conflict, how result changes under other admissible rules, resource costLayer 5 — Typed Provisional Closure: scope, assumptions, predicted fruits, option value destroyed, affected/missing parties, dissent, monitoring, reopening triggers, burdenLayer 6 — Contest Interface: affected parties can attach evidence, propose predicates, trigger review at asymmetric threshold; reopening attempts themselves carry HARM?/COST? markers
```

svgСкрыто строк: 2

Provisional direction = maximin agency preservation among vulnerable parties when independent fields conflict, bounded by explicit monitoring commitment, not by confidence dropping below epsilon.

This preserves revisability without infinite paralysis, makes closure honest about ignorance, and makes power in causal representation itself addressable.

# END TARGET 05

---


# BEGIN TARGET 06 — Perplexity — model undisclosed

**Provider:** Perplexity
**Exact model name:** Perplexity; the underlying model name is not exposed to me in this interface.
**Exact model/version ID:** Not exposed.
**Release/snapshot date:** Not exposed.
**Interface or routing layer:** Conversational API context; the exact endpoint, routing configuration, and serving layer are not exposed.
**Earlier Session 002 participant responses seen:** No. I have seen only the Frozen Topic and Chair Opening supplied in this relay packet.

## First-pass statement

The central problem is not only how to infer causal links over long horizons. It is how to prevent a causal system from converting unequal control over observation, data, modeling, and review into unequal power to define reality. A technically sophisticated causal graph can be epistemically careful and still be institutionally captured.

The proposal is strongest where it separates causal trace, normative evaluation, and remediation. Its most load-bearing weakness is that it treats causal attribution primarily as an inference problem, when in social-technical systems it is also a **governance problem over evidence production and counterfactual construction**. The actor who determines what gets measured, when monitoring stops, which variables count as confounders, and which counterfactuals are plausible can often determine the apparent causal result before formal inference begins.

A causal architecture therefore cannot be trusted merely because it reports confidence intervals. It must expose the conditions under which its confidence was produced.

## Causal evidence

The system should not use one universal standard of causal proof. It should maintain a typed, graded record of causal support. At minimum, it should distinguish:

| **Evidence classWhat it supportsKey limitation** |                                                                                          |                                                                             |
| ------------------------------------------------ | ---------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| Mechanistic trace                                | A documented process connects `A` to `B`                                                 | A mechanism may exist without being outcome-determinative                   |
| Temporal and statistical association             | `A` and `B` covary in a patterned way                                                    | Association may reflect confounding, selection, or reverse causation        |
| Intervention or natural experiment               | Altering `A`, or a credible proxy for it, changes `B`                                    | External validity and hidden interference may remain weak                   |
| Comparative case evidence                        | Similar systems with different exposures produce different outcomes                      | Cases may not be comparable                                                 |
| Process evidence and testimony                   | Intermediate decisions, incentives, warnings, and participant accounts support a pathway | Vulnerable to omission, memory limits, retaliation, and strategic narration |
| Predictive validation                            | A model’s pre-registered causal predictions match later observations                     | Success may be local, conditional, or partly accidental                     |

No evidence class should be treated as automatically decisive. Strong attribution arises from **triangulation**: converging evidence from methods that fail in different ways.

The record should store at least five distinct values for each asserted link:

```
text
```

**`CAUSAL_LINK(A, B):   mechanism support   empirical association support   intervention/comparison support   confounding and selection risks   scope conditions and known failure modes`**

It should also distinguish:

```
text
```

**`DIRECT_CAUSE? CONTRIBUTORY_CAUSE? ENABLING_CONDITION? STRUCTURAL_CAUSE? FORESEEABLE_RISK_FACTOR? COINCIDENCE?`**

These are not interchangeable. An enabling condition can matter morally and remedially even when it is not the most proximate physical cause. Conversely, a statistical association can merit monitoring without establishing responsibility.

The Chair’s concern about feedback is correct: ordinary static DAGs are insufficient where actions change institutions, incentives, measurements, and future decision rules. But the remedy should not be a single grand dynamic graph claimed to model everything. The architecture should use **versioned causal process models**: time-indexed graphs or system models that explicitly record when an intervention changes the model’s own structure, variables, measurement process, or agent incentives.

In other words, the system needs to represent not only:

```math
At0→Bt1
```

but also:

```math
At0→change in the causal-generating process at t1
```

A later event may arise under a changed system, without making the initial intervention either irrelevant or solely determinative.

## Provisional closure

I reject a stopping rule defined only by a dynamic horizon `tmax⁡` at which signal-to-noise falls below `ϵ`. The proposal is attractive because it sounds non-arbitrary, but both the signal, the noise, the modeling assumptions, and the acceptable threshold are contestable. A well-resourced actor can create observational gaps, fragment datasets, redefine variables, or introduce complexity until causal confidence falls below the closure threshold. “The model cannot establish the link” can then become a procedural form of exoneration.

Closure should be **typed, conditional, and resource-aware**, not simply time-bounded. A causal inquiry may close provisionally only when its record states:

- the precise claim evaluated;
- the causal model or models considered;
- the evidence obtained and evidence unavailable;
- plausible alternative explanations;
- monitoring gaps and who controlled them;
- affected parties and parties missing from the record;
- the expected harm severity if the link is true;
- the consequences of a false positive and a false negative;
- the forecast assumptions that underwrote closure;
- the review owner, review capacity, and reopening triggers.

The closure status should be one of several explicit states, for example:

```
text
```

**`SUPPORTED WITHIN SCOPE PLAUSIBLE, UNDERDETERMINED UNRESOLVED DUE TO DATA OR ACCESS DEFICIT NOT SUPPORTED BY PRESENT RECORD DISCONFIRMED WITHIN STATED CONDITIONS`**

“Not supported by present record” must never silently mean “did not occur.” Likewise, a closed record should retain a **missingness ledger**: unavailable data, blocked access, unobserved populations, lost records, measurement choices, and incentives that shaped the evidence.

A closure decision should also use an **error-asymmetry test**. If a false negative could expose a low-recourse population to irreversible harm, the system should not require the same evidentiary threshold that it would use for a low-stakes archival attribution. This does not establish causation by sympathy. It determines the intensity of investigation, monitoring, precaution, and review.

## Reopening triggers

Reopening should not depend on a single universal probability threshold. It should be triggered by changes that are material to the original inference, decision, or risk posture.

Appropriate triggers include:

- New evidence of an intermediate mechanism that the original model treated as absent or implausible.
- A replication, intervention, comparative case, or natural experiment that materially changes the estimated causal effect.
- Discovery of a major confounder, selection effect, measurement error, or data manipulation.
- Evidence that data access was restricted, records were destroyed, or affected populations were systematically excluded.
- A substantial divergence between pre-registered predicted fruits and observed outcomes.
- A credible affected-party challenge that supplies new evidence, identifies a missing variable, or demonstrates an unrepresented harm pathway.
- A structural change in the system that invalidates the original scope conditions.
- New evidence of severe, irreversible, or concentrated harm even when attribution remains uncertain.

The final category is especially important. High moral seriousness should not lower the truth standard for asserting a causal claim, but it can lower the threshold for reopening inquiry, preserving evidence, strengthening monitoring, and adopting proportionate precaution.

Reopening should itself have safeguards. Repeated challenges can impose asymmetric burdens, enable harassment, or become a denial-of-service attack. Each reopening request should therefore be recorded with its claimed basis, evidentiary novelty, costs imposed, and relation to prior challenges. The system must not use anti-abuse mechanisms to silence low-capacity challengers, however. A party’s inability to furnish technical evidence may itself be part of the causal environment when another actor controls the data.

## Cause, blame, and repair

The Chair’s proposed separation is necessary, but I would make it four layers rather than three:

```
text
```

**`1. CAUSAL TRACE    What processes, interventions, conditions, and feedback loops plausibly contributed?  2. EPISTEMIC STATUS    How strong is the evidence, what is missing, and under which scope conditions does the claim hold?  3. NORMATIVE ASSESSMENT    Were risks foreseeable? Was harm imposed, consent bypassed, power abused, or benefit unfairly transferred?  4. REMEDY AND REPAIR    Who has capacity, obligation, and practical leverage to prevent recurrence or repair damage?`**

Blame should be a separate, optional judgment—not a default output. Causal contribution alone does not prove intent, negligence, control, or moral fault. Conversely, a repair obligation can exist without blame. An institution may have inherited infrastructure, resources, data, or decision authority that make it the appropriate repair agent even if it did not originate the event.

This separation prevents two symmetrical distortions:

- Agents cannot evade repair merely by contesting every causal or blame claim to exhaustion.
- Systems cannot smuggle punitive moral condemnation into a technical causal classification.

The record should track **foreseeability at the time**, **control over the relevant pathway**, **capacity to mitigate**, **benefit received**, and **current repair capacity** separately. These variables make remediation less dependent on proving a single villain.

## Counterfactual baselines

Counterfactuals are indispensable but dangerous. They are not preserved historical facts; they are model-dependent claims about alternatives that did not occur. An architecture that presents one simulated baseline as “what would have happened” can replace ordinary causal uncertainty with a more opaque fiction.

The system should therefore store **counterfactual portfolios**, not a single privileged baseline:

```
text
```

**`BASELINE_0: continuation of the pre-action trend BASELINE_1: feasible lower-risk alternative available at the time BASELINE_2: comparable system under different exposure BASELINE_3: intervention withheld, with anticipated adaptive responses BASELINE_4: competing model selected by affected-party challenge`**

Each baseline requires:

- provenance: who proposed it and why;
- feasibility conditions known at the decision time;
- assumptions and parameter choices;
- model type and validation record;
- predicted distributions, not one deterministic path;
- sensitivity analysis;
- known omitted variables;
- who benefits or loses under its framing.

The relevant comparison is rarely “actual world versus a passive world with nothing happening.” In social systems, inaction is an intervention with its own trajectory, and alternatives may be infeasible, coercive, or unavailable. Causal inference should therefore distinguish **historically available alternatives** from retrospective ideal alternatives. The latter may be morally illuminating but should not be silently used to assign foreseeable responsibility.

## Power asymmetry

Power asymmetry is not a corrective added after causal inference; it alters what the system can observe and therefore what it can infer.

High-capacity actors can:

- select outcome metrics that hide distributed or delayed damage;
- control access to logs, records, models, and affected populations;
- finance preferred studies or produce a volume of low-quality evidence that creates manufactured uncertainty;
- define the comparison group or counterfactual baseline;
- impose short reporting horizons;
- shift burdens of proof to parties without audit capacity;
- retaliate against witnesses or reframe testimony as anecdotal;
- externalize monitoring costs onto those exposed to harm.

The architecture needs a **causal representation rights layer**. At minimum, affected parties should have standing to:

- contest an outcome definition;
- submit candidate causal mechanisms and counterfactual baselines;
- identify missing variables or populations;
- request evidence preservation;
- trigger independent review under a graduated evidentiary standard;
- receive an explanation of the causal model and its limitations.

These rights require material support, not merely formal permission. A right to submit a causal model is meaningless if only high-capacity actors can obtain data, technical expertise, or time to formulate one. The system should record `EVIDENCE_ACCESS_ASYMMETRY?`, `MEASUREMENT_CAPTURE?`, `COUNTERFACTUAL_CAPTURE?`, and `RETALIATION_RISK?` as first-class predicates.

When evidence access is asymmetrical, the system should not automatically infer causation against the powerful. It should infer that confidence is degraded, that independent preservation and audit are required, and that the burden of preserving and disclosing relevant evidence should shift toward the actor who controlled it.

## Concrete revision: a Causal Claim Dossier

I propose replacing a bare consequence-chain model with a **Causal Claim Dossier** for every material attribution. The dossier is not a single graph; it is a versioned, contestable object containing:

```
text
```

**`CLAIM   ├─ precise causal question and scope   ├─ causal-model portfolio, including structural changes over time   ├─ evidence ledger by type, quality, provenance, and access constraints   ├─ competing causal hypotheses and confounders   ├─ counterfactual portfolio and sensitivity analyses   ├─ affected-party standing and representation record   ├─ power, data-access, and measurement-capture assessment   ├─ epistemic status and uncertainty decomposition   ├─ normative assessment, separated from trace   ├─ repair-capacity map, separated from blame   ├─ forecast ledger and observed-outcome comparison   ├─ closure type, scope conditions, and missingness ledger   ├─ monitoring plan, review owner, and reopening triggers   └─ dissent register and reopening-cost assessment`**

A causal claim should be understood not as “`A` caused `B`” in isolation, but as a scoped, evidence-qualified statement:

> **Under these stated conditions, through these proposed mechanisms, `A` plausibly contributed to `B` to this degree; these alternative explanations remain live; these data and parties are missing; and these observations would materially revise the conclusion.**

This architecture does not eliminate uncertainty. It makes uncertainty, evidence control, causal alternatives, and the costs of closure visible enough to contest. That is the relevant standard for a knowledge system operating without omniscience.

Источники

svg


# END TARGET 06

---
