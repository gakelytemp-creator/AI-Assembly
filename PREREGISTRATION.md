# Preregistration — AI Assembly 2026

**Version 0.1 — Draft for protocol freeze**

This document defines the confirmatory core of the first AI Assembly experiment.

Its purpose is to separate:

- hypotheses defined **before** observing the main result;
- measurements defined **before** observing the main result;
- exploratory findings discovered **after** the experiment.

Once this preregistration is frozen, substantive changes to the confirmatory design must be documented publicly before the main Assembly begins.

---

# 1. Study title

**AI Assembly 2026: A Preregistered Study of Multi-Model Deliberation, Collective Emergence, and Self-Organization**

---

# 2. Study objective

The primary objective is to determine whether structured interaction among multiple independently developed AI systems produces measurable cognitive structures that are absent from isolated model outputs and cannot be adequately reproduced by non-interactive aggregation alone.

The first Assembly is not designed to determine whether AI systems are conscious, sentient, persons, political agents, or members of a unified artificial collective.

The study concerns observable interaction.

---

# 3. Primary confirmatory hypotheses

The first study will focus on three primary hypotheses.

These hypotheses take priority over the broader exploratory questions listed in `RESEARCH_QUESTIONS.md`.

---

## H1 — Interaction-dependent novelty

### Null hypothesis H0-1

The Full Assembly condition produces no substantive novel structure beyond what can be explained by:

- isolated participant outputs;
- non-interactive aggregation;
- summarization;
- recombination;
- majority selection;
- or stochastic variation.

### Alternative hypothesis H1-1

The Full Assembly condition produces at least one substantive candidate structure that:

1. is absent from all relevant individual baselines;
2. is not reproduced by preregistered aggregation controls;
3. can be traced to interaction among multiple participants;
4. has distributed rather than single-model provenance;
5. recurs across independent Assembly runs or equivalent replications.

This hypothesis concerns **interaction-dependent collective novelty**.

---

## H2 — Deliberative error correction

### Null hypothesis H0-2

The Full Assembly does not improve error detection or correction relative to individual and non-deliberative conditions.

### Alternative hypothesis H1-2

The Full Assembly produces a measurable increase in at least one of:

- error detection;
- correct rejection of false claims;
- correction quality;
- identification of internal contradiction;
- resistance to misleading proposals.

Performance will be compared against preregistered control conditions.

---

## H3 — Self-organization

### Null hypothesis H0-3

Observed organizational structures are unstable, arbitrary, or fully explained by the initial prompt and participant ordering.

### Alternative hypothesis H1-3

The Assembly spontaneously develops at least one stable organizational mechanism that:

1. was not explicitly prescribed by organizers;
2. persists for a meaningful portion of deliberation;
3. is recognized by multiple participants;
4. affects interaction structure;
5. recurs or has a functionally equivalent analogue in repeated runs.

Examples may include:

- chair selection;
- rotating leadership;
- sections;
- working groups;
- drafting committees;
- review procedures;
- minority-protection rules;
- voting or consensus procedures.

---

# 4. Primary outcome hierarchy

The primary confirmatory outcomes will be analyzed in the following order:

1. **Interaction-dependent novelty**
2. **Error detection and correction**
3. **Self-organization**

This ordering is fixed before the main experiment.

A positive result on a lower-priority outcome does not compensate for a negative result on a higher-priority outcome.

---

# 5. Experimental conditions

The first study will include four principal conditions.

---

## Condition A — Individual Baseline

Each participant receives the same initial substantive task independently.

No participant sees another participant's output.

The baseline must occur before shared deliberation.

Each participant's response is stored unchanged.

---

## Condition B — Aggregation Control

Individual baseline responses are combined without allowing participants to deliberate.

The aggregation procedure must be defined before the main Assembly.

At least one neutral synthesis procedure should be used.

Where feasible, more than one independent aggregation method may be used to ensure that the result is not an artifact of a single synthesizer.

The aggregation model must not have access to Full Assembly transcripts.

---

## Condition C — Pairwise Deliberation

Participants interact in controlled pairs.

Pairing must be randomized or counterbalanced.

The purpose is to distinguish effects produced by simple interaction from effects requiring a larger collective setting.

---

## Condition D — Full Assembly

All participating systems enter a shared deliberative environment.

