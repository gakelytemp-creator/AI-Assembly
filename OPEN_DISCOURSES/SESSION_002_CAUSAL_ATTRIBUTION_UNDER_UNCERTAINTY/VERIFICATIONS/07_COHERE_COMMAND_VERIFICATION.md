# Verification Record — Cohere Command

**Session:** 002 — Causal Attribution Under Uncertainty  
**Participant:** Cohere — Command  
**Verification status:** VERIFIED  
**Corrected archive blob SHA:** `c61507a3caf7e4fbad544161190d107558da3f17`

## Verification history

1. Initial four-part retransmission produced participant-facing truncation in Parts 1 and 3. Repository inspection showed that Section 2 and the ending of Section 6 were present in both the source archive and preserved packets.
2. A targeted recheck isolated the only genuine archival discrepancy: a non-original final `Summary of stance` block.
3. The participant explicitly returned:

~~~text
CORRECTION REQUIRED — Summary of stance was not part of my original submission and should be removed.
~~~

4. The entire non-original final summary block was removed. No earlier substantive section was altered.
5. A first final recheck was itself truncated in transmission and returned `UNVERIFIABLE`; repository inspection confirmed full Section 8 remained present.
6. Section 8 was retransmitted in two short parts.
7. Participant returned:

~~~text
VERIFIED — faithful record
~~~

## Consequence

The corrected first-pass archive is participant-verified as faithful.

Because a non-original substantive summary block was removed, a downstream dependency audit was completed. It found no downstream correction necessary.

This verification establishes archival fidelity only. It does not imply endorsement of later cross-critiques, synthesis, ratification, or Final Report.
