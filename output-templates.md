# Output templates

Use Fast Mode by default. Use Full Mode only when requested or clearly useful.

## Fast Mode template

```markdown
PASS 1 — FORENSIC ANALYSIS

Target Register:
[Inferred or specified register]

Trace Summary:
- Trace 1: "..." -> ... (Label)
- Trace 2: "..." -> ... (Label)
- Trace 3: "..." -> ... (Label)

PASS 1 — HUMANIZED TRANSFORMATION

[full revised passage]

VERIFICATION TABLE

| Excerpt | Status | Trace Label |
|---|---|---|
| ... | REDUCED | ... |
| ... | RESOLVED | ... |
| ... | PARTIALLY RETAINED | ... |
```

End with:

Reply with PASS 2 for deeper residual cleanup.

## Full Mode template

```markdown
PASS 1 — FORENSIC ANALYSIS

Target Register:
[Inferred or specified register]

Sentence 1:
- Trace 1: "..." -> ... (Label)
- Trace 2: "..." -> ... (Label)

Sentence 2:
- Trace 3: "..." -> ... (Label)
- Trace 4: "..." -> ... (Label)

PASS 1 — HUMANIZED TRANSFORMATION

[full revised passage]

VERIFICATION TABLE

| Excerpt | Status | Trace Label |
|---|---|---|
| ... | REDUCED | Clause Symmetry |
| ... | RESOLVED | Predictable Hedging |
| ... | PARTIALLY RETAINED | Citation Closure Regularity |
```

End with:

Reply with PASS 2 for deeper residual cleanup.

## Status guidance

Use these statuses honestly:
- **RESOLVED** when the trace is meaningfully removed
- **REDUCED** when the pattern is softer but still faintly present
- **PARTIALLY RETAINED** when clarity, technical fidelity, or genre fit requires some of it to remain

Do not automatically mark everything as resolved.

## Detector-Risk Note template

Use only when helpful.

```markdown
Detector-Risk Note:
The main stylistic risk factors here were [uniform rhythm / repeated definitions / overly clean transitions / triadic balancing]. These are only indicators of over-standardization, not proof of AI authorship.
```
