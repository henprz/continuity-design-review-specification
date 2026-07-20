# Continuity Design Glossary

This glossary defines the principal concepts used throughout the Continuity Design Framework and the Continuity Design Review Specification (CDRS).

The glossary establishes a common vocabulary intended to promote consistency across documentation, reviews, discussions, and implementations.

Unless otherwise specified, the definitions in this document are conceptual rather than normative.

---

# Core Concepts

## Continuity

The degree to which a product helps users continue their broader journey over time.

Continuity emerges when interactions preserve relevant context, support meaningful progress, and shape valuable future possibilities.

It is an emergent property of the user's experience rather than a characteristic of any individual interaction.

---

## User Journey

The sequence of experiences through which a user pursues meaningful goals over time.

The journey extends beyond individual product sessions and belongs to the user rather than the product.

Products participate in journeys but do not own them.

---

## Context

The circumstances surrounding the user's current situation.

Context includes intentions, previous decisions, constraints, preferences, expectations, environment, and other factors that influence the meaning of an interaction.

Context belongs to the user rather than the product.

---

## Context Hypothesis

A product's current interpretation of the user's context.

Because products never possess complete knowledge of the user's true situation, they continuously construct and refine hypotheses about user context using available evidence.

These hypotheses guide product behavior but remain subject to revision as additional information becomes available.

---

## Meaningful Progress

Progress perceived by the user as bringing them closer to goals that matter from the user's perspective.

Meaningful progress is determined by the user's broader objectives rather than by the successful completion of individual product tasks.

---

## Possibility Space

The realistic set of future actions, decisions, and opportunities available to the user after an interaction.

Products influence the possibility space through interfaces, recommendations, workflows, and other design decisions that expand, preserve, constrain, or redirect future opportunities.

---

# Interaction Concepts

## Interaction

A single exchange between a user and a product.

Interactions are individual moments within a broader user journey and should not be evaluated in isolation from their surrounding context.

---

## Decision

A choice made by either the user or the product that influences subsequent interactions.

Design decisions affect the user's possibility space by determining which future paths become more or less accessible.

---

## Continuity Gap

A disruption that interrupts meaningful progress throughout the user's journey.

Continuity gaps often arise when products fail to preserve relevant context, recognize previous progress, or support coherent future actions.

---

# Framework Concepts

## Continuity Design

The conceptual framework for understanding how digital products contribute to the continuity of a user's journey.

The framework defines the theoretical foundations, design principles, evaluation dimensions, and terminology used throughout the project.

---

## Theoretical Foundations

The three fundamental propositions upon which Continuity Design is built:

1. Every interaction has context.
2. Context belongs to the user.
3. Products define a possibility space.

These foundations explain why continuity emerges and provide the conceptual basis for the framework.

---

## Design Principles

The design philosophy that emerges from the theoretical foundations.

The principles describe how products should contribute to a user's broader journey and provide conceptual guidance independent of any specific implementation.

---

## Evaluation Dimensions

The four complementary perspectives through which products are evaluated within the framework:

- Context
- JTBD & Narrative
- Possibility Space
- Continuity

The dimensions operationalize the framework for product evaluation.

---

## Continuity Design Review Specification (CDRS)

The standardized method for applying the Continuity Design Framework during product evaluation.

The CDRS defines the review process, evidence model, confidence model, report structure, and conformance requirements while remaining independent of any specific implementation.

---

# Relationship Between the Concepts

The concepts form a coherent conceptual hierarchy.

```text
User Journey
        ↓
Context
        ↓
Context Hypotheses
        ↓
Meaningful Progress
        ↓
Possibility Space
        ↓
Continuity
```

Products never directly observe the user's journey or true context.

Instead, they continuously construct and refine context hypotheses, support meaningful progress, shape future possibilities, and ultimately contribute to continuity over time.

---

# Relationship to the Framework

The glossary provides the common vocabulary shared by the Continuity Design Framework and the Continuity Design Review Specification (CDRS).

The framework uses these concepts to explain the theory.

The CDRS uses the same concepts to define a standardized review methodology.