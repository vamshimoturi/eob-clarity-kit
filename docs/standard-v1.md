---
layout: default
title: Standard v1
permalink: /standard/
---

# Standard v1 — EOB Clarity (Rubric)

This standard defines what the EOB Clarity Kit will and will not do.

## What this is

An **EOB (Explanation of Benefits)** is **not** a bill.

It is the insurer’s summary of how a claim was processed:
- what the provider billed
- what the plan allowed
- what the plan paid
- what the member may owe (often called “patient responsibility”)

## What this tool provides

### 1) Plain-English summary
- What happened in simple terms  
- What the key amounts mean (charge, allowed, paid, responsibility)

### 2) Key numbers (extracted)
- Total charge
- Allowed amount
- Plan paid
- Patient responsibility
- Date of service (if present)
- Provider name (if present)

### 3) Next-step checklist
Examples:
- Wait for provider bill (if you only have an EOB)
- Confirm bill matches patient responsibility
- Request itemized bill if mismatch
- Call insurer/provider with the right questions

### 4) Red-flag detection (best effort)
Examples:
- math mismatch between amounts
- duplicate charge patterns
- missing due date / unclear payee on a bill
- collections notice without verification steps

## Hard boundaries (very important)

### No medical advice
This tool does **not** interpret diagnoses, treatments, or medical necessity.

### No PHI / privacy-first
Do **not** paste:
- name, address, phone, email
- member ID, claim ID, account number
- full DOB
- portal screenshots
- barcodes / QR codes
Use placeholders like: `[NAME]`, `[ID]`, `[CONTACT]`.

### Not a payment decision engine
Never pay solely based on this output. Always verify with:
- provider billing office, and/or
- insurer customer service.

## Output format (recommended)

1) **Summary (2–4 bullets)**  
2) **Key numbers table**  
3) **What to do next (checklist)**  
4) **Questions to ask (call script)**  
5) **Red flags (if any)**

## Version

**v1.0** — Feb 7, 2026
