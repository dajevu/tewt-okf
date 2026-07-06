---
type: reference
title: "Nexus Radar"
---

# Nexus Radar

## Overview

Nexus Radar is an MCP-delivered reference tool that provides citation-backed answers on U.S. state and local tax nexus, employer withholding obligations, reciprocal agreements between states, and convenience-of-the-employer sourcing rules. Responses include direct citations to statutes, regulations, department of revenue guidance, and case law so practitioners can verify every conclusion.

## Capabilities

- **State Tax Nexus** — Determines whether physical, economic, or statutory presence creates income, sales/use, or franchise tax nexus in a given jurisdiction.
- **Payroll Withholding** — Identifies withholding requirements for employees working across state lines, including remote-work and multi-state scenarios.
- **Reciprocity Agreements** — Reports which states maintain reciprocal withholding agreements and what they cover.
- **Convenience-of-the-Employer Rules** — Surveys states that apply convenience-of-the-employer sourcing to nonresident wages and explains how each state's rule operates.

## How It Works

Nexus Radar is invoked through the Model Context Protocol (MCP). When a practitioner submits a nexus or withholding question, the tool:

1. Parses the query for relevant jurisdictions, tax types, and fact patterns.
2. Retrieves the applicable statutory and regulatory provisions from its maintained knowledge base.
3. Returns a structured answer with inline citations to the controlling authority.

Every answer includes source citations. Where authority is ambiguous or absent, Nexus Radar flags the gap rather than fabricating a conclusion.

## Citation Standards

Responses cite primary authority whenever available, in the following order of preference:

| Priority | Source Type | Example |
|----------|-------------|---------|
| 1 | Statute | Conn. Gen. Stat. § 12-711(b) |
| 2 | Regulation | 830 CMR 63.38.1 |
| 3 | Department guidance | NYS TSB-M-06(5)I |
| 4 | Case law | *Zelinsky v. Tax Appeals Tribunal* |

Secondary sources such as department FAQs and practitioner alerts are cited only when no primary authority directly addresses the question, and they are labeled as non-binding.

## Typical Questions

- "Does an employee who lives in Pennsylvania and works remotely for a New Jersey employer trigger New Jersey withholding?"
- "Which states have economic nexus thresholds for corporate income tax and what are the dollar or transaction thresholds?"
- "Does New York's convenience-of-the-employer rule apply to a Connecticut resident who occasionally works from a New York office?"
- "Are there reciprocal withholding agreements between Maryland and Virginia?"

## Limitations

- Nexus Radar does **not** provide tax advice or determinations for specific taxpayer situations. It reports what the law says and cites authority; application to a particular fact pattern remains the practitioner's responsibility.
- Coverage of local taxes (city, county, and special district) is selective. Confirm local-level obligations with the relevant jurisdiction.
- Laws and guidance change frequently. Citation dates are included in every response; verify that the cited authority has not been superseded.

## Related Documents

- [Tax Research Methodology](guide-tax-research-methodology.md) — How to frame nexus and withholding research questions.
- [State Authority Hierarchy](reference-state-authority-hierarchy.md) — Weight and precedence of state-level tax authority.
- [Citation Format Standards](policy-citation-format-standards.md) — House style for citing statutes, regulations, and case law.
