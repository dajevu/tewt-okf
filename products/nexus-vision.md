---
type: reference
title: "Nexus Vision"
---

# Nexus Vision

Nexus Vision is the analytics and dashboarding layer of the Nexus platform. It ingests employee presence data captured by Nexus Pulse and transforms it into actionable nexus-risk visibility for finance and HR stakeholders. Rather than presenting raw attendance logs, Nexus Vision surfaces trends, anomalies, and risk indicators that help organizations anticipate compliance exposure, workforce disruption, and cost impacts before they escalate.

## What Nexus Vision does

Nexus Vision consolidates presence signals—check-ins, location data, shift adherence, and exception events—into a unified risk dashboard. Each data point is evaluated against organizational policies and regulatory thresholds, then rendered as a visual indicator of nexus exposure.

Key functions include:

- **Presence-to-risk mapping.** Translates physical presence patterns into jurisdictional nexus assessments, flagging days, thresholds, and locations that may create tax or compliance obligations.
- **Exception surfacing.** Highlights anomalies such as unexpected presence in a restricted jurisdiction, repeated short-duration visits, or pattern deviations from approved schedules.
- **Trend visualization.** Displays rolling presence histories so teams can see whether risk is increasing, stabilizing, or resolving over time.
- **Role-based views.** Provides distinct dashboards tuned to the priorities of finance, HR, and compliance audiences.

## Dashboard areas

### Finance overview

The finance dashboard focuses on cost and tax exposure. It shows presence days by jurisdiction, highlights threshold approaches, and estimates potential filing or registration obligations. Finance teams use this view to prioritize remediation and forecast compliance spend.

### HR overview

The HR dashboard emphasizes workforce patterns and policy adherence. It surfaces attendance exceptions, shift compliance, and presence concentration by team or location. HR teams use this view to manage scheduling, support employee mobility, and address policy drift before it becomes a risk event.

### Exception monitor

The exception monitor is a shared view for cross-functional triage. It lists open exceptions with severity, affected jurisdiction, and related employee context. Both finance and HR can assign ownership, add notes, and track resolution status from this dashboard.

### Jurisdiction explorer

This view lets users drill into a single jurisdiction to see who was present, when, and under what circumstances. It supports audit readiness by providing a detailed, exportable history of presence events and their nexus implications.

## Data sources

Nexus Vision draws primarily from [Nexus Pulse](../nexus-pulse/nexus-pulse.md), which captures employee presence at the point of activity. It may also incorporate schedule and policy data from integrated HR systems to contextualize exceptions and assess adherence.

## Intended audience

Nexus Vision is designed for:

- **Finance and tax teams** monitoring nexus exposure and compliance costs.
- **HR and people operations teams** managing mobility, scheduling, and policy compliance.
- **Compliance and risk officers** requiring audit-ready visibility into workforce presence.

It is not an employee-facing tool. Individual presence data is presented in aggregate or role-appropriate detail to preserve privacy while still enabling risk analysis.

## Outputs and integrations

Dashboards can be exported as reports for internal review or external audit. Nexus Vision also feeds summarized risk indicators into broader compliance workflows, enabling downstream action in policy management and case resolution tools.

---

For configuration details, dashboard customization, and data retention rules, see the [Nexus Vision administration guide](../nexus-vision-admin-guide/nexus-vision-admin-guide.md).
