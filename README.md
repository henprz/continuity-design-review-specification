# Continuity Design

> An open framework, specification, and reference implementation for evaluating how digital products support continuity throughout the user's journey.

Continuity Design is an open project dedicated to improving how digital products are evaluated.

Rather than replacing existing approaches such as usability, UX, or Jobs-to-be-Done, Continuity Design complements them by introducing a longitudinal perspective centered on meaningful user progress.

The project provides:

- a conceptual framework for understanding continuity throughout the user's journey;
- a standardized review specification (CDRS);
- reference assets for applying the framework consistently;
- a foundation for software tools and AI-assisted evaluations.

Together, these components enable consistent, transparent, and actionable product evaluations that can be performed by individuals, teams, software applications, or AI systems.

---

# Repository Philosophy

This repository is intentionally modular.

Rather than concentrating all knowledge in a few large documents, each document answers one specific question. This makes the project easier to understand, maintain, and implement while providing clear sources of truth for both human readers and AI systems.

| Question | Document |
|----------|----------|
| What is Continuity Design? | `framework/CONTINUITY_DESIGN.md` |
| Which principles define the framework? | `framework/PRINCIPLES.md` |
| Which dimensions are evaluated? | `framework/DIMENSIONS.md` |
| What do the framework's terms mean? | `framework/GLOSSARY.md` |
| How should a Continuity Design reviewer think? | `framework/REVIEW_PHILOSOPHY.md` |
| How should Continuity Design observations be written? | `templates/reviews/review-patterns.md` |
| How is a Continuity Design review performed? | `specification/CDRS.md` |
| How is the final review report structured? | `templates/reports/report.md` |
| When should a Quick Review be used? | `templates/reviews/quick-review.md` |
| When should a Guided Review be used? | `templates/reviews/guided-review.md` |
| When should a Comprehensive Review be used? | `templates/reviews/comprehensive-review.md` |

Each document owns a single responsibility.

This separation minimizes overlap, simplifies maintenance, and allows implementations to compose the framework consistently.

---

# Why Continuity Design?

Traditional product evaluation methods focus on questions such as:

- Is the interface usable?
- Is the interaction understandable?
- Can users complete their tasks efficiently?

These questions remain important.

Continuity Design introduces a complementary question:

> **How well does this product help users continue their own journey?**

Rather than evaluating isolated interactions, Continuity Design examines how products understand context, preserve continuity, expand future possibilities, and support meaningful progress throughout the user's broader journey.

---

# Project Architecture

The project is organized into four complementary layers.

```text
Continuity Design
        ↓
Framework
        ↓
Specification (CDRS)
        ↓
Reference Assets
        ↓
Implementations
```

Each layer has a distinct responsibility.

| Layer | Responsibility |
|------|----------------|
| Framework | Defines the conceptual foundation. |
| Specification (CDRS) | Defines the standardized review process. |
| Reference Assets | Demonstrate how the framework is applied. |
| Implementations | Apply the framework through software and services. |

---

# Repository Structure

```text
continuity-design/
│
├── framework/
│   ├── CONTINUITY_DESIGN.md
│   ├── PRINCIPLES.md
│   ├── DIMENSIONS.md
│   ├── GLOSSARY.md
│   └── REVIEW_PHILOSOPHY.md
│
├── specification/
│   └── CDRS.md
│
├── templates/
│   ├── reports/
│   │   └── report.md
│   │
│   └── reviews/
│       ├── quick-review.md
│       ├── guided-review.md
│       ├── comprehensive-review.md
│       └── review-patterns.md
│
├── docs/
│
├── README.md
├── ROADMAP.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── LICENSE
└── VERSION
```

---

# Components

## Framework

The Framework defines the conceptual language of Continuity Design.

It introduces the principles, concepts, evaluation dimensions, and terminology required to understand how digital products participate in users' broader journeys.

The Framework explains **what Continuity Design is**.

---

## Specification (CDRS)

The Continuity Design Review Specification (CDRS) defines the standardized review methodology.

It specifies:

- review modes;
- evidence model;
- confidence model;
- evaluation workflow;
- report requirements;
- conformance expectations.

The CDRS explains **how the framework is applied**.

---

## Reference Assets

Reference Assets provide practical guidance for applying the Framework and the CDRS.

They include:

- report templates;
- review patterns;
- review mode definitions;
- future reference reviews.

These assets illustrate one compliant implementation while remaining adaptable to different workflows.

---

## Implementations

Implementations apply the Framework and the CDRS through software and services.

Examples include:

- AI Review Assistants;
- Web Applications;
- IDE Extensions;
- Documentation generators;
- Developer tooling.

Implementations are intentionally independent from both the Framework and the Specification.

---

# Current Status

**Version:** 1.0.0

**Status:** Stable

---

# Roadmap

Current release includes:

- ✅ Continuity Design Framework
- ✅ Continuity Design Review Specification (CDRS)
- ✅ Reference Assets

Future milestones include:

- Reference Product Reviews
- Community Validation
- AI-assisted Tooling
- Additional Implementations

For the complete roadmap, see **ROADMAP.md**.

---

# Contributing

Contributions are welcome.

Please read **CONTRIBUTING.md** before submitting issues, suggestions, or pull requests.

Implementation experience, independent reviews, case studies, and constructive discussions are especially valuable for the continued evolution of the project.

---

# Author

Henrique Przibisczki de Oliveira

---

# License

This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

See the **LICENSE** file for details.