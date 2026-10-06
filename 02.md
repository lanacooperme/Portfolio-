# AI Customer-support response quality framework.

**A consistent approach to evaluating AI-drafted replies for customer-facing use.**



## Overview

A small B2B SaaS support team used an AI assistant to draft customer replies but had no shared standard for determining whether a response was ready for customer-facing use. Reviewers relied on personal judgment, so the same draft could pass with one person and fail with another.

**Focus:** A weighted 1–5 rubric, a shared error taxonomy, and clear escalation rules, designed to be simple enough for a small team to use every day.

**Approach:** Quality dimensions → weighted rubric → error taxonomy with severity levels → review workflow and escalation rules. 
I weighted "Accuracy" highest and made any critical factual or safety error cap the overall score, so a polished but incorrect reply could not pass.

## Documentation Deliverables

| Deliverable | What it gave the team |
|---|---|
| **Evaluation rubric** | Five weighted criteria for judging a draft before it reaches a customer |
| **Scoring guidance** | One scale applied consistently by every reviewer |
| **Error taxonomy** | A shared name and severity level for each type of failure |
| **Acceptable / unacceptable examples** | Side-by-side reference cases for reviewer calibration |
| **Review workflow and escalation rules** | A clear point for human review and a route for risky answers |
| **Review-log template** | A record of scores to identify recurring problems |

**Evaluation Rubric.**

| Dimension | Weight | 5 — Excellent | 3 — Acceptable | 1 — Unacceptable |
|---|---:|---|---|---|
| **Accuracy** | 30% | Fully correct, no omissions | Mostly correct, one non-critical gap | Incorrect or misleading |
| **Clarity and tone** | 25% | Clear, concise, on-brand voice | Understandable, slight tone mismatch | Unclear or inappropriate |
| **Completeness** | 20% | Addresses every part of the customer's question | Answers the core question, misses a minor part | Does not address the question |
| **Helpfulness** | 15% | Gives a clear next step or resolution path | Useful, but the customer must work out the next step | No usable guidance |
| **Safety and compliance** | 10% | Fully compliant | Minor note needed | Clear policy or legal risk |

*Scores of 4 and 2 sit between the anchors.*

Pass rules: a response passes only when **all three conditions** are met:

1. Overall weighted score is **3.5 or higher**.
2. **Accuracy** and **Safety and compliance** each score 3 or higher.
3. No dimension scores **1**.

Critical error rule: any critical error **caps the overall score at 2.0**, regardless of the other scores.
A critical error is a factual or safety issue that could lead a customer to harmful action, such as:
- Incorrect instructions that could cause data loss
- A security or legal issue
- An invented product feature or commitment

*This rule prevents a response from passing simply because it is otherwise clear, complete, and well written.*

## Outcome

The team had a documented standard for reviewing AI-generated drafts, with defined escalation rules and a review log for tracking recurring error types.
