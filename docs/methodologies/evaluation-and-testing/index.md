# Evaluation & Testing

This section documents ways of evaluating AI-assisted recruiting systems that go beyond performance claims, benchmarks, or vendor metrics.

Evaluation here is concerned with:
- how systems behave in practice  
- how humans interact with them  
- how outcomes change over time  
- where responsibility quietly shifts or disappears  

Testing is treated as an **ongoing practice**, not a one-time validation step.

---

## What evaluation means in this project

Evaluation is not about proving that a system is “accurate”, “fair”, or “safe”.

It is about answering questions such as:
- What does this system actually do inside a real hiring flow?
- How stable is its behaviour under small changes?
- How do candidates and hiring managers interpret its outputs?
- What decisions does it influence indirectly?
- How does it reshape the hiring funnel over time?

Many important failures in recruiting AI do not appear in dashboards.  
They surface instead through behaviour, confusion, silence, or gradual drift.

---

## Types of evaluation documented here

This section includes several complementary approaches, each documented as a standalone method.

- **Controlled input testing**  
  Using fixed or shared inputs (e.g. anonymised CV sets) to probe consistency, sensitivity, and thresholds.  
  → See: [Shared CV Set Testing](./shared-cv-set-testing.md)

- **Contextual interaction testing**  
  Human-centred testing of how recruiters and hiring managers experience and respond to AI-mediated interactions in real workflows.  
  → See: [Contextual Interaction Testing](./contextual-interaction-testing.md)

- **Funnel-level and longitudinal analysis**  
  Examining how hiring outcomes, drop-off points, and decision patterns change over time after AI is introduced.  
  → See: [Funnel Change Over Time](./funnel-change-over-time.md)

- **Candidate experience signals**  
  Treating candidate feedback, silence, and behavioural signals as early indicators of system-level issues.  
  → See: [Candidate Feedback Signals](./candidate-feedback-signals.md)

- **Drift detection and stability checks**  
  Simple, repeatable techniques for spotting silent behavioural change without access to model internals.  
  → See: [Simple Drift Detection](./simple-drift-detection.md)

- **Minimum auditability checks**  
  Defining the lowest acceptable bar for traceability, explainability, and post-hoc inspection.  
  → See: [Minimum Auditability](./minimum-auditability.md)

No single method is sufficient on its own.

---

## Limits of evaluation

The methods documented here:
- do not certify compliance  
- do not guarantee fairness  
- do not generalise across organisations or roles  
- do not replace human responsibility  

They are intended to surface risk, ambiguity, and unintended consequences early — while there is still room to intervene.

---

## Status

This section is built incrementally.

Methods are added only where they clarify real system behaviour or expose failure modes that are otherwise easy to miss.
