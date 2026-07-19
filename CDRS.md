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

### 6.1 Review

### 6.2 Reviewer

### 6.3 Evidence

### 6.4 Inference

### 6.5 Confidence

### 6.6 Recommendation

---

# Part II — Review Method

## 7. Review Modes

### 7.1 Quick Review

### 7.2 Guided Review

---

## 8. Accepted Inputs

### 8.1 User-Provided Evidence

### 8.2 Supporting Documentation

### 8.3 Additional Context

---

## 9. Confidence Model

### 9.1 Evidence vs Inference

### 9.2 Confidence Levels

### 9.3 Reporting Assumptions

---

## 10. Review Process

### 10.1 Product Understanding

### 10.2 Context Analysis

### 10.3 User Narrative

### 10.4 Possibility Space Analysis

### 10.5 Continuity Assessment

### 10.6 Findings

### 10.7 Recommendations

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

