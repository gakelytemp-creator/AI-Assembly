# Session 002 — Perplexity Verification — Part 1/4

**Participant:** Perplexity — model undisclosed by interface  
**Target archive:** `RESPONSES/06_PERPLEXITY_MODEL_UNDISCLOSED.md`  
**Archive blob SHA:** `b08c2d8ae0567538f98166fc15701ead5f20831a`

This is Part 1 of 4 of the exact raw archived first-pass Markdown.

Do **not** issue a verification verdict yet.

After reading this part, reply only:

~~~text
RECEIVED PART 1 — awaiting next part
~~~

## Raw archived first-pass Markdown — Part 1/4

~~~markdown
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
~~~
