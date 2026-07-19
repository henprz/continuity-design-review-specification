---
title: Continuity Design Review Specification
short_name: CDRS
version: 1.0.0
status: Stable
author: Henrique Oliveira
license: CC BY 4.0
language: English
framework: Continuity Design
---

# Continuity Design Review Specification (CDRS)

> A practical method for applying the Continuity Design framework to digital product evaluation.

---

# Abstract

The Continuity Design Review Specification (CDRS) defines a standardized method for evaluating digital products through the Continuity Design framework.

The specification establishes a repeatable, implementation-independent review process that produces consistent and actionable evaluations. It defines the review modes, accepted inputs, review process, evaluation dimensions, confidence model, and report structure required for a CDRS-compliant review.

CDRS is intended to be applicable by both human reviewers and artificial intelligence systems. It specifies **what** a compliant review MUST accomplish without prescribing **how** it MUST be implemented.

This specification is normative. The conceptual foundations of the Continuity Design framework are defined separately and are referenced where appropriate.

---

# Table of Contents

---

# Part I — Foundation

## 1. Introduction

---

## 2. Purpose

---

## 3. Design Goals

---

## 4. Scope

---

## 5. Out of Scope

---

## 6. Terminology

---

# Part II — Review Method

## 7. Review Method

## 8. Review Modes

## 9. Accepted Inputs

## 10. Confidence Model

---

# Part III — Review Output

## 11. Evaluation Dimensions

### 11.1 Dimension Structure

### 11.2 Qualitative Ratings

### 11.3 Overall Assessment

---

## 12. Report Structure

### 12.1 Executive Summary

### 12.2 Product Understanding

### 12.3 Findings

### 12.4 Evaluation

### 12.5 Recommendations

### 12.6 Confidence Assessment

### 12.7 Conclusion

---

# Part IV — Specification

## 13. Conformance

---

## 14. References

---

## 15. Versioning

---

## Appendix A — Recommended Review Workflow

---

## Appendix B — Future Extensions

---

# 1. Introduction

Digital products are commonly evaluated using methods that assess usability, interaction quality, accessibility, visual consistency, and task completion. These approaches provide valuable insights into how effectively users perform individual interactions within a product.

The Continuity Design framework introduces a complementary perspective by considering how products support users beyond isolated interactions. Rather than evaluating a single moment of use, it examines how products help users maintain progress throughout their broader journeys.

The Continuity Design Review Specification (CDRS) defines a standardized method for applying this perspective during product evaluation. It establishes a common review process, terminology, and reporting structure that enables consistent evaluations across different reviewers, organizations, and implementations.

CDRS is implementation-independent. It defines the expected behavior and outputs of a review without prescribing the internal processes, tools, or technologies used to perform it.

# 2. Purpose

The purpose of the Continuity Design Review Specification (CDRS) is to define a standardized method for evaluating digital products through the Continuity Design framework.

The specification establishes a common review methodology that enables reviewers to produce consistent, transparent, and actionable evaluations regardless of the implementation used.

CDRS defines:

- the review modes available for conducting an evaluation;
- the information required to perform a review;
- the review process;
- the evaluation dimensions;
- the confidence model;
- the structure of the resulting report.

This specification is intended to promote consistency across reviews rather than prescribe a single implementation. Any implementation that satisfies the normative requirements defined in this document MAY be considered CDRS-compliant.

# 3. Design Goals

The Continuity Design Review Specification (CDRS) is designed to achieve the following goals:

- **Repeatability**  
  Equivalent evidence SHOULD lead to equivalent review outcomes, regardless of the reviewer or implementation.

- **Consistency**  
  The specification SHOULD establish a common structure, terminology, and evaluation process across all compliant reviews.

- **Transparency**  
  Reviews MUST clearly distinguish between observed evidence, inferred conclusions, assumptions, and recommendations.

- **Actionability**  
  Reviews SHOULD produce recommendations that support meaningful improvements to the product.

- **Implementation Independence**  
  The specification MUST define expected behavior without prescribing implementation details, technologies, or internal algorithms.

- **Adaptability**  
  The review method SHOULD remain applicable across different industries, product domains, and levels of product maturity.

- **AI Compatibility**  
  The specification SHOULD be implementable by both human reviewers and artificial intelligence systems without requiring different review methodologies.

  # 4. Scope

This specification defines the normative requirements for conducting a Continuity Design Review (CDR).

Specifically, CDRS defines:

- the supported review modes;
- the accepted forms of review evidence;
- the review method;
- the evaluation dimensions;
- the confidence model;
- the structure of a compliant review report;
- the conformance requirements for CDRS implementations.

The specification defines **what** a compliant review MUST accomplish without prescribing **how** it MUST be implemented.

CDRS is applicable to the evaluation of digital products regardless of:

- industry;
- business model;
- platform;
- product maturity;
- implementation technology.

The specification MAY be implemented by individuals, teams, software applications, or artificial intelligence systems.

# 5. Out of Scope

The Continuity Design Review Specification (CDRS) does not define or prescribe:

- product strategy;
- product discovery methods;
- user research methodologies;
- usability testing procedures;
- UX heuristics;
- interface design principles;
- accessibility standards;
- visual design systems;
- software architecture;
- implementation technologies;
- software development processes;
- business metrics or success criteria.

