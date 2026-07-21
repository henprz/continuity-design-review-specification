# Examples

This directory contains reference examples for the Continuity Design Framework.

Each example consists of:

- a recorded user journey (`.mov` / `.mp4`);
- the corresponding Continuity Design Review (`.md`).

The reviews were generated using the official Continuity Design GPT and follow the Continuity Design Review Specification (CDRS).

---

# Directory Structure

```
examples/
├── autocomplete-amazon.mov
├── example-autocomplete-amazon.md
│
├── search-mercadolivre.mp4
├── example-search-mercadolivre.md
│
├── pdp-enjoei.mov
├── example-pdp-enjoei.md
│
├── pdp-mercadolivre.mov
├── example-pdp-mercadolivre.md
│
├── pdp-petlove.mov
└── example-pdp-petlove.md
```

---

# Naming Convention

Journey recordings follow the pattern:

```
<journey>-<product>.<extension>
```

Examples:

```
autocomplete-amazon.mov
search-mercadolivre.mp4
pdp-petlove.mov
```

Generated reviews follow the pattern:

```
example-<journey>-<product>.md
```

Examples:

```
example-autocomplete-amazon.md
example-search-mercadolivre.md
example-pdp-enjoei.md
```

---

# Review Mode

All examples were generated as **Quick Reviews**.

Each review is based exclusively on a recorded user journey, without access to analytics, user research, business context, implementation details, or internal product documentation.

As a result, the reviews prioritize interpretation of observable behavior while explicitly documenting confidence and assumptions.

---

# Purpose

These examples demonstrate how the Continuity Design Framework interprets products rather than simply evaluating interface quality.

Each review illustrates:

- the broader journey the product appears to support;
- the product's apparent continuity approach;
- the Context Hypotheses inferred from observable behavior;
- the principal trade-offs introduced by that approach;
- recommendations that strengthen continuity without replacing the product's apparent strategy.

Different products should naturally produce different interpretations, even when they achieve similar levels of continuity.

---

# Reproducing the Examples

To reproduce these examples:

1. Open the official Continuity Design GPT.
2. Upload one of the recorded journeys.
3. Request a product review.
4. Accept the recommended **Quick Review** mode.

The generated report should follow the official Continuity Design Review Specification (CDRS).

---

# Notes

These examples are illustrative rather than normative.

They demonstrate how the framework reasons from observable evidence to produce an interpretation of the product's continuity philosophy.

As the Continuity Design Framework evolves, future versions may produce different interpretations while remaining consistent with the same underlying principles.
