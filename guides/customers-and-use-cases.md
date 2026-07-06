---
type: guide
title: "Customers and Use Cases"
---

# Customers and Use Cases

## Who Uses Atteniv

Atteniv serves organizations that need accurate, compliant time and attendance tracking across distributed or complex work environments. While the platform is flexible enough for a wide range of industries, three customer profiles represent the majority of deployments.

---

## Multi-State Employers

Organizations operating across multiple states face a patchwork of labor regulations—meal break rules, overtime thresholds, predictive scheduling mandates, and paid leave accruals that vary by jurisdiction. Manual tracking across these boundaries is error-prone and exposes the business to compliance risk.

### Typical Scenarios

- **Multi-jurisdiction compliance.** A retailer with stores in five states uses Atteniv to apply location-specific break and overtime rules automatically, so managers don't have to memorize each state's requirements. See [Compliance Reference](../reference/compliance.md) for the full rule matrix.
- **Centralized payroll preparation.** A regional healthcare network exports approved time data from Atteniv into its payroll system, reducing manual reconciliation from days to hours.
- **Audit readiness.** HR teams generate on-demand reports showing historical time records, manager edits, and approval trails when regulators or internal auditors request documentation.

### Why Atteniv Fits

Multi-state employers need a system that can hold contradictory rules side by side and apply the correct one based on where an employee is physically working. Atteniv's location-aware rule engine handles this without requiring separate configurations per site.

---

## Mobile Workforces

Field service teams, construction crews, delivery drivers, and traveling sales staff don't sit at a fixed workstation. They clock in from job sites, move between locations throughout the day, and often work in areas with unreliable connectivity.

### Typical Scenarios

- **Geofenced clock-in.** A facilities maintenance company defines geofences around client sites. Technicians can only clock in when they are within the designated area, eliminating off-site time entries.
- **Offline time capture.** Utility workers in remote areas log their hours offline; Atteniv syncs the data automatically once connectivity is restored. Details on offline behavior are in the [Mobile App Guide](./mobile-app-guide.md).
- **Travel time tracking.** A logistics company tracks both driving hours and on-site work hours separately, ensuring accurate pay for each category and simplifying DOT compliance.

### Why Atteniv Fits

Mobile workers need a lightweight app that works anywhere and doesn't require manager intervention for routine connectivity issues. Atteniv's mobile-first design prioritizes fast clock-in, offline resilience, and GPS verification as core features—not add-ons.

---

## Professional Employer Organizations (PEOs)

PEOs manage HR, payroll, and compliance for dozens or hundreds of client companies simultaneously. Each client may have its own pay rules, schedules, and reporting needs, but the PEO needs centralized visibility and consistent processes across its entire book of business.

### Typical Scenarios

- **Multi-tenant configuration.** A PEO onboards a new client company in minutes by cloning a base configuration and adjusting only the client-specific rules—pay periods, overtime calculations, and accrual policies.
- **Consolidated billing.** The PEO pulls aggregated time data across all client companies to generate invoices for time-tracking services based on active employee counts.
- **Client-facing reporting.** Each client company receives a tailored dashboard showing only its own employees, while PEO administrators see a cross-client view. See [Role-Based Access](./role-based-access.md) for how permissions are structured.
- **Payroll export flexibility.** Because PEO clients use different payroll systems, Atteniv supports multiple export formats from a single time-tracking dataset. The [Export Formats Reference](../reference/export-formats.md) lists supported integrations.

### Why Atteniv Fits

PEOs live and die by operational efficiency at scale. A single misconfigured rule replicated across fifty clients becomes a fifty-client problem. Atteniv's tenant isolation, template-based onboarding, and granular permission controls let PEOs serve many clients from one instance without bleed-through between accounts.

---

## Choosing a Deployment Path

If your organization matches one of the profiles above, the recommended starting points are:

| Profile | Recommended Starting Point |
|---|---|
| Multi-state employer | [Initial Setup Guide](./initial-setup.md), then [Compliance Reference](../reference/compliance.md) |
| Mobile workforce | [Mobile App Guide](./mobile-app-guide.md), then [Geofencing Guide](./geofencing.md) |
| PEO | [Multi-Tenant Setup](./multi-tenant-setup.md), then [Role-Based Access](./role-based-access.md) |

For organizations that don't fit neatly into one of these profiles—for example, a single-site manufacturer or a fully remote software company—Atteniv can still be configured to meet your needs. Contact your implementation partner to map your requirements to the platform's capabilities.