CDRS is intended to complement these disciplines rather than replace them.

A CDR MAY reference findings produced by other evaluation methods when they provide relevant evidence. However, those methods remain outside the scope of this specification.

Similarly, this specification does not define the internal architecture of software systems or artificial intelligence systems that implement CDRS. Implementations are free to choose any architecture, algorithms, workflows, or technologies, provided they satisfy the normative requirements defined by this specification.

# 6. Terminology

This section defines the normative terminology used throughout this specification.

## Continuity Design

The theoretical framework upon which this specification is based.

The Continuity Design framework defines the conceptual principles for evaluating how digital products support users throughout their broader journeys. This specification defines a method for applying those principles during product evaluation.

---

## Continuity Design Review (CDR)

A product evaluation performed according to the Continuity Design Review Specification (CDRS).

A CDR consists of the review activities and the resulting report defined by this specification.

---

## Reviewer

The entity responsible for conducting a Continuity Design Review.

A Reviewer MAY be:

- an individual;
- a team;
- a software application; or
- an artificial intelligence system.

---

## Specification

This normative document.

The specification defines the requirements for conducting a Continuity Design Review without prescribing implementation details.

---

## Implementation

Any system, workflow, or process that performs Continuity Design Reviews according to this specification.

Different implementations MAY use different architectures, technologies, workflows, or algorithms provided they satisfy the normative requirements defined by CDRS.

---

## Evidence Source

Any artifact, observation, document, interface, or other source of information used during a review.

Examples include:

- product interfaces;
- screenshots;
- prototypes;
- wireframes;
- product documentation;
- user research;
- interviews;
- analytics.

---

## Evidence

Information directly obtained from one or more Evidence Sources.

Evidence represents observable facts rather than interpretations or conclusions.

---

## Inference

A conclusion derived from available Evidence.

An Inference extends beyond directly observable facts and SHOULD be supported by available Evidence whenever possible.

---

## Assumption

A temporary statement adopted when sufficient Evidence is unavailable.

Assumptions SHOULD be explicitly identified and SHOULD be minimized whenever additional Evidence can reasonably be obtained.

---

## Confidence

A qualitative assessment of how strongly an Inference or Assumption is supported by the available Evidence.

Confidence communicates the certainty of a conclusion rather than its importance.

---

## Recommendation

A proposed improvement intended to strengthen product continuity.

Recommendations SHOULD be actionable, evidence-based, and clearly traceable to the findings of the review.

---

## Compliant Review

A Continuity Design Review that satisfies all normative requirements defined by this specification.

# 7. Review Method

The Continuity Design Review Specification (CDRS) defines a structured method for evaluating digital products through the Continuity Design framework.

Every Continuity Design Review (CDR) MUST follow the review method defined by this specification.

The review method transforms available Evidence into a structured assessment of how effectively a product supports continuity throughout the user's broader journey. The method is designed to produce consistent, transparent, and actionable evaluations while remaining independent of any specific implementation.

A compliant CDR MUST perform the following review activities:

1. **Product Understanding**  
   Establish a shared understanding of the product, its purpose, intended users, and the available Evidence.

2. **Context Analysis**  
   Analyze the user's context and identify the conditions that influence decisions, interactions, and progress.

3. **User Narrative Analysis**  
   Evaluate how the product supports the user's broader narrative beyond individual tasks or isolated interactions.

4. **Possibility Space Analysis**  
   Examine how the product expands, constrains, or guides the meaningful possibilities available to the user.

5. **Continuity Assessment**  
   Assess how effectively the product preserves context, supports progress, and enables users to continue their journey over time.

The review method defines the required outcomes of a Continuity Design Review. It does not prescribe the internal techniques, workflows, or technologies used to perform each review activity.

Different implementations MAY use different processes, algorithms, or software architectures provided they satisfy the normative requirements defined by this specification.

The following sections define the supported review modes, accepted inputs, and confidence model used throughout the review process.

# 8. Review Modes

A Continuity Design Review (CDR) MAY be conducted using different review modes depending on the availability of Evidence.

The selected review mode determines the expected level of completeness and confidence of the review. Regardless of the selected mode, every compliant review MUST follow the review method defined in this specification.

This specification defines the following review modes.

## Quick Review

A Quick Review is intended for rapid evaluations based on limited Evidence.

Typical use cases include:

- early product concepts;
- initial design discussions;
- feature proposals;
- exploratory evaluations.

Quick Reviews SHOULD clearly identify assumptions and SHOULD communicate any limitations resulting from unavailable Evidence.

---

## Guided Review

A Guided Review is intended for structured evaluations supported by multiple Evidence Sources.

Typical use cases include:

- product assessments;
- design reviews;
- product iterations;
- release evaluations.

Guided Reviews SHOULD provide more comprehensive findings than Quick Reviews and SHOULD reduce the number of assumptions whenever additional Evidence is available.

---

## Comprehensive Review

A Comprehensive Review is intended for thorough evaluations supported by extensive Evidence from multiple sources.

Typical use cases include:

- strategic product assessments;
- major redesigns;
- organizational audits;
- certification or governance processes.

Comprehensive Reviews SHOULD maximize evidence-based findings and SHOULD minimize unsupported assumptions.

---

The review mode affects the amount of available Evidence and the expected confidence of the review. It does not modify the review method defined by this specification.

