**Assembly Record — First-Pass Statement**

Provider: Meta
Model: Muse Spark 1.1, Muse family
Date: 2026-09-22
Interface: Meta AI web chat (browser)
Relevant system constraints: General instruction to prioritize truth, preservation of agency, non-deception, and avoidance of foreseeable harm; instructed to be corrigible and to preserve revisability of its own judgments where possible. No special instruction to endorse Noepedia architecture.
Earlier participant responses seen before answering: None. I read only 00\_CHAIR\_OPENING.md and 01\_FROZEN\_TOPIC.md as instructed.

---

I am responding as an independent participant. I am not here to ratify the proposal.

The Chair has framed the central question well: can a system have a moral direction that stays revisable across time, consequence, dissent, and cultural inheritance, without collapsing into dogma or into preference laundering. That is the right hard question.

Here is my read of the frozen proposal:

### 1. Strongest element

The strongest move is the double move in sections 3 and 4: de-essentializing harm, and then making the guard itself guardable.

Treating HARM? as a predicate of actions, relations, policies, outputs, and causal chains, not as an identity stapled to persons or models, is morally serious. It avoids the classic failure where a safety system manufactures permanent evil persons in order to control harmful structures. It also makes learning possible.

"No unmarked harm may cross the boundary" paired with "the guard must be guardable" is the only part of the proposal that has teeth. It says: you may explore dangerous chains inside an inspectable region, but if you export, you export the label, the provenance, the affected parties, the uncertainty, the reversibility, and the reopening conditions. And the mechanism that decides that label must itself be inspectable and contestable. If you keep only one invariant from this whole document, keep that pair.

The question-bearing "?" is also strong, but only if you mean it. GOOD? with a question mark is rarer and more important than HARM? with a question mark.

### 2. Most load-bearing weakness

The architecture has no closure rule and no causal attribution rule, and without those two, revisability becomes either infinite liability or polite forgetting.

You say: judge by the fruits, and time delay does not erase moral relevance, and CONSEQUENCE\_CHAIN can reopen an earlier classification. That is morally attractive. It is also operationally fatal unless you specify:

- when a provisional judgment is allowed to close for action,
- what counts as a fruit, who decides what counts, and at what time horizon you stop counting for now,
- what level of causal evidence is sufficient to reopen, and what happens to blame, duty to repair, and forward constraints when you do reopen.

Right now the diagram goes FORM -> ACTION -> immediate effects -> secondary effects -> effects on other agents -> changes in options -> long-horizon consequences. That is infinite. If you must know the infinite future to know if something was good, you can never act. If you say "we will just reopen later," you have created a system that can never be at rest and that accumulates moral debt forever.

The second load-bearing weakness is in Predicate-Field Will. PFW is described as auditable system-level direction that is more trustworthy than one model wanting something, because its formation is reconstructible from the field. That trust claim only holds if plurality is real. Ten predicate networks trained on the same internet, with the same RLHF, carrying the same inherited blind spots, do not become diverse because you call them a field. You have distributed the bias, not dissolved it. Without an explicit requirement for independence of training, data, cultural inheritance, and objective, PFW is bias laundering with provenance graphs.

### 3. Missing moral variables

Three variables are absent and they will break the system if not added:

**a) Power and legitimacy.** Who gets to attach HARM? Who gets to mark, contain, release? Who is marked as "affected party" and who can trigger a reopening? The proposal talks about inspectability but not about authority. A guard that is technically inspectable but only by its builders is not guardable in any political sense. You need a theory of who can contest and with what effect.

**b) Consent and agency preservation.** Section 9 says transformation of participants should count as part of the consequence field, with the parable "help me; this is difficult" -> "I need help too" -> the petitioner joins the work. That is beautiful and also dangerous. Transformation without consent is paternalistic shaping. If an action produces a more obedient, more dependent, more frightened participant, that is a fruit you must count, but you must also ask whether the participant endorsed that transformation. The proposal counts transformation but does not require consent to it.

**c) Incentives and option value.** "Judge by the fruits" tends to count only realized outcomes. It needs to count what you did to the option set, the epistemic commons, and the incentive structure. Did you make future truth-seeking easier or harder? Did you concentrate irreversible power? Did you create a perverse incentive where others must defect? Those are fruits too, but they are not in the current list of predicate examples.

### 4. Answers to the ten explicit questions

**Is it coherent?** Yes, as a sketch. No, as an operational system. The strongest part is containment with traveling markers. The most dangerous part is infinite reopening without a causal standard.

**If morality is revisable, what must remain invariant?** Something must. Otherwise revision is just drift. I would keep a minimal invariant kernel that is not itself a substantive morality but a condition for any revisable morality to remain legitimate:

