---
layout: default
title: How to Use
---

# How to Use — EOB Clarity (Copy/Paste Workflow)

This is a **copy/paste workflow**: you paste **redacted** text from an EOB or medical bill into ChatGPT (or a Custom GPT) and get a plain-English summary + next-step checklist.

**This page does not process files or uploads.** It provides a safe prompt you can run in ChatGPT.

---

## Important safety rules (read this)
Do **NOT** paste personal or identifying information, including:
- name, address, phone, email
- member ID, claim ID, account number
- full date of birth
- portal screenshots
- barcodes / QR codes

✅ Use only **redacted** text snippets.

---

## Redaction checklist (copy this)
Before pasting, replace sensitive items with placeholders like `[NAME]`, `[ID]`, `[CONTACT]`.

- Patient name → `[NAME]`
- Member/claim/account IDs → `[ID]`
- Address/phone/email → `[CONTACT]`
- Provider tax ID/NPI (optional) → `[PROVIDER_ID]`
- Any portal links → remove

---

## Copy/Paste Prompt (use this in ChatGPT)

Paste the prompt below first, then paste your redacted snippet.

### PROMPT
You are an admin-clarity assistant. You do NOT provide medical advice.
Your job is to help me understand an EOB/bill in simple English and tell me what to verify next.

Follow this exact format:

1) What this document is (EOB vs bill vs statement vs collections)  
2) Plain-English summary (3–6 bullets)  
3) Key numbers (short list; include unknowns as “not shown”)  
4) What to do next (checklist)  
5) Questions to ask (script-ready)  
6) Red flags / missing info  
7) Glossary (only terms used)  
8) Confidence + what to verify  

Rules:
- If it is an EOB, clearly state: “An EOB is not a bill.”
- Do not tell me to pay immediately.
- If key info is missing (due date, payee, itemization), ask me to obtain it.
- Keep language simple.

Now analyze this redacted text:

[PASTE REDACTED TEXT HERE]

---

## Demo 1 (Synthetic) — EOB (not a bill)

### Input (synthetic)
Explanation of Benefits. Total charge $1,200. Allowed $520. Plan paid $400. Patient responsibility $120.  
Provider: ABC Imaging. Date of service: 01/10/2026.

### Output (example style)
1) **What this is:** EOB — **an EOB is not a bill**.  
2) **Summary:** Provider billed $1,200; plan allowed $520; plan paid $400; $120 may be billed to you later.  
3) **Key numbers:** charge $1,200; allowed $520; plan paid $400; patient responsibility $120; due date **not shown**.  
4) **Next steps:** wait for provider bill; match amount; request itemized bill if mismatch.  
5) **Questions:** “Is $120 deductible/coinsurance?” “Is any claim still pending?”  
6) **Red flags:** none obvious; verify against provider bill.  
7) **Glossary:** allowed amount, patient responsibility  
8) **Confidence:** medium; verify line items + billing.

---

## Demo 2 (Synthetic) — Provider bill (amount due + due date)

### Input (synthetic)
Statement: Amount due $245. Due date 03/01/2026.  
Service: Lab test. Insurance pending: Yes. If insurance pays, balance may change.

### Output (example style)
1) **What this is:** Provider bill/statement.  
2) **Summary:** You’re being billed $245, but insurance is still pending so the final amount may change.  
3) **Key numbers:** amount due $245; due date 03/01/2026; insurance status pending; itemization **not shown**.  
4) **Next steps:** confirm whether you must pay now or wait; ask for itemized bill; check if EOB is available.  
5) **Questions:** “Is this a preliminary bill?” “Will you rebill after insurance processes?”  
6) **Red flags:** billing while insurance pending; missing itemization.  
7) **Glossary:** statement, insurance pending  
8) **Confidence:** medium; verify insurer processing status.

---

## Demo 3 (Synthetic) — Collections notice (verify-first checklist)

### Input (synthetic)
Collections notice: Balance $610. “Pay immediately to avoid credit reporting.”  
Original creditor: XYZ Medical Group. Date of service: not listed. Itemization: not listed.

### Output (example style)
1) **What this is:** Collections notice.  
2) **Summary:** They claim you owe $610, but key details are missing (date of service, itemization).  
3) **Key numbers:** claimed balance $610; creditor XYZ Medical Group; due date **not shown**; itemization **not shown**.  
4) **Next steps:** request written validation + itemized bill; confirm it matches your records; do not pay until verified.  
5) **Questions:** “Provide validation details: date of service, CPT/line items, payments applied.”  
6) **Red flags:** urgency language; missing itemization/date of service.  
7) **Glossary:** collections notice, validation  
8) **Confidence:** medium; verify legitimacy before any payment.

---

## Want me to review your scenario publicly?
Use the **Clinic** (synthetic only):  
[Clinic page](../community/clinic.html)

_Last updated: Feb 7, 2026_
