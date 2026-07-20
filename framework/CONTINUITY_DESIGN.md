# Continuity Design

---

## Abstract

Continuity Design is a conceptual framework for understanding how digital products contribute to the continuity of a user's journey.

Traditional product evaluation methods primarily assess the quality of individual interactions. Continuity Design introduces a complementary perspective by examining how products participate in a broader user journey over time.

Rather than asking only whether users successfully complete individual tasks, the framework asks a different question:

> **How does this product help users continue their journey?**

This perspective shifts the object of evaluation from isolated interactions to the continuity of the user's broader trajectory.

The framework is implementation-independent and serves as the conceptual foundation for the Continuity Design Review Specification (CDRS).

---

# 1. Introduction

Digital products are commonly evaluated through perspectives such as usability, accessibility, interaction quality, visual design, performance, and task completion.

These disciplines have significantly improved the quality of digital experiences by helping designers optimize individual interactions.

Users, however, rarely experience products as isolated interactions.

Every interaction is embedded within an ongoing personal, professional, or organizational journey that extends both before and after the product is used.

A search is influenced by previous decisions.

A purchase often represents progress toward a broader objective.

A recommendation may influence decisions long after the current session ends.

Products therefore participate in journeys rather than isolated moments.

Continuity Design proposes that this participation should itself become an object of design and evaluation.

---

# 2. The Problem

Most existing product evaluation methods focus on the quality of individual interactions.

Typical questions include:

- Can the user complete the task?
- Is the interface understandable?
- Is the interaction efficient?
- Are errors minimized?

These questions remain essential.

However, they primarily evaluate the quality of a single interaction.

They do not necessarily explain whether the interaction contributes to the user's broader objectives.

A product may provide an excellent interaction while creating little lasting value beyond that moment.

Conversely, a seemingly simple interaction may significantly influence future decisions, opportunities, or behaviors.

This suggests that product quality cannot be understood solely by examining individual interactions.

It must also consider how those interactions connect throughout the user's broader journey.

---

# 3. A Change in Perspective

Continuity Design proposes a different perspective.

Instead of treating digital products as systems that respond to isolated interactions, it views them as participants in an evolving user journey.

This changes the primary question of product evaluation.

Instead of asking:

> **Was this interaction successful?**

Continuity Design asks:

> **How does this interaction contribute to the user's ongoing journey?**

The objective is no longer limited to optimizing the current interaction.

It also includes supporting meaningful progress over time.

This perspective does not replace existing disciplines such as usability, UX, or Jobs-to-be-Done.

Instead, it complements them by introducing a longitudinal view of product experience.

---

# 4. Theoretical Foundations

The framework is built upon three theoretical foundations.

Together, they explain why continuity emerges and how products influence user journeys.

---

## 4.1 Every Interaction Has Context

No interaction occurs in isolation.

Every action already belongs to a broader context created by previous decisions, intentions, constraints, experiences, and future expectations.

Context is more than historical information.

It is the interpretation that gives meaning to an interaction by connecting it to what came before and what may come next.

Designing interactions without considering context means evaluating only fragments of the user experience.

---

## 4.2 Context Belongs to the User

The product participates in the user's journey but does not own it.

Goals, motivations, intentions, and personal transformations belong to the user.

The product never possesses the user's true context.

Instead, it continuously constructs and refines hypotheses about that context using available evidence.

These hypotheses guide decisions but always remain incomplete representations of the user's actual situation.

Recognizing this distinction encourages products to adapt continuously rather than assume complete understanding.

---

## 4.3 Products Define a Possibility Space

Every design decision influences what users can realistically do next.

Interfaces, recommendations, workflows, and available actions define a possibility space that expands, constrains, or redirects future opportunities.

Products do not determine the user's journey.

They influence the set of possibilities through which that journey continues.

Consequently, product design is not limited to responding to the present interaction.

It also shapes the opportunities available after that interaction.

---

# 5. Fundamental Concepts

The theoretical foundations give rise to five fundamental concepts used throughout the framework.

## User Journey

A sequence of experiences extending beyond individual product sessions.

The journey belongs to the user rather than the product.

---

## Context

The circumstances surrounding the user's current situation, including intentions, constraints, previous decisions, and expectations.

Products reason about context through hypotheses rather than direct knowledge.

---

## Meaningful Progress

Progress perceived by the user as moving closer to goals that matter from the user's perspective.

Meaningful progress may extend far beyond completing a single task.

---

## Possibility Space

The realistic set of future actions, decisions, and opportunities available after an interaction.

Products influence this space through their design decisions.

---

## Continuity

The degree to which interactions connect coherently across time while supporting meaningful progress throughout the user's journey.

Continuity emerges from the interaction between context, progress, and possibility rather than from any single interaction.

---

# 6. Design Philosophy

The theoretical foundations naturally imply several design principles.

## Products Participate in Journeys

Products contribute to broader user journeys rather than isolated interactions.

---

## Context Creates Meaning

The value of an interaction depends on the user's context rather than on the interaction alone.

---

## Progress Is Meaningful

Interactions should contribute to goals that matter from the user's perspective.

---

## Possibilities Shape Future Progress

Design decisions influence future opportunities by defining the user's possibility space.

---

## Continuity Emerges Over Time

Continuity is not an individual interaction property.

It emerges as interactions accumulate into coherent journeys.

---

# 7. Evaluation Dimensions

The framework organizes product evaluation into four complementary dimensions.

These dimensions operationalize the theoretical foundations.

## Context

How effectively the product understands, preserves, and applies hypotheses about the user's context.

---

## JTBD & Narrative

How effectively the product supports meaningful progress within the user's broader journey.

---

## Possibility Space

How effectively the product expands, preserves, or guides meaningful future opportunities.

---

## Continuity

How coherently interactions connect over time while supporting the user's ongoing journey.

Together, these dimensions provide a holistic perspective on how products contribute to user continuity.

---

# 8. Relationship to Existing Disciplines

Continuity Design complements rather than replaces existing product disciplines.

| Discipline | Primary Focus |
|------------|---------------|
| Usability | Ease of interaction |
| UX Design | User experience |
| Interaction Design | Interaction quality |
| Accessibility | Inclusive interaction |
| Jobs-to-be-Done | User motivation |
| Service Design | Cross-channel experience |
| Continuity Design | Continuity of the user's journey |

Existing disciplines primarily optimize interactions.

Continuity Design evaluates how those interactions connect throughout a broader journey.

---

# 9. Applying the Framework

The framework is intentionally independent of any particular evaluation methodology or implementation.

It may be applied through interviews, design critiques, heuristic evaluations, workshops, AI-assisted analyses, or other assessment methods.

The standardized application of the framework is defined by the **Continuity Design Review Specification (CDRS)**.

The framework defines **what should be understood and evaluated**.

The CDRS defines **how a consistent evaluation is performed**.

---

# 10. References

## Primary Reference

Henrique Przibisczki de Oliveira.

*Design de Continuidade* (Portuguese) - https://medium.com/@henrique.prz/design-de-continuidade-8a890183d386

## Related Work

- Clayton Christensen et al. — *Competing Against Luck*
- Alan Klement — *When Coffee and Kale Compete*
- Continuity Design Review Specification (CDRS)