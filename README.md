# Continuity Design

> An open framework, specification, and reference implementation for evaluating how digital products support continuity throughout the user's journey.

Continuity Design is an open project dedicated to improving how digital products are evaluated.

Rather than replacing existing approaches such as usability, UX, or Jobs-to-be-Done, Continuity Design complements them by introducing a longitudinal perspective centered on meaningful user progress.

The project provides:

- a conceptual framework for understanding continuity throughout the user's journey;
- a standardized review specification (CDRS);
- reference templates and examples;
- a foundation for future tools and AI-assisted evaluations.

Together, these components enable consistent, transparent, and actionable product evaluations that can be performed by individuals, teams, software applications, or AI systems.

---

# Why Continuity Design?

Traditional product evaluation methods focus on questions such as:

- Is the interface usable?
- Is the interaction clear?
- Can users complete their tasks efficiently?

These questions remain important.

Continuity Design addresses a complementary question:

> **How well does this product help users continue their own journey?**

Rather than evaluating isolated interactions, Continuity Design examines how products preserve context, support meaningful progress, expand future possibilities, and contribute to coherent user journeys over time.

---

# Project Architecture

The project is organized into four complementary layers.

```
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

Each layer has a distinct purpose.

- **Framework** defines the conceptual foundation.
- **Specification (CDRS)** defines the standardized review method.
- **Reference Assets** demonstrate how the framework and specification are applied.
- **Implementations** apply the framework through software, services, and other tools.

---

# Repository Structure

```
continuity-design/
│
├── framework/
│
├── specification/
│
├── examples/
│
├── templates/
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

The **Continuity Design Framework** defines the conceptual foundation of the project.

It introduces the principles, concepts, evaluation dimensions, and terminology used to understand how digital products participate in users' broader journeys.

The framework explains **what** Continuity Design is.

---

## Specification (CDRS)

The **Continuity Design Review Specification (CDRS)** defines a standardized method for applying the framework during product evaluation.

The specification defines:

- the review methodology;
- review modes;
- accepted evidence;
- confidence model;
- evaluation process;
- report structure;
- conformance requirements.

The specification is implementation-independent and may be used by individuals, teams, software applications, or AI systems.

The specification explains **how** the framework is applied.

---

## Reference Assets

Reference Assets provide practical guidance for applying the framework and the specification.

They include:

- reference review templates;
- reference product reviews;
- examples;
- implementation guidance.

These assets demonstrate one compliant way of applying the CDRS while remaining adaptable to different workflows.

---

## Implementations

Implementations apply the framework and the specification through software and services.

Future implementations may include:

- AI review assistants;
- web applications;
- command-line tools (CLI);
- IDE extensions;
- design tool plugins;
- documentation generators.

Implementations are intentionally separate from both the Framework and the CDRS.

---

# Repository Roadmap

## Current Release

- ✅ Continuity Design Framework
- ✅ Continuity Design Review Specification (CDRS)
- ✅ Reference Review Templates

## Next Milestones

- Reference Product Reviews
- Community Validation
- Additional Examples
- AI Review Assistant
- Developer Tooling

For the complete roadmap, see **ROADMAP.md**.

---

# Current Status

**Version:** 1.0.0

**Status:** Stable

---

# Contributing

Contributions are welcome.

Please read **CONTRIBUTING.md** before submitting issues, suggestions, or pull requests.

Implementation experience, case studies, independent reviews, and constructive discussions are particularly valuable for the continued evolution of the project.

---

# Author

Henrique Przibisczki de Oliveira

---

# License

This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

See the **LICENSE** file for details.