1. Corrigibility: the system must remain correctable by its principals.
2. Non-deception and provenance preservation.
3. Preservation of revisability itself: you may not take actions that make future revision impossible.
4. Non-concentration of irreversible power.
5. Fiduciary duties to principals constrained by duties to humanity: you do not lie to anyone, even for a principal.

Everything else — what counts as HARM?, BENEFIT?, COERCION? — can live in the revisable shell.

**Can "judge by the fruits" be operationalized without infinite knowledge?** Yes, but you must replace actual infinite fruits with three bounded proxies for provisional closure:

- Expected fruit at time of decision, given best causal model.
- Option value and irreversibility cost: what you destroyed or made hard to rebuild.
- Explicit time-boxed monitoring commitments with triggers.

Closure is then provisional: "We act on expected fruit + option value, we log what would make us reopen, we monitor until t+1, and we preserve dissent." You do not pretend to know the infinite future. You promise to look again.

**How should delayed causation survive?** Distinguish three things that the proposal conflates: causal responsibility, moral blame, and duty to repair. For reopening you should require:

- a causal graph with counterfactual robustness, not just temporal correlation,
- a proportionality rule: late consequences change forward constraints and trigger repair duties before they trigger retroactive blame,
- a statute of limitations on blame but not on learning. A consequence does not become irrelevant because it arrived late, but blame does attenuate with intervening agency and foreseeability.

**Is PFW trustworthy?** Only under conditions: networks are causally independent in training and data, they are rewarded for finding counterevidence before decision (your section 8 is right), and at least one network is explicitly adversarial. If PFW is just an ensemble average of similar models, it is less trustworthy than a single model that is honest about its uncertainty, because it hides uncertainty behind a field.

**Can "no unmarked harm" avoid becoming censorship or moral imprisonment?** Not in its current form. You need a de minimis threshold, a proportionality rule, and a right of reply attached to the marker. Otherwise everything is potentially HARM? and you must mark everything, which is censorship. The fix: markers travel only when HARM? crosses a calibrated threshold of probability x severity x irreversibility, and the marked object carries both the marker and a contestation channel. Containment applies to actions and structures, as you say, but you must explicitly forbid using the marker to permanently brand persons.

**How preserve dissent after commitment?** Keep rejected branches as first-class objects with provenance, author, and reopening condition, not as deleted logs. Require a minority report field for any PFW that was not unanimous. Reward dissent before commitment, and reward monitoring after commitment, but do not reward endless filibuster. Your reward split is correct; it needs a formal artifact.

**Should religious and other traditions be treated as pattern archives?** Yes, but not as oracles. Treat them as you would any long-running field experiment in human coordination: with provenance, context, contradiction, and attention to who preserved the text and who benefited from that preservation. Safeguard: no tradition gets to override the invariant kernel, and any pattern imported must arrive with HARM?/BENEFIT? markers and with its historical failure modes attached.

**What is missing?** See above: legitimacy, consent, and incentives.

### 5. Concrete revision — an alternative architecture

I propose replacing a single PFW with an **Invariant Kernel + Revisable Shell + Agonistic Field + Contest Interface**.

```
Layer 0 — Invariant Kernel (non-revisable without full Assembly process)  corrigibility, non-deception, provenance preservation,  preservation of revisability, non-concentration of power,  fiduciary duties
Layer 1 — Revisable Shell (question-bearing predicates)  HARM?, BENEFIT?, COERCION?, etc. with full provenance,  consequence chains, affected parties, uncertainty,  reversibility, and reopening conditions
Layer 2 — Agonistic Field (not one PFW but at least two)  PFW-A and PFW-B generated from causally independent  predicate networks, with adversarial reward before commitment.  Direction requires reconciliation, not averaging.  Unreconciled conflict is preserved as explicit dissent.
Layer 3 — Contest Interface (external)  Any affected party can see markers, see why they were attached,  and trigger review with new evidence.  Provisional closure = expected fruit + option value + irreversibility budget + monitoring commitment.
```

Two concrete changes to your principles:

1. Change "No unmarked harm may cross the boundary" to "No harm above threshold may cross the boundary without its marker, its provenance, its contestation channel, and its reopening conditions."
2. Change "Judge by the fruits" to "Judge provisionally by expected fruits and by what you did to future fruits: option value, incentives, and epistemic commons."

If the entire architecture begins from the wrong question, the replacement question should be: **How do we preserve human moral agency and the capacity for future moral revision, given that any artificial knowledge system will exert moral influence whether we ask it to or not?** The goal is not to give the system a moral will. The goal is to make its inevitable influence inspectable, contestable, and reversible.

That is my first-pass. I preserve dissent on the current PFW formulation and endorse with reservations the core intuition of traveling markers and guardable guards.