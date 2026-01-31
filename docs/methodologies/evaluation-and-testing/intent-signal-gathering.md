# Intent Signal Gathering

## Purpose

This methodology documents how intent is gathered in recruiting,
grounded in the fundamentals defined in:

- [What Recruiting Is](../foundations/what-is-recruiting.md)
- [Intent](../foundations/intent.md)

It focuses on how experienced recruiters surface intent in practice,
and where systems can and cannot support that work.

---

## How intent is gathered in practice

Good recruiters rarely ask directly:
> “What is your intent score?”

Instead, intent emerges through soft, open-ended questions such as:
- What do you want to do next?
- What would make you leave your current role?
- What does “good” look like in your next job?
- What are you optimising for right now?

These questions are designed to surface **direction**, not commitment.

---

## The soft nature of intent

Early intent signals are often:
- tentative
- conditional
- exploratory

A candidate saying “I’m open to chatting” does not imply readiness to interview.

Misreading this early softness is a common source of funnel failure,
explored further in:
- [Funnel Change Over Time](funnel-change-over-time.md)

---

## Two classes of intent signals

This project distinguishes between two classes of intent-related signals.

### 1. Non-measurable signals (interpretive)

These signals:
- arise through conversation
- depend on tone, framing, and trust
- require human interpretation

Examples:
- conditional interest (“if X were true…”)
- hesitation about timing
- curiosity without commitment

These signals **must remain human-owned**.

Attempts to systematise them often lead to:
- false certainty
- loss of accountability

This boundary is enforced in:
- [Minimum Auditability](minimum-auditability.md)

---

### 2. Measurable behaviours (observable)

These are actions that can be observed without interpretation.

Examples:
- response or non-response
- response latency
- application completion or abandonment
- explicit declarations of availability

These behaviours can be recorded by systems,
but must not be treated as intent itself.

How these behaviours shift based on context is examined in:
- [Contextual Interaction Testing](contextual-interaction-testing.md)

---

## Common category errors

Recruiting systems frequently make the following mistakes:

- treating non-response as lack of intent
- treating fast response as high intent
- treating engagement as motivation

These errors are often caused by:
- collapsing interpretation into metrics
- removing recruiter judgment from the loop

Long-term effects of these errors appear in:
- [Simple Drift Detection](simple-drift-detection.md)

---

## A safe boundary for systems

This project proposes a simple boundary:

> Systems may record **what happened**.  
> Humans must interpret **what it means**.

Any system that claims to *know* intent has exceeded its scope.

Candidates correcting misinterpreted intent is addressed in:
- [Candidate Feedback Signals](candidate-feedback-signals.md)

---

## How to use this method

Use this methodology to:
- audit what intent signals your system records
- identify where interpretation is happening
- decide which assumptions need regular review

This method should be revisited whenever:
- hiring context changes
- response patterns shift
- funnels are redesigned
