# Release Governance

## Purpose

This document defines the governance process for ExploreMore AI Knowledge Graph releases.

The objective is to ensure:

- Data quality
- Traceability
- Version control
- Auditability
- Public credibility

---

# Dataset Versioning

Dataset releases follow semantic version progression.

Examples:

- V1
- V2
- V3

Each release must include:

- Release date
- Validation summary
- Dataset statistics
- Remediation history

---

# Change Approval Process

PMO
↓
DIVC
↓
DFCO
↓
Release

### Responsibilities

PMO

- Approves investigations
- Approves releases

DIVC

- Evidence collection
- Validation
- Investigation

DFCO

- Remediation
- Dataset correction
- Integrity verification

Release

- Approved publication

---

# Relationship Retirement Process

Relationships may be retired when:

- Evidence becomes invalid
- Geographic validation fails
- Referential integrity fails
- Semantic validation fails

Retired relationships:

- Must not be deleted
- Must remain in audit history
- Must be documented in release notes

Example:

REL-0019

Status:

Retired following geographic validation review.

---

# Data Quality Investigation Workflow

PMO
↓
DIVC Investigation
↓
DFCO Remediation
↓
Release Approval

All investigations must maintain:

- Evidence traceability
- Validation records
- Remediation history

---

# Release Requirements

A release must satisfy:

- Referential Integrity Pass
- Semantic Validation Pass
- Circuit Integrity Pass

Open critical issues:

0

---

# Audit Principles

All releases must provide:

- Source traceability
- Validation documentation
- Change history
- Retirement history

The objective is transparent and reproducible tourism intelligence data governance.

---

Status:

Approved for TKG v1.0 Release Preparation
