# Minimum Auditability  
*(What a recruiter should be able to reconstruct later)*

This page describes a **minimal, recruiter-safe notion of auditability** for AI-assisted recruiting systems.

It does not describe legal audits, regulatory compliance, or technical traceability.

It exists to help answer a simple question:

> *“Could I reconstruct what happened here well enough to ask a meaningful question later?”*

---

## What auditability means here

In this project, auditability means:

> The ability to reconstruct **what was done, with which inputs, using which system, at roughly what time**, without guessing.

It does **not** require:
- access to model internals
- perfect logs
- formal documentation
- technical explanations

It is about **memory and accountability**, not proof.

---

## The minimum auditability self-check

After using an AI-assisted system in a hiring flow, ask yourself:

1. Could I say **which system or feature** was used?
2. Could I describe **what inputs** it saw?
   - role version?
   - candidate set?
3. Could I say **what output influenced me**?
   - ranking?
   - exclusion?
   - recommendation?
4. Could I say **when** this happened (roughly)?
5. Could I point to **where human judgment entered or overrode it**?

If most of these answers are “no”, then minimum auditability is missing — regardless of vendor claims.

---

## What counts as “enough” evidence

Minimum auditability can often be satisfied with:
- a screenshot
- a saved search or filter
- a copied ranking list
- a dated note or comment
- a shared document

Precision is not required.  
**Reconstructability is.**

---

## Why this matters

When questions arise later — from candidates, managers, or yourself — lack of auditability leads to:

> “We don’t know. The system did it.”

That is where responsibility quietly disappears.

Minimum auditability keeps decisions **anchored to humans**, even when systems assist.

---

## What this does *not* do

This approach:
- does not ensure fairness
- does not explain system behaviour
- does not guarantee compliance
- does not replace formal audits where required

It is a **baseline**, not a shield.

---

## Relationship to other methods

Minimum auditability supports:
- shared candidate × role set testing
- simple drift detection
- desk-side and coffee shop review
- later investigation when outcomes are questioned

Without it, those methods lose value over time.

---

## Contribution notes

Short examples of:
- where auditability failed
- what evidence was missing
- how teams adapted (or didn’t)

are in scope for contribution, provided they avoid blame or promotional framing.
