Mining Calculator Project

Pantheon-Aligned Bitcoin Mining Economics Tool

1. Overview

This repository contains a Bitcoin mining economics calculator and supporting documentation designed to evaluate mining opportunities under transparent, conservative, and institutionally defensible assumptions.

The project is intended to support:

Investor diligence

Scenario analysis

Internal discussion

Client and investment committee conversations

This is a decision-support tool, not a predictive or promotional model.

2. Intended Audience

This project is built for:

Family offices

RIAs and investment committees

Sophisticated UHNW investors

Internal analysis and diligence workflows

The calculator assumes users are:

Capital-literate

Risk-aware

Comfortable evaluating scenario-based outcomes

3. How to Use This Project
Recommended Workflow

Read EXECUTIVE_SUMMARY.md to understand intent and framing

Review ASSUMPTIONS.md to understand modeling philosophy

Use the calculator to explore scenarios

Reference CUSTODY_OPTIONS.md and SALES_PLAYBOOK.md for investor context

Review CHANGELOG.md before relying on outputs

The calculator is most effective when used to understand sensitivity and downside, not to optimize for a single outcome.

4. Folder Structure
Mining Calculator Project/
├── calculator/            # Calculator HTML, JS, CSS files
├── docs/                  # Authoritative documentation
│   ├── README.md
│   ├── EXECUTIVE_SUMMARY.md
│   ├── ASSUMPTIONS.md
│   ├── SALES_PLAYBOOK.md
│   ├── CUSTODY_OPTIONS.md
│   └── CHANGELOG.md
├── brand/
│   ├── BRAND.md
│   └── PANTHEON_REFERENCE.md

5. File Authority Hierarchy (Important)

When interpreting or modifying this project, authority flows in this order:

ASSUMPTIONS.md — economic truth

PANTHEON_REFERENCE.md — brand and tone reference

BRAND.md — visual and UI rules

CHANGELOG.md — historical accountability

Calculator code — implementation

If calculator behavior conflicts with documented assumptions, the calculator is wrong.

6. Baseline & Version Discipline

One calculator file should be treated as the baseline / working version

Experimental versions should be clearly labeled

Baseline files should not be overwritten

Any change affecting outputs must be logged in CHANGELOG.md

Silent changes are explicitly discouraged.

7. Use of Codex / AI Assistance

Codex is used to:

Analyze calculator logic

Cross-reference assumptions

Improve clarity and UX

Identify inconsistencies or risk

Codex should:

Treat /docs and /brand as authoritative

Avoid modifying files unless explicitly instructed

Prompt for changelog entries when logic changes

8. Scope Limitations

This project intentionally does not model:

Taxes

Legal structure

Financing or leverage

Jurisdiction-specific regulation

Custody execution details

Outputs should be interpreted as pre-tax, scenario-based estimates only.

9. Guiding Principle

“If this model still looks reasonable under conservative assumptions and clear risk disclosure, it may merit deeper diligence.”

This project exists to surface risk, not obscure it.