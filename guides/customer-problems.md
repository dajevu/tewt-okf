---
type: guide
title: "Customer Problems We Solve"
---

# Customer Problems We Solve

## Overview

Remote and hybrid work arrangements have outpaced the tools most companies use to manage them. Employees relocate, travel, or work from new states without anyone in HR or finance knowing — until a tax notice arrives, a payroll error surfaces, or an auditor asks for records that don't exist.

Atteniv exists to close that gap. This guide outlines the three core problems we hear about from every prospect we talk to and explains why existing tools fall short.

---

## 1. Unnoticed Nexus Triggers

When an employee works in a state long enough, that state can claim the employer has established **nexus** — a tax-filing obligation — even if the company has no office, no property, and no other presence there.

The problem is visibility. Most companies don't know where their employees are physically working on any given day, let alone over the course of a quarter. By the time a state sends a nexus notice, the company may already owe months of back taxes, interest, and penalties.

**What this looks like in practice:**

- A software engineer "temporarily" visits family in another state and keeps working. Three months later, that state sends a registration notice.
- A salesperson travels across state lines for client meetings and triggers nexus in states the company never intended to operate in.
- Leadership discovers, during diligence for a funding round or acquisition, that the company has unfiled obligations in five states it didn't know about.

**Why existing tools don't solve it:** HRIS platforms record a *work location* field that is self-reported and rarely updated. VPNs and time-tracking tools capture hours, not geography. Neither flags a threshold — say, 20 working days in a new state — before the problem becomes a liability.

Atteniv tracks actual work locations, applies per-state threshold rules, and alerts the right people *before* a trigger threshold is crossed.

---

## 2. Payroll Withholding Mistakes

State and local tax withholding rules are not uniform. An employee who splits time between two states, or who lives in one state and works in another, may need withholding in **both** — or in one and not the other, depending on reciprocity agreements, convenience-of-the-employer rules, and local tax jurisdictions.

When companies don't have reliable data on where employees physically worked during a pay period, payroll teams are forced to guess or default to whatever the HRIS says. That leads to two costly outcomes:

- **Under-withholding:** The employee owes money at tax time and the company faces questions about why it failed to withhold correctly.
- **Over-withholding:** The company withholds in the wrong jurisdiction, creates refund obligations, and generates unnecessary filings in states where it has no requirement.

**What this looks like in practice:**

- An employee moves across a state line and updates their home address, but nobody changes their work-location code. Payroll keeps withholding in the old state for two quarters.
- A hybrid employee works part of the week in a city with a local income tax. The payroll system doesn't know, so no local tax is withheld — and the company discovers the error during a year-end reconciliation.
- A contractor based in one state takes a two-week working vacation in another state. Nobody adjusts anything, and the company later receives a withholding notice from the second state.

Atteniv provides payroll teams with the per-employee, per-pay-period location data they need to withhold correctly the first time.

---

## 3. Audit Exposure from Untracked Remote Work

State labor and tax agencies are increasing enforcement around remote work compliance. Companies are being asked to produce evidence of where employees worked, for how long, and under what authorization — often retroactively.

Without a system of record, companies cannot answer these questions. The result is **audit exposure**: a regulator asks for documentation that doesn't exist, and the company is left to reconstruct it from Slack messages, expense reports, and calendar invites. That reconstruction is always incomplete, sometimes contradictory, and rarely persuasive to an auditor.

**What this looks like in practice:**

- A state unemployment insurance audit requests proof that an employee was not working in-state during a disputed quarter. The company has no records and must default to the auditor's assumption.
- A Department of Labor inquiry asks whether remote workers in a specific state were paid in accordance with that state's wage-and-hour rules. The company can't confirm where the workers were located during the relevant period.
- A potential acquirer's due-diligence team asks for a remote-work compliance report across all 50 states. The answer is assembled manually over several weeks and still has gaps.

Atteniv maintains a continuous, auditable log of employee work locations — not just self-reported addresses, but verified presence data — so that when an audit or diligence request arrives, the answer is a report, not a fire drill.

---

## How These Problems Connect

These three issues are symptoms of the same root cause: **companies don't have reliable, real-time data about where their employees are actually working.**

A company that solves nexus tracking but not payroll withholding will still issue incorrect paychecks. A company that fixes payroll but doesn't maintain audit-ready records will still fail a compliance review. The problems are interlocking, and they require a single source of truth to resolve them together.

That is what Atteniv provides. For a deeper look at the platform's approach, see our [product overview](product-overview.md). For details on how Atteniv applies state-specific threshold rules, refer to the [nexus rules reference](nexus-rules-reference.md).
