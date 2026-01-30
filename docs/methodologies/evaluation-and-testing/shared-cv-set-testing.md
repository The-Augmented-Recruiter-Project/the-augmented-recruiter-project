# Shared Candidate × Role Set Testing  
*(Controlled input testing for matching, search, and screening systems)*

Shared candidate × role set testing is a method for evaluating how AI-assisted recruiting systems behave when given the **same fixed set of candidate profiles and role definitions**.

The method is used to test:
- candidate–role matching and ranking
- search and retrieval behaviour
- screening and shortlisting logic
- ATS and internal talent surfacing features

It focuses on **consistency, sensitivity, and boundary behaviour**, not predictive accuracy, fairness scoring, or vendor comparison.

---

## What is included in a test set

A shared test set consists of two controlled inputs:

### Candidate profiles
A small, fixed collection of CVs representing:
- typical external candidates
- internal or known candidates
- out-of-date or stale profiles
- boundary and edge cases

Profiles are chosen to reflect common hiring buckets (e.g. engineering, sales, creative, service), not to represent a labour market.

---

### Role definitions
One or more fixed role artefacts, such as:
- public-facing job ads
- internal job specifications
- variant descriptions of the same role

Using the same candidate set against different role definitions helps surface sensitivity to wording, structure, and emphasis.
