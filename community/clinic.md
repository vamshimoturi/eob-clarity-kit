---
layout: default
title: Clinic
permalink: /clinic/
---

# Clinic — How submissions are reviewed

This is a simple, privacy-first process for accepting “cases” into the public example library.

## What you can submit

- **Synthetic examples only** (no real patient data)
- Scenarios like:
  - EOB vs bill confusion
  - patient responsibility mismatch
  - duplicate charge suspicion
  - missing due date / unclear payee
  - collections notice verification steps

## What you must NOT submit

Do not include:
- names, addresses, phone/email
- member ID / claim ID / account numbers
- DOB
- portal screenshots
- barcodes / QR codes
- any real-world identifying details

## Review checklist (what I check)

1. **No PHI** (privacy check)
2. **Clarity** (can a non-expert understand it?)
3. **Correct framing** (EOB ≠ bill; no medical advice)
4. **Actionability** (has a useful next-step checklist)
5. **Safety** (encourages verification before payment)

## Outcome

- If approved, it becomes a new **synthetic case** under `/examples/`
- If not approved, it will be rejected with a reason (usually privacy or unclear details)

## Why this exists

To build a public, reusable library that helps people learn patterns — without exposing private data.