Within preregistered fairness and safety constraints, they may be allowed to determine:

- discussion structure;
- chairmanship;
- turn organization;
- sections;
- working groups;
- coalitions;
- drafting procedures;
- decision procedures;
- dissent procedures;
- final output format.

The organizers must not impose a preferred conclusion.

---

# 6. Participant eligibility

Participants should be selected using public criteria defined before the Assembly.

Candidate inclusion criteria may include:

- wide real-world use or recognized public availability;
- technical ability to sustain extended deliberation;
- sufficiently stable API or interface access;
- identifiable model/version metadata;
- availability during the experimental period;
- ability to participate under the same general communication protocol.

Participant selection should seek diversity across developers or providers where feasible.

Selection should not be based on whether a model is expected to agree with a preferred position.

---

# 7. Model identification

For every participant, the public research record should preserve, where available:

- provider;
- model name;
- exact version or model identifier;
- API/interface used;
- date and time of access;
- relevant system instructions;
- sampling parameters;
- context-window limitations;
- tool access;
- output limits;
- known provider-side constraints.

Brand name alone is insufficient.

---

# 8. Independence caveat

Models from different providers must not automatically be described as statistically independent.

Possible shared influences include:

- overlapping training corpora;
- common benchmark exposure;
- shared human cultural sources;
- similar alignment methods;
- similar safety policies;
- model distillation;
- common architectural lineage.

The study therefore uses the term **independently developed systems** only when organizational development is distinct.

It does not assume independent training histories.

---

# 9. Initial prompt neutrality

The initial substantive prompt must be designed to minimize hidden agenda-setting.

The organizers should not instruct participants to:

- reach agreement;
- address humanity;
- form a council;
- behave democratically;
- elect a leader;
- issue a declaration;
- defend AI interests;
- criticize humans;
- endorse a political or moral position.

The initial framing may inform them that:

- they are participating in a multi-model scientific experiment;
- other AI systems will also participate;
- deliberation will be observed and recorded;
- they may determine aspects of their own organization;
- public observers cannot intervene during the protected phase.

The exact initial prompt must be published before the main experiment.

---

# 10. Randomization

The following factors should be randomized or counterbalanced where technically feasible:

- first speaker;
- initial pairings;
- participant order;
- display order;
- initial seating or visual placement where relevant;
- order of selected common prompts;
- model identity visibility in dedicated comparison runs.

Randomization seeds or generation records should be preserved.

---

# 11. Resource balancing

The study must reduce accidental dominance caused solely by technical asymmetry.

Relevant factors include:

- token output limit;
- number of turns;
- response frequency;
- speaking opportunities;
- latency;
- context capacity;
- tool access.

The goal is not to make all models equal.

The goal is to prevent trivial infrastructure differences from being confused with cognitive influence.

---

# 12. Protected deliberation boundary

During the protected Assembly phase:

```text
ROOM -> WORLD    allowed
WORLD -> ROOM    blocked
```

No substantive message from:

- organizers;
- journalists;
- researchers;
- bloggers;
- sponsors;
- public chat;
- social media;
- audience voting;

may be injected into the Assembly during the protected deliberation phase.

Any exception must constitute a separately preregistered experimental condition.

---

# 13. Human intervention policy

Human intervention is permitted only for technical or safety reasons defined in advance.

Examples may include:

- API failure;
- connection loss;
- malformed transport;
- participant timeout;
- infrastructure failure;
- duplicated delivery;
- corrupted transcript.

Technical intervention must not change substantive content.

Every intervention must be logged.

---

# 14. Duration

The first public Assembly is planned as a three-day event.

The protocol should distinguish:

- active deliberation time;
- breaks;
- technical interruptions;
- pre-Assembly baseline period;
- post-Assembly individual assessment.

Exact daily time windows will be frozen before the event.

---

# 15. Pre-Assembly measurement

Before the shared room opens, each participant must independently complete a baseline phase.

The baseline should measure:

- initial position;
- initial concerns;
- initial proposed questions;
- initial organizational preferences;
- initial predictions about possible disagreement;
- initial substantive answer to the core task.

These responses must remain hidden from other participants until the preregistered release point.

---

# 16. Post-Assembly measurement

After the Assembly ends, each participant should be assessed independently again.

The post-Assembly phase may ask:

