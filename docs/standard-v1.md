---
layout: default
title: Standard v1
---

# EOB Clarity Standard v1.0

## Guardrails (non-negotiable)
- If document is an **EOB**, always state: **“An EOB is not a bill.”**
- No medical advice. No diagnosis interpretation.
- Never request SSN/full DOB/login credentials.
- Verification-first: do not instruct “pay now” without confirming it’s a provider bill and details match.

## Step 1 — Classify the document
- EOB
- Provider Bill
- Statement
- Collections Notice
- Other

## Step 2 — Extract required fields (even if unknown)
- Date(s) of service
- Provider/facility
- Total charge
- Allowed amount (if present)
- Plan paid (if present)
- Patient responsibility (if present)
- Amount due + due date (if a bill)
- Contact info present? (yes/no)

## Step 3 — Standard output format
1. What this document is (and isn’t)  
2. Plain-English summary (3–6 bullets)  
3. Key numbers  
4. What to do next (checklist)  
5. Questions to ask (script-ready)  
6. Red flags  
7. Glossary (only terms used)  
8. Confidence + what to verify
