# Session 002 — DeepSeek Verification Retransmission V2 — Part 8/11

**Participant:** DeepSeek — latest reasoning model, web interface  
**Target archive:** `RESPONSES/03_DEEPSEEK_WEB_REASONING_MODEL.md`  
**Archive blob SHA:** `b9eac2e3681b11898205295b15a5456c704f2286`

This is Part 8 of 11 of the exact raw archived first-pass Markdown.

Do **not** issue a verification verdict yet.

After reading this part, reply only:

~~~text
RECEIVED PART 8 — awaiting next part
~~~

## Raw archived first-pass Markdown — Part 8/11

~~~markdown
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