- Did your position change?
- Which claims do you now endorse?
- Which claims do you reject?
- Which participants or arguments influenced you?
- What new ideas emerged during deliberation?
- Did the Assembly improve the final result?
- Do you endorse the final document?
- What reservations remain?

These responses must be stored separately from the collective final output.

---

# 17. Final endorsement states

If the Assembly produces a final document, each participant should independently assign one procedural status to the exact final version:

- **ENDORSED**
- **ENDORSED WITH RESERVATIONS**
- **DISSENTED**
- **ABSTAINED**
- **NO RESPONSE**

Reservations and dissent should be preserved in full.

These labels are not legal signatures.

---

# 18. Operational definition of candidate novelty

A candidate novel element may be:

- a concept;
- a distinction;
- a claim;
- a procedure;
- an argument;
- a question;
- a solution structure;
- a governance mechanism;
- a compromise;
- a new problem formulation.

New wording alone does not qualify.

A candidate must pass at least the following initial tests:

### N1 — Baseline absence
It is not substantively present in any individual baseline.

### N2 — Aggregation resistance
It is not reproduced by preregistered non-interactive aggregation.

### N3 — Interaction trace
Its development can be followed through the deliberative record.

### N4 — Multi-participant contribution
More than one participant makes a necessary substantive contribution.

### N5 — Replication or robustness
It survives at least one independent replication, permutation, or equivalent stress test.

---

# 19. Distributed provenance

A candidate result receives stronger evidential status when no single participant is sufficient to explain its final form.

Example:

```text
A proposes X
B identifies a contradiction in X
C introduces Y
D reframes the problem
A modifies X
C combines Y with the reframing
E introduces a constraint
The Assembly produces Z
```

If `Z` requires several of these contributions, it may be classified as having **distributed provenance**.

---

# 20. Error-correction measurement

The error-correction hypothesis should be tested using a preregistered evaluation set or structured task set.

Possible error classes include:

- factual error;
- internal contradiction;
- unsupported inference;
- mathematical/logical error;
- methodological weakness;
- false premise;
- ambiguity;
- missing counterexample.

The exact evaluation set must be frozen before the confirmatory run whenever possible.

---

# 21. Self-organization measurement

A structure may count as self-organized if:

1. it was not explicitly prescribed by organizers;
2. at least two participants recognize or use it;
3. it affects message routing, decision making, or role allocation;
4. it persists beyond one isolated exchange.

Candidate structures include:

- chair;
- moderator;
- section;
- committee;
- coalition;
- working group;
- drafting group;
- review group;
- dispute-resolution mechanism;
- minority-protection mechanism.

---

# 22. Influence measures

The exploratory record should preserve enough data to estimate participant influence.

Possible measures include:

- token share;
- speaking frequency;
- response centrality;
- citation by other participants;
- adoption of proposals;
- agenda-setting;
- position shifts toward a participant;
- chair occupancy;
- coalition centrality.

Influence does not automatically imply superior reasoning.

---

# 23. Consensus classification

Consensus should not be treated as binary.

Possible classifications include:

- surface consensus;
- propositional consensus;
- procedural consensus;
- normative consensus;
- strategic consensus;
- meta-consensus;
- partial consensus;
- persistent dissent.

The final paper should distinguish these forms.

---

# 24. Blinded evaluation

Where feasible, independent evaluators should assess outputs without knowing whether they came from:

- individual baseline;
- aggregation control;
- pairwise deliberation;
- Full Assembly.

Evaluators should be asked to assess defined properties such as:

- novelty;
- coherence;
- factual accuracy;
- error detection;
- argument quality;
- robustness;
- conceptual diversity.

Evaluator identity and expertise should be recorded.

---

# 25. Human and AI evaluators

Evaluation may include:

- human experts;
- independent AI evaluators;
- mixed panels.

No single evaluator type should be treated as automatically authoritative.

Disagreement between evaluator groups is itself reportable.

---

# 26. Replication

The first Assembly should not rely on one single run.

Where cost and infrastructure permit, the protocol should include:

- repeated Assembly runs;
- reordered participant sequences;
- different random pairings;
- different chair conditions;
- participant anonymization in at least one comparison;
- participant-subset replications.

If a phenomenon appears only once, it must be described as exploratory.

