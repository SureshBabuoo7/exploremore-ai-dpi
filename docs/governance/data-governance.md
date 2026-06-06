# Data Governance Policy

## Purpose

This document defines governance standards for datasets used within the ExploreMore AI Tourism Knowledge Graph.

---

## Entity Governance

Entities must:

- Represent real tourism assets.
- Be traceable to a verifiable source.
- Include a unique Entity ID.
- Include category classification.
- Include verification status.

---

## Relationship Governance

Relationships must:

- Connect two valid entities.
- Include a relationship type.
- Include a confidence score.
- Be supported by evidence whenever possible.

---

## Verification Levels

### Verified

Confirmed through official or authoritative sources.

### Community Verified

Confirmed through multiple independent sources.

### Pending

Awaiting verification.

---

## Confidence Scoring

90–100:
Strong evidence.

70–89:
Probable relationship.

50–69:
Weak relationship.

Below 50:
Requires further review.

---

## Data Stewardship

Repository maintainers are responsible for:

- Dataset quality
- Duplicate prevention
- Version control
- Validation audits

---

## Review Cycle

Datasets should be reviewed before major releases and Knowledge Graph imports.
