# Document Metadata Template

Copy this metadata header to the top of every finance and accounting procedure, control document, data definition, or guide. Tailor the fields based on document type.

---

## Standard Metadata Header (Use for All Finance Documents)

```
═══════════════════════════════════════════════════════════════════
DOCUMENT METADATA
═══════════════════════════════════════════════════════════════════

IDENTIFICATION
──────────────────────────────────────────────────────────────────
Document Title:              [e.g., GL Reconciliation SOP]
Document ID / Version:       [e.g., AR-001 / v1.2]
Effective Date:              [e.g., 2025-06-01]
Last Updated:                [Date of last revision]
Next Scheduled Review:       [e.g., 2026-06-01]

OWNERSHIP & GOVERNANCE
──────────────────────────────────────────────────────────────────
Document Owner:              [Name, Title, Email]
Owner Contact:               [Phone / Email / Teams]
Finance Manager / Approver:  [Name, Title]
Compliance / Audit Contact:  [Name, Title] (if applicable)

APPROVAL & STATUS
──────────────────────────────────────────────────────────────────
Approval Status:             ☐ Draft  ☐ Approved  ☐ Superseded  ☐ Retired
Approved By:                 [Name + Title]
Approval Date:               [Date]
Effective Date:              [Date this version applies]

SCOPE & AUDIENCE
──────────────────────────────────────────────────────────────────
Purpose (one sentence):      [Why this documentation exists]
Scope:                       [What's included; what's not]
Target Audience:             [e.g., AR staff, audit team, finance managers]
Related Documents:           [Links to SOPs, policies, standards this references]

STORAGE & ACCESS
──────────────────────────────────────────────────────────────────
Storage Location:            [Sharepoint folder, Wiki, URL, or path]
View Access:                 [All finance staff / Select roles / Restricted]
Edit Access:                 [Document owner only / Owner + Manager / Other]
Delete/Archive Access:       [Owner + CFO / Owner only / Other]

COMPLIANCE & RISK
──────────────────────────────────────────────────────────────────
Risk Level:                  ☐ HIGH  ☐ MEDIUM  ☐ LOW
Compliance Drivers:          [Regulations, standards, policies that require this]
Review Cadence:              [Annual / Per process change / Quarterly / Other]
Retention Period:            [e.g., 7 years per SOX; 3 years per policy]

═══════════════════════════════════════════════════════════════════
```

---

## Version History Section (Append to Document)

```
VERSION HISTORY
═══════════════════════════════════════════════════════════════════

| Version | Date       | Changes                          | Author         | Status    |
|---------|------------|----------------------------------|----------------|-----------|
| 1.2     | 2025-08-15 | Clarified Step 5; updated...    | Jane Smith     | Approved  |
| 1.1     | 2025-06-01 | Minor: Added examples           | Jane Smith     | Approved  |
| 1.0     | 2024-05-01 | Initial version                 | Jane Smith     | Approved  |

═══════════════════════════════════════════════════════════════════
```

---

## For Control Documentation: Additional Metadata

Add these fields if documenting an internal control:

```
CONTROL SPECIFICATION
──────────────────────────────────────────────────────────────────
Control Objective:           [What risk does this control mitigate?]
Control Type:                ☐ Preventive  ☐ Detective  ☐ Both
Control Frequency:           [Daily / Weekly / Monthly / Quarterly / Annual / Continuous]
Key Control (Y/N):           ☐ Yes  ☐ No [Is this control critical to financial reporting?]
Control Owner:               [Name, Title]
Control Performer:           [Role(s) that execute the control]
Evidence Location:           [Where control evidence is stored/logged]
Variance Tolerance:          [What deviations trigger escalation?]
Escalation Authority:        [Who approves variances?]
```

---

## For Data Definitions: Additional Metadata

Add these fields if documenting data or a data field:

```
DATA SPECIFICATION
──────────────────────────────────────────────────────────────────
Data Element / Field Name:   [Technical name + business name]
Description:                 [Business meaning, not technical jargon]
Source System:               [Where the data originates]
Calculation/Formula:         [If derived; include formula]
Data Owner:                  [Who maintains this data?]
Update Frequency:            [Daily / Weekly / Monthly / Real-time / On-demand]
Data Sensitivity:            [Public / Internal / Confidential / Restricted]
Retention Period:            [How long to keep historical data?]
```

---

## Tips

1. **Keep it visible**: Metadata should be the first thing readers see. Use clear formatting (boxes, headings).
2. **Keep it current**: Update effective date and next review date with every version.
3. **Make it scannable**: Use fields, checkboxes, and short answers—not prose.
4. **Link to storage**: Include the actual location URL or path so users know where the authoritative version lives.
5. **Clarify access**: Be explicit about who can view, edit, and delete. Users need to know if they can modify it.
6. **Record approval**: Always capture who approved, when, and any conditions.

---

## Example: Completed GL Reconciliation SOP Header

```
═══════════════════════════════════════════════════════════════════
DOCUMENT METADATA
═══════════════════════════════════════════════════════════════════

IDENTIFICATION
──────────────────────────────────────────────────────────────────
Document Title:              GL Reconciliation SOP
Document ID / Version:       AR-001 / v2.0
Effective Date:              2025-09-01
Last Updated:                2025-08-30
Next Scheduled Review:       2026-09-01

OWNERSHIP & GOVERNANCE
──────────────────────────────────────────────────────────────────
Document Owner:              Jane Smith, AR Manager, jane.smith@company.com
Owner Contact:               jane.smith@company.com / ext. 5551
Finance Manager / Approver:  John Lee, Director of Finance
Compliance / Audit Contact:  Sarah Brown, Internal Audit

APPROVAL & STATUS
──────────────────────────────────────────────────────────────────
Approval Status:             ☒ Approved  ☐ Superseded  ☐ Retired
Approved By:                 Sarah Brown, CFO
Approval Date:               2025-08-30
Effective Date:              2025-09-01

SCOPE & AUDIENCE
──────────────────────────────────────────────────────────────────
Purpose:                     Describe how to reconcile GL accounts to subledgers monthly
Scope:                       Covers reconciliation of AR, AP, payroll, and revenue GL accounts
Target Audience:             AR staff (5 people), AP staff (3 people), Finance team leads
Related Documents:           GL Chart of Accounts SOP (AR-002), Close Calendar (Finance Policy 3.1)

STORAGE & ACCESS
──────────────────────────────────────────────────────────────────
Storage Location:            https://company.sharepoint.com/sites/Finance/SOP/AR-001
View Access:                 All Finance staff
Edit Access:                 Jane Smith (owner) + John Lee (manager)
Delete/Archive Access:       CFO + Finance Controller

COMPLIANCE & RISK
──────────────────────────────────────────────────────────────────
Risk Level:                  ☒ HIGH (SOX key control; reconciliation required for close)
Compliance Drivers:          SOX 404, COSO Internal Control Framework
Review Cadence:              Annual + per process change
Retention Period:            7 years (SOX compliance)

═══════════════════════════════════════════════════════════════════
```

---

**Use this template for every new finance and accounting document. Update metadata with each revision.**
