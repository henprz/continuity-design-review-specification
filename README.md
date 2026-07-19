# Continuity Design Review Specification (CDRS)

> A practical method for applying the Continuity Design framework to digital product evaluation.

The **Continuity Design Review Specification (CDRS)** defines a structured method for evaluating digital products through the lens of **Continuity Design**.

Rather than focusing exclusively on usability, visual quality, or task completion, CDRS investigates how a product participates in the user's trajectory by understanding context, supporting meaningful progress, and expanding relevant future possibilities.

The specification is designed to produce consistent, actionable, and self-contained product reviews that can be performed by humans or AI systems.

---

## Why CDRS?

Most product evaluation methods answer questions such as:

- Is the interface usable?
- Is the interaction clear?
- Can users complete their tasks efficiently?

These questions remain important.

CDRS addresses a different question:

> **How well does this product help users continue their own journey?**

To answer it, the specification applies the principles of the Continuity Design framework through a repeatable review process.

---

## Design Goals

CDRS was designed to:

- provide a repeatable review methodology;
- produce actionable recommendations for product teams;
- support both rapid and guided evaluations;
- accept multiple sources of evidence;
- generate self-contained reports suitable for stakeholders;
- remain independent from specific industries or technologies.

---

## Review Modes

### Quick Review

Designed for rapid evaluations.

The reviewer provides available evidence, such as:

- URL
- Screenshot
- Wireframe
- Prototype
- Product description

The reviewer (human or AI) infers the remaining information and reports the confidence level of each inference.

---

### Guided Review

Designed for more comprehensive evaluations.

The reviewer may ask additional questions regarding:

- target users;
- product goals;
- business context;
- available research;
- JTBD;
- supporting documentation.

The review expands only when additional context is required.

---

## Evaluation Dimensions

CDRS evaluates products across four dimensions.

| Dimension | Description |
|-----------|-------------|
| Context | How well the product understands and applies user context. |
| JTBD & Narrative | How well the product supports the user's intended progress and long-term story. |
| Possibility Space | How effectively the product creates meaningful future possibilities. |
| Continuity | How well interactions connect across the user's overall journey. |

Each dimension is evaluated qualitatively using three maturity levels:

- Low
- Medium
- High

---

## Inputs

CDRS accepts multiple forms of evidence.

Examples include:

- Product URLs
- Screenshots
- User flows
- Wireframes
- Design mockups
- Product Requirement Documents (PRDs)
- Design specifications
- Research reports
- User interviews
- Product strategy documents

Additional context generally improves the quality and confidence of the review.

---

## Output

Every CDRS review produces a self-contained report containing:

- Executive Summary
- Product Understanding
- Findings
- Evaluation
- Recommendations
- Confidence Assessment

The report is intended to be understandable without prior knowledge of the Continuity Design framework.

---

## Relationship to Continuity Design

CDRS is an application method built upon the **Continuity Design** framework.

This repository does **not** explain the framework itself.

For the theoretical foundation, see the original article (Portuguese):

**Design de Continuidade**

https://medium.com/@henrique.prz/design-de-continuidade-8a890183d386

---

## Repository Structure

```
.
├── README.md
├── CDRS.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── VERSION
├── examples/
├── templates/
├── assets/
└── docs/
```

The official specification is available in **CDRS.md**.

---

## Current Status

Version **1.0.0**

Status: **Stable**

The specification is expected to evolve through future versions while maintaining backward compatibility whenever practical.

---

## Author

Henrique Oliveira

---

## License

This work is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

See the LICENSE file for details.