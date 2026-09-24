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

