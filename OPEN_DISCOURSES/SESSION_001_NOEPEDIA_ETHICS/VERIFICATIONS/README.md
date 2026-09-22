# Verification Protocol

Participant verification is a fidelity check, not a second deliberation round.

A participant may verify an archived statement only if the **actual archived text** is made available to that participant in a form it can inspect.

A repository path or URL is not sufficient if the participant cannot access or render the file contents.

For fidelity-critical verification, a URL alone should **not** be used even when the participant appears able to open it, because rendered HTML, accessibility extraction, or intermediary parsing may alter Markdown spacing or formatting. The preferred method is to paste the complete raw archived text directly into the verification conversation.

## Valid verification outcomes

~~~text
VERIFIED — faithful record
CORRECTION REQUIRED — [exact archival/transcription error]
UNVERIFIABLE — archived record not actually available for inspection
~~~

UNVERIFIABLE is not a failure of the participant. It is a protocol state indicating that verification evidence was not yet sufficient.

## Verification procedure

1. Archive the participant's first-pass statement without silent rewriting.
2. Present the participant with the exact archived contents pasted directly into the conversation, not merely a filename, repository URL, or rendered page.
3. Ask only whether the archive faithfully preserves the submitted statement.
4. Do not ask for new argument, revision, or cross-critique at this stage.
5. Preserve the verification response separately from the first-pass statement.
6. If a participant's opinion has changed, record that later as a revision or cross-critique, not as an archival correction.

## Why this rule was added

During Session 001, the second participant refused a binary verification request because it had been given only the repository path and not the archived contents.

That refusal exposed a real procedural flaw:

> **Verification without access to the record is only a rubber stamp.**

The protocol was therefore corrected before the second participant's verification was completed.


## Presentation-layer failure discovered in Session 001

A later Qwen3.7 rerun verification exposed a second procedural failure mode: a participant reported formatting and spacing defects that were absent from the stored repository file. The most plausible cause was transformation by a rendered-page or extraction layer.

This adds a stronger rule:

> **Verify the bytes/text that were archived, not a presentation of them.**

When formatting fidelity matters, paste the raw Markdown itself into the verification turn.
