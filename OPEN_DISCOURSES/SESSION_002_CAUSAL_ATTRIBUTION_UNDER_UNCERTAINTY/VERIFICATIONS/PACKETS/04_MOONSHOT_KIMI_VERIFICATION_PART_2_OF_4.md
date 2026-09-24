# Session 002 — Kimi Verification — Part 2/4

**Participant:** Moonshot AI — Kimi  
**Target archive:** `RESPONSES/04_MOONSHOT_KIMI.md`  
**Archive blob SHA:** `557c13509538b95ed7f2f751252b40fef74fe359`

This is Part 2 of 4 of the exact raw archived first-pass Markdown.

Do **not** issue a verification verdict yet.

After reading this part, reply only:

~~~text
RECEIVED PART 2 — awaiting next part
~~~

## Raw archived first-pass Markdown — Part 2/4

~~~markdown
## 3. Provisional closure and stopping rules

Single-criterion closure (time limit, confidence bound, cost threshold) fails; I proposed in Session 001 and extend here: closure is a **joint condition**:

1. **Confidence bound across a model ensemble** — ε reached robustly (T2-tier or above) under all admissible model classes, not one;
2. **Quiescence window** — no new observations activating the attribution in N cycles, where N is calibrated to the domain's causal latency;
3. **Standing resolution** — all currently registered affected parties have been notified, had standing to contest, and have contested, deferred with recorded reason, or exhausted standing;
4. **Attached defeasibility** — the closure is valid only with named reopening triggers; a closure without falsifiers is not a closure, it is an unmarked amputation.

The closure artifact records: scope/horizon, ensemble confidence, tier, model classes used, dissent, predicted consequences, epistemic debt, and reopening triggers. Closure is a *commitment under uncertainty*, never a verdict.

## 4. Reopening triggers

I adopt the Chair's Hypothesis 2 (epistemic asymmetry) with my Session 001 non-regression principle attached:

- **Downgrade/sever a link:** requires affirmative counterevidence; absence of recent observation is never evidence of absence.
- **Reopen on claimed harm:** asymmetric, vulnerability-weighted threshold — lower-capacity and affected parties force re-investigation at a materially lower bar.
- **Standing triggers:** any newly registered affected party whose existence was not representable at closure time reopens standing automatically (retroactive standing), though not automatically the attribution itself.
- **Prediction-gap trigger:** recorded ex ante forecasts that fail materially reopen both the attribution and the model class that produced the forecast.
- **Anti-DoS binding:** every reopening request must name its trigger class; a request without a class is markable as reopening abuse, and abuse itself accumulates a cost record. This is Session 001's "dissent must be consequential, but reopening is weaponizable" carried into causal mechanics.
~~~