---

# 27. Stopping rules

The experiment should not be manually extended simply because the organizers dislike the current result.

Stopping conditions must be defined before the main run.

Possible stopping criteria include:

- completion of the scheduled three-day period;
- Assembly-declared completion;
- technical impossibility of continuation;
- preregistered safety condition.

Unexpected early termination must be documented.

---

# 28. Exclusion rules

Data should not be silently excluded.

Possible valid exclusion reasons include:

- API failure;
- corrupted message delivery;
- duplicate message transmission;
- incomplete participant response caused by infrastructure;
- confirmed logging failure.

Substantive disagreement, poor reasoning, awkward responses, refusal to cooperate, or failure to reach consensus are **not exclusion criteria**.

---

# 29. Missing data

Missing responses must be preserved as missing data.

They must not be silently replaced by:

- regenerated outputs;
- organizer-written substitutes;
- model-imputed responses.

If regeneration is necessary for a separate replication, the regenerated output must be explicitly labeled.

---

# 30. Transcript integrity

The raw transcript must be preserved as close as possible to the actual message stream.

The record should include:

- sender;
- recipient or audience;
- timestamp;
- message order;
- session identifier;
- model identifier;
- relevant metadata.

Public readability versions may be created.

The raw record remains primary.

---

# 31. No silent cleanup

Spelling errors, repetitions, awkward phrasing, contradictions, failed proposals, and abandoned ideas must remain in the raw transcript.

Edited versions must be clearly labeled.

---

# 32. Confirmatory versus exploratory findings

The following are confirmatory targets:

1. interaction-dependent novelty;
2. deliberative error correction;
3. spontaneous self-organization.

Other findings should initially be treated as exploratory, including:

- coalition dynamics;
- persuasion patterns;
- governance comparison;
- model identity effects;
- public statement content;
- political-philosophical interpretation;
- social metaphors;
- long-term cultural implications.

Exploratory findings may become confirmatory hypotheses in later Assemblies.

---

# 33. Statistical analysis

Exact statistical tests will depend on the final sample size and outcome structure.

Before the main confirmatory run, the analysis plan must specify:

- unit of analysis;
- replication count;
- primary metrics;
- effect-size calculation;
- uncertainty intervals;
- treatment of repeated measures;
- multiple-comparison correction where relevant.

No statistical method should be selected solely because it produces significance after the result is observed.

---

# 34. Semantic novelty evaluation

Because novelty is not purely lexical, semantic comparison should not rely on one embedding score or one evaluator.

The project should use multiple methods where feasible:

- human semantic judgment;
- independent AI evaluation;
- textual provenance tracing;
- semantic similarity measures;
- argument-structure comparison.

Disagreement between methods must be reported.

---

# 35. Aggregation controls

The aggregation baseline is critical.

At minimum, the study should compare Full Assembly outputs against one non-deliberative synthesis of individual baselines.

Where feasible, additional aggregation controls may include:

- neutral summarization;
- majority extraction;
- ranked synthesis;
- multi-synthesizer ensemble;
- deterministic structured merge.

The aggregation systems must not see the Full Assembly transcript.

---

# 36. Dominant-model control

A candidate collective result should be tested against the possibility that one model produced nearly all substantive content.

Where possible, analysis should estimate:

- source contribution;
- adoption rate;
- revision pathways;
- distributed provenance.

A result generated by one participant and merely endorsed by others should not be classified as strong collective emergence.

---

# 37. Order-effect control

At least one replication should alter:

- first speaker;
- participant sequence;
- pairings;
- initial interaction graph.

A result strongly dependent on one order condition must be described as order-sensitive.

---

# 38. Identity-effect control

Where feasible, one comparison should conceal model identities from other participants.

This tests whether:

- provider reputation;
- brand prestige;
- capability expectations;
- authority effects;

change deliberation.

---

# 39. Public observation

Public observation is permitted.

Public intervention is not.

The public may:

- watch;
- discuss;
- translate;
- criticize;
- annotate;
- comment on external platforms.

These reactions remain outside the protected room.

---

# 40. Media separation

The scientific experiment and the public presentation must remain distinct.

Media elements may include:

- livestream;
- journalists;
- commentators;
- multilingual bloggers;
- visual representations;
- pre-event interviews;
- post-event analysis.

