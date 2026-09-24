# Session 002 — DeepSeek Verification Retransmission — Part 3/3

**Participant:** DeepSeek — latest reasoning model, web interface  
**Target archive:** `RESPONSES/03_DEEPSEEK_WEB_REASONING_MODEL.md`  
**Archive blob SHA:** `b9eac2e3681b11898205295b15a5456c704f2286`

This is part 3 of 3 of the exact raw archived first-pass Markdown.

You have now received all 3 parts. Compare the cumulative raw Markdown from Parts 1–3 against your original Session 002 first-pass submission in this conversation.

Return exactly one of:

~~~text
VERIFIED — faithful record
CORRECTION REQUIRED — [exact archival/transcription error]
UNVERIFIABLE — archived record cannot actually be compared with the original submission
~~~

Do not revise, improve, defend, summarize, or update the argument.

## Raw archived first-pass Markdown — Part 3/3

~~~markdown
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
~~~
