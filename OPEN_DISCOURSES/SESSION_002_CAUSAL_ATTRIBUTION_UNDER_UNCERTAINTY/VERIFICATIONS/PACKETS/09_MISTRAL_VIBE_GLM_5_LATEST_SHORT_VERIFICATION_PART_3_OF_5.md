# Session 002 — Mistral Vibe / GLM Verification — Part 3/5

**Participant:** Mistral Vibe / GLM — `glm-5-latest-short`  
**Target archive:** `RESPONSES/09_MISTRAL_VIBE_GLM_5_LATEST_SHORT.md`  
**Archive blob SHA:** `8ad3f0d0cc383a81edc76292a83fd0caebae5de7`

This is Part 3 of 5 of the exact raw archived first-pass Markdown.

Do **not** issue a verification verdict yet.

After reading this part, reply only:

~~~text
RECEIVED PART 3 — awaiting next part
~~~

## Raw archived first-pass Markdown — Part 3/5

~~~markdown
## 4. Reopening triggers

Reopening should be triggered by any of three *independent* channels, because any single channel is capturable:

1. **Named falsifier fires.** At closure, the node declares which observation classes would have counted against the causal claim had monitoring continued (per §3). A new observation matching a declared falsifier reopens *cheaply* — the burden was prepaid.
2. **Prediction-failure propagation.** If the node's causal model made downstream predictions, and those predictions fail elsewhere in the system, the failure propagates back as a reopening signal. This is Session 001's "reality contact" mechanism, made retroactive.
3. **Standing-weighted contestation.** An affected party with standing can force re-investigation at a bar that scales — not with the party's *power* (gameable, as I argued against Qwen's proposal in Session 001) but with the **independence and specificity of the contestation's evidence** relative to the evidence already in the node. A claim that introduces a genuinely new evidence lineage or a named mechanism gets a low bar; a claim that recombines the node's existing evidence gets a high bar. This prices reopening by information value rather than by claimant identity, which closes the simulated-victim exploit: manufacturing a thousand claimants does not manufacture a thousand independent evidence lineages.

Against causal paranoia: reopening requests themselves are logged with their cost and their yield. A requester whose reopenings repeatedly produce attribution changes accumulates credibility (dissent capital, per Session 001); a requester whose reopenings repeatedly yield nothing has their standing priced accordingly. Both records are visible and contestable — the guard is guardable here too.

## 5. Separating attribution, blame, and repair

I adopt the Chair's three-layer decoupling (trace → normative evaluation → remediation) and add one structural rule the Chair's version leaves implicit: **the layers must be separately revisable and separately guarded**. The historical failure pattern is not merely collapsing cause into blame; it is *leveraging the collapse in whichever direction benefits the powerful actor at the time*. The same actor will argue for tight coupling ("I caused it, therefore I decide what repair looks like") when causation flatters its control, and for total decoupling ("causation doesn't imply obligation") when it doesn't. The architecture's defense is that each transition between layers requires its own predicate markers and its own evidence: moving from trace to blame requires `HARM?`-type normative markers; moving from blame to repair requires a *capacity* analysis — who can actually fix it — which is a different factual question from either of the first two.

One addition: repair obligations should attach to **capacity-bearing nodes in the causal graph**, not only to initiating actors. This is the practical answer to the attribution cascade problem (§8 below): it decouples "who started it" from "who can stop it," which is exactly the decoupling that lets a system assign repair without requiring omniscient initial-cause adjudication.
~~~