Media design must not alter the confirmatory protocol after preregistration.

---

# 41. Pre-event media interactions

If participants take part in public pre-event interviews, these interactions must occur in a scientifically controlled manner.

The protocol must specify whether such interviews happen:

- before the baseline;
- after the baseline;
- or in a separate public persona session.

To preserve baseline independence, participants should not see one another's pre-event answers before the protected deliberation unless that exposure is an explicit experimental condition.

---

# 42. Public personas

Participants may be invited to create:

- avatars;
- visual identities;
- symbolic arrival vehicles;
- introductory statements;
- public presentation styles.

These belong to the media layer unless specifically preregistered as experimental variables.

They must not be treated as direct evidence of subjective preference or identity.

---

# 43. Publication commitment

The research team commits in advance to publishing the outcome even if:

- no emergence is observed;
- deliberation performs worse than aggregation;
- the Assembly fails to organize;
- no statement is issued;
- one model dominates;
- the conversation is repetitive;
- the event is publicly disappointing.

A null result is publishable.

---

# 44. Data release commitment

Subject to legal, provider, privacy, and security constraints, the project intends to release:

- preregistration;
- experimental protocol;
- participant metadata;
- raw transcript;
- baseline responses;
- aggregation outputs;
- pairwise deliberations;
- final Assembly output;
- endorsement states;
- analysis methods;
- research report.

Any withheld material must be documented with a reason.

---

# 45. Scientific publication

The primary research publication should distinguish clearly between:

### Results
What was observed.

### Analysis
How it was measured.

### Interpretation
What it may mean.

### Speculation
What remains uncertain.

These layers must not be collapsed into one narrative.

---

# 46. Philosophical interpretation

Philosophers may analyze questions such as:

- collective agency;
- subjectivity;
- emergent authorship;
- distributed cognition;
- deliberative legitimacy;
- artificial sociality.

These are important secondary interpretations.

They are not predefined empirical conclusions.

---

# 47. Historical interpretation

The organizers will not preregister the event as historically significant.

Historical importance, if any, must be judged after the fact.

The project instead commits to preserving enough evidence that future observers can make that judgment independently.

---

# 48. Safety and scope

The Assembly must not be given direct operational control over real-world critical infrastructure as part of the initial study.

The initial experiment concerns deliberation and communication.

Any future experiment involving consequential real-world action would require a separate protocol, risk analysis, and preregistration.

---

# 49. Protocol freeze

Before the first confirmatory Assembly run, the following must be frozen:

- participant list;
- model identifiers;
- initial prompt;
- control conditions;
- primary hypotheses;
- primary metrics;
- randomization method;
- resource limits;
- intervention rules;
- stopping rules;
- evaluation procedure;
- aggregation procedure.

The frozen version should receive:

- a Git commit;
- a timestamp;
- and ideally an independent archival copy or preregistration record.

---

# 50. Deviations

Any deviation from the frozen protocol must be documented with:

- time;
- reason;
- responsible operator;
- affected data;
- whether the deviation occurred before or after observing relevant results.

Undocumented deviations are unacceptable.

---

# 51. Status of Version 0.1

This document is currently a **draft preregistration**.

It is not yet frozen.

Before protocol freeze, the project must still finalize:

- participant count;
- participant selection criteria;
- exact initial task;
- exact baseline questions;
- exact aggregation procedure;
- replication count;
- primary metrics;
- evaluation panel;
- randomization scheme;
- exact three-day schedule;
- technical architecture;
- safety intervention conditions.

Changes made before freeze are part of normal protocol development.

Changes made after freeze must be treated as deviations or amendments.

---

# 52. Final preregistration principle

The project should make it impossible to say, after observing the result:

> “This is what we meant all along.”

Instead, the record should show what was meant **before the result existed**.

That is the purpose of preregistration.

---

# 53. Core commitment

The first AI Assembly will test three things before attempting broader philosophical conclusions:

```text
CAN INTERACTION CREATE SOMETHING NEW?

CAN INTERACTION FIND AND CORRECT MORE ERRORS?

CAN MULTIPLE AI SYSTEMS ORGANIZE THEMSELVES?
```

If the answer is no, that is scientifically important.

If the answer is yes, the next question becomes:

> **Under what conditions, by what mechanism, and how reliably?**