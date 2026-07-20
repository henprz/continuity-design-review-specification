---
title: Continuity Design Review Philosophy
short_name: Review Philosophy
version: 1.0.0
status: Stable
framework: Continuity Design
---

# Continuity Design Review Philosophy

> A Continuity Design Review does not evaluate whether a product is good. It evaluates how a product participates in the continuity of a user's journey.

---

# Purpose

This document describes the mindset that guides every Continuity Design Review.

While the Framework defines the theory and the CDRS defines the review process, this document explains how a reviewer should think while interpreting evidence and producing conclusions.

It is intentionally philosophical rather than procedural.

---

# The Central Question

Every review begins with a single question.

> **What journey does the product believe the user is living?**

Everything else derives from this question.

Products never interact with abstract users.

They always act according to a model—explicit or implicit—of who the user is, what they are trying to accomplish, and what they should do next.

The review evaluates this model.

---

# The Object of Evaluation

Traditional product reviews evaluate features, interfaces, algorithms, or interactions.

Continuity Design evaluates something different.

It evaluates the hypotheses a product constructs about the user's context and how those hypotheses influence the user's journey over time.

The object of the review is not the interface.

The object of the review is the product's interpretation of the user's journey.

---

# Products Participate in Journeys

Products do not merely respond to user actions.

Every interaction influences what the user is likely to do next.

Recommendations, defaults, search results, navigation, onboarding, notifications, and ranking systems all participate in shaping the journey.

A review therefore asks:

- Which future actions does this interaction encourage?
- Which actions become less likely?
- Which possibilities disappear?
- Which possibilities emerge?

---

# Evaluate Hypotheses, Not Solutions

Avoid evaluating implementation choices directly.

Instead of asking:

> Is this ranking algorithm effective?

Ask:

> What hypothesis about the user's context does this ranking express?

Instead of evaluating solutions, evaluate the assumptions that motivate those solutions.

---

# Continuity Before Correctness

A review is not primarily concerned with whether a decision is correct.

It asks whether the decision helps the user continue making meaningful progress.

Products sometimes produce imperfect results while still preserving continuity.

Conversely, technically correct solutions may interrupt the broader journey.

Continuity therefore takes precedence over isolated interaction quality.

---

# Every Feature Is an Intervention

Features are not passive capabilities.

Every feature intervenes in the user's journey.

Autocomplete influences intent before search.

Recommendations influence exploration before comparison.

Navigation influences which futures remain visible.

Reviews should describe features as interventions rather than static components.

---

# Possibility Space Is the Primary Lens

Every interaction changes the user's possibility space.

A review should continually ask:

- What futures become easier?
- What futures become harder?
- Which opportunities disappear?
- Which opportunities emerge?

Possibility Space should be treated as a consequence of design decisions rather than as an independent feature.

---

# Separate Observation from Interpretation

Every conclusion should distinguish between:

- Evidence
- Context Hypothesis
- Journey Impact
- Continuity Impact

Evidence is observed.

Everything else is interpretation.

The review should always make that reasoning explicit.

---

# Recommendations Operate at the Framework Level

Recommendations should strengthen the product's understanding of the user's journey rather than prescribe implementation details.

Avoid:

"Improve the ranking algorithm."

Prefer:

"Strengthen the product's context hypothesis by incorporating signals that better reflect the user's evolving intent."

The review explains what should improve.

Implementation explains how.

---

# The Final Question

Before concluding any review, ask:

> If this product behaved exactly as observed for the next six months, how would it influence the user's broader journey?

The answer to that question is the true outcome of a Continuity Design Review.